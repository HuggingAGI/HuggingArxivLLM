# 探究 LLMS 是否具备生成建筑设计决策的能力：一项实证研究之旅

发布时间：2024年03月03日

`LLM应用`

> Can LLMs Generate Architectural Design Decisions? -An Exploratory Empirical study

# 摘要

> 建筑知识管理（AKM）的核心在于系统地管理项目或组织内部有关架构决策和设计的相关信息，其中的关键产物就是记录重要设计抉择的架构决策记录（ADR）。ADR 能详实记载决策情境、已作出的决策及其与设计决策相关的多元视角，有助于增进团队间的透明度、协作和共识理解。尽管 ADR 带来了众多优势，但由于时间压力和技术采纳的一致性问题，在软件开发领域的实际应用进度较慢。近期大型语言模型（LLMs）技术的进步有望通过辅助生成 ADR 来填补这一应用鸿沟，不过对于 LLM 在生成或解读 ADR 上的有效性，目前尚缺乏深入研究。为此，本研究开展了一项探索性试验，目标是探究在提供决策背景的前提下，运用 LLM 进行 ADR 生成的可能性。实验过程中，我们采用了 GPT 和基于 T5 的模型，结合零样本（0-shot）、少量样本（few-shot）及微调策略，尝试从 ADR 的情境出发生成对应的决策内容。初步结果显示，在零样本环境下，前沿模型如 GPT-4 能够生成具有一定关联性和准确度的设计决策，但仍未达到人类专家级别。同时，我们也观察到，在少量样本条件下，性价比更高的模型如 GPT-3.5 实现了相近的效果；经过微调的小型模型如 Flan-T5 同样能产出相当的成果。综上所述，本次探索性研究显示 LLM 具备生成设计决策的能力，然而要实现媲美人类的专业化生成水平及推广至标准化广泛应用，还需进一步的研究探索。

> Architectural Knowledge Management (AKM) involves the organized handling of information related to architectural decisions and design within a project or organization. An essential artifact of AKM is the Architecture Decision Records (ADR), which documents key design decisions. ADRs are documents that capture decision context, decision made and various aspects related to a design decision, thereby promoting transparency, collaboration, and understanding. Despite their benefits, ADR adoption in software development has been slow due to challenges like time constraints and inconsistent uptake. Recent advancements in Large Language Models (LLMs) may help bridge this adoption gap by facilitating ADR generation. However, the effectiveness of LLM for ADR generation or understanding is something that has not been explored. To this end, in this work, we perform an exploratory study that aims to investigate the feasibility of using LLM for the generation of ADRs given the decision context. In our exploratory study, we utilize GPT and T5-based models with 0-shot, few-shot, and fine-tuning approaches to generate the Decision of an ADR given its Context. Our results indicate that in a 0-shot setting, state-of-the-art models such as GPT-4 generate relevant and accurate Design Decisions, although they fall short of human-level performance. Additionally, we observe that more cost-effective models like GPT-3.5 can achieve similar outcomes in a few-shot setting, and smaller models such as Flan-T5 can yield comparable results after fine-tuning. To conclude, this exploratory study suggests that LLM can generate Design Decisions, but further research is required to attain human-level generation and establish standardized widespread adoption.

[Arxiv](https://arxiv.org/abs/2403.01709)