# SurgRAW：多智能体工作流结合链式推理的外科智能系统

发布时间：2025年03月13日

`RAG` `机器人辅助手术`

> SurgRAW: Multi-Agent Workflow with Chain-of-Thought Reasoning for Surgical Intelligence

# 摘要

> 视觉语言模型（VLMs）在手术智能中的应用面临幻觉、领域知识差距以及对手术场景任务间依赖关系理解不足的挑战，这影响了临床可靠性。尽管近期VLMs展现了强大的通用推理能力，但它们仍缺乏精准解读手术场景所需的领域专业知识和任务感知能力。虽然链式思维（CoT）能够更有效地结构化推理，但现有方法依赖于自动生成的CoT步骤，这往往会加剧领域差距和幻觉问题。为了解决这些问题，我们提出了SurgRAW，一个基于CoT的多智能体框架，为机器人辅助手术中的大多数任务提供透明且可解释的见解。通过在五个任务中使用专门的CoT提示：器械识别、动作识别、动作预测、患者数据提取和结果评估，SurgRAW通过结构化且领域的推理来缓解幻觉问题。检索增强生成（RAG）也被整合进来，利用外部医疗知识来填补领域差距并提高响应可靠性。最重要的是，一个层次化的智能体系统确保了嵌入CoT的VLM智能体能够有效协作，同时理解任务间的依赖关系，而小组讨论机制则促进了逻辑一致性。为了评估我们的方法，我们引入了SurgCoTBench，这是首个基于推理的数据集，带有结构化的帧级标注。通过全面的实验，我们展示了所提出的SurgRAW相较于基线VLMs在12种机器人手术程序中提升了29.32%的准确率，达到了最先进的性能水平，并推动了可解释、可靠和自主的手术辅助技术的发展。

> Integration of Vision-Language Models (VLMs) in surgical intelligence is hindered by hallucinations, domain knowledge gaps, and limited understanding of task interdependencies within surgical scenes, undermining clinical reliability. While recent VLMs demonstrate strong general reasoning and thinking capabilities, they still lack the domain expertise and task-awareness required for precise surgical scene interpretation. Although Chain-of-Thought (CoT) can structure reasoning more effectively, current approaches rely on self-generated CoT steps, which often exacerbate inherent domain gaps and hallucinations. To overcome this, we present SurgRAW, a CoT-driven multi-agent framework that delivers transparent, interpretable insights for most tasks in robotic-assisted surgery. By employing specialized CoT prompts across five tasks: instrument recognition, action recognition, action prediction, patient data extraction, and outcome assessment, SurgRAW mitigates hallucinations through structured, domain-aware reasoning. Retrieval-Augmented Generation (RAG) is also integrated to external medical knowledge to bridge domain gaps and improve response reliability. Most importantly, a hierarchical agentic system ensures that CoT-embedded VLM agents collaborate effectively while understanding task interdependencies, with a panel discussion mechanism promotes logical consistency. To evaluate our method, we introduce SurgCoTBench, the first reasoning-based dataset with structured frame-level annotations. With comprehensive experiments, we demonstrate the effectiveness of proposed SurgRAW with 29.32% accuracy improvement over baseline VLMs on 12 robotic procedures, achieving the state-of-the-art performance and advancing explainable, trustworthy, and autonomous surgical assistance.

[Arxiv](https://arxiv.org/abs/2503.10265)