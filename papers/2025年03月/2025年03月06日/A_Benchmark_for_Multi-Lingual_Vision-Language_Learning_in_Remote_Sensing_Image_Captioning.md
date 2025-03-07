# # 基准测试
用于遥感图像描述生成的多语言视觉语言学习基准测试

发布时间：2025年03月06日

`LLM应用`

> A Benchmark for Multi-Lingual Vision-Language Learning in Remote Sensing Image Captioning

# 摘要

> 遥感图像描述生成（RSIC）是连接视觉与语言的跨模态领域，致力于自动为遥感图像生成自然语言描述。尽管在训练视觉-语言模型（VLMs）的方法与数据集方面取得了显著进展，但仍面临两大主要挑战：非英语描述数据集的稀缺性，以及模型多语言能力评估的缺失。这些限制严重阻碍了RSIC的发展，尤其是在大型视觉语言模型时代。为解决这些问题，本文做出了以下重要贡献：首先，我们引入并分析了BRSIC（双语遥感图像描述生成），这是一个包含13,634张图像和68,170个双语描述的全面双语数据集，丰富了三个现有英语RSIC数据集。基于此，我们开发了一个系统化的评估框架，通过标准化重新训练解决了现有评估协议的不一致性，能够严格评估模型性能。此外，我们对八种先进大型视觉语言模型（LVLMs）进行了全面研究，考察了它们在零样本推理、监督微调和多语言训练等范式中的能力。这项评估揭示了当前LVLMs在多语言遥感任务中的优势与局限性。我们的跨数据集迁移实验还发现了有趣的研究现象。代码和数据将在https://github.com/mrazhou/BRSIC上公开。

> Remote Sensing Image Captioning (RSIC) is a cross-modal field bridging vision and language, aimed at automatically generating natural language descriptions of features and scenes in remote sensing imagery. Despite significant advances in developing sophisticated methods and large-scale datasets for training vision-language models (VLMs), two critical challenges persist: the scarcity of non-English descriptive datasets and the lack of multilingual capability evaluation for models. These limitations fundamentally impede the progress and practical deployment of RSIC, particularly in the era of large VLMs. To address these challenges, this paper presents several significant contributions to the field. First, we introduce and analyze BRSIC (Bilingual Remote Sensing Image Captioning), a comprehensive bilingual dataset that enriches three established English RSIC datasets with Chinese descriptions, encompassing 13,634 images paired with 68,170 bilingual captions. Building upon this foundation, we develop a systematic evaluation framework that addresses the prevalent inconsistency in evaluation protocols, enabling rigorous assessment of model performance through standardized retraining procedures on BRSIC. Furthermore, we present an extensive empirical study of eight state-of-the-art large vision-language models (LVLMs), examining their capabilities across multiple paradigms including zero-shot inference, supervised fine-tuning, and multi-lingual training. This comprehensive evaluation provides crucial insights into the strengths and limitations of current LVLMs in handling multilingual remote sensing tasks. Additionally, our cross-dataset transfer experiments reveal interesting findings. The code and data will be available at https://github.com/mrazhou/BRSIC.

[Arxiv](https://arxiv.org/abs/2503.04592)