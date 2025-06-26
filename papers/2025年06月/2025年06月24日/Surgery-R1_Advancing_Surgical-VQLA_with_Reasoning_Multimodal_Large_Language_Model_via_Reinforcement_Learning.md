# Surgery-R1：基于强化学习的推理型多模态大语言模型助力 Surgical-VQLA 的突破

发布时间：2025年06月24日

`LLM应用` `机器人手术`

> Surgery-R1: Advancing Surgical-VQLA with Reasoning Multimodal Large Language Model via Reinforcement Learning

# 摘要

> 近年来，手术场景理解领域取得了显著进展，特别是在机器人手术中的视觉问答定位回答任务（Surgical-VQLA）方面。然而，现有模型在手术场景中缺乏深度推理能力和可解释性，限制了其临床应用的潜力。为解决这一问题，我们受到推理型多模态大语言模型（MLLMs）发展的启发，首先构建了 Surgery-R1-54k 数据集，其中包括视觉问答、定位问答和思维链（CoT）的配对数据。随后，我们提出了首个用于 Surgical-VQLA 的推理型 MLLM（Surgery-R1）。在 Surgery-R1 中，我们设计了两阶段微调机制，通过监督微调（SFT）和强化微调（RFT）使基础 MLLM 具备复杂推理能力。此外，为实现高效且高质量的基于规则的奖励系统，我们设计了多模态连贯性奖励机制，以缓解手术场景中的位置错觉问题。实验结果表明，Surgery-R1 在 Surgical-VQLA 任务中优于现有最先进（SOTA）模型和广泛使用的 MLLMs，同时验证了其推理能力和方法的有效性。代码和数据集已整理在 https://github.com/FiFi-HAO467/Surgery-R1。

> In recent years, significant progress has been made in the field of surgical scene understanding, particularly in the task of Visual Question Localized-Answering in robotic surgery (Surgical-VQLA). However, existing Surgical-VQLA models lack deep reasoning capabilities and interpretability in surgical scenes, which limits their reliability and potential for development in clinical applications. To address this issue, inspired by the development of Reasoning Multimodal Large Language Models (MLLMs), we first build the Surgery-R1-54k dataset, including paired data for Visual-QA, Grounding-QA, and Chain-of-Thought (CoT). Then, we propose the first Reasoning MLLM for Surgical-VQLA (Surgery-R1). In our Surgery-R1, we design a two-stage fine-tuning mechanism to enable the basic MLLM with complex reasoning abilities by utilizing supervised fine-tuning (SFT) and reinforcement fine-tuning (RFT). Furthermore, for an efficient and high-quality rule-based reward system in our RFT, we design a Multimodal Coherence reward mechanism to mitigate positional illusions that may arise in surgical scenarios. Experiment results demonstrate that Surgery-R1 outperforms other existing state-of-the-art (SOTA) models in the Surgical-VQLA task and widely-used MLLMs, while also validating its reasoning capabilities and the effectiveness of our approach. The code and dataset will be organized in https://github.com/FiFi-HAO467/Surgery-R1.

[Arxiv](https://arxiv.org/abs/2506.19469)