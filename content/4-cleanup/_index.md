+++
title = "Clean Up Resources"
date = 2021-07-07T21:33:20+07:00
weight = 4
chapter = false
pre = "<b>4. </b>"
+++

In this section, you will disable AWS Security Hub to avoid incurring additional costs for your AWS account (most of the cost comes from AWS Config). However, if you are operating in a production environment, you should keep AWS Security Hub enabled to help better manage your account security.

#### Disable AWS Security Hub

1. Go to **Security Hub CSPM**
   - Select **Settings > General** from the left navigation panel.

2. In the **Settings** page on the right, select the **General** tab
   - Scroll to the bottom and choose **Disable AWS Security Hub**
   - In the prompt, select **Disable AWS Security Hub**

![Security Hub](/images/image-ws00018/20.png)

#### Disable AWS Config

3. Go to **AWS Config**, on the right select **Settings**, then choose **Stop recording**

![Security Hub](/images/image-ws00018/21.png)

#### Delete S3 Bucket

4. Go to **AWS S3 Bucket**

![Security Hub](/images/image-ws00018/22.png)

- Select the bucket you created, then choose **Empty**

![Security Hub](/images/image-ws00018/23.png)

- Type *permanently delete*, then choose **Empty**.

![Security Hub](/images/image-ws00018/24.png)

- Select the same bucket again and choose **Delete**

![Security Hub](/images/image-ws00018/25.png)

- Enter the bucket name and choose **Delete bucket**

![Security Hub](/images/image-ws00018/26.png)
