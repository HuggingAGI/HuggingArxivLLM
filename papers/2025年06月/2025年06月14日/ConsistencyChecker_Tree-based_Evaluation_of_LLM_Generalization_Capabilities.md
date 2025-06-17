# 树基评估LLM泛化能力：一致性检查器

发布时间：2025年06月14日

`LLM理论` `机器翻译` `AI辅助编程`

> ConsistencyChecker: Tree-based Evaluation of LLM Generalization Capabilities

# 摘要

> 评估大型语言模型（LLMs）的一致性对于确保可靠性至关重要，特别是在人类与LLMs之间的复杂多步骤交互中。传统自洽性方法往往忽视细微的语义变化和自然语言中的功能性转变，这些变化可能在多次转换中累积。为了解决这一问题，我们提出了ConsistencyChecker，一个基于树的评估框架，旨在通过一系列可逆变换（包括机器翻译任务和AI辅助编程任务）来衡量一致性。在我们的框架中，节点代表不同的文本状态，而边则对应于逆操作对。动态生成的LLM基准测试确保了对模型泛化能力的公平评估，并消除了基准测试泄漏。一致性通过变换树不同深度上的相似性来量化。在来自不同家族和规模的八种模型上的实验表明，ConsistencyChecker能够区分不同模型的性能。值得注意的是，我们的完全不依赖WMT配对数据的一致性评分与WMT 2024自动排名密切相关（r > 0.7），证明了我们无基准测试方法的有效性。我们的实现可在以下链接获取：https://github.com/ulab-uiuc/consistencychecker。


> Evaluating consistency in large language models (LLMs) is crucial for ensuring reliability, particularly in complex, multi-step interactions between humans and LLMs. Traditional self-consistency methods often miss subtle semantic changes in natural language and functional shifts in code or equations, which can accumulate over multiple transformations. To address this, we propose ConsistencyChecker, a tree-based evaluation framework designed to measure consistency through sequences of reversible transformations, including machine translation tasks and AI-assisted programming tasks. In our framework, nodes represent distinct text states, while edges correspond to pairs of inverse operations. Dynamic and LLM-generated benchmarks ensure a fair assessment of the model's generalization ability and eliminate benchmark leakage. Consistency is quantified based on similarity across different depths of the transformation tree. Experiments on eight models from various families and sizes show that ConsistencyChecker can distinguish the performance of different models. Notably, our consistency scores-computed entirely without using WMT paired data-correlate strongly (r > 0.7) with WMT 2024 auto-ranking, demonstrating the validity of our benchmark-free approach. Our implementation is available at: https://github.com/ulab-uiuc/consistencychecker.

[Arxiv](https://arxiv.org/abs/2506.12376)