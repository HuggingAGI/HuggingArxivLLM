# 认知工具助力语言模型推理能力的激发

发布时间：2025年06月13日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）推理能力的机制，提出了基于认知工具的模块化方法，并通过实验验证了其有效性。研究不仅展示了应用层面的提升，还深入分析了推理能力的理论基础，属于LLM理论类别。` `人工智能` `认知科学`

> Eliciting Reasoning in Language Models with Cognitive Tools

# 摘要

> 近期，OpenAI的o1等推理模型的出现引发了AI社区对其闭源模型背后机制的热烈讨论，并随之掀起了一波复现研究热潮，尤其是在开源社区中。这一讨论热潮最终被DeepSeek-R1的研究成果所平息，他们证明了通过思维链和强化学习（RL）可以在基础LLM之上有效复现推理能力。然而，探索其他能够从理论上揭示推理机制的方法仍然具有重要意义，这不仅有助于我们更好地理解其内在机制，还可能带来具有互补优势的额外方法。

在这里，我们基于认知心理学和认知架构的长期研究文献，提出了一个观点：推理能力源于一系列模块化、预设的认知操作的有序执行。至关重要的是，我们将这一核心理念融入了现代智能体工具调用框架之中。具体而言，我们赋予大型语言模型（LLM）一套小型的“认知工具”，每个工具都封装了特定的推理操作，均由LLM自身执行。令人惊讶的是，这种简单的策略在标准数学推理基准测试中，与基础LLM相比，无论是闭源还是开源权重模型，都取得了显著的性能提升。例如，为GPT-4.1提供我们的“认知工具”后，其在AIME2024测试中的pass@1性能从26.7%提升至43.3%，几乎达到了o1-preview的水平。

除了其实践价值外，这项研究还为关于后训练方法在激发LLM推理能力中的作用，以及这种能力是否仅是预训练过程中获得的固有能力的体现，提供了新的视角。此外，它还探讨了后训练方法是否仅仅揭示了这些潜在能力的讨论。

> The recent advent of reasoning models like OpenAI's o1 was met with excited speculation by the AI community about the mechanisms underlying these capabilities in closed models, followed by a rush of replication efforts, particularly from the open source community. These speculations were largely settled by the demonstration from DeepSeek-R1 that chains-of-thought and reinforcement learning (RL) can effectively replicate reasoning on top of base LLMs. However, it remains valuable to explore alternative methods for theoretically eliciting reasoning that could help elucidate the underlying mechanisms, as well as providing additional methods that may offer complementary benefits.
  Here, we build on the long-standing literature in cognitive psychology and cognitive architectures, which postulates that reasoning arises from the orchestrated, sequential execution of a set of modular, predetermined cognitive operations. Crucially, we implement this key idea within a modern agentic tool-calling framework. In particular, we endow an LLM with a small set of "cognitive tools" encapsulating specific reasoning operations, each executed by the LLM itself. Surprisingly, this simple strategy results in considerable gains in performance on standard mathematical reasoning benchmarks compared to base LLMs, for both closed and open-weight models. For instance, providing our "cognitive tools" to GPT-4.1 increases its pass@1 performance on AIME2024 from 26.7% to 43.3%, bringing it very close to the performance of o1-preview.
  In addition to its practical implications, this demonstration contributes to the debate regarding the role of post-training methods in eliciting reasoning in LLMs versus the role of inherent capabilities acquired during pre-training, and whether post-training merely uncovers these latent abilities.

[Arxiv](https://arxiv.org/abs/2506.12115)