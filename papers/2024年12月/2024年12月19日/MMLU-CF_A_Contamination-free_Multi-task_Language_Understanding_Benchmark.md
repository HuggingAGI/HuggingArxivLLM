# MMLU-CF：一项无污染的多任务语言理解基准

发布时间：2024年12月19日

`LLM应用` `语言模型` `评估标准`

> MMLU-CF: A Contamination-free Multi-task Language Understanding Benchmark

# 摘要

> 像大规模多任务语言理解（MMLU）这样的多项选择题（MCQ）数据集，被广泛用于评估大型语言模型（LLMs）的常识、理解及解决问题的能力。然而，这些基准的开源特性以及LLMs广泛的训练数据来源，不可避免地造成了基准污染，致使评估结果不可靠。为减轻这一问题，我们提出了一个无污染且更具挑战性的MCQ基准——MMLU-CF。此基准通过避免无意和恶意的数据泄露，重新评估LLMs对世界知识的理解。为避免无意的数据泄露，我们从更广泛的领域获取数据，并设计了三条去污规则。为防止恶意的数据泄露，我们将基准划分为难度和主题分布相似的验证集和测试集。测试集保持闭源以确保结果可靠，而验证集则公开可用，以提高透明度并便于独立验证。我们对主流LLMs的评估表明，强大的GPT-4o在测试集上仅取得5-shot得分73.4％和0-shot得分71.9％，这显示出我们的方法在创建更严格且无污染的评估标准方面是有效的。GitHub存储库位于https://github.com/microsoft/MMLU-CF ，数据集可参考https://huggingface.co/datasets/microsoft/MMLU-CF。

> Multiple-choice question (MCQ) datasets like Massive Multitask Language Understanding (MMLU) are widely used to evaluate the commonsense, understanding, and problem-solving abilities of large language models (LLMs). However, the open-source nature of these benchmarks and the broad sources of training data for LLMs have inevitably led to benchmark contamination, resulting in unreliable evaluation results. To alleviate this issue, we propose a contamination-free and more challenging MCQ benchmark called MMLU-CF. This benchmark reassesses LLMs' understanding of world knowledge by averting both unintentional and malicious data leakage. To avoid unintentional data leakage, we source data from a broader domain and design three decontamination rules. To prevent malicious data leakage, we divide the benchmark into validation and test sets with similar difficulty and subject distributions. The test set remains closed-source to ensure reliable results, while the validation set is publicly available to promote transparency and facilitate independent verification. Our evaluation of mainstream LLMs reveals that the powerful GPT-4o achieves merely a 5-shot score of 73.4% and a 0-shot score of 71.9% on the test set, which indicates the effectiveness of our approach in creating a more rigorous and contamination-free evaluation standard. The GitHub repository is available at https://github.com/microsoft/MMLU-CF and the dataset refers to https://huggingface.co/datasets/microsoft/MMLU-CF.

[Arxiv](https://arxiv.org/abs/2412.15194)