# 基于具有多领域适应的在线短视频平台开展个性分析

发布时间：2024年10月25日

`LLM应用` `短视频` `人格分析`

> Personality Analysis from Online Short Video Platforms with Multi-domain Adaptation

# 摘要

> 在线短视频中的人格分析愈发重要，因其在个性化推荐系统、情感分析和人机交互等领域得以应用。传统评估方法，像基于大五人格框架的问卷调查，受自我报告偏差所限，在大规模或实时分析中不实用。利用短视频丰富的多模态数据为更精准的人格推断提供了可行替代方案。然而，整合这些多样且异步的模态面临重大挑战，尤其是对齐时变数据以及确保模型在标记数据有限的新领域能良好泛化。本文中，我们提出一种新颖的多模态人格分析框架，通过同步和整合多模态特征，并借助领域适应增强模型泛化能力来应对这些挑战。我们引入基于时间戳的模态对齐机制，依据口语单词时间戳同步数据，保证跨模态的准确对应，促进有效特征整合。为捕捉时间依赖关系和模态间相互作用，我们运用双向长短期记忆网络和自注意力机制，使模型聚焦于最具信息性的特征进行人格预测。此外，我们开发了基于梯度的领域适应方法，将知识从多个源领域迁移，提升在标记数据稀缺的目标领域的性能。在真实世界数据集上的大量实验表明，我们的框架在人格预测任务中显著优于现有方法，凸显其在捕捉复杂行为线索和适应新领域方面的有效性和稳健性。

> Personality analysis from online short videos has gained prominence due to its applications in personalized recommendation systems, sentiment analysis, and human-computer interaction. Traditional assessment methods, such as questionnaires based on the Big Five Personality Framework, are limited by self-report biases and are impractical for large-scale or real-time analysis. Leveraging the rich, multi-modal data present in short videos offers a promising alternative for more accurate personality inference. However, integrating these diverse and asynchronous modalities poses significant challenges, particularly in aligning time-varying data and ensuring models generalize well to new domains with limited labeled data. In this paper, we propose a novel multi-modal personality analysis framework that addresses these challenges by synchronizing and integrating features from multiple modalities and enhancing model generalization through domain adaptation. We introduce a timestamp-based modality alignment mechanism that synchronizes data based on spoken word timestamps, ensuring accurate correspondence across modalities and facilitating effective feature integration. To capture temporal dependencies and inter-modal interactions, we employ Bidirectional Long Short-Term Memory networks and self-attention mechanisms, allowing the model to focus on the most informative features for personality prediction. Furthermore, we develop a gradient-based domain adaptation method that transfers knowledge from multiple source domains to improve performance in target domains with scarce labeled data. Extensive experiments on real-world datasets demonstrate that our framework significantly outperforms existing methods in personality prediction tasks, highlighting its effectiveness in capturing complex behavioral cues and robustness in adapting to new domains.

[Arxiv](https://arxiv.org/abs/2411.00813)