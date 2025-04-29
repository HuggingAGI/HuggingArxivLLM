# $	exttt{SAGE}$: 一个用于大语言模型安全评估的通用框架

发布时间：2025年04月28日

`LLM应用`

> $\texttt{SAGE}$: A Generic Framework for LLM Safety Evaluation

# 摘要

> # 摘要  
大型语言模型（LLMs）的安全评估虽然取得了进展并吸引了学术界的关注，但仍面临诸多挑战，尤其是在LLMs快速应用于各类场景时。不同应用场景下用户可能面临多样化的潜在风险，因此需要针对具体应用进行定制化的安全评估，包括特定的危害类型和管理策略。另一个重要挑战是现有方法对LLM系统动态性与对话本质关注不足，这种忽视可能导致潜在风险在标准安全评估中被遗漏。  
本文将以上问题列为构建稳健LLM安全评估体系的关键要求。鉴于现有评估方法难以满足这些需求，我们提出了$	exttt{SAGE}$（安全AI通用评估）框架。$	exttt{SAGE}$是一个自动化模块化平台，专为定制化和动态风险评估设计。它采用系统感知且具有独特个性的对抗性用户模型，实现全面的红队评估。通过在三个应用场景和危害政策下评估七种先进LLMs，我们验证了$	exttt{SAGE}$的有效性。  
实验结果表明，多轮对话评估中危害随对话长度增加而稳步上升。此外，模型在面对不同用户个性和场景时表现出显著差异。研究还发现，部分模型通过采用可能削弱其实用性的极端拒绝策略来减少有害输出。这些发现凸显了自适应和场景化测试的重要性，以确保LLMs在实际应用中实现更安全的部署与更好的安全性对齐。

> Safety evaluation of Large Language Models (LLMs) has made progress and attracted academic interest, but it remains challenging to keep pace with the rapid integration of LLMs across diverse applications. Different applications expose users to various harms, necessitating application-specific safety evaluations with tailored harms and policies. Another major gap is the lack of focus on the dynamic and conversational nature of LLM systems. Such potential oversights can lead to harms that go unnoticed in standard safety benchmarks. This paper identifies the above as key requirements for robust LLM safety evaluation and recognizing that current evaluation methodologies do not satisfy these, we introduce the $\texttt{SAGE}$ (Safety AI Generic Evaluation) framework. $\texttt{SAGE}$ is an automated modular framework designed for customized and dynamic harm evaluations. It utilizes adversarial user models that are system-aware and have unique personalities, enabling a holistic red-teaming evaluation. We demonstrate $\texttt{SAGE}$'s effectiveness by evaluating seven state-of-the-art LLMs across three applications and harm policies. Our experiments with multi-turn conversational evaluations revealed a concerning finding that harm steadily increases with conversation length. Furthermore, we observe significant disparities in model behavior when exposed to different user personalities and scenarios. Our findings also reveal that some models minimize harmful outputs by employing severe refusal tactics that can hinder their usefulness. These insights highlight the necessity of adaptive and context-specific testing to ensure better safety alignment and safer deployment of LLMs in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2504.19674)