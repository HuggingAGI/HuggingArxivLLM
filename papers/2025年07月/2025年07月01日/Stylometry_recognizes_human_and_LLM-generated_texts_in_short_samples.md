# Stylometry能够识别短样本中的人类文本和LLM生成的文本

发布时间：2025年07月01日

`LLM应用

理由：这篇论文研究了如何通过文体学方法区分大型语言模型（LLMs）生成的文本与人类文本，探讨了模型归属、知识产权和AI伦理使用等关键问题。研究内容涉及LLM生成文本的分析和分类，属于LLM的应用领域。` `文本分析`

> Stylometry recognizes human and LLM-generated texts in short samples

# 摘要

> 本文研究了通过文体学方法区分大型语言模型（LLMs）生成文本与人类文本的可能性，旨在解决模型归属、知识产权和AI伦理使用等关键问题。文体学作为一门研究文本风格和作者归属的技术，已被广泛应用于文本分析。将其应用于LLM生成文本，我们成功识别出其特有的写作模式。本文基于维基百科构建了一个基准数据集，包含以下四类文本：(a) 人类编写的词条摘要，(b) 由GPT-3.5/4、LLaMa 2/3、Orca和Falcon等LLMs生成的纯机器文本，(c) 经过T5、BART、Gensim和Sumy等多种文本摘要方法处理的文本，以及(d) 经过Dipper和T5等改写方法处理的文本。这些10句长的文本通过决策树和LightGBM等树基模型进行分类，采用了StyloMetrix（人工设计）和n-gram（自研管道）两种文体学特征，涵盖词汇、语法、句法和标点模式等信息。实验结果显示，在7类多分类场景下，交叉验证的马修斯相关系数高达0.87；在二分类场景下，准确率介于0.79到1.0之间，以维基百科和GPT-4为例，在平衡数据集上的准确率高达0.98。通过Shapley加性解释法，我们发现维基百科文本具有特定的文体特征，包括过度使用的词汇，以及LLM文本相较于人类文本在语法上的更高标准化。这些结果表明——尤其是在当前LLMs技术日新月异的背景下——至少对于一种明确的文本类型，我们能够有效区分机器生成和人类生成的文本。

> The paper explores stylometry as a method to distinguish between texts created by Large Language Models (LLMs) and humans, addressing issues of model attribution, intellectual property, and ethical AI use. Stylometry has been used extensively to characterise the style and attribute authorship of texts. By applying it to LLM-generated texts, we identify their emergent writing patterns. The paper involves creating a benchmark dataset based on Wikipedia, with (a) human-written term summaries, (b) texts generated purely by LLMs (GPT-3.5/4, LLaMa 2/3, Orca, and Falcon), (c) processed through multiple text summarisation methods (T5, BART, Gensim, and Sumy), and (d) rephrasing methods (Dipper, T5). The 10-sentence long texts were classified by tree-based models (decision trees and LightGBM) using human-designed (StyloMetrix) and n-gram-based (our own pipeline) stylometric features that encode lexical, grammatical, syntactic, and punctuation patterns. The cross-validated results reached a performance of up to .87 Matthews correlation coefficient in the multiclass scenario with 7 classes, and accuracy between .79 and 1. in binary classification, with the particular example of Wikipedia and GPT-4 reaching up to .98 accuracy on a balanced dataset. Shapley Additive Explanations pinpointed features characteristic of the encyclopaedic text type, individual overused words, as well as a greater grammatical standardisation of LLMs with respect to human-written texts. These results show -- crucially, in the context of the increasingly sophisticated LLMs -- that it is possible to distinguish machine- from human-generated texts at least for a well-defined text type.

[Arxiv](https://arxiv.org/abs/2507.00838)