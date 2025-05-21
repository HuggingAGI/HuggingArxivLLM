# AI自由职业者能否一较高下？衡量收入、可靠性和大规模任务的成功率

发布时间：2025年05月16日

`LLM应用` `自由职业软件开发` `数据分析`

> Can AI Freelancers Compete? Benchmarking Earnings, Reliability, and Task Success at Scale

# 摘要

> # 研究探索
本研究深入探索了大型语言模型（LLMs）作为自主代理在现实世界任务中的应用，涵盖自由职业软件开发等场景。我们推出了一项全新基准测试，旨在评估LLMs在基于经济数据的自由职业编程与数据分析任务中的实际表现。

# 基准构建
我们借助Kaggle自由职业者数据集中的职位发布信息，创建合成任务来构建评估基准。所有任务价格均以美元为单位标准化（固定项目价格中位数约250美元，平均为306美元）。每个任务不仅配有结构化的输入-输出测试用例，还设有预估价格标签，从而实现自动化正确性验证和性能货币化评估。

# 方法创新
我们的研究灵感源自OpenAI近期推出的SWE-Lancer基准（涵盖1,400个真实Upwork任务，总价值100万美元）。然而，我们通过采用可程序化测试的任务和预测价格值，使评估过程更加简洁高效，确保了基准测试的高度可扩展性和可重复性。

# 模型评估
在这一基准测试中，我们对当前四大主流LLMs进行了全面评估，包括Claude 3.5 Haiku、GPT-4o-mini、Qwen 2.5和Mistral。评估指标涵盖任务成功率、测试用例通过率以及“自由职业收入”总额（即解决任务价格总和）。

# 实验结果
实验数据显示，Claude 3.5 Haiku表现最为突出，实现约152万美元的收入，紧随其后的是GPT-4o-mini（149万美元）、Qwen 2.5（133万美元）和Mistral（70万美元）。进一步分析发现，性能最强的模型不仅解决了最多的任务，而且在任何项目上几乎从未完全失败。

# 结果解读
本研究不仅揭示了AI作为自由职业开发人员的可行性，还深入探讨了自动化基准方法的优势与局限性。更重要的是，我们发现结构化任务与现实世界自由职业工作的真正复杂性之间仍存在显著的性能差距，这一发现为未来研究提供了重要方向。

> This study explores Large Language Models (LLMs) as autonomous agents for real-world tasks, including freelance software development. This work presents a new benchmark that evaluates LLMs on freelance programming and data analysis tasks derived from economic data. We construct the benchmark using synthetic tasks created from a Kaggle Freelancer dataset of job postings, with all job prices standardized to USD (median fixed-project price around $250, and an average of $306). Each task is accompanied by structured input-output test cases and an estimated price tag, enabling automated correctness checking and a monetary performance valuation. This approach is inspired by OpenAI's recent SWE-Lancer benchmark (1,400 real Upwork tasks worth $1M total). Still, our framework simplifies evaluation using programmatically testable tasks and predicted price values, making it highly scalable and repeatable. On this benchmark, we evaluate four modern LLMs - Claude 3.5 Haiku, GPT-4o-mini, Qwen 2.5, and Mistral. We report each model's accuracy (task success rate and test-case pass rate) and the total "freelance earnings" it achieves (sum of prices of solved tasks). Our results show that Claude 3.5 Haiku performs best, earning approximately $1.52 million USD, followed closely by GPT-4o-mini at $1.49 million, then Qwen 2.5 ($1.33M) and Mistral ($0.70M). We analyze the distribution of errors per task and observe that the strongest models solve the most tasks and rarely fail completely on any project. We discuss the implications of these results for the feasibility of AI as a freelance developer, the advantages and limitations of our automated benchmark approach, and the gap between performance on structured tasks versus the true complexity of real-world freelance jobs.

[Arxiv](https://arxiv.org/abs/2505.13511)