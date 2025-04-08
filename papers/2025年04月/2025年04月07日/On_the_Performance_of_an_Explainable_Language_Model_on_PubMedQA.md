# 可解释语言模型在PubMedQA医学问答中的性能表现

发布时间：2025年04月07日

`LLM应用` `问答系统`

> On the Performance of an Explainable Language Model on PubMedQA

# 摘要

> 大型语言模型（LLMs）在医学知识检索、推理及回答方面表现卓越，可媲美专业医师。然而，这些模型存在不可解释、易产生幻觉、维护困难及高计算资源需求等局限。本文介绍了一种基于全新架构的可解释语言模型Gyan在PubmedQA数据集上的研究成果。Gyan是一种组合式语言模型，其知识与模型架构分离。该模型具备可信赖、透明、无幻觉生成的特点，且对训练与计算资源需求极低。Gyan还展现出强大的跨领域迁移能力。在PubmedQA数据集上，Gyan-4.3以87.1%的准确率创下最优成绩，超越了基于GPT-4的MedPrompt（82%）和Google与DeepMind联合开发的Med-PaLM 2（81.8%）。未来，我们还将陆续发布Gyan在MedQA、MedMCQA和MMLU - Medicine等其他医学数据集上的研究表现。

> Large language models (LLMs) have shown significant abilities in retrieving medical knowledge, reasoning over it and answering medical questions comparably to physicians. However, these models are not interpretable, hallucinate, are difficult to maintain and require enormous compute resources for training and inference. In this paper, we report results from Gyan, an explainable language model based on an alternative architecture, on the PubmedQA data set. The Gyan LLM is a compositional language model and the model is decoupled from knowledge. Gyan is trustable, transparent, does not hallucinate and does not require significant training or compute resources. Gyan is easily transferable across domains. Gyan-4.3 achieves SOTA results on PubmedQA with 87.1% accuracy compared to 82% by MedPrompt based on GPT-4 and 81.8% by Med-PaLM 2 (Google and DeepMind). We will be reporting results for other medical data sets - MedQA, MedMCQA, MMLU - Medicine in the future.

[Arxiv](https://arxiv.org/abs/2504.05074)