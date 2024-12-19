# 关于常见知识逻辑的模型

发布时间：2024年12月18日

`Agent`

> Models for common knowledge logic

# 摘要

> 在本文中，我们探讨了常识逻辑的模型。常识逻辑属于多模态逻辑，涵盖模态算子 $\mathsf{K}_{i}$ （$i\in\mathcal{I}$）、$\mathsf{E}$ 与 $\mathsf{C}$ 。$\mathsf{K}_{i}φ$ （$i\in\mathcal{I}$）、$\mathsf{E}φ$ 以及 $\mathsf{C}φ$ 的含义分别为“代理 $i$ 知晓 $φ$ ”（$i\in\mathcal{I}$）、“$\mathcal{I}$ 中的所有人都知晓 $φ$ ”以及“$φ$ 是 $\mathcal{I}$ 中的常识”。接着，这些公式的模型需满足以下条件：$\mathsf{E}φ$ 为真的充要条件是对每个 $i\in\mathcal{I}$ ，$\mathsf{K}_{i}φ$ 为真；$\mathsf{C}φ$ 为真的充要条件是 $φ$ 、$\mathsf{E}φ$ 、$\mathsf{E}^{2}φ$ 、$\mathsf{E}^{3}φ,\ldots$ 皆为真。适用于此的克里普克框架为 $\langle W,R_{\mathsf{K}_{i}} (i\in\mathcal{I}), R_{\mathsf{C}}angle$ ，其中 $R_{\mathsf{C}}$ 是 $R_{\mathsf{E}}$ 的自反和传递闭包。我们将这类克里普克框架称作 CKL 框架。此外，适用的代数是具有模态算子 $\mathrm{K}_{i}$ （$i\in\mathcal{I}$）、$\mathrm{E}$ 和 $\mathrm{C}$ 的模态代数，其满足 $\mathrm{E} x=igwedge_{i\in\mathcal{I}} \mathrm{K}_{i} x$ ，$\mathrm{C} x\leq\mathrm{E}\mathrm{C} x$ ，且 $\mathrm{C} x$ 是集合 $\{\mathrm{E}^{n} x\mid n\inω\}$ 的最大下界。我们将这类代数称为 CKL 代数。在本文中，我们指出 CKL 框架的类别是模态可定义的，然而 CKL 代数的类别并非如此，这意味着 CKL 代数的类别并非一个簇。

> In this paper, we discuss models of the common knowledge logic. The common knowledge logic is a multi-modal logic that includes the modal operators $\mathsf{K}_{i}$ ($i\in\mathcal{I}$), $\mathsf{E}$, and $\mathsf{C}$. The intended meanings of $\mathsf{K}_{i}φ$ ($i\in\mathcal{I}$), $\mathsf{E}φ$, and $\mathsf{C}φ$ are ''the agent $i$ knows $φ$'' ($i\in\mathcal{I}$), ''everyone in $\mathcal{I}$ knows $φ$'', and ''$φ$ is common knowledge among $\mathcal{I}$'', respectively. Then, the models of these formulas satisfy the following conditions: $\mathsf{E}φ$ is true if and only if $\mathsf{K}_{i}φ$ is true for every $i\in\mathcal{I}$, and $\mathsf{C}φ$ is true if and only if all of $φ$, $\mathsf{E}φ$, $\mathsf{E}^{2}φ$, $\mathsf{E}^{3}φ,\ldots$ are true. A suitable Kripke frame for this is $\langle W,R_{\mathsf{K}_{i}} (i\in\mathcal{I}), R_{\mathsf{C}}\rangle$, where $R_{\mathsf{C}}$ is the reflexive and transitive closure of $R_{\mathsf{E}}$. We refer to such Kripke frames as CKL-frames. Additionally, an algebra suitable for this is a modal algebra with modal operators $\mathrm{K}_{i}$ ($i\in\mathcal{I}$), $\mathrm{E}$, and $\mathrm{C}$, which satisfies $\mathrm{E} x=\bigwedge_{i\in\mathcal{I}} \mathrm{K}_{i} x$, $\mathrm{C} x\leq\mathrm{E}\mathrm{C} x$, and $\mathrm{C} x$ is the greatest lower bound of the set $\{\mathrm{E}^{n} x\mid n\inω\}$. We refer to such algebras as CKL-algebras. In this paper, we show that the class of CKL-frames is modally definable, but the class of CKL-algebras is not, which means that the class of CKL-algebras is not a variety.

[Arxiv](https://arxiv.org/abs/2412.13537)