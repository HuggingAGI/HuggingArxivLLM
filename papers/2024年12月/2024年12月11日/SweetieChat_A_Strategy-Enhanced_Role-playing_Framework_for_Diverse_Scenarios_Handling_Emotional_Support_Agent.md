# SweetieChat：一个用于应对多样场景中情感支持代理的策略增强型角色扮演框架

发布时间：2024年12月11日

`LLM应用` `情感支持` `对话系统`

> SweetieChat: A Strategy-Enhanced Role-playing Framework for Diverse Scenarios Handling Emotional Support Agent

# 摘要

> 大型语言模型（LLMs）在互动时提供共情支持方面显示出了良好的潜力。但它们的回应常常冗长或过于套路，难以充分满足现实场景中多样的情感支持需求。为解决此难题，我们提出了一个创新的策略增强型角色扮演框架，用于模拟真实的情感支持对话。具体来说，我们的方法分两步走：（1）策略增强型角色扮演互动，包含三个关键角色——寻求者、策略顾问和支持者，在不同场景中参与，以模拟真实世界的互动，推动更广泛的对话；（2）情感支持代理训练，利用我们专门构建的数据集对LLMs进行微调来达成。在这个框架中，我们开发了	extbf{ServeForEmo}数据集，涵盖了大量的3.7K+多轮对话和62.8K+话语。我们还推出了	extbf{SweetieChat}，这是一个能够应对各种开放领域场景的情感支持代理。大量的实验和人类评估证明了该框架在增强情感支持方面的有效性，凸显了其提供更精细和定制化协助的独特能力。

> Large Language Models (LLMs) have demonstrated promising potential in providing empathetic support during interactions. However, their responses often become verbose or overly formulaic, failing to adequately address the diverse emotional support needs of real-world scenarios. To tackle this challenge, we propose an innovative strategy-enhanced role-playing framework, designed to simulate authentic emotional support conversations. Specifically, our approach unfolds in two steps: (1) Strategy-Enhanced Role-Playing Interactions, which involve three pivotal roles -- Seeker, Strategy Counselor, and Supporter -- engaging in diverse scenarios to emulate real-world interactions and promote a broader range of dialogues; and (2) Emotional Support Agent Training, achieved through fine-tuning LLMs using our specially constructed dataset. Within this framework, we develop the \textbf{ServeForEmo} dataset, comprising an extensive collection of 3.7K+ multi-turn dialogues and 62.8K+ utterances. We further present \textbf{SweetieChat}, an emotional support agent capable of handling diverse open-domain scenarios. Extensive experiments and human evaluations confirm the framework's effectiveness in enhancing emotional support, highlighting its unique ability to provide more nuanced and tailored assistance.

[Arxiv](https://arxiv.org/abs/2412.08389)