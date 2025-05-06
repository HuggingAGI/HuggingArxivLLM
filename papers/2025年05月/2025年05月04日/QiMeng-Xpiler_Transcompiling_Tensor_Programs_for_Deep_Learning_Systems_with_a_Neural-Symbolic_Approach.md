# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月04日

`LLM应用

论文摘要：异构深度学习系统（DLS）如GPU和ASIC在工业数据中心广泛应用，但为不同平台开发低级张量程序带来了巨大挑战。针对这一问题，我们提出了一种创新的解决方案：QiMeng-Xpiler转译编译器，它结合大型语言模型（LLMs）和符号程序合成技术，实现跨平台张量程序的自动转换。通过预定义的元提示，我们设计了多个LLM辅助的编译阶段，使程序转换更加高效。在每次转换中，借助符号合成技术修复少量错误代码片段，确保转换质量。为提升性能，我们采用层次化自动调优策略，系统探索编译参数与阶段序列。实验结果表明，QiMeng-Xpiler在4种不同编程接口的DLS平台上，以95%的准确率成功转换张量程序，性能提升达2.0倍，较人工优化库高出96.0倍。这一突破大幅提升了DLS的编程效率。

LLM应用` `编译器`

> QiMeng-Xpiler: Transcompiling Tensor Programs for Deep Learning Systems with a Neural-Symbolic Approach

# 摘要

> 异构深度学习系统（DLS）如GPU和ASIC在工业数据中心广泛应用，但为不同平台开发低级张量程序带来了巨大挑战。针对这一问题，我们提出了一种创新的解决方案：QiMeng-Xpiler转译编译器，它结合大型语言模型（LLMs）和符号程序合成技术，实现跨平台张量程序的自动转换。通过预定义的元提示，我们设计了多个LLM辅助的编译阶段，使程序转换更加高效。在每次转换中，借助符号合成技术修复少量错误代码片段，确保转换质量。为提升性能，我们采用层次化自动调优策略，系统探索编译参数与阶段序列。实验结果表明，QiMeng-Xpiler在4种不同编程接口的DLS平台上，以95%的准确率成功转换张量程序，性能提升达2.0倍，较人工优化库高出96.0倍。这一突破大幅提升了DLS的编程效率。

> Heterogeneous deep learning systems (DLS) such as GPUs and ASICs have been widely deployed in industrial data centers, which requires to develop multiple low-level tensor programs for different platforms. An attractive solution to relieve the programming burden is to transcompile the legacy code of one platform to others. However, current transcompilation techniques struggle with either tremendous manual efforts or functional incorrectness, rendering "Write Once, Run Anywhere" of tensor programs an open question.
  We propose a novel transcompiler, i.e., QiMeng-Xpiler, for automatically translating tensor programs across DLS via both large language models (LLMs) and symbolic program synthesis, i.e., neural-symbolic synthesis. The key insight is leveraging the powerful code generation ability of LLM to make costly search-based symbolic synthesis computationally tractable. Concretely, we propose multiple LLM-assisted compilation passes via pre-defined meta-prompts for program transformation. During each program transformation, efficient symbolic program synthesis is employed to repair incorrect code snippets with a limited scale. To attain high performance, we propose a hierarchical auto-tuning approach to systematically explore both the parameters and sequences of transformation passes. Experiments on 4 DLS with distinct programming interfaces, i.e., Intel DL Boost with VNNI, NVIDIA GPU with CUDA, AMD MI with HIP, and Cambricon MLU with BANG, demonstrate that QiMeng-Xpiler correctly translates different tensor programs at the accuracy of 95% on average, and the performance of translated programs achieves up to 2.0x over vendor-provided manually-optimized libraries. As a result, the programming productivity of DLS is improved by up to 96.0x via transcompiling legacy tensor programs.

[Arxiv](https://arxiv.org/abs/2505.02146)