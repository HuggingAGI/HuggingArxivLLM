# LFTF：定位后微调，缓解大型语言模型中的性别偏见

发布时间：2025年05月21日

`LLM理论` `性别研究` `数据科学`

> LFTF: Locating First and Then Fine-Tuning for Mitigating Gender Bias in Large Language Models

# 摘要

> 如今，大型语言模型（LLMs）因其强大的性能而备受关注。然而，由于训练过程中不可避免地接触了具有社会偏见的数据，LLMs往往表现出性别偏见。为了更好地探索并量化LLMs中的性别偏见，我们提出了两个数据集：GenBiasEval和GenHintEval。GenBiasEval用于评估性别偏见程度，搭配AFGB-Score（绝对公平性别偏见分数）指标；GenHintEval则用于评估模型是否能提供与性别提示一致的响应，搭配UB-Score（无偏见分数）指标。此外，我们提出了LFTF（定位后微调）算法，以更有效地缓解性别偏见。该算法首先通过BMI（块缓解重要性分数）指标按相关性排序LLM块，然后对最相关的块进行微调，采用精心设计的损失函数。实验表明，LFTF算法在显著缓解性别偏见的同时，还能保持模型的一般能力。

> Nowadays, Large Language Models (LLMs) have attracted widespread attention due to their powerful performance. However, due to the unavoidable exposure to socially biased data during training, LLMs tend to exhibit social biases, particularly gender bias. To better explore and quantifying the degree of gender bias in LLMs, we propose a pair of datasets named GenBiasEval and GenHintEval, respectively. The GenBiasEval is responsible for evaluating the degree of gender bias in LLMs, accompanied by an evaluation metric named AFGB-Score (Absolutely Fair Gender Bias Score). Meanwhile, the GenHintEval is used to assess whether LLMs can provide responses consistent with prompts that contain gender hints, along with the accompanying evaluation metric UB-Score (UnBias Score). Besides, in order to mitigate gender bias in LLMs more effectively, we present the LFTF (Locating First and Then Fine-Tuning) algorithm.The algorithm first ranks specific LLM blocks by their relevance to gender bias in descending order using a metric called BMI (Block Mitigating Importance Score). Based on this ranking, the block most strongly associated with gender bias is then fine-tuned using a carefully designed loss function. Numerous experiments have shown that our proposed LFTF algorithm can significantly mitigate gender bias in LLMs while maintaining their general capabilities.

[Arxiv](https://arxiv.org/abs/2505.15475)