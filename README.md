# UnlockCore — tải ứng dụng Windows

**[Tải UnlockCore cho Windows x64](https://github.com/kiyotec/unlockcore-downloads/releases/latest/download/UnlockCore-Windows-x64.zip)**

1. Tải ZIP và giải nén toàn bộ vào một thư mục.
2. Mở **UnlockCore.exe**. Không cần đăng nhập hay chạy server. Gói đã kèm .NET runtime.
3. Nếu máy báo thiếu WebView2, chạy **MicrosoftEdgeWebview2Setup.exe** trong gói rồi mở lại app. Bộ cài này do Microsoft ký và cần kết nối mạng.
4. Cài Steam, vào **Thêm game**, tìm tên/AppID/link Steam rồi thêm vào thư viện máy này.

Thư viện lưu tại `%LOCALAPPDATA%\UnlockCore\local-library.json`, vẫn còn khi mở lại app. Máy khác có thư viện riêng. Giữ thư mục dữ liệu khi cập nhật app; sao lưu riêng nếu cần.

Danh mục nhúng có thể tìm offline; cập nhật danh mục, tải ảnh/metadata và dùng Steam cần mạng. OnlineFix/Denuvo chưa triển khai. Bản ghi danh mục không bảo đảm mọi game đều cài/chơi được.

Trang này chỉ phân phối bản biên dịch và hướng dẫn. Source project nằm trong repo private riêng. Các file “Source code” tự sinh của GitHub tại đây chỉ chứa nội dung trang hướng dẫn này. EXE chưa ký mã; phần mềm biên dịch vẫn có thể bị phân tích ngược.

Xem checksum SHA-256 và ghi chú trong [Releases](https://github.com/kiyotec/unlockcore-downloads/releases).
