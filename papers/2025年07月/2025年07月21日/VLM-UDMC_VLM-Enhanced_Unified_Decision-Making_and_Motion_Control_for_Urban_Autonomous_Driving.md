# VLM-UDMC: 基于VLM的增强型城市自动驾驶统一决策与运动控制

发布时间：2025年07月21日

`LLM应用` `自动驾驶`

> VLM-UDMC: VLM-Enhanced Unified Decision-Making and Motion Control for Urban Autonomous Driving

# 摘要

> 场景理解与风险感知是人类驾驶员安全驾驶的关键。为在城市自动驾驶中实现可解释的决策能力，我们提出了一种名为VLM-UDMC的视觉语言模型增强框架。该框架通过上层慢速系统整合场景推理与风险分析，动态优化下游快速系统的运动规划。系统利用实时环境变化，通过上下文势函数进行编码。上层系统采用检索增强生成策略，结合多模态输入与知识检索，生成风险洞察。轻量级LSTM通过提取平滑趋势进行轨迹预测。实验表明，VLM-UDMC有效提升了城市驾驶性能，代码已开源。

> Scene understanding and risk-aware attentions are crucial for human drivers to make safe and effective driving decisions. To imitate this cognitive ability in urban autonomous driving while ensuring the transparency and interpretability, we propose a vision-language model (VLM)-enhanced unified decision-making and motion control framework, named VLM-UDMC. This framework incorporates scene reasoning and risk-aware insights into an upper-level slow system, which dynamically reconfigures the optimal motion planning for the downstream fast system. The reconfiguration is based on real-time environmental changes, which are encoded through context-aware potential functions. More specifically, the upper-level slow system employs a two-step reasoning policy with Retrieval-Augmented Generation (RAG), leveraging foundation models to process multimodal inputs and retrieve contextual knowledge, thereby generating risk-aware insights. Meanwhile, a lightweight multi-kernel decomposed LSTM provides real-time trajectory predictions for heterogeneous traffic participants by extracting smoother trend representations for short-horizon trajectory prediction. The effectiveness of the proposed VLM-UDMC framework is verified via both simulations and real-world experiments with a full-size autonomous vehicle. It is demonstrated that the presented VLM-UDMC effectively leverages scene understanding and attention decomposition for rational driving decisions, thus improving the overall urban driving performance. Our open-source project is available at https://github.com/henryhcliu/vlmudmc.git.

[Arxiv](https://arxiv.org/abs/2507.15266)