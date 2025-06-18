# 遗忘并非隐形：从模型输出中揭示LLMs的遗忘痕迹

发布时间：2025年06月16日

`LLM应用` `数据隐私` `网络安全`

> Unlearning Isn't Invisible: Detecting Unlearning Traces in LLMs from Model Outputs

# 摘要

> 机器遗忘（MU）针对大型语言模型（LLMs），通常被称为LLM遗忘，旨在从训练好的模型中移除特定的不良数据或知识，同时保持其在标准任务上的性能。尽管遗忘在保护数据隐私、执行版权保护以及缓解LLMs中的社会技术风险方面发挥着重要作用，我们发现了一个新的漏洞：遗忘痕迹检测。我们发现，遗忘会在LLMs中留下持久的''指纹''，这些痕迹在模型行为和内部表示中均可检测到。即使使用与遗忘无关的输入进行提示，这些痕迹仍可从输出响应中识别出来。具体而言，一个简单的监督分类器仅基于模型的文本输出，就能可靠地判断模型是否经历过遗忘。进一步的分析表明，这些痕迹嵌入在中间激活中，并以非线性方式传播到最终层，在激活空间中形成了低维的可学习流形。通过广泛的实验，我们发现，与遗忘相关的提示能够在所有模型规模上实现超过90%的遗忘痕迹检测准确率。即使使用与遗忘无关的输入，大型LLMs仍保持高可检测性，这表明遗忘痕迹检测具有广泛的应用性。这些发现揭示了遗忘会留下可测量的特征，当模型被识别为遗忘状态时，这为逆向工程被遗忘的信息带来了新的风险。代码可在[此链接](https://github.com/OPTML-Group/Unlearn-Trace)获取。

> Machine unlearning (MU) for large language models (LLMs), commonly referred to as LLM unlearning, seeks to remove specific undesirable data or knowledge from a trained model, while maintaining its performance on standard tasks. While unlearning plays a vital role in protecting data privacy, enforcing copyright, and mitigating sociotechnical harms in LLMs, we identify a new vulnerability post-unlearning: unlearning trace detection. We discover that unlearning leaves behind persistent ''fingerprints'' in LLMs, detectable traces in both model behavior and internal representations. These traces can be identified from output responses, even when prompted with forget-irrelevant inputs. Specifically, a simple supervised classifier can reliably determine whether a model has undergone unlearning based solely on its textual outputs. Further analysis shows that these traces are embedded in intermediate activations and propagate nonlinearly to the final layer, forming low-dimensional, learnable manifolds in activation space. Through extensive experiments, we show that forget-relevant prompts enable over 90% accuracy in detecting unlearning traces across all model sizes. Even with forget-irrelevant inputs, large LLMs maintain high detectability, demonstrating the broad applicability of unlearning trace detection. These findings reveal that unlearning leaves measurable signatures, introducing a new risk of reverse-engineering forgotten information when a model is identified as unlearned given an input query. Codes are available at [this URL](https://github.com/OPTML-Group/Unlearn-Trace).

[Arxiv](https://arxiv.org/abs/2506.14003)