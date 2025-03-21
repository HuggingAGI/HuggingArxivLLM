# 转而聚焦神经机制的元学习方法

发布时间：2025年03月20日

`LLM理论` `人工智能` `理论计算机科学`

> Meta-Learning Neural Mechanisms rather than Bayesian Priors

# 摘要

> 儿童在接触数据量远小于大型语言模型所需的情况下仍能掌握语言。元学习被提出作为一种方法，将人类学习偏见融入神经网络架构，兼具符号模型的结构化泛化能力和神经网络模型的扩展性。但元学习究竟赋予了模型什么？我们研究了形式语言的元学习，发现与之前的主张相反，元训练的模型在基于简单性组织的数据集上进行元训练时，并没有学习到基于简单性的先验。相反，我们发现证据表明，元训练在模型中铭刻了神经机制（如计数器），这些机制在下游任务中充当网络的认知原语。最令人惊讶的是，我们发现，如果形式语言激励了有用神经机制的学习，那么对单一形式语言的元训练可以带来与对5000种不同形式语言进行元训练相同的改进。综合来看，我们的发现为高效元学习范式提供了实用启示，并为连接符号理论和神经机制提供了新的理论见解。

> Children acquire language despite being exposed to several orders of magnitude less data than large language models require. Meta-learning has been proposed as a way to integrate human-like learning biases into neural-network architectures, combining both the structured generalizations of symbolic models with the scalability of neural-network models. But what does meta-learning exactly imbue the model with? We investigate the meta-learning of formal languages and find that, contrary to previous claims, meta-trained models are not learning simplicity-based priors when meta-trained on datasets organised around simplicity. Rather, we find evidence that meta-training imprints neural mechanisms (such as counters) into the model, which function like cognitive primitives for the network on downstream tasks. Most surprisingly, we find that meta-training on a single formal language can provide as much improvement to a model as meta-training on 5000 different formal languages, provided that the formal language incentivizes the learning of useful neural mechanisms. Taken together, our findings provide practical implications for efficient meta-learning paradigms and new theoretical insights into linking symbolic theories and neural mechanisms.

[Arxiv](https://arxiv.org/abs/2503.16048)