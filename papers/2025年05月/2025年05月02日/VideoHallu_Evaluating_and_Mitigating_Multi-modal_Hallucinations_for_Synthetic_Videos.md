# VideoHallu: 评估与缓解合成视频中的多模态幻觉

发布时间：2025年05月02日

`LLM应用` `视频生成` `异常检测`

> VideoHallu: Evaluating and Mitigating Multi-modal Hallucinations for Synthetic Videos

# 摘要

> 基于基础模型的合成视频生成凭借其高度写实性和广泛应用备受瞩目。然而，这些模型虽能生成精美的画面，却常忽视常识与物理定律，导致异常内容频现。现有指标如VideoScore虽注重整体质量，却忽视了这些违规现象，且缺乏可解释性。更深入的方法是利用多模态大语言模型（MLLMs）作为可解释评估器，如FactScore所示。然而，MLLMs在合成视频异常检测方面的潜力尚未充分挖掘。为此，我们推出VideoHallu基准测试，该测试集整合了Veo2、Sora、Kling等模型生成的合成视频，并配以专家设计的QA任务，这些任务可通过跨多种类别的类人水平推理解决。我们评估了包括GPT-4o、Gemini-2.5-Pro、Qwen-2.5-VL以及Video-R1和VideoChat-R1等最新MLLMs。尽管这些模型在MVBench和MovieChat等实际场景中表现优异，但在合成环境下的基本常识和物理任务中仍存在幻觉现象，凸显了幻觉检测的挑战。我们进一步利用真实与合成常识/物理数据，通过组相对策略优化（GRPO）对最新MLLMs进行微调。实验结果表明，尤其是结合反例整合后，模型准确率显著提升，推动了MLLMs推理能力的发展。我们的数据集已开源，可在https://github.com/zli12321/VideoHallu获取。

> Synthetic video generation with foundation models has gained attention for its realism and wide applications. While these models produce high-quality frames, they often fail to respect common sense and physical laws, resulting in abnormal content. Existing metrics like VideoScore emphasize general quality but ignore such violations and lack interpretability. A more insightful approach is using multi-modal large language models (MLLMs) as interpretable evaluators, as seen in FactScore. Yet, MLLMs' ability to detect abnormalities in synthetic videos remains underexplored. To address this, we introduce VideoHallu, a benchmark featuring synthetic videos from models like Veo2, Sora, and Kling, paired with expert-designed QA tasks solvable via human-level reasoning across various categories. We assess several SoTA MLLMs, including GPT-4o, Gemini-2.5-Pro, Qwen-2.5-VL, and newer models like Video-R1 and VideoChat-R1. Despite strong real-world performance on MVBench and MovieChat, these models still hallucinate on basic commonsense and physics tasks in synthetic settings, underscoring the challenge of hallucination. We further fine-tune SoTA MLLMs using Group Relative Policy Optimization (GRPO) on real and synthetic commonsense/physics data. Results show notable accuracy gains, especially with counterexample integration, advancing MLLMs' reasoning capabilities. Our data is available at https://github.com/zli12321/VideoHallu.

[Arxiv](https://arxiv.org/abs/2505.01481)