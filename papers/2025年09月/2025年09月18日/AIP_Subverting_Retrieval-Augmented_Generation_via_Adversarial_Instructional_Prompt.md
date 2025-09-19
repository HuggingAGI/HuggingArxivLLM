# AIP：借助对抗性指令提示颠覆检索增强生成

发布时间：2025年09月18日

`RAG` `基础理论`

> AIP: Subverting Retrieval-Augmented Generation via Adversarial Instructional Prompt

# 摘要

> 检索增强生成（RAG）技术通过从外部数据源检索相关文档来增强大型语言模型（LLMs）的能力，从而提升其事实准确性和可验证性。但这种依赖也在检索流程中埋下了新的安全隐患，这一风险超出了LLM本身。尽管以往的RAG攻击已暴露过类似漏洞，但它们大多依赖操纵用户查询——而由于用户输入通常是固定或受保护的，这种方式在实际中往往难以实施。这种局限让我们忽略了一个更现实、更隐蔽的攻击入口：指令提示。这些提示被广泛复用、公开传播，却极少经过安全审计。这种默认的信任让它们成了攻击者隐蔽操纵RAG行为的绝佳目标。
  为此，我们提出了一种全新的对抗性指令提示（AIP）攻击——通过利用恶意指令提示，巧妙改变检索行为，从而操纵RAG的输出结果。AIP将攻击重心转向指令提示，暴露出那些看似无害却被信任的界面组件，是如何被“武器化”来破坏系统完整性的。该攻击设定了三大目标：（1）自然性——能躲过用户的察觉；（2）实用性——促使这些提示被广泛使用；（3）鲁棒性——在各种查询变体中都能发挥作用。我们设计了一种多样化查询生成策略，模拟用户查询中真实的语言差异，从而找到那些能在不同释义和改写中都生效的提示。在此基础上，我们开发了基于遗传算法的联合优化模型，通过平衡攻击成功率、良性任务实用性和隐蔽性，不断“进化”出更优的对抗性提示。实验结果显示，AIP在保持良性功能不受影响的前提下，攻击成功率（ASR）最高可达95.23%。这些发现揭露了RAG系统中一个此前被忽视的重大漏洞，也提醒我们必须重新审视那些被广泛共享的指令提示。

> Retrieval-Augmented Generation (RAG) enhances large language models (LLMs) by retrieving relevant documents from external sources to improve factual accuracy and verifiability. However, this reliance introduces new attack surfaces within the retrieval pipeline, beyond the LLM itself. While prior RAG attacks have exposed such vulnerabilities, they largely rely on manipulating user queries, which is often infeasible in practice due to fixed or protected user inputs. This narrow focus overlooks a more realistic and stealthy vector: instructional prompts, which are widely reused, publicly shared, and rarely audited. Their implicit trust makes them a compelling target for adversaries to manipulate RAG behavior covertly.
  We introduce a novel attack for Adversarial Instructional Prompt (AIP) that exploits adversarial instructional prompts to manipulate RAG outputs by subtly altering retrieval behavior. By shifting the attack surface to the instructional prompts, AIP reveals how trusted yet seemingly benign interface components can be weaponized to degrade system integrity. The attack is crafted to achieve three goals: (1) naturalness, to evade user detection; (2) utility, to encourage use of prompts; and (3) robustness, to remain effective across diverse query variations. We propose a diverse query generation strategy that simulates realistic linguistic variation in user queries, enabling the discovery of prompts that generalize across paraphrases and rephrasings. Building on this, a genetic algorithm-based joint optimization is developed to evolve adversarial prompts by balancing attack success, clean-task utility, and stealthiness. Experimental results show that AIP achieves up to 95.23% ASR while preserving benign functionality. These findings uncover a critical and previously overlooked vulnerability in RAG systems, emphasizing the need to reassess the shared instructional prompts.

[Arxiv](https://arxiv.org/abs/2509.15159)