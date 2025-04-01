# TeleAntiFraud-28k：一个专注于电信欺诈检测的音频-文本慢思考数据集

发布时间：2025年03月31日

`LLM应用

摘要中提到论文主要讨论了如何利用大型语言模型（LLM）进行数据增强，构建了一个专注于电信诈骗检测的多模态数据集，并应用于实际的反欺诈任务。这属于将LLM应用于特定领域的实际问题，因此归类为LLM应用。` `反欺诈`

> TeleAntiFraud-28k: A Audio-Text Slow-Thinking Dataset for Telecom Fraud Detection

# 摘要

> 电信诈骗的检测因缺乏高质量的多模态训练数据而面临巨大挑战，这些数据需整合音频信号与以推理为导向的文本分析。为填补这一空白，我们推出了TeleAntiFraud-28k——首个专注于自动化电信诈骗分析的开源音频-文本慢思考数据集。该数据集通过以下三种创新策略构建：
1. 基于自动语音识别（ASR）转录通话记录（附带匿名化原始音频），生成隐私保护的文本真实样本，并通过文本到语音（TTS）模型再生确保现实世界一致性；
2. 利用大型语言模型（LLM）对真实ASR输出进行自我指令采样，实现语义增强并扩大场景覆盖范围；
3. 通过预定义沟通场景和诈骗类型，模拟新兴诈骗战术的多智能体对抗合成。

该数据集包含28,511个严格处理的语音-文本对，每条数据均配有详细诈骗推理标注。数据集分为三大任务：场景分类、诈骗检测与诈骗类型分类。此外，我们构建了TeleAntiFraud-Bench——一个从数据集中按比例采样实例的标准评估基准，旨在系统化测试模型在电信诈骗检测任务中的性能表现。我们还开源了生产优化的监督微调（SFT）模型及数据处理框架，支持社区驱动的数据集扩展。这项工作不仅为多模态反欺诈研究奠定了基础框架，还有效应对了数据隐私与场景多样性方面的关键挑战。项目详情请访问：https://github.com/JimmyMa99/TeleAntiFraud（GitHub链接）。


> The detection of telecom fraud faces significant challenges due to the lack of high-quality multimodal training data that integrates audio signals with reasoning-oriented textual analysis. To address this gap, we present TeleAntiFraud-28k, the first open-source audio-text slow-thinking dataset specifically designed for automated telecom fraud analysis. Our dataset is constructed through three strategies: (1) Privacy-preserved text-truth sample generation using automatically speech recognition (ASR)-transcribed call recordings (with anonymized original audio), ensuring real-world consistency through text-to-speech (TTS) model regeneration; (2) Semantic enhancement via large language model (LLM)-based self-instruction sampling on authentic ASR outputs to expand scenario coverage; (3) Multi-agent adversarial synthesis that simulates emerging fraud tactics through predefined communication scenarios and fraud typologies. The generated dataset contains 28,511 rigorously processed speech-text pairs, complete with detailed annotations for fraud reasoning. The dataset is divided into three tasks: scenario classification, fraud detection, fraud type classification. Furthermore, we construct TeleAntiFraud-Bench, a standardized evaluation benchmark comprising proportionally sampled instances from the dataset, to facilitate systematic testing of model performance on telecom fraud detection tasks. We also contribute a production-optimized supervised fine-tuning (SFT) model trained on hybrid real/synthetic data, while open-sourcing the data processing framework to enable community-driven dataset expansion. This work establishes a foundational framework for multimodal anti-fraud research while addressing critical challenges in data privacy and scenario diversity. The project will be released at https://github.com/JimmyMa99/TeleAntiFraud.

[Arxiv](https://arxiv.org/abs/2503.24115)