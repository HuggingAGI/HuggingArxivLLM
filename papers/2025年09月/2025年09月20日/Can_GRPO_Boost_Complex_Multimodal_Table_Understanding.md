# GRPO能否提升复杂多模态表格理解？

发布时间：2025年09月20日

`强化学习` `基础理论`

> Can GRPO Boost Complex Multimodal Table Understanding?

# 摘要

> 现有的表格理解方法因表格结构复杂、逻辑推理繁琐而面临挑战。尽管监督微调（SFT）在现有研究中占据主流，但强化学习（RL）（如群体相对策略优化（GRPO））虽已展现潜力，却在表格场景中受限于初始策略准确率低和奖励机制粗糙的问题。本文提出三阶段强化学习框架Table-R1，通过以下方式提升多模态表格理解能力：（1）预热阶段，激活初始感知与推理能力；（2）感知对齐GRPO（PA-GRPO），利用连续树编辑距离相似度（TEDS）奖励识别表格结构与内容；（3）提示补全GRPO（HC-GRPO），基于提示引导的问题，对剩余步骤采用细粒度奖励机制。大量实验结果显示，Table-R1在保留数据集和外推数据集上均能显著提升模型的表格推理性能，且大幅超越SFT与GRPO。值得关注的是，集成Table-R1后，Qwen2-VL-7B模型不仅超越了更大规模的专用表格理解模型（如Table-LLaVA 13B），甚至在保留数据集上性能媲美闭源模型GPT-4o。这表明Table-R1各阶段在克服初始化瓶颈和奖励稀疏性方面成效显著，进而推动了稳健的多模态表格理解研究。

> Existing table understanding methods face challenges due to complex table structures and intricate logical reasoning. While supervised finetuning (SFT) dominates existing research, reinforcement learning (RL), such as Group Relative Policy Optimization (GRPO), has shown promise but struggled with low initial policy accuracy and coarse rewards in tabular contexts. In this paper, we introduce Table-R1, a three-stage RL framework that enhances multimodal table understanding through: (1) Warm-up that prompts initial perception and reasoning capabilities, (2) Perception Alignment GRPO (PA-GRPO), which employs continuous Tree-Edit-Distance Similarity (TEDS) rewards for recognizing table structures and contents, and (3) Hint-Completion GRPO (HC-GRPO), which utilizes fine-grained rewards of residual steps based on the hint-guided question. Extensive experiments demonstrate that Table-R1 can boost the model's table reasoning performance obviously on both held-in and held-out datasets, outperforming SFT and GRPO largely. Notably, Qwen2-VL-7B with Table-R1 surpasses larger specific table understanding models (e.g., Table-LLaVA 13B), even achieving comparable performance to the closed-source model GPT-4o on held-in datasets, demonstrating the efficacy of each stage of Table-R1 in overcoming initialization bottlenecks and reward sparsity, thereby advancing robust multimodal table understanding.

[Arxiv](https://arxiv.org/abs/2509.16889)