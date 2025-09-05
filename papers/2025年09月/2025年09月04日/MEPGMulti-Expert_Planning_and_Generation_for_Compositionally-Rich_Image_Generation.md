# MEPG：面向组合丰富图像生成的多专家规划与生成

发布时间：2025年09月04日

`LLM应用` `媒体与娱乐`

> MEPG:Multi-Expert Planning and Generation for Compositionally-Rich Image Generation

# 摘要

> 文本到图像扩散模型的图像质量已臻卓越，但在处理复杂多元素提示和风格多样性不足方面仍存挑战。为解决这些局限，我们提出多专家规划生成框架（MEPG），将位置与风格感知的大型语言模型（LLMs）与空间语义专家模块协同融合。该框架包含两个核心组件：（1）位置-风格感知（PSA）模块：利用监督微调的LLM将输入提示分解为精确的空间坐标和风格编码的语义指令；（2）多专家扩散（MED）模块：通过跨局部与全局区域的动态专家路由实现跨区域生成。在各局部区域生成过程中，通过基于注意力的门控机制为每个空间分区选择性激活专用模型（如写实专家、风格化专家）。该架构支持专家模型的轻量级集成与替换，具备强大的可扩展性。此外，交互式界面支持实时空间布局编辑及从专家库中进行区域风格选择。实验表明，MEPG在图像质量和风格多样性上均显著优于相同骨干的基线模型。

> Text-to-image diffusion models have achieved remarkable image quality, but they still struggle with complex, multiele ment prompts, and limited stylistic diversity. To address these limitations, we propose a Multi-Expert Planning and Gen eration Framework (MEPG) that synergistically integrates position- and style-aware large language models (LLMs) with spatial-semantic expert modules. The framework comprises two core components: (1) a Position-Style-Aware (PSA) module that utilizes a supervised fine-tuned LLM to decom pose input prompts into precise spatial coordinates and style encoded semantic instructions; and (2) a Multi-Expert Dif fusion (MED) module that implements cross-region genera tion through dynamic expert routing across both local regions and global areas. During the generation process for each lo cal region, specialized models (e.g., realism experts, styliza tion specialists) are selectively activated for each spatial par tition via attention-based gating mechanisms. The architec ture supports lightweight integration and replacement of ex pert models, providing strong extensibility. Additionally, an interactive interface enables real-time spatial layout editing and per-region style selection from a portfolio of experts. Ex periments show that MEPG significantly outperforms base line models with the same backbone in both image quality
  and style diversity.

[Arxiv](https://arxiv.org/abs/2509.04126)