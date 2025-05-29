# R2R：通过小-大模型令牌路由高效地导航不同推理路径

发布时间：2025年05月27日

`LLM应用` `人工智能` `模型优化`

> R2R: Efficiently Navigating Divergent Reasoning Paths with Small-Large Model Token Routing

# 摘要

> 大型语言模型 (LLMs) 以巨大的推理开销为代价，展现了令人惊叹的推理能力，但这也带来了严峻的部署挑战。蒸馏后的小型语言模型 (SLMs) 虽然效率大增，却因无法复制 LLMs 的推理路径而导致性能下降。幸运的是，我们发现仅有少量 token 真的造成了 LLMs 和 SLMs 推理路径的分歧。绝大多数生成的 token 要么完全相同，要么仅有中性差异，例如缩写或表达方式的细微变化。基于这一发现，我们提出了 **Roads to Rome (R2R)**，这是一种神经 token 路由方法，仅针对这些关键的、导致路径分歧的 token 选择性地使用 LLMs，而将大部分 token 的生成任务交由 SLM 完成。我们还开发了一条自动数据生成管道，用于识别分歧 token 并生成 token 级别的路由标签，以训练轻量级路由模型。我们将 R2R 应用于 DeepSeek 家族的 R1-1.5B 和 R1-32B 模型，并在具有挑战性的数学、编码和问答基准测试中进行评估。R2R 的平均激活参数规模为 5.6B，其平均准确率比 R1-7B 高出 1.6 倍，甚至超越了 R1-14B 模型的表现。与 R1-32B 相比，R2R 在保持相近性能的同时，实现了 2.8 倍的时钟速度提升，推动了测试时间缩放效率的帕累托前沿。我们的代码可在 https://github.com/thu-nics/R2R 获取。

> Large Language Models (LLMs) achieve impressive reasoning capabilities at the cost of substantial inference overhead, posing substantial deployment challenges. Although distilled Small Language Models (SLMs) significantly enhance efficiency, their performance suffers as they fail to follow LLMs' reasoning paths. Luckily, we reveal that only a small fraction of tokens genuinely diverge reasoning paths between LLMs and SLMs. Most generated tokens are either identical or exhibit neutral differences, such as minor variations in abbreviations or expressions. Leveraging this insight, we introduce **Roads to Rome (R2R)**, a neural token routing method that selectively utilizes LLMs only for these critical, path-divergent tokens, while leaving the majority of token generation to the SLM. We also develop an automatic data generation pipeline that identifies divergent tokens and generates token-level routing labels to train the lightweight router. We apply R2R to combine R1-1.5B and R1-32B models from the DeepSeek family, and evaluate on challenging math, coding, and QA benchmarks. With an average activated parameter size of 5.6B, R2R surpasses the average accuracy of R1-7B by 1.6x, outperforming even the R1-14B model. Compared to R1-32B, it delivers a 2.8x wall-clock speedup with comparable performance, advancing the Pareto frontier of test-time scaling efficiency. Our code is available at https://github.com/thu-nics/R2R.

[Arxiv](https://arxiv.org/abs/2505.21600)