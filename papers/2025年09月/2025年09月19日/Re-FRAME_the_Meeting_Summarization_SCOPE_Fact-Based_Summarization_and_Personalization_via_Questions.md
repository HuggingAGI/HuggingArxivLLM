# 重构会议摘要的范畴：基于事实的摘要与问题驱动的个性化

发布时间：2025年09月19日

`LLM应用` `基础理论`

> Re-FRAME the Meeting Summarization SCOPE: Fact-Based Summarization and Personalization via Questions

# 摘要

> 用大型语言模型（LLMs）生成会议总结仍容易出错，输出常存在幻觉、遗漏和无关信息。为此，我们提出模块化流水线FRAME，它将总结重构为语义富集任务：提取关键事实并评分，按主题组织这些事实，再以此为基础将大纲扩展为抽象总结。为实现总结个性化，我们引入出声推理协议SCOPE：让模型在选择内容前回答九个问题，从而构建推理轨迹。评估方面，我们提出多维度无参考评估框架P-MESA，用于判断总结是否符合目标读者的需求。P-MESA能可靠识别错误实例，与人类标注相比平衡准确率≥89%，且与人类严重程度评分高度相关（相关系数r≥0.70）。在QMSum和FAME数据集上，FRAME将幻觉和遗漏减少了5分中的2分（以MESA衡量），而SCOPE在知识适配性和目标对齐上比仅用提示词的基线模型表现更优。我们的研究结果表明，应重新思考总结任务，以提升可控性、忠实性和个性化水平。

> Meeting summarization with large language models (LLMs) remains error-prone, often producing outputs with hallucinations, omissions, and irrelevancies. We present FRAME, a modular pipeline that reframes summarization as a semantic enrichment task. FRAME extracts and scores salient facts, organizes them thematically, and uses these to enrich an outline into an abstractive summary. To personalize summaries, we introduce SCOPE, a reason-out-loud protocol that has the model build a reasoning trace by answering nine questions before content selection. For evaluation, we propose P-MESA, a multi-dimensional, reference-free evaluation framework to assess if a summary fits a target reader. P-MESA reliably identifies error instances, achieving >= 89% balanced accuracy against human annotations and strongly aligns with human severity ratings (r >= 0.70). On QMSum and FAME, FRAME reduces hallucination and omission by 2 out of 5 points (measured with MESA), while SCOPE improves knowledge fit and goal alignment over prompt-only baselines. Our findings advocate for rethinking summarization to improve control, faithfulness, and personalization.

[Arxiv](https://arxiv.org/abs/2509.15901)