# # 面向POI推荐的地理感知型大型语言模型

发布时间：2025年05月17日

`LLM应用` `地理信息系统` `位置服务`

> Geography-Aware Large Language Models for Next POI Recommendation

# 摘要

> 兴趣点（POI）推荐任务旨在根据用户的移动历史数据预测其下一个目的地，在基于位置的服务和个性化应用中发挥着关键作用。准确的下一个 POI 推荐依赖于有效地建模地理信息和 POI 转换关系，这对于捕捉空间依赖性和用户移动模式至关重要。尽管大型语言模型（LLMs）在语义理解和上下文推理方面表现出强大的能力，但将其应用于空间任务如下一个 POI 推荐仍然具有挑战性。首先，特定 GPS 坐标的低频性质使得 LLMs 难以建模精确的空间上下文。其次，缺乏关于 POI 转换的知识限制了它们捕捉潜在 POI-POI 关系的能力。为了解决这些问题，我们提出了 GA-LLM（地理感知大型语言模型），一个增强 LLMs 的新框架，配备两个专门组件。地理坐标注入模块（GCIM）使用层次和基于傅里叶的位置编码将 GPS 坐标转换为空间表示，使模型能够从多个角度理解地理特征。POI 对齐模块（PAM）将 POI 转换关系纳入 LLM 的语义空间，使其能够推断全局 POI 关系并推广到未见过的 POI。在三个真实世界数据集上的实验展示了 GA-LLM 的最新性能。

> The next Point-of-Interest (POI) recommendation task aims to predict users' next destinations based on their historical movement data and plays a key role in location-based services and personalized applications. Accurate next POI recommendation depends on effectively modeling geographic information and POI transition relations, which are crucial for capturing spatial dependencies and user movement patterns. While Large Language Models (LLMs) exhibit strong capabilities in semantic understanding and contextual reasoning, applying them to spatial tasks like next POI recommendation remains challenging. First, the infrequent nature of specific GPS coordinates makes it difficult for LLMs to model precise spatial contexts. Second, the lack of knowledge about POI transitions limits their ability to capture potential POI-POI relationships. To address these issues, we propose GA-LLM (Geography-Aware Large Language Model), a novel framework that enhances LLMs with two specialized components. The Geographic Coordinate Injection Module (GCIM) transforms GPS coordinates into spatial representations using hierarchical and Fourier-based positional encoding, enabling the model to understand geographic features from multiple perspectives. The POI Alignment Module (PAM) incorporates POI transition relations into the LLM's semantic space, allowing it to infer global POI relationships and generalize to unseen POIs. Experiments on three real-world datasets demonstrate the state-of-the-art performance of GA-LLM.

[Arxiv](https://arxiv.org/abs/2505.13526)