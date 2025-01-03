# 数字守护者：GPT-4、Perspective API 和 Moderation API 能可靠识别德国在线报纸读者评论中的仇恨言论吗？

发布时间：2025年01月02日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（如GPT-4o）来自动检测和过滤互联网上的有毒内容和仇恨言论。论文通过实验比较了不同模型在特定数据集上的表现，并展示了GPT-4o在检测任务中的优越性。这属于大型语言模型在实际应用中的具体使用场景，因此分类为LLM应用。` `内容审核` `社交媒体`

> Digital Guardians: Can GPT-4, Perspective API, and Moderation API reliably detect hate speech in reader comments of German online newspapers?

# 摘要

> 近年来，互联网上的有毒内容和仇恨言论日益泛滥。在线报纸和论坛的版主们不得不根据法律规定，仔细审查并删除不当的读者评论，这一过程费时费力。目前，一些大型语言模型提供商已推出自动检测仇恨言论和有毒内容的解决方案，如OpenAI的GPT-4o、谷歌Jigsaw的Perspective API以及OpenAI的Moderation API。基于专门用于检测在线报纸读者评论中仇恨言论的德国测试数据集HOCON34k，这些解决方案被相互比较，并与HOCON34k基线进行对比。测试数据集包含1,592个标注文本样本。针对GPT-4o，我们采用了零-shot、一-shot和少-shot三种提示方法。实验结果显示，GPT-4o在MCC和F2-score的综合指标上表现优异，不仅超越了Perspective API和Moderation API，还比HOCON34k基线高出约5个百分点。

> In recent years, toxic content and hate speech have become widespread phenomena on the internet. Moderators of online newspapers and forums are now required, partly due to legal regulations, to carefully review and, if necessary, delete reader comments. This is a labor-intensive process. Some providers of large language models already offer solutions for automated hate speech detection or the identification of toxic content. These include GPT-4o from OpenAI, Jigsaw's (Google) Perspective API, and OpenAI's Moderation API. Based on the selected German test dataset HOCON34k, which was specifically created for developing tools to detect hate speech in reader comments of online newspapers, these solutions are compared with each other and against the HOCON34k baseline. The test dataset contains 1,592 annotated text samples. For GPT-4o, three different promptings are used, employing a Zero-Shot, One-Shot, and Few-Shot approach. The results of the experiments demonstrate that GPT-4o outperforms both the Perspective API and the Moderation API, and exceeds the HOCON34k baseline by approximately 5 percentage points, as measured by a combined metric of MCC and F2-score.

[Arxiv](https://arxiv.org/abs/2501.01256)