# 模型采用何种文化视角？论大型语言模型（LLMs）中的文化定位偏差与智能体缓解

发布时间：2025年09月25日

`Agent` `基础理论`

> Which Cultural Lens Do Models Adopt? On Cultural Positioning Bias and Agentic Mitigation in LLMs

# 摘要

> 大型语言模型（LLMs）已解锁海量下游生成式应用，然而我们发现，这些模型也潜藏着延续文化相关隐性公平问题的风险——它们的生成内容往往锚定美国主流文化视角，却对非主流文化表现出明显的“外部性”。本研究识别并系统探究了这种新型“文化定位偏差”：LLM的默认生成立场会向主流观点倾斜，并将其他文化视为“外来者”。为此，我们提出CultureLens基准——包含4000个生成提示与3个评估指标，通过“文化情境访谈脚本生成”任务量化这种偏差：让LLM扮演现场记者，采访来自10种不同文化的当地人。对5个最先进LLM的实证评估揭示了显著规律：在平均88%以上的美国情境脚本中，模型会使用“局内人”语气；而对弱势文化，却大多以“局外人”姿态呈现，比例严重失衡。为缓解这些偏差，我们提出两种推理时干预方法：一是基于提示的基线方法“公平干预支柱（FIP）”，二是结构化的“公平智能体缓解（MFA）”框架，包含两条流程：（1）MFA-SA（单智能体）：基于公平准则构建“自我反思-重写”循环；（2）MFA-MA（多智能体）：将生成流程拆解为专业化智能体层级——规划智能体（生成初始脚本）、批判智能体（依据公平支柱评估脚本）、优化智能体（整合反馈生成精炼无偏脚本）。实证结果表明，基于智能体的方法能有效缓解生成式LLM的偏差，为该领域提供了极具前景的解决方案。

> Large language models (LLMs) have unlocked a wide range of downstream generative applications. However, we found that they also risk perpetuating subtle fairness issues tied to culture, positioning their generations from the perspectives of the mainstream US culture while demonstrating salient externality towards non-mainstream ones. In this work, we identify and systematically investigate this novel culture positioning bias, in which an LLM's default generative stance aligns with a mainstream view and treats other cultures as outsiders. We propose the CultureLens benchmark with 4000 generation prompts and 3 evaluation metrics for quantifying this bias through the lens of a culturally situated interview script generation task, in which an LLM is positioned as an onsite reporter interviewing local people across 10 diverse cultures. Empirical evaluation on 5 state-of-the-art LLMs reveals a stark pattern: while models adopt insider tones in over 88 percent of US-contexted scripts on average, they disproportionately adopt mainly outsider stances for less dominant cultures. To resolve these biases, we propose 2 inference-time mitigation methods: a baseline prompt-based Fairness Intervention Pillars (FIP) method, and a structured Mitigation via Fairness Agents (MFA) framework consisting of 2 pipelines: (1) MFA-SA (Single-Agent) introduces a self-reflection and rewriting loop based on fairness guidelines. (2) MFA-MA (Multi-Agent) structures the process into a hierarchy of specialized agents: a Planner Agent(initial script generation), a Critique Agent (evaluates initial script against fairness pillars), and a Refinement Agent (incorporates feedback to produce a polished, unbiased script). Empirical results showcase the effectiveness of agent-based methods as a promising direction for mitigating biases in generative LLMs.

[Arxiv](https://arxiv.org/abs/2509.21080)