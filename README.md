#        Xử lý Log máy chủ dung lượng lớn 
                                                

## Phần 1: Phân tích
Lý do Notepad bị treo ("Not Responding"): Trình soạn thảo giao diện đồ họa (GUI) cố gắng nạp toàn bộ tệp 800MB vào bộ nhớ RAM cùng một lúc, dẫn đến tràn bộ nhớ và treo máy. Cần sử dụng các phương pháp đọc theo luồng (Stream) hoặc phân trang.
Lý do lệnh cat lỗi trên CMD: cat là lệnh của hệ sinh thái Unix/Linux, không tồn tại trong Command Prompt (CMD) truyền thống của Windows.
Lý do lệnh cat chạy được trong PowerShell: Trong PowerShell, cat là một alias (bí danh) tích hợp sẵn trỏ đến lệnh gốc Get-Content.


## Phần 2: Hoàn thiện (Bộ lệnh PowerShell)
- ** Lệnh toàn bộ nội dung tệp (phân trang để tránh tràn RAM):**
```powershell
Get-Content server_log_800MB.log -ReadCount 1000 | More
