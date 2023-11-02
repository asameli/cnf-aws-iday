---
title: "Task 2: Delete the references towards FortiGate CNF endpoints"
chapter: true
weight: 2
---


# Task 2: Delete the references towards FortiGate CNF endpoints

- 1.  In the AWS console, go to the **VPC Dashboard**. Go to **Route tables** on the lefthand menu. Check each route table for entries which point towards a GWLBe. These entries start wich **vpce-**. For each route table with such an entry select **Edit routes**.

![](../images/image-cleanup-t2-1.png)

{{% notice info %}}
**Note:** If you can't see any route tables, make sure you have the correct region selected on the top. The region should either be **Ohio** or **N. Virginia**.
{{% /notice %}}

- 2. Delete the respective route by clicking **Remove**.


![](../images/image-cleanup-t2-2.png)

- 3. Repeat these steps for all routes until you don't have any more entries towards any endpoint.

- 4. This concludes this section.
