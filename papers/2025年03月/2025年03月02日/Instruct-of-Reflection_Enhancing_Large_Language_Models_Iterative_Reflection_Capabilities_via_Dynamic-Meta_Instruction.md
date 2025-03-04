# Instruct-of-Reflection: 通过动态元指令提升大型语言模型的迭代反思能力

发布时间：2025年03月02日

`LLM理论

摘要讨论了大语言模型的自我反思机制，提出了一种新的框架来改进模型的迭代反思能力，属于对LLM内在机制的理论研究和改进。` `人工智能`

> Instruct-of-Reflection: Enhancing Large Language Models Iterative Reflection Capabilities via Dynamic-Meta Instruction

# 摘要

> 大语言模型（LLMs）的自我反思机制已引起广泛关注。现有方法主要通过模型基于LLMs的内在反思能力或外部反馈迭代优化先前响应。然而，近期研究对无外部反馈的内在自我修正效果提出了质疑，甚至认为这可能反而损害性能。基于实证研究，我们发现当前静态反思方法可能引发冗余、漂移及固执等问题。为解决这一难题，我们提出了一种新型通用反思框架——Instruct-of-Reflection (IoRT)，该框架通过动态元指令提升LLMs的迭代反思能力。具体而言，我们设计了由元思维驱动的引导器与自我一致性分类器，生成包括刷新、停止及选择在内的多样化指令，以指导下一阶段的反思迭代。实验结果表明，IoRT在数学与常识推理任务中较现有基线平均提升了10.1%，充分验证了其有效性与适用性。

> Self-reflection for Large Language Models (LLMs) has gained significant attention. Existing approaches involve models iterating and improving their previous responses based on LLMs' internal reflection ability or external feedback. However, recent research has raised doubts about whether intrinsic self-correction without external feedback may even degrade performance. Based on our empirical evidence, we find that current static reflection methods may lead to redundant, drift, and stubborn issues. To mitigate this, we introduce Instruct-of-Reflection (IoRT), a novel and general reflection framework that leverages dynamic-meta instruction to enhance the iterative reflection capability of LLMs. Specifically, we propose the instructor driven by the meta-thoughts and self-consistency classifier, generates various instructions, including refresh, stop, and select, to guide the next reflection iteration. Our experiments demonstrate that IoRT achieves an average improvement of 10.1% over established baselines in mathematical and commonsense reasoning tasks, highlighting its efficacy and applicability.

[Arxiv](https://arxiv.org/abs/2503.00902)