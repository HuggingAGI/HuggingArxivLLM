# BioD2C：生物医学视觉问答任务的双层级语义一致性约束框架

发布时间：2025年03月04日

`LLM应用` `生物医学` `视觉问答`

> BioD2C: A Dual-level Semantic Consistency Constraint Framework for Biomedical VQA

# 摘要

> # 摘要
生物医学视觉问答（VQA）在辅助医学诊断等领域展现了显著的应用价值。然而，现有模型仅在大型语言模型（LLMs）内部实现模型层面的多模态交互，导致复杂任务下的语义对齐效果不佳。针对这一问题，我们提出了 BioD2C，一种全新的双层次语义一致性约束框架。BioD2C 在模型和特征两个层面实现语义交互对齐，使模型能够根据问题自适应学习视觉特征。具体而言，我们通过图像-文本融合机制将文本特征融入视觉特征，获得基于文本的视觉特征；再引入基于文本队列的跨模态软语义损失函数，进一步对齐图像语义与问题语义。为解决现有数据集的偏见问题，我们构建了新的 BioVGQ 数据集，通过过滤人工修改的图像并使问答对与多模态上下文对齐，为研究提供更优质的数据支持。实验结果表明，BioD2C 在多个下游数据集上达到最优性能，展现了其强大的鲁棒性和泛化能力，为生物医学 VQA 研究注入新动力。

> Biomedical visual question answering (VQA) has been widely studied and has demonstrated significant application value and potential in fields such as assistive medical diagnosis. Despite their success, current biomedical VQA models perform multimodal information interaction only at the model level within large language models (LLMs), leading to suboptimal multimodal semantic alignment when dealing with complex tasks. To address this issue, we propose BioD2C: a novel Dual-level Semantic Consistency Constraint Framework for Biomedical VQA, which achieves dual-level semantic interaction alignment at both the model and feature levels, enabling the model to adaptively learn visual features based on the question. Specifically, we firstly integrate textual features into visual features via an image-text fusion mechanism as feature-level semantic interaction, obtaining visual features conditioned on the given text; and then introduce a text-queue-based cross-modal soft semantic loss function to further align the image semantics with the question semantics. Specifically, in this work, we establish a new dataset, BioVGQ, to address inherent biases in prior datasets by filtering manually-altered images and aligning question-answer pairs with multimodal context, and train our model on this dataset. Extensive experimental results demonstrate that BioD2C achieves state-of-the-art (SOTA) performance across multiple downstream datasets, showcasing its robustness, generalizability, and potential to advance biomedical VQA research.

[Arxiv](https://arxiv.org/abs/2503.02476)