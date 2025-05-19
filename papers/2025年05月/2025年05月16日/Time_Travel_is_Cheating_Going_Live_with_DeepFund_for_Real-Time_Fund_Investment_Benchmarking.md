# 时间旅行是作弊：实时基金投资基准测试，与 DeepFund 一起实现

发布时间：2025年05月16日

`LLM应用

论文摘要：大型语言模型（LLMs）在财务报告总结、 earnings call 文本分析和资产分类等金融任务中表现突出。然而，其在复杂基金投资中的实际效能仍未得到充分评估。现有评估方法依赖历史回测，这使LLMs能够利用训练数据中的未来信息，导致信息泄露和过于乐观的性能评估。为解决这一问题，我们开发了DeepFund实时基金基准工具，旨在严格评估LLM在实时市场环境中的表现。DeepFund采用多智能体架构，连接模型预训练截止时间之后发布的实时股票数据，确保公平无泄露的评估环境。对全球领先机构的九款旗舰LLMs进行多维度投资测试——包括股票分析、投资决策、投资组合管理和风险控制——揭示了显著的实际挑战。即使是DeepSeek-V3和Claude-3.7-Sonnet等前沿模型，在DeepFund实时环境中也出现净亏损，凸显了当前LLMs在主动基金管理中的局限性。我们的代码可在GitHub上获取。

LLM应用`

> Time Travel is Cheating: Going Live with DeepFund for Real-Time Fund Investment Benchmarking

# 摘要

> 大型语言模型（LLMs）在财务报告总结、 earnings call 文本分析和资产分类等金融任务中表现突出。然而，其在复杂基金投资中的实际效能仍未得到充分评估。现有评估方法依赖历史回测，这使LLMs能够利用训练数据中的未来信息，导致信息泄露和过于乐观的性能评估。为解决这一问题，我们开发了DeepFund实时基金基准工具，旨在严格评估LLM在实时市场环境中的表现。DeepFund采用多智能体架构，连接模型预训练截止时间之后发布的实时股票数据，确保公平无泄露的评估环境。对全球领先机构的九款旗舰LLMs进行多维度投资测试——包括股票分析、投资决策、投资组合管理和风险控制——揭示了显著的实际挑战。即使是DeepSeek-V3和Claude-3.7-Sonnet等前沿模型，在DeepFund实时环境中也出现净亏损，凸显了当前LLMs在主动基金管理中的局限性。我们的代码可在GitHub上获取。

> Large Language Models (LLMs) have demonstrated notable capabilities across financial tasks, including financial report summarization, earnings call transcript analysis, and asset classification. However, their real-world effectiveness in managing complex fund investment remains inadequately assessed. A fundamental limitation of existing benchmarks for evaluating LLM-driven trading strategies is their reliance on historical back-testing, inadvertently enabling LLMs to "time travel"-leveraging future information embedded in their training corpora, thus resulting in possible information leakage and overly optimistic performance estimates. To address this issue, we introduce DeepFund, a live fund benchmark tool designed to rigorously evaluate LLM in real-time market conditions. Utilizing a multi-agent architecture, DeepFund connects directly with real-time stock market data-specifically data published after each model pretraining cutoff-to ensure fair and leakage-free evaluations. Empirical tests on nine flagship LLMs from leading global institutions across multiple investment dimensions-including ticker-level analysis, investment decision-making, portfolio management, and risk control-reveal significant practical challenges. Notably, even cutting-edge models such as DeepSeek-V3 and Claude-3.7-Sonnet incur net trading losses within DeepFund real-time evaluation environment, underscoring the present limitations of LLMs for active fund management. Our code is available at https://github.com/HKUSTDial/DeepFund.

[Arxiv](https://arxiv.org/abs/2505.11065)