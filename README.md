# 👋 Welcome to ippolito-cmu!

![GitHub Org's stars](https://img.shields.io/github/stars/ippolito-cmu?style=social)
![GitHub followers](https://img.shields.io/github/followers/ippolito-cmu?style=social)

Research projects from [Daphne Ippolito's](https://www.daphnei.com/) lab at Carnegie Mellon University's [Language Technologies Institute](https://lti.cmu.edu/). 

*Last updated: July 2025*

## 🔬 Projects

### [diffuse-distributions](https://github.com/ippolito-cmu/diffuse-distributions)
**"Forcing Diffuse Distributions out of Language Models"**  
*Yiming Zhang, Avi Schwarzschild, Nicholas Carlini, Zico Kolter, Daphne Ippolito*  
[![Paper](https://img.shields.io/badge/COLM%202024-Conference-lightblue?style=flat-square)](https://openreview.net/forum?id=9JY1QLVFPZ)  
> Addresses the problem that instruct LLMs exhibit strong biases when asked to generate random outputs, proposing a fine-tuing method to make models produce more uniform distributions for synthetic dataset generation.

### [ChasingRandom](https://github.com/ippolito-cmu/ChasingRandom)
**"Chasing Random: Instruction Selection Strategies Fail to Generalize"**  
*Harshita Diddee, Daphne Ippolito*  
[![Paper](https://img.shields.io/badge/NAACL%202025-Findings-brightgreen?style=flat-square)](https://aclanthology.org/2025.findings-naacl.103/)  
> Demonstrates that popular instruction selection strategies for LLMs generalize poorly across different datasets and evaluation setups, often failing to consistently outperform random baselines while incurring higher computational costs than training on full datasets.

### [allie](https://github.com/ippolito-cmu/allie)
**"Human-Aligned Chess With a Bit of Search"**  
*Yiming Zhang, Athul Paul Jacob, Vivian Lai, Daniel Fried, Daphne Ippolito*   
[![Paper](https://img.shields.io/badge/ICLR%202025-Conference-blue?style=flat-square)](https://openreview.net/forum?id=bc2H72hGxB)  
> Introduces Allie, a chess AI using language modeling and time-adaptive search that achieves remarkable skill calibration with only 49 Elo gap on average across players from 1000-2600 Elo.


### [novelty-bench/novelty-bench](https://github.com/novelty-bench/novelty-bench)
**"NoveltyBench: Evaluating Creativity and Diversity in Language Models"**  
*Yiming Zhang, Harshita Diddee, Susan Holm, Hanchen Liu, Xinyue Liu, Vinay Samuel, Barry Wang, Daphne Ippolito*  
[![Paper](https://img.shields.io/badge/COLM%202025-Conference-lightblue?style=flat-square)](https://arxiv.org/html/2504.05228)
[![Website](https://img.shields.io/badge/website-novelty--bench.github.io-blue?style=flat-square)](https://novelty-bench.github.io)  
> Benchmark for measuring how well language models generate multiple diverse, high-quality responses to queries involving subjectivity, randomness, and creativity. Evaluates 20+ frontier models including GPT-4o, Claude 3.5 Sonnet, and Gemini 2.0 Pro.

### [Command-V](https://github.com/ippolito-cmu/Command-V)
**"Command-V: Pasting LLM Behaviors via Activation Profiles"**  
*Barry Wang, Avi Schwarzschild, Alexander Robey, Ali Payani, Charles Fleming, Mingjie Sun, Daphne Ippolito*  
[![arXiv](https://img.shields.io/badge/arXiv-Preprint-red.svg)](https://arxiv.org/abs/2506.19140)  
> "Finetune once, use on many LLMs" - the first method to demonstrate cross-architecture transfer of finetuned adapters without backpropagation. Works between Llama, Qwen, and other model families.
