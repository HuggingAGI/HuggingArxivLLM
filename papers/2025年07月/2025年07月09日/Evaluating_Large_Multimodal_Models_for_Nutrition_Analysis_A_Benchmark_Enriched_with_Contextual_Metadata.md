# 评测大型多模态模型在营养分析领域的表现：基于情境元数据增强的基准测试

发布时间：2025年07月09日

`LLM应用` `营养分析` `食品科学`

> Evaluating Large Multimodal Models for Nutrition Analysis: A Benchmark Enriched with Contextual Metadata

# 摘要

> 大型多模态模型（LMMs）在餐品图像的营养分析中得到广泛应用。然而，现有研究主要局限于对专有模型（如GPT-4）的评估，导致对各类LMMs的潜力挖掘不足。此外，整合上下文元数据及其与推理增强器的交互效果仍待探索。本研究旨在探讨如何通过解析基于GPS坐标（转换为地点/场所类型）、时间戳（转化为餐品/日期类型）以及餐品内容的上下文元数据，来提升LMMs在估计关键营养指标方面的性能，这些指标包括热量、三大宏量营养素（蛋白质、碳水化合物、脂肪）以及分量大小。我们还推出了即将公开发布的全新食品图像数据集ACETADA。这一开放数据集提供由营养师验证的营养信息，为我们的分析奠定了基础。通过对八种LMMs（包括四种开源模型和四种闭源模型）的评估，我们首先验证了整合上下文元数据相较于单纯基于图像的简单提示方法的优势。随后，我们展示了这种上下文信息的整合如何增强多种推理增强器（如思维链、多模态思维链、尺度提示、少量样本学习和专家角色模拟）的效能。实证结果表明，通过智能整合元数据并结合简单的提示策略，可以显著降低预测营养值的平均绝对误差（MAE）和平均绝对百分比误差（MAPE）。本研究凸显了具备上下文感知能力的LMMs在提升营养分析精度方面的潜力。

> Large Multimodal Models (LMMs) are increasingly applied to meal images for nutrition analysis. However, existing work primarily evaluates proprietary models, such as GPT-4. This leaves the broad range of LLMs underexplored. Additionally, the influence of integrating contextual metadata and its interaction with various reasoning modifiers remains largely uncharted. This work investigates how interpreting contextual metadata derived from GPS coordinates (converted to location/venue type), timestamps (transformed into meal/day type), and the food items present can enhance LMM performance in estimating key nutritional values. These values include calories, macronutrients (protein, carbohydrates, fat), and portion sizes. We also introduce ACETADA, a new food-image dataset slated for public release. This open dataset provides nutrition information verified by the dietitian and serves as the foundation for our analysis. Our evaluation across eight LMMs (four open-weight and four closed-weight) first establishes the benefit of contextual metadata integration over straightforward prompting with images alone. We then demonstrate how this incorporation of contextual information enhances the efficacy of reasoning modifiers, such as Chain-of-Thought, Multimodal Chain-of-Thought, Scale Hint, Few-Shot, and Expert Persona. Empirical results show that integrating metadata intelligently, when applied through straightforward prompting strategies, can significantly reduce the Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE) in predicted nutritional values. This work highlights the potential of context-aware LMMs for improved nutrition analysis.

[Arxiv](https://arxiv.org/abs/2507.07048)