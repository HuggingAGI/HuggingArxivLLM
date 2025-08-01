# # 基于AI与规则引擎结合的框架实现DICOM脱敏处理，支持可扩展且具备不确定性感知的编辑
本研究提出了一种结合AI与规则引擎的混合框架，用于实现DICOM数据的去识别化，特别适用于需要可扩展性和不确定性感知的编辑场景。

发布时间：2025年07月31日

`LLM应用

论文摘要：医学影像及关联文本数据的访问有望推动医疗研究和患者治疗的重大进展。然而，数字医学影像通信（DICOM）文件中包含的受保护健康信息（PHI）和个人身份信息（PII）对影像数据集的伦理化与安全共享构成了重大障碍。本文介绍了一种由Impact Business Information Solutions（IBIS）开发的混合去识别框架，该框架结合了基于规则和AI驱动的技术，并辅以严格的不确定性量化，以全面去除元数据和像素数据中的PHI/PII信息。

我们的方法始于一个两层的基于规则的系统，旨在识别显性和推断性的元数据元素，并进一步借助经过命名实体识别（NER）微调的大型语言模型（LLM），该模型基于一套模拟真实临床PHI/PII的合成数据集进行训练。针对像素数据，我们采用了一种具备不确定性感知的Faster R-CNN模型，用于定位嵌入式文本，通过光学字符识别（OCR）提取候选PHI，并应用NER管道进行最终的遮盖处理。关键在于，不确定性量化为AI识别提供了置信度衡量，从而增强了自动化可靠性，并支持了基于人工介入的验证流程，以管理剩余风险。

这种不确定性感知的去识别框架在基准数据集和监管标准下表现稳健，包括符合DICOM、HIPAA和TCIA的合规指标。通过结合可扩展的自动化、不确定性量化和严格的品质保证，我们的解决方案有效应对了医疗数据去识别的关键挑战，并支持影像数据的安全、伦理化及可信度释放，以供研究使用。` `数据处理`

> DICOM De-Identification via Hybrid AI and Rule-Based Framework for Scalable, Uncertainty-Aware Redaction

# 摘要

> 医学影像及关联文本数据的访问有望推动医疗研究和患者治疗的重大进展。然而，数字医学影像通信（DICOM）文件中包含的受保护健康信息（PHI）和个人身份信息（PII）对影像数据集的伦理化与安全共享构成了重大障碍。本文介绍了一种由Impact Business Information Solutions（IBIS）开发的混合去识别框架，该框架结合了基于规则和AI驱动的技术，并辅以严格的不确定性量化，以全面去除元数据和像素数据中的PHI/PII信息。

我们的方法始于一个两层的基于规则的系统，旨在识别显性和推断性的元数据元素，并进一步借助经过命名实体识别（NER）微调的大型语言模型（LLM），该模型基于一套模拟真实临床PHI/PII的合成数据集进行训练。针对像素数据，我们采用了一种具备不确定性感知的Faster R-CNN模型，用于定位嵌入式文本，通过光学字符识别（OCR）提取候选PHI，并应用NER管道进行最终的遮盖处理。关键在于，不确定性量化为AI识别提供了置信度衡量，从而增强了自动化可靠性，并支持了基于人工介入的验证流程，以管理剩余风险。

这种不确定性感知的去识别框架在基准数据集和监管标准下表现稳健，包括符合DICOM、HIPAA和TCIA的合规指标。通过结合可扩展的自动化、不确定性量化和严格的品质保证，我们的解决方案有效应对了医疗数据去识别的关键挑战，并支持影像数据的安全、伦理化及可信度释放，以供研究使用。

> Access to medical imaging and associated text data has the potential to drive major advances in healthcare research and patient outcomes. However, the presence of Protected Health Information (PHI) and Personally Identifiable Information (PII) in Digital Imaging and Communications in Medicine (DICOM) files presents a significant barrier to the ethical and secure sharing of imaging datasets. This paper presents a hybrid de-identification framework developed by Impact Business Information Solutions (IBIS) that combines rule-based and AI-driven techniques, and rigorous uncertainty quantification for comprehensive PHI/PII removal from both metadata and pixel data.
  Our approach begins with a two-tiered rule-based system targeting explicit and inferred metadata elements, further augmented by a large language model (LLM) fine-tuned for Named Entity Recognition (NER), and trained on a suite of synthetic datasets simulating realistic clinical PHI/PII. For pixel data, we employ an uncertainty-aware Faster R-CNN model to localize embedded text, extract candidate PHI via Optical Character Recognition (OCR), and apply the NER pipeline for final redaction. Crucially, uncertainty quantification provides confidence measures for AI-based detections to enhance automation reliability and enable informed human-in-the-loop verification to manage residual risks.
  This uncertainty-aware deidentification framework achieves robust performance across benchmark datasets and regulatory standards, including DICOM, HIPAA, and TCIA compliance metrics. By combining scalable automation, uncertainty quantification, and rigorous quality assurance, our solution addresses critical challenges in medical data de-identification and supports the secure, ethical, and trustworthy release of imaging data for research.

[Arxiv](https://arxiv.org/abs/2507.23736)