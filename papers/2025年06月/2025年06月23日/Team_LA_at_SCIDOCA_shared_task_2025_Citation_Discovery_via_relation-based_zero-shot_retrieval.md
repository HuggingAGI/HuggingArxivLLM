# LA团队在SCIDOCA共享任务2025中，利用基于关系的零样本检索技术进行引文发现。

发布时间：2025年06月23日

`LLM应用` `信息检索` `引文发现`

> Team LA at SCIDOCA shared task 2025: Citation Discovery via relation-based zero-shot retrieval

# 摘要

> # 引文发现共享任务
本任务旨在从候选池中为给定段落准确匹配合适的引文。主要难点在于摘要篇幅较长，且候选摘要间相似度高，导致难以精准定位目标论文。针对这一难题，我们开发了一套两步走的解决方案：首先，从给定段落中提取关联特征，检索出最相似的前k个摘要；随后，借助大型语言模型（LLM）从候选中精确定位最相关的引用。我们在SCIDOCA 2025提供的训练数据集上进行了实验，结果表明该框架在引文预测任务中表现出色。

> The Citation Discovery Shared Task focuses on predicting the correct citation from a given candidate pool for a given paragraph. The main challenges stem from the length of the abstract paragraphs and the high similarity among candidate abstracts, making it difficult to determine the exact paper to cite. To address this, we develop a system that first retrieves the top-k most similar abstracts based on extracted relational features from the given paragraph. From this subset, we leverage a Large Language Model (LLM) to accurately identify the most relevant citation. We evaluate our framework on the training dataset provided by the SCIDOCA 2025 organizers, demonstrating its effectiveness in citation prediction.

[Arxiv](https://arxiv.org/abs/2506.18316)