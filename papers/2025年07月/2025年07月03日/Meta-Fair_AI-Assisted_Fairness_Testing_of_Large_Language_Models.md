# Meta-Fair：AI辅助的大型语言模型公平性测试

发布时间：2025年07月03日

`LLM应用` `人工智能` `测试评估`

> Meta-Fair: AI-Assisted Fairness Testing of Large Language Models

# 摘要

> 公平性--即不存在无理由的偏见--是人工智能 (AI) 系统开发的核心原则，但其评估和实施仍然面临挑战。现有大型语言模型 (LLMs) 的公平性测试方法通常依赖人工评估、固定模板、确定性启发式方法和精选数据集，这使得它们资源消耗大且难以扩展。本研究旨在为一种新型自动化 LLM 公平性测试方法奠定基础，减少对领域特定资源的依赖，同时扩大现有方法的适用范围。

我们的方法 Meta-Fair 基于两大核心理念。首先，采用变形测试通过观察模型输出对输入提示的受控修改的响应变化来揭示偏见，这些修改由变形关系 (MRs) 定义。其次，我们提出充分利用 LLM 的能力，实现测试用例生成和输出评估，利用其生成多样化输入和有效分类输出的优势。该提案还得到了三个开源工具的支持，这些工具支持基于 LLM 的测试用例生成、执行和评估。

我们报告了涉及 12 个预训练 LLM、14 个 MR、5 个偏见维度和 7,900 个自动生成测试用例的多个实验结果。结果显示，Meta-Fair 在揭示 LLM 偏见方面表现优异，平均精度达到 92%，并在 29% 的执行中揭示了有偏见的行为。此外，LLMs 证明了作为可靠和一致评估器的能力，最佳模型实现了高达 0.79 的 F1 分数。尽管非确定性会影响一致性，但通过仔细设计 MR 可以有效缓解这些影响。

尽管仍需克服挑战以确保更广泛的适用性，但结果表明，我们朝着 LLM 测试前所未有的自动化水平迈出了有希望的一步。

> Fairness--the absence of unjustified bias--is a core principle in the development of Artificial Intelligence (AI) systems, yet it remains difficult to assess and enforce. Current approaches to fairness testing in large language models (LLMs) often rely on manual evaluation, fixed templates, deterministic heuristics, and curated datasets, making them resource-intensive and difficult to scale. This work aims to lay the groundwork for a novel, automated method for testing fairness in LLMs, reducing the dependence on domain-specific resources and broadening the applicability of current approaches. Our approach, Meta-Fair, is based on two key ideas. First, we adopt metamorphic testing to uncover bias by examining how model outputs vary in response to controlled modifications of input prompts, defined by metamorphic relations (MRs). Second, we propose exploiting the potential of LLMs for both test case generation and output evaluation, leveraging their capability to generate diverse inputs and classify outputs effectively. The proposal is complemented by three open-source tools supporting LLM-driven generation, execution, and evaluation of test cases. We report the findings of several experiments involving 12 pre-trained LLMs, 14 MRs, 5 bias dimensions, and 7.9K automatically generated test cases. The results show that Meta-Fair is effective in uncovering bias in LLMs, achieving an average precision of 92% and revealing biased behaviour in 29% of executions. Additionally, LLMs prove to be reliable and consistent evaluators, with the best-performing models achieving F1-scores of up to 0.79. Although non-determinism affects consistency, these effects can be mitigated through careful MR design. While challenges remain to ensure broader applicability, the results indicate a promising path towards an unprecedented level of automation in LLM testing.

[Arxiv](https://arxiv.org/abs/2507.02533)