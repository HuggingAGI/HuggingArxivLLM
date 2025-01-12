# 基于大型语言模型的检索增强TLAPS证明生成

发布时间：2025年01月06日

`LLM应用

理由：该论文摘要描述了一种利用大型语言模型（LLMs）来自动生成TLA+证明系统（TLAPS）证明的方法。该方法结合了检索增强生成（RAG）技术，并通过实验评估了其在不同复杂度证明义务上的表现。虽然论文中提到了检索增强生成（RAG），但核心内容仍然是关于如何将LLMs应用于形式验证工作流程中，因此应归类为LLM应用。` `形式验证` `自动化证明`

> Retrieval-Augmented TLAPS Proof Generation with Large Language Models

# 摘要

> 我们提出了一种利用大型语言模型（LLMs）为TLA+证明系统（TLAPS）自动生成证明的创新方法。该方法包含两个核心环节：一是将复杂证明义务拆解为简单子义务的子证明义务生成阶段；二是结合检索增强生成与已验证证明示例的证明生成阶段。我们通过从基础算术性质到算法性质的不同复杂度证明义务来评估该方法。实验显示，该方法虽能成功生成中等复杂度义务的有效证明，但在处理更复杂定理时仍有局限。这些结果表明，我们的方法能有效辅助特定类别性质的证明开发，推动LLMs在形式验证工作流程中的集成。

> We present a novel approach to automated proof generation for the TLA+ Proof System (TLAPS) using Large Language Models (LLMs). Our method combines two key components: a sub-proof obligation generation phase that breaks down complex proof obligations into simpler sub-obligations, and a proof generation phase that leverages Retrieval-Augmented Generation with verified proof examples. We evaluate our approach using proof obligations from varying complexity levels of proof obligations, spanning from fundamental arithmetic properties to the properties of algorithms. Our experiments demonstrate that while the method successfully generates valid proofs for intermediate-complexity obligations, it faces limitations with more complex theorems. These results indicate that our approach can effectively assist in proof development for certain classes of properties, contributing to the broader goal of integrating LLMs into formal verification workflows.

[Arxiv](https://arxiv.org/abs/2501.03073)