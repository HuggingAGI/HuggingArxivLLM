# DeRAGEC：通过合成理由去噪命名实体候选，用于ASR错误修正

发布时间：2025年06月09日

`LLM应用` `语音识别`

> DeRAGEC: Denoising Named Entity Candidates with Synthetic Rationale for ASR Error Correction

# 摘要

> 我们提出了 DeRAGEC，一种用于提升自动语音识别 (ASR) 系统中命名实体 (NE) 纠正效果的方法。该方法通过扩展基于检索增强的生成式错误纠正 (RAGEC) 框架，引入合成去噪理由在纠正前过滤噪声命名实体候选项。借助音素相似性和增强定义，DeRAGEC 利用上下文学习精炼噪声检索到的 NE，且无需额外训练。在 CommonVoice 和 STOP 数据集上的实验结果表明，DeRAGEC 在词错误率 (WER) 和 NE 击中率方面均显著优于基线 ASR 和 RAGEC 方法。具体而言，与未进行后处理的 ASR 相比，我们实现了 28% 的相对词错误率降低。我们的源代码可在以下链接获取：https://github.com/solee0022/deragec

> We present DeRAGEC, a method for improving Named Entity (NE) correction in Automatic Speech Recognition (ASR) systems. By extending the Retrieval-Augmented Generative Error Correction (RAGEC) framework, DeRAGEC employs synthetic denoising rationales to filter out noisy NE candidates before correction. By leveraging phonetic similarity and augmented definitions, it refines noisy retrieved NEs using in-context learning, requiring no additional training. Experimental results on CommonVoice and STOP datasets show significant improvements in Word Error Rate (WER) and NE hit ratio, outperforming baseline ASR and RAGEC methods. Specifically, we achieved a 28% relative reduction in WER compared to ASR without postprocessing. Our source code is publicly available at: https://github.com/solee0022/deragec

[Arxiv](https://arxiv.org/abs/2506.07510)