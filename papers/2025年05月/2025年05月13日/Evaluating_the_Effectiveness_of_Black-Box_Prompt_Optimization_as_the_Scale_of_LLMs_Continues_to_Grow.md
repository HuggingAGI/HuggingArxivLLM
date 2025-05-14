# # 评估随着LLM规模持续增长的黑盒提示优化有效性
随着大型语言模型规模的持续增长，评估黑盒提示优化的有效性。

发布时间：2025年05月13日

`LLM应用` `大型语言模型`

> Evaluating the Effectiveness of Black-Box Prompt Optimization as the Scale of LLMs Continues to Grow

# 摘要

> 黑盒提示优化方法已展现出作为一种有前景的策略，用于精炼输入提示，使其更好地与大型语言模型（LLMs）对齐，从而提升其任务性能。尽管这些方法已取得令人鼓舞的结果，但大多数研究和实验主要集中在规模较小的模型（例如7B、14B）或LLMs的早期版本（例如GPT-3.5）上。随着LLMs规模的持续扩大，如DeepSeek V3（671B），这些黑盒优化技术是否仍能为如此大规模的模型带来显著性能提升，仍是一个开放性问题。针对此问题，我们选取了三种知名的黑盒优化方法，并在大规模LLMs（DeepSeek V3和Gemini 2.0 Flash）上进行了测试，覆盖了四个NLU和NLG数据集。结果显示，这些黑盒提示优化方法在这些大规模LLMs上仅能带来有限的改进。此外，我们假设模型的规模是导致观察到的有限收益的主要因素。为了验证这一假设，我们在不同规模的LLMs（Qwen 2.5系列，从7B到72B）上进行了实验，发现了一个反向缩放规律：即随着模型规模的增加，黑盒优化方法的有效性逐渐减弱。

> Black-Box prompt optimization methods have emerged as a promising strategy for refining input prompts to better align large language models (LLMs), thereby enhancing their task performance. Although these methods have demonstrated encouraging results, most studies and experiments have primarily focused on smaller-scale models (e.g., 7B, 14B) or earlier versions (e.g., GPT-3.5) of LLMs. As the scale of LLMs continues to increase, such as with DeepSeek V3 (671B), it remains an open question whether these black-box optimization techniques will continue to yield significant performance improvements for models of such scale. In response to this, we select three well-known black-box optimization methods and evaluate them on large-scale LLMs (DeepSeek V3 and Gemini 2.0 Flash) across four NLU and NLG datasets. The results show that these black-box prompt optimization methods offer only limited improvements on these large-scale LLMs. Furthermore, we hypothesize that the scale of the model is the primary factor contributing to the limited benefits observed. To explore this hypothesis, we conducted experiments on LLMs of varying sizes (Qwen 2.5 series, ranging from 7B to 72B) and observed an inverse scaling law, wherein the effectiveness of black-box optimization methods diminished as the model size increased.

[Arxiv](https://arxiv.org/abs/2505.08303)