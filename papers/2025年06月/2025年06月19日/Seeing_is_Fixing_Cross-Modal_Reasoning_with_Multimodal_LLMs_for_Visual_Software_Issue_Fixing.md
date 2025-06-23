# 看见即修复：利用多模态大型语言模型进行跨模态推理解决视觉软件问题

发布时间：2025年06月19日

`LLM应用` `软件工程` `跨模态推理`

> Seeing is Fixing: Cross-Modal Reasoning with Multimodal LLMs for Visual Software Issue Fixing

# 摘要

> 基于大型语言模型（LLM）的自动化程序修复（APR）技术在解决实际GitHub问题任务中展现了令人鼓舞的结果。然而，现有的APR系统主要在单模态场景下进行评估（例如SWE-bench），难以应对多模态问题场景（例如SWE-bench M）。在多模态场景中，LLMs需要依赖图形用户界面（GUI）中的视觉信息来理解错误并生成修复方案。为了解决这一难题，我们提出了GUIRepair，这是一种通过理解和捕捉视觉信息来解决多模态问题场景的跨模态推理方法。GUIRepair整合了两个关键组件：Image2Code和Code2Image，以增强故障理解和补丁验证。Image2Code基于问题报告提取相关项目文档，生成导致视觉症状的再现代码，将GUI图像转化为可执行上下文，从而更好地理解故障。Code2Image通过再现代码重演视觉问题场景，并评估修复是否在视觉上解决问题，为补丁验证提供反馈。我们在SWE-bench M上评估了GUIRepair，该方法展示了显著的有效性。当使用GPT-4o作为基础模型时，GUIRepair解决了157个实例，优于最佳开源基线26个实例。当使用o4-mini作为基础模型时，GUIRepair解决了175个实例，优于顶级商用系统22个实例。这充分证明了我们通过跨模态推理解决多模态问题的新视角的成功。

> Large language model-(LLM) based automated program repair (APR) techniques have shown promising results in resolving real-world GitHub issue tasks. Existing APR systems are primarily evaluated in unimodal settings (e.g., SWE-bench). However, these autonomous systems struggle to resolve multimodal problem scenarios (e.g., SWE-bench M) due to limitations in interpreting and leveraging visual information. In multimodal scenarios, LLMs need to rely on visual information in the graphical user interface (GUI) to understand bugs and generate fixes. To bridge this gap, we propose GUIRepair, a cross-modal reasoning approach for resolving multimodal issue scenarios by understanding and capturing visual information. Specifically, GUIRepair integrates two key components, Image2Code and Code2Image, to enhance fault comprehension and patch validation. Image2Code extracts relevant project documents based on the issue report, then applies this domain knowledge to generate the reproduced code responsible for the visual symptoms, effectively translating GUI images into executable context for better fault comprehension. Code2Image replays the visual issue scenario using the reproduced code and captures GUI renderings of the patched program to assess whether the fix visually resolves the issue, providing feedback for patch validation. We evaluate GUIRepair on SWE-bench M, and the approach demonstrates significant effectiveness. When utilizing GPT-4o as the base model, GUIRepair solves 157 instances, outperforming the best open-source baseline by 26 instances. Furthermore, when using o4-mini as the base model, GUIRepair can achieve even better results and solve 175 instances, outperforming the top commercial system by 22 instances. This emphasizes the success of our new perspective on incorporating cross-modal reasoning by understanding and capturing visual information to resolve multimodal issues.

[Arxiv](https://arxiv.org/abs/2506.16136)