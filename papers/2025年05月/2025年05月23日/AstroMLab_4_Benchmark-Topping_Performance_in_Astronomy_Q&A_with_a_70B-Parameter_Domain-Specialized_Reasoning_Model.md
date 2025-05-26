# # AstroMLab 4: 以700亿参数领域专用推理模型实现天文问答领域的超越基准性能

发布时间：2025年05月23日

`LLM应用` `天文学`

> AstroMLab 4: Benchmark-Topping Performance in Astronomy Q&A with a 70B-Parameter Domain-Specialized Reasoning Model

# 摘要

> 通用大型语言模型虽然功能强大，但在专业领域知识处理上表现欠佳，这一问题在参数量较低的版本中尤为突出。这种差距限制了它们在天文学等高要求领域的应用。基于先前的AstroSage-8B研究，本研究推出了AstroSage-70B——一个更强大、更专业的自然语言AI助手，专为天文学、天体物理学、空间科学、天体粒子物理学、宇宙学和天文仪器等领域的研究与教育设计。AstroSage-70B以Llama-3.1-70B为基础，经过大量天文学文献的持续预训练、监督微调和模型融合。除了700亿参数的规模，该模型还采用了优化的数据集、精选的学习超参数和改进的训练流程，在复杂天文学任务中表现优异。我们还在SFT数据集中融入了推理链，使AstroSage-70B能够立即回答问题，或先展示人类可读的思考过程。在包含4,425个未参与训练的文献问题的AstroMLab-1基准测试中，AstroSage-70B表现最佳，超越了包括o3、Gemini-2.5-Pro、Claude-3.7-Sonnet、Deepseek-R1和Qwen-3-235B在内的所有开源与专有模型，甚至那些API成本高出两个数量级的模型。这表明，领域专用化使大规模模型在天文学等专业领域超越通用模型，推动了AI能力的前沿发展。

> General-purpose large language models, despite their broad capabilities, often struggle with specialized domain knowledge, a limitation particularly pronounced in more accessible, lower-parameter versions. This gap hinders their deployment as effective agents in demanding fields such as astronomy. Building on our prior work with AstroSage-8B, this study introduces AstroSage-70B, a significantly larger and more advanced domain-specialized natural-language AI assistant. It is designed for research and education across astronomy, astrophysics, space science, astroparticle physics, cosmology, and astronomical instrumentation. Developed from the Llama-3.1-70B foundation, AstroSage-70B underwent extensive continued pre-training on a vast corpus of astronomical literature, followed by supervised fine-tuning and model merging. Beyond its 70-billion parameter scale, this model incorporates refined datasets, judiciously chosen learning hyperparameters, and improved training procedures, achieving state-of-the-art performance on complex astronomical tasks. Notably, we integrated reasoning chains into the SFT dataset, enabling AstroSage-70B to either answer the user query immediately, or first emit a human-readable thought process. Evaluated on the AstroMLab-1 benchmark -- comprising 4,425 questions from literature withheld during training -- AstroSage-70B achieves state-of-the-art performance. It surpasses all other tested open-weight and proprietary models, including leading systems like o3, Gemini-2.5-Pro, Claude-3.7-Sonnet, Deepseek-R1, and Qwen-3-235B, even those with API costs two orders of magnitude higher. This work demonstrates that domain specialization, when applied to large-scale models, can enable them to outperform generalist counterparts in specialized knowledge areas like astronomy, thereby advancing the frontier of AI capabilities in the field.

[Arxiv](https://arxiv.org/abs/2505.17592)