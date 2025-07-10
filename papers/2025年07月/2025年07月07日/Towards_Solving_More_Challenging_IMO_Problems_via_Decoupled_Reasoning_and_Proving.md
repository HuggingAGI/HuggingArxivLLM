# 解决更具挑战性的IMO难题：分离式推理与证明的结合

发布时间：2025年07月07日

`LLM应用` `人工智能`

> Towards Solving More Challenging IMO Problems via Decoupled Reasoning and Proving

# 摘要

> 形式语言中的自动定理证明（ATP）是人工智能领域的重要挑战。尽管大型语言模型（LLMs）推动了显著进步，但其非正式推理能力与正式证明性能之间仍存在显著差距。近期研究表明，在PutnamBench等基准测试中，非正式推理准确率超80%，而正式证明成功率不足8%。当前最先进的证明器通过结合推理与证明，并采用惩罚深入推理、支持浅层策略式方法的训练范式，导致这一差距持续存在。我们提出了一种新颖的解耦框架，将高层次推理与低层次证明生成分离。我们的方法采用两个专用模型：功能强大的通用推理器生成多样化战略性子目标引理，以及高效验证器严格验证这些引理。这种模块化设计释放了模型的全部推理潜力，规避了端到端训练的弊端。我们在一组极具挑战性的2000年后IMO问题上评估了我们的方法，这些问题尚未有开源证明器成功案例。我们的框架成功解决了其中5个问题，朝着应对极其困难的数学挑战的自动化推理迈出重要一步。为促进未来研究，我们发布了针对广泛IMO问题生成和验证的引理的完整数据集，可在https://tencent-imo.github.io/获取。


> Automated Theorem Proving (ATP) in formal languages is a foundational challenge for AI. While Large Language Models (LLMs) have driven remarkable progress, a significant gap remains between their powerful informal reasoning capabilities and their weak formal proving performance. Recent studies show that the informal accuracy exceeds 80% while formal success remains below 8% on benchmarks like PutnamBench. We argue this gap persists because current state-of-the-art provers, by tightly coupling reasoning and proving, are trained with paradigms that inadvertently punish deep reasoning in favor of shallow, tactic-based strategies. To bridge this fundamental gap, we propose a novel framework that decouples high-level reasoning from low-level proof generation. Our approach utilizes two distinct, specialized models: a powerful, general-purpose Reasoner to generate diverse, strategic subgoal lemmas, and an efficient Prover to rigorously verify them. This modular design liberates the model's full reasoning potential and bypasses the pitfalls of end-to-end training. We evaluate our method on a challenging set of post-2000 IMO problems, a problem set on which no prior open-source prover has reported success. Our decoupled framework successfully solves 5 of these problems, demonstrating a significant step towards automated reasoning on exceptionally difficult mathematical challenges. To foster future research, we release our full dataset of generated and verified lemmas for a wide range of IMO problems, available at https://tencent-imo.github.io/ .

[Arxiv](https://arxiv.org/abs/2507.06804)