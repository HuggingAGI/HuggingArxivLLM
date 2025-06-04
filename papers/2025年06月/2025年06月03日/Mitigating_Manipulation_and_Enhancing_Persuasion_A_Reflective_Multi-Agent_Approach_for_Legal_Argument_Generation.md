# 遏制操纵，提升说服力：基于反思型多智能体的法律论点生成方法

发布时间：2025年06月03日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在法律论点生成中的应用，提出了一种反思型多智能体方法来解决法律合规劝说中的问题。尽管涉及智能体的概念，但核心是LLM的应用，因此归类为LLM应用。` `多智能体系统`

> Mitigating Manipulation and Enhancing Persuasion: A Reflective Multi-Agent Approach for Legal Argument Generation

# 摘要

> 大型语言模型（LLMs）在法律论点生成中的应用日益增多，但它们存在通过幻觉和无根据劝说被操控的风险，且往往无法有效利用事实依据或在论点不成立时保持克制。本文提出了一种创新的反思型多智能体方法，旨在解决法律合规劝说中的这些问题。我们的方法通过因素分析师和论点润色师这两个专门智能体的迭代协作，生成包含原告、被告和反驳的三层次法律论点。我们采用四种不同LLMs（GPT-4o、GPT-4o-mini、Llama-4-Maverick-17b-128e、Llama-4-Scout-17b-16e）在三种法律场景（可论证、不匹配和不可论证）中，将反思型多智能体与单智能体、增强提示的单智能体和非反思型多智能体基线进行了对比评估。实验结果显示，反思型多智能体在成功克制（避免生成站不住脚的论点）、幻觉准确性（减少编造和错误归属的因素）方面表现显著优于其他方法，尤其在不可论证场景中效果突出，同时提升了对事实依据的利用效率。这表明，在多智能体框架中引入结构化反思为基于LLM的法律论辩系统提供了促进道德劝说和减少操控风险的可靠方法，这是实现法律领域可信AI的重要一步。项目页面：https://lizhang-aiandlaw.github.io/A-Reflective-Multi-Agent-Approach-for-Legal-Argument-Generation/

> Large Language Models (LLMs) are increasingly explored for legal argument generation, yet they pose significant risks of manipulation through hallucination and ungrounded persuasion, and often fail to utilize provided factual bases effectively or abstain when arguments are untenable. This paper introduces a novel reflective multi-agent method designed to address these challenges in the context of legally compliant persuasion. Our approach employs specialized agents--a Factor Analyst and an Argument Polisher--in an iterative refinement process to generate 3-ply legal arguments (plaintiff, defendant, rebuttal). We evaluate Reflective Multi-Agent against single-agent, enhanced-prompt single-agent, and non-reflective multi-agent baselines using four diverse LLMs (GPT-4o, GPT-4o-mini, Llama-4-Maverick-17b-128e, Llama-4-Scout-17b-16e) across three legal scenarios: "arguable", "mismatched", and "non-arguable". Results demonstrate Reflective Multi-Agent's significant superiority in successful abstention (preventing generation when arguments cannot be grounded), marked improvements in hallucination accuracy (reducing fabricated and misattributed factors), particularly in "non-arguable" scenarios, and enhanced factor utilization recall (improving the use of provided case facts). These findings suggest that structured reflection within a multi-agent framework offers a robust computable method for fostering ethical persuasion and mitigating manipulation in LLM-based legal argumentation systems, a critical step towards trustworthy AI in law. Project page: https://lizhang-aiandlaw.github.io/A-Reflective-Multi-Agent-Approach-for-Legal-Argument-Generation/

[Arxiv](https://arxiv.org/abs/2506.02992)