# ChatGPT 遭遇变形攻击检测：多模态大型语言模型与通用视觉模型助力零样本攻击检测

发布时间：2025年03月13日

`LLM应用

论文摘要：人脸识别系统(FRS)日益面临换脸攻击威胁，推动了换脸攻击检测(MAD)算法的开发。然而，现有MAD算法在未见数据上的泛化能力和可解释性不足，这对实际应用环境如注册站和自动边境控制系统构成了挑战。鉴于大多数现有MAD算法依赖监督学习范式，本研究提出了一种基于大型语言模型的零样本学习方法来解决MAD问题。我们设计了两种零样本MAD算法：一种基于通用视觉模型，另一种则基于多模态大型语言模型。对于通用视觉模型，我们通过计算独立支持集的均值支持嵌入来解决MAD任务，且未使用换脸图像。基于LLM的方法采用了GPT-4 Turbo API，并辅以精心设计的提示词。为评估零样本MAD的可行性和所提方法的有效性，我们构建了一个包含多种未见换脸算法的打印-扫描换脸数据集，模拟了具有挑战性的现实应用场景。实验结果表明，我们的检测准确率显著，验证了零样本学习在MAD任务中的适用性。此外，研究发现，多模态大型语言模型如ChatGPT在未训练的MAD任务上展现了出色的泛化能力，并且能够提供解释和指导，这在实际应用中可提升系统的透明度和用户友好性。

LLM应用` `人脸识别`

> ChatGPT Encounters Morphing Attack Detection: Zero-Shot MAD with Multi-Modal Large Language Models and General Vision Models

# 摘要

> 人脸识别系统(FRS)日益面临换脸攻击威胁，推动了换脸攻击检测(MAD)算法的开发。然而，现有MAD算法在未见数据上的泛化能力和可解释性不足，这对实际应用环境如注册站和自动边境控制系统构成了挑战。鉴于大多数现有MAD算法依赖监督学习范式，本研究提出了一种基于大型语言模型的零样本学习方法来解决MAD问题。我们设计了两种零样本MAD算法：一种基于通用视觉模型，另一种则基于多模态大型语言模型。对于通用视觉模型，我们通过计算独立支持集的均值支持嵌入来解决MAD任务，且未使用换脸图像。基于LLM的方法采用了GPT-4 Turbo API，并辅以精心设计的提示词。为评估零样本MAD的可行性和所提方法的有效性，我们构建了一个包含多种未见换脸算法的打印-扫描换脸数据集，模拟了具有挑战性的现实应用场景。实验结果表明，我们的检测准确率显著，验证了零样本学习在MAD任务中的适用性。此外，研究发现，多模态大型语言模型如ChatGPT在未训练的MAD任务上展现了出色的泛化能力，并且能够提供解释和指导，这在实际应用中可提升系统的透明度和用户友好性。

> Face Recognition Systems (FRS) are increasingly vulnerable to face-morphing attacks, prompting the development of Morphing Attack Detection (MAD) algorithms. However, a key challenge in MAD lies in its limited generalizability to unseen data and its lack of explainability-critical for practical application environments such as enrolment stations and automated border control systems. Recognizing that most existing MAD algorithms rely on supervised learning paradigms, this work explores a novel approach to MAD using zero-shot learning leveraged on Large Language Models (LLMs). We propose two types of zero-shot MAD algorithms: one leveraging general vision models and the other utilizing multimodal LLMs. For general vision models, we address the MAD task by computing the mean support embedding of an independent support set without using morphed images. For the LLM-based approach, we employ the state-of-the-art GPT-4 Turbo API with carefully crafted prompts. To evaluate the feasibility of zero-shot MAD and the effectiveness of the proposed methods, we constructed a print-scan morph dataset featuring various unseen morphing algorithms, simulating challenging real-world application scenarios. Experimental results demonstrated notable detection accuracy, validating the applicability of zero-shot learning for MAD tasks. Additionally, our investigation into LLM-based MAD revealed that multimodal LLMs, such as ChatGPT, exhibit remarkable generalizability to untrained MAD tasks. Furthermore, they possess a unique ability to provide explanations and guidance, which can enhance transparency and usability for end-users in practical applications.

[Arxiv](https://arxiv.org/abs/2503.10937)