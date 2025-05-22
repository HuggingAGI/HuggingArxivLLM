# 提升 LLM 的安全对齐：借助安全表示排序

发布时间：2025年05月21日

`LLM应用` `模型安全` `内容安全`

> Advancing LLM Safe Alignment with Safety Representation Ranking

# 摘要

> 大型语言模型 (LLMs) 在各种任务中取得了里程碑式的成功，但其生成有害内容的潜在风险引发了重大的安全担忧。现有的安全评估方法通常直接作用于文本响应，忽视了模型内部表示中蕴含的丰富信息。本文提出了一种名为 Safety Representation Ranking (SRR) 的基于列表的排名框架，该框架利用 LLM 自身的隐藏状态来选择安全的响应。SRR 通过中间的 Transformer 表示对指令和候选完成进行编码，并通过一个轻量级的基于相似性的评分器对候选进行排序。我们的方法直接利用内部模型状态和列表级别的监督来捕捉微妙的安全信号。实验结果表明，SRR 显著提高了对对抗性提示的鲁棒性。我们的代码将在发表后开源。

> The rapid advancement of large language models (LLMs) has demonstrated milestone success in a variety of tasks, yet their potential for generating harmful content has raised significant safety concerns. Existing safety evaluation approaches typically operate directly on textual responses, overlooking the rich information embedded in the model's internal representations. In this paper, we propose Safety Representation Ranking (SRR), a listwise ranking framework that selects safe responses using hidden states from the LLM itself. SRR encodes both instructions and candidate completions using intermediate transformer representations and ranks candidates via a lightweight similarity-based scorer. Our approach directly leverages internal model states and supervision at the list level to capture subtle safety signals. Experiments across multiple benchmarks show that SRR significantly improves robustness to adversarial prompts. Our code will be available upon publication.

[Arxiv](https://arxiv.org/abs/2505.15710)