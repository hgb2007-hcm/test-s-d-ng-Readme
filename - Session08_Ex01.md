# Xử lý xung đột tài liệu trên GitHub
## Phần 1 
Hai sai lầm chính trong tư duy của Nam:

Sai lầm về quản lý phiên bản (Git): Nam nghĩ file Word tốt cho làm việc nhóm. Thực tế, file Word (.docx) là định dạng nhị phân (Rich Text) chứa nhiều mã ẩn phức tạp. Git không thể so sánh chi tiết từng dòng thay đổi (Git Diff) mà chỉ thấy là một cục dữ liệu lớn thay đổi toàn bộ, dẫn đến lỗi xung đột (Conflict) nặng nề khi nhiều người cùng sửa.

Sai lầm về độ an toàn và tính chuyên nghiệp: Nam cho rằng Markdown kém chuyên nghiệp vì chỉ là văn bản thô (Plain Text). Thực tế, Markdown cực kỳ gọn nhẹ và hiển thị rất chuyên nghiệp trên GitHub. Về độ an toàn, file Word nếu bị lỗi mạng mất 1 byte dữ liệu có thể hỏng hoàn toàn cả file, trong khi văn bản thô bền vững và an toàn hơn nhiều trước các sự cố truyền tải.

## Phần 2
Phần 2. Hoàn thiện (Chuyển đổi sang Markdown)
Bạn có thể truy cập trang web StackEdit (stackedit.io), dán nội dung từ Word vào và chuyển đổi thành đoạn mã Markdown ngắn gọn như sau:

Markdown
# Giới thiệu Dự án Nhóm PTIT

Dự án này được xây dựng nhằm giải quyết các bài toán thực tế trong học tập.

## 👥 Thành viên nhóm
- Nam (Trưởng nhóm)
- Các thành viên phát triển

## 🚀 Công nghệ sử dụng
- Ngôn ngữ: Python / JavaScript
- Quản lý mã nguồn: Git & GitHub