# 你的领域中有什么？用知识图谱和大型语言模型构建科学领域的研究图谱

发布时间：2025年03月12日

`LLM应用` `知识图谱`

> What's In Your Field? Mapping Scientific Research with Knowledge Graphs and Large Language Models

# 摘要

> 科学文献的爆炸式增长让跨学科知识的整合与探索变得愈发困难。大型语言模型（LLMs）虽是理解科学文本的利器，但难以捕捉大规模文献中的深层关联。无结构方法如检索增强生成，能够筛选海量语料库以提取相关事实；然而，面对数百万个事实影响答案的情形，无结构方法成本高昂。结构化表示则提供了完美的补充，使系统性分析整个语料库成为可能。近期研究通过无结构或半结构化科学概念表示增强了LLMs；在此基础上，我们尝试利用LLMs提取结构化表示。结合LLMs的语义理解能力与科学概念模式，我们开发了一个能够回答整个文献集精确问题的系统原型。我们的模式跨学科通用，并仅需20个手动标注的摘要即可提取概念。为展示系统效果，我们从arXiv上提取了30,000篇论文的概念，涵盖天体物理、流体动力学和进化生物学领域。生成的数据库不仅突出了新兴趋势，还通过知识图谱可视化，为探索不断扩展的科学知识领域提供了全新视角。演示地址：abby101/surveyor-0 on HF Spaces。代码仓库：https://github.com/chiral-carbon/kg-for-science。

> The scientific literature's exponential growth makes it increasingly challenging to navigate and synthesize knowledge across disciplines. Large language models (LLMs) are powerful tools for understanding scientific text, but they fail to capture detailed relationships across large bodies of work. Unstructured approaches, like retrieval augmented generation, can sift through such corpora to recall relevant facts; however, when millions of facts influence the answer, unstructured approaches become cost prohibitive. Structured representations offer a natural complement -- enabling systematic analysis across the whole corpus. Recent work enhances LLMs with unstructured or semistructured representations of scientific concepts; to complement this, we try extracting structured representations using LLMs. By combining LLMs' semantic understanding with a schema of scientific concepts, we prototype a system that answers precise questions about the literature as a whole. Our schema applies across scientific fields and we extract concepts from it using only 20 manually annotated abstracts. To demonstrate the system, we extract concepts from 30,000 papers on arXiv spanning astrophysics, fluid dynamics, and evolutionary biology. The resulting database highlights emerging trends and, by visualizing the knowledge graph, offers new ways to explore the ever-growing landscape of scientific knowledge. Demo: abby101/surveyor-0 on HF Spaces. Code: https://github.com/chiral-carbon/kg-for-science.

[Arxiv](https://arxiv.org/abs/2503.09894)