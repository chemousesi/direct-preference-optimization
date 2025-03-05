
# Direct Preference Optimization (DPO)

## Overview

This repository contains an implementation example of **Direct Preference Optimization (DPO)**, a novel approach to fine-tuning language models based on human preferences without requiring reinforcement learning.

## Paper Summary

**Title:** Direct Preference Optimization: Your Language Model is Secretly a Reward Model  
**Authors:** Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Finn  
**Institution:** Stanford University  
**Conference:** NeurIPS 2023  

### Key Insights:
- Traditional Reinforcement Learning from Human Feedback (RLHF) methods rely on training a separate reward model and then optimizing a policy using reinforcement learning, which is complex and computationally expensive.
- **DPO replaces this process with a simple classification objective**, directly optimizing a policy to satisfy human preferences without explicit reward modeling or reinforcement learning.
- The approach is theoretically grounded and empirically matches or outperforms RLHF methods like PPO in various tasks (sentiment control, summarization, and dialogue generation).

### Advantages of DPO:
- **Simplifies preference learning** by avoiding reinforcement learning complexities.
- **Stable and efficient** compared to traditional RLHF approaches.
- **Easier to implement and train**, making it more accessible for fine-tuning language models.

## Implementation Example

An implementation example of **DPO** can be found in the provided Jupyter notebook. This notebook demonstrates how to:
- Load and preprocess a dataset of human preferences.
- Train a language model using the **DPO loss function**.
- Compare results against traditional RLHF methods.

## References
For further details, refer to the original paper:
- [ArXiv Link](https://arxiv.org/abs/2305.18290)

## Citation
```
@article{rafailov2023dpo,
  title={Direct Preference Optimization: Your Language Model is Secretly a Reward Model},
  author={Rafailov, Rafael and Sharma, Archit and Mitchell, Eric and Ermon, Stefano and Manning, Christopher D and Finn, Chelsea},
  journal={arXiv preprint arXiv:2305.18290},
  year={2023}
}
```

---
For questions or contributions, feel free to submit an issue or pull request!

