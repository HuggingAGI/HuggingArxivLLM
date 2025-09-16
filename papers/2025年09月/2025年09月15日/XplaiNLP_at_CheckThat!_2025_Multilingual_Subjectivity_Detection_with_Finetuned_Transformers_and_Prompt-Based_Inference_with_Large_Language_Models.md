# XplaiNLP团队于CheckThat! 2025：基于微调Transformer与提示驱动的大型语言模型推理的多语言主观性检测

发布时间：2025年09月15日

`LLM应用` `基础理论`

> XplaiNLP at CheckThat! 2025: Multilingual Subjectivity Detection with Finetuned Transformers and Prompt-Based Inference with Large Language Models

# 摘要

> 本笔记介绍了XplaiNLP团队参与CheckThat! 2025多语言主观性检测共享任务的成果。我们评估了两种方案：（1）在单语及机器翻译训练数据上对Transformer编码器（包括EuroBERT、XLM-RoBERTa和German-BERT）进行有监督微调；（2）基于两个大型语言模型的零样本提示：o3-mini用于Annotation（基于规则的标注），gpt-4.1-mini用于DoubleDown（对比重写）和Perspective（比较推理）。Annotation方法在意大利语单语子任务中表现最佳，F_1分数达0.8104，远超基线的0.6941。罗马尼亚语零样本任务中，微调后的XLM-RoBERTa模型F_1分数为0.7917，位列第3，同样高于基线的0.6461。该模型在多语言任务中表现稳定，在希腊语上也优于基线。德语任务中，基于类型学相关语言翻译数据微调的German-BERT模型性能优于基线，具有竞争力。然而，乌克兰语和波兰语的零样本性能略低于各自基线，这体现了低资源跨语言场景下的泛化难题。

> This notebook reports the XplaiNLP submission to the CheckThat! 2025 shared task on multilingual subjectivity detection. We evaluate two approaches: (1) supervised fine-tuning of transformer encoders, EuroBERT, XLM-RoBERTa, and German-BERT, on monolingual and machine-translated training data; and (2) zero-shot prompting using two LLMs: o3-mini for Annotation (rule-based labelling) and gpt-4.1-mini for DoubleDown (contrastive rewriting) and Perspective (comparative reasoning). The Annotation Approach achieves 1st place in the Italian monolingual subtask with an F_1 score of 0.8104, outperforming the baseline of 0.6941. In the Romanian zero-shot setting, the fine-tuned XLM-RoBERTa model obtains an F_1 score of 0.7917, ranking 3rd and exceeding the baseline of 0.6461. The same model also performs reliably in the multilingual task and improves over the baseline in Greek. For German, a German-BERT model fine-tuned on translated training data from typologically related languages yields competitive performance over the baseline. In contrast, performance in the Ukrainian and Polish zero-shot settings falls slightly below the respective baselines, reflecting the challenge of generalization in low-resource cross-lingual scenarios.

[Arxiv](https://arxiv.org/abs/2509.12130)