# 跨语言的文本丰富型视觉理解：从信息论视角出发

发布时间：2024年12月23日

`LLM应用` `视觉语言模型` `跨语言处理`

> Cross-Lingual Text-Rich Visual Comprehension: An Information Theory Perspective

# 摘要

> 近期的大型视觉语言模型（LVLMs）在富含文本的图像（如图表、表格和文档）上展现出良好的推理能力。然而，这类图像中丰富的文本可能会增强模型对语言的敏感度。这使得我们有必要评估 LVLM 在跨语言且富含文本的视觉输入方面的性能，因为其中图像的语言与指令语言不同。为此，我们引入了 XT-VQA（跨语言富含文本的视觉问答）这一基准，用于评估 LVLMs 处理图像文本与问题之间语言不一致的情况。XT-VQA 整合了五个现有的富含文本的 VQA 数据集以及新收集的 XPaperQA 数据集，涵盖了多种即便存在语言不一致仍需准确识别和理解视觉信息的场景。我们对 XT-VQA 上知名 LVLMs 的评估表明，在跨语言场景中，即便对于具备多语言能力的模型，性能也大幅下降。互信息分析显示，这种性能差距源于跨语言问题未能充分激活相关视觉信息。为缓解此问题，我们提出了 MVCL-MI（视觉语言跨语言互信息最大化），通过最大化模型输出与视觉信息之间的互信息来建立视觉-文本跨语言对齐。这是通过 KL 散度最小化将单语言知识提炼到跨语言设置来实现的，其中单语言输出的对数几率充当教师。XT-VQA 上的实验结果表明，MVCL-MI 有效缩小了视觉-文本跨语言性能差距，同时保留了 LVLMs 的固有能力，为提升 LVLMs 提供了新的可能实践思路。代码可在：https://github.com/Stardust-y/XTVQA.git 获取。

> Recent Large Vision-Language Models (LVLMs) have shown promising reasoning capabilities on text-rich images from charts, tables, and documents. However, the abundant text within such images may increase the model's sensitivity to language. This raises the need to evaluate LVLM performance on cross-lingual text-rich visual inputs, where the language in the image differs from the language of the instructions. To address this, we introduce XT-VQA (Cross-Lingual Text-Rich Visual Question Answering), a benchmark designed to assess how LVLMs handle language inconsistency between image text and questions. XT-VQA integrates five existing text-rich VQA datasets and a newly collected dataset, XPaperQA, covering diverse scenarios that require faithful recognition and comprehension of visual information despite language inconsistency. Our evaluation of prominent LVLMs on XT-VQA reveals a significant drop in performance for cross-lingual scenarios, even for models with multilingual capabilities. A mutual information analysis suggests that this performance gap stems from cross-lingual questions failing to adequately activate relevant visual information. To mitigate this issue, we propose MVCL-MI (Maximization of Vision-Language Cross-Lingual Mutual Information), where a visual-text cross-lingual alignment is built by maximizing mutual information between the model's outputs and visual information. This is achieved by distilling knowledge from monolingual to cross-lingual settings through KL divergence minimization, where monolingual output logits serve as a teacher. Experimental results on the XT-VQA demonstrate that MVCL-MI effectively reduces the visual-text cross-lingual performance disparity while preserving the inherent capabilities of LVLMs, shedding new light on the potential practice for improving LVLMs. Codes are available at: https://github.com/Stardust-y/XTVQA.git

[Arxiv](https://arxiv.org/abs/2412.17787)