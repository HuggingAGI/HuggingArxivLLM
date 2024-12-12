# DocSum：针对文档抽象摘要的领域自适应预训练

发布时间：2024年12月11日

`LLM应用` `文件处理`

> DocSum: Domain-Adaptive Pre-training for Document Abstractive Summarization

# 摘要

> 摘要
抽象式摘要在将大量文本凝练并重新表述为连贯摘要方面成果显著。但由于特定领域术语、OCR 生成的错误以及用于模型微调的标注数据集稀缺，行政文件的摘要工作面临独特挑战。现有模型通常难以适应此类文件的复杂结构和专业内容。为应对这些局限，我们推出了 DocSum，这是一个专为行政文件打造的领域自适应抽象式摘要框架。借助对 OCR 转录文本的预训练以及创新整合问答对进行微调，DocSum 提升了摘要的准确性和相关性。此方法化解了行政内容固有的复杂性，确保输出符合现实业务需求。为评估其能力，我们定义了一个全新的下游任务设置——文档抽象式摘要，它反映了商业和组织环境的实际要求。全面实验表明，DocSum 在生成高质量摘要方面成效显著，展现出其在公共和私营部门改进决策和运营工作流程的潜力。

> Abstractive summarization has made significant strides in condensing and rephrasing large volumes of text into coherent summaries. However, summarizing administrative documents presents unique challenges due to domain-specific terminology, OCR-generated errors, and the scarcity of annotated datasets for model fine-tuning. Existing models often struggle to adapt to the intricate structure and specialized content of such documents. To address these limitations, we introduce DocSum, a domain-adaptive abstractive summarization framework tailored for administrative documents. Leveraging pre-training on OCR-transcribed text and fine-tuning with an innovative integration of question-answer pairs, DocSum enhances summary accuracy and relevance. This approach tackles the complexities inherent in administrative content, ensuring outputs that align with real-world business needs. To evaluate its capabilities, we define a novel downstream task setting-Document Abstractive Summarization-which reflects the practical requirements of business and organizational settings. Comprehensive experiments demonstrate DocSum's effectiveness in producing high-quality summaries, showcasing its potential to improve decision-making and operational workflows across the public and private sectors.

[Arxiv](https://arxiv.org/abs/2412.08196)