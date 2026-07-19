# Đăng nhập Kiro IDE bằng JSON

Công cụ nhỏ giúp người dùng nạp file token JSON vào Kiro IDE. Người dùng không cần cài Python, không cần mở terminal.

## Tải nhanh

Bấm vào đây để tải file chạy:

[Tải KiroJsonIdeLogin.exe](https://github.com/mucphekr/kirologin/raw/main/KiroJsonIdeLogin.exe)

Thông tin bản hiện tại:

- Tên file: `KiroJsonIdeLogin.exe`
- Dung lượng: khoảng `13.5 MB`
- SHA256: `AE0038114F4EFDD16E0D4A2224F4E8EFD8300556AA21330E6B0FE6174308C942`

## Cách sử dụng

1. Tải `KiroJsonIdeLogin.exe` về máy.
2. Đóng Kiro IDE nếu đang mở.
3. Mở `KiroJsonIdeLogin.exe`.
4. Nếu Windows hiện cảnh báo SmartScreen, chọn `More info` rồi `Run anyway`.
5. Bấm `Hướng dẫn sử dụng` trong app nếu dùng lần đầu.
6. Bấm `Nạp từ file .json` và chọn file token được cung cấp.
7. Giữ bật tùy chọn `Làm mới token`.
8. Bấm `Đăng nhập Kiro IDE`.
9. Nếu app báo Kiro IDE đang mở, chọn `Yes` để tool đóng Kiro IDE tự động.
10. Khi app báo hoàn tất, mở lại Kiro IDE.

## Lưu ý quan trọng

- Không cần đăng xuất tài khoản cũ trong Kiro IDE, nhưng nên đóng hẳn Kiro IDE trước khi đăng nhập bằng tool.
- Nếu Kiro IDE vẫn hiện tài khoản cũ, hãy thoát hẳn Kiro IDE trong Task Manager rồi mở lại.
- Nếu Kiro IDE vẫn hiện màn `Sign in to view your account`, hãy đóng toàn bộ process `Kiro.exe`, chạy lại tool, rồi mở lại Kiro IDE.
- Bản mới có nút `Đóng Kiro IDE` để đóng nhanh trước khi đăng nhập.
- File JSON có `refresh_token`, cần xem như mật khẩu đăng nhập.
- Không gửi file JSON cho người khác và không upload file JSON lên GitHub.
- Repo này chỉ chứa tool `.exe`, không chứa token của bất kỳ tài khoản nào.

## Yêu cầu

- Windows 10/11.
- Máy đã cài Kiro IDE.
- Có kết nối internet nếu token cần được làm mới.

## Cập nhật phiên bản mới

Khi có bản exe mới, chỉ cần thay file `KiroJsonIdeLogin.exe` trong repo và cập nhật lại mã SHA256 trong README.
