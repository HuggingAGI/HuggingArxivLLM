# MathFlow：提升多模态大模型对视觉数学问题的感知流畅度

发布时间：2025年03月19日

`LLM应用` `人工智能`

> MathFlow: Enhancing the Perceptual Flow of MLLMs for Visual Mathematical Problems

# 摘要

> 尽管在多种任务中表现卓越，多模态大语言模型（MLLMs）在视觉数学问题解决，特别是在准确感知和解读图表方面，仍有待进一步挖掘潜力。受人类典型解题过程启发，我们提出，从图表中提取有意义信息的感知能力至关重要，因为它直接决定了后续推理的效果。为此，我们开发了FlowVerse，一个全面的基准测试，将问题解决过程中涉及的所有信息划分为四个组成部分，并生成六个不同版本的问题进行评估。初步实验结果表明，现有MLLMs在从图表中提取关键信息、推理属性以及基于视觉输入进行复杂推理时存在明显局限。为应对这一挑战，我们提出了MathFlow，一个模块化的问题解决流水线，将感知和推理解耦为独立的阶段，从而实现对每个环节的独立优化。针对MLLMs的感知限制，我们专门训练了MathFlow-P-7B作为感知模型。实验结果表明，MathFlow-P-7B与多种闭源和开源推理模型集成后，性能显著提升。这不仅验证了MathFlow流水线的有效性，也展现了其与各类推理框架的良好兼容性。FlowVerse基准测试和代码可在https://github.com/MathFlow-zju/MathFlow获取。

> Despite impressive performance across diverse tasks, Multimodal Large Language Models (MLLMs) have yet to fully demonstrate their potential in visual mathematical problem-solving, particularly in accurately perceiving and interpreting diagrams. Inspired by typical processes of humans, we hypothesize that the perception capabilities to extract meaningful information from diagrams is crucial, as it directly impacts subsequent inference processes. To validate this hypothesis, we developed FlowVerse, a comprehensive benchmark that categorizes all information used during problem-solving into four components, which are then combined into six problem versions for evaluation. Our preliminary results on FlowVerse reveal that existing MLLMs exhibit substantial limitations when extracting essential information and reasoned property from diagrams and performing complex reasoning based on these visual inputs. In response, we introduce MathFlow, a modular problem-solving pipeline that decouples perception and inference into distinct stages, thereby optimizing each independently. Given the perceptual limitations observed in current MLLMs, we trained MathFlow-P-7B as a dedicated perception model. Experimental results indicate that MathFlow-P-7B yields substantial performance gains when integrated with various closed-source and open-source inference models. This demonstrates the effectiveness of the MathFlow pipeline and its compatibility to diverse inference frameworks. The FlowVerse benchmark and code are available at https://github.com/MathFlow-zju/MathFlow.

[Arxiv](https://arxiv.org/abs/2503.16549)