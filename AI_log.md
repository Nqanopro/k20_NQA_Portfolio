không hiện ảnh
không đúng đường dẫn

## Báo lỗi - 30/10/2026

- Không phát hiện lỗi cú pháp HTML/CSS bằng công cụ kiểm tra của VS Code.
- Trang trong thư mục `K20_Portfolio_CNTT20-04_NQA` trỏ CSS tới `css/style.css`, nhưng tệp CSS thực tế nằm ở thư mục cha: `../css/style.css`.
- Ảnh minh chứng nằm trong thư mục cha `../ảnh minh chứng/`, gồm `anh2.png`, `anh3.png` và `Untitled.png`. Khi dùng trang nộp trong thư mục con, phải dùng đường dẫn tương đối đi lên một cấp thay vì đường dẫn trực tiếp trong thư mục con.