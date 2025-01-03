# SPADE：利用生成式AI与结构化提示工程，提升自适应网络欺骗策略

发布时间：2025年01月01日

`LLM应用

理由：该论文主要探讨了利用生成式AI（GenAI）模型，特别是LLMs（如ChatGPT-4o、Gemini等），通过结构化提示工程（PE）自动生成自适应网络欺骗策略，以应对现代恶意软件的威胁。研究重点在于如何利用LLMs提升网络欺骗策略的相关性、可操作性和可部署性，并提出了SPADE框架来解决LLMs在自适应欺骗中的挑战。因此，该论文属于LLM在网络安全领域的应用研究，应归类为LLM应用。` `网络安全` `恶意软件防御`

> SPADE: Enhancing Adaptive Cyber Deception Strategies with Generative AI and Structured Prompt Engineering

# 摘要

> 现代恶意软件的迅猛发展给有效防御机制的开发带来了巨大挑战。传统网络欺骗技术依赖静态或手动配置的参数，难以应对动态且复杂的威胁。本研究利用生成式AI（GenAI）模型，通过结构化提示工程（PE）自动生成自适应网络欺骗策略，提升其相关性、可操作性和可部署性。我们提出了SPADE框架，以解决LLMs在自适应欺骗中的固有挑战，如通用输出、模糊性、上下文信息利用不足和可扩展性问题。通过召回率、精确匹配（EM）、BLEU分数和专家评估等指标，ChatGPT-4o在多种恶意软件场景中表现最佳，且以最小改进实现了93%的参与度和96%的准确率。Gemini和ChatGPT-4o Mini表现不俗，Llama3.2虽需优化，但也展现出潜力。这些发现揭示了GenAI在自动化可扩展、自适应欺骗策略中的变革潜力，并凸显了结构化PE在推动网络安全应用中的关键作用。

> The rapid evolution of modern malware presents significant challenges to the development of effective defense mechanisms. Traditional cyber deception techniques often rely on static or manually configured parameters, limiting their adaptability to dynamic and sophisticated threats. This study leverages Generative AI (GenAI) models to automate the creation of adaptive cyber deception ploys, focusing on structured prompt engineering (PE) to enhance relevance, actionability, and deployability. We introduce a systematic framework (SPADE) to address inherent challenges large language models (LLMs) pose to adaptive deceptions, including generalized outputs, ambiguity, under-utilization of contextual information, and scalability constraints. Evaluations across diverse malware scenarios using metrics such as Recall, Exact Match (EM), BLEU Score, and expert quality assessments identified ChatGPT-4o as the top performer. Additionally, it achieved high engagement (93%) and accuracy (96%) with minimal refinements. Gemini and ChatGPT-4o Mini demonstrated competitive performance, with Llama3.2 showing promise despite requiring further optimization. These findings highlight the transformative potential of GenAI in automating scalable, adaptive deception strategies and underscore the critical role of structured PE in advancing real-world cybersecurity applications.

[Arxiv](https://arxiv.org/abs/2501.00940)