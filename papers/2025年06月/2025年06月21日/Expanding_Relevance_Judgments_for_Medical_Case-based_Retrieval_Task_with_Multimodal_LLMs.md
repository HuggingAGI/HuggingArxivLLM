# # 基于多模态大语言模型扩展医学案例检索任务的相关性判断

发布时间：2025年06月21日

`LLM应用` `信息检索`

> Expanding Relevance Judgments for Medical Case-based Retrieval Task with Multimodal LLMs

# 摘要

> 评估信息检索（IR）系统依赖高质量的手动相关性判断（qrels），但获取这些判断成本高、耗时长。虽然数据池化减少了标注工作量，但只能得到部分标注的数据集。大型语言模型（LLMs）为减少对人工判断的依赖提供了有前景的替代方案，特别是在需要分析文本和视觉信息的复杂领域，如基于案例的医疗检索。在本研究中，我们探索使用多模态大型语言模型（MLLM）来扩展相关性判断，创建一个自动化的判断新数据集。具体而言，我们在ImageCLEFmed 2013基于案例的检索任务中使用了Gemini 1.5 Pro，通过迭代优化的结构化提示策略模拟人类评估，该策略结合了二元评分、基于指令的评估和少量样本学习。我们系统地尝试了多种提示配置，以最大限度地与人工判断达成一致。为了评估MLLM与人工判断的一致性，我们使用了Cohen's Kappa，达到了0.6的显著一致性分数，与多模态检索任务中通常观察到的标注者间一致性相当。从最初的15,028个手动判断（4.72%的相关）和35个主题开始，我们的MLLM方法将数据集扩展了37倍，达到558,653个判断，相关标注增加到5,950个。平均而言，每个医疗案例查询获得了15,398个新标注，其中约99%是非相关的，反映了该领域典型的高稀疏性。我们的结果展示了MLLM在扩展相关性判断收集方面的潜力，为支持医疗和多模态IR任务的检索评估提供了有前景的方向。
    

> Evaluating Information Retrieval (IR) systems relies on high-quality manual relevance judgments (qrels), which are costly and time-consuming to obtain. While pooling reduces the annotation effort, it results in only partially labeled datasets. Large Language Models (LLMs) offer a promising alternative to reducing reliance on manual judgments, particularly in complex domains like medical case-based retrieval, where relevance assessment requires analyzing both textual and visual information. In this work, we explore using a Multimodal Large Language Model (MLLM) to expand relevance judgments, creating a new dataset of automated judgments. Specifically, we employ Gemini 1.5 Pro on the ImageCLEFmed 2013 case-based retrieval task, simulating human assessment through an iteratively refined, structured prompting strategy that integrates binary scoring, instruction-based evaluation, and few-shot learning. We systematically experimented with various prompt configurations to maximize agreement with human judgments. To evaluate agreement between the MLLM and human judgments, we use Cohen's Kappa, achieving a substantial agreement score of 0.6, comparable to inter-annotator agreement typically observed in multimodal retrieval tasks. Starting from the original 15,028 manual judgments (4.72% relevant) across 35 topics, our MLLM-based approach expanded the dataset by over 37x to 558,653 judgments, increasing relevant annotations to 5,950. On average, each medical case query received 15,398 new annotations, with approximately 99% being non-relevant, reflecting the high sparsity typical in this domain. Our results demonstrate the potential of MLLMs to scale relevance judgment collection, offering a promising direction for supporting retrieval evaluation in medical and multimodal IR tasks.

[Arxiv](https://arxiv.org/abs/2506.17782)