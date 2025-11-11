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


## 🚀 Hướng Phát Triển

### Các Bước Tiếp Theo

Sau khi hoàn thành workshop này, bạn có thể:

- Implement Zero Trust security model
- Set up Security Hub cho centralized monitoring
- Configure automated compliance checking
- Implement least privilege access
- Set up incident response procedures

### Dịch Vụ Liên Quan

Khám phá các dịch vụ AWS có thể tích hợp:

- **CloudTrail**: Tích hợp để mở rộng chức năng
- **Config**: Tích hợp để mở rộng chức năng
- **Inspector**: Tích hợp để mở rộng chức năng

### Best Practices

- Enable MFA cho tất cả users
- Use IAM Roles instead of access keys
- Regular security audits
- Implement proper logging và monitoring
- Regular credential rotation

### Lộ Trình Học Tập

#### Beginner → Intermediate
1. Hoàn thành workshop cơ bản
2. Thực hành với real-world scenarios
3. Tối ưu hóa và refactor solution

#### Intermediate → Advanced
1. Implement advanced features
2. Performance tuning và optimization
3. Security hardening
4. Production deployment

#### Advanced
1. Multi-region deployment
2. Disaster recovery planning
3. Cost optimization strategies
4. Compliance và governance

### Tài Nguyên Học Tập

- [AWS Documentation](https://docs.aws.amazon.com/)
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- [AWS Workshops](https://workshops.aws/)
- [AWS Skill Builder](https://skillbuilder.aws/)
- [AWS Blog](https://aws.amazon.com/blogs/)

### Chứng Chỉ Liên Quan

- AWS Certified Security - Specialty
- AWS Certified Solutions Architect - Professional

### Community & Support

- [AWS First Cloud Journey Community](https://awsfirstcloudjourney.com)
- [AWS User Groups Vietnam](https://www.meetup.com/pro/aws-user-groups-vietnam/)
- [AWS Support](https://aws.amazon.com/premiumsupport/)
- [Stack Overflow - AWS](https://stackoverflow.com/questions/tagged/amazon-web-services)


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
