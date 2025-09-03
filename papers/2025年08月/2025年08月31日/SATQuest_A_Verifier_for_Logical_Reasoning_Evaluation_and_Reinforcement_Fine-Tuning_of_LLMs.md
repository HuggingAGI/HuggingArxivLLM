# <翻译失败>

发布时间：2025年08月31日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> SATQuest: A Verifier for Logical Reasoning Evaluation and Reinforcement Fine-Tuning of LLMs

# 摘要

> <翻译失败>

> Recent advances in Large Language Models (LLMs) have demonstrated remarkable general reasoning capabilities. However, systematically evaluating and enhancing these reasoning capabilities is challenging due to the lack of controllable and scalable tools for fine-grained analysis. Existing benchmarks and datasets often lack the necessary variable control for multi-dimensional, systematic analysis and training, or have narrow problem types and formats. To address these limitations, we introduce SATQuest, a systematic verifier designed to evaluate and enhance logical reasoning in LLMs by generating diverse, Satisfiability-based logical reasoning problems directly from Conjunctive Normal Form (CNF) instances. SATQuest structures these problems along three orthogonal dimensions: instance scale, problem type, and question format, employing randomized, SAT-based problem generation and objective answer verification via PySAT. This design mitigates memorization issues, allows for nuanced insights into reasoning performance, and enables effective reinforcement fine-tuning. Our extensive evaluation of various LLMs using SATQuest identified significant limitations in their logical reasoning, particularly in generalizing beyond familiar mathematical formats. Furthermore, we show that reinforcement fine-tuning with SATQuest rewards substantially improves targeted task performance and generalizes to more complex instances, while highlighting remaining challenges in cross-format adaptation. Through these demonstrations, we showcase SATQuest's potential as a foundational tool and a valuable starting point for advancing LLM logical reasoning.

[Arxiv](https://arxiv.org/abs/2509.00930)