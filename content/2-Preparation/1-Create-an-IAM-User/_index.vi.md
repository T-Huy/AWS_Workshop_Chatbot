+++
title = "Tạo tài khoản IAM User"
date = 2020-05-14T00:38:32+07:00
weight = 1
chapter = false
pre = "<b>2.1 </b>"
+++

#### Tạo tài khoản IAM User
1. Tìm kiếm **IAM** and click **IAM**.
![IAM](https://t-huy.github.io/AWS_Workshop_Chatbot/images/IAM-User/IAM.png?width=90pc)
2. Trong thanh điều hướng bên trái, chọn **User**, sau đó nhấp vào **Create User**
![User](https://t-huy.github.io/AWS_Workshop_Chatbot/images/IAM-User/user.png?width=90pc)
3. Tại trang **Set user details**, nhập các thông tin sau:
    - Tên người dùng: **Huy**.
    - Loại quyền truy cập: Đánh dấu vào **AWS Management Console access** để cho phép người dùng truy cập bảng điều khiển AWS.
    - Mật khẩu bảng điều khiển: chọn **Custom password** và nhập mật khẩu mà bạn muốn cho người dùng.
    - Yêu cầu đặt lại mật khẩu: bỏ chọn tùy chọn này để người dùng không cần thay đổi mật khẩu khi đăng nhập lần đầu.
    - Kiểm tra và chọn **Next**.
![Specify User Details](https://t-huy.github.io/AWS_Workshop_Chatbot/images/IAM-User/3-specify-user-details-1.png?width=90pc)
![Specify User Details](https://t-huy.github.io/AWS_Workshop_Chatbot/images/IAM-User/4-specify-user-details-2.png?width=90pc)
4. Tại trang **Set permissions**, thực hiện:
    - Chọn **Attach policies directly** để chọn phương thức cấp quyền trực tiếp cho người dùng.
    - Một người dùng IAM với chính sách **AdministratorAccess** được cấp quyền (đối với sản xuất, chúng tôi khuyên bạn nên hạn chế quyền truy cập theo nhu cầu).
![Set Permissions](https://t-huy.github.io/AWS_Workshop_Chatbot/images/IAM-User/5-set-permissions.png?width=90pc)
5. Tại trang Add tags (optional), giữ nguyên mặc định và chọn **Next**.
6. Tại trang **Review and create**, kiểm tra thông tin và chọn **Create user**
![Review And Create](https://t-huy.github.io/AWS_Workshop_Chatbot/images/IAM-User/6-review-and-create.png?width=90pc)
7. Khi khởi tạo hoàn tất, nhấn **Return to users list** để trở lại **IAM Console**.
![Retrieve Password](https://t-huy.github.io/AWS_Workshop_Chatbot/images/IAM-User/7-retrieve-password.png?width=90pc)
8. IAM User đã được tạo thành công.