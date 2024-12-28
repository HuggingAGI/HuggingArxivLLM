# PromptDresser：借助生成性文本提示和提示感知掩码提升虚拟试穿的质量与可控性

发布时间：2024年12月22日

`LLM应用` `虚拟试穿`

> PromptDresser: Improving the Quality and Controllability of Virtual Try-On via Generative Textual Prompt and Prompt-aware Mask

# 摘要

> 近期的虚拟试穿方法通过微调预训练的文本到图像扩散模型，借助其强大的生成能力取得了进步。然而，虚拟试穿中对文本提示的运用仍有待深入探索。本文探讨了一个文本可编辑的虚拟试穿任务，它基于所提供的服装图像来改变服装款式，同时依照文本描述来调整穿着风格（如掖入风格、合身程度）。在这一文本可编辑的虚拟试穿中，存在三个关键要点：（一）为配对的人物与服装数据设计丰富的文本描述以训练模型；（二）解决现有人员服装的文本信息对新服装生成造成干扰的冲突；（三）自适应调整与文本描述相匹配的修复掩码，保证恰当的编辑区域，同时保留与新服装无关的原始人物外观。为应对这些要点，我们提出了 PromptDresser，这是一个文本可编辑的虚拟试穿模型，借助大型多模态模型（LMM）的协助，基于生成的文本提示实现高质量和多样化的操作。我们的方法通过上下文学习利用 LMM 为人物和服装图像独立生成详细的文本描述，涵盖姿势细节和编辑属性，人力成本极低。另外，为确保编辑区域，我们根据文本提示自适应调整修复掩码。我们发现，我们的方法利用详细的文本提示，不但增强了文本的可编辑性，还有效地传递了仅靠图像难以捕捉的服装细节，进而提升了图像质量。我们的代码可在 https://github.com/rlawjdghek/PromptDresser 获取。

> Recent virtual try-on approaches have advanced by fine-tuning the pre-trained text-to-image diffusion models to leverage their powerful generative ability. However, the use of text prompts in virtual try-on is still underexplored. This paper tackles a text-editable virtual try-on task that changes the clothing item based on the provided clothing image while editing the wearing style (e.g., tucking style, fit) according to the text descriptions. In the text-editable virtual try-on, three key aspects exist: (i) designing rich text descriptions for paired person-clothing data to train the model, (ii) addressing the conflicts where textual information of the existing person's clothing interferes the generation of the new clothing, and (iii) adaptively adjust the inpainting mask aligned with the text descriptions, ensuring proper editing areas while preserving the original person's appearance irrelevant to the new clothing. To address these aspects, we propose PromptDresser, a text-editable virtual try-on model that leverages large multimodal model (LMM) assistance to enable high-quality and versatile manipulation based on generative text prompts. Our approach utilizes LMMs via in-context learning to generate detailed text descriptions for person and clothing images independently, including pose details and editing attributes using minimal human cost. Moreover, to ensure the editing areas, we adjust the inpainting mask depending on the text prompts adaptively. We found that our approach, utilizing detailed text prompts, not only enhances text editability but also effectively conveys clothing details that are difficult to capture through images alone, thereby enhancing image quality. Our code is available at https://github.com/rlawjdghek/PromptDresser.

[Arxiv](https://arxiv.org/abs/2412.16978)