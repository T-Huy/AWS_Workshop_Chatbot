+++
title = "Tạo Cơ sở kiến thức cho Amazon Bedrock"
date = 2020
weight = 2
chapter = false
pre = "<b>3.2 </b>"
+++

#### Tạo Cơ sở kiến thức cho Amazon Bedrock
1. Nhập **Bedrock** và chọn **Amazon Bedrock**.
![Bedrock](/images/AWS-Bedrock/1-bedrock.png?width=90pc)
2. Chọn **Knowledge Bases**, chọn **Create** sau đó chọn **Knowledge Base with vector store**.
![Bedrock](/images/AWS-Bedrock/2-knowledge-bases.png?width=90pc)
3. Trong bước **Provide knowledge Base details**, có sẵn **Knowledge Base name** (có thể đổi tên khác nếu muốn):
    - Chọn **Create and use a new service role**. 
    - Chọn **Amazon S3** cho **Data source details**.
    - Nhấn **Next**.
![Bedrock](/images/AWS-Bedrock/3-provide-knowledge-bases-details.png?width=90pc)
![Bedrock](/images/AWS-Bedrock/4-choose-data-source.png?width=90pc)
4. Trong bước **Configure data source**, có sẵn tên **Data source name** (có thể đổi tên khác nếu muốn):
    - Trong phần S3 URL, Chọn **Browse S3** và chọn vào **s3-data-lex** đã thêm vào S3 trước đó.
![Bedrock](/images/AWS-Bedrock/5-confidure-data-source.png?width=90pc)
5. Nhấn **Select model**, Cửa sổ **Select model** xuất hiện:
    - Chọn **Amazon**.
    - Chọn **Titan Embeddings G1 - Text V1.2**.
    - Nhấn **Apply**.
![Bedrock](/images/AWS-Bedrock/6-select-model.png?width=90pc)
6. Giữ nguyên lựa chọn **Quick create a new vector store** trong **Vector database**, sau đó nhấn **Next**.
![Bedrock](/images/AWS-Bedrock/7-vector-database.png?width=90pc)
7. Nhấn **Create Knowledge Bases** để hoàn tất việc tạo Knowledge Base.
![Bedrock](/images/AWS-Bedrock/8-create-knowledge-bases.png?width=90pc)
8. **Knowledge Base** đã được tạo thành công.
![Bedrock](/images/AWS-Bedrock/9-success.png?width=90pc)
9. Để **Knowledge Bases** này có thể hoạt động, tick vào **knowledge base** vừa được tạo để đồng bộ hóa, sau đó nhấn **Sync**.
![Bedrock](/images/AWS-Bedrock/10-sync.png?width=90pc)
10. Đồng bộ hóa thành công.
![Bedrock](/images/AWS-Bedrock/11-sync-completed.png?width=90pc)