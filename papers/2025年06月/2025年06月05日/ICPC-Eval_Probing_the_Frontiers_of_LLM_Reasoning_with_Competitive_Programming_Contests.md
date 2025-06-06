# ICPC-Eval：用竞赛编程探索LLM推理边界

发布时间：2025年06月05日

`LLM应用` `编程竞赛` `代码生成`

> ICPC-Eval: Probing the Frontiers of LLM Reasoning with Competitive Programming Contests

# 摘要

> 随着大型推理模型在复杂编码和推理任务中的重大进展，现有基准测试如LiveCodeBench和CodeElo已无法满足评估大型语言模型（LLMs）在真实竞赛环境中的需求。此外，现有指标如Pass@K未能充分反映推理模型的反思能力。为解决这些问题，我们推出了	extbf{ICPC-Eval}，这是一个专注于探索LLM推理能力的顶级竞赛编码基准。ICPC-Eval精选了来自全球11个地区举办的11场 recent ICPC竞赛中的118个问题，带来三大创新：1）构建了一个高度还原的ICPC竞赛场景，问题类型与难度分布均与真实竞赛一致。2）开发了一套强大的测试用例生成方法和本地评估工具包，实现高效精准的本地评估。3）提出了创新的测试时间缩放评估指标Refine@K，支持基于执行反馈的迭代修复机制。实验结果表明，评估复杂推理能力仍具重大挑战：以DeepSeek-R1为代表的顶级推理模型，需通过多轮代码反馈才能充分释放其上下文推理潜力。此外，尽管代码生成技术 recent 取得突破，但这些模型仍难与顶尖人类团队匹敌。本基准测试已开源：https://github.com/RUCAIBox/Slow_Thinking_with_LLMs

> With the significant progress of large reasoning models in complex coding and reasoning tasks, existing benchmarks, like LiveCodeBench and CodeElo, are insufficient to evaluate the coding capabilities of large language models (LLMs) in real competition environments. Moreover, current evaluation metrics such as Pass@K fail to capture the reflective abilities of reasoning models. To address these challenges, we propose \textbf{ICPC-Eval}, a top-level competitive coding benchmark designed to probing the frontiers of LLM reasoning. ICPC-Eval includes 118 carefully curated problems from 11 recent ICPC contests held in various regions of the world, offering three key contributions: 1) A challenging realistic ICPC competition scenario, featuring a problem type and difficulty distribution consistent with actual contests. 2) A robust test case generation method and a corresponding local evaluation toolkit, enabling efficient and accurate local evaluation. 3) An effective test-time scaling evaluation metric, Refine@K, which allows iterative repair of solutions based on execution feedback. The results underscore the significant challenge in evaluating complex reasoning abilities: top-tier reasoning models like DeepSeek-R1 often rely on multi-turn code feedback to fully unlock their in-context reasoning potential when compared to non-reasoning counterparts. Furthermore, despite recent advancements in code generation, these models still lag behind top-performing human teams. We release the benchmark at: https://github.com/RUCAIBox/Slow_Thinking_with_LLMs

[Arxiv](https://arxiv.org/abs/2506.04894)