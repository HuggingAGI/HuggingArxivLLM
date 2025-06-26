# 本地检索增强生成模型在医学任务中表现更优，准确且节能高效

发布时间：2025年06月24日

`LLM应用` `问答系统`

> Accurate and Energy Efficient: Local Retrieval-Augmented Generation Models Outperform Commercial Large Language Models in Medical Tasks

# 摘要

> <翻译失败>

> Background The increasing adoption of Artificial Intelligence (AI) in healthcare has sparked growing concerns about its environmental and ethical implications. Commercial Large Language Models (LLMs), such as ChatGPT and DeepSeek, require substantial resources, while the utilization of these systems for medical purposes raises critical issues regarding patient privacy and safety. Methods We developed a customizable Retrieval-Augmented Generation (RAG) framework for medical tasks, which monitors its energy usage and CO2 emissions. This system was then used to create RAGs based on various open-source LLMs. The tested models included both general purpose models like llama3.1:8b and medgemma-4b-it, which is medical-domain specific. The best RAGs performance and energy consumption was compared to DeepSeekV3-R1 and OpenAIs o4-mini model. A dataset of medical questions was used for the evaluation. Results Custom RAG models outperformed commercial models in accuracy and energy consumption. The RAG model built on llama3.1:8B achieved the highest accuracy (58.5%) and was significantly better than other models, including o4-mini and DeepSeekV3-R1. The llama3.1-RAG also exhibited the lowest energy consumption and CO2 footprint among all models, with a Performance per kWh of 0.52 and a total CO2 emission of 473g. Compared to o4-mini, the llama3.1-RAG achieved 2.7x times more accuracy points per kWh and 172% less electricity usage while maintaining higher accuracy. Conclusion Our study demonstrates that local LLMs can be leveraged to develop RAGs that outperform commercial, online LLMs in medical tasks, while having a smaller environmental impact. Our modular framework promotes sustainable AI development, reducing electricity usage and aligning with the UNs Sustainable Development Goals.

[Arxiv](https://arxiv.org/abs/2506.20009)