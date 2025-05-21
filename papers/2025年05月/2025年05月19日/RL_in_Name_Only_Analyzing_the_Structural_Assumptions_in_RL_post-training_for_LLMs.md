# 强化学习，仅是徒有其名？解构LLM训练后强化学习的结构假设

发布时间：2025年05月19日

`LLM理论` `人工智能`

> RL in Name Only? Analyzing the Structural Assumptions in RL post-training for LLMs

# 摘要

> 基于强化学习的大语言模型（LLMs）后训练方法近期备受关注，尤其是在DeepSeek R1采用GRPO进行微调后。面对强化学习提升推理能力的种种炒作，我们对相关方法的公式化和假设进行了深入分析。我们首先指出了将LLM训练建模为马尔可夫决策过程（MDP）时的流行假设，并揭示这些假设如何导致了一个无需传统RL/GRPO框架的退化MDP。这两个关键假设包括：（1）将MDP状态简化为上下文窗口，动作则为LLMs中的标记；（2）将轨迹奖励均匀分配。通过全面分析，我们发现这些假设使强化学习方法在本质上等同于结果驱动的监督学习。在GSM8K和Countdown基准测试中，结合正负样本的迭代监督微调与GRPO训练相当。我们进一步指出，这些假设间接激励强化学习生成更长的中间标记序列，从而支持了“RL生成更长思考轨迹”的观点。尽管强化学习可能对提升LLM推理能力大有裨益，但我们的分析表明，MDP建模中的简单假设使得相关框架及其解释值得商榷。

> Reinforcement learning-based post-training of large language models (LLMs) has recently gained attention, particularly following the release of DeepSeek R1, which applied GRPO for fine-tuning. Amid the growing hype around improved reasoning abilities attributed to RL post-training, we critically examine the formulation and assumptions underlying these methods. We start by highlighting the popular structural assumptions made in modeling LLM training as a Markov Decision Process (MDP), and show how they lead to a degenerate MDP that doesn't quite need the RL/GRPO apparatus. The two critical structural assumptions include (1) making the MDP states be just a concatenation of the actions-with states becoming the context window and the actions becoming the tokens in LLMs and (2) splitting the reward of a state-action trajectory uniformly across the trajectory. Through a comprehensive analysis, we demonstrate that these simplifying assumptions make the approach effectively equivalent to an outcome-driven supervised learning. Our experiments on benchmarks including GSM8K and Countdown using Qwen-2.5 base models show that iterative supervised fine-tuning, incorporating both positive and negative samples, achieves performance comparable to GRPO-based training. We will also argue that the structural assumptions indirectly incentivize the RL to generate longer sequences of intermediate tokens-which in turn feeds into the narrative of "RL generating longer thinking traces." While RL may well be a very useful technique for improving the reasoning abilities of LLMs, our analysis shows that the simplistic structural assumptions made in modeling the underlying MDP render the popular LLM RL frameworks and their interpretations questionable.

[Arxiv](https://arxiv.org/abs/2505.13697)