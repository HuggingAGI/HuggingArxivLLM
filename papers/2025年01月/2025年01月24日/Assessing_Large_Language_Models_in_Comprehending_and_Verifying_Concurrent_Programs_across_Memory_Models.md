# 评估大型语言模型在跨内存模型的并发程序理解与验证中的表现

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要研究了大型语言模型（LLMs）在理解和分析软件并发问题中的表现，特别是它们在顺序一致和宽松内存模型下的能力。这属于LLM在实际应用中的表现评估，因此归类为LLM应用。` `并发编程` `软件工程`

> Assessing Large Language Models in Comprehending and Verifying Concurrent Programs across Memory Models

# 摘要

> 随着并发编程的普及，有效识别和解决数据竞争、死锁等并发问题变得至关重要。本研究评估了GPT-3.5-turbo、GPT-4、GPT-4o、GPT-4o-mini和Mistral-AI的Large2等领先大型语言模型（LLMs）在理解和分析软件并发问题中的表现。鉴于Total Store Order（TSO）和Partial Store Order（PSO）等宽松内存模型在现代系统中广泛应用，甚至ARM和x86等架构也支持这些模型，我们的评估不仅涵盖顺序一致内存模型，还涉及这些宽松内存模型。具体而言，我们评估了模型在顺序一致内存模型下检测并发问题的能力，以及它们在顺序一致和宽松内存模型下验证并发程序正确性的能力。为此，我们使用了SV-COMP的pthread测试和25个ARM Litmus测试，这些测试专门用于评估TSO和PSO内存模型。实验结果显示，GPT-4、GPT-4o和Mistral-AI的Large2在顺序一致内存模型下表现出色，能够有效识别数据竞争和死锁。然而，尽管表现优异，所有LLMs在宽松内存模型下验证程序正确性时仍面临重大挑战，尤其是在准确捕捉内存排序约束方面，它们的能力尚不足以验证复杂场景中的小型程序。

> As concurrent programming becomes increasingly prevalent, effectively identifying and addressing concurrency issues such as data races and deadlocks is critical. This study evaluates the performance of several leading large language models (LLMs), including GPT-3.5-turbo, GPT-4, GPT-4o, GPT-4o-mini, and Mistral-AI's Large2, in understanding and analyzing concurrency issues within software programs. Given that relaxed memory models, such as Total Store Order (TSO) and Partial Store Order (PSO), are widely implemented and adapted in modern systems, supported even by commodity architectures like ARM and x86, our evaluation focuses not only on sequentially consistent memory models but also on these relaxed memory models. Specifically, we assess two main aspects: the models' capacity to detect concurrency problems under a sequentially consistent memory model and their ability to verify the correctness conditions of concurrent programs across both sequentially consistent and relaxed memory models. To do this, we leverage SV-COMP's pthread tests and 25 ARM Litmus tests designed to evaluate Total Store Order (TSO) and Partial Store Order (PSO) memory models. The experimental results reveal that GPT-4, GPT-4o, and Mistral-AI's Large2 demonstrate a robust understanding of concurrency issues, effectively identifying data races and deadlocks when assessed under a sequentially consistent memory model. However, despite its superior performance, all selected LLMs face significant challenges verifying program correctness under relaxed memory models. These LLMs exhibit limitations in accurately capturing memory ordering constraints, and their current capabilities fall short in verifying even small programs in these complex scenarios.

[Arxiv](https://arxiv.org/abs/2501.14326)