# 大型视觉语言模型的选择性状态空间记忆

发布时间：2024年12月13日

`LLM应用` `视觉语言模型` `多模态任务`

> Selective State Space Memory for Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）在众多多模态任务里展现出了非凡的性能。但针对特定领域应用来微调这些模型，依旧是个计算量巨大的难题。此文引入了状态空间内存集成（SSMI）这一用于 LVLMs 高效微调的新手段。通过把基于轻量型 Mamba 的状态空间模块融入 LVLM 架构，SSMI 能够捕捉长距离依赖关系，并有效注入特定任务的视觉与序列模式。和传统微调方法不同，SSMI 仅需更新模型的少量参数，在计算上高效且可拓展。在 COCO 字幕、VQA 以及 Flickr30k 等基准数据集上开展的实验显示，SSMI 在保持稳健性和泛化能力的情况下达到了顶尖水平。全面的分析进一步证实了 SSMI 在效率、适应性和可解释性方面的长处，使其成为大规模视觉语言模型微调的有力解决方案。

> Large Vision-Language Models (LVLMs) have demonstrated remarkable performance across a wide range of multimodal tasks. However, fine-tuning these models for domain-specific applications remains a computationally intensive challenge. This paper introduces State Space Memory Integration (SSMI), a novel approach for efficient fine-tuning of LVLMs. By integrating lightweight Mamba-based state space modules into the LVLM architecture, SSMI captures long-range dependencies and injects task-specific visual and sequential patterns effectively. Unlike traditional fine-tuning methods, SSMI requires only a fraction of the model's parameters to be updated, making it computationally efficient and scalable. Experiments on benchmark datasets, including COCO Captioning, VQA, and Flickr30k, demonstrate that SSMI achieves state-of-the-art performance while maintaining robustness and generalization capabilities. Comprehensive analysis further validates the advantages of SSMI in terms of efficiency, adaptability, and interpretability, positioning it as a compelling solution for fine-tuning large-scale vision-language models.

[Arxiv](https://arxiv.org/abs/2412.09875)