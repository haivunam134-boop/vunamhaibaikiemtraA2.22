# Release notes - Portfolio CV Vũ Nam Hải v7

- **Phiên bản:** v7
- **Ngày cập nhật:** 2026-10-30
- **Tác giả:** Vũ Nam Hải
- **Sản phẩm:** Portfolio CV tĩnh, xây dựng bằng HTML và CSS
- **Trang đã xuất bản:** https://haivunam134-boop.github.io/vunamhaibaikiemtraA2.22/
- **Kho mã nguồn:** https://github.com/haivunam134-boop/vunamhaibaikiemtraA2.22

## Thay đổi chính

- Hoàn thiện README với cấu trúc dự án, cách chạy local, nguồn GitHub Pages,
  hướng dẫn kiểm tra nội dung và form, cùng liên kết hồ sơ và minh chứng.
- Viết lại `AI_LOG.md` để ghi dữ kiện, gợi ý AI, quyết định, thay đổi và những
  bước kiểm tra chưa thực hiện.
- Bổ sung ghi chú bàn giao này. Các thay đổi trong đợt bàn giao hiện tại là tài
  liệu; không thay đổi HTML/CSS của website.

## Lỗi đã sửa và xác minh

- Làm rõ trong tài liệu rằng các ghi nhận lỗi đường dẫn trong ghi chú cũ chưa
  chứng minh lỗi còn tồn tại. Mã `index.html` hiện dùng `css/style.css` và các
  ảnh trong `assets/`; chưa có thay đổi mã giao diện để tuyên bố đã sửa lỗi ảnh
  hoặc CSS.
- `git diff --check` không báo lỗi. Đã mở URL GitHub Pages của trang chủ, trang
  kết quả form và kiểm tra URL hồ sơ GitHub. Chưa kiểm tra trực quan từng ảnh/
  kích thước màn hình và chưa gửi thử form.

## Commit và bản mã bàn giao

- **Commit mã nguồn đã có:** [`96aa479`](https://github.com/haivunam134-boop/vunamhaibaikiemtraA2.22/commit/96aa47952010f1efec0c7af9206cedeeaea5d1df)
  (`Add files via upload`), trên nhánh `main`.
- **Lưu ý:** README, AI_LOG và release notes v7 là các thay đổi trong working
  tree chưa được commit. Vì vậy commit trên là nền mã website, chưa chứa đầy đủ
  bộ tài liệu bàn giao v7. Sau khi commit các tài liệu, cập nhật liên kết này
  tới commit mới để trỏ chính xác bản nộp hoàn chỉnh.
- Có thể mở [mã nguồn tại commit nền](https://github.com/haivunam134-boop/vunamhaibaikiemtraA2.22/tree/96aa47952010f1efec0c7af9206cedeeaea5d1df)
  hoặc [trang GitHub Pages](https://haivunam134-boop.github.io/vunamhaibaikiemtraA2.22/).

## Hạn chế còn lại

- Form liên hệ chỉ kiểm tra dữ liệu HTML5 rồi chuyển bằng GET tới trang kết
  quả; không gửi email và không lưu dữ liệu. Dữ liệu nhập có thể xuất hiện
  trong URL.
- Ba dự án trong portfolio còn hiển thị liên kết GitHub mẫu `tranvietanh` được
  đánh dấu cần cập nhật.
- Chưa có kiểm thử tự động hoặc xác minh trực quan responsive trong đợt bàn
  giao này.

## Tiếp tục kiểm tra và bàn giao

1. Chạy local theo hướng dẫn trong [README](./README.md); kiểm tra menu, CSS,
   ảnh, bố cục responsive và luồng form với dữ liệu thử không nhạy cảm.
2. Đối chiếu kết quả local với [bản GitHub Pages](https://haivunam134-boop.github.io/vunamhaibaikiemtraA2.22/).
3. Cập nhật các liên kết dự án mẫu nếu đã có URL thật.
4. Commit bộ tài liệu bàn giao v7, rồi thay liên kết commit nền ở trên bằng
   permalink của commit chứa đầy đủ các tệp được nộp.
