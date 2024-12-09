# 走向低代码平台的互操作

发布时间：2024年12月06日

`LLM应用` `软件开发` `低代码平台`

> Towards the interoperability of low-code platforms

# 摘要

> 随着加速软件开发的承诺，低代码平台（LCPs）在各行业日益流行。然而，其应用仍存在阻碍，供应商锁定便是主要问题之一，尤其是考虑到这些平台间缺乏互操作性。通常，在一个 LCP 中构建应用程序后，迁移到另一个平台就得从头开始重新构建一切（数据模型、图形用户界面、工作流等）。
  为应对此情况，本研究提出一种通过（半）自动将一个平台指定的模型迁移至另一平台来提升 LCPs 互操作性的方法。具体迁移路径取决于源工具和目标工具的能力。我们先对流行的 LCPs 进行分析，阐述其导入和导出的选择，并在可行时定义这些数据格式间的转换。此外，还辅以基于 LLM 的解决方案，利用大型语言模型的图像识别功能，依据手头模型的简单图像导出进行模型迁移。整个流程在 BESSER 建模框架之上实现，该框架充当了各工具间的枢纽表示。

> With the promise of accelerating software development, low-code platforms (LCPs) are becoming popular across various industries. Nevertheless, there are still barriers hindering their adoption. Among them, vendor lock-in is a major concern, especially considering the lack of interoperability between these platforms. Typically, after modeling an application in one LCP, migrating to another requires starting from scratch remodeling everything (the data model, the graphical user interface, workflows, etc.), in the new platform.
  To overcome this situation, this work proposes an approach to improve the interoperability of LCPs by (semi)automatically migrating models specified in one platform to another one. The concrete migration path depends on the capabilities of the source and target tools. We first analyze popular LCPs, characterize their import and export alternatives and define transformations between those data formats when available. This is then complemented with an LLM-based solution, where image recognition features of large language models are employed to migrate models based on a simple image export of the model at hand. The full pipelines are implemented on top of the BESSER modeling framework that acts as a pivot representation between the tools.

[Arxiv](https://arxiv.org/abs/2412.05075)