# PR攻击：协同提示-RAG攻击通过双层优化实现对大型语言模型中检索增强生成的攻击

发布时间：2025年04月10日

`RAG` `计算机安全`

> PR-Attack: Coordinated Prompt-RAG Attacks on Retrieval-Augmented Generation in Large Language Models via Bilevel Optimization

# 摘要

> 大型语言模型（LLMs）在医学问答、数学科学和代码生成等广泛应用领域中表现出色，但它们也存在知识过时和容易产生幻觉等固有局限性。检索增强生成（RAG）作为一种新兴方法，虽然能有效应对这些问题，但也带来了新的安全漏洞。近期研究开始关注基于RAG的LLMs安全性，但现有攻击方法仍面临三大挑战：（1）毒化文本注入量受限时，攻击效果大幅下降；（2）攻击行为缺乏隐蔽性，容易被异常检测系统发现；（3）依赖启发式方法生成毒化文本，缺乏理论保障和优化框架，限制了其实际应用效果。为解决这些问题，我们提出了协调的Prompt-RAG攻击（PR-attack），这是一种基于优化的新型攻击方法。通过在知识库中注入少量毒化文本，并在提示中嵌入后门触发器，当触发器被激活时，LLM会对特定查询生成预设响应，同时保持其他场景下的正常行为。这确保了攻击的高有效性和高隐蔽性。我们采用双层优化框架，将攻击生成过程建模为一个优化问题，以开发最优的毒化文本和触发器。实验结果表明，PR-Attack在多种LLMs和数据集上表现出色，即使毒化文本数量有限，也能实现高攻击成功率，且隐蔽性显著优于现有方法。

> Large Language Models (LLMs) have demonstrated remarkable performance across a wide range of applications, e.g., medical question-answering, mathematical sciences, and code generation. However, they also exhibit inherent limitations, such as outdated knowledge and susceptibility to hallucinations. Retrieval-Augmented Generation (RAG) has emerged as a promising paradigm to address these issues, but it also introduces new vulnerabilities. Recent efforts have focused on the security of RAG-based LLMs, yet existing attack methods face three critical challenges: (1) their effectiveness declines sharply when only a limited number of poisoned texts can be injected into the knowledge database, (2) they lack sufficient stealth, as the attacks are often detectable by anomaly detection systems, which compromises their effectiveness, and (3) they rely on heuristic approaches to generate poisoned texts, lacking formal optimization frameworks and theoretic guarantees, which limits their effectiveness and applicability. To address these issues, we propose coordinated Prompt-RAG attack (PR-attack), a novel optimization-driven attack that introduces a small number of poisoned texts into the knowledge database while embedding a backdoor trigger within the prompt. When activated, the trigger causes the LLM to generate pre-designed responses to targeted queries, while maintaining normal behavior in other contexts. This ensures both high effectiveness and stealth. We formulate the attack generation process as a bilevel optimization problem leveraging a principled optimization framework to develop optimal poisoned texts and triggers. Extensive experiments across diverse LLMs and datasets demonstrate the effectiveness of PR-Attack, achieving a high attack success rate even with a limited number of poisoned texts and significantly improved stealth compared to existing methods.

[Arxiv](https://arxiv.org/abs/2504.07717)