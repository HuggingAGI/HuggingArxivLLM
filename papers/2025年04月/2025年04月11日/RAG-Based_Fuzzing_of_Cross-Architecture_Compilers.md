# 跨架构编译器的 RAG 增强模糊测试方法

发布时间：2025年04月11日

`LLM应用

摘要中提到，论文提出了一种基于大语言模型（LLM）的编译器模糊测试工具，整合了检索增强生成（RAG）的概念，用于自动化生成测试用例。这表明该工作主要关注于将LLM应用于编译器测试领域，属于LLM的应用层面。因此，将其分类为LLM应用是合适的。` `编译器测试` `跨架构软件开发`

> RAG-Based Fuzzing of Cross-Architecture Compilers

# 摘要

> OneAPI 是一个开放标准，让开发者轻松实现跨架构软件开发。它提供了 DPC++ 和 C++ 编译器，这些编译器需要经过全面测试以确保其正确性、可靠性和安全性。编译器包含复杂的代码流和优化特性，因此需要深入了解编译器内部机制的开发者来设计针对特定路径的测试用例。然而，测试用例的创建是一个耗时且昂贵的过程。本文提出了一种基于大语言模型 (LLM) 的编译器模糊测试工具，该工具整合了检索增强生成 (RAG) 的概念。此工具能够自动化测试用例生成，从而解放经验丰富的编译器开发者，使其无需手动设计测试用例生成模式。我们在 Intel DPC++/C++ 编译器上验证了这一方法。该编译器支持 SYCL 代码编译，并允许开发者将其部署到不同架构上，例如来自不同供应商的 GPU 和 CPU。借助此工具，我们成功识别了 87 个 SYCL 代码测试用例，这些用例在使用 Intel DPC++ 和 clang++ 编译器编译并在不同架构上运行时，会导致输出值不匹配或编译器运行时错误。令人惊讶的是，这些测试用例以及受测编译器的意外行为是在没有任何先验背景知识的情况下，在短短数小时内发现的。该工具通过 LLM 提供的动态测试用例创建能力，显著减少了开发人员的时间投入，从而实现了高效的编译器模糊测试。

> OneAPI is an open standard that supports cross-architecture software development with minimal effort from developers. It brings DPC++ and C++ compilers which need to be thoroughly tested to verify their correctness, reliability, and security. Compilers have numerous code flows and optimization features. This process requires developers with deep understanding of the different compiler flows to craft testcases specific to target paths in the compiler. This testcase creation is a time-consuming and costly process. In this paper, we propose a large-language model (LLM)-based compiler fuzzing tool that integrates the concept of retrieval-augmented generation (RAG). This tool automates the testcase generation task and relieves experienced compiler developers from investing time to craft testcase generation patterns. We test our proposed approach on the Intel DPC++/C++ compiler. This compiler compiles SYCL code and allows developers to offload it to different architectures, e.g. GPUs and CPUs from different vendors. Using this tool, we managed to identify 87 SYCL code test cases that lead to output value mismatch or compiler runtime errors when compiled using Intel DPC++ and clang++ compilers and run on different architectures. The testcases and the identified unexpected behaviors of the compilers under test were obtained within only few hours with no prior background on the compiler passes under tests. This tool facilitates efficient compiler fuzzing with reduced developer time requirements via the dynamic testcase creation capability provided by an LLM with RAG.

[Arxiv](https://arxiv.org/abs/2504.08967)