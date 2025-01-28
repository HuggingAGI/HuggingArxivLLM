# 评估大型语言模型在放射肿瘤学中自动生成CT模拟订单摘要的性能

发布时间：2025年01月27日

`LLM应用

解释：这篇论文主要探讨了如何利用大型语言模型（LLM）来自动化生成CT模拟订单的摘要，并评估其性能。这属于LLM在实际医疗场景中的应用，因此分类为LLM应用。` `自动化`

> Evaluating The Performance of Using Large Language Models to Automate Summarization of CT Simulation Orders in Radiation Oncology

# 摘要

> 目的：本研究旨在利用大型语言模型（LLM）自动化生成CT模拟订单的摘要，并评估其性能。
材料与方法：我们从机构的Aria数据库中收集了607份患者的CT模拟订单。通过API服务访问的本地Llama 3.1 405B模型用于提取关键词并生成摘要。CT模拟订单根据治疗方式和疾病部位分为七组。每组均与治疗师合作开发了定制指令提示，以指导模型生成摘要。摘要的真实值通过手动审查每个订单并由治疗师验证得出。治疗师以验证过的真实值为参考，评估了LLM生成摘要的准确性。
结果：约98%的LLM生成摘要在准确性上与手动生成的真实值一致。评估显示，LLM生成的摘要在格式一致性和可读性上优于治疗师生成的摘要。这种自动化方法在所有组中表现一致，不受治疗方式或疾病部位影响。
结论：本研究展示了Llama 3.1 405B模型在提取关键词和总结CT模拟订单方面的高精度和一致性，表明LLM在减轻治疗师工作负担、提升工作流程效率方面具有巨大潜力。

> Purpose: This study aims to use a large language model (LLM) to automate the generation of summaries from the CT simulation orders and evaluate its performance.
  Materials and Methods: A total of 607 CT simulation orders for patients were collected from the Aria database at our institution. A locally hosted Llama 3.1 405B model, accessed via the Application Programming Interface (API) service, was used to extract keywords from the CT simulation orders and generate summaries. The downloaded CT simulation orders were categorized into seven groups based on treatment modalities and disease sites. For each group, a customized instruction prompt was developed collaboratively with therapists to guide the Llama 3.1 405B model in generating summaries. The ground truth for the corresponding summaries was manually derived by carefully reviewing each CT simulation order and subsequently verified by therapists. The accuracy of the LLM-generated summaries was evaluated by therapists using the verified ground truth as a reference.
  Results: About 98% of the LLM-generated summaries aligned with the manually generated ground truth in terms of accuracy. Our evaluations showed an improved consistency in format and enhanced readability of the LLM-generated summaries compared to the corresponding therapists-generated summaries. This automated approach demonstrated a consistent performance across all groups, regardless of modality or disease site.
  Conclusions: This study demonstrated the high precision and consistency of the Llama 3.1 405B model in extracting keywords and summarizing CT simulation orders, suggesting that LLMs have great potential to help with this task, reduce the workload of therapists and improve workflow efficiency.

[Arxiv](https://arxiv.org/abs/2501.16309)