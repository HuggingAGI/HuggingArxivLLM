# 基于增强生成的强化学习为大型语言模型嵌入领域知识

发布时间：2025年09月24日

`强化学习` `医疗健康` `法律科技`

> Embedding Domain Knowledge for Large Language Models via Reinforcement Learning from Augmented Generation

# 摘要

> 大型语言模型（LLMs）在特定领域任务中常表现欠佳，这源于训练数据中专业信息的天然不均衡分布以及数据集的静态特性。知识匮乏与时效性滞后导致领域应用存在知识断层。尽管通过领域数据集后训练能向模型注入知识，但现有方法仍有不足：持续预训练（CPT）对领域文档中的所有标记一视同仁，无法突出关键知识点；而基于问答对的监督微调（SFT）则难以形成复杂推理任务所需的连贯知识结构。针对这些问题，我们提出基于增强生成的强化学习（RLAG）方法。该方法通过计算奖励，在采样生成与模型优化之间迭代循环，高效注入关键且上下文连贯的领域知识。我们选取对数概率最高的生成结果作为采样输出，再通过三个定制奖励指标引导优化过程。为全面评估模型的领域专业能力，我们从答案准确性和正确答案对应解释的合理性两方面进行评测。在医学、法律、天文学及时事数据集上的实验结果显示，所提方法的性能显著优于基线方法。相关代码与数据已开源，地址为https://github.com/ChaojunNie/RLAG。

> Large language models (LLMs) often exhibit limited performance on domain-specific tasks due to the natural disproportionate representation of specialized information in their training data and the static nature of these datasets. Knowledge scarcity and temporal lag create knowledge gaps for domain applications. While post-training on domain datasets can embed knowledge into models, existing approaches have some limitations. Continual Pre-Training (CPT) treats all tokens in domain documents with equal importance, failing to prioritize critical knowledge points, while supervised fine-tuning (SFT) with question-answer pairs struggles to develop the coherent knowledge structures necessary for complex reasoning tasks. To address these challenges, we propose Reinforcement Learning from Augmented Generation (RLAG). Our approach iteratively cycles between sampling generations and optimizing the model through calculated rewards, effectively embedding critical and contextually coherent domain knowledge. We select generated outputs with the highest log probabilities as the sampling result, then compute three tailored reward metrics to guide the optimization process. To comprehensively evaluate domain expertise, we assess answer accuracy and the rationality of explanations generated for correctly answered questions. Experimental results across medical, legal, astronomy, and current events datasets demonstrate that our proposed method significantly outperforms baseline approaches. Our code and data are open sourced at https://github.com/ChaojunNie/RLAG.

[Arxiv](https://arxiv.org/abs/2509.20162)