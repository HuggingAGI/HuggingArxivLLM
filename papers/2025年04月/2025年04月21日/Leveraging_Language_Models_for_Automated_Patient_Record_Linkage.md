# 利用语言模型自动匹配患者档案

发布时间：2025年04月21日

`LLM应用` `人工智能`

> Leveraging Language Models for Automated Patient Record Linkage

# 摘要

> 目标：医疗数据的碎片化为患者数据的整合带来了巨大挑战，亟需强大的记录链接技术来整合来自不同来源的患者记录。本研究旨在探索利用语言模型进行自动化患者记录链接的可行性，重点关注两个关键任务：阻断和匹配。

材料与方法：我们使用了来自密苏里癌症登记与研究中心的真实医疗数据，采用概率链接作为基线方法，将来自两个独立数据源的患者记录进行链接。我们对基于变压器的模型RoBERTa进行了微调，用于阻断任务，通过句子嵌入实现。在匹配任务中，我们在微调和零样本设置下尝试了多种语言模型，并通过与真实标签对比评估其性能。

结果：微调后的阻断模型在保持近乎完美召回率的同时，将候选对数量减少了92%。在匹配任务中，微调后的Mistral-7B表现最佳，仅出现6次错误预测。在零样本模型中，Mistral-Small-24B表现最佳，总错误预测数为55次。

讨论：微调后的语言模型在患者记录阻断和匹配任务中表现出色，错误率极低。然而，它们在阻断任务中的准确性和效率仍低于基于规则和概率的混合方法。此外，像DeepSeek-R1这样的推理模型由于计算成本高昂，不适合大规模记录链接。

结论：本研究凸显了语言模型在自动化患者记录链接方面的潜力，通过消除手动链接患者记录所需的人工努力，显著提高了效率。总体而言，语言模型提供了一种可扩展的解决方案，能够增强数据整合，减少人工努力，并支持疾病监测和研究。

> Objective: Healthcare data fragmentation presents a major challenge for linking patient data, necessitating robust record linkage to integrate patient records from diverse sources. This study investigates the feasibility of leveraging language models for automated patient record linkage, focusing on two key tasks: blocking and matching. Materials and Methods: We utilized real-world healthcare data from the Missouri Cancer Registry and Research Center, linking patient records from two independent sources using probabilistic linkage as a baseline. A transformer-based model, RoBERTa, was fine-tuned for blocking using sentence embeddings. For matching, several language models were experimented under fine-tuned and zero-shot settings, assessing their performance against ground truth labels. Results: The fine-tuned blocking model achieved a 92% reduction in the number of candidate pairs while maintaining near-perfect recall. In the matching task, fine-tuned Mistral-7B achieved the best performance with only 6 incorrect predictions. Among zero-shot models, Mistral-Small-24B performed best, with a total of 55 incorrect predictions. Discussion: Fine-tuned language models achieved strong performance in patient record blocking and matching with minimal errors. However, they remain less accurate and efficient than a hybrid rule-based and probabilistic approach for blocking. Additionally, reasoning models like DeepSeek-R1 are impractical for large-scale record linkage due to high computational costs. Conclusion: This study highlights the potential of language models for automating patient record linkage, offering improved efficiency by eliminating the manual efforts required to perform patient record linkage. Overall, language models offer a scalable solution that can enhance data integration, reduce manual effort, and support disease surveillance and research.

[Arxiv](https://arxiv.org/abs/2504.15261)