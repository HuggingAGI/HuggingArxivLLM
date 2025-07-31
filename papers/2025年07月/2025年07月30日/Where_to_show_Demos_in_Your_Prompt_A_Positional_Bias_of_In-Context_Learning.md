# 如何在提示中安排示例的位置：上下文学习中的位置偏见问题

发布时间：2025年07月30日

`LLM应用` `人工智能`

> Where to show Demos in Your Prompt: A Positional Bias of In-Context Learning

# 摘要

> 上下文学习（ICL）是大型语言模型（LLMs）中一项关键的新兴能力，它通过在提示中包含几个演示（demos）来实现推理过程中的少样本学习。然而，研究发现，ICL的性能可能会受到所选演示及其顺序的影响。本文首次研究了ICL中一个尚未探索的新位置偏见：我们发现，当演示、系统提示和用户消息在LLM输入中的位置发生变化时，预测结果和准确性可能会发生显著漂移。我们将这种偏见称为提示中演示的位置偏见（DPP偏见）。我们设计了一个系统化的评估流程，以研究这种位置偏见在分类、问答、摘要和推理任务中的表现。我们引入了两个指标，ACCURACY-CHANGE和PREDICTION-CHANGE，以量化由于演示位置变化而引起的净收益和输出波动。在四个开源模型家族（QWEN、LLAMA3、MISTRAL、COHERE）的十种LLM上进行的大量实验验证了该偏见对模型准确性和预测结果的显著影响：将演示放在提示的开头能够获得最稳定和准确的输出，准确率提升高达+6个百分点。相反，将演示放在用户消息的末尾会导致问答任务中超过30%的预测结果翻转，而正确性却没有得到提升。较小规模的模型受此敏感性影响最大，尽管即使是较大的模型在复杂任务上仍会受到一定程度的影响。

> In-context learning (ICL) is a critical emerging capability of large language models (LLMs), enabling few-shot learning during inference by including a few demonstrations (demos) in the prompt. However, it has been found that ICL's performance can be sensitive to the choices of demos and their order. This paper investigates an unexplored new positional bias of ICL for the first time: we observe that the predictions and accuracy can drift drastically when the positions of demos, the system prompt, and the user message in LLM input are varied. We refer to this bias as DEMOS' POSITION IN PROMPT (DPP) bias. We design a systematic evaluation pipeline to study this type of positional bias across classification, question answering, summarization, and reasoning tasks. We introduce two metrics, ACCURACY-CHANGE and PREDICTION-CHANGE, to quantify net gains and output volatility induced by changes in the demos' position. Extensive experiments on ten LLMs from four open-source model families (QWEN, LLAMA3, MISTRAL, COHERE) verify that the bias significantly affects their accuracy and predictions: placing demos at the start of the prompt yields the most stable and accurate outputs with gains of up to +6 points. In contrast, placing demos at the end of the user message flips over 30\% of predictions without improving correctness on QA tasks. Smaller models are most affected by this sensitivity, though even large models remain marginally affected on complex tasks.

[Arxiv](https://arxiv.org/abs/2507.22887)