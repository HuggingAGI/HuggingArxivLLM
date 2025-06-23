# 基于自我批判的好奇心机制优化——通过上下文学习提升大型语言模型的诚实性与帮助性

发布时间：2025年06月19日

`LLM应用

论文摘要：大型语言模型（LLMs）在多种自然语言任务中表现卓越。然而，生成始终诚实且有帮助的输出仍是待解决的难题。本文从两个互补方向入手：一方面，对 OpenAI、Meta 和 Google 等公司开发的十种主流 LLMs 进行全面基准测试；另一方面，提出一种新型提示策略——自我批判引导的好奇心精进提示策略。该策略通过两个轻量级步骤（自我批判与精进）让模型在无需额外训练的情况下实现自我优化。实验结果表明，该方法在 HONESET 数据集上显著提升了所有模型的表现。通过 GPT-4o 评估的 H²（诚实与 helpfulness）框架显示，该方法使低质量回应减少，高质量回应增加，并在所有评估模型中实现了 1.4% 到 4.3% 的 H² 评分提升。这证明了结构化自我精进策略在提升 LLMs 输出可信度方面的有效性。

LLM应用` `人工智能`

> Self-Critique-Guided Curiosity Refinement: Enhancing Honesty and Helpfulness in Large Language Models via In-Context Learning

# 摘要

> 大型语言模型（LLMs）在多种自然语言任务中表现卓越。然而，生成始终诚实且有帮助的输出仍是待解决的难题。本文从两个互补方向入手：一方面，对 OpenAI、Meta 和 Google 等公司开发的十种主流 LLMs 进行全面基准测试；另一方面，提出一种新型提示策略——自我批判引导的好奇心精进提示策略。该策略通过两个轻量级步骤（自我批判与精进）让模型在无需额外训练的情况下实现自我优化。
实验结果表明，该方法在 HONESET 数据集上显著提升了所有模型的表现。通过 GPT-4o 评估的 H²（诚实与 helpfulness）框架显示，该方法使低质量回应减少，高质量回应增加，并在所有评估模型中实现了 1.4% 到 4.3% 的 H² 评分提升。这证明了结构化自我精进策略在提升 LLMs 输出可信度方面的有效性。


> Large language models (LLMs) have demonstrated robust capabilities across various natural language tasks. However, producing outputs that are consistently honest and helpful remains an open challenge. To overcome this challenge, this paper tackles the problem through two complementary directions. It conducts a comprehensive benchmark evaluation of ten widely used large language models, including both proprietary and open-weight models from OpenAI, Meta, and Google. In parallel, it proposes a novel prompting strategy, self-critique-guided curiosity refinement prompting. The key idea behind this strategy is enabling models to self-critique and refine their responses without additional training. The proposed method extends the curiosity-driven prompting strategy by incorporating two lightweight in-context steps including self-critique step and refinement step.
  The experiment results on the HONESET dataset evaluated using the framework $\mathrm{H}^2$ (honesty and helpfulness), which was executed with GPT-4o as a judge of honesty and helpfulness, show consistent improvements across all models. The approach reduces the number of poor-quality responses, increases high-quality responses, and achieves relative gains in $\mathrm{H}^2$ scores ranging from 1.4% to 4.3% compared to curiosity-driven prompting across evaluated models. These results highlight the effectiveness of structured self-refinement as a scalable and training-free strategy to improve the trustworthiness of LLMs outputs.

[Arxiv](https://arxiv.org/abs/2506.16064)