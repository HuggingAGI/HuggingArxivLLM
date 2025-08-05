# 文化卫士：迈向多语言安全应用的（文化感知）数据集与守护模型

发布时间：2025年08月03日

`LLM应用` `内容安全` `多语言处理`

> CultureGuard: Towards Culturally-Aware Dataset and Guard Model for Multilingual Safety Applications

# 摘要

> 大型语言模型（LLMs）在代理应用中的广泛应用凸显了对稳健安全防护模型的迫切需求。尽管英语内容安全研究已较为成熟，但由于收集文化适配标注数据集的高昂成本，非英语语言在这一领域进展有限。我们提出了CultureGuard，一种在多种语言中整理文化适配、高质量安全数据集的创新解决方案。我们的方法引入了一个四阶段合成数据生成和过滤管道：文化数据分离、文化数据适配、机器翻译和质量过滤。这一管道实现了将Nemotron-Content-Safety-Dataset-V2英语安全数据集转换并扩展至八种不同语言：阿拉伯语、德语、西班牙语、法语、印地语、日语、泰语和中文。生成的数据集Nemotron-Content-Safety-Dataset-Multilingual-v1包含9种语言的386,661个样本，并通过LoRA基础微调支持训练Llama-3.1-Nemotron-Safety-Guard-Multilingual-8B-v1。最终模型在多个多语言内容安全基准上达到最先进水平。我们还对最新开放LLMs进行多语言安全基准测试，发现这些LLMs在非英语语言提示下更易产生不安全回应。这项工作朝着通过开发文化感知安全防护模型来缩小多语言LLMs安全差距迈出重要一步。

> The increasing use of Large Language Models (LLMs) in agentic applications highlights the need for robust safety guard models. While content safety in English is well-studied, non-English languages lack similar advancements due to the high cost of collecting culturally aligned labeled datasets. We present CultureGuard, a novel solution for curating culturally aligned, high-quality safety datasets across multiple languages. Our approach introduces a four-stage synthetic data generation and filtering pipeline: cultural data segregation, cultural data adaptation, machine translation, and quality filtering. This pipeline enables the conversion and expansion of the Nemotron-Content-Safety-Dataset-V2 English safety dataset into eight distinct languages: Arabic, German, Spanish, French, Hindi, Japanese, Thai, and Chinese. The resulting dataset, Nemotron-Content-Safety-Dataset-Multilingual-v1, comprises 386,661 samples in 9 languages and facilitates the training of Llama-3.1-Nemotron-Safety-Guard-Multilingual-8B-v1 via LoRA-based fine-tuning. The final model achieves state-of-the-art performance on several multilingual content safety benchmarks. We also benchmark the latest open LLMs on multilingual safety and observe that these LLMs are more prone to give unsafe responses when prompted in non-English languages. This work represents a significant step toward closing the safety gap in multilingual LLMs by enabling the development of culturally aware safety guard models.

[Arxiv](https://arxiv.org/abs/2508.01710)