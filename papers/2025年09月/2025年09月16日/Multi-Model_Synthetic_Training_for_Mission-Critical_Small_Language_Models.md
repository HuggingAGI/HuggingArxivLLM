# 关键任务型小型语言模型的多模型合成训练

发布时间：2025年09月16日

`LLM应用` `交通运输`

> Multi-Model Synthetic Training for Mission-Critical Small Language Models

# 摘要

> 大型语言模型（LLMs）虽已在众多领域展现卓越能力，但其在专业领域的应用仍受限于特定训练数据的稀缺性与复杂性。为此，我们提出一种创新方法：将LLMs用作“一次性教师”而非直接推理工具，为海事智能领域实现了261倍的成本降低。该方法通过多模型生成（GPT-4o与o3-mini），将32亿条船舶自动识别系统（AIS）跟踪记录转化为21,543个合成问答对，既能防止过拟合，又可确保推理准确性。经微调的Qwen2.5-7B模型在海事任务中准确率达75%，且推理成本远低于大型模型。本研究为专业AI应用的合成数据集生成这一新兴领域添砖加瓦，并为手动标注难以实现的领域提供了高可复现框架。

> Large Language Models (LLMs) have demonstrated remarkable capabilities across many domains, yet their appli- cation to specialized fields remains constrained by the scarcity and complexity of domain-specific training data. We present a novel approach that achieves a 261x cost reduction for maritime intelligence by using LLMs as one-time teachers rather than using them directly for inference. Our method transforms 3.2 billion Automatic Identification System (AIS) vessel tracking records into 21,543 synthetic question and answer pairs through multi-model generation (GPT-4o and o3-mini), preventing over- fitting and ensuring accurate reasoning. The resulting fine-tuned Qwen2.5-7B model achieves 75% accuracy on maritime tasks, while being substantially cheaper than using a larger model for inference. We show that smaller, cheaper models - when fine tuned properly - can provide similar accuracy compared to larger models that are prohibitively expensive. Our work contributes to the growing field of synthetic dataset generation for specialized AI applications and presents a highly reproducible framework for domains where manual annotation is infeasible. Beyond expand- ing research in the growing field of specialized small language models, our approach has immediate applications in maritime safety, security operations, and vessel traffic management systems in various industries.

[Arxiv](https://arxiv.org/abs/2509.13047)