# 多一轮，输出会更好吗？迭代式LLM提示的逐轮分析

发布时间：2025年09月08日

`LLM应用` `基础理论`

> Another Turn, Better Output? A Turn-Wise Analysis of Iterative LLM Prompting

# 摘要

> 大型语言模型（LLMs）已广泛应用于多轮工作流，但我们仍缺乏清晰方法来判断迭代何时助力、何时添乱。为此，我们提出了一个覆盖构思、代码与数学领域的迭代优化评估框架。该框架的协议会为每个任务开展12轮受控对话，采用从模糊的“改进一下”反馈到精准引导的多样化提示，并记录每轮输出结果。我们通过领域适配的检查方式对结果评分（代码用单元测试；数学看答案等价性与推理严谨性；构思则评估原创性与可行性），同时用三类指标追踪轮次级行为：跨轮语义偏移、轮次间变化幅度及输出规模增长。不同模型与任务的收益呈现领域差异性：构思和代码领域的收益见效快，而数学领域在详细阐述的引导下，后期轮次作用更大。前几轮过后，模糊反馈常导致性能停滞甚至正确性倒退，而精准提示则能稳定调控预期质量维度（构思侧重新颖性与可行性；代码关注速度与可读性；数学领域中，详细阐述比探索更有效，且能带动后期轮次的收益）。我们还发现了一致的领域规律：构思的跨轮语义变化更显著；代码常出现篇幅增加但语义变动甚微的情况；数学初期表现固定，但后期通过精细化迭代可突破原有路径。总之，这套框架与指标让迭代效果在不同模型间具备可衡量性与可比性，并能提示何时该引导、何时该停止或切换策略。

> Large language models (LLMs) are now used in multi-turn workflows, but we still lack a clear way to measure when iteration helps and when it hurts. We present an evaluation framework for iterative refinement that spans ideation, code, and math. Our protocol runs controlled 12-turn conversations per task, utilizing a variety of prompts ranging from vague ``improve it'' feedback to targeted steering, and logs per-turn outputs. We score outcomes with domain-appropriate checks (unit tests for code; answer-equivalence plus reasoning-soundness for math; originality and feasibility for ideation) and track turn-level behavior with three families of metrics: semantic movement across turns, turn-to-turn change, and output size growth. Across models and tasks, gains are domain-dependent: they arrive early in ideas and code, but in math late turns matter when guided by elaboration. After the first few turns, vague feedback often plateaus or reverses correctness, while targeted prompts reliably shift the intended quality axis (novelty vs. feasibility in ideation; speed vs. readability in code; in math, elaboration outperforms exploration and drives late-turn gains). We also observe consistent domain patterns: ideation moves more in meaning across turns, code tends to grow in size with little semantic change, and math starts fixed but can break that path with late, elaborative iteration.Together, the framework and metrics make iteration measurable and comparable across models, and signal when to steer, stop, or switch strategies.

[Arxiv](https://arxiv.org/abs/2509.06770)