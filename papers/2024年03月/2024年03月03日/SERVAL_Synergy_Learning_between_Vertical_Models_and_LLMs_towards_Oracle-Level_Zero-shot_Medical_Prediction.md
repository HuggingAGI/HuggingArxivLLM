# SERVAL 研究通过构建垂直模型与大型语言模型（LLMs）间的协同效应，致力于在零样本条件下达到“Oracle级别”的医疗预测精度。

发布时间：2024年03月03日

`LLM应用`

> SERVAL: Synergy Learning between Vertical Models and LLMs towards Oracle-Level Zero-shot Medical Prediction

# 摘要

> 近期，LLMs 在处理一般性和常识问题时展现出卓越的零样本表现力。但在专业领域的垂直问题上，LLMs 的应用仍有待提升，主要原因在于垂直领域知识的匮乏以及面临的难题。另外，垂直数据的标注工作通常耗时费力，需要专家深度参与，这也成为提升模型垂直能力的一个重要难题。为此，我们提出了 SERVAL——一种协同学习流程，旨在无监督情况下通过双向增强策略提高 LLMs 与小型模型的垂直能力。SERVAL 将 LLM 零样本输出当作潜在标注，并以其自信心态“手把手”教会一个全新的垂直模型。反过来，已训练的垂直模型则指导 LLM 进行微调，逐步增强其零样本能力，二者通过迭代优化共同进步。在医疗这一垂直知识繁杂且标注成本高昂的领域，一系列全面实验显示，在未使用任何权威标签的情况下，结合 OpenAI GPT-3.5 和简易模型协同学习的 SERVAL 在十个广泛应用的医疗数据集中取得了媲美全监督训练的性能。这些数据集涵盖了诸如糖尿病、心脏病、COVID-19 等多个专业的医疗诊断场景，充分证明了 SERVAL 在深化 LLMs 垂直技能及从零开始训练垂直模型方面的巨大潜力，而这一切无需依赖人工标注即可实现。

> Recent development of large language models (LLMs) has exhibited impressive zero-shot proficiency on generic and common sense questions. However, LLMs' application on domain-specific vertical questions still lags behind, primarily due to the humiliation problems and deficiencies in vertical knowledge. Furthermore, the vertical data annotation process often requires labor-intensive expert involvement, thereby presenting an additional challenge in enhancing the model's vertical capabilities. In this paper, we propose SERVAL, a synergy learning pipeline designed for unsupervised development of vertical capabilities in both LLMs and small models by mutual enhancement. Specifically, SERVAL utilizes the LLM's zero-shot outputs as annotations, leveraging its confidence to teach a robust vertical model from scratch. Reversely, the trained vertical model guides the LLM fine-tuning to enhance its zero-shot capability, progressively improving both models through an iterative process. In medical domain, known for complex vertical knowledge and costly annotations, comprehensive experiments show that, without access to any gold labels, SERVAL with the synergy learning of OpenAI GPT-3.5 and a simple model attains fully-supervised competitive performance across ten widely used medical datasets. These datasets represent vertically specialized medical diagnostic scenarios (e.g., diabetes, heart diseases, COVID-19), highlighting the potential of SERVAL in refining the vertical capabilities of LLMs and training vertical models from scratch, all achieved without the need for annotations.

[Arxiv](https://arxiv.org/abs/2403.01570)