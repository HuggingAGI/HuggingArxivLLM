# Lemmanaid：神经符号引理猜想系统

发布时间：2025年04月07日

`LLM应用` `计算机辅助`

> Lemmanaid: Neuro-Symbolic Lemma Conjecturing

# 摘要

> 自动猜想有用且新颖的引理能显著提升自动化推理工具，并降低数学形式化证明的门槛。然而这对神经方法和符号方法都极具挑战。我们介绍了结合LLMs与符号方法的Lemmanaid工具，朝着实用的神经符号引理猜想迈出了第一步。我们在Isabelle证明库上评估了Lemmanaid，训练LLM生成引理模板，并用符号方法填充细节。实验表明神经与符号方法相辅相成。结合两者优势，Lemmanaid能为多种输入领域生成有用引理，助力计算机辅助的理论发展与形式化。

> Automatically conjecturing useful, interesting and novel lemmas would greatly improve automated reasoning tools and lower the bar for formalizing mathematics in proof assistants. It is however a very challenging task for both neural and symbolic approaches. We present the first steps towards a practical neuro-symbolic lemma conjecturing tool, Lemmanaid, that combines Large Language Models (LLMs) and symbolic methods, and evaluate it on proof libraries for the Isabelle proof assistant. We train an LLM to generate lemma templates that describe the shape of a lemma, and use symbolic methods to fill in the details. We compare Lemmanaid against an LLM trained to generate complete lemma statements as well as previous fully symbolic conjecturing methods. Our results indicate that neural and symbolic techniques are complementary. By leveraging the best of both symbolic and neural methods we can generate useful lemmas for a wide range of input domains, facilitating computer-assisted theory development and formalization.

[Arxiv](https://arxiv.org/abs/2504.04942)