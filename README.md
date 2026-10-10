# Thực hành: Tạo menu dọc bằng CSS

Bài thực hành CodeGym **Tạo menu dọc**: menu `ACCP i10` với bốn học kỳ, trong đó `Sem 1` và `Sem 2` có menu con hiển thị bên phải khi đưa chuột vào.

## Nội dung

- `index.html`: cấu trúc HTML với danh sách `ul` / `li` lồng nhau, các mục `Sem 1` – `Sem 4`.
- `styles.css`: định dạng menu nền đen, chữ trắng, đổi nền đỏ khi hover; submenu dùng `position: absolute`, `visibility`.
- `images/menu-mac-dinh.png`: ảnh khi chưa rê chuột.
- `images/menu-hover-sem1.png`: ảnh submenu Sem 1 khi rê chuột.
- `images/menu-hover-sem2.png`: ảnh submenu Sem 2 khi rê chuột.

## Chạy bài

Mở file `index.html` bằng Chrome/Edge. Di chuột lần lượt vào **Sem 1** và **Sem 2** để xem menu con. Cũng có thể dùng phím Tab để hiện menu con khi liên kết được focus.

## CSS chính

- Reset `margin`, `padding` cho menu, danh sách và phần tử danh sách.
- `list-style: none` loại bỏ dấu đầu dòng.
- `#menu li:hover` đổi màu nền đỏ.
- `#menu ul ul` đặt danh sách con ở phía phải (`top: 0`, `left: 140px`) và ẩn mặc định.
- `#menu ul li:hover > ul` hiển thị danh sách con tương ứng.

## Nộp CodeGym

Tạo một repository GitHub **riêng**, ở chế độ **Public** (ví dụ `tao-menu-doc-css`). Upload trực tiếp `index.html`, `styles.css`, `README.md` và thư mục `images`. Mở `index.html` và `styles.css` trên GitHub để chắc chắn có thể đọc được mã nguồn, sau đó dán URL repository vào CodeGym.

Ảnh trong `images/` được chụp từ trang web chạy cục bộ bằng trình duyệt Chromium.
