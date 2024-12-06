# 利用背景运算符提升 LLMs 的数学推理能力

发布时间：2024年12月05日

`LLM应用` `语言模型`

> Enhancing Mathematical Reasoning in LLMs with Background Operators

# 摘要

> 我们提议在大型语言模型（LLMs）中运用背景算子来进行数学推理。为此，我们把一组基础数学谓词设定为基本构建模块。针对每个数学问题，我们开发出一个 Prolog 解决方案，其中涵盖特定问题的谓词以及由这些背景算子衍生出的中间谓词，保证每个解决方案都符合所定义的算子集合。我们引入了 MATH-Prolog 语料库，它源自 MATH 语料库的计数和概率类别。为实现有效的数据增强，我们采用 K 折交叉验证的自训练方法。该方法会为每折逐步生成新的 Prolog 解决方案，并在整个模型训练过程中，把那些被验证正确的解决方案纳入训练集。我们的实验结果显示，5 折交叉验证的自训练能够有效识别出新的、准确的 Prolog 解决方案，在交叉验证集上的准确率达 84.6％，在微调 Meta-Llama-3.1-8B-Instruct 模型的测试集上达 84.8％。这种方法成功为之前未曾见过的问题揭示出具有完全可计算推理步骤的新解决方案。另外，将背景数学谓词纳入提示能增强解决方案的覆盖范围。

> We propose utilizing background operators for mathematical reasoning in large language models (LLMs). To achieve this, we define a set of fundamental mathematical predicates as the basic building blocks. For each mathematical problem, we develop a Prolog solution that includes problem-specific predicates and intermediate predicates derived from these background operators, ensuring that each solution adheres to the defined operator set. We introduce the MATH-Prolog corpus, which is derived from the counting and probability categories of the MATH corpus. For efficient data augmentation, we apply K-fold cross-validated self-training. This method incrementally generates new Prolog solutions for each fold, incorporating those verified as correct into the training set throughout the model training process. Our experimental results demonstrate that 5-fold crossvalidated self-training effectively identifies new, accurate Prolog solutions, achieving an accuracy of 84.6% on the cross-validated set, and 84.8% on the test set during fine-tuning the Meta-Llama-3.1-8B-Instruct model. This approach successfully uncovers new solutions with fully computable inference steps for previously unseen problems. Additionally, incorporating the background mathematical predicates into the prompt enhances solution coverage.

[Arxiv](https://arxiv.org/abs/2412.04110)