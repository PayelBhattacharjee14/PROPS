# PROPS: Progressively Private Self Alignment
The goal of the Progressively Private Self Alignment algorithm (PROPS) is to ensure privacy guarantees for preference data. This repository consists of all the code used in the paper Aligning Large Language Models with Preference Level Privacy.

## References:
For the experimental results presented in the paper, we have used two major datasets:
1. [truthy-dpo-v0.1](https://huggingface.co/datasets/jondurbin/truthy-dpo-v0.1/)
2. [ultrachat](https://huggingface.co/datasets/stingning/ultrachat)

We have used the [GPT-2-Large](https://huggingface.co/openai-community/gpt2-large) model, and codes have been utilized from these repositories:
1.  [Direct Preference Optimization (DPO)](https://github.com/eric-mitchell/direct-preference-optimization)
2.  [Llama-2](https://github.com/Lior-Baruch/LLM-Advanced-FineTuning)
3.  [DPO-trainer](https://huggingface.co/docs/trl/main/en/dpo_trainer)
