# 医学图像去识别基准挑战赛

发布时间：2025年07月31日

`其他

理由：这篇论文主要探讨医学图像的去标识化技术，特别是如何在符合患者隐私法规的同时保留非 PHI 元数据，以支持成像 AI 的开发。虽然论文中提到了参与者使用了大型语言模型 (LLM) 作为工具之一，但论文的核心内容是关于去标识化方法的设计、实施和评估，而不是专注于 LLM 的应用或理论。因此，这篇论文更适合归类到其他类别。` `隐私保护`

> Medical Image De-Identification Benchmark Challenge

# 摘要

> 受保护健康信息 (PHI) 和个人身份信息 (PII) 的去标识化是共享医学图像的基本要求，特别是通过公共存储库进行共享，以确保符合患者隐私法规。同时，在生物医学研究中，保留非 PHI 元数据以支持成像人工智能 (AI) 的开发也至关重要。MIDI-B 的目标是基于 HIPAA 安全港法规、DICOM 属性保密配置文件以及癌症影像档案 (TCIA) 定义的研究关键元数据保留最佳实践，提供一个标准化的 DICOM 图像去标识化工具基准测试平台。该挑战赛采用了一套大型、多样化、多中心和多模式的真实去标识化放射图像，其中插入了合成 PHI/PII。MIDI-B 挑战赛分为三个阶段：训练、验证和测试。共有 80 人注册参加挑战。在训练阶段，参与者可以使用其内部或公共数据调整算法。验证和测试阶段使用了包含合成标识符的 DICOM 图像（分别来自 216 和 322 名受试者）。最终，10 个团队成功完成了挑战的测试阶段。通过计算正确动作数量占所需总动作数量的百分比，我们评估了基于规则的图像去标识化方法的成功率。得分范围从 97.91% 到 99.93%。参与者使用了多种工具，包括开源和专有工具、大型语言模型以及光学字符识别 (OCR)，并进行了定制配置。本文将全面报告 MIDI-B 挑战赛的设计、实施、结果和经验教训。

> The de-identification (deID) of protected health information (PHI) and personally identifiable information (PII) is a fundamental requirement for sharing medical images, particularly through public repositories, to ensure compliance with patient privacy laws. In addition, preservation of non-PHI metadata to inform and enable downstream development of imaging artificial intelligence (AI) is an important consideration in biomedical research. The goal of MIDI-B was to provide a standardized platform for benchmarking of DICOM image deID tools based on a set of rules conformant to the HIPAA Safe Harbor regulation, the DICOM Attribute Confidentiality Profiles, and best practices in preservation of research-critical metadata, as defined by The Cancer Imaging Archive (TCIA). The challenge employed a large, diverse, multi-center, and multi-modality set of real de-identified radiology images with synthetic PHI/PII inserted.
  The MIDI-B Challenge consisted of three phases: training, validation, and test. Eighty individuals registered for the challenge. In the training phase, we encouraged participants to tune their algorithms using their in-house or public data. The validation and test phases utilized the DICOM images containing synthetic identifiers (of 216 and 322 subjects, respectively). Ten teams successfully completed the test phase of the challenge. To measure success of a rule-based approach to image deID, scores were computed as the percentage of correct actions from the total number of required actions. The scores ranged from 97.91% to 99.93%. Participants employed a variety of open-source and proprietary tools with customized configurations, large language models, and optical character recognition (OCR). In this paper we provide a comprehensive report on the MIDI-B Challenge's design, implementation, results, and lessons learned.

[Arxiv](https://arxiv.org/abs/2507.23608)