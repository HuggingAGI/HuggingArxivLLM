# MUG-Eval：多语言生成能力的代理评估框架，适用于任何语言。

发布时间：2025年05月20日

`LLM应用`

> MUG-Eval: A Proxy Evaluation Framework for Multilingual Generation Capabilities in Any Language

# 摘要

> 评估大型语言模型（LLMs）的文本生成能力是一项具有挑战性的任务，尤其是在低资源语言领域，直接评估的方法十分匮乏。我们提出了MUG-Eval，一个新颖的框架，通过将现有基准转换为对话任务，并测量LLMs在这些任务上的准确性，来评估其多语言生成能力。我们特意设计这些对话任务，要求在目标语言中实现有效的沟通。随后，我们简单地将任务成功率作为成功生成对话的替代指标。我们的方法具有两大优势：它不依赖于特定语言的NLP工具或标注数据集（这些资源对大多数语言来说都十分有限），并且它不依赖于将LLMs作为评估者（其评估质量在少数几种高资源语言之外会显著下降）。我们在涵盖高、中、低资源类别的30种语言上评估了8种LLMs，并发现MUG-Eval与现有基准（$r$ > 0.75）具有很强的相关性，同时支持跨语言和跨模型的标准化比较。我们的框架为评估多语言生成能力提供了一种稳健且资源高效的解决方案，可以扩展到数千种语言。

> Evaluating text generation capabilities of large language models (LLMs) is challenging, particularly for low-resource languages where methods for direct assessment are scarce. We propose MUG-Eval, a novel framework that evaluates LLMs' multilingual generation capabilities by transforming existing benchmarks into conversational tasks and measuring the LLMs' accuracies on those tasks. We specifically designed these conversational tasks to require effective communication in the target language. Then, we simply use task success rate as a proxy of successful conversation generation. Our approach offers two key advantages: it is independent of language-specific NLP tools or annotated datasets, which are limited for most languages, and it does not rely on LLMs-as-judges, whose evaluation quality degrades outside a few high-resource languages. We evaluate 8 LLMs across 30 languages spanning high, mid, and low-resource categories, and we find that MUG-Eval correlates strongly with established benchmarks ($r$ > 0.75) while enabling standardized comparisons across languages and models. Our framework provides a robust and resource-efficient solution for evaluating multilingual generation that can be extended to thousands of languages.

[Arxiv](https://arxiv.org/abs/2505.14395)