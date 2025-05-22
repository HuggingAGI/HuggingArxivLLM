# 思考、反思、创造：探索基于大语言模型的零样本机器人规划元认知学习方法

发布时间：2025年05月20日

`LLM应用` `机器人` `多机器人协作`

> Think, Reflect, Create: Metacognitive Learning for Zero-Shot Robotic Planning with LLMs

# 摘要

> 尽管大型语言模型（LLMs）在多个领域展现出巨大潜力，但其在机器人领域的应用仍主要局限于静态、基于提示的行为，且在零样本或少样本设置下处理复杂任务时仍面临挑战。受人类元认知学习和创造性问题解决的启发，我们通过探索一个基本研究问题来解决这一局限性：能否赋予LLMs元认知能力，使其能够推理、反思和创造，从而在仅有少量演示的情况下提升其执行机器人任务的能力？

本文提出了一种将元认知学习整合到LLM驱动的多机器人协作中的早期框架。该框架为LLM驱动的机器人代理配备了技能分解和自我反思机制，能够从先前任务中识别模块化技能，在未见任务场景中反思失败，并合成有效的新解决方案。实验结果表明，我们的元认知学习增强型LLM框架显著优于现有基线。此外，我们观察到该框架能够生成与真实解不同的解决方案，但仍能成功完成任务。这些令人兴奋的发现支持了我们的假设，即元认知学习能够促进机器人规划中的创造力。

> While large language models (LLMs) have shown great potential across various domains, their applications in robotics remain largely limited to static, prompt-based behaviors and still face challenges in handling complex tasks under zero-shot or few-shot settings. Inspired by human metacognitive learning and creative problem-solving, we address this limitation by exploring a fundamental research question: Can LLMs be empowered with metacognitive capabilities to reason, reflect, and create, thereby enhancing their ability to perform robotic tasks with minimal demonstrations? In this paper, we present an early-stage framework that integrates metacognitive learning into LLM-powered multi-robot collaboration. The proposed framework equips the LLM-powered robotic agents with a skill decomposition and self-reflection mechanism that identifies modular skills from prior tasks, reflects on failures in unseen task scenarios, and synthesizes effective new solutions. Experimental results show that our metacognitive-learning-empowered LLM framework significantly outperforms existing baselines. Moreover, we observe that the framework is capable of generating solutions that differ from the ground truth yet still successfully complete the tasks. These exciting findings support our hypothesis that metacognitive learning can foster creativity in robotic planning.

[Arxiv](https://arxiv.org/abs/2505.14899)