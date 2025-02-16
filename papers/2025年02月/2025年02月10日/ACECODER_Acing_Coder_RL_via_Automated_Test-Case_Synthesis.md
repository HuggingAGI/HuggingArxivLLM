# # ACECODER: Acing Coder RL via Automated Test-Case Synthesis
ACECODER：通过自动化合成测试用例掌握Coder RL的技巧

发布时间：2025年02月10日

`LLM应用` `代码生成`

> ACECODER: Acing Coder RL via Automated Test-Case Synthesis

# 摘要

> 近期，代码模型的进展主要归功于监督微调（SFT），而强化学习（RL）的潜力仍未被充分挖掘，这主要是因为代码领域缺乏可靠的奖励数据或模型。本文通过引入大规模自动化测试用例合成技术，有效提升了代码模型的训练效果。具体来说，我们设计了一套从现有代码数据中生成大量（问题，测试用例）对的流水线。基于这些测试用例，我们根据采样程序的通过率构建了偏好对，并采用Bradley-Terry损失训练奖励模型。通过最佳的32采样方法，Llama-3.1-8B-Ins模型的性能平均提升了10个点，Qwen2.5-Coder-7B-Ins模型提升了5个点，使7B模型的性能达到了236B DeepSeek-V2.5的水平。此外，我们结合奖励模型和测试用例通过奖励进行强化学习，在HumanEval、MBPP、BigCodeBench和LiveCodeBench（V4）等多个基准测试中均取得了显著提升。特别值得注意的是，我们采用R1风格的训练方式，直接从Qwen2.5-Coder-base模型开始，并展示了仅需80个优化步骤，我们的RL训练就能使HumanEval-plus的性能提升超过25%，MBPP-plus的性能提升6%。我们相信，这些成果充分展现了强化学习在代码模型中的巨大潜力。

> Most progress in recent coder models has been driven by supervised fine-tuning (SFT), while the potential of reinforcement learning (RL) remains largely unexplored, primarily due to the lack of reliable reward data/model in the code domain. In this paper, we address this challenge by leveraging automated large-scale test-case synthesis to enhance code model training. Specifically, we design a pipeline that generates extensive (question, test-cases) pairs from existing code data. Using these test cases, we construct preference pairs based on pass rates over sampled programs to train reward models with Bradley-Terry loss. It shows an average of 10-point improvement for Llama-3.1-8B-Ins and 5-point improvement for Qwen2.5-Coder-7B-Ins through best-of-32 sampling, making the 7B model on par with 236B DeepSeek-V2.5. Furthermore, we conduct reinforcement learning with both reward models and test-case pass rewards, leading to consistent improvements across HumanEval, MBPP, BigCodeBench, and LiveCodeBench (V4). Notably, we follow the R1-style training to start from Qwen2.5-Coder-base directly and show that our RL training can improve model on HumanEval-plus by over 25\% and MBPP-plus by 6\% for merely 80 optimization steps. We believe our results highlight the huge potential of reinforcement learning in coder models.

[Arxiv](https://arxiv.org/abs/2502.01718)