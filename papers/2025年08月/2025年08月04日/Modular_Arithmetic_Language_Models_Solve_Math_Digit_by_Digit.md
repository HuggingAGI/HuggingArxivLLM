# 模运算：语言模型逐位破解数学难题

发布时间：2025年08月04日

`LLM应用` `问答系统`

> Modular Arithmetic: Language Models Solve Math Digit by Digit

# 摘要

> <翻译失败>

> While recent work has begun to uncover the internal strategies that Large Language Models (LLMs) employ for simple arithmetic tasks, a unified understanding of their underlying mechanisms is still lacking. We extend recent findings showing that LLMs represent numbers in a digit-wise manner and present evidence for the existence of digit-position-specific circuits that LLMs use to perform simple arithmetic tasks, i.e. modular subgroups of MLP neurons that operate independently on different digit positions (units, tens, hundreds). Notably, such circuits exist independently of model size and of tokenization strategy, i.e. both for models that encode longer numbers digit-by-digit and as one token. Using Feature Importance and Causal Interventions, we identify and validate the digit-position-specific circuits, revealing a compositional and interpretable structure underlying the solving of arithmetic problems in LLMs. Our interventions selectively alter the model's prediction at targeted digit positions, demonstrating the causal role of digit-position circuits in solving arithmetic tasks.

[Arxiv](https://arxiv.org/abs/2508.02513)