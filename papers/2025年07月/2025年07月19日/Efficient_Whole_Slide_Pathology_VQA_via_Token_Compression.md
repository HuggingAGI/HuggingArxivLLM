# # 基于Token压缩技术的高效病理全切片VQA

发布时间：2025年07月19日

`LLM应用` `病理学` `视觉问答`

> Efficient Whole Slide Pathology VQA via Token Compression

# 摘要

> 病理学中的全片图像（WSIs）分辨率可高达10000×10000像素，这对多模态大型语言模型（MLLM）带来了双重挑战：长上下文长度和高计算需求。此前基于CLIP模型的多示例学习方法，虽然在基于补丁的分析或全片分类上有所应用，但缺乏用于视觉问答（VQA）所需的生成能力。近期的MLLM方法通过直接将数千个补丁标记输入语言模型来解决VQA问题，但导致了资源消耗过大的问题。为了解决这些局限性，我们提出了基于标记压缩的病理学LLaVA模型（TCP-LLaVA），这是首个通过标记压缩实现WSI视觉问答的MLLM架构。TCP-LLaVA引入了一组可训练的压缩标记，通过模态压缩模块整合视觉与文本信息，灵感来自于BERT中的[CLS]标记机制。仅将压缩后的标记输入LLM进行答案生成，大幅缩短了输入长度并降低了计算成本。在十种TCGA肿瘤亚型上的实验表明，TCP-LLaVA在VQA准确率上超越了现有MLLM基线模型，同时显著降低了训练资源消耗。

> Whole-slide images (WSIs) in pathology can reach up to 10,000 x 10,000 pixels, posing significant challenges for multimodal large language model (MLLM) due to long context length and high computational demands. Previous methods typically focus on patch-level analysis or slide-level classification using CLIP-based models with multi-instance learning, but they lack the generative capabilities needed for visual question answering (VQA). More recent MLLM-based approaches address VQA by feeding thousands of patch tokens directly into the language model, which leads to excessive resource consumption. To address these limitations, we propose Token Compression Pathology LLaVA (TCP-LLaVA), the first MLLM architecture to perform WSI VQA via token compression. TCP-LLaVA introduces a set of trainable compression tokens that aggregate visual and textual information through a modality compression module, inspired by the [CLS] token mechanism in BERT. Only the compressed tokens are forwarded to the LLM for answer generation, significantly reducing input length and computational cost. Experiments on ten TCGA tumor subtypes show that TCP-LLaVA outperforms existing MLLM baselines in VQA accuracy while reducing training resource consumption by a substantial margin.

[Arxiv](https://arxiv.org/abs/2507.14497)