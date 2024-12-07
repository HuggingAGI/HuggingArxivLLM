# 让我们逐个变量来思考：大型语言模型能够实现临时的概率推理

发布时间：2024年12月02日

`LLM应用` `概率推理` `语言模型`

> Let's Think Var-by-Var: Large Language Models Enable Ad Hoc Probabilistic Reasoning

# 摘要

> 智力的一大特点是能够凭借“常识”去充实未详细说明的状况。我们打算从大型语言模型（LLMs）中提取这种常识，使其能用于概率推理。我们把研究重心放在像“新泽西州纽瓦克的爱彼迎房源价格是多少？”这类“猜测”问题上。在无法获取数据的情况下给出合理答案，需要借鉴并整合有关“价格”和“位置”与其他变量（比如“房产类型”）可能存在关系的常识片段。我们的框架通过构建一个临时的概率模型来回答此类问题。首先，提示LLM提出与问题相关的一组随机变量，接着对它们的联合分布给出矩约束。然后，在对数线性族内优化联合分布$p$，以最大程度地满足总体约束。实验表明，LLM能够成功地被提示提出合理变量，虽然给出的数值约束可能存在噪声，但共同优化以满足这些约束能对其进行协调。在对从三个真实世界的表格数据集中衍生出的概率问题进行评估时，我们发现我们的框架在与数据集分布的总变异距离方面和直接提示基线表现相当，并且对噪声同样具有较强的适应性。

> A hallmark of intelligence is the ability to flesh out underspecified situations using "common sense." We propose to extract that common sense from large language models (LLMs), in a form that can feed into probabilistic inference. We focus our investigation on $\textit{guesstimation}$ questions such as "How much are Airbnb listings in Newark, NJ?" Formulating a sensible answer without access to data requires drawing on, and integrating, bits of common knowledge about how $\texttt{Price}$ and $\texttt{Location}$ may relate to other variables, such as $\texttt{Property Type}$. Our framework answers such a question by synthesizing an $\textit{ad hoc}$ probabilistic model. First we prompt an LLM to propose a set of random variables relevant to the question, followed by moment constraints on their joint distribution. We then optimize the joint distribution $p$ within a log-linear family to maximize the overall constraint satisfaction. Our experiments show that LLMs can successfully be prompted to propose reasonable variables, and while the proposed numerical constraints can be noisy, jointly optimizing for their satisfaction reconciles them. When evaluated on probabilistic questions derived from three real-world tabular datasets, we find that our framework performs comparably to a direct prompting baseline in terms of total variation distance from the dataset distribution, and is similarly robust to noise.

[Arxiv](https://arxiv.org/abs/2412.02081)