# 少走少读：基于免调优多模态令牌剪枝提升视觉-语言导航效率

发布时间：2025年09月17日

`Agent` `交通运输`

> Walk and Read Less: Improving the Efficiency of Vision-and-Language Navigation via Tuning-Free Multimodal Token Pruning

# 摘要

> 大型模型在视觉-语言导航（VLN）任务上表现优异，但在资源受限环境中运行成本不菲。Token修剪通过缩减模型输入规模，在效率与性能损失最小化之间实现了理想权衡，然而现有研究未考虑VLN的特有挑战。例如，修剪造成的信息丢失可能因行走路径延长而反而推高计算成本。因此，难以识别无信息token会降低修剪的预期效率收益。为此，我们提出导航感知修剪（NAP）：借助导航特有属性，通过将token预过滤为前景与背景，简化了修剪流程。例如，根据智能体能否向该方向移动来过滤图像视图；我们还借助大型语言模型抽取导航相关指令。过滤后，我们专注于修剪背景token，从而最大限度减少信息损失。为进一步防止导航长度增加，我们通过移除低重要性导航节点来减少回溯。在标准VLN基准测试中，NAP的表现显著优于现有方法，在维持更高成功率的同时节省超50%的FLOPS。

> Large models achieve strong performance on Vision-and-Language Navigation (VLN) tasks, but are costly to run in resource-limited environments. Token pruning offers appealing tradeoffs for efficiency with minimal performance loss by reducing model input size, but prior work overlooks VLN-specific challenges. For example, information loss from pruning can effectively increase computational cost due to longer walks. Thus, the inability to identify uninformative tokens undermines the supposed efficiency gains from pruning. To address this, we propose Navigation-Aware Pruning (NAP), which uses navigation-specific traits to simplify the pruning process by pre-filtering tokens into foreground and background. For example, image views are filtered based on whether the agent can navigate in that direction. We also extract navigation-relevant instructions using a Large Language Model. After filtering, we focus pruning on background tokens, minimizing information loss. To further help avoid increases in navigation length, we discourage backtracking by removing low-importance navigation nodes. Experiments on standard VLN benchmarks show NAP significantly outperforms prior work, preserving higher success rates while saving more than 50% FLOPS.

[Arxiv](https://arxiv.org/abs/2509.15250)