# Table2LaTeX-RL：基于强化多模态语言模型的表格图像高保真LaTeX代码生成

发布时间：2025年09月22日

`LLM应用` `基础理论`

> Table2LaTeX-RL: High-Fidelity LaTeX Code Generation from Table Images via Reinforced Multimodal Language Models

# 摘要

> 本研究聚焦于表格图像转LaTeX代码生成任务，旨在通过视觉输入自动重建高质量、可直接发表的表格。该任务的核心难点在于准确处理复杂表格（如尺寸庞大、结构深度嵌套、单元格内容语义丰富或不规则的表格），现有方法在这类表格上常显乏力。我们首先开展全面分析，明确了核心挑战，并指出了现有评估协议的不足。为解决这些问题，我们提出增强型多模态大型语言模型（MLLM）框架，将预训练MLLM在大规模表格转LaTeX数据集上进行微调。为进一步提升生成质量，我们引入基于组相对策略优化（GRPO）的双奖励强化学习策略。与仅优化文本输出的传统方法不同，我们的方法同时融合了LaTeX代码的结构级奖励和从渲染结果计算的视觉保真度奖励，实现了对视觉输出质量的直接优化。我们采用结合TEDS-Structure与CW-SSIM的混合评估协议，结果显示我们的方法性能达到最先进水平，尤其在结构复杂的表格上表现突出，充分证明了方法的有效性和稳健性。

> In this work, we address the task of table image to LaTeX code generation, with the goal of automating the reconstruction of high-quality, publication-ready tables from visual inputs. A central challenge of this task lies in accurately handling complex tables -- those with large sizes, deeply nested structures, and semantically rich or irregular cell content -- where existing methods often fail. We begin with a comprehensive analysis, identifying key challenges and highlighting the limitations of current evaluation protocols. To overcome these issues, we propose a reinforced multimodal large language model (MLLM) framework, where a pre-trained MLLM is fine-tuned on a large-scale table-to-LaTeX dataset. To further improve generation quality, we introduce a dual-reward reinforcement learning strategy based on Group Relative Policy Optimization (GRPO). Unlike standard approaches that optimize purely over text outputs, our method incorporates both a structure-level reward on LaTeX code and a visual fidelity reward computed from rendered outputs, enabling direct optimization of the visual output quality. We adopt a hybrid evaluation protocol combining TEDS-Structure and CW-SSIM, and show that our method achieves state-of-the-art performance, particularly on structurally complex tables, demonstrating the effectiveness and robustness of our approach.

[Arxiv](https://arxiv.org/abs/2509.17589)