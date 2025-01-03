# Transformer 网络中的上下文学习符号处理机制

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在符号处理方面的机制和局限性，并提出了新的语言和编译器来增强变压器的符号处理能力。这些内容属于对LLM内部机制和理论的研究，因此归类为“LLM理论”。` `人工智能` `符号处理`

> Mechanisms of Symbol Processing for In-Context Learning in Transformer Networks

# 摘要

> 大型语言模型（LLMs）通过上下文学习（ICL）展现了强大的符号处理能力，这一成就颠覆了长期以来关于人工神经网络无法掌握抽象符号操作的预测。我们深入探讨了变压器网络中实现稳健符号处理的机制，揭示了其在符号处理中的成功与局限。借鉴符号AI中生产系统架构的智慧，我们开发了高级语言PSL，用于编写复杂、抽象的符号处理程序，并创建编译器，确保PSL程序在变压器网络中的精确实现，且100%机械可解释。我们证明PSL具有图灵通用性，为理解变压器ICL提供了广泛见解。基于PSL程序编译的变压器架构，我们提出了多种提升变压器符号处理能力的途径。（注：论文第一部分为全文扩展概要。）

> Large Language Models (LLMs) have demonstrated impressive abilities in symbol processing through in-context learning (ICL). This success flies in the face of decades of predictions that artificial neural networks cannot master abstract symbol manipulation. We seek to understand the mechanisms that can enable robust symbol processing in transformer networks, illuminating both the unanticipated success, and the significant limitations, of transformers in symbol processing. Borrowing insights from symbolic AI on the power of Production System architectures, we develop a high-level language, PSL, that allows us to write symbolic programs to do complex, abstract symbol processing, and create compilers that precisely implement PSL programs in transformer networks which are, by construction, 100% mechanistically interpretable. We demonstrate that PSL is Turing Universal, so the work can inform the understanding of transformer ICL in general. The type of transformer architecture that we compile from PSL programs suggests a number of paths for enhancing transformers' capabilities at symbol processing. (Note: The first section of the paper gives an extended synopsis of the entire paper.)

[Arxiv](https://arxiv.org/abs/2410.17498)