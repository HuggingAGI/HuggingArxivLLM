# 输出反哺训练数据：噪声到意义的循环与形式化RSI触发机制

发布时间：2025年05月05日

`Agent` `人工智能`

> When Your Own Output Becomes Your Training Data: Noise-to-Meaning Loops and a Formal RSI Trigger

# 摘要

> 我们提出了一种名为噪声到意义的递归自我改进（N2M-RSI）的极简形式模型，展示了当AI代理实现输出作为输入的自我反馈并跨越信息整合阈值时，在我们的假设下，其内部复杂度将无限增长。该框架整合了自我提示的大型语言模型、哥德尔自我指涉和AutoML等先前概念，同时保持与具体实现无关。此外，该模型可自然扩展至相互作用的智能体群体，预示着在允许实例间通信时可能出现的超线性效应。出于安全考虑，我们未公开系统特定的实现细节，仅在附录C中发布了简短的、与模型无关的玩具原型。

> We present Noise-to-Meaning Recursive Self-Improvement (N2M-RSI), a minimal formal model showing that once an AI agent feeds its own outputs back as inputs and crosses an explicit information-integration threshold, its internal complexity will grow without bound under our assumptions. The framework unifies earlier ideas on self-prompting large language models, Gödelian self-reference, and AutoML, yet remains implementation-agnostic. The model furthermore scales naturally to interacting swarms of agents, hinting at super-linear effects once communication among instances is permitted. For safety reasons, we omit system-specific implementation details and release only a brief, model-agnostic toy prototype in Appendix C.

[Arxiv](https://arxiv.org/abs/2505.02888)