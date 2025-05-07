# 提升模型对齐：开源大语言模型的群体智慧

发布时间：2025年05月05日

`LLM理论` `人工智能` `机器学习`

> Improving Model Alignment Through Collective Intelligence of Open-Source LLMS

# 摘要

> 构建有益且无害的大型语言模型（LLMs）需要有效的模型对齐方法，这需要基于人类指令和反馈的高质量数据。然而，构建这类数据集成本高昂、难以扩展，且可能在多样性和泛化性上存在限制。为解决这些问题，我们提出了多智能体对齐（MoAA），通过整合多种语言模型的优势，为模型对齐提供高质量数据。采用MoAA不仅增强了监督微调和偏好优化，还显著提升了模型性能，例如在Arena-Hard上将LLaMA-3.1-8B-Instruct的胜率从19.5提升至48.3，在AlpacaEval2上从22.33提升至57.23。这表明MoAA是一种极具潜力的模型对齐方案。此外，MoAA还支持自我改进流水线，使基于其生成数据微调的模型超越自身初始能力，证明了这一方法在推动开源LLMs前沿方面的有效性。相关数据和代码即将开放发布。

> Building helpful and harmless large language models (LLMs) requires effective model alignment approach based on human instructions and feedback, which necessitates high-quality human-labeled data. Constructing such datasets is often expensive and hard to scale, and may face potential limitations on diversity and generalization. To address these challenges, we introduce Mixture of Agents Alignment (MoAA), that leverages the collective strengths of various language models to provide high-quality data for model alignment. By employing MoAA, we enhance both supervised fine-tuning and preference optimization, leading to improved performance compared to using a single model alone to generate alignment data (e.g. using GPT-4o alone). Evaluation results show that our approach can improve win rate of LLaMA-3.1-8B-Instruct from 19.5 to 48.3 on Arena-Hard and from 22.33 to 57.23 on AlpacaEval2, highlighting a promising direction for model alignment through this new scalable and diverse synthetic data recipe. Furthermore, we demonstrate that MoAA enables a self-improvement pipeline, where models finetuned on MoA-generated data surpass their own initial capabilities, providing evidence that our approach can push the frontier of open-source LLMs without reliance on stronger external supervision. Data and code will be released.

[Arxiv](https://arxiv.org/abs/2505.03059)