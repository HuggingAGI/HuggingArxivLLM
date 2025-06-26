# SEED: 结构化编码器：驱动嵌入式解码的时间序列预测与LLMs

发布时间：2025年06月25日

`LLM应用` `时间序列预测` `模型架构`

> SEED: A Structural Encoder for Embedding-Driven Decoding in Time Series Prediction with LLMs

# 摘要

> 多变量时间序列预测要求模型同时捕捉变量间结构性依赖关系，并在多样化任务中实现泛化。尽管结构编码器在建模特征交互方面有效，但它们缺乏支持语义级推理或任务适应的能力。相反，大型语言模型（LLMs）具备强大的泛化能力，但仍然无法处理原始时间序列输入。这种差距限制了统一、可迁移预测系统的开发。因此，我们引入了SEED（结构编码器，用于嵌入驱动解码），它整合了四个阶段：基于标记感知的编码器用于补丁提取、对齐补丁与语言模型嵌入的投影模块、将补丁映射到任务感知原型的语义重新编程机制，以及用于预测的冻结语言模型。这种模块化架构将表示学习与推理分离，实现了数值模式与语义推理之间的高效对齐。实证结果表明，所提出的方法在强基线模型上实现了持续改进，而对各种数据集的比较研究证实了SEED在解决结构-语义建模差距中的作用。

> Multivariate time series forecasting requires models to simultaneously capture variable-wise structural dependencies and generalize across diverse tasks. While structural encoders are effective in modeling feature interactions, they lack the capacity to support semantic-level reasoning or task adaptation. Conversely, large language models (LLMs) possess strong generalization capabilities but remain incompatible with raw time series inputs. This gap limits the development of unified, transferable prediction systems. Therefore, we introduce SEED, a structural encoder for embedding-driven decoding, which integrates four stages: a token-aware encoder for patch extraction, a projection module that aligns patches with language model embeddings, a semantic reprogramming mechanism that maps patches to task-aware prototypes, and a frozen language model for prediction. This modular architecture decouples representation learning from inference, enabling efficient alignment between numerical patterns and semantic reasoning. Empirical results demonstrate that the proposed method achieves consistent improvements over strong baselines, and comparative studies on various datasets confirm SEED's role in addressing the structural-semantic modeling gap.

[Arxiv](https://arxiv.org/abs/2506.20167)