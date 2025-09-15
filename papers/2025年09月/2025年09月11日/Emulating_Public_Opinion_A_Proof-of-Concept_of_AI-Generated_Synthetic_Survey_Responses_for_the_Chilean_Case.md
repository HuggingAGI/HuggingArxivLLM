# 模拟公众舆论：AI生成智利合成调查回应的概念验证

发布时间：2025年09月11日

`LLM应用` `基础理论`

> Emulating Public Opinion: A Proof-of-Concept of AI-Generated Synthetic Survey Responses for the Chilean Case

# 摘要

> 大型语言模型（LLMs）借助合成受访者模拟人类的回答与行为，为调查研究的方法学及应用创新开辟了广阔前景，有望减轻测量误差与代表性误差。但LLMs对项目总体分布的还原程度尚不明确，其下游应用还可能复制训练数据中继承的社会刻板印象与偏见。我们以智利公众意见概率抽样调查的真实人类回答为基准，评估了LLM生成的合成调查回答的可靠性。具体而言，我们对128个提示-模型-问题三元组进行了基准测试，生成189,696个合成档案，并在128个问题-子样本对的元分析中汇总了性能指标（即准确率、精确率、召回率及F1分数），以检验关键社会人口统计学维度上的偏差。评估涵盖OpenAI的GPT系列、o系列推理模型，以及Llama和Qwen的模型checkpoint。研究结果有三点尤为突出：一是合成回答在信任类项目上表现优异（F1分数与准确率均>0.90）；二是GPT-4o、GPT-4o-mini与Llama 4 Maverick在该任务上表现相当；三是45-59岁受访者的合成-人类回答一致性最高。总体而言，基于LLM的合成样本虽能接近概率抽样样本的回答，但存在显著的项目层面异质性。要捕捉公众意见的全部细微差别仍颇具挑战，需通过仔细校准及额外的分布测试来确保算法保真度并减少误差。

> Large Language Models (LLMs) offer promising avenues for methodological and applied innovations in survey research by using synthetic respondents to emulate human answers and behaviour, potentially mitigating measurement and representation errors. However, the extent to which LLMs recover aggregate item distributions remains uncertain and downstream applications risk reproducing social stereotypes and biases inherited from training data. We evaluate the reliability of LLM-generated synthetic survey responses against ground-truth human responses from a Chilean public opinion probabilistic survey. Specifically, we benchmark 128 prompt-model-question triplets, generating 189,696 synthetic profiles, and pool performance metrics (i.e., accuracy, precision, recall, and F1-score) in a meta-analysis across 128 question-subsample pairs to test for biases along key sociodemographic dimensions. The evaluation spans OpenAI's GPT family and o-series reasoning models, as well as Llama and Qwen checkpoints. Three results stand out. First, synthetic responses achieve excellent performance on trust items (F1-score and accuracy > 0.90). Second, GPT-4o, GPT-4o-mini and Llama 4 Maverick perform comparably on this task. Third, synthetic-human alignment is highest among respondents aged 45-59. Overall, LLM-based synthetic samples approximate responses from a probabilistic sample, though with substantial item-level heterogeneity. Capturing the full nuance of public opinion remains challenging and requires careful calibration and additional distributional tests to ensure algorithmic fidelity and reduce errors.

[Arxiv](https://arxiv.org/abs/2509.09871)