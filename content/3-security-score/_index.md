+++
title = "Score by Security Standards"
weight = 3
chapter = false
pre = "<b>3. </b>"
+++

#### Review Evaluation by Each Security Standard

After some time, Security Hub will generate evaluations based on scores and highlight existing security risks in your account. To list the detected risks, you can navigate into each security standard to view the assessment results:

1. Log in to the **Amazon Management Console**. In the search bar, type and search for **Security Hub CSPM**.

![Security Hub](/images/image-ws00018/9.png)

2. In the left navigation panel, select **Security standards** to view the overall assessment scores for each security framework.

3. To view detailed evaluation criteria for each standard, choose **View results** (for the respective security standard).

   - Example: The **Foundational Security Best Practices v1.0.0** standard

![Security Hub](/images/image-ws00018/14.png)

![Security Hub](/images/image-ws00018/15.png)

4. If there are certain controls you do not want to apply, you can remove them from the evaluation. Select the specific control in the list of the corresponding standard.

   - **Example**: You want to disable *EC2 instances managed by Systems Manager should have an association compliance status of COMPLIANT* in the **PCI DSS v3.2.1** standard.

![Security Hub](/images/image-ws00018/16.png)

![Security Hub](/images/image-ws00018/17.png)

- On the control details page, click **Enabled**, then choose **Disable**.

![Security Hub](/images/image-ws00018/18.png)

- Enter a reason for disabling the control, then click **Disable**.

![Security Hub](/images/image-ws00018/19.png)
