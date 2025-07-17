# 借助大型语言模型的多粒度融合，提升上下文ASR效果

发布时间：2025年07月16日

`LLM应用` `语音识别`

> Improving Contextual ASR via Multi-grained Fusion with Large Language Models

# 摘要

> 端到端自动语音识别（ASR）模型在转录普通语音方面表现出色，但在识别语境相关的关键词（如专有名词或用户特定实体）时常常力不从心。以往研究尝试通过文本模态中的关键词词典来提升识别效果，方法包括逐词生成的词级别融合，或直接复制关键词短语的短语级别融合。然而，这些方法在不同粒度上运行，各有局限。本文提出了一种全新的多粒度融合方法，结合词级别和短语级别的优势，并借助大型语言模型（LLMs）。我们的方法采用优雅的晚期融合策略，将ASR的声学信息与LLMs的丰富上下文知识相结合，实现细粒度词精度与整体短语理解的平衡。在中文和英文数据集上，我们的方法在关键词相关指标上达到最先进水平，同时保持非关键词文本的高准确率。消融研究证实了词级别和短语级别组件对性能提升的显著贡献，两者在我们的联合多粒度框架中相辅相成。我们的代码和模型将在https://github.com/上公开发布。

> While end-to-end Automatic Speech Recognition (ASR) models have shown impressive performance in transcribing general speech, they often struggle to accurately recognize contextually relevant keywords, such as proper nouns or user-specific entities.
  Previous approaches have explored leveraging keyword dictionaries in the textual modality to improve keyword recognition, either through token-level fusion that guides token-by-token generation or phrase-level fusion that enables direct copying of keyword phrases.
  However, these methods operate at different granularities and have their own limitations.
  In this paper, we propose a novel multi-grained fusion approach that jointly leverages the strengths of both token-level and phrase-level fusion with Large Language Models (LLMs).
  Our approach incorporates a late-fusion strategy that elegantly combines ASR's acoustic information with LLM's rich contextual knowledge, balancing fine-grained token precision with holistic phrase-level understanding.
  Experiments on Chinese and English datasets demonstrate that our approach achieves state-of-the-art performance on keyword-related metrics while preserving high accuracy on non-keyword text.
  Ablation studies further confirm that the token-level and phrase-level components both contribute significantly to the performance gains, complementing each other in our joint multi-grained framework.
  The code and models will be publicly available at https://github.com/.

[Arxiv](https://arxiv.org/abs/2507.12252)