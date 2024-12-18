# 关于黑箱大型语言模型校准过程的调研

发布时间：2024年12月17日

`LLM应用` `语言模型` `模型校准`

> A Survey of Calibration Process for Black-Box LLMs

# 摘要

> 大型语言模型（LLMs）在语义理解和生成上表现出众，然而准确评估其输出的可靠性依旧是个重大难题。虽然众多研究探索了校准技术，可它们主要着眼于参数可访问的白盒 LLMs。黑盒 LLMs 尽管性能出色，但因其仅能通过 API 交互的限制，对校准技术的要求更高。尽管近期在黑盒 LLMs 校准方面有了突破，可对这些方法的系统调研仍很欠缺。为填补这一空白，我们给出了针对黑盒 LLMs 校准技术的首次全面调研。我们先把 LLMs 的校准过程定义为包含两个相互关联的关键步骤：置信度估计和校准。接着，我们对黑盒环境中的适用方法进行了系统梳理，并就实施这些关键步骤时的独特挑战和关联给出了见解。此外，我们探讨了校准过程在黑盒 LLMs 中的典型应用，描绘出了有前景的未来研究方向，为提升可靠性和人机协同提供了新视角。这是我们的 GitHub 链接：https://github.com/LiangruXie/Calibration-Process-in-Black-Box-LLMs

> Large Language Models (LLMs) demonstrate remarkable performance in semantic understanding and generation, yet accurately assessing their output reliability remains a significant challenge. While numerous studies have explored calibration techniques, they primarily focus on White-Box LLMs with accessible parameters. Black-Box LLMs, despite their superior performance, pose heightened requirements for calibration techniques due to their API-only interaction constraints. Although recent researches have achieved breakthroughs in black-box LLMs calibration, a systematic survey of these methodologies is still lacking. To bridge this gap, we presents the first comprehensive survey on calibration techniques for black-box LLMs. We first define the Calibration Process of LLMs as comprising two interrelated key steps: Confidence Estimation and Calibration. Second, we conduct a systematic review of applicable methods within black-box settings, and provide insights on the unique challenges and connections in implementing these key steps. Furthermore, we explore typical applications of Calibration Process in black-box LLMs and outline promising future research directions, providing new perspectives for enhancing reliability and human-machine alignment. This is our GitHub link: https://github.com/LiangruXie/Calibration-Process-in-Black-Box-LLMs

[Arxiv](https://arxiv.org/abs/2412.12767)