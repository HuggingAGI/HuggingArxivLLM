# ECKGBench：基于知识图谱的电商领域大型语言模型基准评测

发布时间：2025年03月20日

`LLM应用

理由：这篇论文讨论了大型语言模型在电子商务领域的应用，特别是如何评估这些模型在电商知识方面的表现。它提出了一个专门的数据集ECKGBench，用于评估LLMs在电商领域的知识能力，并探讨了这些模型在电商中的知识边界。因此，它属于LLM应用类别。` `电子商务` `知识图谱`

> ECKGBench: Benchmarking Large Language Models in E-commerce Leveraging Knowledge Graph

# 摘要

> 大型语言模型（LLMs）在各类NLP任务中表现卓越，其在电子商务领域的潜力同样不可忽视，已在平台搜索、个性化推荐和客户服务中得到广泛应用。然而，LLMs的事实性问题（如幻觉现象）在电商领域尤为紧迫，因其直接影响用户体验和收入。尽管已有方法评估LLMs的事实性，但可靠性不足、成本高昂及缺乏领域专业知识等问题，导致电商领域有效评估仍存空白。为此，我们提出了专门用于评估LLMs电商知识能力的ECKGBench数据集。通过基于大规模知识图谱的标准化工作流程，我们能够自动生成问题，确保可靠性。采用简单问答范式，以最小的输入输出令牌显著提升评估效率。同时，我们在每个评估阶段融入丰富的电商专业知识，包括人工标注、提示设计、负采样和验证。此外，我们从全新视角探索了LLMs在电商领域的知识边界。通过对多种先进LLMs在ECKGBench上的综合评估，我们提供了细致入微的分析和见解，助力更好地利用LLMs赋能电子商务。

> Large language models (LLMs) have demonstrated their capabilities across various NLP tasks. Their potential in e-commerce is also substantial, evidenced by practical implementations such as platform search, personalized recommendations, and customer service. One primary concern associated with LLMs is their factuality (e.g., hallucination), which is urgent in e-commerce due to its significant impact on user experience and revenue. Despite some methods proposed to evaluate LLMs' factuality, issues such as lack of reliability, high consumption, and lack of domain expertise leave a gap between effective assessment in e-commerce. To bridge the evaluation gap, we propose ECKGBench, a dataset specifically designed to evaluate the capacities of LLMs in e-commerce knowledge. Specifically, we adopt a standardized workflow to automatically generate questions based on a large-scale knowledge graph, guaranteeing sufficient reliability. We employ the simple question-answering paradigm, substantially improving the evaluation efficiency by the least input and output tokens. Furthermore, we inject abundant e-commerce expertise in each evaluation stage, including human annotation, prompt design, negative sampling, and verification. Besides, we explore the LLMs' knowledge boundaries in e-commerce from a novel perspective. Through comprehensive evaluations of several advanced LLMs on ECKGBench, we provide meticulous analysis and insights into leveraging LLMs for e-commerce.

[Arxiv](https://arxiv.org/abs/2503.15990)