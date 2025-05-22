# LEANCODE：深入理解模型，助力预训练大型语言模型的代码精简

发布时间：2025年05月20日

`LLM应用

理由：这篇论文专注于优化大型语言模型在处理代码任务时的效率，通过提出LeanCode方法来减少计算复杂度。这属于LLM的具体应用和改进，因此归类为LLM应用。` `软件工程`

> LEANCODE: Understanding Models Better for Code Simplification of Pre-trained Large Language Models

# 摘要

> 面向代码的大型语言模型往往伴随着显著的计算复杂度，且这一复杂度会随着输入代码序列的长度显著增加。为此，我们提出了名为LeanCode的代码简化方法，旨在通过减少训练和预测时间来提升效率。该方法利用代码上下文中的注意力分数来衡量标记的重要性，并建议根据平均上下文感知注意力分数选择性地移除标记，而非采用所有输入的平均分数。在代码搜索等分类任务中，LeanCode采用编码器中`CLS'标记的注意力分数进行分类。同时，它还利用编码器-解码器之间的注意力分数来判断标记的重要性，从而处理代码摘要等序列到序列的任务。我们的评估结果显示，LeanCode在代码搜索和代码摘要任务上均优于现有的SOTA方法DietCode和Slimcode，分别实现了60%和16%的提升，以及29%和27%的提升。


> Large Language Models for code often entail significant computational complexity, which grows significantly with the length of the input code sequence. We propose LeanCode for code simplification to reduce training and prediction time, leveraging code contexts in utilizing attention scores to represent the tokens' importance. We advocate for the selective removal of tokens based on the average context-aware attention scores rather than average scores across all inputs. LeanCode uses the attention scores of `CLS' tokens within the encoder for classification tasks, such as code search. It also employs the encoder-decoder attention scores to determine token significance for sequence-to-sequence tasks like code summarization.Our evaluation shows LeanCode's superiority over the SOTAs DietCode and Slimcode, with improvements of 60% and 16% for code search, and 29% and 27% for code summarization, respectively.

[Arxiv](https://arxiv.org/abs/2505.14759)