# # MedHal：医疗幻觉检测评估数据集

发布时间：2025年04月11日

`LLM应用` `医疗AI`

> MedHal: An Evaluation Dataset for Medical Hallucination Detection

# 摘要

> # 数据集介绍
我们推出MedHal，一个专为评估模型能否检测医学文本中幻觉内容而设计的新型大规模数据集。目前，幻觉检测方法在医学等专业领域应用时面临重大限制，这些限制可能带来灾难性后果。

现有医学数据集存在以下问题：样本量过小（仅几百个样本），或仅专注于单一任务（如问答或自然语言推理）。MedHal通过以下方式填补了这些空白：
- 纳入多样化的医学文本来源和任务
- 提供大量适合训练医学幻觉检测模型的标注样本
- 包含对事实不一致的解释，以指导模型学习

我们通过训练和评估一个基线医学幻觉检测模型，展示了MedHal的实用性。结果显示，与通用幻觉检测方法相比，MedHal在医学场景下表现更优。这一资源使医学文本生成系统的评估更加高效，同时减少了对昂贵专家审查的依赖，从而加速医学AI研究的发展。

> We present MedHal, a novel large-scale dataset specifically designed to evaluate if models can detect hallucinations in medical texts. Current hallucination detection methods face significant limitations when applied to specialized domains like medicine, where they can have disastrous consequences. Existing medical datasets are either too small, containing only a few hundred samples, or focus on a single task like Question Answering or Natural Language Inference. MedHal addresses these gaps by: (1) incorporating diverse medical text sources and tasks; (2) providing a substantial volume of annotated samples suitable for training medical hallucination detection models; and (3) including explanations for factual inconsistencies to guide model learning. We demonstrate MedHal's utility by training and evaluating a baseline medical hallucination detection model, showing improvements over general-purpose hallucination detection approaches. This resource enables more efficient evaluation of medical text generation systems while reducing reliance on costly expert review, potentially accelerating the development of medical AI research.

[Arxiv](https://arxiv.org/abs/2504.08596)