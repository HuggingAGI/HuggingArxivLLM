# GPT 模型中的因果世界表征

发布时间：2024年12月10日

`LLM理论` `人工智能`

> Causal World Representation in the GPT Model

# 摘要

> 生成式预训练 Transformer（GPT）模型仅仅是为预测下一个标记而训练的，还是会隐式地学习一个世界模型，从而逐个标记地生成序列？我们通过推导 GPT 中注意力机制的因果解释来探讨此问题，并提出由此解释衍生出的因果世界模型。此外，我们认为在推理时，GPT 模型可用于分布内序列的零样本因果结构学习。在一个受控的合成环境中，依据奥赛罗棋盘游戏的设置和规则进行了实证评估。一个在旨在获胜的真实世界游戏中预训练过的 GPT，在仅遵循游戏规则的合成数据上接受了测试。我们发现，对于注意力机制以高置信度编码因果结构的序列，GPT 模型倾向于生成符合游戏规则的下一步动作。通常，在 GPT 模型生成不符合游戏规则的动作时，它也无法捕捉到任何因果结构。

> Are generative pre-trained transformer (GPT) models only trained to predict the next token, or do they implicitly learn a world model from which a sequence is generated one token at a time? We examine this question by deriving a causal interpretation of the attention mechanism in GPT, and suggesting a causal world model that arises from this interpretation. Furthermore, we propose that GPT-models, at inference time, can be utilized for zero-shot causal structure learning for in-distribution sequences. Empirical evaluation is conducted in a controlled synthetic environment using the setup and rules of the Othello board game. A GPT, pre-trained on real-world games played with the intention of winning, is tested on synthetic data that only adheres to the game rules. We find that the GPT model tends to generate next moves that adhere to the game rules for sequences for which the attention mechanism encodes a causal structure with high confidence. In general, in cases for which the GPT model generates moves that do not adhere to the game rules, it also fails to capture any causal structure.

[Arxiv](https://arxiv.org/abs/2412.07446)