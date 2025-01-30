# 人类基因组之书：字词、句段与篇章

发布时间：2025年01月22日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLM）的迁移学习能力来处理基因组数据，特别是将自然语言处理技术应用于DNA序列的分析和注释。论文中提到的模型训练、微调以及将DNA序列分割成“单词”、“句子”和“段落”的过程，都是LLM在实际应用中的具体体现。因此，这篇论文应归类为LLM应用。` `基因组学` `生物信息学`

> Human Genome Book: Words, Sentences and Paragraphs

# 摘要

> 自2001年人类基因组测序项目完成以来，基因调控编辑和蛋白质结构预测等领域取得了显著进展。然而，面对海量的基因组数据，能够完全注释和理解的部分仍然有限。如果将基因组比作一本书，构建其对应的单词、句子和段落一直是研究的热点。最近，大型语言模型中的迁移学习研究为这一挑战提供了新思路。多语言迁移能力，即评估在源语言上微调的模型如何应用于其他语言，已在多语言预训练模型中得到了广泛研究。同样，将自然语言能力迁移到“DNA语言”也得到了验证。基于这些发现，我们首先训练了一个能够将语言能力从英语迁移到DNA序列的基础模型，并构建了DNA词汇表，将DNA单词映射到其英语对应词。随后，我们使用英语数据集对该模型进行微调，开发出能够将DNA序列分割成句子和段落的模型。利用这些模型，我们处理了GRCh38.p14人类基因组，将其分割、标记并组织成由基因组“单词”、“句子”和“段落”组成的“书”。此外，基于DNA到英语的词汇映射，我们还创建了基因组书的“英语版本”。这项研究为理解基因组提供了新视角，并为开发创新的DNA搜索、生成和分析工具开辟了令人兴奋的可能性。

> Since the completion of the human genome sequencing project in 2001, significant progress has been made in areas such as gene regulation editing and protein structure prediction. However, given the vast amount of genomic data, the segments that can be fully annotated and understood remain relatively limited. If we consider the genome as a book, constructing its equivalents of words, sentences, and paragraphs has been a long-standing and popular research direction. Recently, studies on transfer learning in large language models have provided a novel approach to this challenge.Multilingual transfer ability, which assesses how well models fine-tuned on a source language can be applied to other languages, has been extensively studied in multilingual pre-trained models. Similarly, the transfer of natural language capabilities to "DNA language" has also been validated. Building upon these findings, we first trained a foundational model capable of transferring linguistic capabilities from English to DNA sequences. Using this model, we constructed a vocabulary of DNA words and mapped DNA words to their English equivalents.Subsequently, we fine-tuned this model using English datasets for paragraphing and sentence segmentation to develop models capable of segmenting DNA sequences into sentences and paragraphs. Leveraging these models, we processed the GRCh38.p14 human genome by segmenting, tokenizing, and organizing it into a "book" comprised of genomic "words," "sentences," and "paragraphs." Additionally, based on the DNA-to-English vocabulary mapping, we created an "English version" of the genomic book. This study offers a novel perspective for understanding the genome and provides exciting possibilities for developing innovative tools for DNA search, generation, and analysis.

[Arxiv](https://arxiv.org/abs/2501.16982)