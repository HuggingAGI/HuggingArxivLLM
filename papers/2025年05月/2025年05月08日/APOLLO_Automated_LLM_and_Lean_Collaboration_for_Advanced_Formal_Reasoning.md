# # APOLLO：通过自动化LLM与精益协作实现高级形式推理

发布时间：2025年05月08日

`LLM应用` `人工智能`

> APOLLO: Automated LLM and Lean Collaboration for Advanced Formal Reasoning

# 摘要

> 形式化推理和自动定理证明是机器学习中一个具有挑战性的子领域，其中机器需要使用像Lean这样的形式语言来证明数学定理。虽然形式化验证系统可以几乎瞬间判断一个证明是否正确，但使用大语言模型（LLMs）生成一个完全正确的形式化证明仍然是一项艰巨的任务。传统方法通常需要多次提示LLM（多达数千次），直到生成的其中一个证明通过验证系统。在本研究中，我们介绍了APOLLO（通过LLM和Lean协作实现的自动化证明修复），这是一个模块化、模型不可知的流水线，结合了Lean编译器的优势与LLM的推理能力，以在较低的采样预算下实现更好的证明生成结果。

Apollo指导一个完全自动化的流程：LLM生成定理的证明，一组代理分析证明，修复语法错误，使用Lean识别证明中的错误，隔离失败的子引理，利用自动求解器，并在每个剩余的目标上以低top-K预算调用LLM。修复后的子证明被重新组合和重新验证，迭代次数最多由用户控制。在miniF2F基准测试中，我们在7B参数模型中实现了75.0%的新最先进的准确率，同时将采样预算保持在一千以下。此外，Apollo将Goedel-Prover-SFT的最新准确率提高到65.6%，同时将样本复杂度从25,600次降低到几百次。通用模型（o3-mini、o4-mini）的准确率从3-7%跃升至40%以上。

我们的结果表明，针对LLM输出的、编译器引导的修复方法在效率和正确性方面都取得了显著提升，这为可扩展的自动化定理证明提供了一个通用范例。

> Formal reasoning and automated theorem proving constitute a challenging subfield of machine learning, in which machines are tasked with proving mathematical theorems using formal languages like Lean. A formal verification system can check whether a formal proof is correct or not almost instantaneously, but generating a completely correct formal proof with large language models (LLMs) remains a formidable task. The usual approach in the literature is to prompt the LLM many times (up to several thousands) until one of the generated proofs passes the verification system. In this work, we present APOLLO (Automated PrOof repair via LLM and Lean cOllaboration), a modular, model-agnostic pipeline that combines the strengths of the Lean compiler with an LLM's reasoning abilities to achieve better proof-generation results at a low sampling budget. Apollo directs a fully automated process in which the LLM generates proofs for theorems, a set of agents analyze the proofs, fix the syntax errors, identify the mistakes in the proofs using Lean, isolate failing sub-lemmas, utilize automated solvers, and invoke an LLM on each remaining goal with a low top-K budget. The repaired sub-proofs are recombined and reverified, iterating up to a user-controlled maximum number of attempts. On the miniF2F benchmark, we establish a new state-of-the-art accuracy of 75.0% among 7B-parameter models while keeping the sampling budget below one thousand. Moreover, Apollo raises the state-of-the-art accuracy for Goedel-Prover-SFT to 65.6% while cutting sample complexity from 25,600 to a few hundred. General-purpose models (o3-mini, o4-mini) jump from 3-7% to over 40% accuracy. Our results demonstrate that targeted, compiler-guided repair of LLM outputs yields dramatic gains in both efficiency and correctness, suggesting a general paradigm for scalable automated theorem proving.

[Arxiv](https://arxiv.org/abs/2505.05758)