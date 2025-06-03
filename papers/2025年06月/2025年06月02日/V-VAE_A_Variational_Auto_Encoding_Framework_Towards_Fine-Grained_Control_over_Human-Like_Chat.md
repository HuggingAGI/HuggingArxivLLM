# V-VAE: 一个实现对类人对话精细控制的变分自编码框架。

发布时间：2025年06月02日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型应用于更智能、更一致的角色扮演对话系统中，提出了一种新的框架V-VAE，并进行了实验验证，展示了其在实际应用中的有效性。因此，它属于LLM应用类别。` `对话系统`

> V-VAE: A Variational Auto Encoding Framework Towards Fine-Grained Control over Human-Like Chat

# 摘要

> 随着基于大型语言模型（LLM）的聊天机器人日益普及，人们不仅希望生成语言流畅的响应，还希望这些响应能在对话中始终与特定角色特征保持一致。然而，现有的角色扮演和基于角色的聊天方法存在以下问题：依赖静态角色描述、粗粒度信号空间以及低质量的合成数据，这些方法难以捕捉类人对话中动态的细粒度细节。类人对话需要建模微妙的潜在特征，例如情感基调、情境意识和不断演变的性格，这些特征难以预先定义，也无法轻易从合成数据或蒸馏数据中学习。为了解决这些问题，我们提出了一种名为Verbal Variational Auto-Encoding（V-VAE）的框架。该框架包含一个变分自动编码模块和一个细粒度控制空间，能够根据跨谈话风格、交互模式和个人属性的细粒度、可解释的潜在变量动态调整对话行为。我们还构建了一个高质量的数据集HumanChatData，并创建了基准测试HumanChatBench，以解决类人领域高质量数据稀缺的问题。实验表明，基于V-VAE的LLMs在HumanChatBench和DialogBench上始终优于标准基线模型，这进一步证明了V-VAE和HumanChatData的有效性。

> With the continued proliferation of Large Language Model (LLM) based chatbots, there is a growing demand for generating responses that are not only linguistically fluent but also consistently aligned with persona-specific traits in conversations. However, existing role-play and persona-based chat approaches rely heavily on static role descriptions, coarse-grained signal space, and low-quality synthetic data, which fail to capture dynamic fine-grained details in human-like chat. Human-like chat requires modeling subtle latent traits, such as emotional tone, situational awareness, and evolving personality, which are difficult to predefine and cannot be easily learned from synthetic or distillation-based data. To address these limitations, we propose a Verbal Variational Auto-Encoding (V-VAE) framework, containing a variational auto-encoding module and fine-grained control space which dynamically adapts dialogue behaviour based on fine-grained, interpretable latent variables across talking style, interaction patterns, and personal attributes. We also construct a high-quality dataset, HumanChatData, and benchmark HumanChatBench to address the scarcity of high-quality data in the human-like domain. Experiments show that LLMs based on V-VAE consistently outperform standard baselines on HumanChatBench and DialogBench, which further demonstrates the effectiveness of V-VAE and HumanChatData.

[Arxiv](https://arxiv.org/abs/2506.01524)