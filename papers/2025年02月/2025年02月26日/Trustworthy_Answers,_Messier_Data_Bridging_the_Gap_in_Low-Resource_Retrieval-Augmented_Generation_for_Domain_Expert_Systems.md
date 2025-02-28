# 可信的答案，杂乱无章的数据：为领域专家系统搭建低资源检索增强生成的桥梁

发布时间：2025年02月26日

`RAG` `汽车工程` `问答系统`

> Trustworthy Answers, Messier Data: Bridging the Gap in Low-Resource Retrieval-Augmented Generation for Domain Expert Systems

# 摘要

> RAG已成为提升大型语言模型（LLMs）的关键技术，尤其在领域专家系统中，LLMs可能缺乏足够的内在知识时，RAG通过减少幻觉现象发挥重要作用。然而，在资源有限的环境中开发这些系统，面临多重挑战：(1) 处理异构数据源，(2) 优化检索阶段以获得可靠答案，(3) 从多方面评估生成的答案。为应对这些挑战，我们提出了一条数据生成流水线，将原始多模态数据转化为结构化语料库和问答对，一个提升检索精度的高级重排序阶段，以及一个增强答案可追溯性的参考匹配算法。应用于汽车工程领域，与非RAG基线相比，我们的系统在事实正确性（+1.94）、信息量（+1.16）和 helpfulness（+1.67）方面均有提升，基于LLM评委的1-5分制评估。这些结果凸显了我们在不同方面方法的有效性，具有强大的答案基础和透明度。

> RAG has become a key technique for enhancing LLMs by reducing hallucinations, especially in domain expert systems where LLMs may lack sufficient inherent knowledge. However, developing these systems in low-resource settings introduces several challenges: (1) handling heterogeneous data sources, (2) optimizing retrieval phase for trustworthy answers, and (3) evaluating generated answers across diverse aspects. To address these, we introduce a data generation pipeline that transforms raw multi-modal data into structured corpus and Q&A pairs, an advanced re-ranking phase improving retrieval precision, and a reference matching algorithm enhancing answer traceability. Applied to the automotive engineering domain, our system improves factual correctness (+1.94), informativeness (+1.16), and helpfulness (+1.67) over a non-RAG baseline, based on a 1-5 scale by an LLM judge. These results highlight the effectiveness of our approach across distinct aspects, with strong answer grounding and transparency.

[Arxiv](https://arxiv.org/abs/2502.19596)