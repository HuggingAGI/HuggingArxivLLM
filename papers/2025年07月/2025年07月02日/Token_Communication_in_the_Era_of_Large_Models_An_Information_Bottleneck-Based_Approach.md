# 大模型时代的Token通信：基于信息瓶颈的方法

发布时间：2025年07月02日

`LLM应用

理由：这篇论文主要探讨了如何将多模态大语言模型（MLLM）应用于通信系统中，提出了一种新的通信范式UniToCom，并结合MLLM进行多模态理解和生成。这属于将LLM应用于具体领域的范畴，因此归类为LLM应用。` `智能通信`

> Token Communication in the Era of Large Models: An Information Bottleneck-Based Approach

# 摘要

> 本文提出了一种名为UniToCom的统一令牌通信范式，将令牌视为处理与无线传输的基本单元。具体而言，我们提出了生成信息瓶颈（GenIB）原则，以实现高效令牌表示，该原则能够学习保留关键信息并支持多模态可靠生成的令牌。基于GenIB的令牌化方法不仅提升了通信效率，还降低了计算复杂度。此外，我们开发了σ-GenIB，有效应对自回归建模中的方差崩溃问题，同时保持表示的多样性和稳定性。我们还采用基于因果Transformer的多模态大语言模型（MLLM）在接收端，通过下一令牌预测范式统一处理离散与连续令牌。仿真结果表明，UniToCom在动态信道条件下相较于基线方法具有显著优势。通过将令牌处理与MLLM相结合，UniToCom实现了可扩展且通用的通信，为多模态理解和生成提供了有力支持，为下一代智能通信提供了一种潜在的解决方案。

> This letter proposes UniToCom, a unified token communication paradigm that treats tokens as the fundamental units for both processing and wireless transmission. Specifically, to enable efficient token representations, we propose a generative information bottleneck (GenIB) principle, which facilitates the learning of tokens that preserve essential information while supporting reliable generation across multiple modalities. By doing this, GenIB-based tokenization is conducive to improving the communication efficiency and reducing computational complexity. Additionally, we develop $σ$-GenIB to address the challenges of variance collapse in autoregressive modeling, maintaining representational diversity and stability. Moreover, we employ a causal Transformer-based multimodal large language model (MLLM) at the receiver to unify the processing of both discrete and continuous tokens under the next-token prediction paradigm. Simulation results validate the effectiveness and superiority of the proposed UniToCom compared to baselines under dynamic channel conditions. By integrating token processing with MLLMs, UniToCom enables scalable and generalizable communication in favor of multimodal understanding and generation, providing a potential solution for next-generation intelligent communications.

[Arxiv](https://arxiv.org/abs/2507.01728)