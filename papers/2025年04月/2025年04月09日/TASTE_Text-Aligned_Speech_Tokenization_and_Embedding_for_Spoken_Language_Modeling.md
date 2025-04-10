# TASTE：文本对齐语音分词与嵌入，面向语音语言建模

发布时间：2025年04月09日

`LLM理论` `语音处理`

> TASTE: Text-Aligned Speech Tokenization and Embedding for Spoken Language Modeling

# 摘要

> 大型语言模型 (LLMs) 在文本处理上表现出色，但受限于文本输入输出的依赖。为实现更自然的人机交互，近期研究致力于开发既能听懂又能生成语音的语音语言模型 (SLM)。语音-文本联合建模为此提供了一个有前景的方向。然而，由于模态不匹配，当前SLM仍落后于文本LLM。其中关键差距在于语音与文本令牌的序列长度差异。为解决这一问题，我们提出了Text-Aligned Speech Tokenization and Embedding (TASTE)，一种通过在分词阶段将语音令牌与对应文本转录对齐，直接解决模态差距的方法。我们提出了一种基于特殊聚合机制，并以语音重建为目标的训练方法来实现这一目标。实验表明，TASTE在保留关键副语言信息的同时，能大幅缩短令牌序列长度。借助TASTE，我们可以利用参数高效的微调技术（如低秩适配 LoRA）将文本LLMs适配为有效的SLMs。在SALMON和StoryCloze等基准任务上的结果表明，基于TASTE的SLMs性能与完整的微调方法相当。据我们所知，TASTE是首个利用重建目标端到端自动学习与文本对齐的语音分词和嵌入，专门用于语音语言建模的方法。我们的演示、代码和模型已在GitHub上公开：https://github.com/mtkresearch/TASTE-SpokenLM。

> Large Language Models (LLMs) excel in text-based natural language processing tasks but remain constrained by their reliance on textual inputs and outputs. To enable more natural human-LLM interaction, recent progress have focused on deriving a spoken language model (SLM) that can not only listen but also generate speech. To achieve this, a promising direction is to conduct speech-text joint modeling. However, recent SLM still lag behind text LLM due to the modality mismatch. One significant mismatch can be the sequence lengths between speech and text tokens. To address this, we introduce Text-Aligned Speech Tokenization and Embedding (TASTE), a method that directly addresses the modality gap by aligning speech token with the corresponding text transcription during the tokenization stage. We propose a method that can achieve this through the special aggregation mechanism and with speech reconstruction as the training objective. We conduct extensive experiments and show that TASTE can preserve essential paralinguistic information while dramatically reducing the token sequence length. Furthermore, by leveraging TASTE, we can adapt text-based LLMs into effective SLMs with parameter-efficient fine-tuning techniques such as Low-Rank Adaptation (LoRA). Experimental results on benchmark tasks, including SALMON and StoryCloze, demonstrate that TASTE-based SLMs perform similarly to previous full-finetuning methods. To our knowledge, TASTE is the first end-to-end approach that utilizes a reconstruction objective to automatically learn a text-aligned speech tokenization and embedding suitable for spoken language modeling. Our demo, code, and models are publicly available at https://github.com/mtkresearch/TASTE-SpokenLM.

[Arxiv](https://arxiv.org/abs/2504.07053)