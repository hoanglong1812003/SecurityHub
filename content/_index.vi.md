+++
title = "Bắt đầu với AWS Security Hub"
weight = 1
chapter = false
+++

# Bắt đầu với AWS Security Hub

#### Tổng quan

**AWS Security** Hub cung cấp cho bạn cái nhìn toàn diện về các cảnh báo bảo mật ưu tiên cao và trạng thái tuân thủ trên các tài khoản AWS.

Sẽ có rất nhiều các công cụ bảo mật mạnh mẽ để bạn sử dụng, từ tường lửa hay ứng dụng bảo vệ endpoint đến các ứng dụng quét lỗ hổng và sự tuân thủ bảo mật. Nhưng đôi khi, điều này khiến đội ngũ của bạn phải chuyển đổi qua lại giữa các công cụ này để đối phó với hàng trăm, hàng nghìn cảnh báo bảo mật mỗi ngày. Với Security Hub, giờ đây bạn có một nơi tổng hợp duy nhất, sắp xếp và phân độ ưu tiên các cảnh báo hoặc phát hiện bảo mật từ nhiều dịch vụ AWS (như Amazon GuardDuty, Amazon Inspector và Amazon Macie) hay từ các giải pháp cung cấp bởi đối tác của AWS.

Các rủi ro được tìm thấy sẽ được tóm tắt trực quan trên trang tổng quan tích hợp với các biểu đồ và bảng mà bạn có thể tương tác. Bạn cũng có thể giám sát hệ thống của bạn liên tục bằng cách sử dụng chức năng kiểm tra tự động sự tuân thủ so với các thực nghiệm tối ưu từ AWS và các tiêu chuẩn trên thị trường mà doanh nghiệp của bạn đang tuân theo.

![Security Hub](/images/serviceicon.png?featherlight=false&width=10pc)

#### Chi phí

Thông thường, chi phí sẽ ít hơn $1 mỗi tháng nếu tài khoản của bạn chỉ sử dụng cho mục đích thử nghiệm, luyện tập và không thực hiện những cuộc tấn công giả lập.  

**Bảng giá AWS Security Hub:**

| Nội dung                    | Chi phí                               | 
|---------------------------- | ----------------                      |
| **Kiểm tra bảo mật**        | 100,000 lần đầu tiên => $0.0010/check |
|                             | 100,001 – 500,000 => $0.0008/check    |
|                             | 500,001+ => $0.0005/check             |
| **Tìm các sự kiện tấn công**| 10,000 lần đầu tiên => miễn phí       | 
|                             | 10,001+ => $0.00003/lần               |

#### Nội dung

1. [Các tiêu chuẩn bảo mật](1-security-standards/)
2. [Kích hoạt Security Hub trên Console](2-enable-sec-hub/)
3. [Kiểm tra điểm đánh giá theo tiêu chuẩn](3-security-score/)
