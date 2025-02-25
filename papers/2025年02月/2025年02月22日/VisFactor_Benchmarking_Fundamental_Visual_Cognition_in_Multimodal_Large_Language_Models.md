# VisFactor：多模态大语言模型的基本视觉理解能力评测。

发布时间：2025年02月22日

`LLM应用` `人工智能` `基准测试`

> VisFactor: Benchmarking Fundamental Visual Cognition in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在多模态理解方面取得了显著进展，但其视觉认知能力仍有待深入探索。为填补这一空白，我们推出了VisFactor——一个基于经典心理测量工具FRCT（Factor-Referenced Cognitive Test）的全新基准测试。VisFactor将FRCT中的视觉相关子测试数字化，系统性地评估MLLMs在空间推理、感知速度和模式识别等关键视觉任务中的表现。我们采用Chain-of-Thought和Multi-Agent Debate等多样化提示策略，对GPT-4o、Gemini-Pro和Qwen-VL等前沿MLLMs进行了全面评测。研究发现，现有MLLMs的视觉认知能力存在明显短板，表现常近似随机猜测，即便借助先进提示技术，改进也十分有限。这些发现凸显了加强MLLMs核心视觉推理能力研究的迫切需求。为推动该领域研究，我们已将VisFactor基准测试开源，地址为https://github.com/CUHK-ARISE/VisFactor。

> Multimodal Large Language Models (MLLMs) have demonstrated remarkable advancements in multimodal understanding; however, their fundamental visual cognitive abilities remain largely underexplored. To bridge this gap, we introduce VisFactor, a novel benchmark derived from the Factor-Referenced Cognitive Test (FRCT), a well-established psychometric assessment of human cognition. VisFactor digitalizes vision-related FRCT subtests to systematically evaluate MLLMs across essential visual cognitive tasks including spatial reasoning, perceptual speed, and pattern recognition. We present a comprehensive evaluation of state-of-the-art MLLMs, such as GPT-4o, Gemini-Pro, and Qwen-VL, using VisFactor under diverse prompting strategies like Chain-of-Thought and Multi-Agent Debate. Our findings reveal a concerning deficiency in current MLLMs' fundamental visual cognition, with performance frequently approaching random guessing and showing only marginal improvements even with advanced prompting techniques. These results underscore the critical need for focused research to enhance the core visual reasoning capabilities of MLLMs. To foster further investigation in this area, we release our VisFactor benchmark at https://github.com/CUHK-ARISE/VisFactor.

[Arxiv](https://arxiv.org/abs/2502.16435)