# 针对语音语言模型端到端训练中的灾难性遗忘问题，研究缓解策略

发布时间：2025年05月23日

`LLM理论` `语音处理` `模型训练`

> Analyzing Mitigation Strategies for Catastrophic Forgetting in End-to-End Training of Spoken Language Models

# 摘要

> 端到端训练口语语言模型（SLMs）通常涉及通过多阶段训练，将预训练的基于文本的大型语言模型（LLMs）适应到语音模态，涵盖如ASR、TTS和口语问答（SQA）等多样化任务。尽管这种多阶段连续学习使LLMs同时具备了语音理解和生成的能力，但各阶段间任务和数据分布的巨大差异可能导致灾难性遗忘，即之前获取的知识被遗忘。本文研究了灾难性遗忘问题，并评估了三种缓解策略：模型合并、降低LoRA缩放因子以及经验回放，以平衡知识保留与新知识学习。结果显示，经验回放最为有效，与其他方法结合使用可进一步提升效果。这些发现为开发更强大和高效的SLM训练流水线提供了见解。

> End-to-end training of Spoken Language Models (SLMs) commonly involves adapting pre-trained text-based Large Language Models (LLMs) to the speech modality through multi-stage training on diverse tasks such as ASR, TTS and spoken question answering (SQA). Although this multi-stage continual learning equips LLMs with both speech understanding and generation capabilities, the substantial differences in task and data distributions across stages can lead to catastrophic forgetting, where previously acquired knowledge is lost. This paper investigates catastrophic forgetting and evaluates three mitigation strategies-model merging, discounting the LoRA scaling factor, and experience replay to balance knowledge retention with new learning. Results show that experience replay is the most effective, with further gains achieved by combining it with other methods. These findings provide insights for developing more robust and efficient SLM training pipelines.

[Arxiv](https://arxiv.org/abs/2505.17496)