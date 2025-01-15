# ArithmAttack: 评估LLM在数学问题解决中对噪声上下文的抗干扰能力

发布时间：2025年01月14日

`LLM理论

理由：这篇论文主要研究大型语言模型（LLMs）在面对噪声输入时的鲁棒性，属于对LLMs的理论性质的研究。论文通过实验探究LLMs在噪声环境下的表现，并提出了ArithmAttack方法来测试模型的鲁棒性。这种研究更偏向于对LLMs的理论理解和性能分析，而不是具体的应用或系统实现。因此，将其归类为“LLM理论”更为合适。`

> ArithmAttack: Evaluating Robustness of LLMs to Noisy Context in Math Problem Solving

# 摘要

> 尽管LLMs在数学解题任务中表现出色，但其对噪声输入的鲁棒性研究尚不充分。本文提出ArithmAttack，旨在探究LLMs在面对含额外噪声（如标点符号）的提示时的表现。ArithmAttack实现简单且不会造成信息丢失，因为上下文中的单词保持不变。我们在噪声GSM8K和MultiArith数据集上测试了包括LLama3、Mistral和Mathstral在内的七种LLMs，结果显示所有模型均对噪声敏感，噪声越多，性能越差。

> While Large Language Models (LLMs) have shown impressive capabilities in math problem-solving tasks, their robustness to noisy inputs is not well-studied. In this work, we propose ArithmAttack to examine how robust the LLMs are when they encounter noisy prompts that contain extra noise in the form of punctuation marks. While being easy to implement, ArithmAttack does not cause any information loss since words are not added or deleted from the context. We evaluate the robustness of seven LLMs, including LLama3, Mistral, and Mathstral, on noisy GSM8K and MultiArith datasets. Our experiments suggest that all the studied models show vulnerability to such noise, with more noise leading to poorer performances.

[Arxiv](https://arxiv.org/abs/2501.08203)