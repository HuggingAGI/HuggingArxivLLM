# 你的诚实回答是什么？利用引导向量为LLM评估者提供诚实的替代方案

发布时间：2025年05月23日

`LLM理论` `人工智能` `安全评估`

> But what is your honest answer? Aiding LLM-judges with honest alternatives using steering vectors

# 摘要

> 近期对大型语言模型 (LLMs) 的安全评估显示，许多模型存在不诚实行为，例如谄媚。然而，现有诚实基准仅关注事实知识或显式有害行为，并依赖外部裁判，这些裁判往往难以察觉不太明显的不诚实行为。本研究引入了一个新框架——Judge Using Safety-Steered Alternatives (JUSSA)，该框架利用基于单个样本训练的引导向量，促使模型生成更诚实的回答，从而帮助LLM裁判检测不诚实行为。为了验证我们的框架，我们构建了一个新的操控数据集，其中包含专门设计的提示，旨在引发欺骗性回答。实验结果表明，JUSSA使LLM裁判能够更准确地区分不诚实和良性回应，并帮助他们识别操纵行为的微妙实例。

> Recent safety evaluations of Large Language Models (LLMs) show that many models exhibit dishonest behavior, such as sycophancy. However, most honesty benchmarks focus exclusively on factual knowledge or explicitly harmful behavior and rely on external judges, which are often unable to detect less obvious forms of dishonesty. In this work, we introduce a new framework, Judge Using Safety-Steered Alternatives (JUSSA), which utilizes steering vectors trained on a single sample to elicit more honest responses from models, helping LLM-judges in the detection of dishonest behavior. To test our framework, we introduce a new manipulation dataset with prompts specifically designed to elicit deceptive responses. We find that JUSSA enables LLM judges to better differentiate between dishonest and benign responses, and helps them identify subtle instances of manipulative behavior.

[Arxiv](https://arxiv.org/abs/2505.17760)