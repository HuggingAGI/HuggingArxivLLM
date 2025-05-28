# # 基于 LLMs 的 eHMI 动作设计自动化，助力自动驾驶车辆通信
通过 LLMs 实现 eHMI 动作设计的自动化，推动自动驾驶车辆通信技术的发展。

发布时间：2025年05月27日

`LLM应用` `自动驾驶`

> Automating eHMI Action Design with LLMs for Automated Vehicle Communication

# 摘要

> 自动驾驶车辆 (AVs) 与其它道路使用者之间缺乏明确的通信渠道，在不确定的场景下必须借助外部人机界面 (eHMIs) 来有效传递信息。目前，大多数 eHMI 研究采用预设的文本信息和人工设计的动作来执行这些信息传递任务，这限制了 eHMIs 在现实世界中的部署，因为在动态场景中适应性至关重要。鉴于大型语言模型 (LLMs) 的通用性和灵活性，它们可能可以作为消息-动作设计任务中的自动化动作设计师。为此，我们做出了以下贡献：(1) 提出了一种将 LLMs 与 3D 渲染器相结合的流水线，使用 LLMs 作为动作设计师来生成可执行的动作，用于控制 eHMIs 和渲染动作片段。(2) 收集了一个用户评分的动作设计评分数据集，包含 8 种预设信息和 4 种代表性 eHMI 模态的总共 320 条动作序列。数据集验证了 LLMs 可以将预设信息转化为接近人类水平的动作，特别是对于具备推理能力的 LLMs。(3) 引入了两个自动化评分器，动作参考分数 (ARS) 和视觉-语言模型 (VLMs)，对 18 种 LLMs 进行基准测试，发现 VLM 与人类偏好一致，但在不同 eHMI 模态上存在差异。

> The absence of explicit communication channels between automated vehicles (AVs) and other road users requires the use of external Human-Machine Interfaces (eHMIs) to convey messages effectively in uncertain scenarios. Currently, most eHMI studies employ predefined text messages and manually designed actions to perform these messages, which limits the real-world deployment of eHMIs, where adaptability in dynamic scenarios is essential. Given the generalizability and versatility of large language models (LLMs), they could potentially serve as automated action designers for the message-action design task. To validate this idea, we make three contributions: (1) We propose a pipeline that integrates LLMs and 3D renderers, using LLMs as action designers to generate executable actions for controlling eHMIs and rendering action clips. (2) We collect a user-rated Action-Design Scoring dataset comprising a total of 320 action sequences for eight intended messages and four representative eHMI modalities. The dataset validates that LLMs can translate intended messages into actions close to a human level, particularly for reasoning-enabled LLMs. (3) We introduce two automated raters, Action Reference Score (ARS) and Vision-Language Models (VLMs), to benchmark 18 LLMs, finding that the VLM aligns with human preferences yet varies across eHMI modalities.

[Arxiv](https://arxiv.org/abs/2505.20711)