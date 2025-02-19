+++
title = "Create an IAM User"
date = 2020-05-14T00:38:32+07:00
weight = 1
chapter = false
pre = "<b>2.1 </b>"
+++

#### Creat an IAM User
1. Search **IAM** and click **IAM**.
![IAM](/images/IAM-User/1-IAM.png?width=90pc)
2. In the left navigation bar, select **User**, then click **Create User**
![User](/images/IAM-User/2-user.png?width=90pc)
3. On the **Specify user details** page, enter the following information:
    - User name: **Huy**.
    - Access type: tick **AWS Management Console access** to allow users to access AWS Management Console.
    - Console password: select **Custom password** and enter the password you like for the user.
    - Require password reset: uncheck this option so that the user does not need to change the password when logging in for the first time
    - Check and select **Next**.
![Specify User Details](/images/IAM-User/3-specify-user-details-1.png?width=90pc)
![Specify User Details](/images/IAM-User/4-specify-user-details-2.png?width=90pc)
4. On the **Set permissions** page, we operate:
    - Select **Attach policies directly** to choose the method of assigning permissions directly to the user.
    - An IAM User with **AdministratorAccess** policy granted (for production, we recommend restricting access as needed).
![Set Permissions](/images/IAM-User/5-set-permissions.png?width=90pc)
5. On the Add tags (optional) page, keep the defaults and select **Next**.
6. On the **Review and create** page, check the information and select **Create user**
![Review And Create](/images/IAM-User/6-review-and-create.png?width=90pc)
7. When the initialization is complete, press **Return to users list** to return to the **IAM Console**.
![Retrieve Password](/images/IAM-User/7-retrieve-password.png?width=90pc)
8. IAM User has been successfully created.
