# # 引导LLM思考的预算指导策略
以预算指导掌控LLM的思考方向，实现更高效的思维引导。

发布时间：2025年06月16日

`LLM应用` `人工智能`

> Steering LLM Thinking with Budget Guidance

# 摘要

> 最近的深度思考大型语言模型（LLMs）通过大量推理来提升性能，但冗长的推理往往带来高昂的推理成本，而性能提升却未必成正比。因此，在不牺牲性能的前提下控制推理长度至关重要，尤其是在严格的思考预算下更具挑战性。我们提出了一种名为“预算引导”的简单而有效的方法，用于引导LLMs的推理过程以符合目标预算，且无需任何模型微调。

我们的方法引入了一个轻量级预测器，在生成下一个令牌时，对剩余思考长度建模为Gamma分布。这一信号随后被用于以柔和、令牌级别的方式引导生成，确保整体推理轨迹符合指定的思考预算。预算引导不仅实现了对思考长度的自然控制，还相较于基线方法，在具有挑战性的数学基准测试中显著提升了令牌效率。

例如，在紧缩预算下，与基线方法相比，它在MATH-500基准上实现了高达26%的准确率提升，同时仅使用了完整思考模型63%的思考令牌，却仍保持了极具竞争力的准确率。预算引导还能够推广到更广泛的任务领域，并展现出诸如估计问题难度等新兴能力。源代码可在以下链接获取：https://github.com/UMass-Embodied-AGI/BudgetGuidance。


> Recent deep-thinking large language models often reason extensively to improve performance, but such lengthy reasoning is not always desirable, as it incurs excessive inference costs with disproportionate performance gains. Controlling reasoning length without sacrificing performance is therefore important, but remains challenging, especially under tight thinking budgets. We propose budget guidance, a simple yet effective method for steering the reasoning process of LLMs toward a target budget without requiring any LLM fine-tuning. Our approach introduces a lightweight predictor that models a Gamma distribution over the remaining thinking length during next-token generation. This signal is then used to guide generation in a soft, token-level manner, ensuring that the overall reasoning trace adheres to the specified thinking budget. Budget guidance enables natural control of the thinking length, along with significant token efficiency improvements over baseline methods on challenging math benchmarks. For instance, it achieves up to a 26% accuracy gain on the MATH-500 benchmark under tight budgets compared to baseline methods, while maintaining competitive accuracy with only 63% of the thinking tokens used by the full-thinking model. Budget guidance also generalizes to broader task domains and exhibits emergent capabilities, such as estimating question difficulty. The source code is available at: https://github.com/UMass-Embodied-AGI/BudgetGuidance.

[Arxiv](https://arxiv.org/abs/2506.13752)