# # 模型内部探秘：探索现代语言模型中的词汇身份与曲折形态学

发布时间：2025年06月02日

`LLM理论

摘要中提到的研究主要集中在分析大语言模型内部如何编码语言信息，探讨了词汇身份和形态屈折特征在不同层中的表现，以及模型在编码这些信息时所使用的机制。这属于对大语言模型工作原理和机制的深入研究，因此应归类为LLM理论。` `人工智能`

> Model Internal Sleuthing: Finding Lexical Identity and Inflectional Morphology in Modern Language Models

# 摘要

> 基于Transformer的大语言模型在现代NLP领域占据主导地位，但目前我们对它们如何编码语言信息的理解主要基于早期模型如BERT和GPT-2的研究。为了深入理解当代语言模型的工作机制，我们对比了经典架构（BERT、DeBERTa、GPT-2）和当代大语言模型（Pythia、OLMo-2、Gemma-2、Qwen2.5、Llama-3.1）在词汇身份和形态屈折特征上的表征方式。通过训练线性与非线性分类器分析各层激活，我们发现：模型在早期层以线性方式编码词汇信息，而随着层数加深逐渐转向非线性编码；同时，形态屈折信息在各层中始终保持均匀可访问且线性可分。进一步分析表明，这些模型通过可泛化的抽象编码形态屈折特征，但主要依赖记忆机制编码词汇身份。令人惊讶的是，尽管模型在架构、规模和训练策略（包括预训练和指令微调版本）上存在差异，上述模式在所有测试的16个模型中均保持一致。这一发现表明，尽管大语言模型技术取得了长足进步，但Transformer模型在语言信息组织方式上仍具相似性，提示这些特性可能是下一词预测的基础，且在预训练早期即被学习。我们的代码可在https://github.com/ml5885/model_internal_sleuthing获取。

> Large transformer-based language models dominate modern NLP, yet our understanding of how they encode linguistic information is rooted in studies of early models like BERT and GPT-2. To better understand today's language models, we investigate how both classical architectures (BERT, DeBERTa, GPT-2)and contemporary large language models (Pythia, OLMo-2, Gemma-2, Qwen2.5, Llama-3.1) represent lexical identity and inflectional morphology. We train linear and nonlinear classifiers on layer-wise activations to predict word lemmas and inflectional features. We discover that models concentrate lexical information linearly in early layers and increasingly nonlinearly in later layers, while keeping inflectional information uniformly accessible and linearly separable throughout the layers. Further analysis reveals that these models encode inflectional morphology through generalizable abstractions, but rely predominantly on memorization to encode lexical identity. Remarkably, these patterns emerge across all 16 models we test, despite differences in architecture, size, and training regime (including pretrained and instruction-tuned variants). This consistency suggests that, despite substantial advances in LLM technologies, transformer models organize linguistic information in similar ways, indicating that these properties could be fundamental for next token prediction and are learned early during pretraining. Our code is available at https://github.com/ml5885/model_internal_sleuthing.

[Arxiv](https://arxiv.org/abs/2506.02132)