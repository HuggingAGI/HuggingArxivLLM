# GUARD：通过数据归属实现大型语言模型的引导式遗忘与保留

发布时间：2025年06月12日

`LLM理论` `人工智能` `数据科学`

> GUARD: Guided Unlearning and Retention via Data Attribution for Large Language Models

# 摘要

> 大型语言模型（LLMs）中的反向学习（unlearning）由于合规性、版权保护和隐私问题变得日益重要。然而，LLM反向学习面临的关键挑战是无意中遗忘（unintended forgetting），即移除特定数据时，无意中损害了模型的效用及其对有价值信息的保留能力。尽管先前的工作主要集中在架构创新上，但数据层面因素对反向学习性能的影响仍未得到充分探索。因此，现有方法在遗忘高影响数据时，往往会导致信息保留能力下降。为解决这一问题，我们提出了GUARD——一种通过数据归属（data attribution）实现引导式反向学习与保留的新颖框架。

GUARD的核心是一个专为LLM反向学习设计的轻量级代理数据归属度量（proxy data attribution metric），它量化了遗忘集与保留集之间的“对齐”程度，同时保持了计算效率。在此基础上，我们设计了一个新颖的反向学习目标，为样本分配自适应的非均匀反向学习权重，这些权重与代理归属分数成反比。通过这种反向学习能力的重新分配，GUARD缓解了保留中的意外损失。

我们提供了严格的理论保证，证明GUARD显著提升了信息保留能力，同时保持了与先前方法相当的遗忘指标。在多个LLM架构上的TOFU基准测试中，大量实验表明，GUARD在确保有效反向学习的同时，显著提高了效用保留。值得注意的是，当遗忘10%的训练数据时，GUARD在保留集上的效用牺牲在真实比率（Truth Ratio）指标上减少了高达194.92%。


> Unlearning in large language models (LLMs) is becoming increasingly important due to regulatory compliance, copyright protection, and privacy concerns. However, a key challenge in LLM unlearning is unintended forgetting, where the removal of specific data inadvertently impairs the utility of the model and its retention of valuable, desired information. While prior work has primarily focused on architectural innovations, the influence of data-level factors on unlearning performance remains underexplored. As a result, existing methods often suffer from degraded retention when forgetting high-impact data. To address this, we propose GUARD-a novel framework for Guided Unlearning And Retention via Data attribution. At its core, GUARD introduces a lightweight proxy data attribution metric tailored for LLM unlearning, which quantifies the "alignment" between the forget and retain sets while remaining computationally efficient. Building on this, we design a novel unlearning objective that assigns adaptive, nonuniform unlearning weights to samples, inversely proportional to their proxy attribution scores. Through such a reallocation of unlearning power, GUARD mitigates unintended losses in retention. We provide rigorous theoretical guarantees that GUARD significantly enhances retention while maintaining forgetting metrics comparable to prior methods. Extensive experiments on the TOFU benchmark across multiple LLM architectures demonstrate that GUARD substantially improves utility preservation while ensuring effective unlearning. Notably, GUARD reduces utility sacrifice on the Retain Set by up to 194.92% in terms of Truth Ratio when forgetting 10% of the training data.

[Arxiv](https://arxiv.org/abs/2506.10946)