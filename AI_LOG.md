sai đường dẫn css
không hiện avatar
không hiện ảnh dự án

Ghi nhận kiểm tra:
- CSS trong index.html đang dùng đường dẫn tuyệt đối trên máy cá nhân (D:\CNTT20-04\portfolio\css\style.css); trên GitHub Pages trình duyệt báo không được phép tải file:///.
- Đường dẫn avatar đang trỏ tới file ở thư mục gốc và trả 404; trong dự án có assets/avatar.svg.
- Trong index.html ở workspace, đường dẫn ba ảnh dự án thiếu thư mục assets/. Trên trang đang chạy, ảnh dự án lại được tải từ assets/ thành công; cần xác nhận bản triển khai khớp với mã nguồn.
- HTTP 304 chỉ cho biết tài nguyên được phục vụ từ cache, không tự nó chứng minh có lỗi.

Hướng sửa tối thiểu đề xuất (chưa áp dụng vào mã nguồn):
- Đổi CSS thành css/style.css.
- Đổi avatar thành assets/avatar.svg.
- Đổi ba ảnh dự án thành assets/du-an-1.svg, assets/du-an-2.svg và assets/du-an-3.svg.
- Sau khi áp dụng và triển khai, kiểm tra URL/status từng tài nguyên trong Network và đối chiếu mã nguồn đã deploy; chưa kết luận lỗi đã được sửa.