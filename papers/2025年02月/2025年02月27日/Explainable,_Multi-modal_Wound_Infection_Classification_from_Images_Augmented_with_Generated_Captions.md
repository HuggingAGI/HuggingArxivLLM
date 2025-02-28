# # 可解释的多模态伤口感染分类
基于图像并结合生成说明

发布时间：2025年02月27日

`LLM应用` `人工智能`

> Explainable, Multi-modal Wound Infection Classification from Images Augmented with Generated Captions

# 摘要

> 糖尿病足溃疡 (DFU) 的感染可能引发严重后果，如组织坏死和肢体截肢，凸显了精准、及时诊断的迫切需求。传统机器学习方法仅通过分析伤口图像来识别感染，而忽略了医疗笔记等重要元数据。本研究推出 SCARWID（SCARWID: 合成式描述增强检索框架），一种新型深度学习方案，旨在通过合成描述提升感染检测效果。SCARWID 由两部分组成：(1) Wound-BLIP，一款基于 GPT-4 描述微调的视觉-语言模型 (VLM)，可从图像生成一致的描述；(2) 图像-文本融合模块，利用交叉注意力机制提取跨模态嵌入。通过检索标注支持集中的 top-k 相似项确定感染状态。为丰富训练数据，我们采用潜在扩散模型生成额外伤口图像。实验结果表明，SCARWID 在感染分类任务中超越现有最优模型，灵敏度、特异性和准确率分别达到 0.85、0.78 和 0.81。展示生成描述、伤口图像及检测结果，提升了模型的可解释性和可信度，帮助护士将 SCARWID 输出与医学知识结合。这一特性在缺乏伤口笔记或协助新手护士识别感染视觉特征时尤为宝贵。


> Infections in Diabetic Foot Ulcers (DFUs) can cause severe complications, including tissue death and limb amputation, highlighting the need for accurate, timely diagnosis. Previous machine learning methods have focused on identifying infections by analyzing wound images alone, without utilizing additional metadata such as medical notes. In this study, we aim to improve infection detection by introducing Synthetic Caption Augmented Retrieval for Wound Infection Detection (SCARWID), a novel deep learning framework that leverages synthetic textual descriptions to augment DFU images. SCARWID consists of two components: (1) Wound-BLIP, a Vision-Language Model (VLM) fine-tuned on GPT-4o-generated descriptions to synthesize consistent captions from images; and (2) an Image-Text Fusion module that uses cross-attention to extract cross-modal embeddings from an image and its corresponding Wound-BLIP caption. Infection status is determined by retrieving the top-k similar items from a labeled support set. To enhance the diversity of training data, we utilized a latent diffusion model to generate additional wound images. As a result, SCARWID outperformed state-of-the-art models, achieving average sensitivity, specificity, and accuracy of 0.85, 0.78, and 0.81, respectively, for wound infection classification. Displaying the generated captions alongside the wound images and infection detection results enhances interpretability and trust, enabling nurses to align SCARWID outputs with their medical knowledge. This is particularly valuable when wound notes are unavailable or when assisting novice nurses who may find it difficult to identify visual attributes of wound infection.

[Arxiv](https://arxiv.org/abs/2502.20277)