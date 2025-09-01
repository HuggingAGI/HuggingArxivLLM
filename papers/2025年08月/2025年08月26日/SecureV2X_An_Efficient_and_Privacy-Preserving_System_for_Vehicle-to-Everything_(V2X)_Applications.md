# SecureV2X：适用于车与万物（V2X）应用的高效隐私保护系统

发布时间：2025年08月26日

`Agent` `交通运输`

> SecureV2X: An Efficient and Privacy-Preserving System for Vehicle-to-Everything (V2X) Applications

# 摘要

> 过去十年，自动驾驶与V2X技术迅猛发展，显著提升了现代交通的安全性与效率。这些系统通过与庞大的车辆网络、路边基础设施及云资源交互，为自身的机器学习能力提供支持。然而，机器学习在V2X系统中的普及应用，也带来了相关数据的隐私隐患。这一问题在智能交通和驾驶员安全应用中尤为突出——这些应用可能会隐性泄露用户位置，或直接暴露脑电图信号等医疗数据。为解决上述问题，我们提出了SecureV2X——一个可扩展的多智能体系统，能够在服务器与车辆间部署安全的神经网络推理。基于该系统，我们研究了两类多智能体V2X应用：安全睡意检测与安全闯红灯检测。该系统不仅性能优于现有基线，还能高效扩展，同时支持大量安全计算交互。例如，在睡意检测任务中，与其他安全系统相比，SecureV2X的速度提升【数学公式】倍，计算轮次减少【数学公式】倍，通信量降低【数学公式】倍。此外，在闯红灯检测的目标识别任务中，其运行速度较当前最先进的基准快近【数学公式】倍。

> Autonomous driving and V2X technologies have developed rapidly in the past decade, leading to improved safety and efficiency in modern transportation. These systems interact with extensive networks of vehicles, roadside infrastructure, and cloud resources to support their machine learning capabilities. However, the widespread use of machine learning in V2X systems raises issues over the privacy of the data involved. This is particularly concerning for smart-transit and driver safety applications which can implicitly reveal user locations or explicitly disclose medical data such as EEG signals. To resolve these issues, we propose SecureV2X, a scalable, multi-agent system for secure neural network inferences deployed between the server and each vehicle. Under this setting, we study two multi-agent V2X applications: secure drowsiness detection, and secure red-light violation detection. Our system achieves strong performance relative to baselines, and scales efficiently to support a large number of secure computation interactions simultaneously. For instance, SecureV2X is $9.4 \times$ faster, requires $143\times$ fewer computational rounds, and involves $16.6\times$ less communication on drowsiness detection compared to other secure systems. Moreover, it achieves a runtime nearly $100\times$ faster than state-of-the-art benchmarks in object detection tasks for red light violation detection.

[Arxiv](https://arxiv.org/abs/2508.19115)