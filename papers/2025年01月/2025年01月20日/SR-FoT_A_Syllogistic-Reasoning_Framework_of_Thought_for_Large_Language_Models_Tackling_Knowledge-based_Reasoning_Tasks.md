# SR-FoT: 大型语言模型处理知识推理任务的三段论推理思维框架

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要讨论了如何通过提出一个多阶段的三段论推理思维框架（SR-FoT）来增强大型语言模型（LLMs）的演绎推理能力，并利用其内置知识进行各种推理任务。这属于对LLMs在实际应用中的改进和优化，因此应归类为LLM应用。` `人工智能` `逻辑推理`

> SR-FoT: A Syllogistic-Reasoning Framework of Thought for Large Language Models Tackling Knowledge-based Reasoning Tasks

# 摘要

> 演绎推理是一种关键的逻辑能力，帮助我们基于现有知识解决复杂问题。尽管通过思维链提示（Chain-of-Thought prompts）增强了大型语言模型（LLMs）的能力，但它们可能不会遵循正确的推理路径。如何增强LLMs的演绎推理能力，并利用其广泛的内置知识进行各种推理任务，仍然是一个开放的问题。我们尝试模仿人类的演绎推理范式，提出了一个多阶段的三段论推理思维框架（Syllogistic-Reasoning Framework of Thought, SR-FoT），使LLMs能够进行三段论演绎推理，以处理复杂的基于知识的推理任务。SR-FoT首先解释问题，然后使用解释和原始问题提出合适的大前提。接着，它通过两个阶段生成并回答小前提问题，以匹配小前提。最后，它引导LLMs使用先前生成的大前提和小前提进行三段论演绎推理，以得出原始问题的答案。在基于知识的推理任务上进行的广泛实验证明了SR-FoT的有效性和优势。

> Deductive reasoning is a crucial logical capability that assists us in solving complex problems based on existing knowledge. Although augmented by Chain-of-Thought prompts, Large Language Models (LLMs) might not follow the correct reasoning paths. Enhancing the deductive reasoning abilities of LLMs, and leveraging their extensive built-in knowledge for various reasoning tasks, remains an open question. Attempting to mimic the human deductive reasoning paradigm, we propose a multi-stage Syllogistic-Reasoning Framework of Thought (SR-FoT) that enables LLMs to perform syllogistic deductive reasoning to handle complex knowledge-based reasoning tasks. Our SR-FoT begins by interpreting the question and then uses the interpretation and the original question to propose a suitable major premise. It proceeds by generating and answering minor premise questions in two stages to match the minor premises. Finally, it guides LLMs to use the previously generated major and minor premises to perform syllogistic deductive reasoning to derive the answer to the original question. Extensive and thorough experiments on knowledge-based reasoning tasks have demonstrated the effectiveness and advantages of our SR-FoT.

[Arxiv](https://arxiv.org/abs/2501.11599)