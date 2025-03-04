# GPIoT：为物联网程序的合成与开发量身定制小型语言模型

发布时间：2025年03月01日

`LLM应用` `物联网` `软件开发`

> GPIoT: Tailoring Small Language Models for IoT Program Synthesis and Development

# 摘要

> 代码大型语言模型（LLMs）能够根据用户需求自动生成代码和文档，从而显著提升软件开发效率。然而，面对需要领域知识的物联网（IoT）应用时，代码LLMs的局限性显现，无法有效合成专业程序。虽然检索增强生成（RAG）通过获取相关领域知识提供了一个解决方案，但其依赖强大的云LLMs（如GPT-4）处理用户需求和检索内容，导致隐私问题、网络不稳定以及高昂的LLM查询成本。此外，确保检索内容的正确性和相关性也是一项挑战。为了解决这些问题，我们提出了GPIoT，这是一个通过在物联网专用数据集上微调本地可部署的小型语言模型（SLMs）来生成物联网应用代码的系统。SLMs具有较小的模型规模，支持高效本地部署和执行，从而有效缓解隐私担忧和网络不确定性。通过在物联网专用数据集上微调SLMs，我们显著提升了其合成物联网相关程序的能力。为了全面评估GPIoT在物联网应用代码生成方面的性能，我们开发了一个基准测试IoTBench。大量实验和用户试用结果表明，GPIoT在生成物联网专用代码方面表现优异，与现有最先进的代码LLMs相比，平均任务准确率提升了64.7%，同时用户满意度也得到了显著提升。

> Code Large Language Models (LLMs) enhance software development efficiency by automatically generating code and documentation in response to user requirements. However, code LLMs cannot synthesize specialized programs when tasked with IoT applications that require domain knowledge. While Retrieval-Augmented Generation (RAG) offers a promising solution by fetching relevant domain knowledge, it necessitates powerful cloud LLMs (e.g., GPT-4) to process user requirements and retrieved contents, which raises significant privacy concerns. This approach also suffers from unstable networks and prohibitive LLM query costs. Moreover, it is challenging to ensure the correctness and relevance of the fetched contents. To address these issues, we propose GPIoT, a code generation system for IoT applications by fine-tuning locally deployable Small Language Models (SLMs) on IoT-specialized datasets. SLMs have smaller model sizes, allowing efficient local deployment and execution to mitigate privacy concerns and network uncertainty. Furthermore, by fine-tuning the SLMs with our IoT-specialized datasets, the SLMs' ability to synthesize IoT-related programs can be substantially improved. To evaluate GPIoT's capability in synthesizing programs for IoT applications, we develop a benchmark, IoTBench. Extensive experiments and user trials demonstrate the effectiveness of GPIoT in generating IoT-specialized code, outperforming state-of-the-art code LLMs with an average task accuracy increment of 64.7% and significant improvements in user satisfaction.

[Arxiv](https://arxiv.org/abs/2503.00686)