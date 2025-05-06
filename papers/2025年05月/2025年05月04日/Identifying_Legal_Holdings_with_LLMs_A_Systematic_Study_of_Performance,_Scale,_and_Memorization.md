# 利用大型语言模型识别法律判决：性能、规模及记忆的研究

发布时间：2025年05月04日

`LLM应用`

> Identifying Legal Holdings with LLMs: A Systematic Study of Performance, Scale, and Memorization

# 摘要

> 随着大型语言模型（LLMs）能力的不断提升，评估它们在已建立的基准测试中的表现至关重要。本研究通过一系列实验，评估了现代LLMs（参数规模从30亿到900亿以上）在CaseHOLD上的性能。CaseHOLD是一个用于识别案例判决的法律基准数据集。实验结果显示了显著的「规模效应」——随着模型规模的增大，性能提升明显。GPT4o和AmazonNovaPro等更强大的模型分别达到了0.744和0.720的宏F1分数，与该数据集上已发表的最佳结果相媲美。值得注意的是，这些结果无需任何复杂的技术训练、微调或少样本提示。为确保这些优异结果并非源于对训练数据中司法意见的死记硬背，我们开发并应用了一种新的引用匿名化测试方法。这种方法在保持语义含义的同时，确保案例名称和引用均为虚构内容。在此条件下，模型仍保持了强劲的性能（宏F1为0.728），表明性能并非源于死记硬背。这些发现既展现了LLMs在法律任务中的潜力，也揭示了当前的局限性，对自动化法律分析和法律基准的发展与评估具有重要意义。

> As large language models (LLMs) continue to advance in capabilities, it is essential to assess how they perform on established benchmarks. In this study, we present a suite of experiments to assess the performance of modern LLMs (ranging from 3B to 90B+ parameters) on CaseHOLD, a legal benchmark dataset for identifying case holdings. Our experiments demonstrate ``scaling effects'' - performance on this task improves with model size, with more capable models like GPT4o and AmazonNovaPro achieving macro F1 scores of 0.744 and 0.720 respectively. These scores are competitive with the best published results on this dataset, and do not require any technically sophisticated model training, fine-tuning or few-shot prompting. To ensure that these strong results are not due to memorization of judicial opinions contained in the training data, we develop and utilize a novel citation anonymization test that preserves semantic meaning while ensuring case names and citations are fictitious. Models maintain strong performance under these conditions (macro F1 of 0.728), suggesting the performance is not due to rote memorization. These findings demonstrate both the promise and current limitations of LLMs for legal tasks with important implications for the development and measurement of automated legal analytics and legal benchmarks.

[Arxiv](https://arxiv.org/abs/2505.02172)