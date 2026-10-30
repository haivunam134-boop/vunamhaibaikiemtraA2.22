# Portfolio CV - Vũ Nam Hải

Trang portfolio cá nhân giới thiệu tác giả, kỹ năng, dự án, quá trình học tập
và thông tin liên hệ. Sản phẩm là website tĩnh được xây dựng bằng HTML và CSS.

## Liên kết

- **Tác giả:** [Vũ Nam Hải](https://github.com/vanhkazen)
- **Hồ sơ GitHub:** https://github.com/vanhkazen
- **Mã nguồn:** https://github.com/haivunam134-boop/vunamhaibaikiemtraA2.22
- **Trang GitHub Pages:** https://haivunam134-boop.github.io/vunamhaibaikiemtraA2.22/
- **Trang kết quả form:** https://haivunam134-boop.github.io/vunamhaibaikiemtraA2.22/ket-qua.html

## Cấu trúc dự án

```text
.
├── index.html       # Portfolio và form liên hệ
├── ket-qua.html     # Trang kết quả sau khi gửi form
├── css/
│   └── style.css    # Giao diện và responsive
├── assets/
│   ├── avatar.svg
│   ├── du-an-1.svg
│   ├── du-an-2.svg
│   ├── du-an-3.svg
│   └── ronaldo-qua-bong-vang-vi-dai-nhat-moi-thoi-dai (1).webp
├── AI_LOG.md        # Nhật ký sử dụng AI và quyết định
└── RELEASE_NOTES.md # Ghi chú bàn giao phiên bản v7
```

## Chạy trên máy cá nhân

Đây là website tĩnh, không cần cài thư viện hay biên dịch.

1. Tải hoặc clone repository về máy.
2. Mở thư mục dự án bằng VS Code.
3. Mở `index.html` trong trình duyệt. Nếu muốn chạy qua máy chủ local, mở
   terminal tại thư mục dự án và chạy:

   ```bash
   python -m http.server 8000
   ```

4. Truy cập http://localhost:8000. Dừng máy chủ bằng `Ctrl+C`.

## Nguồn xuất bản

Website được xuất bản bằng GitHub Pages từ repository ở trên. Đây là dự án HTML
tĩnh; không có bước build. Mã nguồn hiện nằm ở nhánh `main`. Có thể xem hoặc
điều chỉnh nguồn xuất bản trong **Settings → Pages** của repository.

## Cách kiểm tra

1. Mở trang chủ và kiểm tra phần **Giới thiệu**, **Kỹ năng**, **Dự án**,
   **Học tập** và **Liên hệ**. Các mục trên thanh điều hướng đưa tới từng phần
   tương ứng.
2. Kiểm tra ảnh đại diện và ba ảnh minh họa dự án hiển thị; thu nhỏ cửa sổ hoặc
   mở trên điện thoại để xem bố cục responsive.
3. Trong form liên hệ, thử gửi form trống hoặc email sai định dạng để thấy kiểm
   tra dữ liệu HTML5. Sau đó nhập họ tên, email hợp lệ và lời nhắn từ 10 đến
   500 ký tự rồi gửi để mở `ket-qua.html`.
4. Form chỉ phục vụ thực hành: dữ liệu được gửi bằng phương thức GET và có thể
   xuất hiện trên URL; form không gửi email và không lưu dữ liệu lên máy chủ.
   Không nhập thông tin nhạy cảm khi thử.

## Mã nguồn và minh chứng

- [Mã nguồn trang portfolio (`index.html`)](https://github.com/haivunam134-boop/vunamhaibaikiemtraA2.22/blob/main/index.html)
- [Mã nguồn trang kết quả (`ket-qua.html`)](https://github.com/haivunam134-boop/vunamhaibaikiemtraA2.22/blob/main/ket-qua.html)
- [Trang portfolio đã xuất bản](https://haivunam134-boop.github.io/vunamhaibaikiemtraA2.22/)
- [Trang kết quả đã xuất bản](https://haivunam134-boop.github.io/vunamhaibaikiemtraA2.22/ket-qua.html)
- [Ghi chú kiểm tra trong repository (`AI_LOG.md`)](https://github.com/haivunam134-boop/vunamhaibaikiemtraA2.22/blob/main/AI_LOG.md)
- [Release notes bàn giao v7 (`RELEASE_NOTES.md`)](https://github.com/haivunam134-boop/vunamhaibaikiemtraA2.22/blob/main/RELEASE_NOTES.md)
