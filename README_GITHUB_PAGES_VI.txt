MAISON SUCRÉ — GITHUB PAGES

CẤU TRÚC
- index.html: trang web chính (đặt ở thư mục gốc để GitHub Pages dễ triển khai)
- assets/: ảnh và video dùng bởi trang web
- README_VI.txt: ghi chú dự án

CÁCH XUẤT BẢN BẰNG GITHUB PAGES
1. Đăng nhập hoặc tạo tài khoản tại https://github.com/
2. Tạo repository mới, ví dụ: maison-sucre-website
3. Chọn Public. Nếu nộp bài công khai, lưu ý mọi người sẽ xem được mã nguồn trong repository.
4. Tải lên index.html, thư mục assets/ và README_VI.txt ở thư mục gốc của repository (không đặt tất cả bên trong một thư mục con).
5. Mở Settings → Pages.
6. Trong Build and deployment, chọn Deploy from a branch.
7. Chọn branch main và folder /(root), rồi nhấn Save.
8. Đợi GitHub Pages triển khai xong. Link thường có dạng:
   https://TEN-TAI-KHOAN.github.io/maison-sucre-website/
   Thay TEN-TAI-KHOAN và tên repository bằng giá trị thật của bạn.
9. Mở link trên trình duyệt để kiểm tra ảnh, video và các mục điều hướng trước khi nộp.

CÁCH CHỈNH SỬA SAU NÀY
- Mở repository trên GitHub → chọn index.html → biểu tượng bút chì để sửa trực tiếp, hoặc tải file về sửa bằng VS Code rồi upload lại.
- Thay ảnh/video trong assets/ bằng file mới và giữ nguyên tên file nếu không cập nhật đường dẫn trong HTML.
- Mỗi lần commit thay đổi, GitHub Pages sẽ tự cập nhật sau khi build.

LƯU Ý
- Link Pages chỉ có sau khi bạn bật Pages thành công; không dùng link này trước khi kiểm tra.
- Repository Public đồng nghĩa mã nguồn được công khai. Link website là link để người chấm xem giao diện; link repository là link để xem/chỉnh sửa mã nguồn.
- Đây là website tĩnh HTML/CSS/JS; không cần build command.
