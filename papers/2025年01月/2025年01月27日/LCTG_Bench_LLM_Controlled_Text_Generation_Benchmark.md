# LCTG Bench: LLM 控制的文本生成基准

发布时间：2025年01月27日

`LLM应用

**理由**：该论文主要讨论了大型语言模型（LLMs）在可控性方面的应用，特别是针对日语等低资源语言的基准测试。论文提出了一个统一的评估框架（LCTG Bench），用于评估LLMs的可控性，并通过对多种模型的评估揭示了日语LLMs的现状与挑战。这属于LLM在实际应用中的研究，因此分类为LLM应用。`

> LCTG Bench: LLM Controlled Text Generation Benchmark

# 摘要

> 大型语言模型（LLMs）的崛起带来了更丰富、更高质量的机器生成文本，但其强大的表达能力也使得基于特定业务指令控制输出变得复杂。尽管已有专注于LLMs可控性的基准测试，但仍存在两大问题：一是这些测试主要针对英语和汉语等主流语言，忽略了日语等低资源语言；二是现有基准测试多采用任务特定的评估指标，缺乏一个统一的框架来根据不同用例的可控性选择模型。为此，我们推出了LCTG Bench，这是首个用于评估LLMs可控性的日语基准测试。LCTG Bench提供了一个统一的评估框架，帮助用户根据可控性选择最适合其用例的模型。通过对GPT-4等九种日语特定和多语言LLMs的评估，我们揭示了日语LLMs可控性的现状与挑战，并发现多语言模型与日语特定模型之间存在显著差距。

> The rise of large language models (LLMs) has led to more diverse and higher-quality machine-generated text. However, their high expressive power makes it difficult to control outputs based on specific business instructions. In response, benchmarks focusing on the controllability of LLMs have been developed, but several issues remain: (1) They primarily cover major languages like English and Chinese, neglecting low-resource languages like Japanese; (2) Current benchmarks employ task-specific evaluation metrics, lacking a unified framework for selecting models based on controllability across different use cases. To address these challenges, this research introduces LCTG Bench, the first Japanese benchmark for evaluating the controllability of LLMs. LCTG Bench provides a unified framework for assessing control performance, enabling users to select the most suitable model for their use cases based on controllability. By evaluating nine diverse Japanese-specific and multilingual LLMs like GPT-4, we highlight the current state and challenges of controllability in Japanese LLMs and reveal the significant gap between multilingual models and Japanese-specific models.

[Arxiv](https://arxiv.org/abs/2501.15875)