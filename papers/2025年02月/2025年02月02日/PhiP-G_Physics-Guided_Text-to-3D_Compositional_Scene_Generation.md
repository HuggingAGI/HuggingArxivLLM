# PhiP-G: 物理引导的文本生成3D组合场景

发布时间：2025年02月02日

`Agent

理由：这篇论文主要介绍了一个名为PhiP-G的组合场景生成框架，该框架利用LLM代理分析复杂场景描述，生成场景图，并整合多模态2D生成代理和3D高斯生成方法。论文的核心在于通过多个代理（LLM代理、2D生成代理、3D高斯生成方法、物理池和视觉监督代理）的协同工作来实现高质量的3D场景生成。因此，这篇论文的重点在于多代理系统的设计和应用，符合“Agent”分类的定义。` `3D建模` `场景生成`

> PhiP-G: Physics-Guided Text-to-3D Compositional Scene Generation

# 摘要

> # 摘要
在2D扩散先验的指导下，文本到3D资产生成已取得显著进展。然而，现有方法在处理组合场景时面临三大挑战：1）难以确保场景布局符合物理规律；2）难以精准捕捉复杂场景描述中的资产及其关系；3）基于LLM的布局方法在自主生成资产方面能力有限。为此，我们提出了一个全新的组合场景生成框架——PhiP-G，它将生成技术与基于世界模型的布局指导无缝结合。PhiP-G利用LLM代理分析复杂场景描述，生成场景图，并整合多模态2D生成代理和3D高斯生成方法，精准创建目标资产。在布局阶段，PhiP-G通过具备粘附能力的物理池和视觉监督代理，构建了一个用于布局预测和规划的世界模型。大量实验表明，PhiP-G显著提升了组合场景的生成质量和物理合理性。特别值得一提的是，PhiP-G在CLIP分数上达到了SOTA水平，在T$^3$Bench评估的生成质量上与顶尖方法持平，并将效率提升了24倍。

> Text-to-3D asset generation has achieved significant optimization under the supervision of 2D diffusion priors. However, when dealing with compositional scenes, existing methods encounter several challenges: 1). failure to ensure that composite scene layouts comply with physical laws; 2). difficulty in accurately capturing the assets and relationships described in complex scene descriptions; 3). limited autonomous asset generation capabilities among layout approaches leveraging large language models (LLMs). To avoid these compromises, we propose a novel framework for compositional scene generation, PhiP-G, which seamlessly integrates generation techniques with layout guidance based on a world model. Leveraging LLM-based agents, PhiP-G analyzes the complex scene description to generate a scene graph, and integrating a multimodal 2D generation agent and a 3D Gaussian generation method for targeted assets creation. For the stage of layout, PhiP-G employs a physical pool with adhesion capabilities and a visual supervision agent, forming a world model for layout prediction and planning. Extensive experiments demonstrate that PhiP-G significantly enhances the generation quality and physical rationality of the compositional scenes. Notably, PhiP-G attains state-of-the-art (SOTA) performance in CLIP scores, achieves parity with the leading methods in generation quality as measured by the T$^3$Bench, and improves efficiency by 24x.

[Arxiv](https://arxiv.org/abs/2502.00708)