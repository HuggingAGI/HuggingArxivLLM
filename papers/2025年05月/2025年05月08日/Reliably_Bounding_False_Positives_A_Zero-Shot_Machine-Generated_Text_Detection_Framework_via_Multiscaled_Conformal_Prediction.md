# 可靠控制假阳性：基于多尺度符合性预测的零样本机器生成文本检测框架

发布时间：2025年05月08日

`LLM应用

理由：这篇论文专注于开发检测器来应对大型语言模型被恶意利用的风险，属于实际应用层面的研究。它提出了多尺度符合性预测（MCP）框架和RealDet数据集，旨在提高检测性能和减少误报率，这些都是LLM应用中的重要问题。` `跨领域`

> Reliably Bounding False Positives: A Zero-Shot Machine-Generated Text Detection Framework via Multiscaled Conformal Prediction

# 摘要

> 大型语言模型的快速发展引发了对其可能被恶意利用的广泛关注。为此，开发有效的检测器以缓解这些风险已成为当务之急。然而，现有检测方法大多过分追求检测准确性，却忽视了高误报率（FPR）带来的社会风险。本文采用符合性预测（CP），有效约束了FPR的上限，以此解决这一问题。尽管直接应用CP能够限制FPR，但也导致检测性能显著下降。为克服这一权衡，本文提出了一种基于多尺度符合性预测（MCP）的零样本机器生成文本检测框架，该框架在约束FPR的同时提升了检测性能。此外，本文引入了RealDet，一个涵盖广泛领域的高质量数据集，确保了现实校准，并在与MCP结合时实现了更优的检测性能。实证研究表明，MCP不仅有效约束了FPR，显著提升了检测性能，还增强了在多种检测器和数据集上的对抗攻击鲁棒性。

> The rapid advancement of large language models has raised significant concerns regarding their potential misuse by malicious actors. As a result, developing effective detectors to mitigate these risks has become a critical priority. However, most existing detection methods focus excessively on detection accuracy, often neglecting the societal risks posed by high false positive rates (FPRs). This paper addresses this issue by leveraging Conformal Prediction (CP), which effectively constrains the upper bound of FPRs. While directly applying CP constrains FPRs, it also leads to a significant reduction in detection performance. To overcome this trade-off, this paper proposes a Zero-Shot Machine-Generated Text Detection Framework via Multiscaled Conformal Prediction (MCP), which both enforces the FPR constraint and improves detection performance. This paper also introduces RealDet, a high-quality dataset that spans a wide range of domains, ensuring realistic calibration and enabling superior detection performance when combined with MCP. Empirical evaluations demonstrate that MCP effectively constrains FPRs, significantly enhances detection performance, and increases robustness against adversarial attacks across multiple detectors and datasets.

[Arxiv](https://arxiv.org/abs/2505.05084)