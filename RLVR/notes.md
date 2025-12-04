# 目的

* 梳理LLM领域RLVR趋势的起源，演进
* 梳理经典强化学习概念，如MDP, TD, 策略梯度方法
* 对比算法，讨论一些细节：
    * 前序研究和算法，如PPO，RLOO，REINFORCE
    * Limit of RLVR争议
    * token level vs sequence level
    * clip
    * 熵与决策的关系
* 未来趋势

# TODO

--------------

# REINFORCE

策略梯度方法 https://en.wikipedia.org/wiki/Policy_gradient_method

# DeepSeekMath: GRPO

https://arxiv.org/abs/2402.03300

不过当时他们还在用奖励模型就是了，不算真的RLVR。

# Does Reinforcement Learning Really Incentivize Reasoning Capacity in LLMs Beyond the Base Model?

https://arxiv.org/pdf/2504.13837

清华LEAP团队的那个充满争议的论文，他们认为当前的训练方式虽然可以提高正确路径的采样效率（提高正确率），但极少能够发现本质上新的思维模式。

研究主页：https://limit-of-rlvr.github.io/

# Dr GRPO

https://arxiv.org/abs/2503.20783

原标题： Understanding R1-Zero-Like Training: A Critical Perspective 

# 其他材料

* （论坛）Offering a Technical Deep Dive on GRPO/DAPO/Dr. GRPO Algorithms https://discuss.huggingface.co/t/offering-a-technical-deep-dive-on-grpo-dapo-dr-grpo-algorithms/154480
* （博客）From REINFORCE to Dr. GRPO https://lancelqf.github.io/note/llm_post_training/
