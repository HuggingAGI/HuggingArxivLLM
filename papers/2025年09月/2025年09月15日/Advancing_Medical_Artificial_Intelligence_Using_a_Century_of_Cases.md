# 百年病例助力医学人工智能发展

发布时间：2025年09月15日

`LLM应用` `医疗健康`

> Advancing Medical Artificial Intelligence Using a Century of Cases

# 摘要

> 背景：一个多世纪以来，《新英格兰医学杂志》的临床病理讨论会（CPCs）始终是检验医师专业推理能力的“试金石”，近年来更成为人工智能（AI）的“考场”。不过，以往AI评估往往只盯着“最终诊断”，却忽略了专家讨论中至关重要的多维度推理与表达能力。
  方法：我们收集了7102例CPC案例（1923-2025年）和1021项影像挑战（2006-2025年），经大量医师标注与自动化处理，构建出CPC-Bench基准库——这个经医师验证的平台涵盖10项文本及多模态任务，专门用于评估顶尖大型语言模型（LLMs）。同时，我们研发了“Dr. CaBot”AI讨论系统，它仅依据病例介绍就能生成书面报告和幻灯片视频演示，完美复刻人类专家在CPC中的角色。
  结果：面对377例当代CPC案例，OpenAI的o3模型60%能将最终诊断列为首位，84%可进入前十，性能超越20名医师的平均水平；下一步检查选择准确率更是高达98%。事件级医师标注则量化了AI在单位信息下的诊断准确率。但在文献检索和影像任务上，AI表现稍逊：o3与Google的Gemini 2.5 Pro在影像挑战中的准确率为67%。在CaBot与人类专家文本的盲测中，62次试验里有46次（74%）医师误判了鉴别诊断的来源，且CaBot在各项质量评分中均更受青睐。为推动研究，我们将公开CaBot与CPC-Bench。
  结论：LLMs在复杂文本鉴别诊断上已超越医师水平，且能逼真模拟专家医学演示，但影像解读和文献检索仍是短板。CPC-Bench与CaBot或将为医学AI的进展提供透明且持续的追踪工具。

> BACKGROUND: For over a century, the New England Journal of Medicine Clinicopathological Conferences (CPCs) have tested the reasoning of expert physicians and, recently, artificial intelligence (AI). However, prior AI evaluations have focused on final diagnoses without addressing the multifaceted reasoning and presentation skills required of expert discussants.
  METHODS: Using 7102 CPCs (1923-2025) and 1021 Image Challenges (2006-2025), we conducted extensive physician annotation and automated processing to create CPC-Bench, a physician-validated benchmark spanning 10 text-based and multimodal tasks, against which we evaluated leading large language models (LLMs). Then, we developed "Dr. CaBot," an AI discussant designed to produce written and slide-based video presentations using only the case presentation, modeling the role of the human expert in these cases.
  RESULTS: When challenged with 377 contemporary CPCs, o3 (OpenAI) ranked the final diagnosis first in 60% of cases and within the top ten in 84% of cases, outperforming a 20-physician baseline; next-test selection accuracy reached 98%. Event-level physician annotations quantified AI diagnostic accuracy per unit of information. Performance was lower on literature search and image tasks; o3 and Gemini 2.5 Pro (Google) achieved 67% accuracy on image challenges. In blinded comparisons of CaBot vs. human expert-generated text, physicians misclassified the source of the differential in 46 of 62 (74%) of trials, and scored CaBot more favorably across quality dimensions. To promote research, we are releasing CaBot and CPC-Bench.
  CONCLUSIONS: LLMs exceed physician performance on complex text-based differential diagnosis and convincingly emulate expert medical presentations, but image interpretation and literature retrieval remain weaker. CPC-Bench and CaBot may enable transparent and continued tracking of progress in medical AI.

[Arxiv](https://arxiv.org/abs/2509.12194)