# 利用大型语言模型，通过双层句段结构提取与映射实现长文本风格迁移

发布时间：2025年05月11日

`LLM应用` `文本生成`

> Implementing Long Text Style Transfer with LLMs through Dual-Layered Sentence and Paragraph Structure Extraction and Mapping

# 摘要

> 本文针对长文本风格迁移中基于零样本学习的大型语言模型（LLMs）所面临的挑战，提出了一种结合句子级风格适应与段落级结构连贯性的层次化框架。我们主张，在有效的段落级风格迁移过程中，保持原文句法和语义信息的一致性至关重要。为此，我们的方法不仅在句子级别进行风格迁移，还引入了段落级别的语义考量，同时确保段落间结构的连贯性。我们提出的框架ZeroStylus通过两个系统化的阶段进行操作：从参考文本中获取层次化模板以及基于模板的多粒度匹配生成。该框架能够动态构建句子和段落级别的模板库，在保持句间逻辑关系的同时实现语境感知的转换。实验评估表明，与基线方法相比，我们的方法在三轴评估指标（风格一致性、内容保留度和表达质量）下取得了显著提升，其中结构化重写在风格一致性、内容保留和表达质量上的平均得分达到6.90，而直接提示方法的平均得分为6.70。消融实验验证了在风格迁移过程中同时引入句子和段落层次模板的必要性，通过段落级别的结构编码，我们在内容保留率上取得了比仅基于句子方法更高的胜率，同时也优于直接提示方法，这是因为我们采用了基于句子级别模式提取和匹配的策略。这些结果为无需平行语料库或LLM微调的连贯长文本风格迁移开辟了新能力。

> This paper addresses the challenge in long-text style transfer using zero-shot learning of large language models (LLMs), proposing a hierarchical framework that combines sentence-level stylistic adaptation with paragraph-level structural coherence. We argue that in the process of effective paragraph-style transfer, to preserve the consistency of original syntactic and semantic information, it is essential to perform style transfer not only at the sentence level but also to incorporate paragraph-level semantic considerations, while ensuring structural coherence across inter-sentential relationships. Our proposed framework, ZeroStylus, operates through two systematic phases: hierarchical template acquisition from reference texts and template-guided generation with multi-granular matching. The framework dynamically constructs sentence and paragraph template repositories, enabling context-aware transformations while preserving inter-sentence logical relationships. Experimental evaluations demonstrate significant improvements over baseline methods, with structured rewriting achieving 6.90 average score compared to 6.70 for direct prompting approaches in tri-axial metrics assessing style consistency, content preservation, and expression quality. Ablation studies validate the necessity of both template hierarchies during style transfer, showing higher content preservation win rate against sentence-only approaches through paragraph-level structural encoding, as well as direct prompting method through sentence-level pattern extraction and matching. The results establish new capabilities for coherent long-text style transfer without requiring parallel corpora or LLM fine-tuning.

[Arxiv](https://arxiv.org/abs/2505.07888)