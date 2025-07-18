# 去年夏天是谁编写了你的代码？我知晓！LLM生成代码的风格分析助力作者归属判定

发布时间：2025年06月18日

`LLM应用

摘要中提到的论文专注于利用大型语言模型（LLM）来识别AI生成的代码，特别是C程序的归属问题。他们开发了一种新的模型CodeT5-Authorship，并创建了一个基准测试集LLM-AuthorBench。这属于LLM的应用领域，因为他们将LLM用于特定任务，而不是研究其理论或机制。` `人工智能` `软件工程`

> I Know Which LLM Wrote Your Code Last Summer: LLM generated Code Stylometry for Authorship Attribution

# 摘要

> 识别AI生成的代码、深度伪造内容及其他合成内容已成为一项新兴的研究挑战。随着大型语言模型（LLMs）生成的代码日益普及，识别每段代码背后的特定模型变得愈发重要。本文首次系统性地研究了C程序的LLM归属识别问题。我们发布了CodeT5-Authorship，一种仅使用原始CodeT5编码器-解码器架构中的编码器层的新型模型，舍弃了解码器，专注于分类任务。我们的模型编码器输出（首令牌）通过一个带有GELU激活函数和dropout的双层分类头，生成可能作者的概率分布。为了评估我们的方法，我们引入了LLM-AuthorBench，一个包含32,000个可编译C程序的基准测试集，这些程序由八种先进的LLMs在各种任务中生成。我们比较了我们的模型与七种传统ML分类器和八种微调的Transformer模型，包括BERT、RoBERTa、CodeBERT、ModernBERT、DistilBERT、DeBERTa-V3、Longformer以及LoRA微调的Qwen2-1.5B。在二分类任务中，我们的模型在区分GPT-4.1和GPT-4o等密切相关模型生成的C程序时达到了97.56%的准确率，而对于五种领先LLMs（Gemini 2.5 Flash、Claude 3.5 Haiku、GPT-4.1、Llama 3.3和DeepSeek-V3）的多分类归属识别，准确率达到了95.40%。为了支持开放科学，我们发布了CodeT5-Authorship架构、LLM-AuthorBench基准测试集以及所有相关的Google Colab脚本至GitHub：https://github.com/LLMauthorbench/。

> Detecting AI-generated code, deepfakes, and other synthetic content is an emerging research challenge. As code generated by Large Language Models (LLMs) becomes more common, identifying the specific model behind each sample is increasingly important. This paper presents the first systematic study of LLM authorship attribution for C programs. We released CodeT5-Authorship, a novel model that uses only the encoder layers from the original CodeT5 encoder-decoder architecture, discarding the decoder to focus on classification. Our model's encoder output (first token) is passed through a two-layer classification head with GELU activation and dropout, producing a probability distribution over possible authors. To evaluate our approach, we introduce LLM-AuthorBench, a benchmark of 32,000 compilable C programs generated by eight state-of-the-art LLMs across diverse tasks. We compare our model to seven traditional ML classifiers and eight fine-tuned transformer models, including BERT, RoBERTa, CodeBERT, ModernBERT, DistilBERT, DeBERTa-V3, Longformer, and LoRA-fine-tuned Qwen2-1.5B. In binary classification, our model achieves 97.56% accuracy in distinguishing C programs generated by closely related models such as GPT-4.1 and GPT-4o, and 95.40% accuracy for multi-class attribution among five leading LLMs (Gemini 2.5 Flash, Claude 3.5 Haiku, GPT-4.1, Llama 3.3, and DeepSeek-V3). To support open science, we release the CodeT5-Authorship architecture, the LLM-AuthorBench benchmark, and all relevant Google Colab scripts on GitHub: https://github.com/LLMauthorbench/.

[Arxiv](https://arxiv.org/abs/2506.17323)