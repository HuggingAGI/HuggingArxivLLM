# 在微调开源LLM时要当心哦！你的微调数据可能被悄悄窃取！

发布时间：2025年05月21日

`LLM应用` `数据安全` `模型创建`

> Be Careful When Fine-tuning On Open-Source LLMs: Your Fine-tuning Data Could Be Secretly Stolen!

# 摘要

> 在开源大型语言模型（LLMs）上使用专有数据进行微调，已成为下游开发者获取特定任务模型的常规做法。然而，我们发现了一个令人担忧的新风险：开源LLMs的创建者可以通过简单的后门训练，在后期从微调后的下游模型中提取专有的下游微调数据，仅需对微调后的下游模型进行黑盒访问即可。我们的实验涵盖了4个流行的开源模型（参数规模从3B到32B）和2个下游数据集，结果表明，数据提取性能可能异常高：在实际场景中，最多可完美提取5,000个样本中的76.3%的下游微调数据（查询），而在更理想的情况下，成功率可提升至94.9%。我们还探索了一种基于检测的防御策略，但发现该策略可被改进后的攻击手段绕过。总体而言，我们强调了这一新发现的微调数据泄露风险的紧迫性，希望后续研究能够推动解决这一令人担忧的风险。我们实验所用的代码和数据已发布在https://github.com/thu-coai/Backdoor-Data-Extraction。


> Fine-tuning on open-source Large Language Models (LLMs) with proprietary data is now a standard practice for downstream developers to obtain task-specific LLMs. Surprisingly, we reveal a new and concerning risk along with the practice: the creator of the open-source LLMs can later extract the private downstream fine-tuning data through simple backdoor training, only requiring black-box access to the fine-tuned downstream model. Our comprehensive experiments, across 4 popularly used open-source models with 3B to 32B parameters and 2 downstream datasets, suggest that the extraction performance can be strikingly high: in practical settings, as much as 76.3% downstream fine-tuning data (queries) out of a total 5,000 samples can be perfectly extracted, and the success rate can increase to 94.9% in more ideal settings. We also explore a detection-based defense strategy but find it can be bypassed with improved attack. Overall, we highlight the emergency of this newly identified data breaching risk in fine-tuning, and we hope that more follow-up research could push the progress of addressing this concerning risk. The code and data used in our experiments are released at https://github.com/thu-coai/Backdoor-Data-Extraction.

[Arxiv](https://arxiv.org/abs/2505.15656)