# 借助大型语言模型，我们能够从临床记录中预测未知诊断结果。

发布时间：2025年03月27日

`LLM应用`

> Leveraging LLMs for Predicting Unknown Diagnoses from Clinical Notes

# 摘要

> 电子健康记录（EHRs）中常常缺少药物与诊断之间的明确关联，这为临床决策和研究带来了诸多挑战。即使存在关联，诊断列表也可能不完整，尤其是在患者初次就诊时。相比之下，出院总结通常包含更全面的信息，能够帮助推断准确的诊断，尤其是在大型语言模型（LLMs）的辅助下。本研究旨在探讨LLMs能否从临床记录中识别出隐含提及的诊断，并将其与相应的药物建立关联。我们重点关注两个研究问题：（1）多样的LLM配置下的多数投票是否优于单一最佳配置在诊断预测中的表现？（2）多数投票的准确性对LLM超参数（如温度、top-p和摘要长度）的敏感性如何？为了验证这一假设，我们从20份MIMIC-IV记录中构建了一个包含240对专家标注的药物-诊断组合的新数据集。使用GPT-3.5 Turbo，我们在短摘要和长摘要长度下运行了18种提示配置，生成了8568个测试案例。实验结果显示，多数投票方法在诊断预测中达到了75%的准确率，显著优于单一最佳配置的66%。值得注意的是，没有单一的超参数设置能够主导性能表现，但结合确定性、平衡性和探索性策略的配置组合能够显著提升模型表现。此外，较短的摘要通常能带来更高的预测准确率。综上所述，通过多样化的LLM配置进行集成式多数投票的方法，能够有效提升电子健康记录中的诊断预测效果，并为临床文本中关联药物与诊断提供了一种极具潜力的解决方案。


> Electronic Health Records (EHRs) often lack explicit links between medications and diagnoses, making clinical decision-making and research more difficult. Even when links exist, diagnosis lists may be incomplete, especially during early patient visits. Discharge summaries tend to provide more complete information, which can help infer accurate diagnoses, especially with the help of large language models (LLMs). This study investigates whether LLMs can predict implicitly mentioned diagnoses from clinical notes and link them to corresponding medications. We address two research questions: (1) Does majority voting across diverse LLM configurations outperform the best single configuration in diagnosis prediction? (2) How sensitive is majority voting accuracy to LLM hyperparameters such as temperature, top-p, and summary length? To evaluate, we created a new dataset of 240 expert-annotated medication-diagnosis pairs from 20 MIMIC-IV notes. Using GPT-3.5 Turbo, we ran 18 prompting configurations across short and long summary lengths, generating 8568 test cases. Results show that majority voting achieved 75 percent accuracy, outperforming the best single configuration at 66 percent. No single hyperparameter setting dominated, but combining deterministic, balanced, and exploratory strategies improved performance. Shorter summaries generally led to higher accuracy.In conclusion, ensemble-style majority voting with diverse LLM configurations improves diagnosis prediction in EHRs and offers a promising method to link medications and diagnoses in clinical texts.

[Arxiv](https://arxiv.org/abs/2503.22092)