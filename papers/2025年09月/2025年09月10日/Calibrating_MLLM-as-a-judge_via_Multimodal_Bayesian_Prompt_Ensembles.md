# 借助多模态贝叶斯提示集成校准多模态大语言模型评判者

发布时间：2025年09月10日

`LLM应用` `媒体与娱乐`

> Calibrating MLLM-as-a-judge via Multimodal Bayesian Prompt Ensembles

# 摘要

> 多模态大型语言模型（MLLMs）如今被广泛用于评估文本到图像（TTI）生成系统，能结合视觉和文本上下文给出自动化评判。然而，这些“评判”模型常受偏差、过度自信困扰，且在不同图像领域的表现参差不齐。尽管提示集成在单模态纯文本场景中已展现出缓解这些问题的潜力，但实验发现，标准集成方法在TTI任务中难以有效泛化。为克服这些局限，我们提出了一种名为多模态贝叶斯提示混合集成（MMB）的新型多模态感知方法。该方法以贝叶斯提示集成方法为基础，结合图像聚类进行增强，让评判模型能根据样本的视觉特征动态分配提示权重。结果显示，MMB不仅提升了成对偏好判断的准确性，还显著增强了校准度，便于衡量评判模型的真实不确定性。在HPSv2和MJBench两个TTI基准测试中，MMB在与人类注释的一致性以及跨图像内容的校准表现上均优于现有基线。研究结果凸显了针对评判模型校准的多模态专属策略的重要性，并为可靠的大规模TTI评估提供了可行方向。

> Multimodal large language models (MLLMs) are increasingly used to evaluate text-to-image (TTI) generation systems, providing automated judgments based on visual and textual context. However, these "judge" models often suffer from biases, overconfidence, and inconsistent performance across diverse image domains. While prompt ensembling has shown promise for mitigating these issues in unimodal, text-only settings, our experiments reveal that standard ensembling methods fail to generalize effectively for TTI tasks. To address these limitations, we propose a new multimodal-aware method called Multimodal Mixture-of-Bayesian Prompt Ensembles (MMB). Our method uses a Bayesian prompt ensemble approach augmented by image clustering, allowing the judge to dynamically assign prompt weights based on the visual characteristics of each sample. We show that MMB improves accuracy in pairwise preference judgments and greatly enhances calibration, making it easier to gauge the judge's true uncertainty. In evaluations on two TTI benchmarks, HPSv2 and MJBench, MMB outperforms existing baselines in alignment with human annotations and calibration across varied image content. Our findings highlight the importance of multimodal-specific strategies for judge calibration and suggest a promising path forward for reliable large-scale TTI evaluation.

[Arxiv](https://arxiv.org/abs/2509.08777)