# # 大型和小型 MLLMs 的基准测试

发布时间：2025年01月04日

`LLM应用

**理由**：这篇论文主要讨论了大型和小型多模态语言模型（MLLMs）在实际应用中的表现对比，包括推理速度、计算成本、设备端应用等方面。研究重点在于评估这些模型在不同任务和场景中的性能，并探讨它们的应用潜力和局限性。因此，这篇论文属于LLM应用类别。`

> Benchmarking Large and Small MLLMs

# 摘要

> 大型多模态语言模型（MLLMs），如 GPT-4V 和 GPT-4o，在多模态内容的理解和生成上取得了显著进展，展现了在各种任务中的卓越能力。然而，它们的部署面临推理速度慢、计算成本高以及设备端应用不切实际等挑战。相比之下，小型 MLLMs（如 LLava 系列和 Phi-3-Vision）提供了更快的推理速度、更低的部署成本以及处理特定领域场景的能力，成为有前景的替代方案。尽管小型 MLLMs 的应用日益广泛，但大型与小型 MLLMs 之间的能力边界仍未充分探索。本研究通过系统评估，对比了小型和大型 MLLMs 在物体识别、时间推理、多模态理解等一般能力以及工业、汽车等实际应用中的表现。结果显示，小型 MLLMs 在特定场景下可与大型模型媲美，但在需要深度推理或细致理解的任务中表现明显不足。此外，我们总结了小型和大型 MLLMs 的常见失败案例，揭示了即使是顶尖模型也难以应对的领域。我们希望这些发现能为研究社区提供指导，推动 MLLMs 的质量边界，提升其在不同应用中的可用性和有效性。

> Large multimodal language models (MLLMs) such as GPT-4V and GPT-4o have achieved remarkable advancements in understanding and generating multimodal content, showcasing superior quality and capabilities across diverse tasks. However, their deployment faces significant challenges, including slow inference, high computational cost, and impracticality for on-device applications. In contrast, the emergence of small MLLMs, exemplified by the LLava-series models and Phi-3-Vision, offers promising alternatives with faster inference, reduced deployment costs, and the ability to handle domain-specific scenarios. Despite their growing presence, the capability boundaries between large and small MLLMs remain underexplored. In this work, we conduct a systematic and comprehensive evaluation to benchmark both small and large MLLMs, spanning general capabilities such as object recognition, temporal reasoning, and multimodal comprehension, as well as real-world applications in domains like industry and automotive. Our evaluation reveals that small MLLMs can achieve comparable performance to large models in specific scenarios but lag significantly in complex tasks requiring deeper reasoning or nuanced understanding. Furthermore, we identify common failure cases in both small and large MLLMs, highlighting domains where even state-of-the-art models struggle. We hope our findings will guide the research community in pushing the quality boundaries of MLLMs, advancing their usability and effectiveness across diverse applications.

[Arxiv](https://arxiv.org/abs/2501.04150)