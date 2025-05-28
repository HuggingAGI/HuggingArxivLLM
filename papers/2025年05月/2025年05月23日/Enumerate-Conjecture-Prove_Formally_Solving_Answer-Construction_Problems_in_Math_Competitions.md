# 枚举-猜想-证明：系统解决数学竞赛中的答题构造问题

发布时间：2025年05月23日

`LLM应用` `数学竞赛` `数学推理`

> Enumerate-Conjecture-Prove: Formally Solving Answer-Construction Problems in Math Competitions

# 摘要

> 数学推理是人工智能的核心，支撑着教育、程序验证和研究级数学发现等领域的应用。数学竞赛尤其提出了两类具有挑战性的问题：定理证明，需要对所陈述的结论进行严格证明；以及答案构造，涉及假设和对数学对象的形式验证。大型语言模型（LLMs）能够有效地生成创意候选答案，但在形式验证方面表现较弱，而符号验证器则能确保严谨性，却无法高效处理创意猜想生成。我们引入了枚举-猜想-证明（ECP）框架，这是一种模块化的神经符号方法，整合了基于LLM的枚举和模式驱动的猜想生成，与形式化定理证明相结合。我们提出了ConstructiveBench，一个包含3,431个来自各种数学竞赛的答案构造问题的数据集，这些问题都有经过验证的Lean形式化表达。在ConstructiveBench数据集上，ECP将答案构造的准确率从Chain-of-Thought（CoT）基线的14.54%提升到了45.06%，使用gpt-4.1-mini模型。此外，结合ECP生成的答案，最先进的DeepSeek-Prover-V2-7B模型在Lean中为3,431个构造性问题中的858个生成了正确的证明，准确率为25.01%，而仅使用符号验证器的基线准确率为9.86%。我们的代码和数据集分别在GitHub和HuggingFace上公开可用。

> Mathematical reasoning lies at the heart of artificial intelligence, underpinning applications in education, program verification, and research-level mathematical discovery. Mathematical competitions, in particular, present two challenging problem types: theorem-proving, requiring rigorous proofs of stated conclusions, and answer-construction, involving hypothesizing and formally verifying mathematical objects. Large Language Models (LLMs) effectively generate creative candidate answers but struggle with formal verification, while symbolic provers ensure rigor but cannot efficiently handle creative conjecture generation. We introduce the Enumerate-Conjecture-Prove (ECP) framework, a modular neuro-symbolic method integrating LLM-based enumeration and pattern-driven conjecturing with formal theorem proving. We present ConstructiveBench, a dataset of 3,431 answer-construction problems in various math competitions with verified Lean formalizations. On the ConstructiveBench dataset, ECP improves the accuracy of answer construction from the Chain-of-Thought (CoT) baseline of 14.54% to 45.06% with the gpt-4.1-mini model. Moreover, combining with ECP's constructed answers, the state-of-the-art DeepSeek-Prover-V2-7B model generates correct proofs for 858 of the 3,431 constructive problems in Lean, achieving 25.01% accuracy, compared to 9.86% for symbolic-only baselines. Our code and dataset are publicly available at GitHub and HuggingFace, respectively.

[Arxiv](https://arxiv.org/abs/2505.18492)