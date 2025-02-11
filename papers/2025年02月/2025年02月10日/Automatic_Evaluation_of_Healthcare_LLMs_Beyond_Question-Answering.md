# 医疗LLMs的自动评估：超越问答任务

发布时间：2025年02月10日

`LLM理论` `评估体系`

> Automatic Evaluation of Healthcare LLMs Beyond Question-Answering

# 摘要

> 当前的大型语言模型（LLMs）基准测试主要基于开放性或封闭性问答评估，避免了人工劳动的介入。封闭式评估虽能衡量回答的事实性，却缺乏表达性；而开放性评估虽能捕捉模型生成 discourse 的能力，却更难评估正确性。这两种方法常被单独或结合使用，但它们之间的关系仍不明确。本研究聚焦医疗领域，事实性和 discourse 在此同等重要。我们推出了一套全面的医疗 LLM 评估体系，深入探究开放性和封闭性基准与指标间的关联。研究发现现有方法存在盲点和重叠。作为更新的合理性验证，我们发布了一个新的医疗基准--CareQA--，包含开放性和封闭性变体。最后，我们提出了一种用于开放性评估的新指标--Relaxed Perplexity--以缓解现有限制。

> Current Large Language Models (LLMs) benchmarks are often based on open-ended or close-ended QA evaluations, avoiding the requirement of human labor. Close-ended measurements evaluate the factuality of responses but lack expressiveness. Open-ended capture the model's capacity to produce discourse responses but are harder to assess for correctness. These two approaches are commonly used, either independently or together, though their relationship remains poorly understood. This work is focused on the healthcare domain, where both factuality and discourse matter greatly. It introduces a comprehensive, multi-axis suite for healthcare LLM evaluation, exploring correlations between open and close benchmarks and metrics. Findings include blind spots and overlaps in current methodologies. As an updated sanity check, we release a new medical benchmark--CareQA--, with both open and closed variants. Finally, we propose a novel metric for open-ended evaluations --Relaxed Perplexity-- to mitigate the identified limitations.

[Arxiv](https://arxiv.org/abs/2502.06666)