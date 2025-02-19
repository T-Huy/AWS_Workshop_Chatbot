+++
title = "Create an Amazon Lex"
date = 2020
weight = 3
chapter = false
pre = "<b>3.3 </b>"
+++

#### Create an Amazon Lex
1. Search for **Lex**, then select **Amazon Lex**.
![AWS Lex](/images/AWS-Lex/1-lex.png?width=90pc)
2. Click **Create bot** to create a chatbot.
![AWS Lex](/images/AWS-Lex/2-create-bot.png?width=90pc)
3. Enter **ChatbotAI** in the **Bot name** field, then select **Create a role with basic Amazon Lex permissions**.
    - In the **Children's Online Privacy Protection Act (COPPA)** section, select **No**, then click **Next** to proceed.
![AWS Lex](/images/AWS-Lex/3-bot-configuration.png?width=90pc)
![AWS Lex](/images/AWS-Lex/4-children-and-next.png?width=90pc)
4. On the **Add language** to bot page:
    - Select **language**.
    - Select **Voice interaction**.
    - Then click **Done**.
![AWS Lex](/images/AWS-Lex/5-add-language-to-bot.png?width=90pc)
5. On the **Intent:NewIntent** page:
    - Enter **ChatBotIntent** in the **Intent name** field.
    - In the **Sample utterances** section, enter example phrases to trigger chatbot responses.
    - In the **Initial response** section, enter **Hi! How can I help you today?** in the **Message - optional** field, then select **Advanced options**.
    - In the **Next step in conversation** section, select **Wait for user input** to allow the chatbot to wait for the user's response before proceeding, then click **Update options** to save.
    - Click **Save intent** to save the configured settings.
![AWS Lex](/images/AWS-Lex/6-intent-newintent.png?width=90pc)
![AWS Lex](/images/AWS-Lex/7-sample-utterances.png?width=90pc)
![AWS Lex](/images/AWS-Lex/8-initial-response.png?width=90pc)
![AWS Lex](/images/AWS-Lex/9-update-options.png?width=90pc)
6. On the **Intents** page, click **Add intent**, then select **Use built-in intent**.
![AWS Lex](/images/AWS-Lex/10-use-build-in-intent.png?width=90pc)
7. The **Use built-in intent** interface appears:
    - Select **AMAZON QnAIntent - GenAI feature** under **Built-in inten**t.
    - Enter **QnABotIntent** in the **Intent name** field.
    - Click **Add** to confirm
![AWS Lex](/images/AWS-Lex/11-add-build-in.png?width=90pc)
8. On the **QnABotIntent** page:
    - Select the model provider **Anthropic**.
    - Choose the model **Claude3 Haiku**.
    - Select **Knowledge base for Amazon Bedrock**.
    - The Amazon Bedrock ID will be displayed-be sure to save it for the next step.
    - Click **Save intent** to save the settings
![AWS Lex](/images/AWS-Lex/12-select-model.png?width=90pc)
9. Click **Build**, wait a few minutes for the build process to complete, then click **Test** to start using the chatbot.
![AWS Lex](/images/AWS-Lex/13-build-and-test.png?width=90pc)
