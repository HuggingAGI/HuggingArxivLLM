# MedAgentBoard：多智能体协作在医疗任务中的传统方法评测基准

发布时间：2025年05月18日

`LLM应用` `人工智能`

> MedAgentBoard: Benchmarking Multi-Agent Collaboration with Conventional Methods for Diverse Medical Tasks

# 摘要

> 大型语言模型（LLMs）的快速发展激发了利用多智能体协作解决复杂医疗任务的兴趣。然而，多智能体协作方法的实际优势仍不明确。现有评估通常缺乏普适性，未能涵盖反映真实临床实践的多样化任务，且常忽略与基于单个LLM和传统成熟方法的严格对比。

为填补这一关键空白，我们推出了MedAgentBoard，这是一个全面的基准测试，用于系统评估多智能体协作、单个LLM和传统方法。MedAgentBoard涵盖四大类医疗任务：(1) 医疗（视觉）问答，(2) 普及性摘要生成，(3) 结构化电子健康记录（EHR）预测建模，(4) 临床工作流自动化，涉及文本、医学影像和结构化EHR数据。

我们的广泛实验揭示了复杂景象：尽管多智能体协作在特定场景（如提升临床工作流自动化的任务完整性）中具有优势，但它并不始终超越先进的单个LLM（如在文本医疗问答中），更关键的是，它未能超越在医疗VQA和EHR预测等任务中表现更佳的传统专门方法。

MedAgentBoard提供了宝贵资源和实用见解，强调在医学领域选择和发展AI解决方案时，需采取基于任务、循证的方法。它表明，多智能体协作的内在复杂性和开销必须与实际性能提升相权衡。

所有代码、数据集、详细提示和实验结果均可在https://medagentboard.netlify.app/开源获取。

> The rapid advancement of Large Language Models (LLMs) has stimulated interest in multi-agent collaboration for addressing complex medical tasks. However, the practical advantages of multi-agent collaboration approaches remain insufficiently understood. Existing evaluations often lack generalizability, failing to cover diverse tasks reflective of real-world clinical practice, and frequently omit rigorous comparisons against both single-LLM-based and established conventional methods. To address this critical gap, we introduce MedAgentBoard, a comprehensive benchmark for the systematic evaluation of multi-agent collaboration, single-LLM, and conventional approaches. MedAgentBoard encompasses four diverse medical task categories: (1) medical (visual) question answering, (2) lay summary generation, (3) structured Electronic Health Record (EHR) predictive modeling, and (4) clinical workflow automation, across text, medical images, and structured EHR data. Our extensive experiments reveal a nuanced landscape: while multi-agent collaboration demonstrates benefits in specific scenarios, such as enhancing task completeness in clinical workflow automation, it does not consistently outperform advanced single LLMs (e.g., in textual medical QA) or, critically, specialized conventional methods that generally maintain better performance in tasks like medical VQA and EHR-based prediction. MedAgentBoard offers a vital resource and actionable insights, emphasizing the necessity of a task-specific, evidence-based approach to selecting and developing AI solutions in medicine. It underscores that the inherent complexity and overhead of multi-agent collaboration must be carefully weighed against tangible performance gains. All code, datasets, detailed prompts, and experimental results are open-sourced at https://medagentboard.netlify.app/.

[Arxiv](https://arxiv.org/abs/2505.12371)