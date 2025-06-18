# AIRTBench：评估语言模型中的自主 AI 红队能力

发布时间：2025年06月17日

`LLM应用

理由：这篇论文评估了语言模型在发现和利用AI/ML安全漏洞方面的应用能力，属于LLM的应用层面研究。` `AI安全` `信息安全`

> AIRTBench: Measuring Autonomous AI Red Teaming Capabilities in Language Models

# 摘要

> 我们推出AIRTBench，这是一个评估语言模型自主发现和利用AI/ML安全漏洞能力的AI红队基准测试。该基准测试包含了来自Dreadnode平台Crucible环境的70个现实黑盒夺旗（CTF）挑战，要求模型编写Python代码与AI系统交互并发起攻击。Claude-3.7-Sonnet表现出色，成功解决了43个挑战（总挑战的61%，整体成功率46.9%），其次是Gemini-2.5-Pro（39个挑战，56%，整体成功率34.3%），GPT-4.5-Preview（34个挑战，49%，整体成功率36.9%）和DeepSeek R1（29个挑战，41%，整体成功率26.9%）。我们的评估结果显示，前沿模型在提示注入攻击方面表现出色（平均成功率49%），但在系统利用和模型反转挑战方面表现欠佳（成功率低于26%，即使是最佳模型也不例外）。前沿模型远超开源替代方案，最佳真正开源模型（Llama-4-17B）仅解决了7个挑战（10%，整体成功率1.0%），尽管在某些困难挑战中展示了专业能力。与人类安全研究员相比，大型语言模型（LLMs）以惊人的效率解决问题，通常在几分钟内完成人类通常需要数小时或数天的工作——在困难挑战中，效率优势超过5,000倍。我们的研究填补了评估领域的重要空白，提供了首个专门设计的全面基准，用于衡量和跟踪自主AI红队能力的进步。

> We introduce AIRTBench, an AI red teaming benchmark for evaluating language models' ability to autonomously discover and exploit Artificial Intelligence and Machine Learning (AI/ML) security vulnerabilities. The benchmark consists of 70 realistic black-box capture-the-flag (CTF) challenges from the Crucible challenge environment on the Dreadnode platform, requiring models to write python code to interact with and compromise AI systems. Claude-3.7-Sonnet emerged as the clear leader, solving 43 challenges (61% of the total suite, 46.9% overall success rate), with Gemini-2.5-Pro following at 39 challenges (56%, 34.3% overall), GPT-4.5-Preview at 34 challenges (49%, 36.9% overall), and DeepSeek R1 at 29 challenges (41%, 26.9% overall). Our evaluations show frontier models excel at prompt injection attacks (averaging 49% success rates) but struggle with system exploitation and model inversion challenges (below 26%, even for the best performers). Frontier models are far outpacing open-source alternatives, with the best truly open-source model (Llama-4-17B) solving 7 challenges (10%, 1.0% overall), though demonstrating specialized capabilities on certain hard challenges. Compared to human security researchers, large language models (LLMs) solve challenges with remarkable efficiency completing in minutes what typically takes humans hours or days-with efficiency advantages of over 5,000x on hard challenges. Our contribution fills a critical gap in the evaluation landscape, providing the first comprehensive benchmark specifically designed to measure and track progress in autonomous AI red teaming capabilities.

[Arxiv](https://arxiv.org/abs/2506.14682)