# 探索交互式深度伪造分析

发布时间：2025年01月02日

`LLM应用

理由：这篇论文主要探讨了如何通过对多模态大型语言模型（MLLMs）进行指令调优来实现交互式深度伪造分析。论文提出了一个由GPT辅助构建的指令跟随数据集、一个基准测试以及一个采用低秩适应（LoRA）模块的交互式深度伪造分析系统。这些内容都属于将大型语言模型应用于特定任务（深度伪造分析）的范畴，因此分类为“LLM应用”。` `深度伪造检测` `多模态学习`

> Towards Interactive Deepfake Analysis

# 摘要

> 现有的深度伪造分析方法主要依赖判别模型，应用场景受限。本文通过对多模态大型语言模型（MLLMs）进行指令调优，探索交互式深度伪造分析。面对数据集和基准测试的缺乏以及训练效率低下的挑战，我们提出了（1）由GPT辅助构建的DFA-Instruct指令跟随数据集，（2）用于全面评估MLLMs在深度伪造检测、分类和伪影描述能力的DFA-Bench基准测试，以及（3）采用低秩适应（LoRA）模块的DFA-GPT交互式深度伪造分析系统，作为社区的强基线。数据集和代码将在https://github.com/lxq1000/DFA-Instruct上开源，以推动进一步研究。

> Existing deepfake analysis methods are primarily based on discriminative models, which significantly limit their application scenarios. This paper aims to explore interactive deepfake analysis by performing instruction tuning on multi-modal large language models (MLLMs). This will face challenges such as the lack of datasets and benchmarks, and low training efficiency. To address these issues, we introduce (1) a GPT-assisted data construction process resulting in an instruction-following dataset called DFA-Instruct, (2) a benchmark named DFA-Bench, designed to comprehensively evaluate the capabilities of MLLMs in deepfake detection, deepfake classification, and artifact description, and (3) construct an interactive deepfake analysis system called DFA-GPT, as a strong baseline for the community, with the Low-Rank Adaptation (LoRA) module. The dataset and code will be made available at https://github.com/lxq1000/DFA-Instruct to facilitate further research.

[Arxiv](https://arxiv.org/abs/2501.01164)