# Tab-MIA：用于评估大型语言模型中表格数据的成员推断攻击的基准测试数据集

发布时间：2025年07月23日

`LLM应用` `数据隐私` `机器学习`

> Tab-MIA: A Benchmark Dataset for Membership Inference Attacks on Tabular Data in LLMs

# 摘要

> 大型语言模型（LLMs）越来越多地在表格数据上进行训练，这些数据与无结构文本不同，通常以高度结构化和明确的形式包含个人身份信息（PII）。因此，隐私风险随之而来，因为敏感记录可能被模型无意中保留并通过数据提取或成员推断攻击（MIAs）泄露。虽然现有的MIAs方法主要针对文本内容，但当应用于结构化数据时，其效果和威胁可能有所不同，原因在于结构化数据的内容有限、数据类型多样、值分布独特以及列级别语义的特性。本文中，我们介绍了Tab-MIA，这是一个用于评估LLMs中表格数据成员推断攻击的基准数据集，并展示了如何使用它。Tab-MIA包含五个数据集，每个数据集以六种不同的编码格式表示。通过我们的Tab-MIA基准，我们首次对经过表格数据微调的LLMs进行了跨多种编码格式的最先进的MIAs方法评估。在评估中，我们分析了预训练LLMs对维基百科表格中结构化数据的记忆行为。我们的研究发现，LLMs以不同方式记忆表格数据，这种差异因编码格式而异，使得它们容易受到MIAs的提取。即使经过仅三个epoch的微调，模型也表现出高度的脆弱性，AUROC评分在大多数情况下接近90%。Tab-MIA使系统性评估这些风险成为可能，并为开发适用于LLMs中表格数据的隐私保护方法奠定了基础。

> Large language models (LLMs) are increasingly trained on tabular data, which, unlike unstructured text, often contains personally identifiable information (PII) in a highly structured and explicit format. As a result, privacy risks arise, since sensitive records can be inadvertently retained by the model and exposed through data extraction or membership inference attacks (MIAs). While existing MIA methods primarily target textual content, their efficacy and threat implications may differ when applied to structured data, due to its limited content, diverse data types, unique value distributions, and column-level semantics. In this paper, we present Tab-MIA, a benchmark dataset for evaluating MIAs on tabular data in LLMs and demonstrate how it can be used. Tab-MIA comprises five data collections, each represented in six different encoding formats. Using our Tab-MIA benchmark, we conduct the first evaluation of state-of-the-art MIA methods on LLMs finetuned with tabular data across multiple encoding formats. In the evaluation, we analyze the memorization behavior of pretrained LLMs on structured data derived from Wikipedia tables. Our findings show that LLMs memorize tabular data in ways that vary across encoding formats, making them susceptible to extraction via MIAs. Even when fine-tuned for as few as three epochs, models exhibit high vulnerability, with AUROC scores approaching 90% in most cases. Tab-MIA enables systematic evaluation of these risks and provides a foundation for developing privacy-preserving methods for tabular data in LLMs.

[Arxiv](https://arxiv.org/abs/2507.17259)