# CKD-EHR：临床知识蒸馏在电子健康记录中的应用

发布时间：2025年06月17日

`LLM应用` `精准医学`

> CKD-EHR:Clinical Knowledge Distillation for Electronic Health Records

# 摘要

> 基于电子健康记录 (EHR) 的疾病预测模型在推动精准医学和实现早期干预方面展现出了显著的临床价值。然而，现有的大型语言模型在两个主要方面面临挑战：一是对医学知识的表示不足，二是临床部署效率低下。为了解决这些问题，本研究提出了 CKD-EHR（临床知识蒸馏用于 EHR）框架，该框架通过知识蒸馏技术实现了高效且准确的疾病风险预测。具体而言，首先对增强医学知识的大型语言模型 Qwen2.5-7B 进行微调，使其成为教师模型。然后，通过多粒度注意力蒸馏机制生成可解释的软标签。最后，将蒸馏得到的知识转移至轻量级的 BERT 学生模型。实验结果表明，在 MIMIC-III 数据集上，CKD-EHR 显著优于基线模型：诊断准确率提高了 9%，F1 值提升了 27%，推理速度提升了 22.2 倍。这一创新解决方案不仅大幅提升了资源利用率，还显著增强了诊断的准确性和及时性，为临床资源优化提供了切实可行的技术途径。本研究的代码和数据可在 https://github.com/209506702/CKD_EHR 获取。

> Electronic Health Records (EHR)-based disease prediction models have demonstrated significant clinical value in promoting precision medicine and enabling early intervention. However, existing large language models face two major challenges: insufficient representation of medical knowledge and low efficiency in clinical deployment. To address these challenges, this study proposes the CKD-EHR (Clinical Knowledge Distillation for EHR) framework, which achieves efficient and accurate disease risk prediction through knowledge distillation techniques. Specifically, the large language model Qwen2.5-7B is first fine-tuned on medical knowledge-enhanced data to serve as the teacher model.It then generates interpretable soft labels through a multi-granularity attention distillation mechanism. Finally, the distilled knowledge is transferred to a lightweight BERT student model. Experimental results show that on the MIMIC-III dataset, CKD-EHR significantly outperforms the baseline model:diagnostic accuracy is increased by 9%, F1-score is improved by 27%, and a 22.2 times inference speedup is achieved. This innovative solution not only greatly improves resource utilization efficiency but also significantly enhances the accuracy and timeliness of diagnosis, providing a practical technical approach for resource optimization in clinical settings. The code and data for this research are available athttps://github.com/209506702/CKD_EHR.

[Arxiv](https://arxiv.org/abs/2506.15118)