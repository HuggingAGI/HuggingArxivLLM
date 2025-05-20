# MedAgentBoard：通过传统方法评估多智能体协作在多样化医疗任务中的基准性能

发布时间：2025年05月18日

`Agent` `医疗AI`

> MedAgentBoard: Benchmarking Multi-Agent Collaboration with Conventional Methods for Diverse Medical Tasks

# 摘要

> 大型语言模型（LLMs）的快速发展引发了人们对多智能体协作在解决复杂医疗任务中的广泛关注。然而，多智能体协作的实际优势仍不明确。现有评估通常缺乏普适性，未能涵盖真实临床实践中的多样化任务，且常忽略与基于单一LLM和传统方法的严格对比。为填补这一空白，我们推出MedAgentBoard，一个全面的基准测试，用于系统性评估多智能体协作、单一LLM和传统方法。MedAgentBoard涵盖四个医疗任务类别：（1）医学问答，（2）非专业摘要生成，（3）结构化电子健康记录（EHR）预测建模，（4）临床工作流程自动化，涉及文本、医学影像和结构化EHR数据。我们的实验揭示：多智能体协作在特定场景（如临床工作流程自动化）中具有优势，但在文本医学问答中未超越先进单一LLMs，尤其在医学视觉问答和EHR预测中，传统方法表现更优。MedAgentBoard提供重要资源和见解，强调在医疗AI开发中需采取任务特定、基于证据的方法，并谨慎权衡多智能体协作的复杂性与性能提升。所有资源均可在https://medagentboard.netlify.app/获取。

> The rapid advancement of Large Language Models (LLMs) has stimulated interest in multi-agent collaboration for addressing complex medical tasks. However, the practical advantages of multi-agent collaboration approaches remain insufficiently understood. Existing evaluations often lack generalizability, failing to cover diverse tasks reflective of real-world clinical practice, and frequently omit rigorous comparisons against both single-LLM-based and established conventional methods. To address this critical gap, we introduce MedAgentBoard, a comprehensive benchmark for the systematic evaluation of multi-agent collaboration, single-LLM, and conventional approaches. MedAgentBoard encompasses four diverse medical task categories: (1) medical (visual) question answering, (2) lay summary generation, (3) structured Electronic Health Record (EHR) predictive modeling, and (4) clinical workflow automation, across text, medical images, and structured EHR data. Our extensive experiments reveal a nuanced landscape: while multi-agent collaboration demonstrates benefits in specific scenarios, such as enhancing task completeness in clinical workflow automation, it does not consistently outperform advanced single LLMs (e.g., in textual medical QA) or, critically, specialized conventional methods that generally maintain better performance in tasks like medical VQA and EHR-based prediction. MedAgentBoard offers a vital resource and actionable insights, emphasizing the necessity of a task-specific, evidence-based approach to selecting and developing AI solutions in medicine. It underscores that the inherent complexity and overhead of multi-agent collaboration must be carefully weighed against tangible performance gains. All code, datasets, detailed prompts, and experimental results are open-sourced at https://medagentboard.netlify.app/.

[Arxiv](https://arxiv.org/abs/2505.12371)