# 温度与人格塑造LLM代理共识，定性编码中准确度提升有限

发布时间：2025年07月15日

`LLM应用` `社会科学` `市场研究`

> Temperature and Persona Shape LLM Agent Consensus With Minimal Accuracy Gains in Qualitative Coding

# 摘要

> 大型语言模型（LLMs）为大规模定性研究带来了新的可能性，包括编码和数据标注。尽管多智能体系统（MAS）能够模拟人类编码工作流程，但其相较于单智能体编码的优势仍不明确。我们开展了一项实验研究，探讨智能体角色和温度对基于包含8个代码的代码本的对话片段共识构建和编码准确性的影响。我们的开源MAS通过结构化智能体讨论和共识仲裁来模拟演绎式的人类编码。使用六种开源LLMs（参数规模从30亿到320亿）和18种实验配置，我们分析了超过77,000个编码决策，对比了来自在线数学辅导的人类标注转录本的黄金标准数据集。温度对所有六种LLMs是否以及何时达成共识产生了显著影响。相较于统一角色，拥有多个角色（包括中立、自信或共情）的MAS在四分之六的LLMs中显著延迟了共识的达成。在其中三种LLMs中，更高的温度显著减弱了多个角色对共识的影响。然而，温度或角色配对并未带来编码准确性的显著提升。在大多数情况下，单智能体的表现与MAS共识持平或更优。仅有一种模型（OpenHermesV2:7B）和代码类别在温度低于或等于0.5时从MAS商议中获得了高于随机水平的提升，尤其是在智能体中至少包含一个自信角色时。对这些配置下MAS协作的定性分析表明，MAS可能有助于缩小模糊代码的应用范围，从而改进代码本和人机编码。我们对基于LLM的定性方法的局限性提供了新的见解，挑战了多样化MAS角色会带来更好结果的观点。我们开源了我们的MAS和实验代码。

> Large Language Models (LLMs) enable new possibilities for qualitative research at scale, including coding and data annotation. While multi-agent systems (MAS) can emulate human coding workflows, their benefits over single-agent coding remain poorly understood. We conducted an experimental study of how agent persona and temperature shape consensus-building and coding accuracy of dialog segments based on a codebook with 8 codes. Our open-source MAS mirrors deductive human coding through structured agent discussion and consensus arbitration. Using six open-source LLMs (with 3 to 32 billion parameters) and 18 experimental configurations, we analyze over 77,000 coding decisions against a gold-standard dataset of human-annotated transcripts from online math tutoring sessions. Temperature significantly impacted whether and when consensus was reached across all six LLMs. MAS with multiple personas (including neutral, assertive, or empathetic), significantly delayed consensus in four out of six LLMs compared to uniform personas. In three of those LLMs, higher temperatures significantly diminished the effects of multiple personas on consensus. However, neither temperature nor persona pairing lead to robust improvements in coding accuracy. Single agents matched or outperformed MAS consensus in most conditions. Only one model (OpenHermesV2:7B) and code category showed above-chance gains from MAS deliberation when temperature was 0.5 or lower and especially when the agents included at least one assertive persona. Qualitative analysis of MAS collaboration for these configurations suggests that MAS may nonetheless aid in narrowing ambiguous code applications that could improve codebooks and human-AI coding. We contribute new insight into the limits of LLM-based qualitative methods, challenging the notion that diverse MAS personas lead to better outcomes. We open-source our MAS and experimentation code.

[Arxiv](https://arxiv.org/abs/2507.11198)