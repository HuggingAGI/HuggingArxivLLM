# MiCull2 -- 挤奶顺序模拟乳腺炎传播

发布时间：2024年12月13日

`其他

理由：这篇论文主要讨论的是传染性乳腺炎病原体通过挤奶传播的模拟模型，属于生物学和农业科学的交叉领域，与计算机科学中的Agent、RAG、LLM应用、LLM理论等分类无关。因此，将其分类为其他。` `传染病`

> MiCull2 -- simulating mastitis transmission through milking order

# 摘要

> # 摘要
传染性乳腺炎病原体可通过挤奶传播，但之前的MiCull等模拟模型并未直接考虑这一点。我们重新实现了MiCull模型，模拟挤奶厅中病原体通过挤奶的传播。这一复杂性增加了计算量，并需结构化代码以便未来灵活使用。本文目标有三：一是用更快的编程语言实现新模型；二是描述新模型，特别是病原体通过挤奶的传播；三是比较三种挤奶顺序策略对乳腺内感染流行率和发病率的影响。模拟了500个牛群，每个200头奶牛，持续10年，并使用文献参数校准模型。我们假设挤奶顺序对疾病传播有显著影响，特别是临床感染奶牛先进入挤奶厅时。检查的挤奶顺序包括随机顺序、先挤或后挤临床病例。出乎意料的是，对于中等感染率的牛群，这些策略间差异不大。预计在感染率极高的牛群中差异会更明显。我们开发了基于挤奶顺序的乳腺炎病原体传播模拟模型，预计新版本MiCull将因其灵活性、适应性和快速计算而对研究人员和顾问有用。

> Contagious mastitis pathogens can be transmitted through milking. However, previously published simulation models, such as MiCull, have not directly taken this into account. We have reimplemented the MiCull model to model transmission of contagious mastitis pathogens through milking in a milking parlor. This additional complexity requires a substantial increase in computations and a need to structure the program code to make it more flexible for future use. The aim of this paper was threefold: First, to implement the new model in a faster programming language; secondly, to describe the new model, in particular transmission of a contagious mastitis pathogen through milking; and thirdly, to compare three different milking order strategies in regards to prevalence and incidence of intramammary infections. For each scenario, 500 herds with 200 cows each were simulated over 10 years. The model was calibrated using available mastitis parameters from the literature. We hypothesized that milking order should have a considerable effect on disease transmission, especially if the infected cows with clinical enter the milking parlor first and thereby have a high risk of infecting the following cows. The milking order scenarios examined were random milking order and milking clinical cases first, or last. Unexpectedly, there were no large differences between these scenarios for reasonably sized infection rates corresponding to a herd with a moderate level of clinical mastitis in the herd. Larger differences are expected to be found in herds with very high infection rates. We have developed a transmission simulation model of mastitis pathogens using a new mode of transmission by milking order. We expect that this new version of MiCull will be useful for both researchers and advisors since it is flexible, can be fitted to various in-herd situations and the computations are fast.

[Arxiv](https://arxiv.org/abs/2412.10165)