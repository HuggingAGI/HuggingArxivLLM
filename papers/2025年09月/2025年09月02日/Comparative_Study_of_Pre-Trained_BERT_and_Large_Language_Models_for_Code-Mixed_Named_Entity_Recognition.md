# 预训练BERT与大型语言模型在代码混合命名实体识别中的比较研究

发布时间：2025年09月02日

`LLM应用` `基础理论`

> Comparative Study of Pre-Trained BERT and Large Language Models for Code-Mixed Named Entity Recognition

# 摘要

> 语码混合文本（尤其是印地语-英语混合的Hinglish）中的命名实体识别（NER）面临独特挑战，这源于其非正规结构、音译现象及频繁的语言切换。本研究对语码混合微调模型、非语码混合多语言模型及零样本生成式大型语言模型（LLMs）展开了比较评估。具体而言，我们评估了HingBERT、HingMBERT和HingRoBERTa（均基于语码混合数据训练），以及BERT Base Cased、IndicBERT、RoBERTa和MuRIL（均基于非语码混合多语言数据训练）。我们还在零样本设置下，采用移除NER标签的数据集修改版本评估了Google Gemini的性能。所有模型均在基准Hinglish NER数据集上通过精确率、召回率和F1分数进行测试。结果显示，语码混合模型（尤其是基于HingRoBERTa和HingBERT的微调模型）凭借领域特定预训练，性能优于其他模型，包括Google Gemini等闭源LLM。非语码混合模型表现尚可，但适应性有限。值得注意的是，Google Gemini展现出极具竞争力的零样本性能，突显了现代LLM的泛化优势。本研究为语码混合NER任务中专用模型与通用模型的有效性对比提供了关键见解。

> Named Entity Recognition (NER) in code-mixed text, particularly Hindi-English (Hinglish), presents unique challenges due to informal structure, transliteration, and frequent language switching. This study conducts a comparative evaluation of code-mixed fine-tuned models and non-code-mixed multilingual models, along with zero-shot generative large language models (LLMs). Specifically, we evaluate HingBERT, HingMBERT, and HingRoBERTa (trained on code-mixed data), and BERT Base Cased, IndicBERT, RoBERTa and MuRIL (trained on non-code-mixed multilingual data). We also assess the performance of Google Gemini in a zero-shot setting using a modified version of the dataset with NER tags removed. All models are tested on a benchmark Hinglish NER dataset using Precision, Recall, and F1-score. Results show that code-mixed models, particularly HingRoBERTa and HingBERT-based fine-tuned models, outperform others - including closed-source LLMs like Google Gemini - due to domain-specific pretraining. Non-code-mixed models perform reasonably but show limited adaptability. Notably, Google Gemini exhibits competitive zero-shot performance, underlining the generalization strength of modern LLMs. This study provides key insights into the effectiveness of specialized versus generalized models for code-mixed NER tasks.

[Arxiv](https://arxiv.org/abs/2509.02514)