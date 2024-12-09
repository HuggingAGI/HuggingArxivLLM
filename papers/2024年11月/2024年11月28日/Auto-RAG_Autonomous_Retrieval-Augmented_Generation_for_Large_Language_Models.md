# Auto-RAG：大型语言模型的自主检索增强式生成

发布时间：2024年11月28日

`RAG` `信息检索`

> Auto-RAG: Autonomous Retrieval-Augmented Generation for Large Language Models

# 摘要

> 迭代检索指的是在生成过程中，模型持续向检索器进行查询，以增强所检索知识的相关性，进而提升检索增强生成（RAG）的性能。现有的工作往往通过少样本提示或人工构建的规则来实现迭代检索。这不仅带来了额外的推理开销，还忽视了大型语言模型（LLMs）强大的推理能力。在本文中，我们推出了 Auto-RAG，这是一个围绕 LLM 强大决策能力的自主迭代检索模型。Auto-RAG 与检索器展开多轮对话，有规划地进行检索并优化查询，以获取宝贵知识。该过程持续进行，直至收集到足够的外部信息，再将结果呈现给用户。为此，我们研发了一种在迭代检索中自主合成基于推理的决策指令的方法，并对最新的开源 LLMs 进行了微调。实验结果显示，Auto-RAG 能够与检索器进行自主迭代交互，有效利用 LLMs 出色的推理和决策能力，在六个基准测试中表现卓越。进一步分析表明，Auto-RAG 能够依据问题的难度和所检索知识的效用，自主调整迭代次数，无需任何人工干预。此外，Auto-RAG 用自然语言呈现迭代检索过程，增强了可解释性，同时为用户带来更直观的体验ootnote{代码可在 url{https://github.com/ictnlp/Auto-RAG}获取。

> Iterative retrieval refers to the process in which the model continuously queries the retriever during generation to enhance the relevance of the retrieved knowledge, thereby improving the performance of Retrieval-Augmented Generation (RAG). Existing work typically employs few-shot prompting or manually constructed rules to implement iterative retrieval. This introduces additional inference overhead and overlooks the remarkable reasoning capabilities of Large Language Models (LLMs). In this paper, we introduce Auto-RAG, an autonomous iterative retrieval model centered on the LLM's powerful decision-making capabilities. Auto-RAG engages in multi-turn dialogues with the retriever, systematically planning retrievals and refining queries to acquire valuable knowledge. This process continues until sufficient external information is gathered, at which point the results are presented to the user. To this end, we develop a method for autonomously synthesizing reasoning-based decision-making instructions in iterative retrieval and fine-tuned the latest open-source LLMs. The experimental results indicate that Auto-RAG is capable of autonomous iterative interaction with the retriever, effectively leveraging the remarkable reasoning and decision-making abilities of LLMs, which lead to outstanding performance across six benchmarks. Further analysis reveals that Auto-RAG can autonomously adjust the number of iterations based on the difficulty of the questions and the utility of the retrieved knowledge, without requiring any human intervention. Moreover, Auto-RAG expresses the iterative retrieval process in natural language, enhancing interpretability while providing users with a more intuitive experience\footnote{Code is available at \url{https://github.com/ictnlp/Auto-RAG}.

[Arxiv](https://arxiv.org/abs/2411.19443)