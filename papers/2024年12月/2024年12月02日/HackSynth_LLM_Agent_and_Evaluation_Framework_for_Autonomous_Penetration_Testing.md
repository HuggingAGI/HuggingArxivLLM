# HackSynth：自主渗透测试的 LLM 代理及评估框架

发布时间：2024年12月02日

`Agent` `网络安全` `渗透测试`

> HackSynth: LLM Agent and Evaluation Framework for Autonomous Penetration Testing

# 摘要

> 我们推出了 HackSynth，这是一款新颖的基于大型语言模型（LLM）、能够自主开展渗透测试的代理。HackSynth 的双模块架构涵盖了规划器和总结器，使其能够迭代生成命令并处理反馈。为给 HackSynth 设定基准测试，我们借助热门平台 PicoCTF 和 OverTheWire 提出了两个新的基于夺旗（CTF）的基准测试集。这些测试集包含了横跨不同领域和难度的两百个挑战，为评估基于 LLM 的渗透测试代理提供了标准化框架。基于这些基准测试，开展了广泛的实验，对 HackSynth 的核心参数进行了分析，包括创造力（温度和 top-p）以及令牌利用率。运用了多个开源和专有 LLM 来衡量该代理的能力。实验显示，该代理在 GPT-4o 模型上表现最为出色，优于 GPT-4o 系统卡所呈现的效果。我们还探讨了 HackSynth 行动的安全性和可预测性。我们的研究结果表明，基于 LLM 的代理在推动自主渗透测试方面具有潜力，同时也凸显了强大保障措施的重要性。HackSynth 及基准测试均可公开获取，以助力自主网络安全解决方案的研究。

> We introduce HackSynth, a novel Large Language Model (LLM)-based agent capable of autonomous penetration testing. HackSynth's dual-module architecture includes a Planner and a Summarizer, which enable it to generate commands and process feedback iteratively. To benchmark HackSynth, we propose two new Capture The Flag (CTF)-based benchmark sets utilizing the popular platforms PicoCTF and OverTheWire. These benchmarks include two hundred challenges across diverse domains and difficulties, providing a standardized framework for evaluating LLM-based penetration testing agents. Based on these benchmarks, extensive experiments are presented, analyzing the core parameters of HackSynth, including creativity (temperature and top-p) and token utilization. Multiple open source and proprietary LLMs were used to measure the agent's capabilities. The experiments show that the agent performed best with the GPT-4o model, better than what the GPT-4o's system card suggests. We also discuss the safety and predictability of HackSynth's actions. Our findings indicate the potential of LLM-based agents in advancing autonomous penetration testing and the importance of robust safeguards. HackSynth and the benchmarks are publicly available to foster research on autonomous cybersecurity solutions.

[Arxiv](https://arxiv.org/abs/2412.01778)