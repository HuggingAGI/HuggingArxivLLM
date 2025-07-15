# PBIG竞赛中的MK2：打造高效提示生成解决方案

发布时间：2025年07月11日

`LLM应用` `产品开发` `材料化学`

> MK2 at PBIG Competition: A Prompt Generation Solution

# 摘要

> 基于专利的创意生成任务要求系统将真实专利转化为三年内可行的产品创意。我们提出 MK2，一个提示词驱动的管道：Gemini 2.5 起草并迭代优化提示词，从较弱的输出中提取有用片段；GPT-4.1 则利用该提示词为每个专利生成创意，最后由 Qwen3-8B 判决的 Elo 循环筛选出最佳提示词——整个流程无需额外训练数据。跨三个领域、两种评估者类型和六个标准测试，MK2 在自动排行榜上表现优异，并在 36 项测试中胜出 25 项。尽管材料-化学领域表现稍逊，表明需要更深入的领域知识，但整体结果证明，轻量级提示词工程已能从专利中生成具有竞争力且商业价值显著的创意。

> The Patent-Based Idea Generation task asks systems to turn real patents into product ideas viable within three years. We propose MK2, a prompt-centric pipeline: Gemini 2.5 drafts and iteratively edits a prompt, grafting useful fragments from weaker outputs; GPT-4.1 then uses this prompt to create one idea per patent, and an Elo loop judged by Qwen3-8B selects the best prompt-all without extra training data. Across three domains, two evaluator types, and six criteria, MK2 topped the automatic leaderboard and won 25 of 36 tests. Only the materials-chemistry track lagged, indicating the need for deeper domain grounding; yet, the results show that lightweight prompt engineering has already delivered competitive, commercially relevant ideation from patents.

[Arxiv](https://arxiv.org/abs/2507.08335)