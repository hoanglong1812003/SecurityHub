+++
title = "Kích hoạt Security Hub"
weight = 2
chapter = false
pre = "<b>2. </b>"
+++

#### Tổng quan

Để kích hoạt Security Hub, AWS có cung cấp cho người dùng một giao diện hình ảnh để tương tác với dịch vụ này. Ở bước này, chúng ta sẽ kích hoạt Security Hub thông qua giao diện console này.

#### Kích hoạt Security Hub thông qua console

Để kích hoạt Security Hub trên một Region, bạn hãy làm theo các bước sau đây:

1. Đăng nhập vào **Amazon Management Console**. Trên thanh tìm kiếm, nhập và tìm kiếm dịch vụ **Security Hub CSPM**.
2. Ở trang **AWS Security Hub**, chọn **Go to Security Hub CSPM**.

![Security Hub](/images/updateimage/1.png)


![Security Hub](/images/updateimage/2.png)

3. Trên trang **Welcome to AWS Security Hub**, chọn các tiêu chuẩn về bảo mật (**Security standards**) như là **AWS Foundational Security Best Practices**, **CIS AWS Foundations Benchmark**, và **PCI DSS**.
4. Chọn **Enable Security Hub**.

![Security Hub](/images/updateimage/3.png)

5. Sau khi kích hoạt, bạn sẽ cần chờ một khoản thời gian để Security Hub đánh giá **Security Score** của tài khoản hiện tại của bạn so với từng bộ tiêu chuẩn bảo mật mà bạn thiết lập.

![Security Hub](/images/image-ws00018/12.png)

6. Chọn vào mục **Control** để xem **Security Score**

![Security Hub](/images/image-ws00018/13.png)



{{% notice warning %}}
Một số trường hợp bạn sẽ gặp thông báo liên quan đến về việc cấu hình **AWS Config**, hãy bật dịch vụ AWS Config tại Region tương ứng. Hầu hết các tiêu chí đánh giá dựa trên các service-level rule của AWS Config. Khi kích hoạt tính năng ghi nhận của AWS Config, hãy chọn phương án ghi nhận tất cả các tài nguyên trên Region tương ứng và các tài nguyên dạng global.
{{% /notice %}}

#### Cấu hình AWS Config
1. Ở trang console, tìm kiếm và chọn dịch vụ **AWS Config**

![Security Hub](/images/image-ws00018/1.png)

2. Chọn **Get started**

![Security Hub](/images/image-ws00018/2.png)

3. Ở phần **Resource type**, chọn **"All globally recorded IAM..."**. Ở phần **Override**, chọn **Exclude from recording**

![Security Hub](/images/image-ws00018/3.png)

4. Ở phần **Data governance**, chọn **Use an existing AWS Config service-linked role** 

![Security Hub](/images/image-ws00018/4.png)

5. Ở phần **Delivery channel**, chọn **Create a bucket**, giữ nguyên **bucket name**, chọn **Next**

![Security Hub](/images/image-ws00018/5.png)

6. Tiếp tục chọn **Next**

![Security Hub](/images/image-ws00018/6.png)

7. Chọn **Confirm**

![Security Hub](/images/image-ws00018/7.png)

8. Hoàn tất thiết lập **AWS Config**

![Security Hub](/images/image-ws00018/8.png)
