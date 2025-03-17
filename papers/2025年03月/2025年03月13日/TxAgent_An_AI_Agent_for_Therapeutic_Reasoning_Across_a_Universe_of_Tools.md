# # TxAgent: 横跨工具的治疗推理AI代理

发布时间：2025年03月13日

`Agent` `人工智能`

> TxAgent: An AI Agent for Therapeutic Reasoning Across a Universe of Tools

# 摘要

> 精准治疗需要多模态自适应模型来生成个性化的治疗建议。我们介绍了TxAgent，一个AI代理，它利用多步推理和实时生物医学知识检索，在一个包含211种工具的工具箱中分析药物相互作用、禁忌症和患者特定的治疗策略。TxAgent评估药物在分子、药代动力学和临床水平上的相互作用，基于患者的合并症和正在服用的药物识别禁忌症，并根据患者的个体特征定制治疗策略。它从多个生物医学来源检索和综合证据，评估药物与患者状况之间的相互作用，并通过迭代推理来完善治疗建议。它根据任务目标选择工具，并执行结构化的函数调用来解决需要临床推理和跨来源验证的治疗任务。工具宇宙整合了来自可信来源的211种工具，包括自1939年以来所有FDA批准的药物以及Open Targets验证的临床见解。TxAgent在五个新的基准测试中优于领先的LLMs、工具使用模型和推理代理：DrugPC、BrandPC、GenericPC、TreatmentPC和DescriptionPC，涵盖了3,168个药物推理任务和456个个性化治疗场景。它在开放式的药物推理任务中达到了92.1%的准确率，超越了GPT-4o，并在结构化的多步推理中优于DeepSeek-R1（671B）。TxAgent能够推广到药物名称变体和描述。通过整合多步推理、实时知识 grounding 和工具辅助决策，TxAgent确保治疗建议与既定的临床指南和真实世界证据相一致，从而降低不良事件的风险并改善治疗决策。

> Precision therapeutics require multimodal adaptive models that generate personalized treatment recommendations. We introduce TxAgent, an AI agent that leverages multi-step reasoning and real-time biomedical knowledge retrieval across a toolbox of 211 tools to analyze drug interactions, contraindications, and patient-specific treatment strategies. TxAgent evaluates how drugs interact at molecular, pharmacokinetic, and clinical levels, identifies contraindications based on patient comorbidities and concurrent medications, and tailors treatment strategies to individual patient characteristics. It retrieves and synthesizes evidence from multiple biomedical sources, assesses interactions between drugs and patient conditions, and refines treatment recommendations through iterative reasoning. It selects tools based on task objectives and executes structured function calls to solve therapeutic tasks that require clinical reasoning and cross-source validation. The ToolUniverse consolidates 211 tools from trusted sources, including all US FDA-approved drugs since 1939 and validated clinical insights from Open Targets. TxAgent outperforms leading LLMs, tool-use models, and reasoning agents across five new benchmarks: DrugPC, BrandPC, GenericPC, TreatmentPC, and DescriptionPC, covering 3,168 drug reasoning tasks and 456 personalized treatment scenarios. It achieves 92.1% accuracy in open-ended drug reasoning tasks, surpassing GPT-4o and outperforming DeepSeek-R1 (671B) in structured multi-step reasoning. TxAgent generalizes across drug name variants and descriptions. By integrating multi-step inference, real-time knowledge grounding, and tool-assisted decision-making, TxAgent ensures that treatment recommendations align with established clinical guidelines and real-world evidence, reducing the risk of adverse events and improving therapeutic decision-making.

[Arxiv](https://arxiv.org/abs/2503.10970)