# Gỡ Lỗi Trang Hướng Dẫn Nộp Bài Của Giảng Viên 
## Phần 1: Phân tích lỗi
Lỗi ở tiêu đề phụ ###Lưu ý quan trọng:

Lỗi gì: Thiếu khoảng trắng (space) giữa ký tự # và chữ "Lưu ý quan trọng".

Hậu quả khi render: Trình duyệt sẽ không nhận diện đây là tiêu đề (Heading) mà sẽ hiển thị nguyên văn chuỗi ###Lưu ý quan trọng thành một dòng chữ thường bình thường.

Lỗi ở phần danh sách các bước (-Bước 1, -Bước 2,...):

Lỗi gì: Thiếu khoảng trắng sau dấu gạch ngang (-).

Hậu quả khi render: Hệ thống không coi đây là các mục trong danh sách (List), dẫn đến việc danh sách bị mất dấu chấm/gạch đầu dòng, hiển thị dính liền thành chữ thường hoặc văn bản thô.

Lỗi ở định dạng chữ in đậm tên repository (**HNKS25CNTT1_IT101_Session08):

Lỗi gì: Chỉ mở dấu ** ở đầu mà thiếu dấu ** đóng ở cuối câu.

Hậu quả khi render: Toàn bộ văn bản từ chỗ mở thẻ đến hết đoạn hoặc hết dòng sẽ bị ảnh hưởng hiển thị sai, hoặc xuất hiện dấu sao thừa thãi vì thẻ in đậm không được đóng lại đúng cú pháp.

Lỗi ở định dạng câu chứa Deadline và chữ in nghiêng:

Lỗi gì: Thừa dấu sao đóng ** ở cuối câu (- Nộp muộn sẽ bị trừ 50% điểm!**).

Hậu quả khi render: Cú pháp in nghiêng (*Nộp muộn...*) bị lỗi dấu thừa, khiến ký tự * hiển thị thô trên trang web thay vì tạo định dạng chuẩn.

## Phần 2: Sửa lỗi và Trả lời câu hỏi bẫy dữ liệu
 Đoạn Markdown hoàn chỉnh đã sửa đúng cú pháp:
Markdown
## Hướng Dẫn Nộp Bài Tập - Session 08

Các bước nộp bài:
- Bước 1: Tạo tài khoản GitHub tại [GitHub](https://github.com)
- Bước 2: Tạo repository mới đặt tên theo định dạng **HNKS25CNTT1_IT101_Session08**
- Bước 3: Upload file .md của bài làm lên repository
- Bước 4: Copy đường dẫn và nộp lên Portal

> Deadline: Chủ nhật 23:59 — *Nộp muộn sẽ bị trừ 50% điểm!*
 Trả lời bẫy dữ liệu về đường link GitHub:
Nếu sinh viên gõ link mà quên tiền tố https:// (ví dụ chỉ viết github.com), trình duyệt khi render sẽ hiểu đây là một đường dẫn tương đối (relative link) gắn liền với tên miền của trang hiện tại (tức là trang chủ của GitHub Pages đang chạy).

Khi người dùng bấm vào, trình duyệt sẽ lỗi 404 hoặc dẫn sai lệch hoàn toàn đến một địa chỉ không tồn tại bên trong website thay vì chuyển hướng ra trang ngoài github.com.