# # PersonaBench：评估AI模型对个人信息的理解能力，通过访问（合成）用户数据。

发布时间：2025年02月27日

`RAG` `数据隐私` `个性化服务`

> PersonaBench: Evaluating AI Models on Understanding Personal Information through Accessing (Synthetic) Private User Data

# 摘要

> 在AI助手领域，个性化至关重要，尤其是在与单个用户协作的私有AI模型中。一个关键场景是使AI模型能够访问和解读用户的私有数据（例如，聊天记录、用户与AI的互动、应用程序使用情况），以便理解用户的个人信息，如传记信息、偏好和社交关系。然而，由于此类数据的敏感性，目前没有公开可用的数据集允许我们评估AI模型通过直接访问个人信息来理解用户的能力。
    为了解决这一问题，我们引入了一个合成数据生成管道，用于创建多样化且逼真的用户档案和模拟人类活动的私有文档。利用这些合成数据，我们提出了PersonaBench，这是一个旨在评估AI模型从模拟私有用户数据中理解个人信息能力的基准。
    我们通过与用户个人信息直接相关的问题，结合提供给模型的相关私有文档，评估了检索增强生成（RAG）管道。我们的结果显示，目前的检索增强AI模型在从用户文档中提取个人信息以回答私有问题方面存在困难，突显了改进方法以增强AI个性化能力的必要性。
    

> Personalization is critical in AI assistants, particularly in the context of private AI models that work with individual users. A key scenario in this domain involves enabling AI models to access and interpret a user's private data (e.g., conversation history, user-AI interactions, app usage) to understand personal details such as biographical information, preferences, and social connections. However, due to the sensitive nature of such data, there are no publicly available datasets that allow us to assess an AI model's ability to understand users through direct access to personal information.
  To address this gap, we introduce a synthetic data generation pipeline that creates diverse, realistic user profiles and private documents simulating human activities. Leveraging this synthetic data, we present PersonaBench, a benchmark designed to evaluate AI models' performance in understanding personal information derived from simulated private user data.
  We evaluate Retrieval-Augmented Generation (RAG) pipelines using questions directly related to a user's personal information, supported by the relevant private documents provided to the models. Our results reveal that current retrieval-augmented AI models struggle to answer private questions by extracting personal information from user documents, highlighting the need for improved methodologies to enhance personalization capabilities in AI.

[Arxiv](https://arxiv.org/abs/2502.20616)