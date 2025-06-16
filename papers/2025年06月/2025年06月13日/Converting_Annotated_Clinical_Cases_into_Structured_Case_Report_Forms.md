# 临床案例标注转结构化病例报告表

发布时间：2025年06月13日

`LLM应用` `数据科学`

> Converting Annotated Clinical Cases into Structured Case Report Forms

# 摘要

> 病例报告表 (CRFs) 在医学研究中被广泛应用，因为它们确保了临床研究结果的准确性、可靠性和有效性。然而，公开可用的、标注良好的 CRF 数据集非常稀缺，这限制了能够从临床笔记中填写 CRF 的槽填充系统的发展。为了解决这一问题，我们提出了一种利用现有信息提取数据集并将其转换为结构化 CRFs 的方法。我们采用的半自动转换方法已成功应用于两种语言（英语和意大利语）的 E3C 数据集，生成了一个高质量的 CRF 槽填充新数据集。实验结果表明，在关闭大型语言模型（零样本）中，槽填充在意大利语中达到了 59.7% 的准确率，在英语中达到了 67.3% 的准确率，而在开源模型上的表现则较差，这表明即使对于近期最先进的 LLMs，填写 CRFs 仍然是具有挑战性的。我们已将数据集发布在 https://huggingface.co/collections/NLP-FBK/e3c-to-crf-67b9844065460cbe42f80166。


> Case Report Forms (CRFs) are largely used in medical research as they ensure accuracy, reliability, and validity of results in clinical studies. However, publicly available, wellannotated CRF datasets are scarce, limiting the development of CRF slot filling systems able to fill in a CRF from clinical notes. To mitigate the scarcity of CRF datasets, we propose to take advantage of available datasets annotated for information extraction tasks and to convert them into structured CRFs. We present a semi-automatic conversion methodology, which has been applied to the E3C dataset in two languages (English and Italian), resulting in a new, high-quality dataset for CRF slot filling. Through several experiments on the created dataset, we report that slot filling achieves 59.7% for Italian and 67.3% for English on a closed Large Language Models (zero-shot) and worse performances on three families of open-source models, showing that filling CRFs is challenging even for recent state-of-the-art LLMs. We release the datest at https://huggingface.co/collections/NLP-FBK/e3c-to-crf-67b9844065460cbe42f80166

[Arxiv](https://arxiv.org/abs/2506.11666)