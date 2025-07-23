# 深度带来虚假隐私感：LLM内部状态反转

发布时间：2025年07月22日

`LLM理论

摘要讨论了大型语言模型（LLMs）的内部状态逆向工程，提出攻击方法和防御措施，属于对模型内在机制的理论研究。` `数据安全` `隐私保护`

> Depth Gives a False Sense of Privacy: LLM Internal States Inversion

# 摘要

> 大型语言模型（LLMs）正在日常应用中发挥越来越重要的作用，但随之而来的隐私与安全问题也日益凸显。近期研究提出了协作推理，通过将早期层推理外包以确保数据本地性，并基于内部神经元模式引入了模型安全审计。这两种方法揭示了LLMs的内部状态（ISs），这些状态传统上被认为由于优化挑战和深层的高度抽象表示而无法逆向输入。在本研究中，我们挑战这一传统观点，提出了四种显著提升逆向输入语义相似性和标记匹配率的逆向攻击方法。具体而言，我们首先针对浅层和深层ISs开发了两种基于优化的白盒攻击。这些攻击通过两阶段逆向过程避免了先前工作中观察到的局部最小值收敛问题。随后，我们借助源模型与衍生模型之间的可迁移性，将优化攻击扩展到更实际的黑盒权重访问场景。此外，我们引入了一种生成式攻击，将逆向过程视为翻译任务，利用逆向模型重构输入。通过对医疗咨询和编程辅助数据集中的短长提示以及6种LLMs的广泛评估，验证了我们的逆向攻击的有效性。值得注意的是，一个4,112个标记的长医疗咨询提示可以从Llama-3模型的中层几乎完美逆向，标记匹配率达到86.88的F1值。最后，我们评估了四种实用防御措施，发现它们无法完全防止ISs逆向，并为未来的缓解设计提出了结论。

> Large Language Models (LLMs) are increasingly integrated into daily routines, yet they raise significant privacy and safety concerns. Recent research proposes collaborative inference, which outsources the early-layer inference to ensure data locality, and introduces model safety auditing based on inner neuron patterns. Both techniques expose the LLM's Internal States (ISs), which are traditionally considered irreversible to inputs due to optimization challenges and the highly abstract representations in deep layers. In this work, we challenge this assumption by proposing four inversion attacks that significantly improve the semantic similarity and token matching rate of inverted inputs. Specifically, we first develop two white-box optimization-based attacks tailored for low-depth and high-depth ISs. These attacks avoid local minima convergence, a limitation observed in prior work, through a two-phase inversion process. Then, we extend our optimization attack under more practical black-box weight access by leveraging the transferability between the source and the derived LLMs. Additionally, we introduce a generation-based attack that treats inversion as a translation task, employing an inversion model to reconstruct inputs. Extensive evaluation of short and long prompts from medical consulting and coding assistance datasets and 6 LLMs validates the effectiveness of our inversion attacks. Notably, a 4,112-token long medical consulting prompt can be nearly perfectly inverted with 86.88 F1 token matching from the middle layer of Llama-3 model. Finally, we evaluate four practical defenses that we found cannot perfectly prevent ISs inversion and draw conclusions for future mitigation design.

[Arxiv](https://arxiv.org/abs/2507.16372)