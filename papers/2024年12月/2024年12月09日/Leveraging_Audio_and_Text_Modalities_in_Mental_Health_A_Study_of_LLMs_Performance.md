# 音频与文本双模态在心理健康中的应用：LLMs 性能探析

发布时间：2024年12月09日

`LLM应用

**理由**：这篇论文探讨了大型语言模型（LLMs）在多模态心理健康诊断中的应用，特别是通过文本和音频模态来检测抑郁症和创伤后应激障碍。研究涉及了多模态融合对诊断准确性的提升，并使用了Gemini 1.5 Pro和GPT-4o mini等模型进行实验。这些内容直接涉及LLM在实际应用中的使用和性能评估，因此应归类为LLM应用。` `心理健康` `多模态诊断`

> Leveraging Audio and Text Modalities in Mental Health: A Study of LLMs Performance

# 摘要

> # 摘要
全球心理健康问题日益严重，亟需创新工具助力早期诊断与干预。本研究探索了大型语言模型（LLMs）在多模态心理健康诊断中的应用潜力，特别是通过文本和音频模态检测抑郁症和创伤后应激障碍。基于E-DAIC数据集，我们对比了文本与音频模态，探究LLMs在音频输入下的表现是否更优。进一步，我们研究了多模态融合对诊断准确性的提升效果，通常能带来性能指标的显著改善。我们特别设计了模态优势分数和分歧解决分数两个指标，评估多模态融合对模型性能的影响。Gemini 1.5 Pro模型在多模态融合下的二元抑郁症分类中表现最佳，F1得分为0.67，平衡准确率（BA）达77.4%，较文本模态提升3.1%，较音频模态提升2.7%，充分展现了多模态融合提升诊断准确性的优势。值得注意的是，所有结果均在零样本推断中获得，无需任务特定微调，凸显了模型的强大泛化能力。我们还通过零样本和少样本提示进行了二元、严重性和多类任务，研究了不同提示对模型性能的影响。结果显示，Gemini 1.5 Pro在文本和音频模态中，以及GPT-4o mini在文本模态中，通常在多个任务中的平衡准确率和F1得分上表现优异。

> Mental health disorders are increasingly prevalent worldwide, creating an urgent need for innovative tools to support early diagnosis and intervention. This study explores the potential of Large Language Models (LLMs) in multimodal mental health diagnostics, specifically for detecting depression and Post Traumatic Stress Disorder through text and audio modalities. Using the E-DAIC dataset, we compare text and audio modalities to investigate whether LLMs can perform equally well or better with audio inputs. We further examine the integration of both modalities to determine if this can enhance diagnostic accuracy, which generally results in improved performance metrics. Our analysis specifically utilizes custom-formulated metrics; Modal Superiority Score and Disagreement Resolvement Score to evaluate how combined modalities influence model performance. The Gemini 1.5 Pro model achieves the highest scores in binary depression classification when using the combined modality, with an F1 score of 0.67 and a Balanced Accuracy (BA) of 77.4%, assessed across the full dataset. These results represent an increase of 3.1% over its performance with the text modality and 2.7% over the audio modality, highlighting the effectiveness of integrating modalities to enhance diagnostic accuracy. Notably, all results are obtained in zero-shot inferring, highlighting the robustness of the models without requiring task-specific fine-tuning. To explore the impact of different configurations on model performance, we conduct binary, severity, and multiclass tasks using both zero-shot and few-shot prompts, examining the effects of prompt variations on performance. The results reveal that models such as Gemini 1.5 Pro in text and audio modalities, and GPT-4o mini in the text modality, often surpass other models in balanced accuracy and F1 scores across multiple tasks.

[Arxiv](https://arxiv.org/abs/2412.10417)