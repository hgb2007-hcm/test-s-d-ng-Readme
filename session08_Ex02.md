# Kiểm tra tài liệu trước khi xuất bản
## Phần 1. Phân tích các lỗi cú pháp

Trong đoạn mã của bạn sinh viên có 3 lỗi chính khiến giao diện hiển thị lộn xộn:

Lỗi phân cấp tiêu đề (Heading Logic & Syntax):

Tiêu đề nhảy vọt từ # Tiêu đề 1 (H1) xuống thẳng ### Giới thiệu dự án (H3) mà bỏ qua H2. Điều này làm vỡ cấu trúc phân cấp chuẩn của tài liệu.

Bẫy: Một file Markdown chuẩn chỉ nên có 1 tiêu đề H1 duy nhất làm tên bài/dự án.

Lỗi chèn hình ảnh (Image Syntax):

Cú pháp [Logo PTIT] ([https://ptit.edu.vn/logo.png](https://ptit.edu.vn/logo.png)) bị sai vì có khoảng trắng giữa dấu ] và (.

Ngoài ra, đây là cú pháp của Đường dẫn (Link) chứ không phải Hình ảnh (Image). Muốn hiển thị ảnh trực tiếp, phải có dấu chấm than ! ở phía trước.

Lỗi định dạng chữ in đậm (Emphasis Syntax):

Đoạn văn bản chỉ viết chữ thuần túy mà không dùng cú pháp in đậm của Markdown (**văn bản** hoặc __văn bản__), làm chữ hiển thị dạng thường chứ không nổi bật.

## Phần 2. Mã Markdown chuẩn hoàn thiện
# Quản lý Dự án Sinh viên PTIT

![Logo PTIT](https://tse1.mm.bing.net/th/id/OIP.-WoPNI1phj7xnJPVbJsrQwHaIA?r=0&rs=1&pid=ImgDetMain&o=7&rm=3)

## Giới thiệu dự án

Đây là **đoạn văn bản in đậm** đúng quy tắc.

## Mục tiêu

- Quản lý sinh viên
- Quản lý môn học