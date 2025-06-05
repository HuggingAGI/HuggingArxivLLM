# 高准确度，少废话（HALT）：通过能力对齐的微调，打造值得信赖的大语言模型

发布时间：2025年06月04日

`LLM应用` `大型语言模型` `问答系统`

> High Accuracy, Less Talk (HALT): Reliable LLMs through Capability-Aligned Finetuning

# 摘要

> 当前的大型语言模型（LLMs）能够对任何输入提示进行回应。然而，当模型缺乏相关知识或能力时，可能会生成错误的答案，这一问题被称为幻觉。我们提出了一种后训练方法，使LLM仅在确信答案正确时生成内容，否则（部分）保留不回答。具体来说，我们的方法HALT生成与模型能力相匹配的后训练数据，这些数据编码了模型能够可靠生成和无法可靠生成的内容。我们通过将预训练LLM的响应拆分为事实片段（原子声明或推理步骤），并使用真实信息来识别错误片段，从而生成这些数据。我们通过删除错误片段或根据可调节的阈值将其替换为"从这里开始不确定"来实现与能力相匹配的微调响应，该阈值允许实践者在响应完整性和响应片段的平均正确性之间进行权衡。我们使用HALT对四个开源模型进行了生物写作、数学、编码和医学领域的微调，采用了三种不同的权衡阈值。HALT有效地在正确性和响应完整性之间进行了权衡，将响应片段的平均正确性提高了15%，同时与相关基线相比，F1分数（响应完整性和正确性的平均值）提高了4%。通过将HALT调整为最高正确性，我们在所有四个领域中训练了一个可靠的Llama3-70B模型，正确性从51%提高到87%，同时保持了标准微调下响应完整性的53%。

> Large Language Models (LLMs) currently respond to every prompt. However, they can produce incorrect answers when they lack knowledge or capability -- a problem known as hallucination. We instead propose post-training an LLM to generate content only when confident in its correctness and to otherwise (partially) abstain. Specifically, our method, HALT, produces capability-aligned post-training data that encodes what the model can and cannot reliably generate. We generate this data by splitting responses of the pretrained LLM into factual fragments (atomic statements or reasoning steps), and use ground truth information to identify incorrect fragments. We achieve capability-aligned finetuning responses by either removing incorrect fragments or replacing them with "Unsure from Here" -- according to a tunable threshold that allows practitioners to trade off response completeness and mean correctness of the response's fragments. We finetune four open-source models for biography writing, mathematics, coding, and medicine with HALT for three different trade-off thresholds. HALT effectively trades off response completeness for correctness, increasing the mean correctness of response fragments by 15% on average, while resulting in a 4% improvement in the F1 score (mean of completeness and correctness of the response) compared to the relevant baselines. By tuning HALT for highest correctness, we train a single reliable Llama3-70B model with correctness increased from 51% to 87% across all four domains while maintaining 53% of the response completeness achieved with standard finetuning.

[Arxiv](https://arxiv.org/abs/2506.04051)