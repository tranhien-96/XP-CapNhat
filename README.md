# XP-CapNhat

Kho phát hành và thông báo bản mới cho bộ công cụ XpressTools của tranhien:

- **XP Vật liệu XSMP** (3ds Max + Corona, dùng kèm XSMP)
- **XP Vật liệu Corona** (3ds Max + Corona, không cần XSMP)

## Tải bản mới

Vào mục **[Releases](https://github.com/tranhien-96/XP-CapNhat/releases/latest)**, tải file zip của bộ mình đang dùng, giải nén rồi chạy file cài như hướng dẫn trong file Excel đi kèm. Giấy phép (.lic) đang dùng vẫn dùng tiếp được, không phải xin lại.

## Công cụ tự báo bản mới thế nào

Mỗi ngày, lần đầu mở bảng công cụ, công cụ đọc file `phienban.json` trong kho này. Nếu số phiên bản ở đây lớn hơn bản đang cài, bảng hiện thông báo kèm nút **Tải bản mới**. Không có mạng thì bỏ qua, công cụ vẫn chạy bình thường. Công cụ không gửi thông tin gì của máy lên mạng.

## Phát hành bản mới (dành cho tranhien)

1. Tạo Release mới, tag dạng `xsmp-v2.12.2` hoặc `corona-v1.3.2`, kéo thả file zip vào.
2. Sửa `phienban.json`: đổi `phien_ban`, `ngay`, `noi_dung` của bộ vừa phát hành. Bấm Commit.
3. Trong vòng khoảng 5 phút, máy nào mở công cụ sẽ thấy thông báo.

© tranhien - XpressTools
