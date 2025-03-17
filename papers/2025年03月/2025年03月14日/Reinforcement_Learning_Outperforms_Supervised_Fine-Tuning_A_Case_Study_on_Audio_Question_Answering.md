# 强化学习超越监督微调：一项关于音频问答的案例研究

发布时间：2025年03月14日

`LLM应用` `问答系统`

> Reinforcement Learning Outperforms Supervised Fine-Tuning: A Case Study on Audio Question Answering

# 摘要

> 强化学习（RL）近期在提升大型语言模型推理能力方面表现突出，并逐渐被应用到视觉多模态任务中。然而，音频模态在此类进展中却鲜少受到关注。为此，我们针对音频问答（AQA）任务展开了一系列基于RL的探索。通过将组相对策略优化（GRPO）算法应用于Qwen2-Audio-7B-Instruct模型，我们在MMAU Test-mini基准上取得了64.5%的准确率，展现了前沿性能。本报告的主要发现包括：1）GRPO算法能够有效应用于仅有82亿参数的大型音频语言模型（LALMs）；2）仅需3.8万个后训练样本，RL的表现显著优于监督微调（SFT），证明基于RL的方法在小数据集下同样有效；3）显式推理过程在AQA任务中并未展现出显著优势，如何有效利用深度思考仍是一个开放问题；4）当前LALMs在听觉-语言推理方面仍远逊于人类，提示基于RL的方法值得进一步探索。我们的项目已在GitHub和Hugging Face上开源，链接为https://github.com/xiaomi/r1-aqa和https://huggingface.co/mispeech/r1-aqa。

> Recently, reinforcement learning (RL) has been shown to greatly enhance the reasoning capabilities of large language models (LLMs), and RL-based approaches have been progressively applied to visual multimodal tasks. However, the audio modality has largely been overlooked in these developments. Thus, we conduct a series of RL explorations in audio understanding and reasoning, specifically focusing on the audio question answering (AQA) task. We leverage the group relative policy optimization (GRPO) algorithm to Qwen2-Audio-7B-Instruct, and our experiments demonstrated state-of-the-art performance on the MMAU Test-mini benchmark, achieving an accuracy rate of 64.5%. The main findings in this technical report are as follows: 1) The GRPO algorithm can be effectively applied to large audio language models (LALMs), even when the model has only 8.2B parameters; 2) With only 38k post-training samples, RL significantly outperforms supervised fine-tuning (SFT), indicating that RL-based approaches can be effective without large datasets; 3) The explicit reasoning process has not shown significant benefits for AQA tasks, and how to efficiently utilize deep thinking remains an open question for further research; 4) LALMs still lag far behind humans auditory-language reasoning, suggesting that the RL-based approaches warrant further exploration. Our project is available at https://github.com/xiaomi/r1-aqa and https://huggingface.co/mispeech/r1-aqa.

[Arxiv](https://arxiv.org/abs/2503.11197)