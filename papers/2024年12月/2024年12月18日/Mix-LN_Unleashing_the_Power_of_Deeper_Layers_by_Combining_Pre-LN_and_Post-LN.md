# Mix-LN：结合 Pre-LN 与 Post-LN 以释放深层的力量

发布时间：2024年12月18日

`LLM理论` `模型训练`

> Mix-LN: Unleashing the Power of Deeper Layers by Combining Pre-LN and Post-LN

# 摘要

> 大型语言模型（LLMs）成绩斐然，然而近期发现其深层部分贡献甚微，在不影响整体性能的情况下可进行删减。有人将此视作模型压缩的契机，而我们认为这是广泛使用预层归一化（Pre-LN）所致的训练缺陷。我们证实，GPT 和 LLaMA 等模型常用的 Pre-LN 会使深层梯度范数减小，降低其有效性。相较而言，后层归一化（Post-LN）在深层能保留较大梯度范数，但早期层存在梯度消失问题。为此，我们推出 Mix-LN 这一创新的归一化技术，将 Pre-LN 和 Post-LN 的优势在同一模型中融合。Mix-LN 对早期层采用 Post-LN，对深层采用 Pre-LN，确保各层梯度更均匀。这使得网络的浅层和深层都能有效助力训练。针对从 7000 万到 70 亿等各种规模模型开展的大量实验表明，Mix-LN 始终优于 Pre-LN 和 Post-LN，促进整个网络形成更平衡、更健康的梯度范数，提升 LLM 预训练的整体质量。此外，我们证明在监督微调（SFT）和基于人类反馈的强化学习（RLHF）中，使用 Mix-LN 预训练的模型比使用 Pre-LN 或 Post-LN 的模型学得更好，凸显了高质量深层的至关重要性。通过有效化解当前 LLMs 中深层的低效问题，Mix-LN 释放了模型潜力，在不增大模型规模的情况下增强了模型能力。我们的代码可在 https://github.com/pixeli99/MixLN 获取。

> Large Language Models (LLMs) have achieved remarkable success, yet recent findings reveal that their deeper layers often contribute minimally and can be pruned without affecting overall performance. While some view this as an opportunity for model compression, we identify it as a training shortfall rooted in the widespread use of Pre-Layer Normalization (Pre-LN). We demonstrate that Pre-LN, commonly employed in models like GPT and LLaMA, leads to diminished gradient norms in its deeper layers, reducing their effectiveness. In contrast, Post-Layer Normalization (Post-LN) preserves larger gradient norms in deeper layers but suffers from vanishing gradients in earlier layers. To address this, we introduce Mix-LN, a novel normalization technique that combines the strengths of Pre-LN and Post-LN within the same model. Mix-LN applies Post-LN to the earlier layers and Pre-LN to the deeper layers, ensuring more uniform gradients across layers. This allows all parts of the network--both shallow and deep layers--to contribute effectively to training. Extensive experiments with various model sizes from 70M to 7B demonstrate that Mix-LN consistently outperforms both Pre-LN and Post-LN, promoting more balanced, healthier gradient norms throughout the network, and enhancing the overall quality of LLM pre-training. Furthermore, we demonstrate that models pre-trained with Mix-LN learn better compared to those using Pre-LN or Post-LN during supervised fine-tuning (SFT) and reinforcement learning from human feedback (RLHF), highlighting the critical importance of high-quality deep layers. By effectively addressing the inefficiencies of deep layers in current LLMs, Mix-LN unlocks their potential, enhancing model capacity without increasing model size. Our code is available at https://github.com/pixeli99/MixLN.

[Arxiv](https://arxiv.org/abs/2412.13795)