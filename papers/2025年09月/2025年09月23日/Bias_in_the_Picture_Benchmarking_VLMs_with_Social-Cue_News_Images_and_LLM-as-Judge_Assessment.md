# 图片中的偏见：基于社会线索新闻图片与LLM评判评估的视觉语言模型（VLMs）基准测试

发布时间：2025年09月23日

`LLM应用` `媒体与娱乐`

> Bias in the Picture: Benchmarking VLMs with Social-Cue News Images and LLM-as-Judge Assessment

# 摘要

> 大型视觉语言模型（VLMs）能够协同理解图像与文本，却也容易在遇到年龄、性别、种族、着装或职业等视觉线索时，吸收并再现有害的社会刻板印象。为探究这些风险，我们构建了一个新闻图像基准，包含1343个取自不同媒体的图像-问题对，并标注了真实答案及人口统计属性（年龄、性别、种族、职业和运动项目）。我们评估了多款最先进的VLMs，同时采用大型语言模型（LLM）作为评判工具并辅以人工验证。研究发现：（i）视觉上下文会在开放式任务中系统性地改变模型输出；（ii）偏见的普遍程度因属性和模型而异，其中性别和职业相关的风险尤为突出；（iii）更高的忠实度并不一定意味着更低的偏见。我们发布了该基准的提示词、评估标准和代码，旨在支持可复现且具有公平感知的多模态评估。

> Large vision-language models (VLMs) can jointly interpret images and text, but they are also prone to absorbing and reproducing harmful social stereotypes when visual cues such as age, gender, race, clothing, or occupation are present. To investigate these risks, we introduce a news-image benchmark consisting of 1,343 image-question pairs drawn from diverse outlets, which we annotated with ground-truth answers and demographic attributes (age, gender, race, occupation, and sports). We evaluate a range of state-of-the-art VLMs and employ a large language model (LLM) as judge, with human verification. Our findings show that: (i) visual context systematically shifts model outputs in open-ended settings; (ii) bias prevalence varies across attributes and models, with particularly high risk for gender and occupation; and (iii) higher faithfulness does not necessarily correspond to lower bias. We release the benchmark prompts, evaluation rubric, and code to support reproducible and fairness-aware multimodal assessment.

[Arxiv](https://arxiv.org/abs/2509.19659)