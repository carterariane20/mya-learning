# Mya English

App macOS cho bé 4 tuổi học tiếng Anh bằng giọng nói với hươu Mya. Repo này chỉ chứa bản cài (`.dmg`) và các buổi học; mã nguồn không công khai.

- Tải `Mya-English-<bản>.dmg` ở mục [Releases](../../releases), kéo Mya English vào Applications rồi mở. Lần đầu macOS có thể báo app của nhà phát triển không xác định (app chưa notarize); bỏ cảnh báo bằng một trong hai cách:
  - Chuột phải vào app, chọn Mở, rồi Mở lần nữa; hoặc System Settings → Privacy & Security → Open Anyway.
  - Hoặc chạy trong Terminal:
    ```bash
    xattr -dr com.apple.quarantine "/Applications/Mya English.app"
    ```
  Hồ sơ của bé và API key được lưu trong chính app, xoá app là mất hết.
- `latest.json`: bản mới nhất của app và danh sách bài (kèm sha256) để app tự kiểm tra và tải.
