# # 多模态推理助力对话诊断 AI 的发展

发布时间：2025年05月06日

`LLM应用` `多模态数据处理`

> Advancing Conversational Diagnostic AI with Multimodal Reasoning

# 摘要

> 大型语言模型（LLMs）在诊断对话中展现出巨大潜力，但现有评估主要局限于纯语言交互，与远程医疗的实际需求仍有差距。即时通讯平台让医患双方能在诊疗中无缝共享和讨论多模态医疗数据，但LLMs在保持专业诊断对话属性的同时处理这些数据的能力尚不明确。我们通过赋予Articulate Medical Intelligence Explorer（AMIE）收集、解释多模态数据并在咨询中精准推理的新能力，显著提升了其诊断对话与管理表现。借助Gemini 2.0 Flash，我们的系统构建了一个基于状态的对话框架，其中对话流程由反映患者状态和诊断演化的中间模型输出动态调整。后续问题基于患者状态的不确定性进行战略性引导，形成一个更有条理的多模态病史采集过程，其结构与经验丰富的临床医生的问诊方式相似。我们在一项随机、盲法、基于聊天的OSCE风格研究中将AMIE与全科医生（PCPs）进行了对比，研究对象为患者演员。我们使用智能手机皮肤照片、心电图和临床文档PDF等多模态数据构建了105个评估场景，涵盖多种疾病和人口统计学特征。我们的评估标准不仅考察了多模态能力，还包括病史采集、诊断准确性、管理推理、沟通和同理心等临床相关维度。专家评估显示，AMIE在9个多模态维度中的7个和32个非多模态维度中的29个（包括诊断准确性）表现优于PCPs。结果表明，多模态对话诊断AI取得了显著进展，但距离临床实际应用仍需进一步研究。

> Large Language Models (LLMs) have demonstrated great potential for conducting diagnostic conversations but evaluation has been largely limited to language-only interactions, deviating from the real-world requirements of remote care delivery. Instant messaging platforms permit clinicians and patients to upload and discuss multimodal medical artifacts seamlessly in medical consultation, but the ability of LLMs to reason over such data while preserving other attributes of competent diagnostic conversation remains unknown. Here we advance the conversational diagnosis and management performance of the Articulate Medical Intelligence Explorer (AMIE) through a new capability to gather and interpret multimodal data, and reason about this precisely during consultations. Leveraging Gemini 2.0 Flash, our system implements a state-aware dialogue framework, where conversation flow is dynamically controlled by intermediate model outputs reflecting patient states and evolving diagnoses. Follow-up questions are strategically directed by uncertainty in such patient states, leading to a more structured multimodal history-taking process that emulates experienced clinicians. We compared AMIE to primary care physicians (PCPs) in a randomized, blinded, OSCE-style study of chat-based consultations with patient actors. We constructed 105 evaluation scenarios using artifacts like smartphone skin photos, ECGs, and PDFs of clinical documents across diverse conditions and demographics. Our rubric assessed multimodal capabilities and other clinically meaningful axes like history-taking, diagnostic accuracy, management reasoning, communication, and empathy. Specialist evaluation showed AMIE to be superior to PCPs on 7/9 multimodal and 29/32 non-multimodal axes (including diagnostic accuracy). The results show clear progress in multimodal conversational diagnostic AI, but real-world translation needs further research.

[Arxiv](https://arxiv.org/abs/2505.04653)