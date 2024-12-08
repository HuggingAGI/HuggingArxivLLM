# 通过动态视觉标记退出加速多模态大型语言模型以及相关经验发现

发布时间：2024年11月29日

`LLM应用` `多模态` `语言模型`

> Accelerating Multimodal Large Language Models via Dynamic Visual-Token Exit and the Empirical Findings

# 摘要

> 在现有的多模态大型语言模型（MLLMs）中，视觉标记的过度使用往往明显冗余，还带来极高的计算成本。为深入探究此问题，我们先是对 MLLMs 的注意力行为展开了广泛的实证研究，总结出 MLLMs 的三个主要推理阶段：（i）标记间的早期融合率先快速完成。（ii）接着进行模态内建模。（iii）多模态推理恢复并持续至推理结束。特别要指出的是，我们发现当文本标记获取到足够的图像信息时，视觉标记就不再为推理做贡献，从而产生明显的视觉冗余。基于这些普遍观察，我们提出了一种简单却有效的方法来提升 MLLMs 的效率，名为动态视觉标记退出（DyVTE）。DyVTE 借助轻量级超网络来感知文本标记状态，并决定在某一层之后移除所有视觉标记，以此解决所观察到的视觉冗余问题。为验证 VTE，我们将其应用于包括 LLaVA、VILA、Eagle 和 InternVL 在内的一组 MLLMs，并在众多基准上开展了大量实验。实验结果不但表明了我们的 VTE 在提高 MLLMs 效率方面的有效性，还得出了 MLLMs 的一般建模模式，有力地促进了对 MLLMs 的深入理解。我们的代码匿名发布于 https://github.com/DoubtedSteam/DyVTE 。

> The excessive use of visual tokens in existing Multimoal Large Language Models (MLLMs) often exhibits obvious redundancy and brings in prohibitively expensive computation. To gain insights into this problem, we first conduct extensive empirical studies on the attention behaviors of MLLMs, and summarize three main inference stages in MLLMs: (i) Early fusion between tokens is first accomplished quickly. (ii) Intra-modality modeling then comes to play. (iii) Multimodal reasoning} resumes and lasts until the end of inference. In particular, we reveal that visual tokens will stop contributing to reasoning when the text tokens receive enough image information, yielding obvious visual redundancy. Based on these generalized observations, we propose a simple yet effective method to improve the efficiency of MLLMs, termed dynamic visual-token exit (DyVTE). DyVTE uses lightweight hyper-networks to perceive the text token status and decide the removal of all visual tokens after a certain layer, thereby addressing the observed visual redundancy. To validate VTE, we apply it to a set of MLLMs, including LLaVA, VILA, Eagle and InternVL, and conduct extensive experiments on a bunch of benchmarks. The experiment results not only show the effectiveness of our VTE in improving MLLMs' efficiency, but also yield the general modeling patterns of MLLMs, well facilitating the in-depth understanding of MLLMs. Our code is anonymously released at https://github.com/DoubtedSteam/DyVTE.

[Arxiv](https://arxiv.org/abs/2411.19628)