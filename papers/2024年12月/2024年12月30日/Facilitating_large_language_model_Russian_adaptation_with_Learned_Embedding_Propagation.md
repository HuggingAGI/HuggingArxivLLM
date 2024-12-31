# 利用学习嵌入传播助力大型语言模型适配俄语

发布时间：2024年12月30日

`LLM应用` `人工智能`

> Facilitating large language model Russian adaptation with Learned Embedding Propagation

# 摘要

> 大型语言模型（LLM）技术发展迅猛，推出了强大的开源指令调优型LLM，其文本生成质量可与GPT-4等前沿模型媲美。此类模型虽加速了LLM技术在敏感信息环境中的应用，但其作者未公开复制结果所需的训练数据，导致成果仅限模型本身使用。由于这些开源模型是多语言的，这就降低了训练特定语言LLM的益处，因为提高推理计算效率成了这一昂贵过程唯一确定的优势。由于缺少高质量的指令调优数据，更具成本效益的选择，如词汇扩展及后续的持续预训练也受到阻碍，毕竟这是LLM任务解决能力的关键因素。为应对语言适应流程的局限并降低成本，我们提出了学习嵌入传播（LEP）。与现有方法不同，我们的方法因对现有LLM知识影响极小，所以对训练数据规模的要求较低。我们通过新颖的特别嵌入传播流程来强化这一点，该流程能跳过指令调优步骤，直接将新语言知识植入任何现有的指令调优变体中。我们对LLaMa-3-8B和Mistral-7B的四个俄语词汇适应情况进行了评估，结果表明LEP与传统的指令调优方法旗鼓相当，性能可与OpenChat 3.5和LLaMa-3-8B-Instruct相媲美，通过自校准和持续调优进一步增强了任务解决能力。

> Rapid advancements of large language model (LLM) technologies led to the introduction of powerful open-source instruction-tuned LLMs that have the same text generation quality as the state-of-the-art counterparts such as GPT-4. While the emergence of such models accelerates the adoption of LLM technologies in sensitive-information environments the authors of such models don not disclose the training data necessary for replication of the results thus making the achievements model-exclusive. Since those open-source models are also multilingual this in turn reduces the benefits of training a language specific LLMs as improved inference computation efficiency becomes the only guaranteed advantage of such costly procedure. More cost-efficient options such as vocabulary extension and subsequent continued pre-training are also inhibited by the lack of access to high-quality instruction-tuning data since it is the major factor behind the resulting LLM task-solving capabilities. To address the limitations and cut the costs of the language adaptation pipeline we propose Learned Embedding Propagation (LEP). Unlike existing approaches our method has lower training data size requirements due to minimal impact on existing LLM knowledge which we reinforce using novel ad-hoc embedding propagation procedure that allows to skip the instruction-tuning step and instead implant the new language knowledge directly into any existing instruct-tuned variant. We evaluated four Russian vocabulary adaptations for LLaMa-3-8B and Mistral-7B, showing that LEP is competitive with traditional instruction-tuning methods, achieving performance comparable to OpenChat 3.5 and LLaMa-3-8B-Instruct, with further improvements via self-calibration and continued tuning enhancing task-solving capabilities.

[Arxiv](https://arxiv.org/abs/2412.21140)