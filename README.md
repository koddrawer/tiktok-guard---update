# tiktok-guard---update

Kho chứa bản cập nhật nóng cho TikTok Guard.

- `latest.json`: thông tin bản mới nhất (version, sha256, link zip).
- `TikTokGuard_<version>.zip`: gói cài đặt đầy đủ.

## Link cập nhật cho app

Dán vào ô "Link cập nhật" trong TikTok Guard (hoặc `update_url` trong `config.json`):

```
https://raw.githubusercontent.com/koddrawer/tiktok-guard---update/main/latest.json
```

Mỗi lần ra bản mới: đưa zip mới + `latest.json` mới lên nhánh `main`, các máy sẽ tự cập nhật.
