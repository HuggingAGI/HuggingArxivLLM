# 下一个token就足够：基于多模态大型语言模型的真实图像质量与美学评分

发布时间：2025年03月08日

`LLM应用` `图像处理` `计算机视觉`

> Next Token Is Enough: Realistic Image Quality and Aesthetic Scoring with Multimodal Large Language Model

# 摘要

> 移动互联网的迅猛发展带来了用户生成内容（UGC）图片的激增，使得对UGC图片的全面评估变得至关重要。近期，多模态大语言模型（MLLMs）在图像质量评估（IQA）和美学评估（IAA）领域展现出巨大潜力。然而，尽管取得了进展，对UGC图片进行有效评分仍面临两大挑战：1）单一评分难以全面反映人类的分层感知；2）如何利用MLLMs输出数值评分（如平均意见评分MOS）仍是待解难题。

为解决这些问题，我们推出全新数据集Realistic图像质量与美学（RealQA），包含14,715张UGC图片，每张图片标注了10个细粒度属性，涵盖低级（如清晰度）、中级（如主体完整性）和高级（如构图）三个层级。此外，我们深入研究了如何有效利用MLLMs预测数值评分。令人惊喜的是，仅需预测两个额外显著数字，下一个令牌范式即可实现最先进（SOTA）性能。更重要的是，结合思维链（CoT）与细粒度属性，我们的方法在五个公开数据集上显著超越现有最优方法，且具有优越的可解释性，并在视频质量评估（VQA）中展现出强大的零样本泛化能力。代码和数据集即将发布。

> The rapid expansion of mobile internet has resulted in a substantial increase in user-generated content (UGC) images, thereby making the thorough assessment of UGC images both urgent and essential. Recently, multimodal large language models (MLLMs) have shown great potential in image quality assessment (IQA) and image aesthetic assessment (IAA). Despite this progress, effectively scoring the quality and aesthetics of UGC images still faces two main challenges: 1) A single score is inadequate to capture the hierarchical human perception. 2) How to use MLLMs to output numerical scores, such as mean opinion scores (MOS), remains an open question. To address these challenges, we introduce a novel dataset, named Realistic image Quality and Aesthetic (RealQA), including 14,715 UGC images, each of which is annoted with 10 fine-grained attributes. These attributes span three levels: low level (e.g., image clarity), middle level (e.g., subject integrity) and high level (e.g., composition). Besides, we conduct a series of in-depth and comprehensive investigations into how to effectively predict numerical scores using MLLMs. Surprisingly, by predicting just two extra significant digits, the next token paradigm can achieve SOTA performance. Furthermore, with the help of chain of thought (CoT) combined with the learnt fine-grained attributes, the proposed method can outperform SOTA methods on five public datasets for IQA and IAA with superior interpretability and show strong zero-shot generalization for video quality assessment (VQA). The code and dataset will be released.

[Arxiv](https://arxiv.org/abs/2503.06141)