# IRLBench：一个多模态、文化导向的爱尔兰-英语双语基准测试，专为开放性大语言模型推理能力评估而设计。

发布时间：2025年05月15日

`LLM应用` `多语言`

> IRLBench: A Multi-modal, Culturally Grounded, Parallel Irish-English Benchmark for Open-Ended LLM Reasoning Evaluation

# 摘要

> 大型语言模型（LLMs）近期的发展展示了令人鼓舞的知识和推理能力，但在多语言和低资源环境中的表现仍有待深入探索。现有基准测试常存在文化偏见，局限于文本评估，依赖于多项选择格式，更重要的是，对极度低资源语言的支持有限。为此，我们推出了IRLBench，该基准测试同时提供英语和爱尔兰语版本，其中爱尔兰语被联合国教科文组织认定为严重濒危语言。我们的基准测试基于2024年爱尔兰离校考试，涵盖12个代表性学科，支持对模型跨领域能力的细致分析。通过将任务定义为长文本生成，并结合官方评分标准，它不仅支持对正确性的全面评估，还支持对语言准确性的评估。我们对领先闭源和开源LLMs的广泛实验揭示了英语和爱尔兰语之间持续存在的性能差距，其中模型生成有效爱尔兰语回答的频率不到80%，而最佳性能模型在爱尔兰语中的正确率为55.8%，相比之下在英语中为76.2%。我们发布了IRLBench（https://huggingface.co/datasets/ReliableAI/IRLBench）和配套的评估代码库（https://github.com/ReML-AI/IRLBench），以支持未来在稳健、文化感知的多语言AI开发方面的研究。

> Recent advances in Large Language Models (LLMs) have demonstrated promising knowledge and reasoning abilities, yet their performance in multilingual and low-resource settings remains underexplored. Existing benchmarks often exhibit cultural bias, restrict evaluation to text-only, rely on multiple-choice formats, and, more importantly, are limited for extremely low-resource languages. To address these gaps, we introduce IRLBench, presented in parallel English and Irish, which is considered definitely endangered by UNESCO. Our benchmark consists of 12 representative subjects developed from the 2024 Irish Leaving Certificate exams, enabling fine-grained analysis of model capabilities across domains. By framing the task as long-form generation and leveraging the official marking scheme, it does not only support a comprehensive evaluation of correctness but also language fidelity. Our extensive experiments of leading closed-source and open-source LLMs reveal a persistent performance gap between English and Irish, in which models produce valid Irish responses less than 80\% of the time, and answer correctly 55.8\% of the time compared to 76.2\% in English for the best-performing model. We release IRLBench (https://huggingface.co/datasets/ReliableAI/IRLBench) and an accompanying evaluation codebase (https://github.com/ReML-AI/IRLBench) to enable future research on robust, culturally aware multilingual AI development.

[Arxiv](https://arxiv.org/abs/2505.13498)