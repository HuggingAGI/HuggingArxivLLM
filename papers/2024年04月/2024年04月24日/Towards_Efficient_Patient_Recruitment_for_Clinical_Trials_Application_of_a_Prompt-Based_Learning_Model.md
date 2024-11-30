# 高效招募临床试验患者：应用一种基于提示的学习模型

发布时间：2024年04月24日

`LLM应用`

> Towards Efficient Patient Recruitment for Clinical Trials: Application of a Prompt-Based Learning Model

# 摘要

> 目标：临床试验对于推动药物干预至关重要，但筛选合适的参与者却是一个难题。尽管利用电子健康记录（EHR）招募参与者的方法日益普及，但非结构化医疗文本的复杂性使得高效识别参与者变得困难。自然语言处理（NLP）技术，特别是变换器模型，已成为解决这一问题的有效手段。本研究旨在评估一种基于提示的大型语言模型在从EHR中收集的非结构化医疗笔记中进行队列筛选任务的性能。方法：我们筛选出与临床试验资格标准最相关的句子来处理医疗记录。收集了与各资格标准相关的SNOMED CT概念，并基于SNOMED CT本体论对医疗记录进行了MedCAT注释。随后，提取了包含与标准相关术语相匹配概念的注释句子。我们采用了基于提示的大型语言模型（本研究中为生成预训练变换器GPT）和这些句子作为训练集。为了测试其效果，我们使用了2018年n2c2挑战的数据集来评估模型性能，该挑战旨在通过NLP技术对311名患者的医疗记录根据13个资格标准进行分类。结果：我们所提出的模型在整体微观和宏观F测量值上分别达到了0.9061和0.8060，这在该数据集上的所有实验中得分名列前茅。结论：本研究中应用的基于提示的大型语言模型在根据资格标准对患者进行分类的任务上取得了令人鼓舞的成绩。此外，我们还提出了一种利用SNOMED CT本体论进行提取式摘要的方法，该方法同样适用于其他医疗文本的处理。

> Objective: Clinical trials are essential for advancing pharmaceutical interventions, but they face a bottleneck in selecting eligible participants. Although leveraging electronic health records (EHR) for recruitment has gained popularity, the complex nature of unstructured medical texts presents challenges in efficiently identifying participants. Natural Language Processing (NLP) techniques have emerged as a solution with a recent focus on transformer models. In this study, we aimed to evaluate the performance of a prompt-based large language model for the cohort selection task from unstructured medical notes collected in the EHR. Methods: To process the medical records, we selected the most related sentences of the records to the eligibility criteria needed for the trial. The SNOMED CT concepts related to each eligibility criterion were collected. Medical records were also annotated with MedCAT based on the SNOMED CT ontology. Annotated sentences including concepts matched with the criteria-relevant terms were extracted. A prompt-based large language model (Generative Pre-trained Transformer (GPT) in this study) was then used with the extracted sentences as the training set. To assess its effectiveness, we evaluated the model's performance using the dataset from the 2018 n2c2 challenge, which aimed to classify medical records of 311 patients based on 13 eligibility criteria through NLP techniques. Results: Our proposed model showed the overall micro and macro F measures of 0.9061 and 0.8060 which were among the highest scores achieved by the experiments performed with this dataset. Conclusion: The application of a prompt-based large language model in this study to classify patients based on eligibility criteria received promising scores. Besides, we proposed a method of extractive summarization with the aid of SNOMED CT ontology that can be also applied to other medical texts.

[Arxiv](https://arxiv.org/abs/2404.16198)