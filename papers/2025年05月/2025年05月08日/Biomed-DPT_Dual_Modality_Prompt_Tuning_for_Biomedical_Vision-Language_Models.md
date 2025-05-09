# Biomed-DPT：生物医学视觉语言模型的双模态提示调优方法

发布时间：2025年05月08日

`LLM应用` `知识图谱`

> Biomed-DPT: Dual Modality Prompt Tuning for Biomedical Vision-Language Models

# 摘要

> 提示学习是将预训练视觉-语言模型（VLM）应用于少量样本生物医学图像分类任务的最有效方法之一。然而，现有方法大多仅依赖文本提示，忽视了生物医学图像中复杂的解剖结构和微妙的病理特征。为此，我们提出了知识增强的双模态提示微调技术——Biomed-DPT。在文本提示设计上，Biomed-DPT创新性地构建了包含模板驱动临床提示和大型语言模型（LLM）驱动领域适应提示的双提示结构，并通过知识蒸馏技术提取临床知识。在视觉提示设计上，Biomed-DPT采用零向量作为软提示，利用注意力重新加权机制，有效避免了对非诊断区域的关注以及对非关键病理特征的误识别。实验结果表明，Biomed-DPT在涵盖9种模态和10种器官的11个生物医学图像数据集上实现了66.14%的平均分类准确率，其中基础类别准确率达到78.06%，新型类别达到75.97%，分别超越了Context Optimization（CoOp）方法6.20%、3.78%和8.04%。我们的代码已开源，地址为underline{https://github.com/Kanyooo/Biomed-DPT}。

> Prompt learning is one of the most effective paradigms for adapting pre-trained vision-language models (VLMs) to the biomedical image classification tasks in few shot scenarios. However, most of the current prompt learning methods only used the text prompts and ignored the particular structures (such as the complex anatomical structures and subtle pathological features) in the biomedical images. In this work, we propose Biomed-DPT, a knowledge-enhanced dual modality prompt tuning technique. In designing the text prompt, Biomed-DPT constructs a dual prompt including the template-driven clinical prompts and the large language model (LLM)-driven domain-adapted prompts, then extracts the clinical knowledge from the domain-adapted prompts through the knowledge distillation technique. In designing the vision prompt, Biomed-DPT introduces the zero vector as a soft prompt to leverage attention re-weighting so that the focus on non-diagnostic regions and the recognition of non-critical pathological features are avoided. Biomed-DPT achieves an average classification accuracy of 66.14\% across 11 biomedical image datasets covering 9 modalities and 10 organs, with performance reaching 78.06\% in base classes and 75.97\% in novel classes, surpassing the Context Optimization (CoOp) method by 6.20\%, 3.78\%, and 8.04\%, respectively. Our code are available at \underline{https://github.com/Kanyooo/Biomed-DPT}.

[Arxiv](https://arxiv.org/abs/2505.05189)