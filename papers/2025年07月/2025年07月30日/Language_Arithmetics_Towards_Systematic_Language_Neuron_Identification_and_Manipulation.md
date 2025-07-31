# 语言算术：探索系统化语言神经元识别与操控方法

发布时间：2025年07月30日

`LLM理论` `跨语言技术`

> Language Arithmetics: Towards Systematic Language Neuron Identification and Manipulation

# 摘要

> 大型语言模型（LLMs）具备强大的多语言能力，但其背后特定语言处理的神经机制仍不明确。我们研究了Llama-3.1-8B、Mistral-Nemo-12B和Aya-Expanse-8B & 32B模型在21种类型学各异的语言中的语言特异性神经元，揭示了控制语言行为的关键神经元。通过语言激活概率熵（LAPE）方法，我们发现这些神经元在深层网络中聚集，而非拉丁语系字符表现出更高的专业化。语言间的亲缘关系通过共享神经元得以体现。利用语言算术（系统性激活加法与乘法），我们成功引导模型去激活非目标语言并激活目标语言，超越了简单的替换策略。这种方法在语言强制、翻译、问答、理解与自然语言推理等五项跨语言任务中均有效。高资源语言的操控成功率更高，而类型学相似性则提升操控效果。我们还发现跨语言神经元引导可增强下游任务性能，并揭示了当神经元被去激活时，模型内部用于语言选择的“回退”机制。我们的研究代码已开源，地址为https://github.com/d-gurgurov/Language-Neurons-Manipulation。

> Large language models (LLMs) exhibit strong multilingual abilities, yet the neural mechanisms behind language-specific processing remain unclear. We analyze language-specific neurons in Llama-3.1-8B, Mistral-Nemo-12B, and Aya-Expanse-8B & 32B across 21 typologically diverse languages, identifying neurons that control language behavior. Using the Language Activation Probability Entropy (LAPE) method, we show that these neurons cluster in deeper layers, with non-Latin scripts showing greater specialization. Related languages share overlapping neurons, reflecting internal representations of linguistic proximity.
  Through language arithmetics, i.e. systematic activation addition and multiplication, we steer models to deactivate unwanted languages and activate desired ones, outperforming simpler replacement approaches. These interventions effectively guide behavior across five multilingual tasks: language forcing, translation, QA, comprehension, and NLI. Manipulation is more successful for high-resource languages, while typological similarity improves effectiveness. We also demonstrate that cross-lingual neuron steering enhances downstream performance and reveal internal "fallback" mechanisms for language selection when neurons are progressively deactivated. Our code is made publicly available at https://github.com/d-gurgurov/Language-Neurons-Manipulation.

[Arxiv](https://arxiv.org/abs/2507.22608)