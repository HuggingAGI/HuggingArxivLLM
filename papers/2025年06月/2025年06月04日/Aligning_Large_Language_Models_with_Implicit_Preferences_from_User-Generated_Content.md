# # 用户生成内容中的隐含偏好对齐的大语言模型

发布时间：2025年06月04日

`LLM理论` `模型训练` `生成质量`

> Aligning Large Language Models with Implicit Preferences from User-Generated Content

# 摘要

> 从偏好反馈中学习对于使大型语言模型（LLMs）与人类价值观保持一致并提高生成响应的质量至关重要。然而，现有的偏好学习方法严重依赖于人工整理的数据或先进LLMs生成的数据，这种方法成本高昂且难以扩展。本文提出了一种名为PUGC的全新框架，该框架利用未标注用户生成内容（UGC）中隐含的人类偏好来生成偏好数据。虽然UGC并非特意为指导LLMs生成符合人类偏好的响应而创作，但它往往反映了其创作者有价值的见解和隐含偏好，这些内容具有解决读者问题的潜力。PUGC将UGC转换为用户查询，并从策略模型中生成响应。随后，将UGC用作响应评分的参考文本，使模型与这些隐含偏好保持一致。这种方法不仅提升了偏好数据的质量，还实现了可扩展的、特定领域的模型对齐。在Alpaca Eval 2上的实验结果表明，与传统方法相比，采用DPO和PUGC训练的模型性能提升了9.37%，使用Mistral-7B-Instruct实现了35.93%的最新长度控制胜率。进一步研究表明，在奖励质量、特定领域对齐效果、对UGC质量的鲁棒性以及心智理论能力方面均取得了提升。我们的代码和数据集可在https://zhaoxuan.info/PUGC.github.io/获取。

> Learning from preference feedback is essential for aligning large language models (LLMs) with human values and improving the quality of generated responses. However, existing preference learning methods rely heavily on curated data from humans or advanced LLMs, which is costly and difficult to scale. In this work, we present PUGC, a novel framework that leverages implicit human Preferences in unlabeled User-Generated Content (UGC) to generate preference data. Although UGC is not explicitly created to guide LLMs in generating human-preferred responses, it often reflects valuable insights and implicit preferences from its creators that has the potential to address readers' questions. PUGC transforms UGC into user queries and generates responses from the policy model. The UGC is then leveraged as a reference text for response scoring, aligning the model with these implicit preferences. This approach improves the quality of preference data while enabling scalable, domain-specific alignment. Experimental results on Alpaca Eval 2 show that models trained with DPO and PUGC achieve a 9.37% performance improvement over traditional methods, setting a 35.93% state-of-the-art length-controlled win rate using Mistral-7B-Instruct. Further studies highlight gains in reward quality, domain-specific alignment effectiveness, robustness against UGC quality, and theory of mind capabilities. Our code and dataset are available at https://zhaoxuan.info/PUGC.github.io/

[Arxiv](https://arxiv.org/abs/2506.04463)