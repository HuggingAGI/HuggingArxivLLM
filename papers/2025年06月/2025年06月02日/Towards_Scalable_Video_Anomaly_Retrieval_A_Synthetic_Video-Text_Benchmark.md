# 构建可扩展的视频异常检索：合成视频文本基准测试

发布时间：2025年06月02日

`LLM应用` `视频异常检测` `跨模态检索`

> Towards Scalable Video Anomaly Retrieval: A Synthetic Video-Text Benchmark

# 摘要

> # 摘要  
视频异常检索致力于通过自然语言查询定位视频中的异常事件，从而提升公共安全。然而，现有数据集面临两大挑战：一是现实世界异常事件的长尾特性导致数据稀缺，二是隐私限制阻碍了大规模数据收集。为解决这些问题，我们推出了 SVTA（合成视频-文本异常基准数据集），这是首个用于跨模态异常检索的大规模数据集，借助生成模型克服了数据获取难题。  
具体而言，我们利用现成的大型语言模型（LLM）收集并生成涵盖 68 种异常类别的视频描述，如投掷、偷窃和射击等，这些描述全面覆盖了常见的长尾事件。随后，我们利用这些文本引导视频生成模型生成多样且高质量的视频。最终，SVTA 包含 41,315 个视频（136 万帧）及其配对字幕，涵盖 30 种正常活动（如站立、行走和运动）以及 68 种异常事件（如跌倒、打架、盗窃、爆炸和自然灾害）。通过采用三种主流的视频-文本检索基线模型对 SVTA 进行全面测试，我们验证了 SVTA 的挑战性及其在评估跨模态检索方法方面的有效性。SVTA 在保持现实场景的同时，彻底消除了与现实世界异常数据收集相关的隐私风险。数据集演示页面现已开放，访问链接为：[https://svta-mm.github.io/SVTA.github.io/]。

> Video anomaly retrieval aims to localize anomalous events in videos using natural language queries to facilitate public safety. However, existing datasets suffer from severe limitations: (1) data scarcity due to the long-tail nature of real-world anomalies, and (2) privacy constraints that impede large-scale collection. To address the aforementioned issues in one go, we introduce SVTA (Synthetic Video-Text Anomaly benchmark), the first large-scale dataset for cross-modal anomaly retrieval, leveraging generative models to overcome data availability challenges. Specifically, we collect and generate video descriptions via the off-the-shelf LLM (Large Language Model) covering 68 anomaly categories, e.g., throwing, stealing, and shooting. These descriptions encompass common long-tail events. We adopt these texts to guide the video generative model to produce diverse and high-quality videos. Finally, our SVTA involves 41,315 videos (1.36M frames) with paired captions, covering 30 normal activities, e.g., standing, walking, and sports, and 68 anomalous events, e.g., falling, fighting, theft, explosions, and natural disasters. We adopt three widely-used video-text retrieval baselines to comprehensively test our SVTA, revealing SVTA's challenging nature and its effectiveness in evaluating a robust cross-modal retrieval method. SVTA eliminates privacy risks associated with real-world anomaly collection while maintaining realistic scenarios. The dataset demo is available at: [https://svta-mm.github.io/SVTA.github.io/].

[Arxiv](https://arxiv.org/abs/2506.01466)