# 利用大型语言模型进行零-Shot ATC 编码以用于临床评估

发布时间：2024年12月10日

`LLM应用` `药物编码`

> Zero-Shot ATC Coding with Large Language Models for Clinical Assessments

# 摘要

> 手动为处方记录分配解剖治疗化学（ATC）代码，在安大略健康和加拿大InterRAI的医疗保健研究及运营中是个重大瓶颈，这需要耗费大量专家的时间和精力。为在保障数据隐私的同时实现此流程自动化，我们借助可本地部署的大型语言模型（LLMs）开发出一种实用方法。受近期自动国际疾病分类（ICD）编码进展的启发，我们把ATC编码设定为分层信息提取任务，通过ATC本体逐层引导LLMs。我们以GPT-4o作为准确率上限来评估我们的方法，并着重开发适用于隐私敏感部署的开源Llama模型。在加拿大卫生部药品产品数据、RABBITS基准以及安大略健康的真实临床笔记上进行测试，我们的方法与GPT-4o的精确匹配准确率达78%，与Llama 3.1 70B的准确率达60%。通过对药物定义的研究来探究知识基础，发现准确率有一定程度的提高。此外，我们发现微调后的Llama 3.1 8B与零样本Llama 3.1 70B的准确率相当，这表明使用较小的模型进行有效的ATC编码是可行的。我们的成果证明了在隐私敏感的医疗保健环境中自动ATC编码的可行性，为未来的部署奠定了基础。

> Manual assignment of Anatomical Therapeutic Chemical (ATC) codes to prescription records is a significant bottleneck in healthcare research and operations at Ontario Health and InterRAI Canada, requiring extensive expert time and effort. To automate this process while maintaining data privacy, we develop a practical approach using locally deployable large language models (LLMs). Inspired by recent advances in automatic International Classification of Diseases (ICD) coding, our method frames ATC coding as a hierarchical information extraction task, guiding LLMs through the ATC ontology level by level. We evaluate our approach using GPT-4o as an accuracy ceiling and focus development on open-source Llama models suitable for privacy-sensitive deployment. Testing across Health Canada drug product data, the RABBITS benchmark, and real clinical notes from Ontario Health, our method achieves 78% exact match accuracy with GPT-4o and 60% with Llama 3.1 70B. We investigate knowledge grounding through drug definitions, finding modest improvements in accuracy. Further, we show that fine-tuned Llama 3.1 8B matches zero-shot Llama 3.1 70B accuracy, suggesting that effective ATC coding is feasible with smaller models. Our results demonstrate the feasibility of automatic ATC coding in privacy-sensitive healthcare environments, providing a foundation for future deployments.

[Arxiv](https://arxiv.org/abs/2412.07743)