# Proof2Silicon：基于强化学习的验证代码与硬件生成提示修复

发布时间：2025年09月07日

`强化学习` `工业与制造`

> Proof2Silicon: Prompt Repair for Verified Code and Hardware Generation via Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）在自动化代码生成领域已展现出惊人实力，但生成的代码却常无法通过形式化验证——这正是硬件和安全关键领域的必备要求。为解决这一核心局限，我们此前提出了PREFACE框架：这是一个基于强化学习（RL）的模型无关工具，通过迭代修复输入给冻结LLMs的提示，无需昂贵微调即可系统引导模型生成可形式化验证的Dafny代码。本文进一步提出全新端到端综合框架Proof2Silicon，它集成了PREFACE流程，能够直接从自然语言规范生成“构造即正确”的硬件。其工作流程包括：（1）借助PREFACE的验证器驱动RL智能体迭代优化提示生成，确保Dafny代码正确；（2）通过Dafny的Python后端与PyLog将验证后的Dafny程序自动转换为可综合高级C语言；（3）利用Vivado HLS生成RTL实现。在包含100个复杂任务的基准测试中，PREFACE的RL引导提示优化在多种LLM上均能将Dafny验证成功率提升最高21%。更重要的是，Proof2Silicon的端到端硬件综合成功率高达72%，可通过Vivado HLS流程生成RTL设计。这些结果证明了一个稳健、可扩展且自动化的LLM驱动形式化验证硬件综合流程，成功架起了自然语言规范与硅芯片实现之间的桥梁。

> Large Language Models (LLMs) have demonstrated impressive capabilities in automated code generation but frequently produce code that fails formal verification, an essential requirement for hardware and safety-critical domains. To overcome this fundamental limitation, we previously proposed PREFACE, a model-agnostic framework based on reinforcement learning (RL) that iteratively repairs the prompts provided to frozen LLMs, systematically steering them toward generating formally verifiable Dafny code without costly fine-tuning. This work presents Proof2Silicon, a novel end-to-end synthesis framework that embeds the previously proposed PREFACE flow to enable the generation of correctness-by-construction hardware directly from natural language specifications. Proof2Silicon operates by: (1) leveraging PREFACE's verifier-driven RL agent to optimize prompt generation iteratively, ensuring Dafny code correctness; (2) automatically translating verified Dafny programs into synthesizable high-level C using Dafny's Python backend and PyLog; and (3) employing Vivado HLS to produce RTL implementations. Evaluated rigorously on a challenging 100-task benchmark, PREFACE's RL-guided prompt optimization consistently improved Dafny verification success rates across diverse LLMs by up to 21%. Crucially, Proof2Silicon achieved an end-to-end hardware synthesis success rate of up to 72%, generating RTL designs through Vivado HLS synthesis flows. These results demonstrate a robust, scalable, and automated pipeline for LLM-driven, formally verified hardware synthesis, bridging natural-language specification and silicon realization.

[Arxiv](https://arxiv.org/abs/2509.06239)