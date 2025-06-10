# MedChat：基于大型语言模型的多模态诊断多智能体框架

发布时间：2025年06月08日

`Agent`

> MedChat: A Multi-Agent Framework for Multimodal Diagnosis with Large Language Models

# 摘要

> 将基于深度学习的青光眼检测与大型语言模型（LLMs）相结合，提出了一种自动化解决方案，旨在缓解眼科医生短缺问题并提升临床报告效率。然而，将通用LLMs应用于医学成像仍面临挑战，如幻觉、有限的可解释性以及特定领域医学知识不足，这些可能影响临床准确性。尽管结合成像模型与LLM推理的方法改进了报告生成，但它们通常依赖单一的通用型智能体，限制了其在模拟多学科医疗团队多样化推理方面的能力。为了解决这些问题，我们提出了一种名为MedChat的多智能体诊断框架和平台。该平台整合了专门的视觉模型与多个特定角色的LLM智能体，并由协调器智能体统一调度。这种设计不仅提高了可靠性，降低了幻觉风险，还通过一个专为临床审查和教育用途设计的界面实现了交互式诊断报告。代码可在https://github.com/Purdue-M2/MedChat获取。

> The integration of deep learning-based glaucoma detection with large language models (LLMs) presents an automated strategy to mitigate ophthalmologist shortages and improve clinical reporting efficiency. However, applying general LLMs to medical imaging remains challenging due to hallucinations, limited interpretability, and insufficient domain-specific medical knowledge, which can potentially reduce clinical accuracy. Although recent approaches combining imaging models with LLM reasoning have improved reporting, they typically rely on a single generalist agent, restricting their capacity to emulate the diverse and complex reasoning found in multidisciplinary medical teams. To address these limitations, we propose MedChat, a multi-agent diagnostic framework and platform that combines specialized vision models with multiple role-specific LLM agents, all coordinated by a director agent. This design enhances reliability, reduces hallucination risk, and enables interactive diagnostic reporting through an interface tailored for clinical review and educational use. Code available at https://github.com/Purdue-M2/MedChat.

[Arxiv](https://arxiv.org/abs/2506.07400)