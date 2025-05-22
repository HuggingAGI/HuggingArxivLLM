# # DayDreamer亮相CQs-Gen 2025：通过论辩框架补全打造关键问题生成方案

发布时间：2025年05月21日

`LLM应用

论文摘要：批判性问题是引发批判性思维的重要资源，尤其在面对论证性文本时。本文介绍我们在ArgMining 2025共享任务中开发的批判性问题生成系统（CQs-Gen）。我们的方法结合大型语言模型（LLMs）和链式思维提示，根据沃尔顿的论辩方案生成批判性问题。对于每个输入的干预，我们通过对话式引导LLMs实例化相应的论辩方案模板，先提取结构化的论点，再生成相关批判性问题。随后，我们通过提示LLMs根据原始干预文本选择最相关的三个问题，对所有可用的批判性问题进行排序。这种将结构化论辩理论与逐步推理相结合的方法，能够生成上下文相关且多样化的批判性问题。我们的流水线在最终测试集中表现出色，证明其在促进批判性思维、识别缺失或未经充分研究的主张方面的潜力。代码可在\href{https://git.ecdf.ed.ac.uk/s2236454/DayDreamer-CQs-Gen}{DayDreamer}获取。

LLM应用` `学术研究`

> DayDreamer at CQs-Gen 2025: Generating Critical Questions through Argument Scheme Completion

# 摘要

> 批判性问题是引发批判性思维的重要资源，尤其在面对论证性文本时。本文介绍我们在ArgMining 2025共享任务中开发的批判性问题生成系统（CQs-Gen）。我们的方法结合大型语言模型（LLMs）和链式思维提示，根据沃尔顿的论辩方案生成批判性问题。对于每个输入的干预，我们通过对话式引导LLMs实例化相应的论辩方案模板，先提取结构化的论点，再生成相关批判性问题。随后，我们通过提示LLMs根据原始干预文本选择最相关的三个问题，对所有可用的批判性问题进行排序。这种将结构化论辩理论与逐步推理相结合的方法，能够生成上下文相关且多样化的批判性问题。我们的流水线在最终测试集中表现出色，证明其在促进批判性思维、识别缺失或未经充分研究的主张方面的潜力。代码可在\href{https://git.ecdf.ed.ac.uk/s2236454/DayDreamer-CQs-Gen}{DayDreamer}获取。

> Critical questions are essential resources to provoke critical thinking when encountering an argumentative text. We present our system for the Critical Questions Generation (CQs-Gen) Shared Task at ArgMining 2025. Our approach leverages large language models (LLMs) with chain-of-thought prompting to generate critical questions guided by Walton's argumentation schemes. For each input intervention, we conversationally prompt LLMs to instantiate the corresponding argument scheme template to first obtain structured arguments, and then generate relevant critical questions. Following this, we rank all the available critical questions by prompting LLMs to select the top 3 most helpful questions based on the original intervention text. This combination of structured argumentation theory and step-by-step reasoning enables the generation of contextually relevant and diverse critical questions. Our pipeline achieves competitive performance in the final test set, showing its potential to foster critical thinking given argumentative text and detect missing or uninformed claims. Code available at \href{https://git.ecdf.ed.ac.uk/s2236454/DayDreamer-CQs-Gen}{DayDreamer}.

[Arxiv](https://arxiv.org/abs/2505.15554)