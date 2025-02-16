# 面向资源受限NLP系统幻觉检测的少样本优化设计框架

发布时间：2025年01月27日

`LLM应用` `幻觉检测`

> Few-Shot Optimized Framework for Hallucination Detection in Resource-Limited NLP Systems

# 摘要

> 幻觉检测在文本生成领域一直是NLP系统的难点，尤其在机器翻译和定义建模等应用中常导致输出结果不可靠。现有方法在数据稀缺性和未标注数据集的限制方面仍显不足，这一点在SemEval-2024的SHROOM共享任务中得到了凸显。本研究提出了一种全新的框架来应对这些挑战，通过引入DeepSeek 少样本优化方法，借助迭代提示工程来提升弱标签生成效果。通过将数据重构以匹配指令生成模型，我们实现了高质量的标注，显著提升了下游模型的性能。进一步地，我们基于这些优化后的标注对Mistral-7B-Instruct-v0.3模型进行了微调，使其在资源受限的环境下能够准确检测幻觉。结合集成学习策略，我们的方法在测试集上达到了85.5%的准确率，为SHROOM任务树立了新的基准。本研究证明了数据重构、少样本优化和微调在构建适用于资源受限NLP系统的可扩展且鲁棒的幻觉检测框架中的有效性。


> Hallucination detection in text generation remains an ongoing struggle for natural language processing (NLP) systems, frequently resulting in unreliable outputs in applications such as machine translation and definition modeling. Existing methods struggle with data scarcity and the limitations of unlabeled datasets, as highlighted by the SHROOM shared task at SemEval-2024. In this work, we propose a novel framework to address these challenges, introducing DeepSeek Few-shot optimization to enhance weak label generation through iterative prompt engineering. We achieved high-quality annotations that considerably enhanced the performance of downstream models by restructuring data to align with instruct generative models. We further fine-tuned the Mistral-7B-Instruct-v0.3 model on these optimized annotations, enabling it to accurately detect hallucinations in resource-limited settings. Combining this fine-tuned model with ensemble learning strategies, our approach achieved 85.5% accuracy on the test set, setting a new benchmark for the SHROOM task. This study demonstrates the effectiveness of data restructuring, few-shot optimization, and fine-tuning in building scalable and robust hallucination detection frameworks for resource-constrained NLP systems.

[Arxiv](https://arxiv.org/abs/2501.16616)