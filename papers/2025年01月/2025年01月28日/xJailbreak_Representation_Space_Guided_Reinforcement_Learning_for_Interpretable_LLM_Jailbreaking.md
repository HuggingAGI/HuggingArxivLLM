# xJailbreak: 基于表示空间引导的强化学习实现可解释的LLM越狱

发布时间：2025年01月28日

`LLM应用

理由：这篇论文主要讨论了如何通过强化学习（RL）方法来优化提示生成，以绕过大型语言模型（LLMs）的安全对齐机制。这涉及到对LLMs的实际应用和攻击方法的研究，属于LLM应用领域。论文的重点在于如何在实际应用中利用RL技术来提升攻击效果，而不是对LLM的理论或基础架构进行探讨。` `人工智能安全`

> xJailbreak: Representation Space Guided Reinforcement Learning for Interpretable LLM Jailbreaking

# 摘要

> # 摘要
安全对齐机制是防止大型语言模型（LLMs）生成有害或不道德内容的关键。然而，精心设计的提示可以绕过这些安全措施，无需访问模型内部参数，这种现象称为黑盒越狱。现有的启发式黑盒攻击方法（如遗传算法）因随机性而效果有限，而基于强化学习（RL）的方法则常缺乏有效的奖励信号。为此，我们提出了一种基于RL的新型黑盒越狱方法，通过分析良性提示与恶意提示的嵌入相似性来优化提示生成，确保重写提示与原始意图一致，同时提升攻击效果。我们还引入了一个综合评估框架，结合关键词、意图匹配和答案验证，全面评估越狱成功率。实验表明，我们的方法在多个主流开源和闭源LLMs（如Qwen2.5-7B-Instruct、Llama3.1-8B-Instruct和GPT-4o-0806）上达到了SOTA性能，为越狱攻击树立了新标杆，揭示了LLMs的潜在漏洞。代码已开源：https://github.com/Aegis1863/xJailbreak。

> Safety alignment mechanism are essential for preventing large language models (LLMs) from generating harmful information or unethical content. However, cleverly crafted prompts can bypass these safety measures without accessing the model's internal parameters, a phenomenon known as black-box jailbreak. Existing heuristic black-box attack methods, such as genetic algorithms, suffer from limited effectiveness due to their inherent randomness, while recent reinforcement learning (RL) based methods often lack robust and informative reward signals. To address these challenges, we propose a novel black-box jailbreak method leveraging RL, which optimizes prompt generation by analyzing the embedding proximity between benign and malicious prompts. This approach ensures that the rewritten prompts closely align with the intent of the original prompts while enhancing the attack's effectiveness. Furthermore, we introduce a comprehensive jailbreak evaluation framework incorporating keywords, intent matching, and answer validation to provide a more rigorous and holistic assessment of jailbreak success. Experimental results show the superiority of our approach, achieving state-of-the-art (SOTA) performance on several prominent open and closed-source LLMs, including Qwen2.5-7B-Instruct, Llama3.1-8B-Instruct, and GPT-4o-0806. Our method sets a new benchmark in jailbreak attack effectiveness, highlighting potential vulnerabilities in LLMs. The codebase for this work is available at https://github.com/Aegis1863/xJailbreak.

[Arxiv](https://arxiv.org/abs/2501.16727)