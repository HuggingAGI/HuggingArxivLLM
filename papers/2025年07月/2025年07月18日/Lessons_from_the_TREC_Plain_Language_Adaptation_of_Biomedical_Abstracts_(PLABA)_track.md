# # 从 TREC 生物医学摘要平实语言转化赛道中汲取的经验

发布时间：2025年07月18日

`LLM应用` `生物医学`

> Lessons from the TREC Plain Language Adaptation of Biomedical Abstracts (PLABA) track

# 摘要

> # 目标
近期语言模型的突破性进展为将专业生物医学文献转化为PLAIN语言带来了希望，使患者和护理人员能够轻松理解。然而，鉴于其不可预测性以及该领域的高风险特性，严格的评估至关重要。本次竞赛旨在推动相关研究，并为最具潜力的系统提供高质量的评估。

# 方法
我们在2023和2024年的文本检索会议上举办了生物医学摘要PLAIN语言转化（PLABA）竞赛。竞赛包含两项任务：对摘要进行完整的、句子级别的重写（任务1）以及识别和替换困难术语（任务2）。为自动评估任务1，我们开发了一套由专业人士撰写的四组参考文本。两项任务的提交作品都接受了来自生物医学专家的详细人工评估。

# 结果
共有来自12个国家的12支队伍参赛，使用的模型从多层感知机到大型预训练变换器模型不等。在任务1的人工评判中，顶尖模型在事实准确性和完整性上几乎与人类水平相当，但在简洁性和简短性上仍有差距。基于参考的自动评测指标通常与人工评判的相关性不高。在任务2中，系统在识别困难术语和分类如何替换它们方面表现挣扎。然而，在生成替换词时，基于大型语言模型的系统在人工评判的准确性、完整性和简洁性方面表现良好，尽管在简短性上仍有不足。

# 结论
PLABA竞赛展示了使用大型语言模型将生物医学文献转化为PLAIN语言的潜力，同时也凸显了其不足，并强调了开发更完善的自动评测工具的必要性。


> Objective: Recent advances in language models have shown potential to adapt professional-facing biomedical literature to plain language, making it accessible to patients and caregivers. However, their unpredictability, combined with the high potential for harm in this domain, means rigorous evaluation is necessary. Our goals with this track were to stimulate research and to provide high-quality evaluation of the most promising systems.
  Methods: We hosted the Plain Language Adaptation of Biomedical Abstracts (PLABA) track at the 2023 and 2024 Text Retrieval Conferences. Tasks included complete, sentence-level, rewriting of abstracts (Task 1) as well as identifying and replacing difficult terms (Task 2). For automatic evaluation of Task 1, we developed a four-fold set of professionally-written references. Submissions for both Tasks 1 and 2 were provided extensive manual evaluation from biomedical experts.
  Results: Twelve teams spanning twelve countries participated in the track, with models from multilayer perceptrons to large pretrained transformers. In manual judgments of Task 1, top-performing models rivaled human levels of factual accuracy and completeness, but not simplicity or brevity. Automatic, reference-based metrics generally did not correlate well with manual judgments. In Task 2, systems struggled with identifying difficult terms and classifying how to replace them. When generating replacements, however, LLM-based systems did well in manually judged accuracy, completeness, and simplicity, though not in brevity.
  Conclusion: The PLABA track showed promise for using Large Language Models to adapt biomedical literature for the general public, while also highlighting their deficiencies and the need for improved automatic benchmarking tools.

[Arxiv](https://arxiv.org/abs/2507.14096)