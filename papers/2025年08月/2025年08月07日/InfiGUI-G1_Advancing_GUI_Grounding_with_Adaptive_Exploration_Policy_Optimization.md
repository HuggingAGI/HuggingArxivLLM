# InfiGUI-G1: 基于自适应探索策略优化提升 GUI 锚定能力

发布时间：2025年08月07日

`LLM应用` `人工智能` `人机交互`

> InfiGUI-G1: Advancing GUI Grounding with Adaptive Exploration Policy Optimization

# 摘要

> 多模态大型语言模型（MLLMs）的出现推动了基于纯视觉输入的图形用户界面（GUIs）自主代理的发展。一个核心挑战是实现稳健的自然语言指令与界面元素的对齐，这需要精确的空间对齐（准确定位每个元素的坐标）和正确的语义对齐（将指令与合适的UI功能匹配）。虽然可验证奖励的强化学习（RLVR）在提升MLLMs的空间对齐方面表现出色，但我们发现，低效的探索瓶颈严重制约了语义对齐，阻碍了模型学习复杂的语义关联。为解决这一探索难题，我们提出了自适应探索策略优化（AEPO），一种全新的策略优化框架。AEPO采用多答案生成策略拓宽探索范围，并通过基于效率原理eta=U/C的自适应探索奖励（AER）函数进行引导。我们的InfiGUI-G1-3B和InfiGUI-G1-7B模型在多个具有挑战性的GUI对齐基准测试中取得了突破性成果，在测试泛化和语义理解的基准上，较基础RLVR实现了高达9.0%的显著提升。更多资源请访问https://github.com/InfiXAI/InfiGUI-G1。

> The emergence of Multimodal Large Language Models (MLLMs) has propelled the development of autonomous agents that operate on Graphical User Interfaces (GUIs) using pure visual input. A fundamental challenge is robustly grounding natural language instructions. This requires a precise spatial alignment, which accurately locates the coordinates of each element, and, more critically, a correct semantic alignment, which matches the instructions to the functionally appropriate UI element. Although Reinforcement Learning with Verifiable Rewards (RLVR) has proven to be effective at improving spatial alignment for these MLLMs, we find that inefficient exploration bottlenecks semantic alignment, which prevent models from learning difficult semantic associations. To address this exploration problem, we present Adaptive Exploration Policy Optimization (AEPO), a new policy optimization framework. AEPO employs a multi-answer generation strategy to enforce broader exploration, which is then guided by a theoretically grounded Adaptive Exploration Reward (AER) function derived from first principles of efficiency eta=U/C. Our AEPO-trained models, InfiGUI-G1-3B and InfiGUI-G1-7B, establish new state-of-the-art results across multiple challenging GUI grounding benchmarks, achieving significant relative improvements of up to 9.0% against the naive RLVR baseline on benchmarks designed to test generalization and semantic understanding. Resources are available at https://github.com/InfiXAI/InfiGUI-G1.

[Arxiv](https://arxiv.org/abs/2508.05731)