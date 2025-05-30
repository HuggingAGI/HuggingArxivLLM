# 借助动态焦点锚点提升大型语言模型的机器翻译能力

发布时间：2025年05月29日

`LLM应用` `机器翻译`

> Enhancing Large Language Models'Machine Translation via Dynamic Focus Anchoring

# 摘要

> 大型语言模型在跨语言NLP任务中表现优异，尤其在机器翻译（MT）领域。然而，面对多义词等上下文敏感单元（CSUs），仍存在亟待解决的挑战。这些CSUs不仅会影响模型的局部翻译准确性，还可能削弱其对句子和任务的整体理解能力，甚至导致翻译失败。为应对这一难题，我们提出了一种简单而有效的方法，通过获取CSUs并应用语义聚焦，来提升大型语言模型的机器翻译能力。具体而言，我们动态分析和识别翻译挑战，然后以结构化的方式将其融入模型，从而缓解因信息扁平化导致的CSUs误译或误解问题。通过这种方式，能够高效激活模型，使其从庞大的数据池中识别并应用相关知识，从而实现对疑难词汇的更准确翻译。在机器翻译的基准数据集上，我们的方法与多种现有的开源基线模型相比，均取得了具有竞争力的性能表现。该方法在多种语言对上均展现出有效性与鲁棒性，包括相似语言对和远距离语言对。值得注意的是，该方法无需额外的模型训练，且仅需极低的资源消耗，即可显著提升大型语言模型在多种NLP任务中的性能表现。

> Large language models have demonstrated exceptional performance across multiple crosslingual NLP tasks, including machine translation (MT). However, persistent challenges remain in addressing context-sensitive units (CSUs), such as polysemous words. These CSUs not only affect the local translation accuracy of LLMs, but also affect LLMs' understanding capability for sentences and tasks, and even lead to translation failure. To address this problem, we propose a simple but effective method to enhance LLMs' MT capabilities by acquiring CSUs and applying semantic focus. Specifically, we dynamically analyze and identify translation challenges, then incorporate them into LLMs in a structured manner to mitigate mistranslations or misunderstandings of CSUs caused by information flattening. Efficiently activate LLMs to identify and apply relevant knowledge from its vast data pool in this way, ensuring more accurate translations for translating difficult terms. On a benchmark dataset of MT, our proposed method achieved competitive performance compared to multiple existing open-sourced MT baseline models. It demonstrates effectiveness and robustness across multiple language pairs, including both similar language pairs and distant language pairs. Notably, the proposed method requires no additional model training and enhances LLMs' performance across multiple NLP tasks with minimal resource consumption.

[Arxiv](https://arxiv.org/abs/2505.23140)