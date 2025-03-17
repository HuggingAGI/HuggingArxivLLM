# # 研究标题
看中学：借助专家知识与语言，深入理解手术视频

发布时间：2025年03月14日

`LLM应用` `视频分析`

> Watch and Learn: Leveraging Expert Knowledge and Language for Surgical Video Understanding

# 摘要

> 自动化的外科手术工作流程分析在教育、研究和临床决策中具有重要意义，但标注数据的缺失严重限制了精准且全面的分析方案开发。我们提出了一种创新方法，旨在解决标注训练数据稀疏性和异质性问题，灵感来自于人类通过观察专家并理解其解释的学习过程。

我们的方法采用了一个经过对齐、去噪和生成任务训练的视频-语言模型，用于学习短期时空和多模态表示。随后，通过特定任务的时间模型捕捉视频间的关系。为实现外科领域的全面视频-语言理解，我们设计了一种数据收集与筛选策略，从教育类 YouTube 视频中构建大规模预训练数据集。再通过将公开外科数据集的下游任务标注映射至语言领域，实现参数高效的微调。

在两个外科领域的广泛实验中，我们的方法表现出显著优势：阶段分割任务性能提升7%，零样本阶段分割提升8%，少样本场景下与全监督模型能力相当。凭借模型在长时时间定位与文本生成方面的优势，我们首次提出了针对外科手术视频的密集视频字幕（DVC）全面解决方案，成功克服了现有外科领域缺乏DVC数据集的难题。

我们的方法结合视频-语言预训练、大规模视频预训练与优化微调，不仅超越现有最优技术，更为外科手术视频理解开辟了新的下游任务。

> Automated surgical workflow analysis is crucial for education, research, and clinical decision-making, but the lack of annotated datasets hinders the development of accurate and comprehensive workflow analysis solutions. We introduce a novel approach for addressing the sparsity and heterogeneity of annotated training data inspired by the human learning procedure of watching experts and understanding their explanations. Our method leverages a video-language model trained on alignment, denoising, and generative tasks to learn short-term spatio-temporal and multimodal representations. A task-specific temporal model is then used to capture relationships across entire videos. To achieve comprehensive video-language understanding in the surgical domain, we introduce a data collection and filtering strategy to construct a large-scale pretraining dataset from educational YouTube videos. We then utilize parameter-efficient fine-tuning by projecting downstream task annotations from publicly available surgical datasets into the language domain. Extensive experiments in two surgical domains demonstrate the effectiveness of our approach, with performance improvements of up to 7% in phase segmentation tasks, 8% in zero-shot phase segmentation, and comparable capabilities to fully-supervised models in few-shot settings. Harnessing our model's capabilities for long-range temporal localization and text generation, we present the first comprehensive solution for dense video captioning (DVC) of surgical videos, addressing this task despite the absence of existing DVC datasets in the surgical domain. We introduce a novel approach to surgical workflow understanding that leverages video-language pretraining, large-scale video pretraining, and optimized fine-tuning. Our method improves performance over state-of-the-art techniques and enables new downstream tasks for surgical video understanding.

[Arxiv](https://arxiv.org/abs/2503.11392)