# 模块化多智能体框架MAM：通过角色专业化协作实现多模态医学诊断

发布时间：2025年06月24日

`Agent` `多模态`

> MAM: Modular Multi-Agent Framework for Multi-Modal Medical Diagnosis via Role-Specialized Collaboration

# 摘要

> 医学大型语言模型（LLMs）近期的进展展示了其强大的推理与诊断能力。然而，现有统一的多模态医学LLMs在知识更新成本、全面性和灵活性方面仍存在局限。为解决这些问题，我们提出了模块化多智能体多模态医疗诊断框架（MAM）。基于实证研究中关于角色分配和诊断辨别在LLMs中优势的启发，MAM将医疗诊断过程分解为五个专门化角色：全科医生、专科团队、放射科医生、医疗助理和主任，每个角色均由基于LLMs的代理实现。这种模块化协作框架不仅实现了高效的知识更新，还充分利用了现有的医学LLMs和知识库。在涵盖文本、图像、音频和视频等多种模态的广泛公开多模态医疗数据集上进行的大量实验表明，MAM在多模态LLMs中的表现始终优于单一模态的LLMs。特别地，与基线模型相比，MAM实现了从18%到365%的显著性能提升。我们的代码已发布在https://github.com/yczhou001/MAM。

> Recent advancements in medical Large Language Models (LLMs) have showcased their powerful reasoning and diagnostic capabilities. Despite their success, current unified multimodal medical LLMs face limitations in knowledge update costs, comprehensiveness, and flexibility. To address these challenges, we introduce the Modular Multi-Agent Framework for Multi-Modal Medical Diagnosis (MAM). Inspired by our empirical findings highlighting the benefits of role assignment and diagnostic discernment in LLMs, MAM decomposes the medical diagnostic process into specialized roles: a General Practitioner, Specialist Team, Radiologist, Medical Assistant, and Director, each embodied by an LLM-based agent. This modular and collaborative framework enables efficient knowledge updates and leverages existing medical LLMs and knowledge bases. Extensive experimental evaluations conducted on a wide range of publicly accessible multimodal medical datasets, incorporating text, image, audio, and video modalities, demonstrate that MAM consistently surpasses the performance of modality-specific LLMs. Notably, MAM achieves significant performance improvements ranging from 18% to 365% compared to baseline models. Our code is released at https://github.com/yczhou001/MAM.

[Arxiv](https://arxiv.org/abs/2506.19835)