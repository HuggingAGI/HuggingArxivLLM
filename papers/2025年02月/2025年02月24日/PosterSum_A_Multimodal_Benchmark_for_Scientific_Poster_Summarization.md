# # PosterSum：一个多模态科学海报摘要生成基准测试

发布时间：2025年02月24日

`LLM应用` `多模态处理`

> PosterSum: A Multimodal Benchmark for Scientific Poster Summarization

# 摘要

> 从多模态文档中生成准确且简洁的文本摘要是一项极具挑战性的任务，尤其是在处理视觉复杂的内容如科学海报时。为此，我们推出了 PosterSum，这是一个全新的基准测试，旨在推动视觉-语言模型的发展，使其能够理解和将科学海报总结为研究论文摘要。我们的数据集包含 16,305 份会议海报及其对应的摘要作为参考。每份海报以图像格式呈现，并包含多种视觉理解挑战，例如复杂的布局、密集的文本区域、表格和图表。我们在 PosterSum 上对最先进的多模态大型语言模型 (MLLMs) 进行了全面评估，结果发现它们在准确解读和总结科学海报方面仍存在困难。为此，我们提出了一种名为 Segment & Summarize 的分层方法，该方法在自动化评估指标上显著优于现有的 MLLMs，ROUGE-L 分数提高了 3.14%。这一成果将为未来关于海报总结的研究提供重要的参考和起点。

> Generating accurate and concise textual summaries from multimodal documents is challenging, especially when dealing with visually complex content like scientific posters. We introduce PosterSum, a novel benchmark to advance the development of vision-language models that can understand and summarize scientific posters into research paper abstracts. Our dataset contains 16,305 conference posters paired with their corresponding abstracts as summaries. Each poster is provided in image format and presents diverse visual understanding challenges, such as complex layouts, dense text regions, tables, and figures. We benchmark state-of-the-art Multimodal Large Language Models (MLLMs) on PosterSum and demonstrate that they struggle to accurately interpret and summarize scientific posters. We propose Segment & Summarize, a hierarchical method that outperforms current MLLMs on automated metrics, achieving a 3.14% gain in ROUGE-L. This will serve as a starting point for future research on poster summarization.

[Arxiv](https://arxiv.org/abs/2502.17540)