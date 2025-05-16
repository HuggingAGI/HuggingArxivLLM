# CoT 指南：解析、预测与掌控推理模型的思维模式

发布时间：2025年05月15日

`LLM理论` `人工智能`

> The CoT Encyclopedia: Analyzing, Predicting, and Controlling how a Reasoning Model will Think

# 摘要

> 长链式思维（CoT）是现代大型语言模型有效应用的关键因素，但目前我们对支持这些能力的推理策略理解仍然有限。尽管此前有研究尝试通过预定义的策略类型对 CoT 进行分类，但这些方法受限于人类直觉，难以全面反映模型行为的多样性。本研究推出 CoT 百科全书，一个自下而上的框架，用于分析和引导模型推理。我们的方法从模型生成的 CoT 中自动提取多样化推理标准，将其嵌入语义空间，聚类为具有代表性的类别，并推导出对比标准以解释推理行为。通过人类评估，我们发现该框架生成的分析比现有方法更具可解释性和全面性。此外，我们展示了这一理解如何提升性能：我们可以预测模型可能使用的策略，并引导其转向更有效的替代方案。最后，我们揭示了实用见解，例如训练数据格式（如自由形式与多选题）对推理行为的影响远大于数据领域，强调了格式感知模型设计的重要性。

> Long chain-of-thought (CoT) is an essential ingredient in effective usage of modern large language models, but our understanding of the reasoning strategies underlying these capabilities remains limited. While some prior works have attempted to categorize CoTs using predefined strategy types, such approaches are constrained by human intuition and fail to capture the full diversity of model behaviors. In this work, we introduce the CoT Encyclopedia, a bottom-up framework for analyzing and steering model reasoning. Our method automatically extracts diverse reasoning criteria from model-generated CoTs, embeds them into a semantic space, clusters them into representative categories, and derives contrastive rubrics to interpret reasoning behavior. Human evaluations show that this framework produces more interpretable and comprehensive analyses than existing methods. Moreover, we demonstrate that this understanding enables performance gains: we can predict which strategy a model is likely to use and guide it toward more effective alternatives. Finally, we provide practical insights, such as that training data format (e.g., free-form vs. multiple-choice) has a far greater impact on reasoning behavior than data domain, underscoring the importance of format-aware model design.

[Arxiv](https://arxiv.org/abs/2505.10185)