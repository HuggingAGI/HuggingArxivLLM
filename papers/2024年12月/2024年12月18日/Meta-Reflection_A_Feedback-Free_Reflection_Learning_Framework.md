# Meta-Reflection：一种无需反馈的反思学习框架

发布时间：2024年12月18日

`LLM应用` `电子商务`

> Meta-Reflection: A Feedback-Free Reflection Learning Framework

# 摘要

> 尽管大型语言模型（LLMs）在自然语言理解和推理上能力出众，但它们时常会有不良表现，像产生幻觉和推理不忠实。一种常见的用以缓解这些问题的策略是运用反思，它通过迭代流程来优化回应。然而，虽说有希望，但反思严重依赖高品质的外部反馈，还需要迭代的多智能体推理过程，这就阻碍了其实际应用。在本文中，我们提出了元反思，这是一种全新的无需反馈的反思机制，仅需一次推理过程，无需外部反馈。受人类在遇到类似问题时能够记住并从过往经验中检索反思的能力所启发，元反思将反思的见解整合进一个码本，使得历史见解能够被存储、检索并用于指导LLMs解决问题。为了全面探究和评估元反思在现实场景中的实用性，我们引入了一个名为电子商务客户意图检测（ECID）的工业电子商务基准。在公共数据集和ECID基准上开展的大量实验彰显了我们所提出方法的有效性和高效性。

> Despite the remarkable capabilities of large language models (LLMs) in natural language understanding and reasoning, they often display undesirable behaviors, such as generating hallucinations and unfaithful reasoning. A prevalent strategy to mitigate these issues is the use of reflection, which refines responses through an iterative process. However, while promising, reflection heavily relies on high-quality external feedback and requires iterative multi-agent inference processes, thus hindering its practical application. In this paper, we propose Meta-Reflection, a novel feedback-free reflection mechanism that necessitates only a single inference pass without external feedback. Motivated by the human ability to remember and retrieve reflections from past experiences when encountering similar problems, Meta-Reflection integrates reflective insights into a codebook, allowing the historical insights to be stored, retrieved, and used to guide LLMs in problem-solving. To thoroughly investigate and evaluate the practicality of Meta-Reflection in real-world scenarios, we introduce an industrial e-commerce benchmark named E-commerce Customer Intent Detection (ECID). Extensive experiments conducted on both public datasets and the ECID benchmark highlight the effectiveness and efficiency of our proposed approach.

[Arxiv](https://arxiv.org/abs/2412.13781)