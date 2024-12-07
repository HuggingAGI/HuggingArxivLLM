# 借助思维代理蒸馏来解锁视频-LLM

发布时间：2024年12月02日

`Agent` `问答系统`

> Unlocking Video-LLM via Agent-of-Thoughts Distillation

# 摘要

> 这篇论文致力于解决视频问答（VideoQA）的难题，此任务通常需要多步推理以及对时空动态的深入理解。尽管大型视频语言模型在基准测试中表现出色，但其往往缺乏可解释性与时空基础。在本文中，我们提出了思维代理蒸馏（AoTD）这一方法，它通过将自动生成的思维链（CoTs）融入指令调整过程来强化模型。具体而言，我们借助基于代理的系统将复杂问题拆解为子任务，并运用专门的视觉模型加以解决，中间结果被视作推理链。我们还引入了利用大型语言模型（LLM）的验证机制，以保障生成的 CoTs 的可靠性。大量实验表明，AoTD 提升了多项选择和开放式基准测试的性能。

> This paper tackles the problem of video question answering (VideoQA), a task that often requires multi-step reasoning and a profound understanding of spatial-temporal dynamics. While large video-language models perform well on benchmarks, they often lack explainability and spatial-temporal grounding. In this paper, we propose Agent-of-Thoughts Distillation (AoTD), a method that enhances models by incorporating automatically generated Chain-of-Thoughts (CoTs) into the instruction-tuning process. Specifically, we leverage an agent-based system to decompose complex questions into sub-tasks, and address them with specialized vision models, the intermediate results are then treated as reasoning chains. We also introduce a verification mechanism using a large language model (LLM) to ensure the reliability of generated CoTs. Extensive experiments demonstrate that AoTD improves the performance on multiple-choice and open-ended benchmarks.

[Arxiv](https://arxiv.org/abs/2412.01694)