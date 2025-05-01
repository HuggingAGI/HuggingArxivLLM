# 大型语言模型理解二进制代码的有效性研究

发布时间：2025年04月30日

`LLM应用

理由：这篇论文探讨了大语言模型（LLMs）在二进制代码分析中的应用，特别是针对逆向工程任务如函数名称恢复和二进制代码总结。通过基准测试评估LLMs的能力，属于LLM的应用层面研究。` `软件安全` `软件工程`

> An Empirical Study on the Effectiveness of Large Language Models for Binary Code Understanding

# 摘要

> 二进制代码分析在软件安全领域发挥着关键作用，广泛应用于软件维护、恶意软件检测、漏洞发现和补丁分析等任务。然而，与源代码不同，二进制代码缺乏直观的语义信息，使得逆向工程师在理解时面临巨大挑战。传统逆向工具虽能将二进制代码转换为类似C语言的伪代码，但缺乏代码注释和函数名称等符号信息，仍使理解困难。

近年来，两类技术展现出巨大前景：(1) 基于深度学习的技术在二进制代码理解任务中表现出色，(2) 大语言模型（LLMs）在代码理解和生成任务上进行了广泛预训练。这使人们开始思考LLMs在二进制代码理解方面的能力。

为此，本研究提出一个基准测试，用于评估LLMs在真实逆向工程场景中的有效性，涵盖两个关键任务：函数名称恢复和二进制代码总结。我们纳入了多种目标架构和不同优化选项的二进制文件以全面评估。通过使用我们的基准对流行LLMs进行广泛研究，我们获得了对其能力和限制的深刻见解。

评估表明，现有LLMs能在一定程度上理解二进制代码，从而提高分析效率。我们的结果凸显了LLMs在推动二进制代码理解领域的巨大潜力，并为相关技术提供了新的研究方向。


> Binary code analysis plays a pivotal role in the field of software security and is widely used in tasks such as software maintenance, malware detection, software vulnerability discovery, patch analysis, etc. However, unlike source code, reverse engineers face significant challenges in understanding binary code due to the lack of intuitive semantic information. Although traditional reverse tools can convert binary code into C-like pseudo code, the lack of code comments and symbolic information such as function names still makes code understanding difficult. In recent years, two groups of techniques have shown promising prospects: (1) Deep learning-based techniques have demonstrated competitive results in tasks related to binary code understanding, furthermore, (2) Large Language Models (LLMs) have been extensively pre-trained at the source-code level for tasks such as code understanding and generation. This has left participants wondering about the capabilities of LLMs in binary code understanding. To this end, this work proposes a benchmark to evaluate the effectiveness of LLMs in real-world reverse engineering scenarios, which covers two key binary code understanding tasks, i.e., function name recovery and binary code summarization. To more comprehensively evaluate, we include binaries with multiple target architectures as well as different optimization options. We gain valuable insights into the capabilities and limitations through extensive empirical studies of popular LLMs using our benchmark. Our evaluations reveal that existing LLMs can understand binary code to a certain extent, thereby improving the efficiency of binary code analysis. Our results highlight the great potential of the LLMs in advancing the field of binary code understanding, and provide new directions for binary code analysis techniques.

[Arxiv](https://arxiv.org/abs/2504.21803)