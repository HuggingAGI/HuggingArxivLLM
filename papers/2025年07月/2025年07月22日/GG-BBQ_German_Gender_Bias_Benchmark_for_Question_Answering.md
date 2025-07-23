# GG-BBQ: 德语性别偏见基准测试在问答任务中的应用

发布时间：2025年07月22日

`LLM应用

摘要讨论了将大型语言模型（LLMs）用于评估性别偏见，属于LLM的应用层面。` `公平性评估`

> GG-BBQ: German Gender Bias Benchmark for Question Answering

# 摘要

> 在自然语言处理（NLP）领域，公平性评估涉及偏见评估及减少由此带来的伤害。通常，我们会通过基准数据集（如问答任务）来评估模型预测在性别认同等多个维度上的偏见。在本研究中，我们参考Parrish等人（2022）的问答偏见基准，对德语大型语言模型（LLMs）中的性别偏见进行了评估。我们首先将该基准数据集中的性别认同子集模板进行了机器翻译，将其从英语转换为德语。随后，我们邀请语言专家对机器翻译中的错误进行了人工审核和修正。这一过程表明，人工修订在创建用于性别偏见评估的数据集时至关重要，因为从英语到德语（具有语性性别）的机器翻译存在一定的局限性。我们的最终数据集包含两个子集：子集I包含与性别认同相关的群体术语，而子集II则用专有名词替换了群体术语。我们使用这个新创建的数据集对多个用于德语NLP的LLMs进行了评估，并报告了准确性和偏见分数。结果显示，所有模型都存在偏见，既符合现有的社会刻板印象，也与之相反。

> Within the context of Natural Language Processing (NLP), fairness evaluation is often associated with the assessment of bias and reduction of associated harm. In this regard, the evaluation is usually carried out by using a benchmark dataset, for a task such as Question Answering, created for the measurement of bias in the model's predictions along various dimensions, including gender identity. In our work, we evaluate gender bias in German Large Language Models (LLMs) using the Bias Benchmark for Question Answering by Parrish et al. (2022) as a reference. Specifically, the templates in the gender identity subset of this English dataset were machine translated into German. The errors in the machine translated templates were then manually reviewed and corrected with the help of a language expert. We find that manual revision of the translation is crucial when creating datasets for gender bias evaluation because of the limitations of machine translation from English to a language such as German with grammatical gender. Our final dataset is comprised of two subsets: Subset-I, which consists of group terms related to gender identity, and Subset-II, where group terms are replaced with proper names. We evaluate several LLMs used for German NLP on this newly created dataset and report the accuracy and bias scores. The results show that all models exhibit bias, both along and against existing social stereotypes.

[Arxiv](https://arxiv.org/abs/2507.16410)