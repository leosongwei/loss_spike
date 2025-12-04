# 可解释AI


## On Policy

* Retaining by Doing: The Role of On-Policy Data in Mitigating Forgetting https://arxiv.org/abs/2510.18874

> We identify that the mode-seeking nature of RL, which stems from its use of on-policy data, enables keeping prior knowledge intact when learning the target task.
> Namely, minimizing the cross-entropy loss via SFT is equivalent to minimizing the forward KL divergence with respect to the optimal policy,
> while maximizing the RL objective corresponds to minimizing the reverse KL.
> In contrast, minimizing reverse KL maintains the shape of the old mode and covers the target distribution by shifting the new mode of $π_θ$.

* Synthetic Error Injection Fails to Elicit Self-Correction In Language Models https://arxiv.org/abs/2512.02389

> Our approach inserts artificial errors into reasoning chains, masks them, and supervises the model to recognize and correct these mistakes.
> Despite the intuitive appeal of this method, we find that it fails to significantly improve performance even on simple synthetic tasks across multiple models.
> Moreover, even when the model catches its own error, it often parrots the original mistake.
> We find that the distribution shift of synthetic errors to on-policy errors significantly degrades the error-correction capabilities of the fine-tuned model, even with good synthetic coverage of on-policy errors.

