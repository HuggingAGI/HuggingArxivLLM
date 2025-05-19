# Vaiage：一个多智能体的个性化旅行规划解决方案

发布时间：2025年05月16日

`Agent` `行程规划`

> Vaiage: A Multi-Agent Solution to Personalized Travel Planning

# 摘要

> 旅行规划是一项复杂任务，涉及用户偏好、外部信息和多维度优化。传统平台往往力不从心，难以提供动态、个性化的解决方案。
    我们的 Vaiage 系统采用基于 LLM 的多智能体框架，通过自然语言交互和情境感知，实现智能行程规划。系统平均得分 8.5 分，显著优于传统方法，尤其在行程可行性和智能化方面表现突出。这证明了 LLM 与多智能体协调的结合在现实场景中的巨大潜力。
    

> Planning trips is a cognitively intensive task involving conflicting user preferences, dynamic external information, and multi-step temporal-spatial optimization. Traditional platforms often fall short - they provide static results, lack contextual adaptation, and fail to support real-time interaction or intent refinement.
  Our approach, Vaiage, addresses these challenges through a graph-structured multi-agent framework built around large language models (LLMs) that serve as both goal-conditioned recommenders and sequential planners. LLMs infer user intent, suggest personalized destinations and activities, and synthesize itineraries that align with contextual constraints such as budget, timing, group size, and weather. Through natural language interaction, structured tool use, and map-based feedback loops, Vaiage enables adaptive, explainable, and end-to-end travel planning grounded in both symbolic reasoning and conversational understanding.
  To evaluate Vaiage, we conducted human-in-the-loop experiments using rubric-based GPT-4 assessments and qualitative feedback. The full system achieved an average score of 8.5 out of 10, outperforming the no-strategy (7.2) and no-external-API (6.8) variants, particularly in feasibility. Qualitative analysis indicated that agent coordination - especially the Strategy and Information Agents - significantly improved itinerary quality by optimizing time use and integrating real-time context. These results demonstrate the effectiveness of combining LLM reasoning with symbolic agent coordination in open-ended, real-world planning tasks.

[Arxiv](https://arxiv.org/abs/2505.10922)