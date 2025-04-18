# # 个性判别：基于令牌级自我判断的大型语言模型个性化对齐

发布时间：2025年04月17日

`LLM理论` `个性化` `偏好对齐`

> Persona-judge: Personalized Alignment of Large Language Models via Token-level Self-judgment

# 摘要

> 将语言模型与人类偏好对齐面临重大挑战，尤其在实现个性化的同时避免高昂计算成本。现有方法依赖奖励信号和额外标注数据，这限制了其扩展性和对多样化人类价值观的适应能力。为应对这些挑战，我们提出了一种新型判别范式Persona-judge，它无需训练即可实现个性化对齐，适用于未见偏好。与通过外部奖励反馈优化策略参数不同，Persona-judge利用模型自身内在的偏好判断能力。具体而言，草稿模型根据给定偏好生成候选标记，而判别模型通过体现不同偏好，对预测标记进行交叉验证，判断其是否应被接受。实验结果表明，Persona-judge通过利用模型固有的偏好评估机制，为个性化对齐提供了一种可扩展且计算高效的解决方案，为更灵活的定制化对齐奠定了基础。

> Aligning language models with human preferences presents significant challenges, particularly in achieving personalization without incurring excessive computational costs. Existing methods rely on reward signals and additional annotated data, limiting their scalability and adaptability to diverse human values. To address these challenges, we introduce Persona-judge, a novel discriminative paradigm that enables training-free personalized alignment with unseen preferences. Instead of optimizing policy parameters through external reward feedback, Persona-judge leverages the intrinsic preference judgment capabilities of the model. Specifically, a draft model generates candidate tokens conditioned on a given preference, while a judge model, embodying another preference, cross-validates the predicted tokens whether to be accepted. Experimental results demonstrate that Persona-judge, using the inherent preference evaluation mechanisms of the model, offers a scalable and computationally efficient solution to personalized alignment, paving the way for more adaptive customized alignment.

[Arxiv](https://arxiv.org/abs/2504.12663)