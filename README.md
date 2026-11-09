# Android Click – bản phát hành

Nơi đăng file APK của **Android Click**, app autoclick riêng tư cho Android của [congnghe.id.vn](https://congnghe.id.vn). Repo này chỉ chứa bản phát hành, không có mã nguồn.

## Tải về

**[Tải bản mới nhất (androidclick.apk)](https://github.com/trunghuynhvan0310/androidclick-releases/releases/latest/download/androidclick.apk)**

Các bản cũ và mã SHA-256 của từng bản nằm ở mục [Releases](https://github.com/trunghuynhvan0310/androidclick-releases/releases).

Kiểm tra file không bị đổi: trên Windows chạy `certutil -hashfile androidclick.apk SHA256`, trên Linux/macOS chạy `sha256sum androidclick.apk`, rồi so với mã ghi trong ghi chú của bản phát hành.

## Yêu cầu

Android 8.0 trở lên. Tính năng cấp quyền ngay trên điện thoại (tùy chọn, thử nghiệm) cần Android 11 trở lên.

## Cài đặt

1. Tải APK và mở. Cho phép cài từ nguồn không rõ nếu máy hỏi. Google Play Protect có thể cảnh báo vì app không cài từ Google Play; chọn **Cài đặt dù sao**.
2. Mở app → **Mở cài đặt Trợ năng** → bật dịch vụ **Android Click**.
3. Android 13 trở lên: nếu nút bật bị mờ, vào *Cài đặt → Ứng dụng → Android Click → ⋮ → Cho phép cài đặt bị hạn chế*, rồi bật lại.
4. Xiaomi, Oppo, Vivo…: cho phép tự khởi động và tắt tối ưu pin cho app.
5. Từ bản phát hành ký bằng khóa cố định này trở đi, các bản mới cài đè lên nhau được. Nếu trước đó bạn cài bản thử nghiệm ký khác khóa, hãy gỡ bản cũ trước (mất cài đặt và bản lưu).

Hướng dẫn dùng chi tiết có ở trang giới thiệu trên [congnghe.id.vn](https://congnghe.id.vn).

## Quyền và riêng tư

- Dịch vụ Trợ năng chỉ dùng để phát cú chạm tại các điểm bạn đặt, không đọc nội dung màn hình.
- Quyền INTERNET chỉ dùng để nối tới chính điện thoại của bạn khi dùng tính năng cấp quyền ADB tùy chọn. App không gửi dữ liệu ra ngoài.
- Không có tài khoản, không quảng cáo, không thống kê.

Chỉ dùng cho mục đích hợp pháp và tuân thủ điều khoản của ứng dụng hoặc trò chơi bạn thao tác.
