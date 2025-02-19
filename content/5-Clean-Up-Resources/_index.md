+++
title = "Clean Up Resources"
date = 2020-05-14T00:38:32+07:00
weight = 5
chapter = false
pre = "<b>5. </b>"
+++

To avoid unnecessary costs, delete the resources you created in this exercise. The following steps will remove the **Knowledge Bases** in **Amazon Bedrock**, the **Collection** in **Amazon OpenSearch**, the data stored in **Amazon S3** and the chatbot in **Amazon Lex**.

**Content:**
- [Delete the Knowledge Bases](#delete-the-knowledge-bases)
- [Delete the Opensearch](#delete-the-opensearch)
- [Delete the S3 Bucket](#delete-the-s3-bucket)
- [Delete the Amazon Lex](#delete-the-amazon-lex)

#### Delete the Knowledge Bases
1. Go to the **Amazon Bedrock Console**.
2. Select **Knowledge Bases**, then choose the previously created Knowledge Base. Click **Delete**.
![Clean Up Resources](https://t-huy.github.io/AWS_Workshop_Chatbot/images/Clean-Up-Resource/1-select-knowledge-bases.png?width=90pc)
3. Enter **delete**,  then click **Delete**.
![Clean Up Resources](https://t-huy.github.io/AWS_Workshop_Chatbot/images/Clean-Up-Resource/2-delete-knowledge-bases.png?width=90pc)

#### Delete the Opensearch
1. Go to the **Amazon OpenSearch Console**
2. Under the **Serverless** section, select **Dashboard**.
3. Choose the **Collection** you created, then click **Delete**
![Clean Up Resources](https://t-huy.github.io/AWS_Workshop_Chatbot/images/Clean-Up-Resource/3-select-opensearch.png?width=90pc)
4. Enter **confirm** to confirm, then click **Delete**
![Clean Up Resources](https://t-huy.github.io/AWS_Workshop_Chatbot/images/Clean-Up-Resource/4-delete-opensearch.png?width=90pc)

#### Delete the S3 Bucket
1. Go to the **Amazon S3 Console**.
2. Select **s3-data-lex**, then click **Delete**.
![Clean Up Resources](https://t-huy.github.io/AWS_Workshop_Chatbot/images/Clean-Up-Resource/5-select-s3.png?width=90pc)
3. Click **Empty bucket**.
![Clean Up Resources](https://t-huy.github.io/AWS_Workshop_Chatbot/images/Clean-Up-Resource/6-empty-bucket.png?width=90pc)
4. Enter **permanently delete**, then click **Empty**.
![Clean Up Resources](https://t-huy.github.io/AWS_Workshop_Chatbot/images/Clean-Up-Resource/7-comfirm-empty-bucket.png?width=90pc)
5. Enter **s3-data-lex**, then click **Delete bucket**.
![Clean Up Resources](https://t-huy.github.io/AWS_Workshop_Chatbot/images/Clean-Up-Resource/8-delete-bucket.png?width=90pc)

#### Delete the Amazon Lex
1. Go to the **Amazon Lex Console**.
2. Select the Bots **ChatbotAI**, then under **Action**, click **Delete** to remove the chatbot
![Clean Up Resources](https://t-huy.github.io/AWS_Workshop_Chatbot/images/Clean-Up-Resource/9-select-and-delete-amazon-lex.png?width=90pc)