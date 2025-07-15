# ExpStar：迈向多学科科学实验的自动评论生成

发布时间：2025年07月13日

`LLM应用`

> ExpStar: Towards Automatic Commentary Generation for Multi-discipline Scientific Experiments

# 摘要

> **实验评论**在描述实验流程、深入探讨科学原理以及融入安全规范方面至关重要。然而，目前人类教师需要依赖专业知识并投入大量时间来准备这些评论。为解决这一难题，我们提出了跨多学科科学实验的自动评论生成任务。尽管大型多模态模型（LMMs）在视频理解和推理方面取得了显著进展，但其生成细致且富有洞见的实验评论的能力仍待探索。本文主要贡献如下：（i）我们构建了首个专为实验评论生成设计的 	extit{ExpInstruct} 数据集，包含来自科学、医疗和工程三大领域的21个学科的7千余条步骤级评论。每条样本均包含实验流程描述、科学原理（如化学方程式和物理定律）以及安全指南。（ii）我们提出了基于检索增强机制的自动实验评论生成模型 ExpStar，能够自适应地利用外部知识。（iii）实验结果显示，ExpStar 在14个领先 LMMs 中表现最优，充分证明了我们数据集和模型的优越性。我们相信，ExpStar 将为 AI 辅助科学实验教学带来重要突破。


> Experiment commentary is crucial in describing the experimental procedures, delving into underlying scientific principles, and incorporating content-related safety guidelines. In practice, human teachers rely heavily on subject-specific expertise and invest significant time preparing such commentary. To address this challenge, we introduce the task of automatic commentary generation across multi-discipline scientific experiments. While recent progress in large multimodal models (LMMs) has demonstrated promising capabilities in video understanding and reasoning, their ability to generate fine-grained and insightful experiment commentary remains largely underexplored. In this paper, we make the following contributions: (i) We construct \textit{ExpInstruct}, the first dataset tailored for experiment commentary generation, featuring over 7\textit{K} step-level commentaries across 21 scientific subjects from 3 core disciplines (\ie, science, healthcare and engineering). Each sample includes procedural descriptions along with potential scientific principles (\eg, chemical equations and physical laws) and safety guidelines. (ii) We propose ExpStar, an automatic experiment commentary generation model that leverages a retrieval-augmented mechanism to adaptively access, evaluate, and utilize external knowledge. (iii) Extensive experiments show that our ExpStar substantially outperforms 14 leading LMMs, which highlights the superiority of our dataset and model. We believe that ExpStar holds great potential for advancing AI-assisted scientific experiment instruction.

[Arxiv](https://arxiv.org/abs/2507.09693)