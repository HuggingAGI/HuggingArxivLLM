# 为何止步于单词？行级OCR带你窥见更完整的图景

发布时间：2025年08月29日

`其他` `基础理论`

> Why Stop at Words? Unveiling the Bigger Picture through Line-Level OCR

# 摘要

> 传统光学字符识别（OCR）技术通常先分割单个字符，再进行识别。这种方式不仅在字符分割环节容易出错，还无法借助上下文来发挥语言模型的作用。过去十年，序列到序列翻译技术的进步催生了现代OCR方法：先检测单词，再将单个单词逐次输入模型，直接输出完整单词的字符序列。这不仅能更好地利用语言模型，还避开了易错的字符分割环节。我们发现，这种技术范式的转变将准确率瓶颈转移到了单词分割上。因此，本文提出了从单词级OCR向行级OCR的自然且合理的演进方案。该方案不仅能避开单词检测错误，还能提供更大的句子上下文，从而更好地发挥语言模型的作用。我们的研究表明，所提技术不仅提升了OCR的准确率，还提高了效率。尽管我们进行了全面的文献调研，但未发现任何公开数据集可用于训练和评估这种从单词级到行级OCR的转变。为此，我们还贡献了一个精心构建的数据集，包含251张带有行级标注的英文页面图像。实验结果显示，端到端准确率显著提升5.4%，突显了转向行级OCR的潜在优势，尤其适用于文档图像。与基于单词的处理流程相比，效率也提升了4倍。随着大型语言模型的持续发展，我们的方法也有望借助这些技术进步进一步提升。项目网站：https://nishitanand.github.io/line-level-ocr-website

> Conventional optical character recognition (OCR) techniques segmented each character and then recognized. This made them prone to error in character segmentation, and devoid of context to exploit language models. Advances in sequence to sequence translation in last decade led to modern techniques first detecting words and then inputting one word at a time to a model to directly output full words as sequence of characters. This allowed better utilization of language models and bypass error-prone character segmentation step. We observe that the above transition in style has moved the bottleneck in accuracy to word segmentation. Hence, in this paper, we propose a natural and logical progression from word level OCR to line-level OCR. The proposal allows to bypass errors in word detection, and provides larger sentence context for better utilization of language models. We show that the proposed technique not only improves the accuracy but also efficiency of OCR. Despite our thorough literature survey, we did not find any public dataset to train and benchmark such shift from word to line-level OCR. Hence, we also contribute a meticulously curated dataset of 251 English page images with line-level annotations. Our experimentation revealed a notable end-to-end accuracy improvement of 5.4%, underscoring the potential benefits of transitioning towards line-level OCR, especially for document images. We also report a 4 times improvement in efficiency compared to word-based pipelines. With continuous improvements in large language models, our methodology also holds potential to exploit such advances. Project Website: https://nishitanand.github.io/line-level-ocr-website

[Arxiv](https://arxiv.org/abs/2508.21693)