# VeriReason：一种基于测试台反馈的强化学习方法，用于推理增强型Verilog生成

发布时间：2025年05月17日

`LLM应用` `电子设计自动化` `RTL生成`

> VeriReason: Reinforcement Learning with Testbench Feedback for Reasoning-Enhanced Verilog Generation

# 摘要

> 利用大型语言模型（LLMs）自动化寄存器传输级（RTL）代码生成，为数字电路设计带来了巨大潜力，能够显著降低人工工作量。然而，现有LLM方法在训练数据稀缺、规格与代码对齐、验证机制缺失以及通用性与专用性平衡等方面仍面临诸多挑战。受DeepSeek-R1启发，我们提出了VeriReason框架，该框架通过结合监督微调与引导奖励邻近优化（GRPO）强化学习，专门用于RTL生成。借助精心整理的训练示例和基于反馈的奖励模型，VeriReason将测试台评估与结构启发式方法相结合，并内置了自我检查功能以实现自主错误修正。在VerilogEval基准测试中，VeriReason取得了显著改进：在VerilogEval Machine基准上实现了83.1%的功能正确性，远超同规模模型及GPT-4 Turbo等更大规模的商用系统。此外，我们的方法相比基线方法，首次尝试的功能正确性提升了2.8倍，并展现出对未见设计的鲁棒泛化能力。据我们所知，VeriReason是首个成功将显式推理能力与强化学习相结合用于Verilog生成的系统，为自动RTL综合设定了新标杆。模型和数据集可在以下链接获取：https://huggingface.co/collections/AI4EDA-CASE 代码可访问：https://github.com/NellyW8/VeriReason

> Automating Register Transfer Level (RTL) code generation using Large Language Models (LLMs) offers substantial promise for streamlining digital circuit design and reducing human effort. However, current LLM-based approaches face significant challenges with training data scarcity, poor specification-code alignment, lack of verification mechanisms, and balancing generalization with specialization. Inspired by DeepSeek-R1, we introduce VeriReason, a framework integrating supervised fine-tuning with Guided Reward Proximal Optimization (GRPO) reinforcement learning for RTL generation. Using curated training examples and a feedback-driven reward model, VeriReason combines testbench evaluations with structural heuristics while embedding self-checking capabilities for autonomous error correction. On the VerilogEval Benchmark, VeriReason delivers significant improvements: achieving 83.1% functional correctness on the VerilogEval Machine benchmark, substantially outperforming both comparable-sized models and much larger commercial systems like GPT-4 Turbo. Additionally, our approach demonstrates up to a 2.8X increase in first-attempt functional correctness compared to baseline methods and exhibits robust generalization to unseen designs. To our knowledge, VeriReason represents the first system to successfully integrate explicit reasoning capabilities with reinforcement learning for Verilog generation, establishing a new state-of-the-art for automated RTL synthesis. The models and datasets are available at: https://huggingface.co/collections/AI4EDA-CASE Code is Available at: https://github.com/NellyW8/VeriReason

[Arxiv](https://arxiv.org/abs/2505.11849)