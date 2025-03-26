# # 分布式LLMs与多模态大型语言模型：研究进展、挑战与未来展望

发布时间：2025年03月20日

`LLM理论

理由：论文主要探讨了语言模型的分布式解决方案，包括训练、推理、微调和部署，属于理论层面的研究，分析了现有方法并提出了未来方向。` `人工智能`

> Distributed LLMs and Multimodal Large Language Models: A Survey on Advances, Challenges, and Future Directions

# 摘要

> 语言模型（LMs）通过分析大规模数据（如文本）来预测语言规律，广泛应用于自动完成功能和机器翻译等自然语言处理（NLP）任务。尽管更大规模的数据通常能提升模型性能，但计算资源的限制仍使扩展性面临挑战。分布式计算策略为此提供了关键解决方案，帮助提升模型性能并应对日益增长的计算需求。同时，训练和部署过程中涉及敏感数据引发了隐私问题。近期研究致力于开发去中心化技术，支持分布式训练和推理，同时利用边缘计算资源推动AI应用。本文综述了包括大型语言模型（LLMs）、视觉语言模型（VLMs）、多模态大语言模型（MLLMs）和小型语言模型（SLMs）在内的各类语言模型的分布式解决方案。LLMs专注于文本处理与生成，而MLLMs则能跨模态（如文本、图像和音频）整合信息，实现更广泛的应用。本文深入探讨了MLLM流水线中的关键进展，包括分布式训练、推理、微调和部署，同时分析了现有方法的优缺点和未来改进方向。此外，本文从去中心化的六个核心领域对相关文献进行了系统分类。通过分析，我们明确了当前方法在实现语言模型分布式解决方案方面的不足，并指出了未来研究的重点方向，强调开发创新解决方案以提升分布式语言模型的鲁棒性和实际应用价值的重要性。

> Language models (LMs) are machine learning models designed to predict linguistic patterns by estimating the probability of word sequences based on large-scale datasets, such as text. LMs have a wide range of applications in natural language processing (NLP) tasks, including autocomplete and machine translation. Although larger datasets typically enhance LM performance, scalability remains a challenge due to constraints in computational power and resources. Distributed computing strategies offer essential solutions for improving scalability and managing the growing computational demand. Further, the use of sensitive datasets in training and deployment raises significant privacy concerns. Recent research has focused on developing decentralized techniques to enable distributed training and inference while utilizing diverse computational resources and enabling edge AI. This paper presents a survey on distributed solutions for various LMs, including large language models (LLMs), vision language models (VLMs), multimodal LLMs (MLLMs), and small language models (SLMs). While LLMs focus on processing and generating text, MLLMs are designed to handle multiple modalities of data (e.g., text, images, and audio) and to integrate them for broader applications. To this end, this paper reviews key advancements across the MLLM pipeline, including distributed training, inference, fine-tuning, and deployment, while also identifying the contributions, limitations, and future areas of improvement. Further, it categorizes the literature based on six primary focus areas of decentralization. Our analysis describes gaps in current methodologies for enabling distributed solutions for LMs and outline future research directions, emphasizing the need for novel solutions to enhance the robustness and applicability of distributed LMs.

[Arxiv](https://arxiv.org/abs/2503.16585)