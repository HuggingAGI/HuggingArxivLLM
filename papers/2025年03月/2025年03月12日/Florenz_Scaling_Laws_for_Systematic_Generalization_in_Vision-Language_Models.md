# Florenz：视觉-语言模型的系统性泛化扩展定律研究

发布时间：2025年03月12日

`其他` `视觉语言模型` `跨语言处理`

> Florenz: Scaling Laws for Systematic Generalization in Vision-Language Models

# 摘要

> 跨语言迁移使视觉语言模型 (VLM) 能够仅使用单语言训练数据在多种语言中执行视觉任务。然而，现有方法面临多语言诅咒，为实现多语言能力而牺牲下游任务性能，难以处理词汇歧义，并且落后于近期进展。本研究探讨了单语言 VLM 在多语言任务中的系统性泛化扩展规律，重点关注模型规模和已见训练样本的影响。我们提出了 Florenz，一种结合预训练 VLM Florence-2 和大型语言模型 Gemma-2 的单语言编码器-解码器 VLM，参数范围从 0.4B 到 11.2B。Florenz 在一个合成数据集上进行了不同计算预算的训练，该数据集在图像描述任务上故意设计为语言覆盖不完整，从而测试从完全覆盖的翻译任务中进行泛化的能力。我们发现，间接学习未见的任务-语言组合不仅遵循扩展规律，而且通过我们的数据生成管道和提出的 Florenz 模型族，即使仅提供翻译任务的数据，特定语言的图像描述能力也能够显现。在下游数据集混合上进行微调，可以实现具有竞争力的性能，并在多模态机器翻译（Multi30K、CoMMuTE）、词汇消歧（CoMMuTE）和图像描述（Multi30K、XM3600、COCO Karpathy）方面展现出有前景的扩展趋势。

> Cross-lingual transfer enables vision-language models (VLMs) to perform vision tasks in various languages with training data only in one language. Current approaches rely on large pre-trained multilingual language models. However, they face the curse of multilinguality, sacrificing downstream task performance for multilingual capabilities, struggling with lexical ambiguities, and falling behind recent advances. In this work, we study the scaling laws of systematic generalization with monolingual VLMs for multilingual tasks, focusing on the impact of model size and seen training samples. We propose Florenz, a monolingual encoder-decoder VLM with 0.4B to 11.2B parameters combining the pre-trained VLM Florence-2 and the large language model Gemma-2. Florenz is trained with varying compute budgets on a synthetic dataset that features intentionally incomplete language coverage for image captioning, thus, testing generalization from the fully covered translation task. We show that not only does indirectly learning unseen task-language pairs adhere to a scaling law, but also that with our data generation pipeline and the proposed Florenz model family, image captioning abilities can emerge in a specific language even when only data for the translation task is available. Fine-tuning on a mix of downstream datasets yields competitive performance and demonstrates promising scaling trends in multimodal machine translation (Multi30K, CoMMuTE), lexical disambiguation (CoMMuTE), and image captioning (Multi30K, XM3600, COCO Karpathy).

[Arxiv](https://arxiv.org/abs/2503.09443)