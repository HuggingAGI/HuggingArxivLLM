# # DesignCoder：基于大型语言模型的层次结构感知与自我修正用户界面代码生成

发布时间：2025年06月16日

`LLM应用` `前端开发` `软件工程`

> DesignCoder: Hierarchy-Aware and Self-Correcting UI Code Generation with Large Language Models

# 摘要

> 多模态大型语言模型 (MLLMs) 通过自动化代码生成显著简化了前端界面开发流程，但同时也带来了代码质量保障的挑战。现有方法难以兼顾生成组件的视觉一致性和功能完整性，且缺乏对渲染页面保真度和正确性的评估机制。为解决这些问题，我们提出了 DesignCoder，一种全新的层次感知且具备自我纠错功能的自动化代码生成框架。通过引入 UI 分组链，我们增强了 MLLMs 对复杂嵌套 UI 层次结构的理解和预测能力。DesignCoder 采用层次化分治方法生成前端代码，并集成了自我纠错机制以提升模型识别和修复代码错误的能力。在来自开源社区和行业项目的 UI 模拟数据集上的广泛评估表明，DesignCoder 在 React Native（一种广泛使用的 UI 框架）中显著优于现有最先进的基线模型。我们在视觉相似性指标 (MSE, CLIP, SSIM) 上实现了 37.63%、9.52% 和 12.82% 的性能提升，并在 TreeBLEU、Container Match 和 Tree Edit Distance 方面显著提高了代码结构相似性，分别提升了 30.19%、29.31% 和 24.67%。此外，我们与专业开发人员合作进行的用户研究结果显示，DesignCoder 符合行业最佳实践，展现了高可用性、可读性和可维护性。我们的方法为敏捷前端开发提供了一种高效且实用的解决方案，使开发团队能够更加专注于核心功能和产品创新。

> Multimodal large language models (MLLMs) have streamlined front-end interface development by automating code generation. However, these models also introduce challenges in ensuring code quality. Existing approaches struggle to maintain both visual consistency and functional completeness in the generated components. Moreover, they lack mechanisms to assess the fidelity and correctness of the rendered pages. To address these issues, we propose DesignCoder, a novel hierarchical-aware and self-correcting automated code generation framework. Specifically, we introduce UI Grouping Chains, which enhance MLLMs' capability to understand and predict complex nested UI hierarchies. Subsequently, DesignCoder employs a hierarchical divide-and-conquer approach to generate front-end code. Finally, we incorporate a self-correction mechanism to improve the model's ability to identify and rectify errors in the generated code. Extensive evaluations on a dataset of UI mockups collected from both open-source communities and industry projects demonstrate that DesignCoder outperforms state-of-the-art baselines in React Native, a widely adopted UI framework. Our method achieves a 37.63%, 9.52%, 12.82% performance increase in visual similarity metrics (MSE, CLIP, SSIM) and significantly improves code structure similarity in terms of TreeBLEU, Container Match, and Tree Edit Distance by 30.19%, 29.31%, 24.67%. Furthermore, we conducted a user study with professional developers to assess the quality and practicality of the generated code. Results indicate that DesignCoder aligns with industry best practices, demonstrating high usability, readability, and maintainability. Our approach provides an efficient and practical solution for agile front-end development, enabling development teams to focus more on core functionality and product innovation.

[Arxiv](https://arxiv.org/abs/2506.13663)