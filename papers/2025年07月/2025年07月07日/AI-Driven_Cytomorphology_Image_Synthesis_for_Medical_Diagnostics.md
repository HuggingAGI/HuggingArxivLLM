# AI驱动合成细胞形态学图像，助力医学诊断

发布时间：2025年07月07日

`LLM应用` `生物医学` `计算机视觉`

> AI-Driven Cytomorphology Image Synthesis for Medical Diagnostics

# 摘要

> 生物医学数据集普遍存在样本不平衡问题，并受制于严格的隐私限制，这些挑战共同阻碍了精准机器学习模型的开发。生成合成图像是一个有潜力的解决方案，它既能提升数据可用性，又能保护患者隐私。然而，生成高质量的合成图像以训练稳健分类器仍具挑战性。本研究聚焦于单个白细胞分类任务，这是诊断急性髓性白血病（AML）等血液疾病的关键环节。我们展示了通过基于真实少量样本的微调稳定扩散模型（采用LoRA权重）生成的合成图像，如何能有效提升分类器在有限数据情况下的表现。在训练ResNet分类器时，通过向一个小型且严重不平衡的真实数据集中添加每类5000张合成图像，准确率从27.3%提升至78.4%（+51.1%）。对于基于CLIP的分类器，准确率从61.8%提升至76.8%（+15.0%）。这些合成图像与真实图像高度相似，能够帮助克服数据集限制，提升模型泛化能力。我们的研究结果证明，合成图像是生物医学研究中的一种有力工具，它不仅改进了机器学习模型，还推动了医学诊断和研究的发展。

> Biomedical datasets often contain a large sample imbalance and are subject to strict privacy constraints, which together hinder the development of accurate machine learning models. One potential solution is to generate synthetic images, as this can improve data availability while preserving patient privacy. However, it remains difficult to generate synthetic images of sufficient quality for training robust classifiers. In this work, we focus on the classification of single white blood cells, a key component in the diagnosis of hematological diseases such as acute myeloid leukemia (AML), a severe blood cancer. We demonstrate how synthetic images generated with a fine-tuned stable diffusion model using LoRA weights when guided by real few-shot samples of the target white blood cell classes, can enhance classifier performance for limited data. When training a ResNet classifier, accuracy increased from 27.3\% to 78.4\% (+51.1\%) by adding 5000 synthetic images per class to a small and highly imbalanced real dataset. For a CLIP-based classifier, the accuracy improved from 61.8\% to 76.8\% (+15.0\%). The synthetic images are highly similar to real images, and they can help overcome dataset limitations, enhancing model generalization. Our results establish synthetic images as a tool in biomedical research, improving machine learning models, and facilitating medical diagnosis and research.

[Arxiv](https://arxiv.org/abs/2507.05063)