# ATP-LLaVA：针对大型视觉语言模型的自适应令牌剪枝

发布时间：2024年11月30日

`LLM应用` `计算机视觉` `多模态任务`

> ATP-LLaVA: Adaptive Token Pruning for Large Vision Language Models

# 摘要

> 大型视觉语言模型（LVLMs）在多模态任务方面成绩斐然。但在资源有限的设备上处理长视觉标记，其计算成本高昂得让人却步。此前的方法已在大型语言模型（LLM）解码器层中察觉到视觉标记的冗余，并通过采用预定义或固定比例来修剪标记，以此降低计算开销。不过，我们发现修剪比例在不同的 LLM 层和实例（图像 - 提示对）中影响各异。所以，开发一种分层和依实例而定的视觉标记修剪策略，对有效平衡计算成本与模型性能至关重要。我们提出了 ATP - LLaVA 这一创新方法，它能为每个 LLM 层自适应地确定特定实例的标记修剪比例。具体而言，我们引入了自适应标记修剪（ATP）模块，它能依据输入实例自适应地算出重要性得分和修剪阈值。ATP 模块能在任意两个 LLM 层之间无缝融合，计算开销微乎其微。另外，我们还制定了空间增强修剪（SAP）策略，从标记冗余和空间建模的视角修剪视觉标记。我们的方法将平均标记数量减少 75%，同时保持性能，在七个广泛使用的基准测试中，性能仅下降了极小的 1.9%。该项目页面可通过 https://yxxxb.github.io/ATP - LLaVA - page/ 访问。

> Large Vision Language Models (LVLMs) have achieved significant success across multi-modal tasks. However, the computational cost of processing long visual tokens can be prohibitively expensive on resource-limited devices. Previous methods have identified redundancy in visual tokens within the Large Language Model (LLM) decoder layers and have mitigated this by pruning tokens using a pre-defined or fixed ratio, thereby reducing computational overhead. Nonetheless, we observe that the impact of pruning ratio varies across different LLM layers and instances (image-prompt pairs). Therefore, it is essential to develop a layer-wise and instance-wise vision token pruning strategy to balance computational cost and model performance effectively. We propose ATP-LLaVA, a novel approach that adaptively determines instance-specific token pruning ratios for each LLM layer. Specifically, we introduce an Adaptive Token Pruning (ATP) module, which computes the importance score and pruning threshold based on input instance adaptively. The ATP module can be seamlessly integrated between any two LLM layers with negligible computational overhead. Additionally, we develop a Spatial Augmented Pruning (SAP) strategy that prunes visual tokens with both token redundancy and spatial modeling perspectives. Our approach reduces the average token count by 75% while maintaining performance, with only a minimal 1.9% degradation across seven widely used benchmarks. The project page can be accessed via https://yxxxb.github.io/ATP-LLaVA-page/.

[Arxiv](https://arxiv.org/abs/2412.00447)