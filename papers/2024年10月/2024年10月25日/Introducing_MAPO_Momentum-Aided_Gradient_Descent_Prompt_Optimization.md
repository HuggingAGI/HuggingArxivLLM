# 为您介绍 MAPO：动量辅助的梯度下降提示优化

发布时间：2024年10月25日

`LLM应用` `语言模型` `自动提示工程`

> Introducing MAPO: Momentum-Aided Gradient Descent Prompt Optimization

# 摘要

> 动量辅助提示优化（MAPO）提升了大型语言模型（LLMs）提示优化的效率与效果。MAPO 以 ProTeGi 为基础，运用积极的自然语言“梯度”和基于动量的扩展，有效优化提示。通过追踪梯度历史，MAPO 规避了局部最小值和振荡。它还借助波束搜索和上置信界（UCB）算法，实现候选的均衡扩展与选择。基准测试显示，相较于 ProTeGi，MAPO 以更少的 API 调用实现了更快的收敛时间和更高的 F1 分数，证明其是 LLMs 中自动提示工程的强大且可扩展的解决方案。

> Momentum-Aided Prompt Optimization (MAPO) enhances the efficiency and efficacy of prompt optimization for Large Language Models (LLMs). Building on ProTeGi, MAPO uses positive natural language "gradients" and a momentum-based extension to refine prompts effectively. By tracking gradient history, MAPO avoids local minima and oscillations. It also utilizes beam search and an Upper Confidence Bound (UCB) algorithm for balanced candidate expansion and selection. Benchmark testing shows that MAPO achieves faster convergence time with fewer API calls and higher F1 scores than ProTeGi, proving it as a robust and scalable solution for automated prompt engineering in LLMs.

[Arxiv](https://arxiv.org/abs/2410.19499)