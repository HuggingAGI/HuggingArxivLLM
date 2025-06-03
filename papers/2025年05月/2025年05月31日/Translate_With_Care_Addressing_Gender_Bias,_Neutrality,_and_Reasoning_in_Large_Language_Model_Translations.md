# 谨慎翻译：关注大型语言模型翻译中的性别偏见、中立性与推理能力

发布时间：2025年05月31日

`LLM应用

分类解释：这篇论文探讨了机器翻译中的性别偏见和逻辑连贯性问题，并提出了一种新的数据集和微调方法来改进模型性能，属于将LLM应用于特定任务的范畴，因此归类为LLM应用。` `机器翻译`

> Translate With Care: Addressing Gender Bias, Neutrality, and Reasoning in Large Language Model Translations

# 摘要

> 机器翻译中的性别偏见和逻辑连贯性问题仍然具有挑战性，尤其是在处理英语等自然性别语言与波斯语、印度尼西亚语和芬兰语等无性别语言的翻译时。我们推出了Translate-with-Care (TWC) 数据集，涵盖六种低至中资源语言的3,950个具有挑战性的场景，用于评估翻译系统的性能表现。通过对GPT-4、mBART-50、NLLB-200和Google Translate等技术的分析，我们发现所有模型在翻译无性别内容时都面临着普遍的困难，导致性别刻板印象和推理错误。当性别刻板印象可能影响选择时，所有模型都更倾向于使用阳性代词。Google Translate和GPT-4显示出特别明显的偏见，在涉及领导力和职业成功的场景中，阳性代词的使用频率是阴性代词的4到6倍。通过对mBART-50进行TWC微调，我们成功解决了这些偏见和错误，实现了强大的泛化能力，并在保持开源的同时超越了专有LLM。这项研究强调了在机器翻译中采取定向方法解决性别和语义连贯性问题的重要性，特别是在无性别语言中，为构建更加公平和准确的翻译系统提供了重要贡献。

> Addressing gender bias and maintaining logical coherence in machine translation remains challenging, particularly when translating between natural gender languages, like English, and genderless languages, such as Persian, Indonesian, and Finnish. We introduce the Translate-with-Care (TWC) dataset, comprising 3,950 challenging scenarios across six low- to mid-resource languages, to assess translation systems' performance. Our analysis of diverse technologies, including GPT-4, mBART-50, NLLB-200, and Google Translate, reveals a universal struggle in translating genderless content, resulting in gender stereotyping and reasoning errors. All models preferred masculine pronouns when gender stereotypes could influence choices. Google Translate and GPT-4 showed particularly strong bias, favoring male pronouns 4-6 times more than feminine ones in leadership and professional success contexts. Fine-tuning mBART-50 on TWC substantially resolved these biases and errors, led to strong generalization, and surpassed proprietary LLMs while remaining open-source. This work emphasizes the need for targeted approaches to gender and semantic coherence in machine translation, particularly for genderless languages, contributing to more equitable and accurate translation systems.

[Arxiv](https://arxiv.org/abs/2506.00748)