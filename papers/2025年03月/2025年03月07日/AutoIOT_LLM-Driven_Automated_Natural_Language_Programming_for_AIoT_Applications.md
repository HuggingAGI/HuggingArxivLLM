# AutoIOT: 基于LLM驱动的自动化自然语言编程，专为AIoT应用打造

发布时间：2025年03月07日

`LLM应用` `AIoT` `物联网`

> AutoIOT: LLM-Driven Automated Natural Language Programming for AIoT Applications

# 摘要

> 大型语言模型（LLMs）的出现深刻改变了我们的生活，不仅革新了与AI的交互方式，还大大降低了使用AI的门槛。尽管LLMs主要用于自然语言交互，但其内置的丰富知识使其能够理解数字传感器数据，从而通过物联网传感器和执行器与物理世界互动，完成各种AIoT任务。这一演变引发了传统AIoT应用开发的范式转变，通过自然语言促进AIoT应用的设计与开发，使其触手可及。然而，要充分发挥LLMs在AIoT应用开发中的潜力，仍需解决一些局限性。首先，现有解决方案通常需要将原始传感器数据传输到LLM服务器，这引发了隐私问题，产生了高昂的查询费用，并受限于令牌大小。此外，LLMs的推理过程对用户来说是不透明的，使得验证推理结果的鲁棒性和正确性变得困难。本文介绍了AutoIOT，一种基于LLM的AIoT应用自动化程序生成器。AutoIOT使用户能够使用自然语言（输入）指定需求，并自动生成带文档的可解释程序（输出）。AutoIOT通过自动化迭代优化来提升生成代码的质量，同时尽量减少用户参与。AutoIOT不仅使AIoT任务的执行更具可解释性，还通过本地执行合成程序缓解了隐私担忧并降低了令牌成本。广泛的实验和用户研究表明，AutoIOT在各种AIoT任务的程序合成方面表现出色，其合成的程序不仅能够匹配，甚至在某些情况下超越一些具有代表性的基线。

> The advent of Large Language Models (LLMs) has profoundly transformed our lives, revolutionizing interactions with AI and lowering the barrier to AI usage. While LLMs are primarily designed for natural language interaction, the extensive embedded knowledge empowers them to comprehend digital sensor data. This capability enables LLMs to engage with the physical world through IoT sensors and actuators, performing a myriad of AIoT tasks. Consequently, this evolution triggers a paradigm shift in conventional AIoT application development, democratizing its accessibility to all by facilitating the design and development of AIoT applications via natural language. However, some limitations need to be addressed to unlock the full potential of LLMs in AIoT application development. First, existing solutions often require transferring raw sensor data to LLM servers, which raises privacy concerns, incurs high query fees, and is limited by token size. Moreover, the reasoning processes of LLMs are opaque to users, making it difficult to verify the robustness and correctness of inference results. This paper introduces AutoIOT, an LLM-based automated program generator for AIoT applications. AutoIOT enables users to specify their requirements using natural language (input) and automatically synthesizes interpretable programs with documentation (output). AutoIOT automates the iterative optimization to enhance the quality of generated code with minimum user involvement. AutoIOT not only makes the execution of AIoT tasks more explainable but also mitigates privacy concerns and reduces token costs with local execution of synthesized programs. Extensive experiments and user studies demonstrate AutoIOT's remarkable capability in program synthesis for various AIoT tasks. The synthesized programs can match and even outperform some representative baselines.

[Arxiv](https://arxiv.org/abs/2503.05346)