# 面向房屋损坏评估的多模态RAG框架：图像编码与政策向量检索的协同优化

发布时间：2025年09月09日

`RAG` `金融科技`

> A Multimodal RAG Framework for Housing Damage Assessment: Collaborative Optimization of Image Encoding and Policy Vector Retrieval

# 摘要

> 自然灾害发生后，精准评估房屋受损情况对保险理赔响应和资源规划至关重要。本研究提出一种新颖的多模态检索增强生成（MM-RAG）框架。在经典RAG架构基础上，该框架进一步设计双分支多模态编码器结构：图像分支采用ResNet与Transformer组成的视觉编码器提取灾后建筑损坏特征，文本分支则通过BERT检索器对帖子及保险政策进行文本向量化，并构建可检索的恢复索引。为实现跨模态语义对齐，模型集成跨模态交互模块，借助多头注意力机制衔接图像与文本的语义表示。同时，生成模块引入模态注意力门控机制，可动态调控生成过程中视觉证据与文本先验信息的作用。整个框架采用端到端训练，融合对比损失、检索损失与生成损失构建多任务优化目标，通过协同学习实现图像理解与政策匹配。实验结果显示，该框架在检索准确率和损坏严重程度分类指标上表现卓越，Top-1检索准确率提升9.6%。

> After natural disasters, accurate evaluations of damage to housing are important for insurance claims response and planning of resources. In this work, we introduce a novel multimodal retrieval-augmented generation (MM-RAG) framework. On top of classical RAG architecture, we further the framework to devise a two-branch multimodal encoder structure that the image branch employs a visual encoder composed of ResNet and Transformer to extract the characteristic of building damage after disaster, and the text branch harnesses a BERT retriever for the text vectorization of posts as well as insurance policies and for the construction of a retrievable restoration index. To impose cross-modal semantic alignment, the model integrates a cross-modal interaction module to bridge the semantic representation between image and text via multi-head attention. Meanwhile, in the generation module, the introduced modal attention gating mechanism dynamically controls the role of visual evidence and text prior information during generation. The entire framework takes end-to-end training, and combines the comparison loss, the retrieval loss and the generation loss to form multi-task optimization objectives, and achieves image understanding and policy matching in collaborative learning. The results demonstrate superior performance in retrieval accuracy and classification index on damage severity, where the Top-1 retrieval accuracy has been improved by 9.6%.

[Arxiv](https://arxiv.org/abs/2509.09721)