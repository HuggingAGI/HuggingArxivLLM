# PerHalluEval：大型语言模型的波斯语幻觉评估基准

发布时间：2025年09月25日

`LLM应用` `基础理论`

> PerHalluEval: Persian Hallucination Evaluation Benchmark for Large Language Models

# 摘要

> 幻觉问题长期困扰着所有大型语言模型（LLMs），在波斯语这类低资源语言中表现得尤为突出。PerHalluEval（波斯语幻觉评估）应运而生，它是首个专为波斯语打造的动态幻觉评估基准。该基准采用三阶段LLM驱动流程，并结合人工验证，针对问答与摘要任务生成逼真的答案和摘要，核心目标是检测外在与内在幻觉。我们还借助生成token的对数概率筛选出最具迷惑性的幻觉实例，同时邀请人工标注员在问答数据集中标注波斯语特有的语境，以此评估LLMs对波斯文化相关内容的处理能力。通过PerHalluEval对12个LLMs（涵盖开源与闭源模型）的评估显示，这些模型在识别波斯语幻觉文本时普遍力不从心。研究发现，提供外部知识（如摘要任务的原始文档）可部分减轻幻觉现象；此外，专门针对波斯语训练的LLMs与其他模型在幻觉表现上并无显著差异。

> Hallucination is a persistent issue affecting all large language Models (LLMs), particularly within low-resource languages such as Persian. PerHalluEval (Persian Hallucination Evaluation) is the first dynamic hallucination evaluation benchmark tailored for the Persian language. Our benchmark leverages a three-stage LLM-driven pipeline, augmented with human validation, to generate plausible answers and summaries regarding QA and summarization tasks, focusing on detecting extrinsic and intrinsic hallucinations. Moreover, we used the log probabilities of generated tokens to select the most believable hallucinated instances. In addition, we engaged human annotators to highlight Persian-specific contexts in the QA dataset in order to evaluate LLMs' performance on content specifically related to Persian culture. Our evaluation of 12 LLMs, including open- and closed-source models using PerHalluEval, revealed that the models generally struggle in detecting hallucinated Persian text. We showed that providing external knowledge, i.e., the original document for the summarization task, could mitigate hallucination partially. Furthermore, there was no significant difference in terms of hallucination when comparing LLMs specifically trained for Persian with others.

[Arxiv](https://arxiv.org/abs/2509.21104)