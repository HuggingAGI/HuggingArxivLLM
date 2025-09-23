# GRIL：与大型语言模型结合的知识图谱检索集成学习

发布时间：2025年09月19日

`RAG` `基础理论`

> GRIL: Knowledge Graph Retrieval-Integrated Learning with Large Language Models

# 摘要

> 检索增强生成（RAG）借助外部知识为生成内容锚定事实依据，大幅降低了大型语言模型（LLMs）的幻觉现象。近期，RAG向图检索的扩展为多跳推理开辟了新路径——通过结构化知识提升推理能力，前景广阔。但现有图RAG方案普遍存在检索与推理过程脱节的问题，导致检索器难以适配LLM的推理需求；此外，这类方法在大规模图上进行多跳扩展时易受限于可扩展性，或过度依赖人工标注的真实实体——而开放域场景中这类标注往往缺失。

针对上述问题，我们提出一种与LLM端到端协同训练的新型图检索器：其核心是基于注意力的动态生长与剪枝机制，能自适应游走至多跳相关实体，并同步滤除噪声信息。在提取的子图中，结构化知识通过“软令牌”编码，语义特征通过“文本化图”表达，二者共同输入LLM——这不仅增强了LLM的推理能力，还实现了图检索器与LLM推理器的交互式联合训练。

在三个问答基准测试中，我们的方法均达到当前最优性能，印证了图-LLM联合优化在复杂推理任务中的显著优势。值得关注的是，该框架无需预定义真实实体——通过LLM的logits作为隐式反馈直接优化检索器，这让它在开放域场景中尤为高效。

> Retrieval-Augmented Generation (RAG) has significantly mitigated the hallucinations of Large Language Models (LLMs) by grounding the generation with external knowledge. Recent extensions of RAG to graph-based retrieval offer a promising direction, leveraging the structural knowledge for multi-hop reasoning. However, existing graph RAG typically decouples retrieval and reasoning processes, which prevents the retriever from adapting to the reasoning needs of the LLM. They also struggle with scalability when performing multi-hop expansion over large-scale graphs, or depend heavily on annotated ground-truth entities, which are often unavailable in open-domain settings. To address these challenges, we propose a novel graph retriever trained end-to-end with LLM, which features an attention-based growing and pruning mechanism, adaptively navigating multi-hop relevant entities while filtering out noise. Within the extracted subgraph, structural knowledge and semantic features are encoded via soft tokens and the verbalized graph, respectively, which are infused into the LLM together, thereby enhancing its reasoning capability and facilitating interactive joint training of the graph retriever and the LLM reasoner. Experimental results across three QA benchmarks show that our approach consistently achieves state-of-the-art performance, validating the strength of joint graph-LLM optimization for complex reasoning tasks. Notably, our framework eliminates the need for predefined ground-truth entities by directly optimizing the retriever using LLM logits as implicit feedback, making it especially effective in open-domain settings.

[Arxiv](https://arxiv.org/abs/2509.16502)