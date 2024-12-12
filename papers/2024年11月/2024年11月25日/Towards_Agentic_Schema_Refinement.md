# 走向智能体模式的精细化

发布时间：2024年11月25日

`Agent` `数据库`

> Towards Agentic Schema Refinement

# 摘要

> 大型企业数据库往往复杂又混乱，致使分析任务所需的数据语义被掩盖。我们提议在数据库与用户之间构建一个语义层，它由一组小巧且易于解读的数据库视图组成，实际上就是模式的优化版。为了找出这些视图，我们引入了一种多智能体大型语言模型（LLM）模拟，在其中，LLM 智能体相互协作，以最少的输入来反复定义和优化视图。我们的方法为借助 LLM 探索难以驾驭的数据库开辟了道路。

> Large enterprise databases can be complex and messy, obscuring the data semantics needed for analytical tasks. We propose a semantic layer in-between the database and the user as a set of small and easy-to-interpret database views, effectively acting as a refined version of the schema. To discover these views, we introduce a multi-agent Large Language Model (LLM) simulation where LLM agents collaborate to iteratively define and refine views with minimal input. Our approach paves the way for LLM-powered exploration of unwieldy databases.

[Arxiv](https://arxiv.org/abs/2412.07786)