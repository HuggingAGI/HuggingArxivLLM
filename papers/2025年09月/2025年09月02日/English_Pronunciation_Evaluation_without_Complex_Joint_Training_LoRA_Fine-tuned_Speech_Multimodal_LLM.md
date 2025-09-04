# 无需复杂联合训练的英语发音评估：LoRA微调的语音多模态大语言模型

发布时间：2025年09月02日

`LLM应用` `教育科技`

> English Pronunciation Evaluation without Complex Joint Training: LoRA Fine-tuned Speech Multimodal LLM

# 摘要

> 本研究证实，通过低秩适应（LoRA）适配的多模态大型语言模型（MLLM）可同时完成自动发音评估（APA）与发音错误检测诊断（MDD）两项任务。基于微软Phi-4-multimodal-instruct模型，我们的微调方法省去了传统上这些不同任务所需的复杂架构调整或单独训练流程。在Speechocean762数据集上微调后，模型预测的发音评估分数与人工评分高度相关（皮尔逊相关系数PCC > 0.7），且词错误率（WER）和音素错误率（PER）均较低（均<0.15）。值得关注的是，仅微调LoRA层便能达到与微调所有音频层相当的性能。研究表明，无需全量微调大型多模态模型即可构建集成发音评估系统，相比以往同时处理APA和MDD的联合模型，本方法训练过程显著简化。这种高效的LoRA适配方案为英语第二语言学习者带来了更易获取、集成化且高效的计算机辅助发音训练（CAPT）技术。

> This study demonstrates that a Multimodal Large Language Model (MLLM) adapted via Low-Rank Adaptation (LoRA) can perform both Automatic Pronunciation Assessment (APA) and Mispronunciation Detection and Diagnosis (MDD) simultaneously. Leveraging Microsoft's Phi-4-multimodal-instruct, our fine-tuning method eliminates the need for complex architectural changes or separate training procedures conventionally required for these distinct tasks. Fine-tuned on the Speechocean762 dataset, the pronunciation evaluation scores predicted by the model exhibited a strong Pearson Correlation Coefficient (PCC > 0.7) with human-assigned scores, while achieving low Word Error Rate (WER) and Phoneme Error Rate (PER) (both < 0.15). Notably, fine-tuning only the LoRA layers was sufficient to achieve performance levels comparable to those achieved by fine-tuning all audio layers. This research highlights that an integrated pronunciation assessment system can be established by adapting large multimodal models without full fine-tuning, utilizing a significantly simpler training methodology compared to previous joint models designed for simultaneous APA and MDD. This efficient LoRA-based approach paves the way for more accessible, integrated, and effective Computer-Assisted Pronunciation Training (CAPT) technologies for English L2 learners.

[Arxiv](https://arxiv.org/abs/2509.02915)