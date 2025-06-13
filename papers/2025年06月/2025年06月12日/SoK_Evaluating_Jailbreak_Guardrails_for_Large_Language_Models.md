# 研究综述：探索大型语言模型的越狱防护评估机制

发布时间：2025年06月12日

`LLM应用` `人工智能安全` `信息安全`

> SoK: Evaluating Jailbreak Guardrails for Large Language Models

# 摘要

> 大型语言模型（LLMs）虽然取得了显著进展，但部署过程中暴露了关键漏洞，特别是面对能够绕过安全机制的越狱攻击。护栏机制作为一种外部防御方案应运而生，用于监控和控制 LLM 交互。然而，当前的 LLM 护栏机制领域仍处于分散状态，缺乏统一的分类体系和全面的评估框架。在本篇知识系统化（SoK）论文中，我们首次对 LLM 越狱护栏机制进行了全面分析。我们提出了一种基于六个关键维度的多维分类法，并引入安全性-效率-效用评估框架，以评估护栏机制的实际有效性。通过深入分析和实验，我们揭示了现有护栏方法的优势与局限，探讨了它们在各类攻击中的适用性，并为优化防御组合提供了见解。我们的研究成果为未来研究和开发奠定了结构化基础，旨在推动稳健 LLM 护栏机制的有原则发展与部署。代码已开源，详情请访问 https://github.com/xunguangwang/SoK4JailbreakGuardrails。

> Large Language Models (LLMs) have achieved remarkable progress, but their deployment has exposed critical vulnerabilities, particularly to jailbreak attacks that circumvent safety mechanisms. Guardrails--external defense mechanisms that monitor and control LLM interaction--have emerged as a promising solution. However, the current landscape of LLM guardrails is fragmented, lacking a unified taxonomy and comprehensive evaluation framework. In this Systematization of Knowledge (SoK) paper, we present the first holistic analysis of jailbreak guardrails for LLMs. We propose a novel, multi-dimensional taxonomy that categorizes guardrails along six key dimensions, and introduce a Security-Efficiency-Utility evaluation framework to assess their practical effectiveness. Through extensive analysis and experiments, we identify the strengths and limitations of existing guardrail approaches, explore their universality across attack types, and provide insights into optimizing defense combinations. Our work offers a structured foundation for future research and development, aiming to guide the principled advancement and deployment of robust LLM guardrails. The code is available at https://github.com/xunguangwang/SoK4JailbreakGuardrails.

[Arxiv](https://arxiv.org/abs/2506.10597)