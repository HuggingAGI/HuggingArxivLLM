# TraveLLaMA：助力多模态大型语言模型理解城市场景并提供旅行辅助

发布时间：2025年04月23日

`LLM应用

摘要分析：这篇论文介绍了TraveLLaMA，一个专为城市旅行辅助设计的多模态语言模型。它通过特定数据集进行微调，提升在旅行任务中的性能，属于将LLM应用于特定领域的实例。` `旅行规划`

> TraveLLaMA: Facilitating Multi-modal Large Language Models to Understand Urban Scenes and Provide Travel Assistance

# 摘要

> 旅游与旅行规划越来越依赖数字辅助，但现有的多模态AI系统在城市环境的专门知识和情境理解上仍有欠缺。我们推出了TraveLLaMA，一款专为城市场景理解和旅行辅助设计的多模态语言模型。通过一个包含22万问答对的新型大规模数据集，我们解决了开发实用AI旅行助手的核心挑战。这一独特的数据集结合了13万精心挑选自真实旅行论坛的文本问答对（附带GPT增强回复），以及9万专注于地图理解和场景感知的视觉-语言问答对。通过对当前最先进的视觉-语言模型（LLaVA、Qwen-VL、Shikra）进行广泛微调实验，我们在纯文本旅行理解和视觉问答任务中均实现了6.5%-9.4%的显著性能提升。TraveLLaMA在提供情境化旅行建议、解读地图位置、理解特定场景图像的同时，还能提供实用信息如营业时间及游客评价。对比评估显示，TraveLLaMA在特定旅行任务中显著超越通用模型，为多模态旅行辅助系统树立了新的标杆。

> Tourism and travel planning increasingly rely on digital assistance, yet existing multimodal AI systems often lack specialized knowledge and contextual understanding of urban environments. We present TraveLLaMA, a specialized multimodal language model designed for urban scene understanding and travel assistance. Our work addresses the fundamental challenge of developing practical AI travel assistants through a novel large-scale dataset of 220k question-answer pairs. This comprehensive dataset uniquely combines 130k text QA pairs meticulously curated from authentic travel forums with GPT-enhanced responses, alongside 90k vision-language QA pairs specifically focused on map understanding and scene comprehension. Through extensive fine-tuning experiments on state-of-the-art vision-language models (LLaVA, Qwen-VL, Shikra), we demonstrate significant performance improvements ranging from 6.5\%-9.4\% in both pure text travel understanding and visual question answering tasks. Our model exhibits exceptional capabilities in providing contextual travel recommendations, interpreting map locations, and understanding place-specific imagery while offering practical information such as operating hours and visitor reviews. Comparative evaluations show TraveLLaMA significantly outperforms general-purpose models in travel-specific tasks, establishing a new benchmark for multi-modal travel assistance systems.

[Arxiv](https://arxiv.org/abs/2504.16505)