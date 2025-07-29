# 任务嵌入的软注入方法在性能上超越了基于提示的上下文学习

发布时间：2025年07月28日

`LLM应用` `人工智能`

> Soft Injection of Task Embeddings Outperforms Prompt-Based In-Context Learning

# 摘要

> 上下文学习（ICL）让大型语言模型（LLMs）无需更新参数，只需通过在提示中设置输入-输出示例即可执行任务。尽管被广泛应用，但使用多个示例进行提示是否是最有效和最高效的任务信息传递方式仍不明确。为此，我们提出了任务嵌入的软注入方法。该方法只需通过少量的ICL提示构建任务嵌入一次，并在推理过程中重复使用。软注入通过预先优化的混合参数（称为软头选择参数）将任务嵌入与注意力头激活进行柔和混合。此方法不仅无需在提示中进行演示即可执行所需任务，还在减少推理时内存使用和计算成本的同时，显著超越现有ICL方法。我们对57项任务和12种LLMs进行了全面评估，涵盖4个模型家族，规模从4B到70B。在57项任务的平均结果中，我们的方法在12种LLMs上优于10-shot ICL，提升幅度为10.1%-13.9%。额外分析表明，我们的方法还可作为分析注意力头任务相关性的有用工具，揭示了由我们的方法选择的任务相关头位置在相似任务间具有迁移性，但在不相似任务间不具备迁移性——突显了头功能的特定任务性质。我们的软注入方法开启了一种新范式，通过将任务条件从提示空间转移到激活空间，从而减少提示长度并提升任务性能。


> In-Context Learning (ICL) enables Large Language Models (LLMs) to perform tasks by conditioning on input-output examples in the prompt, without requiring any update in model parameters. While widely adopted, it remains unclear whether prompting with multiple examples is the most effective and efficient way to convey task information. In this work, we propose Soft Injection of task embeddings. The task embeddings are constructed only once using few-shot ICL prompts and repeatedly used during inference. Soft injection is performed by softly mixing task embeddings with attention head activations using pre-optimized mixing parameters, referred to as soft head-selection parameters. This method not only allows a desired task to be performed without in-prompt demonstrations but also significantly outperforms existing ICL approaches while reducing memory usage and compute cost at inference time. An extensive evaluation is performed across 57 tasks and 12 LLMs, spanning four model families of sizes from 4B to 70B. Averaged across 57 tasks, our method outperforms 10-shot ICL by 10.1%-13.9% across 12 LLMs. Additional analyses show that our method also serves as an insightful tool for analyzing task-relevant roles of attention heads, revealing that task-relevant head positions selected by our method transfer across similar tasks but not across dissimilar ones -- underscoring the task-specific nature of head functionality. Our soft injection method opens a new paradigm for reducing prompt length and improving task performance by shifting task conditioning from the prompt space to the activation space.

[Arxiv](https://arxiv.org/abs/2507.20906)