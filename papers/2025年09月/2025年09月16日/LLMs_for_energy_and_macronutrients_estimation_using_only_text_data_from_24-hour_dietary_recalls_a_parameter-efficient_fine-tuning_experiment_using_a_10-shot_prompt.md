# 大型语言模型仅用24小时膳食回顾文本数据估计能量与宏量营养素：基于10-shot提示的参数高效微调实验

发布时间：2025年09月16日

`LLM应用` `医疗健康`

> LLMs for energy and macronutrients estimation using only text data from 24-hour dietary recalls: a parameter-efficient fine-tuning experiment using a 10-shot prompt

# 摘要

> BACKGROUND: 目前大多数估算营养成分的人工智能工具都依赖图像输入，而大型语言模型（LLMs）能否仅通过食物的文本描述准确预测营养价值，这一问题尚不清楚。若该方法可行，将实现无需拍照的简易饮食监测。
METHODS: 研究数据来源于美国国家健康与营养检查调查（NHANES）中12-19岁青少年的24小时饮食回顾。我们采用开源量化大型语言模型，通过10样本思维链提示方法，仅依据食物及其数量的文本信息估算能量和五种宏量营养素。随后应用参数高效微调（PEFT）以验证预测准确性是否提升，NHANES计算值作为能量、蛋白质、碳水化合物、总糖、膳食纤维及总脂肪的真实参考标准。
RESULTS: 在11,281名青少年（男性49.9%，平均年龄15.4岁）的合并数据中，未微调的基础模型预测效果较差：能量的平均绝对误差（MAE）达652.08，所有指标的林氏一致性相关系数（Lin's CCC）均<0.46。经微调后，模型性能显著提升——各子集的能量MAE降至171.34至190.90之间，且所有结果指标的Lin's CCC均超过0.89。
CONCLUSIONS: 经思维链提示与PEFT微调后，仅通过文本输入的开源大型语言模型，能准确从24小时饮食回顾中预测能量及宏量营养素值。该方法为开发低负担、基于文本的饮食监测工具提供了新可能。

> BACKGROUND: Most artificial intelligence tools used to estimate nutritional content rely on image input. However, whether large language models (LLMs) can accurately predict nutritional values based solely on text descriptions of foods consumed remains unknown. If effective, this approach could enable simpler dietary monitoring without the need for photographs. METHODS: We used 24-hour dietary recalls from adolescents aged 12-19 years in the National Health and Nutrition Examination Survey (NHANES). An open-source quantized LLM was prompted using a 10-shot, chain-of-thought approach to estimate energy and five macronutrients based solely on text strings listing foods and their quantities. We then applied parameter-efficient fine-tuning (PEFT) to evaluate whether predictive accuracy improved. NHANES-calculated values served as the ground truth for energy, proteins, carbohydrates, total sugar, dietary fiber and total fat. RESULTS: In a pooled dataset of 11,281 adolescents (49.9% male, mean age 15.4 years), the vanilla LLM yielded poor predictions. The mean absolute error (MAE) was 652.08 for energy and the Lin's CCC <0.46 across endpoints. In contrast, the fine-tuned model performed substantially better, with energy MAEs ranging from 171.34 to 190.90 across subsets, and Lin's CCC exceeding 0.89 for all outcomes. CONCLUSIONS: When prompted using a chain-of-thought approach and fine-tuned with PEFT, open-source LLMs exposed solely to text input can accurately predict energy and macronutrient values from 24-hour dietary recalls. This approach holds promise for low-burden, text-based dietary monitoring tools.

[Arxiv](https://arxiv.org/abs/2509.13268)