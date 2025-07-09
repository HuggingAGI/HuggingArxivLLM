# # DeSTA2.5-音频：致力于构建通用型大规模音频语言模型，基于自动生成的跨模态对齐

发布时间：2025年07月03日

`LLM应用` `语言模型`

> DeSTA2.5-Audio: Toward General-Purpose Large Audio Language Model with Self-Generated Cross-Modal Alignment

# 摘要

> 我们推出DeSTA2.5-Audio，一款通用型大型音频语言模型（LALM），专注于实现强大的听觉感知和指令执行，无需针对特定任务进行音频指令微调。当前主流的LALMs通常通过训练大规模的人工整理或由LLM生成的音频指令数据集，为大型语言模型（LLMs）增添听觉功能。然而，这类方法常导致LLM原有语言能力的严重遗忘。为解决这一问题，我们重新设计了数据构建流程，并提出了DeSTA——一种自生成跨模态对齐策略，其中主干LLM自行生成训练目标。这种方法不仅保留了LLM的原生语言能力，还实现了有效的音频-文本对齐，从而无需特定任务微调即可实现零样本泛化。基于DeSTA，我们构建了DeSTA-AQA5M——一个大规模、任务无关的数据集，包含500万个训练样本，这些样本来自涵盖语音、环境音和音乐等50个多样化数据集的7000小时音频。在Dynamic-SUPERB、MMAU、SAKURA、Speech-IFEval和VoiceBench等广泛音频-语言基准测试中，DeSTA2.5-Audio展现了顶尖或极具竞争力的性能。全面的对比研究表明，我们的自生成策略在听觉感知和指令执行能力上超越了现有主流的数据构建与训练方法。我们的研究结果凸显了精心设计的数据构建在LALM开发中的关键作用，并为打造稳健通用的LALM提供了宝贵的实践启示。


> We introduce DeSTA2.5-Audio, a general-purpose Large Audio Language Model (LALM) designed for robust auditory perception and instruction-following, without requiring task-specific audio instruction-tuning. Recent LALMs typically augment Large Language Models (LLMs) with auditory capabilities by training on large-scale, manually curated or LLM-synthesized audio-instruction datasets. However, these approaches have often suffered from the catastrophic forgetting of the LLM's original language abilities. To address this, we revisit the data construction pipeline and propose DeSTA, a self-generated cross-modal alignment strategy in which the backbone LLM generates its own training targets. This approach preserves the LLM's native language proficiency while establishing effective audio-text alignment, thereby enabling zero-shot generalization without task-specific tuning. Using DeSTA, we construct DeSTA-AQA5M, a large-scale, task-agnostic dataset containing 5 million training samples derived from 7,000 hours of audio spanning 50 diverse datasets, including speech, environmental sounds, and music. DeSTA2.5-Audio achieves state-of-the-art or competitive performance across a wide range of audio-language benchmarks, including Dynamic-SUPERB, MMAU, SAKURA, Speech-IFEval, and VoiceBench. Comprehensive comparative studies demonstrate that our self-generated strategy outperforms widely adopted data construction and training strategies in both auditory perception and instruction-following capabilities. Our findings underscore the importance of carefully designed data construction in LALM development and offer practical insights for building robust, general-purpose LALMs.

[Arxiv](https://arxiv.org/abs/2507.02768)