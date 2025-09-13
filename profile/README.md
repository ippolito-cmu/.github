# 👋 Welcome to ippolito-cmu!

Research projects from [Daphne Ippolito's](https://www.daphnei.com/) lab at Carnegie Mellon University's [Language Technologies Institute](https://lti.cmu.edu/). 

*Last updated: July 2025*

## 🔬 Projects 

### [diffuse-distributions](https://github.com/ippolito-cmu/diffuse-distributions)
**"Forcing Diffuse Distributions out of Language Models"**  
*Yiming Zhang, Avi Schwarzschild, Nicholas Carlini, Zico Kolter, Daphne Ippolito*  
[![Paper](https://img.shields.io/badge/COLM%202024-Conference%20Paper-lightblue)](https://openreview.net/forum?id=9JY1QLVFPZ)  
> Addresses the problem that instruct LLMs exhibit strong biases when asked to generate random outputs, proposing a fine-tuing method to make models produce more uniform distributions for synthetic dataset generation.

### [ChasingRandom](https://github.com/ippolito-cmu/ChasingRandom)
**"Chasing Random: Instruction Selection Strategies Fail to Generalize"**  
*Harshita Diddee, Daphne Ippolito*  
[![Paper](https://img.shields.io/badge/NAACL%202025-Findings%20Paper-brightgreen)](https://aclanthology.org/2025.findings-naacl.103/)  
> Demonstrates that popular instruction selection strategies for LLMs generalize poorly across different datasets and evaluation setups, often failing to consistently outperform random baselines while incurring higher computational costs than training on full datasets.

### [allie](https://github.com/ippolito-cmu/allie)
**"Human-Aligned Chess With a Bit of Search"**  
*Yiming Zhang, Athul Paul Jacob, Vivian Lai, Daniel Fried, Daphne Ippolito*   
[![Paper](https://img.shields.io/badge/ICLR%202025-Conference%20Paper-blue)](https://openreview.net/forum?id=bc2H72hGxB)  
> Introduces Allie, a chess AI that learns to *ponder* lke humans with a time-adaptive MCTS algorithm. Achieves state-of-the-art prediction of human behavior and strong skill adaptation against online players from 1000-2600 Elo.

### [pretraining-poisoning](https://github.com/facebookresearch/pretraining-poisoning)
**"Persistent Pre-Training Poisoning of LLMs"**  
*Yiming Zhang\*, Javier Rando\*, Ivan Evtimov, Jianfeng Chi, Eric Michael Smith, Nicholas Carlini, Florian Tramèr, Daphne Ippolito*
[![Paper](https://img.shields.io/badge/ICLR%202025-Conference%20Paper-blue)](https://openreview.net/forum?id=eiqrnVaeIw)  
> Shows that 0.1\% poisoning of LLM's pre-training data persists after alignment (SFT and DPO), and an attacker can achieve various goals such as denial-of-service, context extraction and belief manipulation with access to pre-training data alone.

### [novelty-bench/novelty-bench](https://github.com/novelty-bench/novelty-bench)
**"NoveltyBench: Evaluating Creativity and Diversity in Language Models"**  
*Yiming Zhang, Harshita Diddee, Susan Holm, Hanchen Liu, Xinyue Liu, Vinay Samuel, Barry Wang, Daphne Ippolito*  
[![Paper](https://img.shields.io/badge/COLM%202025-Conference%20Paper-lightblue)](https://arxiv.org/html/2504.05228)
[![Website](https://img.shields.io/badge/website-novelty--bench.github.io-A394BC)](https://novelty-bench.github.io)  
> Benchmark for measuring how well language models generate multiple diverse, high-quality responses to queries involving subjectivity, randomness, and creativity. Evaluates 20+ frontier models including GPT-4o, Claude 3.5 Sonnet, and Gemini 2.0 Pro.

### [CIE](https://github.com/ippolito-cmu/CIE)
**"CIE: Controlling Language Model Text Generations Using Continuous Signals"**  
*Vinay Samuel, Harshita Diddee, Yiming Zhang, Daphne Ippolito*  
[![Paper](https://img.shields.io/badge/EMNLP%202025-Conference%20Paper-lightblue)](https://arxiv.org/abs/2505.13448)  
> Continuous control signal approach for controlling attributes in LM outputs. Experiments ran for response word count attribute but designed to be extended to other attributes as well. We show stronger control of desired word count compared to previous approaches including prompting approaches.

### [Command-V](https://github.com/ippolito-cmu/Command-V)
**"Command-V: Pasting LLM Behaviors via Activation Profiles"**  
*Barry Wang, Avi Schwarzschild, Alexander Robey, Ali Payani, Charles Fleming, Mingjie Sun, Daphne Ippolito*  
[![arXiv](https://img.shields.io/badge/arXiv-Preprint-red.svg)](https://arxiv.org/abs/2506.19140)  
> "Finetune once, use on many LLMs" - the first method to demonstrate cross-architecture transfer of finetuned adapters without backpropagation. Works between Llama, Qwen, and other model families.
