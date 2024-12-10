# Facade：运用深度上下文异常检测实现高精度的内部威胁检测

发布时间：2024年12月09日

`Agent` `网络安全` `异常检测`

> Facade: High-Precision Insider Threat Detection Using Deep Contextual Anomaly Detection

# 摘要

> 我们推出了 Facade（快速准确的上下文异常检测）：这是一个高精度的基于深度学习的异常检测系统，自 2018 年起就在谷歌（一家大型科技公司）部署，作为抵御内部威胁的最后防线。Facade 是创新的无监督动作上下文系统，通过考量每个动作周边的上下文，涵盖有关用户及其他相关实体的相关事实来检测可疑动作。它基于新的多模态模型构建，该模型以公司文档访问、SQL 查询和 HTTP/RPC 请求日志为训练数据。
  为应对事件数据的稀缺，Facade 采用了一种全新的仅依赖良性数据的对比学习策略。其对历史和隐式社交网络特征的运用，有效处理了在快速变化的公司环境中频繁出现的分布外事件，并在训练后一整年都维持了 Facade 的高精度性能。除核心模型外，Facade 还贡献了一种基于用户和动作嵌入的创新聚类方法，以增强检测的稳健性，实现高精度、多尺度检测。
  在功能方面，Facade 与现有异常检测系统的不同之处在于其高精度。它检测内部攻击者时的误报率极低，低于 0.01%。对于单个恶意动作，比如非法访问敏感文档，误报率低至 0.0003%。据我们所知，Facade 是唯一公开的内部风险异常检测系统，能够保障如此大规模的公司环境安全。

> We present Facade (Fast and Accurate Contextual Anomaly DEtection): a high-precision deep-learning-based anomaly detection system deployed at Google (a large technology company) as the last line of defense against insider threats since 2018. Facade is an innovative unsupervised action-context system that detects suspicious actions by considering the context surrounding each action, including relevant facts about the user and other entities involved. It is built around a new multi-modal model that is trained on corporate document access, SQL query, and HTTP/RPC request logs.
  To overcome the scarcity of incident data, Facade harnesses a novel contrastive learning strategy that relies solely on benign data. Its use of history and implicit social network featurization efficiently handles the frequent out-of-distribution events that occur in a rapidly changing corporate environment, and sustains Facade's high precision performance for a full year after training. Beyond the core model, Facade contributes an innovative clustering approach based on user and action embeddings to improve detection robustness and achieve high precision, multi-scale detection.
  Functionally what sets Facade apart from existing anomaly detection systems is its high precision. It detects insider attackers with an extremely low false positive rate, lower than 0.01%. For single rogue actions, such as the illegitimate access to a sensitive document, the false positive rate is as low as 0.0003%. To the best of our knowledge, Facade is the only published insider risk anomaly detection system that helps secure such a large corporate environment.

[Arxiv](https://arxiv.org/abs/2412.06700)