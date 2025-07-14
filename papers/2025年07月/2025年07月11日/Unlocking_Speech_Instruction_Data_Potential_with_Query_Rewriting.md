# # 查询改写：释放语音指令数据的无限潜力

发布时间：2025年07月11日

`LLM应用` `语音合成` `语音指令`

> Unlocking Speech Instruction Data Potential with Query Rewriting

# 摘要

> 端到端的大型语音语言模型（	extbf{LSLMs}）在响应延迟和语音理解能力方面展现出强大的潜力，尤其在语音理解任务中表现出色。然而，由于数据集的缺失和训练任务的偏颇，语音指令的执行能力尚未完全释放。基于丰富的自动语音识别（	extbf{ASR}）数据集，先前的研究通过大型语言模型（	extbf{LLMs}）延续语音的语义信息来构建语音指令数据集。但受限于 LLM 生成结果与真实人类回应的差距，延续方法进一步放大了这些不足。鉴于人工收集和标注语音指令数据集成本高昂，利用语音合成构建大规模语音指令数据集成为一种高效且可靠的替代方案。尽管现代文本到语音（	extbf{TTS}）模型已达到接近人类水平的合成质量，但受限于训练数据分布，将分布外的文本指令转化为语音仍具挑战。为解决这一问题，我们提出了一种基于多 LLM 知识融合的查询重写框架，通过多个代理对合成语音进行标注和验证，从而无需人工标注即可构建高质量的语音指令数据集。实验表明，该方法通过零样本重写，可将文本指令转换为更适用于 TTS 模型的分布，使数据可用性从 72% 提升至 93%。它在需要复杂知识和上下文相关能力的重写任务中也展现出独特优势。

> End-to-end Large Speech Language Models~(\textbf{LSLMs}) demonstrate strong potential in response latency and speech comprehension capabilities, showcasing general intelligence across speech understanding tasks. However, the ability to follow speech instructions has not been fully realized due to the lack of datasets and heavily biased training tasks. Leveraging the rich ASR datasets, previous approaches have used Large Language Models~(\textbf{LLMs}) to continue the linguistic information of speech to construct speech instruction datasets. Yet, due to the gap between LLM-generated results and real human responses, the continuation methods further amplify these shortcomings. Given the high costs of collecting and annotating speech instruction datasets by humans, using speech synthesis to construct large-scale speech instruction datasets has become a balanced and robust alternative. Although modern Text-To-Speech~(\textbf{TTS}) models have achieved near-human-level synthesis quality, it is challenging to appropriately convert out-of-distribution text instruction to speech due to the limitations of the training data distribution in TTS models. To address this issue, we propose a query rewriting framework with multi-LLM knowledge fusion, employing multiple agents to annotate and validate the synthesized speech, making it possible to construct high-quality speech instruction datasets without relying on human annotation. Experiments show that this method can transform text instructions into distributions more suitable for TTS models for speech synthesis through zero-shot rewriting, increasing data usability from 72\% to 93\%. It also demonstrates unique advantages in rewriting tasks that require complex knowledge and context-related abilities.

[Arxiv](https://arxiv.org/abs/2507.08603)