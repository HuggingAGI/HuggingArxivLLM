# GenieBlue：大型语言模型的移动设备语言与多模态能力融合

发布时间：2025年03月07日

`LLM应用

摘要讨论了多模态大型语言模型在移动设备上的部署挑战，并提出了一种名为GenieBlue的高效结构设计，以优化模型在移动设备上的性能和应用。这属于应用层面的研究，专注于将模型应用于实际设备，解决部署问题。因此，归类为LLM应用。` `移动设备` `智能手机`

> GenieBlue: Integrating both Linguistic and Multimodal Capabilities for Large Language Models on Mobile Devices

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展使其在移动设备上的部署成为可能。然而，保持强大的语言能力以及确保硬件兼容性仍面临挑战，这对于用户体验和实际部署效率至关重要。在我们的部署过程中，发现现有MLLMs在纯语言任务上常出现性能下降，且智能手机上的NPU平台不支持用于多模态训练中保留纯语言能力的MoE架构。为解决这些问题，我们系统性地分析了在MLLMs训练过程中保持纯语言能力的方法，重点关注了训练数据和模型架构。基于这些分析，提出了GenieBlue——一个高效的MLLM结构设计，将语言和多模态能力相结合，适用于移动设备上的LLMs。GenieBlue通过冻结原始LLM参数以保持纯语言能力，并复制特定的Transformer块进行全微调，同时集成轻量级LoRA模块以获取多模态能力。这种方法在保持语言能力的同时，通过大量训练实现了与现有方法相当的多模态性能。在智能手机NPU上部署GenieBlue，展示了其在移动设备应用中的高效性和实用性。

> Recent advancements in Multimodal Large Language Models (MLLMs) have enabled their deployment on mobile devices. However, challenges persist in maintaining strong language capabilities and ensuring hardware compatibility, both of which are crucial for user experience and practical deployment efficiency. In our deployment process, we observe that existing MLLMs often face performance degradation on pure language tasks, and the current NPU platforms on smartphones do not support the MoE architecture, which is commonly used to preserve pure language capabilities during multimodal training. To address these issues, we systematically analyze methods to maintain pure language capabilities during the training of MLLMs, focusing on both training data and model architecture aspects. Based on these analyses, we propose GenieBlue, an efficient MLLM structural design that integrates both linguistic and multimodal capabilities for LLMs on mobile devices. GenieBlue freezes the original LLM parameters during MLLM training to maintain pure language capabilities. It acquires multimodal capabilities by duplicating specific transformer blocks for full fine-tuning and integrating lightweight LoRA modules. This approach preserves language capabilities while achieving comparable multimodal performance through extensive training. Deployed on smartphone NPUs, GenieBlue demonstrates efficiency and practicality for applications on mobile devices.

[Arxiv](https://arxiv.org/abs/2503.06019)