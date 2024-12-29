# 大型语言模型能够成为基于隐藏原理进行检索的基石。

发布时间：2024年12月21日

`RAG` `情感支持对话`

> Large Language Model Can Be a Foundation for Hidden Rationale-Based Retrieval

# 摘要

> 尽管检索增强生成（RAG）系统近来有所发展，但多数检索方法通常是为事实检索开发的，其假定查询和有效文档在语义上相似。在本文中，我们提出并研究了一种更具挑战性的检索任务——隐藏原理检索，在这种任务中，查询和文档不相似，但可通过推理链、逻辑关系或经验来推断。为应对此类问题，采用交叉编码器架构且经指令调整的大型语言模型（LLM）或许是不错的选择。为进一步强化开创性的基于 LLM 的检索器，我们设计了特殊指令，通过促使 LLM 回答二元选择问题，将检索任务转变为生成任务。该模型可通过直接偏好优化（DPO）进行微调。此框架还针对计算效率进行了优化，且性能未降低。我们将此检索框架命名为 RaHoRe，并在情感支持对话（ESC）中验证了其零样本和微调性能的优越性，与以往的检索工作相比更胜一筹。我们的研究表明，以 LLM 为基础开展更广泛的检索任务具有潜力。我们的代码、模型和数据集可在 https://github.com/flyfree5/LaHoRe 上获取。

> Despite the recent advancement in Retrieval-Augmented Generation (RAG) systems, most retrieval methodologies are often developed for factual retrieval, which assumes query and positive documents are semantically similar. In this paper, we instead propose and study a more challenging type of retrieval task, called hidden rationale retrieval, in which query and document are not similar but can be inferred by reasoning chains, logic relationships, or empirical experiences. To address such problems, an instruction-tuned Large language model (LLM) with a cross-encoder architecture could be a reasonable choice. To further strengthen pioneering LLM-based retrievers, we design a special instruction that transforms the retrieval task into a generative task by prompting LLM to answer a binary-choice question. The model can be fine-tuned with direct preference optimization (DPO). The framework is also optimized for computational efficiency with no performance degradation. We name this retrieval framework by RaHoRe and verify its zero-shot and fine-tuned performance superiority on Emotional Support Conversation (ESC), compared with previous retrieval works. Our study suggests the potential to employ LLM as a foundation for a wider scope of retrieval tasks. Our codes, models, and datasets are available on https://github.com/flyfree5/LaHoRe.

[Arxiv](https://arxiv.org/abs/2412.16615)