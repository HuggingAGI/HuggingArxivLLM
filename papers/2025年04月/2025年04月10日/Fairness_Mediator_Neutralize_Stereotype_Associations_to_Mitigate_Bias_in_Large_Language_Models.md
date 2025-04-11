# 公平调解员：消除刻板印象关联，缓解大型语言模型中的偏见

发布时间：2025年04月10日

`LLM理论` `社会公平` `偏见消除`

> Fairness Mediator: Neutralize Stereotype Associations to Mitigate Bias in Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）在各类应用中表现卓越，但它们在训练数据中无意间吸收了虚假关联，导致偏见概念与特定社会群体之间形成刻板印象关联。这些关联不仅延续了社会偏见，甚至使其放大，引发了严重的公平性问题。为了缓解这一问题，先前研究尝试通过将模型嵌入投影到无偏空间来消除偏见，但这些方法由于与下游社会偏见的对齐度不足，效果有限。我们发现 LLM 的概念认知主要通过线性关联记忆机制实现，其中键值映射发生在多层感知机（MLP）层。基于此，我们提出偏见概念和社会群体可以被编码为实体（键）和信息（值）对，通过操作这些编码可以促进更公平的关联。为此，我们开发了 Fairness Mediator（FairMed），一个旨在中和刻板印象关联的偏见缓解框架。该框架由两个核心组件构成：刻板印象关联探测器和对抗性去偏中和器。探测器通过围绕偏见概念设计提示，捕捉 MLP 层激活中的刻板印象关联，并检测社会群体的发射概率。随后，对抗性去偏中和器在推理过程中干预 MLP 激活，平衡不同社会群体的关联概率。实验结果表明，FairMed 在九种受保护属性上显著优于现有最优方法。与最有效的基线相比，FairMed 通过减少数百分钟的缓解开销，展现出极具竞争力的效率。此外，FairMed 保持了 LLM 的语言理解能力，同时确保整体性能不受影响。

> LLMs have demonstrated remarkable performance across diverse applications, yet they inadvertently absorb spurious correlations from training data, leading to stereotype associations between biased concepts and specific social groups. These associations perpetuate and even amplify harmful social biases, raising significant fairness concerns. To mitigate such biases, prior studies have attempted to project model embeddings into unbiased spaces during inference. However, these approaches have shown limited effectiveness due to their weak alignment with downstream social biases. Inspired by the observation that concept cognition in LLMs is primarily represented through a linear associative memory mechanism, where key-value mapping occurs in the MLP layers, we posited that biased concepts and social groups are similarly encoded as entity (key) and information (value) pairs, which can be manipulated to promote fairer associations. To this end, we propose Fairness Mediator (FairMed), a bias mitigation framework that neutralizes stereotype associations. Our framework comprises two main components: a stereotype association prober and an adversarial debiasing neutralizer. The prober captures stereotype associations encoded within MLP layer activations by employing prompts centered around biased concepts to detect the emission probabilities for social groups. Subsequently, the adversarial debiasing neutralizer intervenes in MLP activations during inference to equalize the association probabilities among different social groups. Extensive experiments across nine protected attributes show that FairMed significantly outperforms SOTA methods in effectiveness. Compared to the most effective baseline, FairMed presents competitive efficiency by cutting mitigation overhead by hundreds of minutes. FairMed also maintains the LLM's language understanding capabilities without compromising overall performance.

[Arxiv](https://arxiv.org/abs/2504.07787)