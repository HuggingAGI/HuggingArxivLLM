# CAFE：基于检索头的粗到细信息检索方法，提升多文档问答能力

发布时间：2025年05月15日

`LLM应用` `问答系统` `信息检索`

> CAFE: Retrieval Head-based Coarse-to-Fine Information Seeking to Enhance Multi-Document QA Capability

# 摘要

> 尽管大型语言模型 (LLMs) 的上下文长度得到了扩展，但在处理长上下文输入的检索和推理方面仍存在挑战。现有方法通过提示策略和检索头试图缓解这一问题，但平衡检索精度和召回率仍是一大难点，这也影响了它们在问答任务中的表现。为此，我们提出了一种名为【数学公式】的两阶段粗到细方法，旨在提升多文档问答能力。通过逐步过滤背景和干扰文档的干扰，CAFE使回答更加依赖于关键证据。首先，粗粒度筛选利用检索头识别并排序相关文档；接着，细粒度引导机制将注意力集中于最相关的内容。实验结果表明，CAFE在多个基准测试中均优于现有方法，分别在Mistral模型上将SFT和RAG方法的SubEM指标提升了22.1%和13.7%。

> Advancements in Large Language Models (LLMs) have extended their input context length, yet they still struggle with retrieval and reasoning in long-context inputs. Existing methods propose to utilize the prompt strategy and retrieval head to alleviate this limitation. However, they still face challenges in balancing retrieval precision and recall, impacting their efficacy in answering questions. To address this, we introduce $\textbf{CAFE}$, a two-stage coarse-to-fine method to enhance multi-document question-answering capacities. By gradually eliminating the negative impacts of background and distracting documents, CAFE makes the responses more reliant on the evidence documents. Initially, a coarse-grained filtering method leverages retrieval heads to identify and rank relevant documents. Then, a fine-grained steering method guides attention to the most relevant content. Experiments across benchmarks show CAFE outperforms baselines, achieving up to 22.1% and 13.7% SubEM improvement over SFT and RAG methods on the Mistral model, respectively.

[Arxiv](https://arxiv.org/abs/2505.10063)