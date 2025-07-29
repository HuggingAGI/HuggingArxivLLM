# 构建一个基于效用的小型段落选择器，以提升检索增强生成的效果

发布时间：2025年07月25日

`RAG` `问答系统`

> Distilling a Small Utility-Based Passage Selector to Enhance Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过整合检索到的信息来提升大型语言模型（LLMs）的表现。标准检索流程优先考虑相关性，侧重于查询与段落之间的主题一致性。相比之下，在 RAG 中，重点已转向实用性，即考虑段落对生成准确答案的有用性。尽管实证研究表明基于实用性的检索在 RAG 中具有优势，但使用 LLM 进行实用性判断的高计算成本限制了评估的段落数量。这一限制对于需要大量信息的复杂查询尤为棘手。

为了解决这一问题，我们提出了一种方法，将 LLM 的实用性判断能力蒸馏到更小、更高效的模型中。我们的方法专注于基于实用性的选择而非排序，从而能够动态选择特定查询的有用段落，无需固定阈值。我们训练学生模型从教师 LLM 学习伪答案生成和实用性判断，采用滑动窗口方法动态选择有用段落。实验表明，基于实用性的选择为 RAG 提供了一种灵活且经济高效的解决方案，显著降低了计算成本，同时提升了答案质量。

我们展示了使用 Qwen3-32B 作为教师模型进行相关性排序和基于实用性的选择的蒸馏结果，分别蒸馏为 RankQwen1.7B 和 UtilityQwen1.7B。研究发现，对于复杂问题，基于实用性的选择在提升答案生成性能方面比相关性排序更有效。我们将为 MS MARCO 数据集提供相关性排序和基于实用性的选择的标注，支持该领域的进一步研究。

> Retrieval-augmented generation (RAG) enhances large language models (LLMs) by incorporating retrieved information. Standard retrieval process prioritized relevance, focusing on topical alignment between queries and passages. In contrast, in RAG, the emphasis has shifted to utility, which considers the usefulness of passages for generating accurate answers. Despite empirical evidence showing the benefits of utility-based retrieval in RAG, the high computational cost of using LLMs for utility judgments limits the number of passages evaluated. This restriction is problematic for complex queries requiring extensive information. To address this, we propose a method to distill the utility judgment capabilities of LLMs into smaller, more efficient models. Our approach focuses on utility-based selection rather than ranking, enabling dynamic passage selection tailored to specific queries without the need for fixed thresholds. We train student models to learn pseudo-answer generation and utility judgments from teacher LLMs, using a sliding window method that dynamically selects useful passages. Our experiments demonstrate that utility-based selection provides a flexible and cost-effective solution for RAG, significantly reducing computational costs while improving answer quality. We present the distillation results using Qwen3-32B as the teacher model for both relevance ranking and utility-based selection, distilled into RankQwen1.7B and UtilityQwen1.7B. Our findings indicate that for complex questions, utility-based selection is more effective than relevance ranking in enhancing answer generation performance. We will release the relevance ranking and utility-based selection annotations for the MS MARCO dataset, supporting further research in this area.

[Arxiv](https://arxiv.org/abs/2507.19102)