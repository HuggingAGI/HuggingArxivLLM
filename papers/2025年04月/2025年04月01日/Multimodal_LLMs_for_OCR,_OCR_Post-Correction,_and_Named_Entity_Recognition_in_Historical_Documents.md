# 多模态 LLM 在 OCR、OCR 后校正及历史文档命名实体识别中的研究

发布时间：2025年04月01日

`LLM应用

摘要中提到多模态大语言模型（mLLMs）在历史文档处理中的应用，包括OCR、OCR后校正和命名实体识别任务，展示了其在实际问题中的效果，属于具体的应用场景。` `文档处理`

> Multimodal LLMs for OCR, OCR Post-Correction, and Named Entity Recognition in Historical Documents

# 摘要

> 我们研究了多模态大语言模型（mLLMs）在历史文档处理中的潜力，具体包括转录、信息提取和数据集构建。我们选取了1754年至1870年间出版的德文城市目录，重点考察了mLLMs在光学字符识别（OCR）、OCR后校正和命名实体识别（NER）任务中的表现。首先，我们对比了mLLMs与传统OCR模型的转录效果，发现最佳mLLM模型显著优于现有OCR技术。其次，我们开创性地将mLLMs用于OCR后校正，结果显示这一方法无需预处理或微调，即可将转录准确率提升至<1% CER。最后，我们证明了mLLMs能够高效解析历史文档中的实体信息并生成结构化数据。这些发现表明，mLLMs有望彻底改变历史数据收集与文档处理的方式。


> We explore how multimodal Large Language Models (mLLMs) can help researchers transcribe historical documents, extract relevant historical information, and construct datasets from historical sources. Specifically, we investigate the capabilities of mLLMs in performing (1) Optical Character Recognition (OCR), (2) OCR Post-Correction, and (3) Named Entity Recognition (NER) tasks on a set of city directories published in German between 1754 and 1870. First, we benchmark the off-the-shelf transcription accuracy of both mLLMs and conventional OCR models. We find that the best-performing mLLM model significantly outperforms conventional state-of-the-art OCR models and other frontier mLLMs. Second, we are the first to introduce multimodal post-correction of OCR output using mLLMs. We find that this novel approach leads to a drastic improvement in transcription accuracy and consistently produces highly accurate transcriptions (<1% CER), without any image pre-processing or model fine-tuning. Third, we demonstrate that mLLMs can efficiently recognize entities in transcriptions of historical documents and parse them into structured dataset formats. Our findings provide early evidence for the long-term potential of mLLMs to introduce a paradigm shift in the approaches to historical data collection and document transcription.

[Arxiv](https://arxiv.org/abs/2504.00414)