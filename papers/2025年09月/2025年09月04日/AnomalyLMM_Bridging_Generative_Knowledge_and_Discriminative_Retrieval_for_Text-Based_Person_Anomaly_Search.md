# AnomalyLMM：桥接生成式知识与判别式检索的基于文本人物异常搜索

发布时间：2025年09月04日

`LLM应用` `基础理论`

> AnomalyLMM: Bridging Generative Knowledge and Discriminative Retrieval for Text-Based Person Anomaly Search

# 摘要

> 随着公共安全需求日益增长，基于文本的人物异常搜索已成为一项关键任务，其目标是通过自然语言描述检索具有异常行为的个体。与传统人物搜索相比，该任务面临两个独特挑战：（1）文本异常与视觉行为的细粒度跨模态对齐；（2）稀疏真实样本下的异常识别。尽管大型多模态模型（LMMs）在多模态理解上表现卓越，但其在细粒度异常检索中的潜力尚未得到充分挖掘，主要受制于生成式知识与判别式检索的领域差异，以及缺乏高效的部署适配方案。为此，我们提出AnomalyLMM——首个利用LMMs实现基于文本的人物异常搜索的框架。核心贡献如下：（1）构建新颖的从粗到细处理管道，通过整合LMMs连接生成式世界知识与检索导向的异常检测；（2）设计一套无需训练的适配策略，包括掩码跨模态提示、行为显著性预测和知识感知重排序，实现零样本聚焦细微异常线索。作为首次将LMMs应用于该任务的研究，我们在PAB数据集（目前唯一公开的文本人物异常搜索基准）上开展严格评估，该数据集涵盖摔倒、碰撞、被击打等多种真实场景的异常案例。实验结果显示，所提方法效果显著，Recall@1准确率较竞争基线提升+0.96%。值得注意的是，通过定性分析验证，该方法实现了文本异常与视觉行为的可解释性对齐。我们将开源代码和模型，以促进未来研究。

> With growing public safety demands, text-based person anomaly search has emerged as a critical task, aiming to retrieve individuals with abnormal behaviors via natural language descriptions. Unlike conventional person search, this task presents two unique challenges: (1) fine-grained cross-modal alignment between textual anomalies and visual behaviors, and (2) anomaly recognition under sparse real-world samples. While Large Multi-modal Models (LMMs) excel in multi-modal understanding, their potential for fine-grained anomaly retrieval remains underexplored, hindered by: (1) a domain gap between generative knowledge and discriminative retrieval, and (2) the absence of efficient adaptation strategies for deployment. In this work, we propose AnomalyLMM, the first framework that harnesses LMMs for text-based person anomaly search. Our key contributions are: (1) A novel coarse-to-fine pipeline integrating LMMs to bridge generative world knowledge with retrieval-centric anomaly detection; (2) A training-free adaptation cookbook featuring masked cross-modal prompting, behavioral saliency prediction, and knowledge-aware re-ranking, enabling zero-shot focus on subtle anomaly cues. As the first study to explore LMMs for this task, we conduct a rigorous evaluation on the PAB dataset, the only publicly available benchmark for text-based person anomaly search, with its curated real-world anomalies covering diverse scenarios (e.g., falling, collision, and being hit). Experiments show the effectiveness of the proposed method, surpassing the competitive baseline by +0.96% Recall@1 accuracy. Notably, our method reveals interpretable alignment between textual anomalies and visual behaviors, validated via qualitative analysis. Our code and models will be released for future research.

[Arxiv](https://arxiv.org/abs/2509.04376)