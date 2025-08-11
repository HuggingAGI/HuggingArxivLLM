# 基于不确定性量化的 rollout 策略自适应方法用于无标签跨领域时间对齐任务

发布时间：2025年08月08日

`其他` `视频处理` `计算机视觉`

> Uncertainty-quantified Rollout Policy Adaptation for Unlabelled Cross-domain Temporal Grounding

# 摘要

> # 摘要  
视频时间定位（TG）的目标是在长视频中找到与自然语言描述匹配的视频片段并进行时间定位。尽管视觉语言模型（VLMs）在整体语义匹配方面表现出色，但它们在精细时间定位方面表现欠佳。最近，Group Relative Policy Optimisation（GRPO）通过将推理过程重新表述为一个强化学习任务，实现了精细的时间定位，并在领域内取得了优异的性能。然而，GRPO依赖于标注数据，因此不适合无标注领域。此外，由于视频数据量大且存储和处理成本高昂，进行大规模适应会导致无法承受的延迟和计算开销，使其无法实现实时部署。为了解决这两个问题，我们提出了一种数据高效的无标注跨域时间定位方法。具体来说，我们首先在标注的源域上训练一个模型，然后仅使用目标域中少量无标注视频将其适应到目标域。这种方法消除了对目标标注的需求，同时将计算和存储开销保持在足够低的水平以实现实时运行。具体而言，我们引入了不确定性量化 rollout 策略适应（URPA），用于在学习视频时间定位时进行跨域知识转移，而无需目标标签。URPA 使用 GRPO 的 rollout 生成多个候选预测，对其进行平均以形成伪标签，并通过这些 rollout 的方差估计置信度。这种置信度随后用于加权训练奖励，引导模型关注可靠的监督信号。在六个跨域设置下的三个数据集上的实验表明，URPA 仅使用少量无标注目标视频就能很好地进行泛化。一旦发表，代码将对外公开。

> Video Temporal Grounding (TG) aims to temporally locate video segments matching a natural language description (a query) in a long video. While Vision-Language Models (VLMs) are effective at holistic semantic matching, they often struggle with fine-grained temporal localisation. Recently, Group Relative Policy Optimisation (GRPO) reformulates the inference process as a reinforcement learning task, enabling fine-grained grounding and achieving strong in-domain performance. However, GRPO relies on labelled data, making it unsuitable in unlabelled domains. Moreover, because videos are large and expensive to store and process, performing full-scale adaptation introduces prohibitive latency and computational overhead, making it impractical for real-time deployment. To overcome both problems, we introduce a Data-Efficient Unlabelled Cross-domain Temporal Grounding method, from which a model is first trained on a labelled source domain, then adapted to a target domain using only a small number of unlabelled videos from the target domain. This approach eliminates the need for target annotation and keeps both computational and storage overhead low enough to run in real time. Specifically, we introduce. Uncertainty-quantified Rollout Policy Adaptation (URPA) for cross-domain knowledge transfer in learning video temporal grounding without target labels. URPA generates multiple candidate predictions using GRPO rollouts, averages them to form a pseudo label, and estimates confidence from the variance across these rollouts. This confidence then weights the training rewards, guiding the model to focus on reliable supervision. Experiments on three datasets across six cross-domain settings show that URPA generalises well using only a few unlabelled target videos. Codes will be released once published.

[Arxiv](https://arxiv.org/abs/2508.06317)