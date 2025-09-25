# WEST：基于LLM的语音工具包——面向语音理解、生成与交互

发布时间：2025年09月24日

`LLM应用` `媒体与娱乐`

> WEST: LLM based Speech Toolkit for Speech Understanding, Generation, and Interaction

# 摘要

> 本文提出了WEST（WE语音工具包）——一个基于大型语言模型（LLM）的语音工具包，支持语音理解、生成与交互任务。WEST具备三大核心特性：1）全LLM驱动：借力大型模型的成熟架构、生态（如Hugging Face）及方法（如序列打包），真正实现“站在巨人肩膀上”。2）全栈覆盖：涵盖语音识别、合成、理解、对话及多模态能力等任务，且支持灵活整合开源模型。3）简单友好：力求“简单友好”，让每个用户都能轻松上手。此外，WEST提供两类实验方案、模型及实验结果：第一类完全基于开源模型与开源数据，用户可据此完整复现本文实验，同时可作为验证系统或最小系统基线；第二类经海量数据训练，性能更优，用户可直接开箱即用。WEST已开源发布，项目地址：https://github.com/wenet-e2e/west/

> In this paper, we present WEST(WE Speech Toolkit), a speech toolkit based on a large language model (LLM) for speech understanding, generation, and interaction. There are three key features of WEST: 1) Fully LLM-based: Standing on the shoulders of giants by reusing mature architectures, ecosystems (e.g., Hugging Face), and methods (e.g., sequence packing) from large models. 2) Full-stack: Supports tasks such as recognition, synthesis, understanding, dialogue, and multimodal capabilities, with extensibility to incorporate open-source models. 3) Simple and Stupid: A simple and stupid speech toolkit that everyone can Touch. In addition, WEST provides two types of recipes, models, and experimental results. The first is entirely based on open-source models and open-source data, allowing users to fully reproduce the experiments in this paper and serving as a verification system or minimal system baseline. The second is trained on massive data, offering superior performance so the user can directly apply it out of the box. WEST is publicly avilable at https://github.com/wenet-e2e/west/

[Arxiv](https://arxiv.org/abs/2509.19902)