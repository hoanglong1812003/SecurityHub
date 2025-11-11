# Bắt đầu với AWS Security Hub

## Giới thiệu

**AWS Security** Hub cung cấp cho bạn cái nhìn toàn diện về các cảnh báo bảo mật ưu tiên cao và trạng thái tuân thủ trên các tài khoản AWS.

## Thông tin Workshop

- **Workshop ID**: `000018`
- **Repository**: `000018-SecurityHub`
- **Source**: https://gitlab.com/awsfirstcloudjourney/000018-SecurityHub.git

## Yêu cầu

- Tài khoản AWS (có thể sử dụng AWS Free Tier)
- Kiến thức cơ bản về AWS
- Trình duyệt web hiện đại

## Nội dung Workshop

Chi tiết nội dung xem trong workshop.

## Cấu trúc Repository

Repository này được xây dựng bằng Hugo framework:

```
.
├── content/          # Nội dung workshop (Markdown)
├── static/           # Tài nguyên tĩnh (hình ảnh, CSS, JS)
├── layouts/          # Template Hugo
└── config.toml       # Cấu hình Hugo
```

## Xem Workshop

### Cách 1: Xem trực tiếp (nếu đã deploy)

Truy cập vào website workshop (nếu có).

### Cách 2: Chạy local với Hugo

1. Clone repository:
```bash
git clone https://gitlab.com/awsfirstcloudjourney/000018-SecurityHub.git
cd 000018-SecurityHub
```

2. Cài đặt Hugo (nếu chưa có):
```bash
# macOS
brew install hugo

# Ubuntu/Debian
sudo apt-get install hugo

# Windows
choco install hugo
```

3. Chạy Hugo server:
```bash
hugo server -D
```

4. Mở trình duyệt và truy cập `http://localhost:1313`

## Đóng góp

Nếu bạn tìm thấy lỗi hoặc muốn cải thiện workshop, vui lòng:

1. Fork repository
2. Tạo branch mới (`git checkout -b feature/improvement`)
3. Commit thay đổi (`git commit -am 'Add new feature'`)
4. Push lên branch (`git push origin feature/improvement`)
5. Tạo Pull Request

## Giấy phép

Workshop này được phát triển bởi AWS First Cloud Journey.

## Liên hệ

- Website: [AWS First Cloud Journey](https://awsfirstcloudjourney.com)
- GitLab: [awsfirstcloudjourney](https://gitlab.com/awsfirstcloudjourney)

---

**Lưu ý**: Workshop này được tạo ra cho mục đích học tập và thực hành. Hãy đảm bảo xóa các tài nguyên AWS sau khi hoàn thành để tránh phát sinh chi phí không mong muốn.
