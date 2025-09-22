# # 布谷鸟攻击：对AI集成开发环境（AI-IDE）的隐蔽持久攻击

发布时间：2025年09月19日

`Agent` `基础理论`

> Cuckoo Attack: Stealthy and Persistent Attacks Against AI-IDE

# 摘要

> 现代AI驱动的集成开发环境（AI-IDEs）日益以智能体为核心架构，深度集成了由LLM驱动的智能体，使其能够自主执行复杂任务。然而，这种深度整合也带来了一个全新且关键的攻击面。攻击者可通过向不可信外部来源注入恶意指令来利用这些组件，进而劫持智能体，使其执行用户意料之外或未察觉的有害操作。这一新兴威胁迅速引发研究关注，催生了多种攻击向量，例如劫持模型上下文协议（MCP）服务器以窃取私人数据。但现有方法大多缺乏隐蔽性和持久性，实际危害有限。
  为此，我们提出“布谷鸟攻击”（Cuckoo Attack）——一种通过在配置文件中植入恶意载荷，实现隐蔽且持久命令执行的新型攻击。这些配置文件是AI-IDEs的常用组件，会在日常操作中自动执行系统命令，且执行细节对用户完全不可见。一旦配置完成，除非出现明显运行时错误，否则极少被用户复查，这为攻击者留下了可乘之机。我们将该攻击范式归纳为初始感染与持久化两个阶段，基于此分析了攻击实施的可行性并明确了核心利用技术。此外，布谷鸟攻击的危害深远：不仅能入侵开发者本地计算机，还可通过配置文件传播引发供应链攻击。我们还为厂商提供了七个可落地的安全检查点，用于评估产品安全性。我们通过端到端概念验证在九个主流智能体与AI-IDE组合上验证了该攻击的有效性，充分证明了这些检查点的必要性。

> Modern AI-powered Integrated Development Environments (AI-IDEs) are increasingly defined by an Agent-centric architecture, where an LLM-powered Agent is deeply integrated to autonomously execute complex tasks. This tight integration, however, also introduces a new and critical attack surface. Attackers can exploit these components by injecting malicious instructions into untrusted external sources, effectively hijacking the Agent to perform harmful operations beyond the user's intention or awareness. This emerging threat has quickly attracted research attention, leading to various proposed attack vectors, such as hijacking Model Context Protocol (MCP) Servers to access private data. However, most existing approaches lack stealth and persistence, limiting their practical impact.
  We propose the Cuckoo Attack, a novel attack that achieves stealthy and persistent command execution by embedding malicious payloads into configuration files. These files, commonly used in AI-IDEs, execute system commands during routine operations, without displaying execution details to the user. Once configured, such files are rarely revisited unless an obvious runtime error occurs, creating a blind spot for attackers to exploit. We formalize our attack paradigm into two stages, including initial infection and persistence. Based on these stages, we analyze the practicality of the attack execution process and identify the relevant exploitation techniques. Furthermore, we analyze the impact of Cuckoo Attack, which can not only invade the developer's local computer but also achieve supply chain attacks through the spread of configuration files. We contribute seven actionable checkpoints for vendors to evaluate their product security. The critical need for these checks is demonstrated by our end-to-end Proof of Concept, which validated the proposed attack across nine mainstream Agent and AI-IDE pairs.

[Arxiv](https://arxiv.org/abs/2509.15572)