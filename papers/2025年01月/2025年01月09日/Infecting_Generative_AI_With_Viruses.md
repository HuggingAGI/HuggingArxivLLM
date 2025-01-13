# 生成式AI的病毒感染

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要探讨了在视觉-大型语言模型（VLM/LLM）中嵌入EICAR测试文件的方法，并测试了多个LLM平台的安全性。研究涉及LLM在实际应用中的文件处理与执行能力，属于LLM在实际场景中的应用研究，因此分类为LLM应用。` `信息安全` `人工智能`

> Infecting Generative AI With Viruses

# 摘要

> 本研究提出了一种创新方法，通过将EICAR测试文件嵌入JPEG图像中，测试视觉-大型语言模型（VLM/LLM）的安全边界。我们在多个LLM平台（如OpenAI GPT-4o、Microsoft Copilot、Google Gemini 1.5 Pro和Anthropic Claude 3.5 Sonnet）上成功执行了四种协议。实验表明，包含EICAR签名的JPEG图像可在LLM虚拟工作空间中上传、操作并可能执行。主要发现包括：1）能在图像元数据中隐藏EICAR字符串而不被检测，2）通过Python操作在LLM环境中成功提取测试文件，3）展示了base64编码和字符串反转等混淆技术。本研究扩展了微软研究院的“渗透测试参与规则”框架，评估了生成式AI和LLM在容器化环境中的文件处理与执行能力。

> This study demonstrates a novel approach to testing the security boundaries of Vision-Large Language Model (VLM/ LLM) using the EICAR test file embedded within JPEG images. We successfully executed four distinct protocols across multiple LLM platforms, including OpenAI GPT-4o, Microsoft Copilot, Google Gemini 1.5 Pro, and Anthropic Claude 3.5 Sonnet. The experiments validated that a modified JPEG containing the EICAR signature could be uploaded, manipulated, and potentially executed within LLM virtual workspaces. Key findings include: 1) consistent ability to mask the EICAR string in image metadata without detection, 2) successful extraction of the test file using Python-based manipulation within LLM environments, and 3) demonstration of multiple obfuscation techniques including base64 encoding and string reversal. This research extends Microsoft Research's "Penetration Testing Rules of Engagement" framework to evaluate cloud-based generative AI and LLM security boundaries, particularly focusing on file handling and execution capabilities within containerized environments.

[Arxiv](https://arxiv.org/abs/2501.05542)