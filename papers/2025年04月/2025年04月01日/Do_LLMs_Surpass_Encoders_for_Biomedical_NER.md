# 大型语言模型（LLMs）在生物医学命名实体识别（NER）上能否超越编码器？

发布时间：2025年04月01日

`LLM应用` `生物医学`

> Do LLMs Surpass Encoders for Biomedical NER?

# 摘要

> **生物医学命名实体识别：编码模型与解码模型的较量**  
在信息抽取（IE）流程中，生物医学命名实体识别（NER）是不可或缺的基础模块。它负责从自由文本中识别生物医学概念的区间及其类型（如药物或基因）。如果没有强大的NER能力支撑，诸如知识发现和信息检索等应用将难以有效开展。  

近年来，NER领域的技术发展经历了从传统机器学习模型到深度神经网络的转变，基于Transformer的编码模型（如BERT）已成为当前的主流标准。然而，解码模型（即大型语言模型，LLMs）在IE领域正逐渐崭露头角。  

尽管LLMs在生成能力上表现出色，但其在NER任务中存在两个主要问题：首先，由于解码模型的生成特性，LLM驱动的NER往往忽视位置信息；其次，LLMs在计算资源上的消耗极大（无论是推理时间还是硬件需求）。因此，我们不禁要问：LLMs在生物医学NER上的实际优势究竟有多大？它们是否值得为此付出高昂的计算代价？  

为回答这些问题，我们采用相同的BIO实体标注方案（保留位置信息），并使用了五个不同数据集（包含不同比例的长实体），对编码模型与LLMs的表现进行了全面对比。结果发现：  
- 所选的LLMs（Mistral和Llama：80亿参数量级）在F值上通常比最佳编码模型（BERT-(un)cased、BiomedBERT和DeBERTav3：3亿参数量级）高出2-8%，仅在一个数据集中与编码模型持平。  
- 这种优势在长度>=3个词的较长实体中表现得尤为明显。  

然而，LLMs的高表现并非没有代价：它们在推理时间上的成本要高出一到两个数量级，并且可能需要成本高昂的硬件支持。因此，当性能差异较小时，或需要实时用户反馈时，编码模型可能仍比LLMs更合适。  


> Recognizing spans of biomedical concepts and their types (e.g., drug or gene) in free text, often called biomedical named entity recognition (NER), is a basic component of information extraction (IE) pipelines. Without a strong NER component, other applications, such as knowledge discovery and information retrieval, are not practical. State-of-the-art in NER shifted from traditional ML models to deep neural networks with transformer-based encoder models (e.g., BERT) emerging as the current standard. However, decoder models (also called large language models or LLMs) are gaining traction in IE. But LLM-driven NER often ignores positional information due to the generative nature of decoder models. Furthermore, they are computationally very expensive (both in inference time and hardware needs). Hence, it is worth exploring if they actually excel at biomedical NER and assess any associated trade-offs (performance vs efficiency). This is exactly what we do in this effort employing the same BIO entity tagging scheme (that retains positional information) using five different datasets with varying proportions of longer entities. Our results show that the LLMs chosen (Mistral and Llama: 8B range) often outperform best encoder models (BERT-(un)cased, BiomedBERT, and DeBERTav3: 300M range) by 2-8% in F-scores except for one dataset, where they equal encoder performance. This gain is more prominent among longer entities of length >= 3 tokens. However, LLMs are one to two orders of magnitude more expensive at inference time and may need cost prohibitive hardware. Thus, when performance differences are small or real time user feedback is needed, encoder models might still be more suitable than LLMs.

[Arxiv](https://arxiv.org/abs/2504.00664)