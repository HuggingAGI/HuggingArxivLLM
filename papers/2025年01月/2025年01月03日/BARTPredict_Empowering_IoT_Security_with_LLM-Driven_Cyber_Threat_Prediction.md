# BARTPredict：利用LLM驱动的网络威胁预测，提升物联网安全

发布时间：2025年01月03日

`LLM应用

**理由**：该论文提出了一种基于预训练大型语言模型（LLMs）的入侵预测框架，用于主动预测并预先缓解恶意活动。该框架整合了两个LLMs（BART和BERT），并应用于物联网（IoT）网络安全领域。这属于将LLM技术应用于特定领域（网络安全）的实际问题解决，因此归类为“LLM应用”。` `物联网` `网络安全`

> BARTPredict: Empowering IoT Security with LLM-Driven Cyber Threat Prediction

# 摘要

> 物联网（IoT）技术的广泛应用虽然推动了运营效率的提升，但也带来了新的网络安全威胁，近期针对IoT设备的网络攻击便是明证。传统的入侵检测系统多为被动响应，依赖于网络中的特定模式或异常触发。为应对这一挑战，本研究提出了一种主动预测并预先缓解恶意活动的方法，旨在防患于未然。本文创新性地提出了一种基于预训练大型语言模型（LLMs）的入侵预测框架。该框架整合了两个LLMs：一个用于预测网络流量的微调BART模型，以及一个用于评估预测流量的微调BERT模型。通过BART的双向能力，框架能够从预测中识别恶意数据包。基于CICIoT2023 IoT攻击数据集的评估显示，该框架在预测性能上取得了显著提升，整体准确率高达98%，为IoT网络的网络安全挑战提供了强有力的解决方案。

> The integration of Internet of Things (IoT) technology in various domains has led to operational advancements, but it has also introduced new vulnerabilities to cybersecurity threats, as evidenced by recent widespread cyberattacks on IoT devices. Intrusion detection systems are often reactive, triggered by specific patterns or anomalies observed within the network. To address this challenge, this work proposes a proactive approach to anticipate and preemptively mitigate malicious activities, aiming to prevent potential damage before it occurs. This paper proposes an innovative intrusion prediction framework empowered by Pre-trained Large Language Models (LLMs). The framework incorporates two LLMs: a fine-tuned Bidirectional and AutoRegressive Transformers (BART) model for predicting network traffic and a fine-tuned Bidirectional Encoder Representations from Transformers (BERT) model for evaluating the predicted traffic. By harnessing the bidirectional capabilities of BART the framework then identifies malicious packets among these predictions. Evaluated using the CICIoT2023 IoT attack dataset, our framework showcases a notable enhancement in predictive performance, attaining an impressive 98% overall accuracy, providing a powerful response to the cybersecurity challenges that confront IoT networks.

[Arxiv](https://arxiv.org/abs/2501.01664)