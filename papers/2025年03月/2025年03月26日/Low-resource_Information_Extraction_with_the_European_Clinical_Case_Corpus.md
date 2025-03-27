# 基于欧洲临床案例语料库的低资源信息抽取研究

发布时间：2025年03月26日

`LLM应用`

> Low-resource Information Extraction with the European Clinical Case Corpus

# 摘要

> 我们推出了 E3C-3.0，一个多语言医学领域数据集，包含标注了疾病和检验结果关系的临床案例。该数据集不仅收录了五种语言（英语、法语、意大利语、西班牙语和巴斯克语）的原文本，还包含了从英语来源翻译并投射到五种目标语言（希腊语、意大利语、波兰语、斯洛伐克语和斯洛文尼亚语）的文本。我们采用了一种半自动方法，结合基于大型语言模型（LLMs）的自动标注投射和人工修订。实验表明，当前最先进的 LLM 通过在 E3C-3.0 数据集上进行微调，能够显著提升性能。此外，跨语言迁移学习表现出色，有效缓解了数据稀缺问题。最后，我们分别在原文本和投射文本上进行了性能对比。数据集已发布：https://huggingface.co/collections/NLP-FBK/e3c-projected-676a7d8221608d60e4e9fd89 。


> We present E3C-3.0, a multilingual dataset in the medical domain, comprising clinical cases annotated with diseases and test-result relations. The dataset includes both native texts in five languages (English, French, Italian, Spanish and Basque) and texts translated and projected from the English source into five target languages (Greek, Italian, Polish, Slovak, and Slovenian). A semi-automatic approach has been implemented, including automatic annotation projection based on Large Language Models (LLMs) and human revision. We present several experiments showing that current state-of-the-art LLMs can benefit from being fine-tuned on the E3C-3.0 dataset. We also show that transfer learning in different languages is very effective, mitigating the scarcity of data. Finally, we compare performance both on native data and on projected data. We release the data at https://huggingface.co/collections/NLP-FBK/e3c-projected-676a7d6221608d60e4e9fd89 .

[Arxiv](https://arxiv.org/abs/2503.20568)