# 令牌高亮工具：对大型语言模型的越狱提示进行检查与缓解

发布时间：2024年12月24日

`LLM应用` `语言模型` `安全防御`

> Token Highlighter: Inspecting and Mitigating Jailbreak Prompts for Large Language Models

# 摘要

> 大型语言模型（LLMs）日益融入 ChatGPT 等服务中，为用户的查询提供回应。为降低潜在危害、防止滥用，人们齐心协力，将诸如基于人类反馈的强化学习（RLHF）等多种技术融入 LLMs 的训练，使 LLMs 契合人类价值观和法律合规要求。然而，近期研究发现，即便已对齐的 LLMs 也易遭受被称作越狱攻击的对抗性操纵。为应对此挑战，本文提出一种名为令牌高亮器的方法，用于检测和减轻用户查询中潜在的越狱威胁。令牌高亮器引入了称作肯定损失的概念，用于衡量 LLM 回答用户查询的意愿。接着，它利用用户查询中每个令牌的肯定损失梯度来定位越狱关键令牌。此外，令牌高亮器运用我们提出的软删除技术，通过缩小关键令牌的令牌嵌入来减轻其越狱影响。在两个已对齐的 LLMs（LLaMA-2 和 Vicuna-V1.5）上的实验结果表明，所提方法能有效抵御各类越狱攻击，同时在 AlpacaEval 基准的良性问题上保持出色表现。另外，令牌高亮器是一种性价比高且可解释的防御手段，因为它仅需查询受保护的 LLM 一次来计算肯定损失，且能在拒绝时突出关键令牌。

> Large Language Models (LLMs) are increasingly being integrated into services such as ChatGPT to provide responses to user queries. To mitigate potential harm and prevent misuse, there have been concerted efforts to align the LLMs with human values and legal compliance by incorporating various techniques, such as Reinforcement Learning from Human Feedback (RLHF), into the training of the LLMs. However, recent research has exposed that even aligned LLMs are susceptible to adversarial manipulations known as Jailbreak Attacks. To address this challenge, this paper proposes a method called Token Highlighter to inspect and mitigate the potential jailbreak threats in the user query. Token Highlighter introduced a concept called Affirmation Loss to measure the LLM's willingness to answer the user query. It then uses the gradient of Affirmation Loss for each token in the user query to locate the jailbreak-critical tokens. Further, Token Highlighter exploits our proposed Soft Removal technique to mitigate the jailbreak effects of critical tokens via shrinking their token embeddings. Experimental results on two aligned LLMs (LLaMA-2 and Vicuna-V1.5) demonstrate that the proposed method can effectively defend against a variety of Jailbreak Attacks while maintaining competent performance on benign questions of the AlpacaEval benchmark. In addition, Token Highlighter is a cost-effective and interpretable defense because it only needs to query the protected LLM once to compute the Affirmation Loss and can highlight the critical tokens upon refusal.

[Arxiv](https://arxiv.org/abs/2412.18171)