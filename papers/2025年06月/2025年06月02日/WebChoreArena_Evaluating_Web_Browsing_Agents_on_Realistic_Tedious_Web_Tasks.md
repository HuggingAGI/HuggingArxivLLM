# WebChoreArena：评估网络浏览代理在真实繁琐的网页任务中的性能

发布时间：2025年06月02日

`LLM应用` `网络浏览` `自动化任务`

> WebChoreArena: Evaluating Web Browsing Agents on Realistic Tedious Web Tasks

# 摘要

> 借助大型语言模型（LLM）的力量，网络浏览代理能够以人类般的方式操作网络浏览器，为自动化各种日常任务提供了高度透明的路径。随着网络代理能力的不断提升，它们在通用浏览任务中表现出色。一个关键问题随之浮现：它们是否能够超越通用浏览， robustly 处理那些繁琐复杂、人类往往不愿亲力亲为的任务？

在本文中，我们介绍了 WebChoreArena，一个全新的完全可复现的基准测试，包含 532 个精心策划的任务，旨在将 WebArena 的范围从通用浏览扩展到更 labor-intensive 和繁琐的任务。WebChoreArena 系统性地整合了三大核心挑战：(i) 大规模记忆任务，需要在观察中准确检索大量信息；(ii) 计算任务，需要精准的数学推理；(iii) 长期记忆任务，需要跨多个网页的长期记忆。

基于四个广泛采用且完全可复现的 WebArena 模拟环境构建，WebChoreArena 确保了严格的可复现性，并支持与 established WebArena 基准进行公平直接的比较，为代理进展提供了关键见解。我们的实验结果表明，随着 LLM 的发展，以 GPT-4o、Claude 3.7 Sonnet 和 Gemini 2.5 Pro 为代表，WebChoreArena 上的性能有了显著提升。这些发现表明，WebChoreArena 是衡量 state-of-the-art LLMs 进展的理想工具，具有更高的清晰度。然而，结果也显示，即使使用 Gemini 2.5 Pro，与 WebArena 相比仍有显著改进空间，突显了 WebChoreArena 增加的挑战性。

> Powered by a large language model (LLM), a web browsing agent operates web browsers in a human-like manner and offers a highly transparent path toward automating a wide range of everyday tasks. As web agents become increasingly capable and demonstrate proficiency in general browsing tasks, a critical question emerges: Can they go beyond general browsing to robustly handle tasks that are tedious and complex, or chores that humans often avoid doing themselves? In this paper, we introduce WebChoreArena, a new fully reproducible benchmark comprising 532 carefully curated tasks designed to extend the scope of WebArena beyond general browsing to more labor-intensive and tedious tasks. WebChoreArena systematically integrates three key challenges: (i) Massive Memory tasks requiring accurate retrieval of large amounts of information in the observations, (ii) Calculation tasks demanding precise mathematical reasoning, and (iii) Long-Term Memory tasks necessitating long-term memory across multiple webpages. Built on top of the fully reproducible and widely adopted four WebArena simulation environments, WebChoreArena ensures strict reproducibility and enables fair, direct comparisons with the established WebArena benchmark, offering key insights into agent progress. Our experimental results demonstrate that as LLMs evolve, represented by GPT-4o, Claude 3.7 Sonnet, and Gemini 2.5 Pro, significant improvements in performance are observed on WebChoreArena. These findings suggest that WebChoreArena is well-suited to measure the advancement of state-of-the-art LLMs with greater clarity. Nevertheless, the results also indicate that even with Gemini 2.5 Pro, there remains substantial room for improvement compared to WebArena, highlighting the increased challenges posed by WebChoreArena.

[Arxiv](https://arxiv.org/abs/2506.01952)