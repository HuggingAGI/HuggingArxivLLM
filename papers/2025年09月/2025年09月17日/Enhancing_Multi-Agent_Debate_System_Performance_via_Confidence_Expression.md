# 基于置信度表达提升多智能体辩论系统性能

发布时间：2025年09月17日

`Agent` `基础理论`

> Enhancing Multi-Agent Debate System Performance via Confidence Expression

# 摘要

> 生成式大型语言模型（LLMs）在各类任务中均表现卓越。近期研究提出了多智能体辩论（MAD）系统，通过多个LLM模拟人类辩论来提升任务表现。然而，尽管部分LLM在特定任务中拥有更优的知识或推理能力，却常因缺乏信心表达而难以在辩论中清晰展现这一优势。此外，不当的信心表达会使MAD系统中的智能体要么固执己见、坚持错误观点，要么过早收敛于非最优答案，最终削弱辩论效果并降低系统整体性能。为应对这些问题，我们提出在MAD系统中引入信心表达机制，让LLM能明确传递自身的信心程度。为验证该方法，我们构建了ConfMAD——一个在辩论全程融入信心表达的MAD框架。实验结果证实了该方法的有效性，我们还深入分析了信心对辩论动态的影响，为设计具备信心感知能力的MAD系统提供了启示。

> Generative Large Language Models (LLMs) have demonstrated remarkable performance across a wide range of tasks. Recent research has introduced Multi-Agent Debate (MAD) systems, which leverage multiple LLMs to simulate human debate and thereby improve task performance. However, while some LLMs may possess superior knowledge or reasoning capabilities for specific tasks, they often struggle to clearly communicate this advantage during debates, in part due to a lack of confidence expression. Moreover, inappropriate confidence expression can cause agents in MAD systems to either stubbornly maintain incorrect beliefs or converge prematurely on suboptimal answers, ultimately reducing debate effectiveness and overall system performance. To address these challenges, we propose incorporating confidence expression into MAD systems to allow LLMs to explicitly communicate their confidence levels. To validate this approach, we develop ConfMAD, a MAD framework that integrates confidence expression throughout the debate process. Experimental results demonstrate the effectiveness of our method, and we further analyze how confidence influences debate dynamics, offering insights into the design of confidence-aware MAD systems.

[Arxiv](https://arxiv.org/abs/2509.14034)