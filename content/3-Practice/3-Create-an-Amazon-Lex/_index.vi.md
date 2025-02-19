+++
title = "Tạo Amazon Lex"
date = 2020
weight = 3
chapter = false
pre = "<b>3.3 </b>"
+++

#### Tạo Amazon Lex
1. Tìm kiếm **Lex**, sau đó chọn **Amazon Lex**.
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/1-lex.png?width=90pc)
2. Nhấn **Create bot** để tạo chatbot
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/2-create-bot.png?width=90pc)
3. Nhập **ChatbotAI** trong ô **Bot name**, sau đó **Create a role with basic Amazon Lex permissions**.
    - Trong **Children's Online Privacy Protection Act (COPPA)**, chọn **No**, sau đó chọn **Next** để sang bước tiếp theo.
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/3-bot-configuration.png?width=90pc)
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/4-children-and-next.png?width=90pc)
4. Trong trang **Add language to bot**:
    - Chọn **language**.
    - Chọn **Voice interaction**
    - Sau đó, chọn **Done**.
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/5-add-language-to-bot.png?width=90pc)
5. Trong trang Intent:NewIntent: 
    - Nhập **ChatBotIntent** trong **Intent name**.
    - Trong mục **Samle utterances**, nhập các câu mở đầu để chatbot bắt đầu trả lời.
    - Trong mục **intial response**, nhập **Hi! How can I help you today?** trong **Message-optinal**, sau đó chọn **Advanced options**.
    - Sau đó chọn **Wait for users input** trong **Next step in conversation** để chuyển thành đợi người dùng nhập vào mới trả lời tiếp, nhấn **Update options** lưu lại.
    - Nhấn **Save intent** để lưu những thông tin vừa rồi đã chọn.
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/6-intent-newintent.png?width=90pc)
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/7-sample-utterances.png?width=90pc)
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/8-initial-response.png?width=90pc)
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/9-update-options.png?width=90pc)
6. Trong trang **Intents**, nhấn **Add intent**, sau đó chọn **Use built-in intent**.
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/10-use-build-in-intent.png?width=90pc)
7. Giao diện **Use build-in intent** được mở ra:
    - Chọn **AMAZON QnAIntent - GenAI feature** trong **Built-in intent**.
    - Nhập **QnABotIntent** trong **Intent name**.
    - Nhấn **Add** để đóng.
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/11-add-build-in.png?width=90pc)
8. Trong trang **QnABotIntent**:
    - Chọn nhà cung cấp model **Anthropic**.
    - Chọn model **Claude3 Haiku**.
    - Chọn **Knowledge base for Amazon bedrock**.
    - Amazon Bedrock id hiển thị, nhớ lưu lại để dùng cho bước tiếp theo.
    - Nhấn **Save intent** để lưu những nội dung vừa chọn.
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/12-select-model.png?width=90pc)
9. Nhấn **Build**, chờ một vài phút để quá trình build hoàn tất, sau đó nhấn **Test** để sử dụng chatbot.
![AWS Lex](https://t-huy.github.io/AWS_Workshop_Chatbot/images/AWS-Lex/13-build-and-test.png?width=90pc)