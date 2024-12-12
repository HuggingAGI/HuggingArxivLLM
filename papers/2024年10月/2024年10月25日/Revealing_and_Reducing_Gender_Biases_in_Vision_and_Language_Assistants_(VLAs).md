# 揭示并减少视觉和语言助手（VLAs）中的性别偏差

发布时间：2024年10月25日

`LLM应用` `多模态任务` `性别偏见评估`

> Revealing and Reducing Gender Biases in Vision and Language Assistants (VLAs)

# 摘要

> 预训练的大型语言模型（LLMs）已成功与视觉输入融合，用于多模态任务。像 LLaVA 和 InternVL 这类指令调优的图像转文本视觉语言助手（VLAs）被广泛应用，这使得评估性别偏见成为必要。我们针对 22 种热门开源 VLAs 在个性特质、技能和职业方面的性别偏见展开研究。结果显示，VLAs 重现了数据中可能存在的人类偏见，比如现实中的职业失衡。同样，它们往往认为女性比男性具备更多技能和积极的个性特质，并且存在将消极个性特质与男性关联的一贯趋势。为消除这些模型中的性别偏见，我们发现基于微调的去偏方法在去偏和保留下游任务性能之间达到了最佳平衡。我们提倡在 VLAs 中预先进行性别偏见评估，并激励进一步开发去偏策略，以保障公平的社会成果。

> Pre-trained large language models (LLMs) have been reliably integrated with visual input for multimodal tasks. The widespread adoption of instruction-tuned image-to-text vision-language assistants (VLAs) like LLaVA and InternVL necessitates evaluating gender biases. We study gender bias in 22 popular open-source VLAs with respect to personality traits, skills, and occupations. Our results show that VLAs replicate human biases likely present in the data, such as real-world occupational imbalances. Similarly, they tend to attribute more skills and positive personality traits to women than to men, and we see a consistent tendency to associate negative personality traits with men. To eliminate the gender bias in these models, we find that finetuning-based debiasing methods achieve the best tradeoff between debiasing and retaining performance on downstream tasks. We argue for pre-deploying gender bias assessment in VLAs and motivate further development of debiasing strategies to ensure equitable societal outcomes.

[Arxiv](https://arxiv.org/abs/2410.19314)