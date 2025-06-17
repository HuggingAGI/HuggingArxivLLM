# EvolvTrip：利用时间心智图深化文学角色解析

发布时间：2025年06月16日

`LLM应用` `叙事写作` `文学分析`

> EvolvTrip: Enhancing Literary Character Understanding with Temporal Theory-of-Mind Graphs

# 摘要

> 生动刻画人物是叙事写作成功的关键。欣赏人物特质需要读者具备心理理论（ToM）能力，即推断人物在复杂情节中不断演变的信念、欲望和意图。虽然人类在长篇叙事中进行心理理论推理得心应手，但大型语言模型（LLMs）常常力不从心。为此，我们构建了 LitCharToM 基准测试，基于经典文学作品，涵盖四个心理理论维度，专为评估 LLMs 在长篇叙事中的心理理论推理能力而设计。同时，我们推出了 EvolvTrip，一个视角感知的时序知识图谱，能够全程追踪人物心理发展。实验结果表明，EvolvTrip 能在各种规模下显著提升 LLMs 的性能，尤其在长上下文场景中表现突出。对小型模型而言，EvolvTrip 更是如虎添翼，显著缩小了其与大型 LLMs 的性能差距，且与长篇叙事高度兼容。我们的研究凸显了明确表示时序人物心理状态在叙事理解中的重要性，并为更深入的角色理解奠定了基础。我们的数据和代码已开源，详情请访问 https://github.com/Bernard-Yang/EvolvTrip。

> A compelling portrayal of characters is essential to the success of narrative writing. For readers, appreciating a character's traits requires the ability to infer their evolving beliefs, desires, and intentions over the course of a complex storyline, a cognitive skill known as Theory-of-Mind (ToM). Performing ToM reasoning in prolonged narratives requires readers to integrate historical context with current narrative information, a task at which humans excel but Large Language Models (LLMs) often struggle. To systematically evaluate LLMs' ToM reasoning capability in long narratives, we construct LitCharToM, a benchmark of character-centric questions across four ToM dimensions from classic literature. Further, we introduce EvolvTrip, a perspective-aware temporal knowledge graph that tracks psychological development throughout narratives. Our experiments demonstrate that EvolvTrip consistently enhances performance of LLMs across varying scales, even in challenging extended-context scenarios. EvolvTrip proves to be particularly valuable for smaller models, partially bridging the performance gap with larger LLMs and showing great compatibility with lengthy narratives. Our findings highlight the importance of explicit representation of temporal character mental states in narrative comprehension and offer a foundation for more sophisticated character understanding. Our data and code are publicly available at https://github.com/Bernard-Yang/EvolvTrip.

[Arxiv](https://arxiv.org/abs/2506.13641)