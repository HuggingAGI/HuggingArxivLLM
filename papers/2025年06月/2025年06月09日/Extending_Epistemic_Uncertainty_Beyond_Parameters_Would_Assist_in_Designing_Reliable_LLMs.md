# 将知识不确定性研究拓展到参数之外，有助于打造更可靠的大型语言模型。

发布时间：2025年06月09日

`LLM理论` `可靠性工程` `风险管理`

> Extending Epistemic Uncertainty Beyond Parameters Would Assist in Designing Reliable LLMs

# 摘要

> 尽管大型语言模型（LLMs）高度交互且可扩展，但目前确保模型部署可靠性的方法仍主要局限于拒绝高不确定性输出以避免错误信息传播。这种保守策略反映出我们缺乏系统化区分和应对不同不确定性来源的工具。本文提倡采用贝叶斯实验建模框架——一个为推理不确定性并明确其可减少性提供连贯基础的框架——来主动管理和应对LLM部署中的不确定性。该框架使LLMs及其用户能够采取情境化适当的措施，如请求澄清、检索外部信息或优化输入。通过支持主动解决而非被动规避，它为构建更可靠、透明且广泛应用的LLM系统铺平了道路，特别是在高风险的现实场景中。

> Although large language models (LLMs) are highly interactive and extendable, current approaches to ensure reliability in deployments remain mostly limited to rejecting outputs with high uncertainty in order to avoid misinformation. This conservative strategy reflects the current lack of tools to systematically distinguish and respond to different sources of uncertainty. In this paper, we advocate for the adoption of Bayesian Modeling of Experiments -- a framework that provides a coherent foundation to reason about uncertainty and clarify the reducibility of uncertainty -- for managing and proactively addressing uncertainty that arises in LLM deployments. This framework enables LLMs and their users to take contextually appropriate steps, such as requesting clarification, retrieving external information, or refining inputs. By supporting active resolution rather than passive avoidance, it opens the door to more reliable, transparent, and broadly applicable LLM systems, particularly in high-stakes, real-world settings.

[Arxiv](https://arxiv.org/abs/2506.07448)