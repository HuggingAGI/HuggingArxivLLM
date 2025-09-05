# MTQA: 思维矩阵：增强复杂问答推理

发布时间：2025年09月04日

`LLM应用` `基础理论`

> MTQA:Matrix of Thought for Enhanced Reasoning in Complex Question Answering

# 摘要

> 复杂问答（QA）是自然语言处理（NLP）领域的一项基础性难题。尽管大型语言模型（LLMs）在问答任务中表现出色，但面对复杂抽象的问题时，其推理能力不足导致性能大幅下降。思维链（CoT）、思维树（ToT）等方法虽致力于提升LLMs的推理能力，却存在树结构层内冗余、链结构路径单一等局限。部分研究尝试用检索增强生成（RAG）辅助LLMs推理，但如何高效利用包含多实体、多跳的海量信息仍是核心难题。为此，我们提出思维矩阵（MoT）——一种新颖高效的LLM思维结构。MoT借助“列-单元格通信”机制，从横向和纵向双维度剖析问题，促使LLMs主动开展多策略、深层次思考，既减少列单元格冗余，又提升推理能力。此外，我们还构建了事实校正机制：从检索到的知识图谱三元组与原始文本中提炼知识单元，以此强化LLM推理的初始知识储备并修正错误答案。这最终形成了一个高效精准的问答框架（MTQA）。实验结果显示，该框架在四个主流数据集上的F1和EM评分均超越现有最优方法，推理时间仅为基线方法的14.4%，充分体现了高效性与准确性。相关代码已开源至https://github.com/lyfiter/mtqa。

> Complex Question Answering (QA) is a fundamental and challenging task in NLP. While large language models (LLMs) exhibit impressive performance in QA, they suffer from significant performance degradation when facing complex and abstract QA tasks due to insufficient reasoning capabilities. Works such as Chain-of-Thought (CoT) and Tree-of-Thought (ToT) aim to enhance LLMs' reasoning abilities, but they face issues such as in-layer redundancy in tree structures and single paths in chain structures. Although some studies utilize Retrieval-Augmented Generation (RAG) methods to assist LLMs in reasoning, the challenge of effectively utilizing large amounts of information involving multiple entities and hops remains critical. To address this, we propose the Matrix of Thought (MoT), a novel and efficient LLM thought structure. MoT explores the problem in both horizontal and vertical dimensions through the "column-cell communication" mechanism, enabling LLMs to actively engage in multi-strategy and deep-level thinking, reducing redundancy within the column cells and enhancing reasoning capabilities. Furthermore, we develop a fact-correction mechanism by constructing knowledge units from retrieved knowledge graph triples and raw text to enhance the initial knowledge for LLM reasoning and correct erroneous answers. This leads to the development of an efficient and accurate QA framework (MTQA). Experimental results show that our framework outperforms state-of-the-art methods on four widely-used datasets in terms of F1 and EM scores, with reasoning time only 14.4\% of the baseline methods, demonstrating both its efficiency and accuracy. The code for this framework is available at https://github.com/lyfiter/mtqa.

[Arxiv](https://arxiv.org/abs/2509.03918)