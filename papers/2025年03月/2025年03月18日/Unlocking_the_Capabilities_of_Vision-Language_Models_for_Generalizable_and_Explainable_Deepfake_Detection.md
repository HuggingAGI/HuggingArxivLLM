# 释放视觉-语言模型的潜力：实现通用化且可解释的深度伪造检测

发布时间：2025年03月18日

`LLM应用` `深度伪造检测` `多模态学习`

> Unlocking the Capabilities of Vision-Language Models for Generalizable and Explainable Deepfake Detection

# 摘要

> 当前视觉-语言模型（VLMs）在多模态数据理解方面表现卓越，但其在深度伪造检测领域的潜力尚未充分挖掘，主要由于其知识与取证模式的不匹配。为此，我们提出了一种全新的范式，通过三个核心组件释放VLMs的潜力：（1）知识引导的伪造适应模块，利用对比学习与外部操作知识，将VLM的语义空间与取证特征对齐；（2）多模态提示微调框架，联合优化视觉-文本嵌入，实现定位与可解释性；（3）迭代细化策略，支持基于证据推理的多轮对话。我们的框架由基于VLM的知识引导伪造检测器（KFD）、VLM图像编码器和大型语言模型（LLM）组成。图像编码器提取视觉提示嵌入，LLM接收视觉和问题提示嵌入进行推理。KFD通过计算图像特征与原始/深度伪造类嵌入的相关性，实现伪造分类与定位。组件输出用于构建伪造提示嵌入，最终输入LLM生成文本检测响应，辅助判断。在FF++、CDF2、DFD、DFDCP和DFDC等基准数据集上的广泛实验表明，我们的方案不仅超越现有最优方法的泛化性能，还支持多轮对话能力。


> Current vision-language models (VLMs) have demonstrated remarkable capabilities in understanding multimodal data, but their potential remains underexplored for deepfake detection due to the misaligned of their knowledge and forensics patterns. To this end, we present a novel paradigm that unlocks VLMs' potential capabilities through three components: (1) A knowledge-guided forgery adaptation module that aligns VLM's semantic space with forensic features through contrastive learning with external manipulation knowledge; (2) A multi-modal prompt tuning framework that jointly optimizes visual-textual embeddings for both localization and explainability; (3) An iterative refinement strategy enabling multi-turn dialog for evidence-based reasoning. Our framework includes a VLM-based Knowledge-guided Forgery Detector (KFD), a VLM image encoder, and a Large Language Model (LLM). The VLM image encoder extracts visual prompt embeddings from images, while the LLM receives visual and question prompt embeddings for inference. The KFD is used to calculate correlations between image features and pristine/deepfake class embeddings, enabling forgery classification and localization. The outputs from these components are used to construct forgery prompt embeddings. Finally, we feed these prompt embeddings into the LLM to generate textual detection responses to assist judgment. Extensive experiments on multiple benchmarks, including FF++, CDF2, DFD, DFDCP, and DFDC, demonstrate that our scheme surpasses state-of-the-art methods in generalization performance, while also supporting multi-turn dialogue capabilities.

[Arxiv](https://arxiv.org/abs/2503.14853)