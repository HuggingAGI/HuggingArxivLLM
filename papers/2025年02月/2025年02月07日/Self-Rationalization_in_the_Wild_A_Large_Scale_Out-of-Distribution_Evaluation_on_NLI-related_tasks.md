# 真实世界中的自我合理化：大规模自然语言推理任务的分布外评估

发布时间：2025年02月07日

`LLM应用` `人工智能`

> Self-Rationalization in the Wild: A Large Scale Out-of-Distribution Evaluation on NLI-related tasks

# 摘要

> 自由文本解释表达性强且易于理解，但现有数据集中标注解释数据的缺失为训练可解释性预测模型带来了挑战。我们研究了如何利用现有解释数据集进行自我理性化，并评估模型在分布外（OOD）任务上的性能。通过对 T5-Large 和 OLMo-7B 模型进行微调，我们评估了微调数据质量、样本数量及小样本选择方法的影响。我们在涵盖自然语言推理（NLI）、事实核查和摘要幻觉检测三个任务的 19 个多样化 OOD 数据集上对模型进行了评估。针对生成解释的评估，我们对 13 个模型进行了人类研究，并分析其与可接受性分数（T5-11B）及三个无参考 LLM 指标的关联。结果显示，可接受性分数与人类判断相关性最高，证明其在评估自由文本解释中的有效性。研究发现：1）少量标注样本即可有效适应模型生成 OOD 解释；2）相比样本选择策略，微调数据源对 OOD 性能影响更大；3）标签预测准确率更高的模型通常生成更优解释，体现在更高的可接受性分数上。

> Free-text explanations are expressive and easy to understand, but many datasets lack annotated explanation data, making it challenging to train models for explainable predictions. To address this, we investigate how to use existing explanation datasets for self-rationalization and evaluate models' out-of-distribution (OOD) performance. We fine-tune T5-Large and OLMo-7B models and assess the impact of fine-tuning data quality, the number of fine-tuning samples, and few-shot selection methods. The models are evaluated on 19 diverse OOD datasets across three tasks: natural language inference (NLI), fact-checking, and hallucination detection in abstractive summarization. For the generated explanation evaluation, we conduct a human study on 13 selected models and study its correlation with the Acceptability score (T5-11B) and three other LLM-based reference-free metrics. Human evaluation shows that the Acceptability score correlates most strongly with human judgments, demonstrating its effectiveness in evaluating free-text explanations. Our findings reveal: 1) few annotated examples effectively adapt models for OOD explanation generation; 2) compared to sample selection strategies, fine-tuning data source has a larger impact on OOD performance; and 3) models with higher label prediction accuracy tend to produce better explanations, as reflected by higher Acceptability scores.

[Arxiv](https://arxiv.org/abs/2502.04797)