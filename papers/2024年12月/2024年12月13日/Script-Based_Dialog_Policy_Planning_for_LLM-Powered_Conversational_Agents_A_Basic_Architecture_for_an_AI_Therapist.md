# 基于脚本的对话策略规划：LLM驱动的“AI治疗师”基础架构

发布时间：2024年12月13日

`Agent

理由：这篇论文主要讨论了如何通过创新的对话策略规划范式来改进大型语言模型（LLM）驱动的对话代理，使其能够更好地遵循预定义规则并使其决策路径透明化。这些改进是为了使对话代理能够更好地应用于行为健康支持和“AI治疗师”场景。因此，这篇论文的核心内容是关于对话代理（Agent）的设计和改进，属于Agent分类。` `心理健康`

> Script-Based Dialog Policy Planning for LLM-Powered Conversational Agents: A Basic Architecture for an "AI Therapist"

# 摘要

> 大型语言模型（LLM）驱动的对话代理有望为用户提供大规模的行为健康支持，甚至在未来可能实现全面的“AI治疗”。尽管这些代理已经能够进行流畅且主动的情感支持对话，但它们仍存在两个关键缺陷：（a）无法始终如一地遵循预定义规则，以确保对话与整体治疗理念一致；（b）无法使其决策路径透明化，以便进行风险管理和临床评估——这两点都是“AI治疗师”不可或缺的要求。
    本研究提出了一种创新的对话策略规划范式，使对话代理能够（a）依据专家编写的“脚本”行动，该脚本详细描述了治疗方法；（b）在对话过程中明确地通过一组有限状态进行转换。脚本作为确定性组件，以理想的方式约束LLM的行为，为AI治疗师构建了基础架构。
    我们通过不同的提示技术实现了两种基于脚本的对话策略规划变体，并与LLM模拟的患者进行了100次对话。实验结果验证了该技术的可行性，并深入分析了不同实现变体的效率和效果。

> Large Language Model (LLM)-Powered Conversational Agents have the potential to provide users with scaled behavioral healthcare support, and potentially even deliver full-scale "AI therapy'" in the future. While such agents can already conduct fluent and proactive emotional support conversations, they inherently lack the ability to (a) consistently and reliably act by predefined rules to align their conversation with an overarching therapeutic concept and (b) make their decision paths inspectable for risk management and clinical evaluation -- both essential requirements for an "AI Therapist".
  In this work, we introduce a novel paradigm for dialog policy planning in conversational agents enabling them to (a) act according to an expert-written "script" that outlines the therapeutic approach and (b) explicitly transition through a finite set of states over the course of the conversation. The script acts as a deterministic component, constraining the LLM's behavior in desirable ways and establishing a basic architecture for an AI Therapist.
  We implement two variants of Script-Based Dialog Policy Planning using different prompting techniques and synthesize a total of 100 conversations with LLM-simulated patients. The results demonstrate the feasibility of this new technology and provide insights into the efficiency and effectiveness of different implementation variants.

[Arxiv](https://arxiv.org/abs/2412.15242)