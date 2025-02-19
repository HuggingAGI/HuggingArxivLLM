# None of the Others：辨别多选题LLM评估基准中推理与记忆的通用方法

发布时间：2025年02月18日

`LLM理论` `评估方法`

> None of the Others: a General Technique to Distinguish Reasoning from Memorization in Multiple-Choice LLM Evaluation Benchmarks

# 摘要

> 在 LLM 评估中，推理通常通过在数学问题上进行数值变化与记忆区分开来。我们提出了一种适用于多选题的通用变体方法，这种方法彻底将正确答案与模型之前见过的任何标记或概念脱钩，要求 LLM 真正理解和推理（而非单纯记忆）才能正确作答。我们利用这种方法，对公开和专有的最新 LLM 在两个英文和西班牙语可用的数据集上进行了评估：公开的 MMLU 基准和私有的 UNED-Access 2024 数据集。结果显示，所有模型在我们提出的变体下都出现了显著的准确性下降，MMLU 的平均损失为 57%，UNED-Access 2024 为 50%，各模型间的下降幅度从 10% 到 93% 不等。值得注意的是，实验中表现最准确的模型（OpenAI-o3-mini）并非最稳健的（DeepSeek-R1-70B），这表明在标准评估中表现最佳的模型未必具备更强的推理能力。此外，我们观察到公共数据集（与私有数据集相比）以及原语言问题（与人工翻译相比）的准确性下降更为明显，这表明了数据污染的存在，同时也揭示了当前 LLM 回答中记忆/记忆机制的重要作用。

> In LLM evaluations, reasoning is often distinguished from recall/memorization by performing numerical variations to math-oriented questions. Here we introduce a general variation method for multiple-choice questions that completely dissociates the correct answer from previously seen tokens or concepts, requiring LLMs to understand and reason (rather than memorizing) in order to answer correctly. Using this method, we evaluate state-of-the-art proprietary and open-source LLMs on two datasets available in English and Spanish: the public MMLU benchmark and the private UNED-Access 2024 dataset. Results show that all models experience remarkable accuracy drops under our proposed variation, with an average loss of 57% on MMLU and 50% on UNED-Access 2024, ranging from 10% to 93% across models. Notably, the most accurate model in our experimentation (OpenAI-o3-mini) is not the most robust (DeepSeek-R1-70B), suggesting that the best models in standard evaluations may not be the ones with better reasoning capabilities. Also, we see larger accuracy drops in public (vs private) datasets and questions posed in their original language (vs a manual translation), which are signs of contamination and also point to a relevant role of recall/memorization in current LLMs' answers.

[Arxiv](https://arxiv.org/abs/2502.12896)