# 长链式思维中的过度思考：从自我怀疑的视角再探

发布时间：2025年05月29日

`LLM理论` `人工智能` `推理系统`

> Revisiting Overthinking in Long Chain-of-Thought from the Perspective of Self-Doubt

# 摘要

> 具备推理能力的大语言模型（RLLMs）在复杂任务中表现出色，这主要得益于长链式推理（Long CoT）的应用。然而，这些模型常常存在过度思考的问题——即使已经得出正确答案，仍会进行不必要的推理步骤。此前的研究主要通过基于样本观察长链式推理来定性分析过度思考现象。相比之下，我们从自我怀疑的角度对过度思考进行了定量分析，其特征是过度使用标记用于重新验证已正确的答案。我们发现，自我怀疑显著导致过度思考。对此，我们提出了一种简单有效的提示方法，以减少模型对输入问题的过度依赖，从而避免自我怀疑。具体而言，我们首先提示模型质疑输入问题的有效性，然后根据评估结果进行简洁回应。在三个数学推理任务和四个缺失前提的数据集上的实验表明，我们的方法显著缩短了答案长度，并在几乎所有的数据集上对四种常用的RLLMs实现了显著改进。进一步的分析表明，我们的方法能够有效减少推理步骤数量并降低自我怀疑。

> Reasoning Large Language Models (RLLMs) have demonstrated impressive performance on complex tasks, largely due to the adoption of Long Chain-of-Thought (Long CoT) reasoning. However, they often exhibit overthinking -- performing unnecessary reasoning steps even after arriving at the correct answer. Prior work has largely focused on qualitative analyses of overthinking through sample-based observations of long CoTs. In contrast, we present a quantitative analysis of overthinking from the perspective of self-doubt, characterized by excessive token usage devoted to re-verifying already-correct answer. We find that self-doubt significantly contributes to overthinking. In response, we introduce a simple and effective prompting method to reduce the model's over-reliance on input questions, thereby avoiding self-doubt. Specifically, we first prompt the model to question the validity of the input question, and then respond concisely based on the outcome of that evaluation. Experiments on three mathematical reasoning tasks and four datasets with missing premises demonstrate that our method substantially reduces answer length and yields significant improvements across nearly all datasets upon 4 widely-used RLLMs. Further analysis demonstrates that our method effectively minimizes the number of reasoning steps and reduces self-doubt.

[Arxiv](https://arxiv.org/abs/2505.23480)