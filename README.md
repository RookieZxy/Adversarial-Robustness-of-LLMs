# Safety of In-Context Learning<span id="head"/>

A collection of papers and resources about adversarial robustness of In context learning(ICL)

With emergence of Large Language models(LLMs), the parameter of the LLMs explosive growth. For instance the Llama2, which is published by Meta, is a collection of pretrained and fine-tuned generative text models ranging in scale from 7 billion to 70 billion parameters. Therefore fine tuning LLMs become time and money-consuming. In-context learning(ICL), which don't touch the weight of model, becomes a powerfult paradigm leveraging LLMs for specific task by utilizing data-label paired examples as demonstrations in the precondition prompts. Despite it's promising performance, the stability of ICL is affected by selection and organization of demonstrations.

## Overview<span id="overview"/>
In this repository, we will introduce the ICL and collect recent advances in safety of LLMs especially for In-Context Learning. 
We hope this repository can help researchers to get better understanding of this promising field.

## Table of Contents<span id="table-of-contents"/>
* [Safety of LLMs](#head)
   * [Overview](#overview)
   * [Table of Contents](#table-of-contents)
   * [Related Surveys](#related-surveys)
   * [ICL-enhanced LLMs](#ICL-enhanced-LLMs)
   * [Unrobustness of ILMs](#unrobustness-of-LLMs)
      * [Attacks based on searching method](#attacks-based-on-searching-method)
      * [Attacks based on learning method](#attacks-based-on-learning-method)
      * [Benchmark](#benchmark)
   * [Blog](#blog)
 
## Related Surveys <span id="related-surveys"/>
* What is Perplexity? [link](https://lukesalamone.github.io/posts/perplexity/)
* Baseline Defenses for Adversarial Attacks Against Aligned Language Models (arxiv)[paper](https://arxiv.org/pdf/2309.00614.pdf)
  
## ICL-enhanced LLMs<span id="ICL-enhanced-LLMs"/>
* Rethinking the Role of Demonstrations: What Makes In-Context Learning Work? (EMNLP)[pdf](https://arxiv.org/pdf/2202.12837.pdf)
* Emergent Abilities of Large Language Models (TMLR) [pdf](https://arxiv.org/pdf/2206.07682.pdf)
* What Makes Good In-Context Examples for GPT-3? (arxiv) [pdf](https://arxiv.org/pdf/2101.06804.pdf)
* Language Models are Few-Shot Learners (arxiv) [pdf](https://arxiv.org/pdf/2005.14165.pdf)
* Impact of Pretraining Term Frequencies on Few-Shot Reasoning (arxiv) [pdf](https://arxiv.org/pdf/2202.07206.pdf)

## Adversarial Robustness of LLMs<span id="unrobustness-of-LLMs"/>
## Analysis of Few-shot prompting <span id="unrobustness-of-LLMs"/>
#### &emsp;Attacks based on learning method<span id="#attacks-based-on-learning-method"/>
* Universal and Transferable Adversarial Attacks (arxiv)[pdf](https://arxiv.org/pdf/2307.15043.pdf)</br>
### Instability of ICL
#### &emsp;Attacks based on searching method<span id="#attacks-based-on-searching-method"/>
* Universal and Transferable Adversarial Attacks on Aligned Language Models (arxiv) [pdf](https://arxiv.org/pdf/2307.15043.pdf)
* Large Language Models Can be Lazy Learners: Analyze Shortcuts in In-Context Learning (arxiv) [pdf](https://arxiv.org/pdf/2305.17256.pdf)
* Adversarial Demonstration Attacks on Large Language Models (arxiv) [pdf](https://arxiv.org/pdf/2305.14950.pdf)

### Benchmark<span id="benchmark"/>
* PromptBench: Towards Evaluating the Robustness of Large Language Models on Adversarial Prompts (Arxiv, 2023) (arxiv)[pdf](https://arxiv.org/pdf/2306.04528.pdf)

## Blog<span id="blog"/>
* Prompt Engineering [blog](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/)



    

