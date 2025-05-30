# 打造异常行为测试工具，助力大型语言模型

发布时间：2025年05月28日

`LLM应用` `软件工程`

> A Tool for Generating Exceptional Behavior Tests With Large Language Models

# 摘要

> 异常行为测试（EBTs）是软件开发中不可或缺的一部分，用于确保代码能够正确处理不受欢迎的事件并抛出适当的异常。然而，开发人员往往更关注测试“快乐路径”（即没有不受欢迎事件的路径），而忽视了异常场景。针对这一问题，我们提出了exLong框架，它能够自动生成EBTs。exLong基于从CodeLlama微调的大型语言模型（LLM），结合了对抛出异常的跟踪、保护抛出语句的条件表达式以及执行类似跟踪的非异常行为测试的推理。我们的演示视频展示了exLong如何有效协助开发人员为项目创建全面的EBTs（可在https://youtu.be/Jro8kMgplZk观看）。

> Exceptional behavior tests (EBTs) are crucial in software development for verifying that code correctly handles unwanted events and throws appropriate exceptions. However, prior research has shown that developers often prioritize testing "happy paths", e.g., paths without unwanted events over exceptional scenarios. We present exLong, a framework that automatically generates EBTs to address this gap. exLong leverages a large language model (LLM) fine-tuned from CodeLlama and incorporates reasoning about exception-throwing traces, conditional expressions that guard throw statements, and non-exceptional behavior tests that execute similar traces. Our demonstration video illustrates how exLong can effectively assist developers in creating comprehensive EBTs for their project (available at https://youtu.be/Jro8kMgplZk).

[Arxiv](https://arxiv.org/abs/2505.22818)