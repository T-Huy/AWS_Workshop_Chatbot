+++
title = "Dọn dẹp tài nguyên"
date = 2020-05-14T00:38:32+07:00
weight = 5
chapter = false
pre = "<b>5. </b>"
+++

Để tránh chi phí không cần thiết, hãy xóa các tài nguyên bạn đã tạo trong bài tập này. Các bước sau sẽ xóa **Knowledge Bases** trong **Amazon Bedrock**, **Collection** trong **Amazon Opensearch**, dữ liệu được lưu trong **Amazon S3** và chatbot trong **Amazon Lex**.

**Nội dung:**
- [Xóa Knowledge Bases](#xóa-knowledge-bases)
- [Xóa Opensearch](#xóa-opensearch)
- [Xóa S3 Bucket](#xóa-s3-bucket)
- [Xóa Amazon Lex](#xóa-amazon-lex)

#### Xóa Knowledge Bases
1. Truy cập vào **Amazon Bedrock Console**
2. Chọn **Knowledge Bases**, chọn Knowledge Bases đã tạo trước đó. Sau đó bấm **Delete**.
![Clean Up Resources](/images/Clean-Up-Resource/1-select-knowledge-bases.png?width=90pc)
3. Nhập **delete**, sau đó nhấn **Delete**
![Clean Up Resources](/images/Clean-Up-Resource/2-delete-knowledge-bases.png?width=90pc)

#### Xóa Opensearch
1. Truy cập vào **Amazon Opensearch Console**
2. Trong mục **Serverless**, chọn **Dashboard**
3. Chọn **Collection** đã tạo, sau đó bấm **Delete**
![Clean Up Resources](/images/Clean-Up-Resource/3-select-opensearch.png?width=90pc)
4. Nhập **confirm** để xác nhận, sau đó nhấn **Delete**
![Clean Up Resources](/images/Clean-Up-Resource/4-delete-opensearch.png?width=90pc)

#### Xóa S3 Bucket
1. Truy cập vào **Amazon S3 Console**
2. Chọn **s3-data-lex**, sau đó nhấn **Delete**
![Clean Up Resources](/images/Clean-Up-Resource/5-select-s3.png?width=90pc)
3. Nhấn **Empty bucket**
![Clean Up Resources](/images/Clean-Up-Resource/6-empty-bucket.png?width=90pc)
4. Nhập **permanently delete**, sau đó nhấn **Empty**
![Clean Up Resources](/images/Clean-Up-Resource/7-comfirm-empty-bucket.png?width=90pc)
5. Nhập **d3-data-lex**, sau đó nhấn **Delete bucket**
![Clean Up Resources](/images/Clean-Up-Resource/8-delete-bucket.png?width=90pc)

#### Xóa Amazon Lex
1. Truy cập vào **Amazon Lex Console**
2. Chọn Bots: **ChatbotAI**, sau đó chọn **Delete** trong **Action** để xóa chatbot
![Clean Up Resources](/images/Clean-Up-Resource/9-select-and-delete-amazon-lex.png?width=90pc)
