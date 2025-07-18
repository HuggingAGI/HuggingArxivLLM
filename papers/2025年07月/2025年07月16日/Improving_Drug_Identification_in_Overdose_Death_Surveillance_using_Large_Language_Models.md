# 借助大型语言模型，在过量死亡监测中提升药物识别能力

发布时间：2025年07月16日

`LLM应用` `公共卫生`

> Improving Drug Identification in Overdose Death Surveillance using Large Language Models

# 摘要

> # 摘要  
美国药物相关死亡率的激增，尤其是芬太尼相关死亡，亟需更及时、精准的监测手段。然而，关键的过量用药数据往往深埋于自由文本的验尸报告中，导致在将其编码为国际疾病分类（ICD）-10分类时出现延误和信息流失。  
自然语言处理（NLP）技术为解决这一难题提供了新思路，但此前的应用范围和效果仍有待提升。  
本研究基于2020年来自多个美国管辖区的35,433份死亡记录数据集进行模型训练和内部测试，并采用2023-2024年的3,335份独立记录进行了外部验证。  
研究评估了多种NLP方法在从非结构化死亡证明文本中分类特定药物参与情况的效果，包括：  
- 传统单标签和多标签分类器  
- 经过微调的仅编码器语言模型（如BERT和BioClinicalBERT）  
- 当代仅解码器大型语言模型（如Qwen 3和Llama 3）  

通过宏平均F1分数评估模型性能，并计算95%置信区间以量化结果不确定性。  
结果显示，经过微调的BioClinicalBERT模型表现优异，在内部测试集中宏F1分数高达0.998，外部验证中也保持了0.966的稳健性能，显著优于传统机器学习方法、通用领域BERT模型及多种仅解码器大型语言模型。  
研究发现，NLP模型，尤其是经过微调的临床变体如BioClinicalBERT，为从自由文本报告中分类过量死亡提供了一种高效、精准且可扩展的解决方案。这些方法不仅能够显著加速监控工作流程，还能突破传统手动ICD-10编码的局限性，为实时追踪新兴物质使用趋势提供了有力工具。

> The rising rate of drug-related deaths in the United States, largely driven by fentanyl, requires timely and accurate surveillance. However, critical overdose data are often buried in free-text coroner reports, leading to delays and information loss when coded into ICD (International Classification of Disease)-10 classifications. Natural language processing (NLP) models may automate and enhance overdose surveillance, but prior applications have been limited. A dataset of 35,433 death records from multiple U.S. jurisdictions in 2020 was used for model training and internal testing. External validation was conducted using a novel separate dataset of 3,335 records from 2023-2024. Multiple NLP approaches were evaluated for classifying specific drug involvement from unstructured death certificate text. These included traditional single- and multi-label classifiers, as well as fine-tuned encoder-only language models such as Bidirectional Encoder Representations from Transformers (BERT) and BioClinicalBERT, and contemporary decoder-only large language models such as Qwen 3 and Llama 3. Model performance was assessed using macro-averaged F1 scores, and 95% confidence intervals were calculated to quantify uncertainty. Fine-tuned BioClinicalBERT models achieved near-perfect performance, with macro F1 scores >=0.998 on the internal test set. External validation confirmed robustness (macro F1=0.966), outperforming conventional machine learning, general-domain BERT models, and various decoder-only large language models. NLP models, particularly fine-tuned clinical variants like BioClinicalBERT, offer a highly accurate and scalable solution for overdose death classification from free-text reports. These methods can significantly accelerate surveillance workflows, overcoming the limitations of manual ICD-10 coding and supporting near real-time detection of emerging substance use trends.

[Arxiv](https://arxiv.org/abs/2507.12679)