# 基于 LLM 的自动化评分系统，结合人工回环机制

发布时间：2025年04月07日

`LLM应用` `评分评估`

> LLM-based Automated Grading with Human-in-the-Loop

# 摘要

> 人工智能（AI）技术，尤其是大型语言模型（LLMs），为教育领域注入了革新动力。在众多应用中，专注于评估开放文本回答的自动简答评分（ASAG）因 LLMs 的引入而取得显著突破。这些模型不仅超越传统 ASAG 方法的评分性能，更突破了简单对比“黄金”答案的局限，支持基于评分标准等更复杂的评估场景。然而，现有 LLM 驱动方法在基于评分标准的评估中仍难以匹敌人类水平，主要源于其对全自动方法的依赖。本研究通过人机协同（HITL）方式，探索 LLMs 在 ASAG 任务中的潜力。我们提出的 GradeHITL 框架，借助 LLMs 的生成能力，向人类专家提问并整合其见解，动态优化评分标准。这一自适应机制显著提升了评分准确性，超越现有方法，使 ASAG 更趋近于人类水平的评估。

> The rise of artificial intelligence (AI) technologies, particularly large language models (LLMs), has brought significant advancements to the field of education. Among various applications, automatic short answer grading (ASAG), which focuses on evaluating open-ended textual responses, has seen remarkable progress with the introduction of LLMs. These models not only enhance grading performance compared to traditional ASAG approaches but also move beyond simple comparisons with predefined "golden" answers, enabling more sophisticated grading scenarios, such as rubric-based evaluation. However, existing LLM-powered methods still face challenges in achieving human-level grading performance in rubric-based assessments due to their reliance on fully automated approaches. In this work, we explore the potential of LLMs in ASAG tasks by leveraging their interactive capabilities through a human-in-the-loop (HITL) approach. Our proposed framework, GradeHITL, utilizes the generative properties of LLMs to pose questions to human experts, incorporating their insights to refine grading rubrics dynamically. This adaptive process significantly improves grading accuracy, outperforming existing methods and bringing ASAG closer to human-level evaluation.

[Arxiv](https://arxiv.org/abs/2504.05239)