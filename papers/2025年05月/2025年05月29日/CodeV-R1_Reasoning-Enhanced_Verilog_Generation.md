# CodeV-R1：通过增强推理能力实现Verilog代码生成

发布时间：2025年05月29日

`LLM应用

摘要中的论文主要探讨了如何将强化学习（RLVR）应用于训练大语言模型（LLMs）以生成硬件描述语言（HDLs），如Verilog。这属于将LLM应用于特定任务（EDA中的代码生成）的范畴，因此归类为LLM应用。` `电子设计自动化`

> CodeV-R1: Reasoning-Enhanced Verilog Generation

# 摘要

> 通过可验证奖励的强化学习（RLVR）训练的大语言模型（LLMs）在软件编程和数学问题等需要明确、可自动验证的任务中取得了突破。然而，将RLVR应用于电子设计自动化（EDA），特别是从自然语言（NL）规范中自动生成硬件描述语言（HDLs）如Verilog时，我们面临三大挑战：缺乏自动化且准确的验证环境、高质量NL-代码对的稀缺性以及RLVR的高昂计算成本。为此，我们推出了CodeV-R1，一个专为训练Verilog生成LLMs设计的RLVR框架。首先，我们开发了一种规则式的测试台生成方法，能够对黄金参考进行强大的等价性检查。其次，我们提出了一种往返数据综合方法，通过将开源的Verilog代码片段与LLM生成的NL描述配对，利用生成的测试台验证代码-NL-代码的一致性，并筛选出不等价的示例，从而构建高质量的数据集。最后，我们采用了一种创新的两阶段“蒸馏-然后-RL”训练pipeline：首先通过蒸馏启动模型的推理能力，然后使用我们的新型RLVR算法——自适应DAPO，通过自适应调整采样率来降低训练成本。最终，我们的模型CodeV-R1-7B在VerilogEval v2和RTLLM v1.1上的pass@1分别达到68.6%和72.9%，较之前最先进方法提升了12~20%，甚至在某些方面超过了671B参数的DeepSeek-R1。我们计划开放我们的模型、训练pipeline和数据集，以推动EDA和LLM社区的研究进展。

> Large language models (LLMs) trained via reinforcement learning with verifiable reward (RLVR) have achieved breakthroughs on tasks with explicit, automatable verification, such as software programming and mathematical problems. Extending RLVR to electronic design automation (EDA), especially automatically generating hardware description languages (HDLs) like Verilog from natural-language (NL) specifications, however, poses three key challenges: the lack of automated and accurate verification environments, the scarcity of high-quality NL-code pairs, and the prohibitive computation cost of RLVR. To this end, we introduce CodeV-R1, an RLVR framework for training Verilog generation LLMs. First, we develop a rule-based testbench generator that performs robust equivalence checking against golden references. Second, we propose a round-trip data synthesis method that pairs open-source Verilog snippets with LLM-generated NL descriptions, verifies code-NL-code consistency via the generated testbench, and filters out inequivalent examples to yield a high-quality dataset. Third, we employ a two-stage "distill-then-RL" training pipeline: distillation for the cold start of reasoning abilities, followed by adaptive DAPO, our novel RLVR algorithm that can reduce training cost by adaptively adjusting sampling rate. The resulting model, CodeV-R1-7B, achieves 68.6% and 72.9% pass@1 on VerilogEval v2 and RTLLM v1.1, respectively, surpassing prior state-of-the-art by 12~20%, while matching or even exceeding the performance of 671B DeepSeek-R1. We will release our model, training pipeline, and dataset to facilitate research in EDA and LLM communities.

[Arxiv](https://arxiv.org/abs/2505.24183)