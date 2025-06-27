# DrishtiKon：针对文本丰富文档图像的多粒度视觉定位

发布时间：2025年06月26日

`LLM应用` `文档智能` `视觉问答`

> DrishtiKon: Multi-Granular Visual Grounding for Text-Rich Document Images

# 摘要

> 文本丰富的文档图像中的视觉定位是文档智能和视觉问答（VQA）系统面临的关键挑战，这一领域尚未得到充分探索。我们推出\drishtikon——一个多粒度视觉定位框架，专为提升复杂多语言文档中VQA的可解释性和可信度而设计。我们的方法巧妙融合了强大的多语言OCR、大型语言模型和创新的区域匹配算法，能够在块、行、词和点等多个粒度级别精准定位答案。我们从CircularsVQA测试集中精心整理出一个全新的基准数据集，并为各粒度级别提供了细致且经过人工验证的标注。实验结果表明，我们的方法在定位精度上达到了当前最优水平，其中行级别粒度在精度与召回率之间实现了最佳平衡。通过消融实验，我们进一步验证了多块与多行推理的优势。与现有领先视觉语言模型的对比评估揭示了当前VLM在精准定位方面的局限性，充分证明了我们基于结构化对齐方法的有效性。我们的研究成果为在以文本为中心的现实场景中构建更 robust 且可解释的文档理解系统奠定了坚实基础。代码和数据集已开源，访问地址为https://github.com/kasuba-badri-vishal/DhrishtiKon。

> Visual grounding in text-rich document images is a critical yet underexplored challenge for document intelligence and visual question answering (VQA) systems. We present \drishtikon, a multi-granular visual grounding framework designed to enhance interpretability and trust in VQA for complex, multilingual documents. Our approach integrates robust multi-lingual OCR, large language models, and a novel region matching algorithm to accurately localize answer spans at block, line, word, and point levels. We curate a new benchmark from the CircularsVQA test set, providing fine-grained, human-verified annotations across multiple granularities. Extensive experiments demonstrate that our method achieves state-of-the-art grounding accuracy, with line-level granularity offering the best trade-off between precision and recall. Ablation studies further highlight the benefits of multi-block and multi-line reasoning. Comparative evaluations with leading vision-language models reveal the limitations of current VLMs in precise localization, underscoring the effectiveness of our structured, alignment-based approach. Our findings pave the way for more robust and interpretable document understanding systems in real-world, text-centric scenarios. Code and dataset has been made available at https://github.com/kasuba-badri-vishal/DhrishtiKon.

[Arxiv](https://arxiv.org/abs/2506.21316)