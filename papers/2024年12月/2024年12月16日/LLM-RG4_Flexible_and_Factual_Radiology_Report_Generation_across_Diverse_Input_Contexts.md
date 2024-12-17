# LLM-RG4：可在多样输入语境中实现灵活且基于事实的放射学报告生成

发布时间：2024年12月16日

`LLM应用` `放射学`

> LLM-RG4: Flexible and Factual Radiology Report Generation across Diverse Input Contexts

# 摘要

> 起草放射学报告是一项复杂且需要灵活性的任务，放射科医生会依据可用信息和特定临床需求来调整内容。然而，当下大多数放射学报告生成（RRG）模型都受限于固定的任务范式，比如从单张图像预测完整的“发现”部分，这本质上就存在输入与输出的不匹配。训练后的模型对各种输入缺乏灵活性，可能产生有害且与输入无关的幻觉。为填补当前RRG模型与实际临床需求的差距，我们先是开发了一个数据生成管道，创建了新的MIMIC-RG4数据集，该数据集涵盖了四种常见的放射学报告起草场景，且输入与输出完美对应。其次，我们提出了一个新颖的基于大型语言模型（LLM）的RRG框架，即LLM-RG4，它借助了LLM灵活的遵循指令能力和广泛的常识。我们还进一步开发了一个自适应令牌融合模块，为处理不同输入组合的各种场景提供了灵活性，同时最大程度减少了因输入量增加而带来的额外计算负担。另外，我们提出了一种令牌级损失加权策略，引导模型关注积极和不确定的描述。实验结果显示，LLM-RG4在MIMIC-RG4和MIMIC-CXR数据集上的临床效率和自然语言生成方面均达到了领先水平。我们定量证明了我们的模型具有极少的与输入无关的幻觉，而当前的开源模型通常存在此问题。

> Drafting radiology reports is a complex task requiring flexibility, where radiologists tail content to available information and particular clinical demands. However, most current radiology report generation (RRG) models are constrained to a fixed task paradigm, such as predicting the full ``finding'' section from a single image, inherently involving a mismatch between inputs and outputs. The trained models lack the flexibility for diverse inputs and could generate harmful, input-agnostic hallucinations. To bridge the gap between current RRG models and the clinical demands in practice, we first develop a data generation pipeline to create a new MIMIC-RG4 dataset, which considers four common radiology report drafting scenarios and has perfectly corresponded input and output. Secondly, we propose a novel large language model (LLM) based RRG framework, namely LLM-RG4, which utilizes LLM's flexible instruction-following capabilities and extensive general knowledge. We further develop an adaptive token fusion module that offers flexibility to handle diverse scenarios with different input combinations, while minimizing the additional computational burden associated with increased input volumes. Besides, we propose a token-level loss weighting strategy to direct the model's attention towards positive and uncertain descriptions. Experimental results demonstrate that LLM-RG4 achieves state-of-the-art performance in both clinical efficiency and natural language generation on the MIMIC-RG4 and MIMIC-CXR datasets. We quantitatively demonstrate that our model has minimal input-agnostic hallucinations, whereas current open-source models commonly suffer from this problem.

[Arxiv](https://arxiv.org/abs/2412.12001)