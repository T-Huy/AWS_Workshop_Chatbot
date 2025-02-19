+++
title = "Create a Knowledge Bases for Amazon Bedrock"
date = 2020
weight = 2
chapter = false
pre = "<b>3.2 </b>"
+++

#### Create a Knowledge Bases for Amazon Bedrock
1. Enter **Bedrock** and select **Amazon Bedrock**.
![Bedrock](/images/AWS-Bedrock/1-bedrock.png?width=90pc)
2. Select **Knowledge Bases**, click **Create**, then choose **Knowledge Base with vector store**.
![Bedrock](/images/AWS-Bedrock/2-knowledge-bases.png?width=90pc)
3. In the **Provide knowledge Base details** step, the **Knowledge Base name** is pre-filled (you can change it if desired):
    - Select **Create and use a new service role**.
    - Choose **Amazon S3** for **Data source details**.
    - Click **Next**.
![Bedrock](/images/AWS-Bedrock/3-provide-knowledge-bases-details.png?width=90pc)
![Bedrock](/images/AWS-Bedrock/4-choose-data-source.png?width=90pc)
4. In the **Configure data source** step, the **Data source name** is pre-filled (you can change it if desired):
    - In the S3 URL section, click **Browse S3** and select **s3-data-lex**, which was previously added to S3.
![Bedrock](/images/AWS-Bedrock/5-confidure-data-source.png?width=90pc)\
5. Click **Select model**, and the **Select model** window will appear:
    - Choose **Amazon**.
    - Select **Titan Embeddings G1 - Text V1.2**.
    - Click **Apply**.
![Bedrock](/images/AWS-Bedrock/6-select-model.png?width=90pc)
6. Keep the **Quick create a new vector** store option selected under **Vector database**, then click **Next**.
![Bedrock](/images/AWS-Bedrock/7-vector-database.png?width=90pc)
7. Click **Create Knowledge Bases** to complete the creation of the Knowledge Base
![Bedrock](/images/AWS-Bedrock/8-create-knowledge-bases.png?width=90pc)
8. **Knowledge Base** has been successfully created
![Bedrock](/images/AWS-Bedrock/9-success.png?width=90pc)
9. To enable this **Knowledge Base**, tick the newly created **knowledge base** to sync it, then click **Sync**.
![Bedrock](/images/AWS-Bedrock/10-sync.png?width=90pc)
10. Sync completed successfully
![Bedrock](/images/AWS-Bedrock/11-sync-completed.png?width=90pc)
