# # SafeAuto: 知识增强型安全自动驾驶系统，采用多模态基础模型实现

发布时间：2025年02月28日

`LLM应用` `自动驾驶` `人工智能`

> SafeAuto: Knowledge-Enhanced Safe Autonomous Driving with Multimodal Foundation Models

# 摘要

> 传统自动驾驶系统在整合高层推理与底层控制方面表现乏力，常常导致次优甚至不安全的驾驶行为。多模态大语言模型（MLLMs）的出现带来了转机，其视觉和文本数据处理能力为统一感知与推理任务提供了一体化解决方案。然而，如何将精确的安全知识嵌入MLLMs以实现安全自动驾驶仍是一项重大挑战。

我们提出了SafeAuto框架，通过整合非结构化与结构化知识，显著提升了MLLM驱动的自动驾驶系统性能。具体而言，我们创新性地引入了位置相关交叉熵（PDCE）损失函数，有效提升了文本表示下的底层控制信号预测精度。为确保安全驾驶，我们开发了SafeAuto推理组件，将驾驶安全法规转化为一阶逻辑规则（如"红灯 => 停止"），并融入马尔可夫逻辑网络（MLN）等概率图模型。该组件通过环境属性识别模型（如红灯检测）提取环境特征，验证预测动作，构建谓词系统。

此外，我们构建了多模态RAG模型，整合视频数据、控制信号与环境属性，实现从历史驾驶经验中的高效学习。通过PDCE、MLN与多模态RAG的协同优化，SafeAuto在多个数据集上显著超越现有基线。这一突破推动了更精确、可靠和安全的自动驾驶系统发展，使系统能够从经验中学习、遵守交通法规并执行精准控制动作。


> Traditional autonomous driving systems often struggle to integrate high-level reasoning with low-level control, resulting in suboptimal and sometimes unsafe driving behaviors. The emergence of Multimodal Large Language Models (MLLMs), which can process both visual and textual data, presents an opportunity to unify perception and reasoning tasks within a single framework. However, effectively embedding precise safety knowledge into MLLMs for autonomous driving remains a significant challenge. To address this, we propose SafeAuto, a novel framework that enhances MLLM-based autonomous driving systems by incorporating both unstructured and structured knowledge. Specifically, we first introduce the Position-Dependent Cross-Entropy (PDCE) loss function, designed to improve the accuracy of low-level control signal predictions when numerical values are represented as text. Second, to ensure safe autonomous driving by explicitly integrating precise safety knowledge into the MLLM, we develop a reasoning component for SafeAuto. This component translates driving safety regulations into first-order logic rules (e.g., "red light => stop") and incorporates these rules into a probabilistic graphical model, such as a Markov Logic Network (MLN). The MLN is trained to verify the predicted next actions using environmental attributes identified by attribute recognition models (e.g., detecting a red light) to form the predicates. Additionally, we construct a Multimodal RAG model that leverages video data, control signals, and environmental attributes to learn more effectively from past similar driving experiences. By integrating PDCE, MLN, and Multimodal RAG, SafeAuto significantly outperforms existing baselines across multiple datasets. This advancement enables more accurate, reliable, and safer autonomous driving systems that learn from experience, obey traffic laws, and perform precise control actions.

[Arxiv](https://arxiv.org/abs/2503.00211)