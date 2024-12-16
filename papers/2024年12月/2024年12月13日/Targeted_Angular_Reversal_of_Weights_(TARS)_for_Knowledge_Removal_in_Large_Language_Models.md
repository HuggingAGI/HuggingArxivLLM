# 大型语言模型中用于知识去除的目标角度权重反转（TARS）

发布时间：2024年12月13日

`LLM应用` `语言模型` `知识去除`

> Targeted Angular Reversal of Weights (TARS) for Knowledge Removal in Large Language Models

# 摘要

> 训练现代大型语言模型（LLMs）所需的庞大数据量带来了显著风险，因为模型可能会获取像生物安全这类敏感主题的知识，还可能具备复制有版权作品的能力。旨在消除这类知识的方法必须能从所有提示方向，以多语言能力且不降低模型整体性能的方式来操作。为此，我们推出了从 LLMs 中去除知识的有针对性的角度反转（TARS）方法。TARS 方法先是把 LLM 与详细的提示相结合，在 LLM 的内部表示空间中汇总有关选定概念的信息。接着，通过给近似概念向量添加噪声并用语言模型头将其转化为令牌分数，来优化这个近似概念向量，以高概率触发概念令牌。直接作用于内部表示空间且与该目标向量余弦相似度最高的 LLM 中的前馈权重向量，随后会被反向目标向量取代，从而限制概念在模型中的传播。TARS 方法的模块化能够让我们从 Llama 3.1 8B 中依次去除概念，比如著名的文学侦探夏洛克·福尔摩斯和土星。事实证明，仅进行 1 次 TARS 编辑，触发目标概念的概率就能降到 0.00，同时双向去除知识。而且，尽管只是针对英语，在所有语言中都表明知识已被去除。重要的是，TARS 对模型的整体能力影响极小，因为以模块化方式去除 5 个不同概念后，在维基百科文本的大型语料库中，LLM 下一个令牌概率的最小 KL 散度（中位数为 0.002）。

> The sheer scale of data required to train modern large language models (LLMs) poses significant risks, as models are likely to gain knowledge of sensitive topics such as bio-security, as well the ability to replicate copyrighted works. Methods designed to remove such knowledge must do so from all prompt directions, in a multi-lingual capacity and without degrading general model performance. To this end, we introduce the targeted angular reversal (TARS) method of knowledge removal from LLMs. The TARS method firstly leverages the LLM in combination with a detailed prompt to aggregate information about a selected concept in the internal representation space of the LLM. It then refines this approximate concept vector to trigger the concept token with high probability, by perturbing the approximate concept vector with noise and transforming it into token scores with the language model head. The feedforward weight vectors in the LLM which operate directly on the internal representation space, and have the highest cosine similarity with this targeting vector, are then replaced by a reversed targeting vector, thus limiting the ability of the concept to propagate through the model. The modularity of the TARS method allows for a sequential removal of concepts from Llama 3.1 8B, such as the famous literary detective Sherlock Holmes, and the planet Saturn. It is demonstrated that the probability of triggering target concepts can be reduced to 0.00 with as few as 1 TARS edit, whilst simultaneously removing the knowledge bi-directionally. Moreover, knowledge is shown to be removed across all languages despite only being targeted in English. Importantly, TARS has minimal impact on the general model capabilities, as after removing 5 diverse concepts in a modular fashion, there is minimal KL divergence in the next token probabilities of the LLM on large corpora of Wikipedia text (median of 0.002).

[Arxiv](https://arxiv.org/abs/2412.10257)