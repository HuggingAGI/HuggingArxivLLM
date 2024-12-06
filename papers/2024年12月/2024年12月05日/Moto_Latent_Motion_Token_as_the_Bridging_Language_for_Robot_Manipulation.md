# Moto：潜在运动令牌充当机器人操作的桥梁式语言

发布时间：2024年12月05日

`LLM应用` `机器人`

> Moto: Latent Motion Token as the Bridging Language for Robot Manipulation

# 摘要

> 近期，基于大量语料库预训练的大型语言模型在各类自然语言处理任务中取得显著成果，且只需少量微调。这一成就为长期受动作标注数据高成本困扰的机器人领域带来新契机。我们思考：鉴于存在大量富含交互相关知识的视频数据可充当丰富“语料库”，类似的生成式预训练方法能否有效用于强化机器人学习？关键在于确定有益于机器人操作任务的自回归预训练的有效表征。受人类通过观察动态环境学习新技能的方式启发，我们认为有效的机器人学习应注重与运动相关的知识，其与低级动作紧密相连且不受硬件限制，利于将所学动作迁移至实际机器人动作中。为此，我们引入 Moto，它借助潜在运动标记器将视频内容转化为潜在运动标记序列，以无监督方式从视频中学习运动的“衔接语言”。我们通过运动标记自回归对 Moto-GPT 进行预训练，使其能够获取多样的视觉运动知识。预训练后，Moto-GPT 展现出产生语义可解释的运动标记、预测合理运动轨迹以及通过输出可能性评估轨迹合理性的出色能力。为将所学运动先验迁移至实际机器人动作，我们实施了一种协同微调策略，无缝衔接潜在运动标记预测与实际机器人控制。大量实验表明，微调后的 Moto-GPT 在机器人操作基准测试中表现出超强的鲁棒性和高效性，凸显了其将视频数据中的知识迁移至下游视觉操作任务的有效性。

> Recent developments in Large Language Models pre-trained on extensive corpora have shown significant success in various natural language processing tasks with minimal fine-tuning. This success offers new promise for robotics, which has long been constrained by the high cost of action-labeled data. We ask: given the abundant video data containing interaction-related knowledge available as a rich "corpus", can a similar generative pre-training approach be effectively applied to enhance robot learning? The key challenge is to identify an effective representation for autoregressive pre-training that benefits robot manipulation tasks. Inspired by the way humans learn new skills through observing dynamic environments, we propose that effective robotic learning should emphasize motion-related knowledge, which is closely tied to low-level actions and is hardware-agnostic, facilitating the transfer of learned motions to actual robot actions. To this end, we introduce Moto, which converts video content into latent Motion Token sequences by a Latent Motion Tokenizer, learning a bridging "language" of motion from videos in an unsupervised manner. We pre-train Moto-GPT through motion token autoregression, enabling it to capture diverse visual motion knowledge. After pre-training, Moto-GPT demonstrates the promising ability to produce semantically interpretable motion tokens, predict plausible motion trajectories, and assess trajectory rationality through output likelihood. To transfer learned motion priors to real robot actions, we implement a co-fine-tuning strategy that seamlessly bridges latent motion token prediction and real robot control. Extensive experiments show that the fine-tuned Moto-GPT exhibits superior robustness and efficiency on robot manipulation benchmarks, underscoring its effectiveness in transferring knowledge from video data to downstream visual manipulation tasks.

[Arxiv](https://arxiv.org/abs/2412.04445)