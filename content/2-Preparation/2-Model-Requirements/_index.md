+++
title = "Model Requirements"
date = 2020-05-14T00:38:32+07:00
weight = 2
chapter = false
pre = "<b>2.2 </b>"
+++

#### Amazon Bedrock requirements
**Base Models Access**
If you are looking to interact with models from Amazon Bedrock, you need to request access to the base models in one of the regions where Amazon Bedrock is available. 
Make sure to read and accept models’ end-user license agreements or EULA.

{{%notice note%}}
You can deploy the solution to a different region from where you requested Base Model access. **While the Base Model access approval is instant, it might take several minutes to get access and see the list of models in the UI.**
{{%/notice%}}

1. Find **Bedrock**
2. Click **Bedrock**

![1-bedrock](/images/AWS-Bedrock/1-bedrock.png?width=90pc)

3. Click **Model access**
4. Click **Modify model access**
![Bedrock](/images/Model-Access/Bedrock.png?width=90pc)
5. Click **Next**
![Next](/images/Model-Access/Next.png?width=90pc)
6. Click **Submit**
![Submit](/images/Model-Access/Submit.png?width=90pc)
7. **Amazon Bedrock**
![Amazon bedrock](/images/Model-Access/base-model.png?width=90pc)

