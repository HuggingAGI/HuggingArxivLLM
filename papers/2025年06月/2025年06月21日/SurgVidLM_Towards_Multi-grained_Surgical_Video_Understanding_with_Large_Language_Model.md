# SurgVidLM：基于大型语言模型的多粒度手术视频理解探索

发布时间：2025年06月21日

`LLM应用` `视频处理`

> SurgVidLM: Towards Multi-grained Surgical Video Understanding with Large Language Model

# 摘要

> 多模态大型语言模型在医疗领域的最新进展为手术场景和流程的理解提供了巨大助力。除了传统的图像方法，视频大型语言模型（Vid-LLMs）的探索成为捕捉手术中复杂信息序列的前沿途径。然而，目前仍缺乏专门针对精细手术视频理解任务的Vid-LLMs，这对于分析手术过程中的具体步骤或细节至关重要。为填补这一空白，我们提出了SurgVidLM——首个同时解决全面和精细手术视频理解的视频语言模型。为训练SurgVidLM，我们构建了包含超过31,000个视频-指令对的SVU-31K数据集，支持对手术过程的整体理解与详细分析。此外，我们引入了StageFocus机制——一个两阶段框架，用于对 surgical videos 进行多粒度、逐步理解。我们还开发了Multi-frequency Fusion Attention，以有效整合低频和高频视觉令牌，确保关键信息的保留。实验结果表明，SurgVidLM在全面和精细的视频理解任务中显著优于现有的Vid-LLMs，展示了其在捕捉复杂程序背景方面的卓越能力。

> Recent advances in Multimodal Large Language Models have demonstrated great potential in the medical domain, facilitating users to understand surgical scenes and procedures. Beyond image-based methods, the exploration of Video Large Language Models (Vid-LLMs) has emerged as a promising avenue for capturing the complex sequences of information involved in surgery. However, there is still a lack of Vid-LLMs specialized for fine-grained surgical video understanding tasks, which is crucial for analyzing specific processes or details within a surgical procedure. To bridge this gap, we propose SurgVidLM, the first video language model designed to address both full and fine-grained surgical video comprehension. To train our SurgVidLM, we construct the SVU-31K dataset which consists of over 31K video-instruction pairs, enabling both holistic understanding and detailed analysis of surgical procedures. Furthermore, we introduce the StageFocus mechanism which is a two-stage framework performing the multi-grained, progressive understanding of surgical videos. We also develop the Multi-frequency Fusion Attention to effectively integrate low and high-frequency visual tokens, ensuring the retention of critical information. Experimental results demonstrate that SurgVidLM significantly outperforms state-of-the-art Vid-LLMs in both full and fine-grained video understanding tasks, showcasing its superior capability in capturing complex procedural contexts.

[Arxiv](https://arxiv.org/abs/2506.17873)