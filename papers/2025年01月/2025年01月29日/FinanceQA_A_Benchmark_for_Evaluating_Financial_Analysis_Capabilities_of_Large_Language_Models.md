# FinanceQA: 评估大型语言模型金融分析能力的基准

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要讨论了LLMs在金融分析任务中的表现，并提出了一个测试套件FinanceQA来评估LLMs在这些任务中的能力。论文还提到了使用OpenAI的微调API进行实验，这表明论文关注的是如何将LLMs应用于特定的金融分析任务，而不是理论上的LLM研究或Agent、RAG等方向。因此，将其分类为LLM应用是合适的。` `投资分析`

> FinanceQA: A Benchmark for Evaluating Financial Analysis Capabilities of Large Language Models

# 摘要

> FinanceQA 是一个测试套件，用于评估 LLMs 在复杂数值金融分析任务中的表现，这些任务模拟了现实世界的投资工作。尽管近期有所进展，但当前 LLMs 在模拟对冲基金、私募股权公司、投资银行等金融机构的实际任务中，失败率仍高达 60%。主要挑战包括手动扩展指标、遵守标准会计和企业估值惯例，以及在信息不完整的情况下进行分析——尤其是在需要生成假设的多步骤任务中。这一性能差距揭示了现有 LLM 能力与专业金融分析需求之间的脱节，而当前的测试架构未能充分测试这些需求。结果表明，需要更高质量的训练数据来支持此类任务，我们使用 OpenAI 的微调 API 进行了实验。FinanceQA 已在 [此链接](https://huggingface.co/datasets/AfterQuery/FinanceQA) 公开发布。

> FinanceQA is a testing suite that evaluates LLMs' performance on complex numerical financial analysis tasks that mirror real-world investment work. Despite recent advances, current LLMs fail to meet the strict accuracy requirements of financial institutions, with models failing approximately 60% of realistic tasks that mimic on-the-job analyses at hedge funds, private equity firms, investment banks, and other financial institutions. The primary challenges include hand-spreading metrics, adhering to standard accounting and corporate valuation conventions, and performing analysis under incomplete information - particularly in multi-step tasks requiring assumption generation. This performance gap highlights the disconnect between existing LLM capabilities and the demands of professional financial analysis that are inadequately tested by current testing architectures. Results show that higher-quality training data is needed to support such tasks, which we experiment with using OpenAI's fine-tuning API. FinanceQA is publicly released at [this https URL](https://huggingface.co/datasets/AfterQuery/FinanceQA).

[Arxiv](https://arxiv.org/abs/2501.18062)