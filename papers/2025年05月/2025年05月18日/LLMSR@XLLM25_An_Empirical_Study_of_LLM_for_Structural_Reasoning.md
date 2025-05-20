# LLMSR@XLLM25：大型语言模型结构推理的实证研究

发布时间：2025年05月18日

`LLM应用` `推理系统`

> LLMSR@XLLM25: An Empirical Study of LLM for Structural Reasoning

# 摘要

> 我们展示了团队asdfo123在LLMSR@XLLM25共享任务中的参赛作品，该任务旨在评估大型语言模型生成精细、可控且可解释推理过程的能力。系统需提取所有问题条件，将思路链分解为陈述-证据对，并验证每一对的逻辑有效性。仅利用现成的Meta-Llama-3-8B-Instruct模型，我们设计了一个简洁的多轮少量样本提示，首先列出所有条件，然后引导模型对每一步推理进行标注、引用和裁决。基于正则表达式的轻量级后处理器对跨度进行规范化处理，并强制执行官方JSON模式。无需微调、外部检索或集成，我们的方法总体排名第5，实现了与复杂得多且资源消耗更大的管道相当的宏F1分数。我们通过分析我们方法的优势和局限性，以及未来在大型语言模型结构化推理方面的研究方向来总结。我们的代码可在https://github.com/asdfo123/LLMSR-asdfo123获取。

> We present Team asdfo123's submission to the LLMSR@XLLM25 shared task, which evaluates large language models on producing fine-grained, controllable, and interpretable reasoning processes. Systems must extract all problem conditions, decompose a chain of thought into statement-evidence pairs, and verify the logical validity of each pair. Leveraging only the off-the-shelf Meta-Llama-3-8B-Instruct, we craft a concise few-shot, multi-turn prompt that first enumerates all conditions and then guides the model to label, cite, and adjudicate every reasoning step. A lightweight post-processor based on regular expressions normalises spans and enforces the official JSON schema. Without fine-tuning, external retrieval, or ensembling, our method ranks 5th overall, achieving macro F1 scores on par with substantially more complex and resource-consuming pipelines. We conclude by analysing the strengths and limitations of our approach and outlining directions for future research in structural reasoning with LLMs. Our code is available at https://github.com/asdfo123/LLMSR-asdfo123.

[Arxiv](https://arxiv.org/abs/2505.12328)