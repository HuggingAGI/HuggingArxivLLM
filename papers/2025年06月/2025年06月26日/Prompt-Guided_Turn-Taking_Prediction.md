# 基于提示的对话轮次预测

发布时间：2025年06月26日

`LLM应用` `对话系统` `语音技术`

> Prompt-Guided Turn-Taking Prediction

# 摘要

> 对话轮换预测模型是口语对话系统和会话机器人中的关键组件。近年来，基于 transformer 的架构被用来连续且实时地预测语音活动。本研究提出了一种新型模型，能够通过文本提示动态控制对话轮换预测。该方法通过诸如 'faster' 或 'calmer' 这样的指令，实现了对对话轮换的直观且明确的控制，并能动态适应对话伙伴和语境。所提出的模型基于基于 transformer 的语音活动投影 (VAP) 模型，将文本提示嵌入到通道内的 transformer 和跨通道的 transformer 中。我们利用超过 950 小时的真人对话数据，评估了我们方法的可行性。由于现有数据集中缺乏适用于我们方法的文字提示数据，我们利用大型语言模型 (LLM) 生成了合成的提示句。实验结果表明，所提出的模型不仅提高了预测精度，还能根据文本提示有效调整对话轮换的时机。

> Turn-taking prediction models are essential components in spoken dialogue systems and conversational robots. Recent approaches leverage transformer-based architectures to predict speech activity continuously and in real-time. In this study, we propose a novel model that enables turn-taking prediction to be dynamically controlled via textual prompts. This approach allows intuitive and explicit control through instructions such as "faster" or "calmer" adapting dynamically to conversational partners and contexts. The proposed model builds upon a transformer-based voice activity projection (VAP) model, incorporating textual prompt embeddings into both channel-wise transformers and a cross-channel transformer. We evaluated the feasibility of our approach using over 950 hours of human-human spoken dialogue data. Since textual prompt data for the proposed approach was not available in existing datasets, we utilized a large language model (LLM) to generate synthetic prompt sentences. Experimental results demonstrated that the proposed model improved prediction accuracy and effectively varied turn-taking timing behaviors according to the textual prompts.

[Arxiv](https://arxiv.org/abs/2506.21191)