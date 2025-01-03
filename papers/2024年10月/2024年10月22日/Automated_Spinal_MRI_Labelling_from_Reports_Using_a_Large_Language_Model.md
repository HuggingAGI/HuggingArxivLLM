# 基于大型语言模型的脊柱MRI报告自动标注

发布时间：2024年10月22日

`LLM应用

理由：这篇论文描述了一种利用大型语言模型（LLM）来自动提取放射学报告中的标签的方法，并将其应用于脊柱MRI报告。这种方法展示了LLM在实际医疗应用中的潜力，属于LLM在特定领域（医疗影像分析）中的应用。因此，将其分类为“LLM应用”是合适的。` `放射学`

> Automated Spinal MRI Labelling from Reports Using a Large Language Model

# 摘要

> 我们提出了一种通用流程，利用大型语言模型自动从放射学报告中提取标签，并在脊柱MRI报告中进行了验证。我们的标签方法在五种不同条件下（脊柱癌症、狭窄、脊椎滑脱、马尾神经压迫和椎间盘突出）表现出色。使用开源模型，我们的方法在一组保留报告上的表现与GPT-4相当甚至更优。此外，提取的标签可用于训练成像模型，以分类伴随MR扫描中的识别条件。所有使用自动标签训练的分类器均达到了与临床医生手动注释的扫描训练的模型相当的性能。代码详见https://github.com/robinyjpark/AutoLabelClassifier。

> We propose a general pipeline to automate the extraction of labels from radiology reports using large language models, which we validate on spinal MRI reports. The efficacy of our labelling method is measured on five distinct conditions: spinal cancer, stenosis, spondylolisthesis, cauda equina compression and herniation. Using open-source models, our method equals or surpasses GPT-4 on a held-out set of reports. Furthermore, we show that the extracted labels can be used to train imaging models to classify the identified conditions in the accompanying MR scans. All classifiers trained using automated labels achieve comparable performance to models trained using scans manually annotated by clinicians. Code can be found at https://github.com/robinyjpark/AutoLabelClassifier.

[Arxiv](https://arxiv.org/abs/2410.17235)