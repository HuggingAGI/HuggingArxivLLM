# SURE-VQA：对医疗 VQA 任务中鲁棒性评估的系统性理解

发布时间：2024年11月29日

`LLM应用` `视觉问答`

> SURE-VQA: Systematic Understanding of Robustness Evaluation in Medical VQA Tasks

# 摘要

> 视觉语言模型（VLMs）在诸如视觉问答（VQA）等医疗任务中潜力巨大，能充当患者和临床医生的互动助手。然而，它们在应对未见过数据的分布变化时的稳健性，仍是安全部署的关键问题。评估这种稳健性需要可控的实验设置，以便系统地洞察模型行为。但我们发现，当前的设置无法进行足够全面的评估，限制了准确评估模型稳健性的能力。为弥补这一差距，我们的工作推出了一个新框架——SURE-VQA，围绕三个关键要求来克服现有缺陷并系统分析 VLMs 的稳健性：1）对合成变化的稳健性不一定适用于现实世界的变化，所以应基于 VQA 数据固有的现实世界变化来衡量稳健性；2）传统的令牌匹配指标通常难以捕捉底层语义，故而需要借助大型语言模型（LLMs）进行更精准的语义评估；3）由于缺少合理的基线，模型性能往往缺乏可解释性，因此应当报告有意义的基线，以便评估多模态对 VLM 的影响。为证明该框架的有效性，我们针对三种医疗数据集，研究了各种微调方法在四种不同类型分布变化下的稳健性。我们的研究有以下几个重要发现：1）不使用图像数据的合理基线表现竟出乎意料地好；2）我们确认 LoRA 是表现最佳的 PEFT 方法；3）没有哪种 PEFT 方法在应对变化的稳健性方面始终优于其他方法。代码可在 https://github.com/IML-DKFZ/sure-vqa 获取。

> Vision-Language Models (VLMs) have great potential in medical tasks, like Visual Question Answering (VQA), where they could act as interactive assistants for both patients and clinicians. Yet their robustness to distribution shifts on unseen data remains a critical concern for safe deployment. Evaluating such robustness requires a controlled experimental setup that allows for systematic insights into the model's behavior. However, we demonstrate that current setups fail to offer sufficiently thorough evaluations, limiting their ability to accurately assess model robustness. To address this gap, our work introduces a novel framework, called SURE-VQA, centered around three key requirements to overcome the current pitfalls and systematically analyze the robustness of VLMs: 1) Since robustness on synthetic shifts does not necessarily translate to real-world shifts, robustness should be measured on real-world shifts that are inherent to the VQA data; 2) Traditional token-matching metrics often fail to capture underlying semantics, necessitating the use of large language models (LLMs) for more accurate semantic evaluation; 3) Model performance often lacks interpretability due to missing sanity baselines, thus meaningful baselines should be reported that allow assessing the multimodal impact on the VLM. To demonstrate the relevance of this framework, we conduct a study on the robustness of various fine-tuning methods across three medical datasets with four different types of distribution shifts. Our study reveals several important findings: 1) Sanity baselines that do not utilize image data can perform surprisingly well; 2) We confirm LoRA as the best-performing PEFT method; 3) No PEFT method consistently outperforms others in terms of robustness to shifts. Code is provided at https://github.com/IML-DKFZ/sure-vqa.

[Arxiv](https://arxiv.org/abs/2411.19688)