# GAOKAO-Eval：高考分数真能体现大型语言模型的强大能力吗？

发布时间：2024年12月13日

`LLM应用` `语言模型评估`

> GAOKAO-Eval: Does high scores truly reflect strong capabilities in LLMs?

# 摘要

> 大型语言模型（LLMs）通常借助人工打造的基准来评估，默认高分就意味着更出色的类人性能。然而，人们愈发担忧LLMs可能因数据泄露而“钻空子”，在获得高分的同时，面对人类觉得简单的任务却表现不佳。为切实解决此问题，我们创建了GAOKAO-Eval，这是基于中国高考的综合基准，并对高考前发布的代表性模型进行“闭卷”评估。与普遍看法相反，即便解决了数据泄露和全面性问题，GAOKAO-Eval仍显示高分并不能真正体现与人对齐的能力。为更好理解这种不匹配，我们从认知心理学引入Rasch模型来分析LLM的评分模式，确定了两个关键差异：1.在不同问题难度上表现异常一致；2.在相似难度问题上表现差异大。此外，我们发现教师对LLM生成答案的评分不一致以及反复出现的错误模式。我们发现这些现象在OpenAI o1背后的动机中有充分依据，而且o1的推理难度能够缓解这种不匹配。这些结果表明，GAOKAO-Eval能够揭示当前基准未捕捉到的LLM能力的局限性，也突显了需要更多与LLM对齐的难度分析。

> Large Language Models (LLMs) are commonly evaluated using human-crafted benchmarks, under the premise that higher scores implicitly reflect stronger human-like performance. However, there is growing concern that LLMs may ``game" these benchmarks due to data leakage, achieving high scores while struggling with tasks simple for humans. To substantively address the problem, we create GAOKAO-Eval, a comprehensive benchmark based on China's National College Entrance Examination (Gaokao), and conduct ``closed-book" evaluations for representative models released prior to Gaokao. Contrary to prevailing consensus, even after addressing data leakage and comprehensiveness, GAOKAO-Eval reveals that high scores still fail to truly reflect human-aligned capabilities. To better understand this mismatch, We introduce the Rasch model from cognitive psychology to analyze LLM scoring patterns and identify two key discrepancies: 1) anomalous consistent performance across various question difficulties, and 2) high variance in performance on questions of similar difficulty. In addition, We identified inconsistent grading of LLM-generated answers among teachers and recurring mistake patterns. we find that the phenomenons are well-grounded in the motivations behind OpenAI o1, and o1's reasoning-as-difficulties can mitigate the mismatch. These results show that GAOKAO-Eval can reveal limitations in LLM capabilities not captured by current benchmarks and highlight the need for more LLM-aligned difficulty analysis.

[Arxiv](https://arxiv.org/abs/2412.10056)