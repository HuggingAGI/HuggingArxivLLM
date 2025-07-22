# WebGuard：为网络智能体构建通用保护机制

发布时间：2025年07月18日

`LLM应用` `网络安全` `网络行为分析`

> WebGuard: Building a Generalizable Guardrail for Web Agents

# 摘要

> 大型语言模型（LLMs）驱动的自主网络代理在提升效率的同时，也带来了非预期或有害行动的风险。为应对这一挑战，我们推出了WebGuard，这是首个专注于网络代理行为风险评估的数据集，旨在支持护栏模型的开发。WebGuard包含来自193个网站、涵盖22个领域的4,939个人工标注行为，采用SAFE、LOW和HIGH的三级风险分类体系。初步评估显示，前沿LLMs在行为结果预测和HIGH风险行为召回上表现不足，凸显了开发防护措施的必要性。通过微调Qwen2.5VL-7B模型，我们在准确率和召回率上取得了显著提升，但距离高可靠性部署仍有差距。

> The rapid development of autonomous web agents powered by Large Language Models (LLMs), while greatly elevating efficiency, exposes the frontier risk of taking unintended or harmful actions. This situation underscores an urgent need for effective safety measures, akin to access controls for human users. To address this critical challenge, we introduce WebGuard, the first comprehensive dataset designed to support the assessment of web agent action risks and facilitate the development of guardrails for real-world online environments. In doing so, WebGuard specifically focuses on predicting the outcome of state-changing actions and contains 4,939 human-annotated actions from 193 websites across 22 diverse domains, including often-overlooked long-tail websites. These actions are categorized using a novel three-tier risk schema: SAFE, LOW, and HIGH. The dataset includes designated training and test splits to support evaluation under diverse generalization settings. Our initial evaluations reveal a concerning deficiency: even frontier LLMs achieve less than 60% accuracy in predicting action outcomes and less than 60% recall in lagging HIGH-risk actions, highlighting the risks of deploying current-generation agents without dedicated safeguards. We therefore investigate fine-tuning specialized guardrail models using WebGuard. We conduct comprehensive evaluations across multiple generalization settings and find that a fine-tuned Qwen2.5VL-7B model yields a substantial improvement in performance, boosting accuracy from 37% to 80% and HIGH-risk action recall from 20% to 76%. Despite these improvements, the performance still falls short of the reliability required for high-stakes deployment, where guardrails must approach near-perfect accuracy and recall.

[Arxiv](https://arxiv.org/abs/2507.14293)