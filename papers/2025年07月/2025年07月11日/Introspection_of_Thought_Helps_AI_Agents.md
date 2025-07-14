# 思考的自我反思助力AI代理

发布时间：2025年07月11日

`Agent` `人工智能`

> Introspection of Thought Helps AI Agents

# 摘要

> AI代理依赖于大型语言模型（LLMs）和多模态语言模型（MLLMs）来在文本和图像任务中执行无需后训练的解释和推理，其中LLMs和MLLMs发挥着最关键的作用，决定了AI代理的初始能力和局限性。通常，AI代理利用复杂的提示工程和外部推理框架与LLMs进行富有前景的交互，例如思维链（Chain-of-Thought）、思维迭代（Iteration of Thought）和图像思维（Image-of-Thought）。然而，它们仍然受限于LLMs在理解自然语言方面的固有局限性，而迭代推理过程会产生大量的推理成本。为此，我们通过设计一种新的提示中的LLM-Read代码，提出了一种具有思维内省（INoT）功能的新型AI代理推理框架。它使LLMs能够按照提示中的代码执行程序化对话推理过程。因此，自我否定和反思发生在LLMs内部而非外部，从而能够有效减少token成本。通过我们在三个不同任务上的六个基准实验，INoT的有效性得到了验证，性能平均提高了7.95%，超过了基线方法。此外，INoT的token成本平均比基线中表现最好的方法低58.3%。我们还通过验证实验展示了INoT在图像解释和推理中的多功能性。

> AI Agents rely on Large Language Models (LLMs) and Multimodal-LLMs (MLLMs) to perform interpretation and inference in text and image tasks without post-training, where LLMs and MLLMs play the most critical role and determine the initial ability and limitations of AI Agents. Usually, AI Agents utilize sophisticated prompt engineering and external reasoning framework to obtain a promising interaction with LLMs, e.g., Chain-of-Thought, Iteration of Thought and Image-of-Thought. However, they are still constrained by the inherent limitations of LLM in understanding natural language, and the iterative reasoning process will generate a large amount of inference cost. To this end, we propose a novel AI Agent Reasoning Framework with Introspection of Thought (INoT) by designing a new LLM-Read code in prompt. It enables LLM to execute programmatic dialogue reasoning processes following the code in prompt. Therefore, self-denial and reflection occur within LLM instead of outside LLM, which can reduce token cost effectively. Through our experiments on six benchmarks for three different tasks, the effectiveness of INoT is verified, with an average improvement of 7.95\% in performance, exceeding the baselines. Furthermore, the token cost of INoT is lower on average than the best performing method at baseline by 58.3\%. In addition, we demonstrate the versatility of INoT in image interpretation and inference through verification experiments.

[Arxiv](https://arxiv.org/abs/2507.08664)