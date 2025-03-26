# AGIR：基于LLMs的3D步态损伤推理评估

发布时间：2025年03月23日

`LLM应用` `神经退行性疾病`

> AGIR: Assessing 3D Gait Impairment with Reasoning based on LLMs

# 摘要

> 步态障碍评估在神经退行性疾病的早期诊断、疾病监测和治疗评估中发挥着关键作用。然而，尽管在临床实践中广泛应用，其局限性在于主观性和缺乏精确性。近年来，基于深度学习的方法虽然在分类准确率上有所提升，但它们通常缺乏可解释性，限制了在临床决策中的应用。为了解决这些挑战，我们提出了AGIR，一个创新的管道，结合预训练的VQ-VAE运动分词器和经过微调的大型语言模型（LLM），该模型基于运动分词对和链式推理（CoT）进行训练。

为了微调LLM用于病理步态分析，我们首先创建了一个多模态数据集，通过在现有PD步态数据集中添加专门用于MDS-UPDRS步态评分评估的解释。然后，我们引入了一个两阶段的监督微调（SFT）策略，以增强LLM对病理特异性知识的运动理解。该策略包括：1）生成阶段，通过双向运动-描述生成将步态运动与分析性描述对齐；2）推理阶段，通过逻辑链式推理（CoT）将UPDRS步态评分整合到障碍评估中。

在现有数据集上的验证以及与最新方法的对比证明了我们管道的稳健性和准确性，展示了其根据运动输入分配步态障碍评分的能力，并提供具有临床意义的解释。


> Assessing gait impairment plays an important role in early diagnosis, disease monitoring, and treatment evaluation for neurodegenerative diseases. Despite its widespread use in clinical practice, it is limited by subjectivity and a lack of precision. While recent deep learning-based approaches have consistently improved classification accuracies, they often lack interpretability, hindering their utility in clinical decision-making. To overcome these challenges, we introduce AGIR, a novel pipeline consisting of a pre-trained VQ-VAE motion tokenizer and a subsequent Large Language Model (LLM) fine-tuned over pairs of motion tokens and Chain-of-Thought (CoT) reasonings. To fine-tune an LLM for pathological gait analysis, we first introduce a multimodal dataset by adding rationales dedicated to MDS-UPDRS gait score assessment to an existing PD gait dataset. We then introduce a two-stage supervised fine-tuning (SFT) strategy to enhance the LLM's motion comprehension with pathology-specific knowledge. This strategy includes: 1) a generative stage that aligns gait motions with analytic descriptions through bidirectional motion-description generation, 2) a reasoning stage that integrates logical Chain-of-Thought (CoT) reasoning for impairment assessment with UPDRS gait score. Validation on an existing dataset and comparisons with state-of-the-art methods confirm the robustness and accuracy of our pipeline, demonstrating its ability to assign gait impairment scores from motion input with clinically meaningful rationales.

[Arxiv](https://arxiv.org/abs/2503.18141)