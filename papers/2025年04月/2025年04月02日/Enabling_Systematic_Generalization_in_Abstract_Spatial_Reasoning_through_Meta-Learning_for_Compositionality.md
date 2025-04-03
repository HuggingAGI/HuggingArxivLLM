# 通过元学习赋能抽象空间推理，实现系统性泛化与组合性的统一。

发布时间：2025年04月02日

`LLM理论` `抽象空间推理` `元学习`

> Enabling Systematic Generalization in Abstract Spatial Reasoning through Meta-Learning for Compositionality

# 摘要

> 系统性泛化能力是指从已知组件中理解和生成新的组合的能力。尽管大型语言模型在各领域取得了进展，但它们在面对新的组合场景时往往表现不佳，这凸显了系统性泛化方面的局限性。关于神经网络是否具备系统性泛化能力的争论持续存在，但近期研究表明，针对组合性的元学习方法能显著提升这一能力。然而，这些发现主要局限于语言领域，其在其他任务中的应用仍有待探索。本研究将针对组合性的元学习方法扩展到抽象空间推理领域。为此，我们引入了【数学公式】——一个用于评估模型从已知几何变换（如平移、旋转）到这些变换的新组合（如平移+旋转）的系统性泛化能力的数据集。实验结果表明，通过针对组合性的元学习训练的基于变换器的编解码模型，能够系统性地泛化到之前未见过的变换组合，显著优于现有的大型语言模型，包括o3-mini、GPT-4o和Gemini 2.0 Flash，这些模型未能展现出类似的系统性行为。我们的研究结果表明，元学习在提升系统性方面具有显著效果，尤其是在超越语言任务的场景中，为构建更加稳健和通用的模型提供了重要方向。

> Systematic generalization refers to the capacity to understand and generate novel combinations from known components. Despite recent progress by large language models (LLMs) across various domains, these models often fail to extend their knowledge to novel compositional scenarios, revealing notable limitations in systematic generalization. There has been an ongoing debate about whether neural networks possess the capacity for systematic generalization, with recent studies suggesting that meta-learning approaches designed for compositionality can significantly enhance this ability. However, these insights have largely been confined to linguistic problems, leaving their applicability to other tasks an open question. In this study, we extend the approach of meta-learning for compositionality to the domain of abstract spatial reasoning. To this end, we introduce $\textit{SYGAR}$-a dataset designed to evaluate the capacity of models to systematically generalize from known geometric transformations (e.g., translation, rotation) of two-dimensional objects to novel combinations of these transformations (e.g., translation+rotation). Our results show that a transformer-based encoder-decoder model, trained via meta-learning for compositionality, can systematically generalize to previously unseen transformation compositions, significantly outperforming state-of-the-art LLMs, including o3-mini, GPT-4o, and Gemini 2.0 Flash, which fail to exhibit similar systematic behavior. Our findings highlight the effectiveness of meta-learning in promoting systematicity beyond linguistic tasks, suggesting a promising direction toward more robust and generalizable models.

[Arxiv](https://arxiv.org/abs/2504.01445)