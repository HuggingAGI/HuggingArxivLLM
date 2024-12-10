# GameArena：借由实时电脑游戏评估 LLM 的推理水平

发布时间：2024年12月09日

`LLM应用` `语言模型` `推理能力评估`

> GameArena: Evaluating LLM Reasoning through Live Computer Games

# 摘要

> 评估大型语言模型（LLMs）的推理能力颇具挑战。现有的基准要么依赖易受数据污染且可能随时间饱和的静态数据集，要么依赖将推理与其他能力混淆的二元实时人类反馈。作为最为突出的动态基准，Chatbot Arena 虽能在现实场景中评估开放式问题，却在评估特定推理能力时缺乏精细度。我们推出了 GameArena 这一动态基准，旨在通过与人类的互动游戏来测评 LLM 的推理能力。GameArena 包含三款专为测试特定推理能力（如演绎推理和归纳推理）而设计的游戏，同时能让参与者乐在其中并积极参与。我们对游戏数据进行回溯分析，以揭示 LLMs 的潜在推理过程，并衡量其细粒度推理能力。我们收集了 2000 多个游戏会话，并针对五个先进的 LLMs 给出了各种推理能力的详尽评估。我们对 100 名参与者开展的用户研究表明，与 Chatbot Arena 相比，GameArena 提升了用户的参与度。GameArena 首次能够在实际环境中收集逐步的 LLM 推理数据。

> Evaluating the reasoning abilities of large language models (LLMs) is challenging. Existing benchmarks often depend on static datasets, which are vulnerable to data contamination and may get saturated over time, or on binary live human feedback that conflates reasoning with other abilities. As the most prominent dynamic benchmark, Chatbot Arena evaluates open-ended questions in real-world settings, but lacks the granularity in assessing specific reasoning capabilities. We introduce GameArena, a dynamic benchmark designed to evaluate LLM reasoning capabilities through interactive gameplay with humans. GameArena consists of three games designed to test specific reasoning capabilities (e.g., deductive and inductive reasoning), while keeping participants entertained and engaged. We analyze the gaming data retrospectively to uncover the underlying reasoning processes of LLMs and measure their fine-grained reasoning capabilities. We collect over 2000 game sessions and provide detailed assessments of various reasoning capabilities for five state-of-the-art LLMs. Our user study with 100 participants suggests that GameArena improves user engagement compared to Chatbot Arena. For the first time, GameArena enables the collection of step-by-step LLM reasoning data in the wild.

[Arxiv](https://arxiv.org/abs/2412.06394)