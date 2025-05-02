# AdaptMI: 针对小型语言模型的自适应技能型上下文数学教学

发布时间：2025年04月30日

`LLM应用` `人工智能`

> AdaptMI: Adaptive Skill-based In-context Math Instruction for Small Language Models

# 摘要

> 上下文学习让语言模型在获得合适的信息后，能够提升自己的解题能力。由于上下文信息的选择可以根据具体问题来决定，因此上下文学习类似于人类在课堂上向老师学习的过程。最近的研究表明，可以通过利用前沿大型语言模型的元认知能力（即预测解决问题所需技能的能力），并使用推荐的技能构建必要的上下文示例来提升ICL的表现。然而，尽管这种基于技能的策略能够提升大型模型的ICL性能，但它对小型语言模型（SLM）的提升效果却微乎其微，凸显出ICL能力上的性能差距。我们研究了这一差距，并发现基于技能的提示可能通过引入不必要的信息损害SLM在简单问题上的表现，这类似于认知过载。为此，我们提出了AdaptMI，这是一种为SLM自适应选择基于技能的上下文数学指令的方法。受人类教学中认知负荷理论的启发，我们仅在模型表现不佳时引入基于技能的示例。我们进一步提出了AdaptMI+，该方法增加了针对模型响应中缺失的具体技能的示例。在流行的数学基准测试和五个SLM（1B至7B；Qwen、Llama）上进行的5-shot评估中，AdaptMI+相比 naive 的基于技能策略，准确率提升了高达6%。

> In-context learning (ICL) allows a language model to improve its problem-solving capability when provided with suitable information in context. Since the choice of in-context information can be determined based on the problem itself, in-context learning is analogous to human learning from teachers in a classroom. Recent works (Didolkar et al., 2024a; 2024b) show that ICL performance can be improved by leveraging a frontier large language model's (LLM) ability to predict required skills to solve a problem, popularly referred to as an LLM's metacognition, and using the recommended skills to construct necessary in-context examples. While this skill-based strategy boosts ICL performance in larger models, its gains on small language models (SLMs) have been minimal, highlighting a performance gap in ICL capabilities. We investigate this gap and show that skill-based prompting can hurt SLM performance on easy questions by introducing unnecessary information, akin to cognitive overload. To address this, we introduce AdaptMI, an adaptive approach to selecting skill-based in-context Math Instructions for SLMs. Inspired by cognitive load theory from human pedagogy, our method only introduces skill-based examples when the model performs poorly. We further propose AdaptMI+, which adds examples targeted to the specific skills missing from the model's responses. On 5-shot evaluations across popular math benchmarks and five SLMs (1B--7B; Qwen, Llama), AdaptMI+ improves accuracy by up to 6% over naive skill-based strategies.

[Arxiv](https://arxiv.org/abs/2505.00147)