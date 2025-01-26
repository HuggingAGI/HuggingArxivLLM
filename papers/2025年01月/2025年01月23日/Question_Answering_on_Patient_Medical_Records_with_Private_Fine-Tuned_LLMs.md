# 基于私有微调LLMs的患者医疗记录问答

发布时间：2025年01月23日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来解决医疗系统中电子健康记录（EHRs）的复杂性问题，特别是通过语义问答（QA）技术来提高用户与健康记录的互动效率。论文还探讨了在私有环境中部署LLMs的方法，并评估了不同模型的性能。这些内容主要涉及LLMs在实际应用中的使用和优化，因此应归类为“LLM应用”。` `电子健康记录`

> Question Answering on Patient Medical Records with Private Fine-Tuned LLMs

# 摘要

> # 摘要
医疗系统持续生成海量电子健康记录（EHRs），通常以FHIR标准存储。尽管这些记录信息丰富，但其复杂性和规模使得用户难以提取和解读关键医疗洞察。最近，大型语言模型（LLMs）的突破性进展为这一问题提供了解决方案，通过语义问答（QA）技术，用户能够更高效地与健康记录互动。然而，为确保隐私和合规性，LLMs需要在边缘和私有环境中部署。
本文提出了一种创新的语义QA方法，首先识别用户查询中最相关的FHIR资源（任务1），随后基于这些资源回答查询（任务2）。我们评估了私有托管和微调的LLMs的性能，并与GPT-4和GPT-4o等基准模型进行了对比。结果显示，尽管微调LLMs的规模小了250倍，但在任务1中的F1分数比GPT-4系列模型高出0.55%，在任务2中的Meteor任务中高出42%。此外，我们还探讨了LLM使用的高级技术，如顺序微调、模型自我评估（自恋评估）以及训练数据规模对性能的影响。模型和数据集可在此处获取：https://huggingface.co/genloop

> Healthcare systems continuously generate vast amounts of electronic health records (EHRs), commonly stored in the Fast Healthcare Interoperability Resources (FHIR) standard. Despite the wealth of information in these records, their complexity and volume make it difficult for users to retrieve and interpret crucial health insights. Recent advances in Large Language Models (LLMs) offer a solution, enabling semantic question answering (QA) over medical data, allowing users to interact with their health records more effectively. However, ensuring privacy and compliance requires edge and private deployments of LLMs.
  This paper proposes a novel approach to semantic QA over EHRs by first identifying the most relevant FHIR resources for a user query (Task1) and subsequently answering the query based on these resources (Task2). We explore the performance of privately hosted, fine-tuned LLMs, evaluating them against benchmark models such as GPT-4 and GPT-4o. Our results demonstrate that fine-tuned LLMs, while 250x smaller in size, outperform GPT-4 family models by 0.55% in F1 score on Task1 and 42% on Meteor Task in Task2. Additionally, we examine advanced aspects of LLM usage, including sequential fine-tuning, model self-evaluation (narcissistic evaluation), and the impact of training data size on performance. The models and datasets are available here: https://huggingface.co/genloop

[Arxiv](https://arxiv.org/abs/2501.13687)