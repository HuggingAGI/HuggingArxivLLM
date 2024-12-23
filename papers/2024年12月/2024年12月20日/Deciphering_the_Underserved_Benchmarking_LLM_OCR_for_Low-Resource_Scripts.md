# 解读服务欠缺之处：针对低资源脚本为 LLM OCR 设立基准

发布时间：2024年12月20日

`LLM应用` `光学字符识别（OCR）` `低资源语言`

> Deciphering the Underserved: Benchmarking LLM OCR for Low-Resource Scripts

# 摘要

> 本研究探索了大型语言模型（LLMs），尤其是 GPT-4o，在乌尔都语、阿尔巴尼亚语和塔吉克语等低资源脚本中的光学字符识别（OCR）潜力，并以英语作为参照。通过使用精心整理的包含 2520 张图像的数据集，其中涵盖了文本长度、字体大小、背景颜色和模糊程度的受控变化，该研究模拟了多种现实世界的挑战。研究结果凸显了基于零样本 LLM 的 OCR 的局限性，特别是对于语言结构复杂的脚本，这表明需要有标注的数据集和经过微调的模型。此项工作突显了弥补文本数字化中可访问性差距的紧迫性，为针对资源匮乏语言的包容性强且稳健的 OCR 解决方案铺平了道路。

> This study investigates the potential of Large Language Models (LLMs), particularly GPT-4o, for Optical Character Recognition (OCR) in low-resource scripts such as Urdu, Albanian, and Tajik, with English serving as a benchmark. Using a meticulously curated dataset of 2,520 images incorporating controlled variations in text length, font size, background color, and blur, the research simulates diverse real-world challenges. Results emphasize the limitations of zero-shot LLM-based OCR, particularly for linguistically complex scripts, highlighting the need for annotated datasets and fine-tuned models. This work underscores the urgency of addressing accessibility gaps in text digitization, paving the way for inclusive and robust OCR solutions for underserved languages.

[Arxiv](https://arxiv.org/abs/2412.16119)