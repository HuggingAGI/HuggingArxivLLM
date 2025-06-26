# # 使用量子梯度下降增强防篡改大型语言模型中的生物安全

发布时间：2025年06月23日

`LLM应用` `生物医学`

> Enhancing Biosecurity in Tamper-Resistant Large Language Models With Quantum Gradient Descent

# 摘要

> 本文提出了一种针对医疗应用的大型语言模型（LLMs）防篡改框架，该框架采用量子梯度下降（QGD）技术实时检测恶意参数篡改。通过将其集成到LLaMA模型中，QGD能够有效监控权重幅度分布，识别对抗微调过程中的异常行为。实验结果表明，在MIMIC和eICU数据集上，该方法对模型性能的影响微乎其微（准确率仅从89.1降至88.3），同时具备 robust 的篡改检测能力。此外，PubMedQA评估证实了该框架在生物医学问答任务中的有效性。与选择性遗忘和密码指纹等传统方法相比，QGD在检测细微权重变化方面表现更为灵敏。这种量子启发的创新方法不仅为医疗AI提供了更高的安全性和可靠性，还为其他高风险领域的应用开辟了新的可能性。

> This paper introduces a tamper-resistant framework for large language models (LLMs) in medical applications, utilizing quantum gradient descent (QGD) to detect malicious parameter modifications in real time. Integrated into a LLaMA-based model, QGD monitors weight amplitude distributions, identifying adversarial fine-tuning anomalies. Tests on the MIMIC and eICU datasets show minimal performance impact (accuracy: 89.1 to 88.3 on MIMIC) while robustly detecting tampering. PubMedQA evaluations confirm preserved biomedical question-answering capabilities. Compared to baselines like selective unlearning and cryptographic fingerprinting, QGD offers superior sensitivity to subtle weight changes. This quantum-inspired approach ensures secure, reliable medical AI, extensible to other high-stakes domains.

[Arxiv](https://arxiv.org/abs/2506.19086)