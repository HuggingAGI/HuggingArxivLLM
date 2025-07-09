# 谁是内鬼？基于LLM的多智能体系统中意图隐藏恶意智能体的建模与识别

发布时间：2025年07月07日

`Agent` `多智能体系统` `系统安全`

> Who's the Mole? Modeling and Detecting Intention-Hiding Malicious Agents in LLM-Based Multi-Agent Systems

# 摘要

> 大型语言模型驱动的多智能体系统 (LLM-MAS) 在协作问题解决方面展现出非凡的能力。然而，尽管 LLM-MAS 具备强大的协作能力，但其通信与协调过程中的安全风险尚未得到充分探索。我们通过系统研究 LLM-MAS 中意图隐藏威胁，填补了这一研究空白，并设计了四种具有代表性的攻击范式，这些攻击能够在保持高度隐蔽性的同时，巧妙地破坏任务完成。我们在集中式、去中心化和分层通信结构中对这些攻击进行了评估。在 MMLU、MMLU-Pro、HumanEval、GSM8K、arithmetic 和 biographies 六个基准数据集上进行的实验表明，这些攻击具有强大的破坏能力。为了识别这些威胁，我们提出了一种基于心理学的检测框架 AgentXposed，该框架结合了 HEXACO 人格模型和 Reid 技术，通过渐进式问卷调查和行为监测来发现恶意行为。在六种攻击类型上的实验表明，我们的检测框架能够有效识别所有类型的恶意行为。针对意图隐藏攻击的检测率略低于两种基线攻击（错误事实注入和暗黑特质注入），这证明了意图隐藏的有效性。我们的研究揭示了意图隐藏攻击带来的结构和行为风险，并从心理学视角为保障基于 LLM 的多智能体系统安全提供了有价值的见解，从而加深了对多智能体安全性的理解。代码和数据可在 https://anonymous.4open.science/r/AgentXposed-F814 获取。

> Multi-agent systems powered by Large Language Models (LLM-MAS) demonstrate remarkable capabilities in collaborative problem-solving. While LLM-MAS exhibit strong collaborative abilities, the security risks in their communication and coordination remain underexplored. We bridge this gap by systematically investigating intention-hiding threats in LLM-MAS, and design four representative attack paradigms that subtly disrupt task completion while maintaining high concealment. These attacks are evaluated in centralized, decentralized, and layered communication structures. Experiments conducted on six benchmark datasets, including MMLU, MMLU-Pro, HumanEval, GSM8K, arithmetic, and biographies, demonstrate that they exhibit strong disruptive capabilities. To identify these threats, we propose a psychology-based detection framework AgentXposed, which combines the HEXACO personality model with the Reid Technique, using progressive questionnaire inquiries and behavior-based monitoring. Experiments conducted on six types of attacks show that our detection framework effectively identifies all types of malicious behaviors. The detection rate for our intention-hiding attacks is slightly lower than that of the two baselines, Incorrect Fact Injection and Dark Traits Injection, demonstrating the effectiveness of intention concealment. Our findings reveal the structural and behavioral risks posed by intention-hiding attacks and offer valuable insights into securing LLM-based multi-agent systems through psychological perspectives, which contributes to a deeper understanding of multi-agent safety. The code and data are available at https://anonymous.4open.science/r/AgentXposed-F814.

[Arxiv](https://arxiv.org/abs/2507.04724)