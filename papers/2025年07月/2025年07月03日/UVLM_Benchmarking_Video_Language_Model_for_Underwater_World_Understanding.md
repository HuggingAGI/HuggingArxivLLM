# UVLM：视频语言模型在水下世界理解中的基准测试

发布时间：2025年07月03日

`LLM应用` `海洋科学` `计算机视觉`

> UVLM: Benchmarking Video Language Model for Underwater World Understanding

# 摘要

> 近期，大型语言模型（LLMs）的突破性进展对人工智能领域产生了深远影响。基于LLMs的众多先进应用已在多个场景中崭露头角。其中，视频语言模型（VidLMs）的应用尤为广泛。然而，现有研究主要集中在陆地场景，忽视了水下观测这一亟需关注的领域。为填补这一空白，我们推出了UVLM，一个通过结合人类专业知识与AI模型构建的水下观测基准。为确保数据质量，我们从多角度进行了深入考量。首先，为应对水下环境的独特挑战，我们选取了涵盖光线变化、水体浑浊及多角度观测等典型水下挑战的视频来构建数据集。其次，为确保数据多样性，该数据集涵盖了广泛的帧率、分辨率、419类海洋生物以及多种静态植物和地形。接下来，为实现任务多样性，我们采用了结构化设计，将观测目标分为两大类：生物类与环境类。每类下又细分为内容观测与变化/动作观测，总计20种不同任务类型。最后，我们设计了若干具有挑战性的评估指标，以便对不同方法进行定量比较与分析。在两个代表性VidLMs上的实验表明，基于UVLM对VidLMs进行微调可显著提升对水下世界的理解能力，同时在现有空中学界VidLM基准（如VideoMME和Perception text）上也展现出小幅提升的潜力。该数据集及提示工程将公开发布。

> Recently, the remarkable success of large language models (LLMs) has achieved a profound impact on the field of artificial intelligence. Numerous advanced works based on LLMs have been proposed and applied in various scenarios. Among them, video language models (VidLMs) are particularly widely used. However, existing works primarily focus on terrestrial scenarios, overlooking the highly demanding application needs of underwater observation. To overcome this gap, we introduce UVLM, an under water observation benchmark which is build through a collaborative approach combining human expertise and AI models. To ensure data quality, we have conducted in-depth considerations from multiple perspectives. First, to address the unique challenges of underwater environments, we selected videos that represent typical underwater challenges including light variations, water turbidity, and diverse viewing angles to construct the dataset. Second, to ensure data diversity, the dataset covers a wide range of frame rates, resolutions, 419 classes of marine animals, and various static plants and terrains. Next, for task diversity, we adopted a structured design where observation targets are categorized into two major classes: biological and environmental. Each category includes content observation and change/action observation, totaling 20 distinct task types. Finally, we designed several challenging evaluation metrics to enable quantitative comparison and analysis of different methods. Experiments on two representative VidLMs demonstrate that fine-tuning VidLMs on UVLM significantly improves underwater world understanding while also showing potential for slight improvements on existing in-air VidLM benchmarks, such as VideoMME and Perception text. The dataset and prompt engineering will be released publicly.

[Arxiv](https://arxiv.org/abs/2507.02373)