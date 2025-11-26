+++
title = "Enable Security Hub"
weight = 2
chapter = false
pre = "<b>2. </b>"
+++

#### Overview

To enable Security Hub, AWS provides users with a graphical interface to interact with this service. In this step, we will activate Security Hub through the AWS console.

#### Enable Security Hub via Console

To enable Security Hub in a Region, follow these steps:

1. Log in to the **Amazon Management Console**. In the search bar, type and find the **Security Hub CSPM** service.
2. On the **AWS Security Hub** page, select **Go to Security Hub CSPM**.

![Security Hub](/images/image-ws00018/9.png)

![Security Hub](/images/image-ws00018/10.png)

3. On the **Welcome to AWS Security Hub** page, choose the security standards (Security standards) such as **AWS Foundational Security Best Practices**, **CIS AWS Foundations Benchmark**, and **PCI DSS**.
4. Select **Enable Security Hub**.

![Security Hub](/images/image-ws00018/11.png)

5. After enabling, you will need to wait for Security Hub to evaluate the **Security Score** of your current account based on each security standard you have selected.

![Security Hub](/images/image-ws00018/12.png)

6. Select the **Control** tab to view the **Security Score**.

![Security Hub](/images/image-ws00018/13.png)

{{% notice warning %}}
In some cases, you may see a notification regarding the configuration of **AWS Config**. Enable AWS Config in the corresponding Region. Most evaluation criteria rely on AWS Config service-level rules. When enabling AWS Config recording, choose the option to record all resources in the Region and all global resources.
{{% /notice %}}

#### Configure AWS Config

1. From the AWS console, search for and select **AWS Config**.

![Security Hub](/images/image-ws00018/1.png)

2. Select **Get started**.

![Security Hub](/images/image-ws00018/2.png)

3. In the **Resource type** section, choose **"All globally recorded IAM..."**. In the **Override** section, select **Exclude from recording**.

![Security Hub](/images/image-ws00018/3.png)

4. In the **Data governance** section, choose **Use an existing AWS Config service-linked role**.

![Security Hub](/images/image-ws00018/4.png)

5. In the **Delivery channel** section, choose **Create a bucket**, keep the default bucket name, and select **Next**.

![Security Hub](/images/image-ws00018/5.png)

6. Continue by selecting **Next**.

![Security Hub](/images/image-ws00018/6.png)

7. Select **Confirm**.

![Security Hub](/images/image-ws00018/7.png)

8. Complete the **AWS Config** setup.

![Security Hub](/images/image-ws00018/8.png)
