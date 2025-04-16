# MSCRS：面向对话推荐系统的多模态语义图提示学习框架

发布时间：2025年04月15日

`LLM应用` `推荐系统` `多模态`

> MSCRS: Multi-modal Semantic Graph Prompt Learning Framework for Conversational Recommender Systems

# 摘要

> 对话推荐系统（CRSs）通过与用户的对话交互提供个性化推荐。现有研究多聚焦于从对话上下文中提取用户偏好，但受限于对话上下文的短小和稀疏特性，仅靠对话上下文难以全面捕捉用户偏好。我们认为，多模态语义信息可以从多个维度丰富用户偏好的表达（例如，用户对某部电影的偏好可能源于其震撼的视觉效果和引人入胜的情节）。本文提出了一种名为 MSCRS 的基于多模态语义图的提示学习框架。首先，我们提取对话上下文中提到的项目的文本和图像特征。其次，通过构建特定于语义模态（协作、文本和图像）的图结构，我们捕获不同语义模态内的高阶语义关联。最后，我们创新性地将多模态语义图与提示学习相结合，利用大型语言模型的能力，全面探索高维语义关系。实验结果表明，我们的方法显著提升了项目推荐的准确性，同时在响应生成中产生了更自然且上下文相关的文本内容。我们发布了代码和扩展的多模态 CRS 数据集，以促进相关研究的进一步探索。

> Conversational Recommender Systems (CRSs) aim to provide personalized recommendations by interacting with users through conversations. Most existing studies of CRS focus on extracting user preferences from conversational contexts. However, due to the short and sparse nature of conversational contexts, it is difficult to fully capture user preferences by conversational contexts only. We argue that multi-modal semantic information can enrich user preference expressions from diverse dimensions (e.g., a user preference for a certain movie may stem from its magnificent visual effects and compelling storyline). In this paper, we propose a multi-modal semantic graph prompt learning framework for CRS, named MSCRS. First, we extract textual and image features of items mentioned in the conversational contexts. Second, we capture higher-order semantic associations within different semantic modalities (collaborative, textual, and image) by constructing modality-specific graph structures. Finally, we propose an innovative integration of multi-modal semantic graphs with prompt learning, harnessing the power of large language models to comprehensively explore high-dimensional semantic relationships. Experimental results demonstrate that our proposed method significantly improves accuracy in item recommendation, as well as generates more natural and contextually relevant content in response generation. We have released the code and the expanded multi-modal CRS datasets to facilitate further exploration in related research\footnote{https://github.com/BIAOBIAO12138/MSCRS-main}.

[Arxiv](https://arxiv.org/abs/2504.10921)