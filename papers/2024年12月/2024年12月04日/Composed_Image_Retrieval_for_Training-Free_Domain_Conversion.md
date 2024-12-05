# 用于无训练域转换的组合图像检索

发布时间：2024年12月04日

`LLM应用` `图像检索` `域转换`

> Composed Image Retrieval for Training-Free Domain Conversion

# 摘要

> 这项工作着眼于域转换情境下的组合图像检索，即按照查询文本指定的域来检索查询图像的内容。我们发现，强大的视觉语言模型无需额外训练就具备足够的描述能力。利用文本反转，将查询图像映射到文本输入空间。和常见的在文本标记连续空间中反转的做法不同，我们通过在文本词汇表中进行最近邻搜索，使用离散词空间。经此反转，图像在词汇表中实现软性映射，并通过基于检索的增强变得更稳健。通过对结合了映射词与域文本的文本查询进行加权集成来检索数据库图像。我们的方法在标准及新引入的基准测试中，大幅领先于现有技术。代码：https://github.com/NikosEfth/freedom

> This work addresses composed image retrieval in the context of domain conversion, where the content of a query image is retrieved in the domain specified by the query text. We show that a strong vision-language model provides sufficient descriptive power without additional training. The query image is mapped to the text input space using textual inversion. Unlike common practice that invert in the continuous space of text tokens, we use the discrete word space via a nearest-neighbor search in a text vocabulary. With this inversion, the image is softly mapped across the vocabulary and is made more robust using retrieval-based augmentation. Database images are retrieved by a weighted ensemble of text queries combining mapped words with the domain text. Our method outperforms prior art by a large margin on standard and newly introduced benchmarks. Code: https://github.com/NikosEfth/freedom

[Arxiv](https://arxiv.org/abs/2412.03297)