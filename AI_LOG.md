# Nhật ký sử dụng AI

## Vấn đề và dữ kiện ban đầu

- Ghi chú ban đầu nêu hiện tượng CSS, ảnh đại diện và ảnh dự án không hiển thị;
  đồng thời đề xuất thay các đường dẫn trong `index.html`. Ghi chú đó chưa xác
  nhận các đề xuất đã được áp dụng.
- Khi kiểm tra mã nguồn hiện tại, `index.html` dùng `css/style.css`, ảnh đại
  diện trong `assets/` và ba ảnh dự án trong `assets/`. Các đường dẫn này khớp
  với cấu trúc tệp trong repository. Ảnh đại diện hiện dùng là tệp WebP, không
  phải `avatar.svg`.
- Repository có trang portfolio và trang kết quả form. Form dùng GET tới
  `ket-qua.html`; trang kết quả nêu rõ không gửi email và không lưu dữ liệu.

## AI được dùng và gợi ý

- **Công cụ:** AI assistant trong VS Code.
- **Yêu cầu/prompt:** Đối chiếu README với sản phẩm thực tế và ghi thông tin
  để người khác mở, chạy, kiểm tra trang cùng các chức năng chính.
- **Gợi ý/đầu ra liên quan:** Xác nhận URL GitHub Pages và hồ sơ tác giả; mô tả
  cấu trúc website tĩnh, cách chạy local, các phần cần kiểm tra và giới hạn
  của form. AI cũng đề xuất các đường dẫn trong ghi chú cũ; đó là đề xuất từ
  ghi nhận ban đầu, không phải thay đổi đã thực hiện trong lượt này.

## Quyết định và phần đã sửa

- Đối chiếu các gợi ý với mã nguồn trước khi ghi tài liệu. Vì các đường dẫn CSS
  và ảnh trong mã nguồn hiện tại đã khớp với tệp trong repository, không sửa
  `index.html` và không đổi ảnh đại diện sang `avatar.svg`.
- Cập nhật `README.md` để mô tả hai trang, cách chạy website tĩnh, cách thử
  điều hướng và kiểm tra form; ghi rõ dữ liệu GET có thể hiện trên URL và không
  được gửi/lưu trên máy chủ.
- Giữ tên nhật ký thống nhất là `AI_LOG.md`; liên kết trong README dùng đúng
  tên này.

## Cách thử lại và kết quả đã xác nhận

- `git diff --check`: hoàn tất, không báo lỗi định dạng diff.
- Mở URL GitHub Pages của trang chủ và `ket-qua.html`: cả hai trả nội dung
  trang tương ứng khi được kiểm tra.
- Mở hồ sơ GitHub `vanhkazen`: API GitHub trả đúng URL hồ sơ.
- Chưa thực hiện kiểm tra trực quan trên trình duyệt cho từng ảnh/responsive;
  chưa gửi thử form. Vì vậy nhật ký không kết luận các bước đó đã được kiểm
  chứng.
