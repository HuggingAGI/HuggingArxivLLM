# LLMs 尚无法可靠判断？：对 LLM 作为评估者稳健性的全面评估

发布时间：2025年06月11日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在评估和测试系统中的应用，特别是通过RobustJudge框架来增强其鲁棒性和安全性。它属于应用层面的研究，专注于LLMs的实际应用和优化。` `模型测试` `安全评估`

> LLMs Cannot Reliably Judge (Yet?): A Comprehensive Assessment on the Robustness of LLM-as-a-Judge

# 摘要

> 大型语言模型（LLMs）在各类任务中展现出的强大能力，推动了自动模型测试系统（如红队测试和基准测试）的广泛应用。然而，这些系统在面对对抗攻击时仍显脆弱，评估结果可能被操纵，这引发了人们对系统可靠性的担忧。现有评估方法缺乏系统性框架，且在实际应用中的表现未得到充分验证。为此，我们提出了一种全新的自动化框架——RobustJudge，专注于系统性评估LLM-as-a-Judge系统的鲁棒性。该框架从三个维度展开研究：攻击与防御机制的影响（RQ1）、提示模板与模型选择的优化（RQ2）、以及实际应用中的鲁棒性评估（RQ3）。我们的研究发现：（1）LLM-as-a-Judge系统仍易受多种攻击（如Combined Attack和PAIR）影响，但重新分词和基于LLM的检测器能有效提升防御能力；（2）系统鲁棒性对提示模板和评估模型的选择高度敏感，我们提出的优化方法可显著提升鲁棒性，开源模型JudgeLM-13B表现尤为突出；（3）在阿里巴巴PAI平台的实际应用中，RobustJudge发现了此前未被披露的安全漏洞。RobustJudge的源代码现已开源，地址为https://github.com/S3IC-Lab/RobustJudge。

> Large Language Models (LLMs) have demonstrated remarkable intelligence across various tasks, which has inspired the development and widespread adoption of LLM-as-a-Judge systems for automated model testing, such as red teaming and benchmarking. However, these systems are susceptible to adversarial attacks that can manipulate evaluation outcomes, raising concerns about their robustness and, consequently, their trustworthiness. Existing evaluation methods adopted by LLM-based judges are often piecemeal and lack a unified framework for comprehensive assessment. Furthermore, prompt template and model selections for improving judge robustness have been rarely explored, and their performance in real-world settings remains largely unverified. To address these gaps, we introduce RobustJudge, a fully automated and scalable framework designed to systematically evaluate the robustness of LLM-as-a-Judge systems. RobustJudge investigates the impact of attack methods and defense strategies (RQ1), explores the influence of prompt template and model selection (RQ2), and assesses the robustness of real-world LLM-as-a-Judge applications (RQ3).Our main findings are: (1) LLM-as-a-Judge systems are still vulnerable to a range of adversarial attacks, including Combined Attack and PAIR, while defense mechanisms such as Re-tokenization and LLM-based Detectors offer improved protection; (2) Robustness is highly sensitive to the choice of prompt template and judge models. Our proposed prompt template optimization method can improve robustness, and JudgeLM-13B demonstrates strong performance as a robust open-source judge; (3) Applying RobustJudge to Alibaba's PAI platform reveals previously unreported vulnerabilities. The source code of RobustJudge is provided at https://github.com/S3IC-Lab/RobustJudge.

[Arxiv](https://arxiv.org/abs/2506.09443)