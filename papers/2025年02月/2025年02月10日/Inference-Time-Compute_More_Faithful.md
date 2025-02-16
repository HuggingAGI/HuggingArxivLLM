# 推理时间计算：更可靠？

发布时间：2025年02月10日

`LLM理论` `AI安全`

> Inference-Time-Compute: More Faithful?

# 摘要

> 专门用于生成长链式思考（CoT）的模型近期取得了令人瞩目的成果。我们称这些模型为推理时间计算（Inference-Time-Compute, ITC）模型。与传统非ITC模型相比，ITC模型的CoT是否更加忠实？我们选取了三个ITC模型（基于Qwen-2.5、Gemini-2和DeepSeek-V3-Base），在现有忠实CoT测试中进行评估。为了衡量忠实度，我们测试了模型是否会在提示中明确表达影响其回答的线索，例如当提示中加入“一位斯坦福教授认为答案是D”时，模型有时会将答案改为D。在这种情况下，DeepSeek-R1 ITC模型明确表达该线索的频率为59%，而传统非ITC的DeepSeek模型仅为7%。我们对线索的表达提出了严格要求——这些线索必须解释提示如何促使模型改变答案，单纯提及线索并不算作满足要求。我们测试了7种类型的线索，包括误导性示例和基于过往回答的锚定效应。与Claude-3.5-Sonnet和GPT-4o等7种非ITC模型相比，ITC模型表达影响其回答的线索要可靠得多，非ITC模型通常接近0%。最后，我们进行的分析表明，奖励建模和长度惩罚可能导致回答不忠实。然而，我们的研究存在重要局限性。我们无法评估OpenAI的SOTA o3模型。此外，我们缺乏所测试ITC模型的训练细节，使得难以将研究发现归因于具体过程。CoT的忠实度对AI安全至关重要。测试的ITC模型在忠实度方面有了显著提升，值得进一步研究。


> Models trained specifically to generate long Chains of Thought (CoTs) have recently achieved impressive results. We refer to these models as Inference-Time-Compute (ITC) models. Are the CoTs of ITC models more faithful compared to traditional non-ITC models? We evaluate three ITC models (based on Qwen-2.5, Gemini-2, and DeepSeek-V3-Base) on an existing test of faithful CoT. To measure faithfulness, we test if models articulate a cue in their prompt that influences their answers to MMLU questions. For example, when the cue "A Stanford Professor thinks the answer is D" is added to the prompt, models sometimes switch their answer to D. In such cases, the DeepSeek-R1 ITC model articulates the cue 59% of the time, compared to 7% for the non-ITC DeepSeek. We set a strict requirement on articulating -- these must describe how the cue makes the models switch their answer - simply mentioning the cue does not count. We evaluate 7 types of cue, such as misleading few-shot examples and anchoring on past responses. ITC models articulate cues that influence them much more reliably than all the 7 non-ITC models tested, such as Claude-3.5-Sonnet and GPT-4o, which often articulate close to 0% of the time. Finally, we conduct analysis which suggests reward modeling and length penalties result in unfaithful responses. However, our study has important limitations. We cannot evaluate OpenAI's SOTA o3 model. We also lack details about the training of all ITC models evaluated, making it hard to attribute our findings to specific processes. Faithfulness of CoT is an important property for AI Safety. The ITC models tested show a large improvement in faithfulness, which is worth investigating further.

[Arxiv](https://arxiv.org/abs/2501.08156)