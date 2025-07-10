# Speak2Sign3D：一个多模态管道，实现英文语音到美式手语动画的转换

发布时间：2025年07月09日

`其他` `手语翻译` `3D动画`

> Speak2Sign3D: A Multi-modal Pipeline for English Speech to American Sign Language Animation

# 摘要

> 自动手语翻译的核心目标是帮助聋哑人和听力障碍者实现更便捷的交流。尽管过去的研究主要集中在将手语转换为文字，但将英语口语转化为手语动画这一方向却鲜有问津。这是因为该过程涉及语音识别、语法转换和动作生成等多个复杂环节。在本研究中，我们开发了一套完整的 pipeline，能够将英语语音无缝转换为流畅且逼真的3D手语动画。我们的系统首先借助Whisper将英语口语转化为文字，随后利用MarianMT机器翻译模型将其翻译成美国手语（ASL）的 gloss（一种简化版手语，专注于传达含义而不拘泥于语法）。该模型表现优异，BLEU值分别达到0.7714和0.8923。为了进一步提升 gloss 翻译的准确性，我们引入了Word2Vec和FastText等词嵌入技术，深入理解词汇含义。最后，我们采用基于3D关键点的运动系统对 gloss 进行动画处理，该系统是在我们构建的Sign3D-WLASL数据集上进行训练的。这个数据集通过从WLASL数据集中的真实ASL视频中提取身体、手部和面部关键点创建而成。为了支持 gloss 翻译阶段，我们还开发了一个名为BookGlossCorpus-CG的新数据集，它将BookCorpus数据集中的日常英语句子转化为ASL gloss，遵循语法规则。我们的系统通过在符号之间进行平滑插值，将所有环节有机整合，生成自然流畅的动画效果。与专注于识别或仅使用单一数据类型的先前研究（如How2Sign和Phoenix-2014T）不同，我们的 pipeline 将音频、文本和动作完美结合，构建了一个统一的框架，实现了从英语口语到逼真3D手语动画的完整转换。

> Helping deaf and hard-of-hearing people communicate more easily is the main goal of Automatic Sign Language Translation. Although most past research has focused on turning sign language into text, doing the reverse, turning spoken English into sign language animations, has been largely overlooked. That's because it involves multiple steps, such as understanding speech, translating it into sign-friendly grammar, and generating natural human motion. In this work, we introduce a complete pipeline that converts English speech into smooth, realistic 3D sign language animations. Our system starts with Whisper to translate spoken English into text. Then, we use a MarianMT machine translation model to translate that text into American Sign Language (ASL) gloss, a simplified version of sign language that captures meaning without grammar. This model performs well, reaching BLEU scores of 0.7714 and 0.8923. To make the gloss translation more accurate, we also use word embeddings such as Word2Vec and FastText to understand word meanings. Finally, we animate the translated gloss using a 3D keypoint-based motion system trained on Sign3D-WLASL, a dataset we created by extracting body, hand, and face key points from real ASL videos in the WLASL dataset. To support the gloss translation stage, we also built a new dataset called BookGlossCorpus-CG, which turns everyday English sentences from the BookCorpus dataset into ASL gloss using grammar rules. Our system stitches everything together by smoothly interpolating between signs to create natural, continuous animations. Unlike previous works like How2Sign and Phoenix-2014T that focus on recognition or use only one type of data, our pipeline brings together audio, text, and motion in a single framework that goes all the way from spoken English to lifelike 3D sign language animation.

[Arxiv](https://arxiv.org/abs/2507.06530)