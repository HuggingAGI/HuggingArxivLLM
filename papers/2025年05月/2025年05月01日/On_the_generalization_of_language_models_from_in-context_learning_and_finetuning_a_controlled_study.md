# 语言模型的上下文学习与微调泛化能力研究：一项控制性研究

发布时间：2025年05月01日

`LLM理论

摘要讨论了大型语言模型的泛化能力，比较了上下文学习与微调学习之间的差异，并提出了一种结合上下文推理的方法来改进微调后的模型。这些内容属于对语言模型学习机制和理论的研究，因此归类为LLM理论。` `人工智能`

> On the generalization of language models from in-context learning and finetuning: a controlled study

# 摘要

> 大型语言模型虽然能力出众，但在微调后却常表现出意料之外的狭窄泛化能力，例如无法推广到与其训练数据关系简单的反转，或是未能从训练信息中进行逻辑推理。这些微调后的泛化失败可能阻碍了这些模型的实际应用。然而，语言模型的上下文学习展现了不同的归纳偏置，能够在某些情况下更好地进行泛化。本研究旨在探讨上下文学习与基于微调学习之间的泛化差异。为此，我们构建了几个新颖的数据集，旨在评估和改进模型从微调数据中进行泛化的 ability。这些数据集的构建方式将数据集中的知识与预训练中的知识分离，从而创建干净的泛化测试。我们让预训练的大型模型接触这些数据集信息的受控子集——无论是通过上下文，还是通过微调——并在需要不同类型泛化的测试集上评估其性能。总体而言，我们发现，在数据匹配的设置下，上下文学习的泛化比微调更灵活（尽管我们也发现了一些先前研究的例外情况，例如当微调可以推广到嵌入在更大知识结构中的关系反转时）。基于这些发现，我们提出了一种方法，以实现从微调中改进泛化：在微调数据中添加上下文推理。我们展示了这种方法在我们的数据集和其它基准测试的不同分割上提高了泛化能力。我们的研究结果不仅对理解语言模型不同学习模式的归纳偏置具有重要意义，而且在实际应用中可以有效提升模型性能。

> Large language models exhibit exciting capabilities, yet can show surprisingly narrow generalization from finetuning -- from failing to generalize to simple reversals of relations they are trained on, to missing logical deductions that can be made from trained information. These failures to generalize from fine-tuning can hinder practical application of these models. However, language models' in-context learning shows different inductive biases, and can generalize better in some of these cases. Here, we explore these differences in generalization between in-context- and fine-tuning-based learning. To do so, we constructed several novel datasets to evaluate and improve models' ability to generalize from finetuning data. The datasets are constructed to isolate the knowledge in the dataset from that in pretraining, to create clean tests of generalization. We expose pretrained large models to controlled subsets of the information in these datasets -- either in context, or through fine-tuning -- and evaluate their performance on test sets that require various types of generalization. We find overall that in data-matched settings, in-context learning can generalize more flexibly than fine-tuning (though we also find some qualifications of prior findings, such as cases when fine-tuning can generalize to reversals embedded in a larger structure of knowledge). We build on these findings to propose a method to enable improved generalization from fine-tuning: adding in-context inferences to finetuning data. We show that this method improves generalization across various splits of our datasets and other benchmarks. Our results have implications for understanding the inductive biases of different modes of learning in language models, and practically improving their performance.

[Arxiv](https://arxiv.org/abs/2505.00661)