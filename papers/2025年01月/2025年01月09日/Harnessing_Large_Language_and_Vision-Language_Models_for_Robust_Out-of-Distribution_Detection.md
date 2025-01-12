# 借助大型语言和视觉-语言模型实现稳健的分布外检测

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）和视觉-语言模型（VLMs）来提升零-shot OOD检测的性能。虽然涉及到LLM的使用，但重点在于如何将LLM与VLMs结合，应用于具体的任务（OOD检测），而不是探讨LLM的理论或构建Agent系统。因此，将其归类为LLM应用更为合适。` `计算机视觉`

> Harnessing Large Language and Vision-Language Models for Robust Out-of-Distribution Detection

# 摘要

> # 摘要
分布外（OOD）检测借助CLIP等强大的视觉-语言模型（VLMs），在零-shot方法上取得了显著进展。然而，现有研究多聚焦于提升远分布外（Far-OOD）性能，却可能牺牲了近分布外（Near-OOD）效果，正如我们的初步研究所揭示的。为此，我们提出了一种创新策略，通过巧妙结合大型语言模型（LLMs）和VLMs，全面提升零-shot OOD检测在Far-OOD和Near-OOD场景中的表现。我们的方法首先利用LLM生成ID标签的超类及其背景描述，随后通过CLIP提取特征。接着，我们从超类特征中剔除背景特征，提取出ID数据的核心语义特征。这种精炼的表示有助于从WordNet的候选标签集中筛选出更合适的负标签，从而提升零-shot OOD检测的性能。此外，我们引入了少样本提示调优和视觉提示调优，使框架更好地适应目标分布。实验结果显示，该方法在多个基准测试中均优于当前最先进的方法，AUROC提升2.9%，FPR95降低12.6%。同时，该方法在不同领域的协变量偏移下表现出卓越的鲁棒性，进一步证明了其在现实场景中的高效性。

> Out-of-distribution (OOD) detection has seen significant advancements with zero-shot approaches by leveraging the powerful Vision-Language Models (VLMs) such as CLIP. However, prior research works have predominantly focused on enhancing Far-OOD performance, while potentially compromising Near-OOD efficacy, as observed from our pilot study. To address this issue, we propose a novel strategy to enhance zero-shot OOD detection performances for both Far-OOD and Near-OOD scenarios by innovatively harnessing Large Language Models (LLMs) and VLMs. Our approach first exploit an LLM to generate superclasses of the ID labels and their corresponding background descriptions followed by feature extraction using CLIP. We then isolate the core semantic features for ID data by subtracting background features from the superclass features. The refined representation facilitates the selection of more appropriate negative labels for OOD data from a comprehensive candidate label set of WordNet, thereby enhancing the performance of zero-shot OOD detection in both scenarios. Furthermore, we introduce novel few-shot prompt tuning and visual prompt tuning to adapt the proposed framework to better align with the target distribution. Experimental results demonstrate that the proposed approach consistently outperforms current state-of-the-art methods across multiple benchmarks, with an improvement of up to 2.9% in AUROC and a reduction of up to 12.6% in FPR95. Additionally, our method exhibits superior robustness against covariate shift across different domains, further highlighting its effectiveness in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2501.05228)