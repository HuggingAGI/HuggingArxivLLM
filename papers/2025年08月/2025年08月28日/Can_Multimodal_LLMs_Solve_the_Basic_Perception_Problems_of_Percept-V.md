# 多模态大型语言模型能否攻克Percept-V的基本感知难题？

发布时间：2025年08月28日

`LLM应用` `基础理论`

> Can Multimodal LLMs Solve the Basic Perception Problems of Percept-V?

# 摘要

> 多模态大型语言模型（MLLMs）的推理能力近年来广受关注，在编码、数学、科学等前沿领域已取得诸多进展。然而，在评估MLLMs在包含基本形状和结构的纯净生成图像上执行简单感知任务的性能时，相关实验却极为有限。为此，该研究提出了一个名为Percept-V的数据集，包含7200张程序生成图像，平均分为30个类别，每个类别均测试视觉感知技能的组合。与现有数据集不同，Percept-V包含复杂度各异的基础任务，专门用于测试MLLMs的感知能力。研究人员随后在最先进的MLLMs（如GPT-4o、Gemini、Claude）及大型推理模型（LRMs，如OpenAI o4-mini、DeepSeek R1）上对该数据集进行了测试，以评估模型性能。实验结果与MLLMs擅长复杂任务的普遍认知相反：在所有类别中，随着问题复杂度的提升，模型性能均显著下降。性能分析还显示，在测试特定认知技能的不同类别中，这些MLLMs的准确率呈现相似趋势，且部分技能的难度明显高于其他技能。

> The reasoning abilities of Multimodal Large Language Models (MLLMs) have garnered a lot of attention in recent times, with advances made in frontiers like coding, mathematics, and science. However, very limited experiments have been done to assess their performance in simple perception tasks performed over uncontaminated, generated images containing basic shapes and structures. To address this issue, the paper introduces a dataset, Percept-V, containing a total of 7200 program-generated images equally divided into 30 categories, each testing a combination of visual perception skills. Unlike previously proposed datasets, Percept-V comprises very basic tasks of varying complexity that test the perception abilities of MLLMs. This dataset is then tested on state-of-the-art MLLMs like GPT-4o, Gemini, and Claude as well as Large Reasoning Models (LRMs) like OpenAI o4-mini and DeepSeek R1 to gauge their performance. Contrary to the evidence that MLLMs excel in many complex tasks, our experiments show a significant drop in the models' performance with increasing problem complexity across all categories. An analysis of the performances also reveals that the tested MLLMs exhibit a similar trend in accuracy across categories, testing a particular cognitive skill and find some skills to be more difficult than others.

[Arxiv](https://arxiv.org/abs/2508.21143)