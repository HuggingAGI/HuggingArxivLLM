# # 人类最后的代码考试：大语言模型能否攻克人类最难编程竞赛？

发布时间：2025年06月15日

`LLM应用` `软件工程` `代码生成`

> Humanity's Last Code Exam: Can Advanced LLMs Conquer Human's Hardest Code Competition?

# 摘要

> 代码生成是大型语言模型 (LLMs) 的核心能力，但现有主流基准测试（如 APPs 和 LiveCodeBench）中的问题难度中等，无法对先进 LLMs 构成挑战。为此，我们推出了“人类最后的代码考试” (HLCE)，从 2010 年至 2024 年的国际大学生程序设计竞赛 (ICPC 世界总决赛) 和国际信息学奥林匹克 (IOI) 中精选了 235 道最具挑战性的题目。作为 HLCE 的一部分，我们设计了一个线上线下一体化的沙盒环境，确保评估过程可完全复现。通过全面评估，我们发现即使是最强的推理型 LLMs：o4-mini(high) 和 Gemini-2.5 Pro，其 pass@1 通过率也只有 15.9% 和 11.4%。同时，我们提出了一种新型“自我认知”任务，用于衡量 LLMs 对自身能力的意识。结果显示，LLMs 的自我认知能力与其代码生成性能之间并无显著关联。最后，我们对测试时的缩放定律进行了实证验证，发现当前先进 LLMs 在复杂编程任务上仍有巨大的提升空间。我们期望 HLCE 能成为代码生成领域的重要里程碑挑战，并推动高性能推理和人机协作编程的发展。我们的代码和数据集已公开可用（https://github.com/Humanity-s-Last-Code-Exam/HLCE）。

> Code generation is a core capability of large language models (LLMs), yet mainstream benchmarks (e.g., APPs and LiveCodeBench) contain questions with medium-level difficulty and pose no challenge to advanced LLMs. To better reflected the advanced reasoning and code generation ability, We introduce Humanity's Last Code Exam (HLCE), comprising 235 most challenging problems from the International Collegiate Programming Contest (ICPC World Finals) and the International Olympiad in Informatics (IOI) spanning 2010 - 2024. As part of HLCE, we design a harmonized online-offline sandbox that guarantees fully reproducible evaluation. Through our comprehensive evaluation, we observe that even the strongest reasoning LLMs: o4-mini(high) and Gemini-2.5 Pro, achieve pass@1 rates of only 15.9% and 11.4%, respectively. Meanwhile, we propose a novel "self-recognition" task to measure LLMs' awareness of their own capabilities. Results indicate that LLMs' self-recognition abilities are not proportionally correlated with their code generation performance. Finally, our empirical validation of test-time scaling laws reveals that current advanced LLMs have substantial room for improvement on complex programming tasks. We expect HLCE to become a milestone challenge for code generation and to catalyze advances in high-performance reasoning and human-AI collaborative programming. Our code and dataset are also public available(https://github.com/Humanity-s-Last-Code-Exam/HLCE).

[Arxiv](https://arxiv.org/abs/2506.12713)