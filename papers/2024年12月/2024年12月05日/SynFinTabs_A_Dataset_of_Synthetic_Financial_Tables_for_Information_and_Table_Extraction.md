# SynFinTabs：一个用于信息与表格提取的合成金融表格数据集

发布时间：2024年12月05日

`LLM应用` `文档图像`

> SynFinTabs: A Dataset of Synthetic Financial Tables for Information and Table Extraction

# 摘要

> 从文档图像中提取表格是个颇具挑战性的 AI 难题，许多内容领域的标注数据都难以获取。现有的表格提取数据集往往因大量现成的学术文章及其源代码，而侧重于科学表格。然而，科学、金融等领域的表格在布局和排版上存在显著差异。当前的数据集通常缺少表格内的字词及其位置，而是依赖不可靠的 OCR 来提取这些特征，以用于自然语言处理任务中训练现代机器学习模型。所以，需要一种更通用的获取标注数据的办法。我们推出了 SynFinTabs，这是一个大规模的合成金融表格标注数据集。我们期望生成这些合成表格的方法能够应用于其他领域。为展示我们的数据集在训练模型从表格图像中提取信息方面的有效性，我们创建了 FinTabQA，这是一个基于提取式问答任务训练的布局大型语言模型。我们用真实的金融表格对模型进行测试，并将其与最先进的生成模型作比较，同时讨论结果。我们将数据集、模型和数据集生成代码公开。

> Table extraction from document images is a challenging AI problem, and labelled data for many content domains is difficult to come by. Existing table extraction datasets often focus on scientific tables due to the vast amount of academic articles that are readily available, along with their source code. However, there are significant layout and typographical differences between tables found across scientific, financial, and other domains. Current datasets often lack the words, and their positions, contained within the tables, instead relying on unreliable OCR to extract these features for training modern machine learning models on natural language processing tasks. Therefore, there is a need for a more general method of obtaining labelled data. We present SynFinTabs, a large-scale, labelled dataset of synthetic financial tables. Our hope is that our method of generating these synthetic tables is transferable to other domains. To demonstrate the effectiveness of our dataset in training models to extract information from table images, we create FinTabQA, a layout large language model trained on an extractive question-answering task. We test our model using real-world financial tables and compare it to a state-of-the-art generative model and discuss the results. We make the dataset, model, and dataset generation code publicly available.

[Arxiv](https://arxiv.org/abs/2412.04262)