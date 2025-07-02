# # 安全移动：多模态移动智能体的链式级别越狱检测与自动化评估

发布时间：2025年07月01日

`Agent` `智能体系统` `信息安全`

> SafeMobile: Chain-level Jailbreak Detection and Automated Evaluation for Multimodal Mobile Agents

# 摘要

> 多模态基础模型在智能体系统中的广泛应用，推动了移动设备控制、智能助手交互及多模态任务执行等场景的智能化发展，这些场景逐渐依赖于大型模型驱动的智能体。然而，随之而来的越狱风险日益凸显。攻击者可能通过特定输入诱导智能体绕过原有行为约束，触发修改设置、执行未经授权的命令或冒充用户身份等风险敏感操作，给系统安全带来新的挑战。现有安全防护措施在处理复杂交互时仍存在局限性，尤其是在跨多轮对话或任务序列的潜在风险行为检测方面。此外，目前还缺乏一种高效且一致的自动化方法来辅助评估和判定此类风险的影响。本研究聚焦于移动多模态智能体的安全问题，尝试通过引入行为序列信息构建风险甄别机制，并基于大型语言模型设计了自动化辅助评估方案。通过在多个具有代表性的高风险任务中进行初步验证，结果显示该方法能在一定程度上提升对风险行为的识别能力，并有助于降低智能体被越狱的概率。我们希望这项研究能够为多模态智能体系统的安全风险建模与防护提供有价值的参考。


> With the wide application of multimodal foundation models in intelligent agent systems, scenarios such as mobile device control, intelligent assistant interaction, and multimodal task execution are gradually relying on such large model-driven agents. However, the related systems are also increasingly exposed to potential jailbreak risks. Attackers may induce the agents to bypass the original behavioral constraints through specific inputs, and then trigger certain risky and sensitive operations, such as modifying settings, executing unauthorized commands, or impersonating user identities, which brings new challenges to system security. Existing security measures for intelligent agents still have limitations when facing complex interactions, especially in detecting potentially risky behaviors across multiple rounds of conversations or sequences of tasks. In addition, an efficient and consistent automated methodology to assist in assessing and determining the impact of such risks is currently lacking. This work explores the security issues surrounding mobile multimodal agents, attempts to construct a risk discrimination mechanism by incorporating behavioral sequence information, and designs an automated assisted assessment scheme based on a large language model. Through preliminary validation in several representative high-risk tasks, the results show that the method can improve the recognition of risky behaviors to some extent and assist in reducing the probability of agents being jailbroken. We hope that this study can provide some valuable references for the security risk modeling and protection of multimodal intelligent agent systems.

[Arxiv](https://arxiv.org/abs/2507.00841)