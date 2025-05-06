# AI代理或许名不虚传，但资源投入尚不值得（至少目前如此）：法律与新闻领域三种语言对的机器翻译质量与成本的初步探索

发布时间：2025年05月02日

`LLM应用` `机器翻译`

> AI agents may be worth the hype but not the resources (yet): An initial exploration of machine translation quality and costs in three language pairs in the legal and news domains

# 摘要

> 大型语言模型（LLMs）和多智能体编排被视为机器翻译（MT）领域的重大突破，但它们相对于传统神经机器翻译（NMT）的实际优势仍不明确。本文通过实证研究对此进行了检验。

我们选取了五种代表性范式进行对比：Google Translate（强大的NMT基线）、GPT-4o（通用型LLM）、o1-preview（增强推理的LLM），以及两种基于GPT-4o的智能体工作流（顺序三阶段和迭代改进）。测试数据来自法律合同和新闻散文，涵盖西班牙语、加泰罗尼亚语和土耳其语三种语言对英语的翻译任务。

在自动评估方面，我们采用了COMET、BLEU、chrF2和TER等指标；人工评估则通过专家对翻译质量的充分性和流畅性进行评分；效率评估基于输入加输出总令牌数，并参照2025年4月的定价标准。

结果显示，成熟的NMT系统在十二项指标-语言组合中排名第一；o1-preview在大多数情况下紧随其后，而两种多智能体工作流的表现相对落后。然而，人工评估揭示了不同维度的价值：o1-preview在六项比较中的五项中提供了最优质输出，迭代智能体则在一次比较中领先，表明其推理能力能够捕捉到传统指标所忽视的语义细微差别。

尽管如此，这些质的提升伴随着显著的成本代价。顺序智能体的令牌消耗约为NMT或单次LLM的五倍，而迭代智能体则高达十五倍。

我们建议采用多维度、成本敏感的评估方法，并强调以下研究方向可能带来突破：优化协调策略、选择性智能体激活以及结合单次LLMs与针对性智能体干预的混合流水线。

> Large language models (LLMs) and multi-agent orchestration are touted as the next leap in machine translation (MT), but their benefits relative to conventional neural MT (NMT) remain unclear. This paper offers an empirical reality check. We benchmark five paradigms, Google Translate (strong NMT baseline), GPT-4o (general-purpose LLM), o1-preview (reasoning-enhanced LLM), and two GPT-4o-powered agentic workflows (sequential three-stage and iterative refinement), on test data drawn from a legal contract and news prose in three English-source pairs: Spanish, Catalan and Turkish. Automatic evaluation is performed with COMET, BLEU, chrF2 and TER; human evaluation is conducted with expert ratings of adequacy and fluency; efficiency with total input-plus-output token counts mapped to April 2025 pricing.
  Automatic scores still favour the mature NMT system, which ranks first in seven of twelve metric-language combinations; o1-preview ties or places second in most remaining cases, while both multi-agent workflows trail. Human evaluation reverses part of this narrative: o1-preview produces the most adequate and fluent output in five of six comparisons, and the iterative agent edges ahead once, indicating that reasoning layers capture semantic nuance undervalued by surface metrics. Yet these qualitative gains carry steep costs. The sequential agent consumes roughly five times, and the iterative agent fifteen times, the tokens used by NMT or single-pass LLMs.
  We advocate multidimensional, cost-aware evaluation protocols and highlight research directions that could tip the balance: leaner coordination strategies, selective agent activation, and hybrid pipelines combining single-pass LLMs with targeted agent intervention.

[Arxiv](https://arxiv.org/abs/2505.01560)