# # 如此说道的长上下文大型语言模型

长上下文LLMs能够理解和回应超长提示，远远突破了传统4k令牌的限制。然而，长上下文模型的优势并非没有挑战。首先，所需的计算资源显著增加。其次，模型需要经过精心微调，以处理超长序列而不丢失上下文。

发布时间：2025年02月24日

`LLM理论` `计算机科学`

> Thus Spake Long-Context Large Language Model

# 摘要

> 长上下文是自然语言处理（NLP）中的重要主题，贯穿了NLP架构的发展历程，并为大型语言模型（LLMs）带来了巨大机遇，赋予其类似人类的终身学习潜力。然而，追求长上下文的过程充满挑战。尽管如此，长上下文仍是LLMs的核心竞争优势。过去两年中，LLMs的上下文长度实现了突破性扩展，达到数百万个token。同时，长上下文LLMs的研究已从长度外推扩展到对架构、基础设施、训练和评估技术的全面关注。
受交响诗《查拉图斯特拉如是说》启发，我们将扩展LLMs上下文的过程与人类试图超越其 mortality 的努力相类比。在这篇综述中，我们将展示LLMs如何在对更长上下文的巨大需求与其最终有限的事实之间挣扎。为此，我们将从架构、基础设施、训练和评估四个角度，全面描绘长上下文LLMs的生命周期，展现长上下文技术的全貌。在本综述的结尾，我们将提出目前长上下文LLMs面临的10个未解答问题。我们希望这篇综述能为长上下文LLMs的研究提供一个系统的介绍。

> Long context is an important topic in Natural Language Processing (NLP), running through the development of NLP architectures, and offers immense opportunities for Large Language Models (LLMs) giving LLMs the lifelong learning potential akin to humans. Unfortunately, the pursuit of a long context is accompanied by numerous obstacles. Nevertheless, long context remains a core competitive advantage for LLMs. In the past two years, the context length of LLMs has achieved a breakthrough extension to millions of tokens. Moreover, the research on long-context LLMs has expanded from length extrapolation to a comprehensive focus on architecture, infrastructure, training, and evaluation technologies.
  Inspired by the symphonic poem, Thus Spake Zarathustra, we draw an analogy between the journey of extending the context of LLM and the attempts of humans to transcend its mortality. In this survey, We will illustrate how LLM struggles between the tremendous need for a longer context and its equal need to accept the fact that it is ultimately finite. To achieve this, we give a global picture of the lifecycle of long-context LLMs from four perspectives: architecture, infrastructure, training, and evaluation, showcasing the full spectrum of long-context technologies. At the end of this survey, we will present 10 unanswered questions currently faced by long-context LLMs. We hope this survey can serve as a systematic introduction to the research on long-context LLMs.

[Arxiv](https://arxiv.org/abs/2502.17129)