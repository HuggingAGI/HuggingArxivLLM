# LMGame-Bench：大型语言模型玩游戏的能力如何？

发布时间：2025年05月21日

`LLM应用` `游戏测试` `模型评估`

> lmgame-Bench: How Good are LLMs at Playing Games?

# 摘要

> 玩视频游戏需要感知、记忆和规划能力，这正是现代大型语言模型（LLM）代理所期望掌握的技能。我们研究了使用流行视频游戏来评估现代LLM的主要挑战，并发现直接将LLM放入游戏中无法进行有效的评估，原因有三--脆性视觉感知、提示敏感性和潜在数据污染。我们引入了lmgame-Bench，将游戏转变为可靠的评估工具。lmgame-Bench通过统一的Gym风格API提供了一系列平台、解谜和叙事类游戏，并配备了轻量级的感知和记忆框架，旨在稳定提示变化并消除污染。在13个领先的模型中，我们展示了lmgame-Bench具有挑战性，同时仍能有效区分模型。相关性分析表明，每款游戏都测试了一种独特的能力组合，这些能力通常在其他地方单独测试。更有趣的是，在lmgame-Bench的单个游戏中进行强化学习，可以迁移到未见过的游戏和外部规划任务中。我们的评估代码可在https://github.com/lmgame-org/GamingAgent/lmgame-bench获取。

> Playing video games requires perception, memory, and planning, exactly the faculties modern large language model (LLM) agents are expected to master. We study the major challenges in using popular video games to evaluate modern LLMs and find that directly dropping LLMs into games cannot make an effective evaluation, for three reasons -- brittle vision perception, prompt sensitivity, and potential data contamination. We introduce lmgame-Bench to turn games into reliable evaluations. lmgame-Bench features a suite of platformer, puzzle, and narrative games delivered through a unified Gym-style API and paired with lightweight perception and memory scaffolds, and is designed to stabilize prompt variance and remove contamination. Across 13 leading models, we show lmgame-Bench is challenging while still separating models well. Correlation analysis shows that every game probes a unique blend of capabilities often tested in isolation elsewhere. More interestingly, performing reinforcement learning on a single game from lmgame-Bench transfers both to unseen games and to external planning tasks. Our evaluation code is available at https://github.com/lmgame-org/GamingAgent/lmgame-bench.

[Arxiv](https://arxiv.org/abs/2505.15146)