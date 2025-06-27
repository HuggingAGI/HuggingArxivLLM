# HumanOmniV2：从理解到多模态推理的上下文应用

发布时间：2025年06月26日

`LLM应用` `多模态`

> HumanOmniV2: From Understanding to Omni-Modal Reasoning with Context

# 摘要

> 多模态大型语言模型的快速发展使深入理解与解读人类意图的能力成为关键。近期研究表明，强化学习（RL）在提升大型语言模型（LLMs）推理能力方面具有潜力，但将其适配到多模态数据与格式的挑战仍未解决。我们发现现有模型存在两个主要问题：全局上下文理解不足与捷径问题。前者源于模型对多模态上下文的误读，导致错误回答；后者则表现为模型忽视关键线索，直接回应而未充分利用多模态信息。为解决这些问题，我们强调模型需具备清晰理解多模态输入全局上下文的能力，以防止忽略关键提示并确保全面推理。为此，我们引入了由大型语言模型判定的上下文奖励机制，并结合格式和准确性奖励。同时，我们利用大型语言模型评估逻辑奖励，确保推理过程将多模态信息与逻辑方法有效结合。我们还推出了全模态推理基准测试——IntentBench，用于评估模型在理解复杂人类意图和情感方面的能力。实验表明，与现有开源全模态模型相比，我们的方法在多个基准测试中表现更优。

> With the rapid evolution of multimodal large language models, the capacity to deeply understand and interpret human intentions has emerged as a critical capability, which demands detailed and thoughtful reasoning. In recent studies, Reinforcement Learning (RL) has demonstrated potential in enhancing the reasoning capabilities of Large Language Models (LLMs). Nonetheless, the challenges associated with adapting RL to multimodal data and formats remain largely unaddressed. In this paper, we identify two issues in existing multimodal reasoning models: insufficient global context understanding and shortcut problems. Insufficient context understanding can happen when a model misinterprets multimodal context, resulting in incorrect answers. The shortcut problem occurs when the model overlooks crucial clues in multimodal inputs, directly addressing the query without considering the multimodal information. To tackle these issues, we emphasize the necessity for the model to reason with a clear understanding of the global context within multimodal inputs. This global context understanding can effectively prevent the model from overlooking key multimodal cues and ensure a thorough reasoning process. To ensure the accurate interpretation of multimodal context information, we implement a context reward judged by a large language model, alongside format and accuracy rewards. Additionally, to improve complex reasoning capability, we employ the LLM to assess the logical reward, determining whether the reasoning process successfully integrates multimodal information with logical methods. We also introduce a reasoning omni-modal benchmark, IntentBench, aimed at evaluating models in understanding complex human intentions and emotions. Our proposed method demonstrates advanced performance across multiple omni-modal benchmarks compared to other open-source omni-modal models.

[Arxiv](https://arxiv.org/abs/2506.21277)