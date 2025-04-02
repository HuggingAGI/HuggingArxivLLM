# # m1: 探索大型语言模型在医疗推理中进行测试时缩放的潜力

发布时间：2025年04月01日

`LLM应用` `大型语言模型`

> m1: Unleash the Potential of Test-Time Scaling for Medical Reasoning with Large Language Models

# 摘要

> 测试时缩放作为一种强大的技术手段，能够有效提升大型语言模型的推理能力。然而，它在医学推理中的效果尚不明确，因为医学领域在知识表示和决策过程上与数学任务有着本质的不同。本文首次全面研究了测试时缩放在医学推理中的应用，并提出了一种简单而有效的m1方法，能够在推理过程中提升模型的医学推理能力。我们在多种医学任务上的评估表明，测试时缩放能够持续提升医学推理性能，使100亿参数以下的轻量化微调模型达到新的最优水平，而我们的320亿参数模型甚至可以与之前700亿规模的医学LLM相媲美。然而，我们发现存在一个最优的推理代币预算，约为4K，超出这一预算可能会因过度思考而导致性能下降。通过迭代提示扩展测试时计算的预算强制方法，可以帮助模型复查答案，但并不一定能提升整体医学问答表现，有时甚至会导致原本正确的回答出现错误。通过逐一案例分析，我们发现医学知识的不足是限制测试时缩放进一步提升性能的关键瓶颈。我们发现，增加数据规模、提升数据质量以及扩大模型容量能够持续增强医学知识的根基，从而推动性能的持续改进，尤其是在小型模型达到性能瓶颈的困难医学基准测试中。这些发现突显了医学推理与数学推理在大型语言模型中的根本差异，强调了除增加推理深度外，丰富医学知识对于充分发挥测试时缩放优势的重要性。


> Test-time scaling has emerged as a powerful technique for enhancing the reasoning capabilities of large language models. However, its effectiveness in medical reasoning remains uncertain, as the medical domain fundamentally differs from mathematical tasks in terms of knowledge representation and decision-making processes. In this paper, we provide the first comprehensive investigation of test-time scaling for medical reasoning and present m1, a simple yet effective approach that increases a model's medical reasoning capability at inference. Our evaluation across diverse medical tasks demonstrates that test-time scaling consistently enhances medical reasoning, enabling lightweight fine-tuned models under 10B parameters to establish new state-of-the-art performance, while our 32B model rivals previous 70B-scale medical LLMs. However, we identify an optimal reasoning token budget of approximately 4K, beyond which performance may degrade due to overthinking. Budget forcing, which extends test-time computation through iterative prompts, helps models double-check answers but does not necessarily improve the overall medical QA performance and, in some cases, even introduces errors into previously correct responses. Our case-by-case analysis identifies insufficient medical knowledge as a key bottleneck that prevents further performance gains through test-time scaling. We find that increasing data scale, improving data quality, and expanding model capacity consistently enhance medical knowledge grounding, enabling continued performance improvements, particularly on challenging medical benchmarks where smaller models reach saturation. These findings underscore fundamental differences between medical and mathematical reasoning in LLMs, highlighting that enriched medical knowledge, other than increased reasoning depth alone, is essential for realizing the benefits of test-time scaling.

[Arxiv](https://arxiv.org/abs/2504.00869)