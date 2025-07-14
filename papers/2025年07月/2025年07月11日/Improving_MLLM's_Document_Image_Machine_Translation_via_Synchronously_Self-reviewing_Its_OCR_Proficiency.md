# 提升多语言大语言模型的文档图像机器翻译：通过同步自我审查OCR能力

发布时间：2025年07月11日

`LLM应用` `文档处理` `机器翻译`

> Improving MLLM's Document Image Machine Translation via Synchronously Self-reviewing Its OCR Proficiency

# 摘要

> 多模态大型语言模型（MLLMs）在OCR等文档图像任务中表现优异，但在文档图像机器翻译（DIMT）方面却面临挑战，因为这需要同时处理跨模态和跨语言的问题。传统的通过监督微调（SFT）提升DIMT能力的方法，常常导致模型遗忘其原有的OCR等单语能力。为了解决这一问题，我们提出了一种名为“同步自我回顾”（SSR）的新型微调范式，灵感来源于“双语认知优势”概念。具体来说，SSR会提示模型在生成翻译文本之前先生成OCR文本，这使得模型能够利用其强大的OCR能力，同时学习跨语言翻译。实验结果表明，SSR学习方法能够有效缓解灾难性遗忘，提升MLLMs在OCR和DIMT任务上的表现。

> Multimodal Large Language Models (MLLMs) have shown strong performance in document image tasks, especially Optical Character Recognition (OCR). However, they struggle with Document Image Machine Translation (DIMT), which requires handling both cross-modal and cross-lingual challenges. Previous efforts to enhance DIMT capability through Supervised Fine-Tuning (SFT) on the DIMT dataset often result in the forgetting of the model's existing monolingual abilities, such as OCR. To address these challenges, we introduce a novel fine-tuning paradigm, named Synchronously Self-Reviewing (SSR) its OCR proficiency, inspired by the concept "Bilingual Cognitive Advantage". Specifically, SSR prompts the model to generate OCR text before producing translation text, which allows the model to leverage its strong monolingual OCR ability while learning to translate text across languages. Comprehensive experiments demonstrate the proposed SSR learning helps mitigate catastrophic forgetting, improving the generalization ability of MLLMs on both OCR and DIMT tasks.

[Arxiv](https://arxiv.org/abs/2507.08309)