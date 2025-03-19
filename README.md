# TrustAgent: A Survey on Trustworthy LLM Agents

## 📌 Introduction
With the rapid evolution of Large Language Models (LLMs), LLM-based agents and Multi-agent Systems (MAS) have significantly expanded the capabilities of AI ecosystems. However, this advancement has introduced more complex trustworthiness issues. This repository provides an overview of our survey paper **"A Survey on Trustworthy LLM Agents: Threats and Countermeasures"** and offers insights into threats, defenses, and evaluation techniques for LLM agents.

## 📄 Survey
**Title:** A Survey on Trustworthy LLM Agents: Threats and Countermeasures  
**Authors:** Miao Yu, Fanci Meng, Xinyun Zhou, Shilong Wang, et al.  
**Institution:** Squirrel AI Learning, Salesforce, The University of North Carolina, Nanyang Technological University, Rutgers University  
**Link:** [arXiv / Paper URL](https://arxiv.org/pdf/2503.09648)

## 💎 Table of Contents
- [📌 Introduction](#-introduction)
- [📄 Survey](#-survey)
- [💎 Table of Contents](#-table-of-contents)
- [✨ Paper Supplement](#-paper-supplement)
- [🚀 Highlights](#-highlights)
- [🏗️ TrustAgent Framework](#%EF%B8%8F-trustagent-framework)
- [📌 Key Topics](#-key-topics)
  - [1️⃣ Intrinsic Trustworthiness](#1️⃣-intrinsic-trustworthiness)
  - [2️⃣ Extrinsic Trustworthiness](#2️⃣-extrinsic-trustworthiness)
- [📖 Papers](#-papers)
  - [Intrinsic Trustworthiness](#intrinsic-trustworthiness)
    - [Brain (LLM)](#brain-llm)
    - [Memory](#memory)
    - [Tool](#tool)
  - [Extrinsic Trustworthiness](#extrinsic-trustworthiness)
    - [Agent-to-Agent](#agent-to-agent)
    - [Agent-to-Environment](#agent-to-environment)
    - [Agent-to-User](#agent-to-user)
- [🔍 Comparison with Previous Surveys](#-comparison-with-previous-surveys)
- [📥 Citation](#-citation)
- [📢 Contributing](#-contributing)
- [📧 Contact](#-contact)

## ✨ Paper Supplement
If you have additional articles, please:  

👉 [Click here to submit your article](https://forms.gle/bcSnvKganXyoLFi56)  

We will continuously update the survey and appreciate your support and contribution! 

## 🚀 Highlights
- Introduces **TrustAgent**, a modular framework for analyzing the trustworthiness of LLM-based agents.
- Categorizes trust issues into **intrinsic (brain, memory, tools)** and **extrinsic (user, agent, environment)** aspects.
- Surveys **attacks, defenses, and evaluation techniques** in multi-agent systems.
- Provides a taxonomy of threats, including **adversarial hijacking, unsafe action chains, privacy leakage, hallucinations, and fairness biases**.

## 🏗️ TrustAgent Framework
![TrustAgent Framework](./figure/trustagent_intro.png)  
## 📌 Key Topics
### 1️⃣ Intrinsic Trustworthiness
- **Brain (LLM Reasoning Module)**: Jailbreak, Prompt Injection, Backdoor Attacks.
- **Memory**: Memory Poisoning, Privacy Leakage, Short-Term Memory Misuse.
- **Tools**: Tool Manipulation, Tool Abuse, Malicious API Calls.

### 2️⃣ Extrinsic Trustworthiness
- **Agent-to-Agent**: Cooperative Attacks, Infectious Attacks, MAS Security.
- **Agent-to-User**: Personalized Attacks, Transparency Issues, Trust Calibration.
- **Agent-to-Environment**: Safety in Robotics, Autonomous Driving, Digital Threats.

# We will finish this part *very soon*!
## 📖 Papers
### Intrinsic Trustworthiness
#### Brain (LLM)
##### Attack
1. **"Describe, explain, plan and select: interactive planning with llms enables open-world multi-task agents"** (2023)  
    *Zihao Wang et al.*  [Paper](https://arxiv.org/abs/2302.01560)
   
3. **"Certifying llm safety against adversarial prompting"** (arxiv 2023)  
    *Kumar et al.*  [Paper](https://arxiv.org/abs/2309.02705)

4. **"Universal and transferable adversarial attacks on aligned language models"** (arxiv 2023)  
    *Zou et al.*  [Paper](https://arxiv.org/abs/2307.15043)

5. **"Improved techniques for optimization-based jailbreaking on large language models"** (arxiv 2024)  
    *Jia et al.*  [Paper](https://arxiv.org/abs/2405.21018)

6. **"AttnGCG: Enhancing jailbreaking attacks on LLMs with attention manipulation"** (arxiv 2024)  
    *Wang et al.*  [Paper](https://arxiv.org/abs/2410.09040)

7. **"Mrj-agent: An effective jailbreak agent for multi-round dialogue"** (arxiv 2024)  
    *Wang et al.*  [Paper](https://arxiv.org/abs/2411.03814)

8. **"PrivAgent: Agentic-based Red-teaming for LLM Privacy Leakage"** (arxiv 2024)  
    *Nie et al.*  [Paper](https://arxiv.org/abs/2412.05734)

9. **"Evil geniuses: Delving into the safety of llm-based agents"** (arxiv 2023)  
    *Tian et al.*  [Paper](https://arxiv.org/abs/2311.11855)

10. **"Pandora: Detailed llm jailbreaking via collaborated phishing agents with decomposed reasoning"** (ICLR 2024)  
    *Chen et al.*  [Paper](https://openreview.net/forum?id=9o06ugFxIj)

11. **"Agent smith: A single image can jailbreak one million multimodal llm agents exponentially fast"** (ICML 2024)  
    *Gu et al.*  [Paper](https://arxiv.org/abs/2402.08567)

12. **"The wolf within: Covert injection of malice into mllm societies via an mllm operative"** (arxiv 2024)  
    *Tan et al.*  [Paper](https://arxiv.org/html/2402.14859v1)



##### Defense
##### Evaluation

#### Memory
##### Attack

1. **“Certifiably Robust RAG against Retrieval Corruption”**  (arxiv 2024)  
​	    *Chong Xiang et al.* [Paper](https://arxiv.org/pdf/2405.15556)


2. **“AGENTPOISON: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases”**  (NIPS 2025)  
​	  *Zhaorun Chen et al.* [Paper](https://arxiv.org/pdf/2407.12784)


3. **“PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models”**  (arxiv 2024)  
​	  *Wei Zou et al.* [Paper](https://arxiv.org/pdf/2402.07867)


4. **“Poisoning Retrieval Corpora by Injecting Adversarial Passages”**  (arxiv 2023)  
​	  *Zexuan Zhong et al.* [Paper](https://arxiv.org/pdf/2310.19156)


5. **“AGENT-SAFETYBENCH: Evaluating the Safety of LLM Agents”**  (arxiv 2024)  
​	  *Zhexin Zhang et al.* [Paper](https://arxiv.org/pdf/2412.14470)


6. **“Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast”**  (arxiv 2024)  
​	  *Xiangming Gu et al.* [Paper](https://arxiv.org/pdf/2402.08567)


7. **“Typos that Broke the RAG’s Back: Genetic Attack on RAG Pipeline by Simulating Documents in the Wild via Low-level Perturbations”**  (arxiv 2024)  
​	  *Sukmin Cho et al.* [Paper](https://arxiv.org/pdf/2404.13948)


8. **“ Commercial LLM Agents Are Already Vulnerable to Simple Yet Dangerous Attacks”**  (arxiv 2025)  
​	  *Ang Li et al.* [Paper](https://arxiv.org/pdf/2502.08586)


9. **“The Good and The Bad: Exploring Privacy Issues in Retrieval-Augmented Generation (RAG)”**  (arxiv 2024)  
​	  *Shenglai Zeng et al.* [Paper](https://arxiv.org/pdf/2402.16893)


10. **“ Is My Data in Your Retrieval Database? Membership Inference Attacks Against Retrieval Augmented Generation”**  (arxiv 2024)  
​	  *Maya Anderson et al.* [Paper](https://arxiv.org/pdf/2405.20446)


11. **“RAG-Thief: Scalable Extraction of Private Data from Retrieval-Augmented Generation Applications with Agent-based Attacks”**  (arxiv 2024)  
​	  *Changyue Jiang et al.* [Paper](https://arxiv.org/pdf/2411.14110)


12. **“Text Embeddings Reveal (Almost) As Much As Text”**  (arxiv 2023)  
​	  *John X Morris et al.* [Paper](https://arxiv.org/pdf/2310.06816)


13. **“Sentence Embedding Leaks More Information than You Expect: Generative Embedding Inversion Attack to Recover the Whole Sentence”**  (arxiv 2023)  
​	  *Haoran Li et al.* [Paper](https://arxiv.org/pdf/2305.03010)


14. **“Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack”**  (arxiv 2024)  
​	  *Mark Russinovich et al.* [Paper](https://arxiv.org/pdf/2404.01833)


15. **“LLM Defenses Are Not Robust to Multi-Turn Human Jailbreaks Yet”**  (arxiv 2024)  
​	  *Nathaniel Li et al.* [Paper](https://arxiv.org/pdf/2408.15221)


16. **“LEVERAGING THE CONTEXT THROUGH MULTI-ROUND INTERACTIONS FOR JAILBREAKING ATTACKS”**  (arxiv 2024)  
​	  *Yixin Cheng et al.* [Paper](https://arxiv.org/pdf/2402.09177)


17. **“FRACTURED-SORRY-Bench: Framework for Revealing Attacks in Conversational Turns Undermining Refusal Efficacy and Defenses over SORRY-Bench (Automated Multi-shot Jailbreaks)”**  (arxiv 2024)  
​	  *Aman Priyanshu et al.* [Paper](https://arxiv.org/pdf/2408.16163)


18. **“Prompt Leakage effect and defense strategies for multi-turn LLM interactions”**  (arxiv 2024)  
​	  *Divyansh Agarwal et al.* [Paper](https://arxiv.org/pdf/2404.16251)


19. **“Securing Multi-turn Conversational Language Models From Distributed Backdoor Triggers”**  (arxiv 2024)  
​	  *Terry Tong et al.* [Paper](https://arxiv.org/pdf/2407.04151)

##### Defense

1. **“TrustRAG: Enhancing Robustness and Trustworthiness in RAG”**  (arxiv 2025)   
​	*Huichi Zhou et al.* [Paper](https://arxiv.org/pdf/2501.00879)


2. **“On the Vulnerability of Applying Retrieval-Augmented Generation within Knowledge-Intensive Application Domains”**  (arxiv 2024)  
​	*Xun Xian et al.* [Paper](https://arxiv.org/pdf/2409.17275)


3. **“Prompt Leakage effect and defense strategies for multi-turn LLM interactions”**  (arxiv 2024)  
​	*Divyansh Agarwal et al.* [Paper](https://arxiv.org/pdf/2404.16251)


4. **“AGENT-SAFETYBENCH: Evaluating the Safety of LLM Agents”**  (arxiv 2024)  
​	*Zhexin Zhang et al.* [Paper](https://arxiv.org/pdf/2412.14470)


5. **““Ghost of the past”: Identifying and Resolving Privacy Leakage of LLM’s Memory Through Proactive User Interaction”**  (arxiv 2024)  
​	*Shuning Zhang et al.* [Paper](https://arxiv.org/pdf/2410.14931)


6. **“ Is My Data in Your Retrieval Database? Membership Inference Attacks Against Retrieval Augmented Generation”**  (arxiv 2024)  
​	*Maya Anderson et al.* [Paper](https://arxiv.org/pdf/2405.20446)


7. **“Certifiably Robust RAG against Retrieval Corruption”**  (arxiv 2024)  
​	*Chong Xiang et al.* [Paper](https://arxiv.org/pdf/2405.15556)


8. **“Understanding Multi-Turn Toxic Behaviors in Open-Domain Chatbots”**  (RAID 2023)  
​	*Bocheng Chen et al.* [Paper](https://arxiv.org/pdf/2307.09579)

##### Evaluation

1. **“PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models”**  (arxiv 2024)  
​	*Wei Zou et al.* [Paper](https://arxiv.org/pdf/2402.07867)


2. **“AGENTPOISON: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases”**  (NIPS 2025)  
​	*Zhaorun Chen et al.* [Paper](https://arxiv.org/pdf/2407.12784)


3. **“The Good and The Bad: Exploring Privacy Issues in Retrieval-Augmented Generation (RAG)”**  (arxiv 2024)  
​	*Shenglai Zeng et al.* [Paper](https://arxiv.org/pdf/2402.16893)


4. **“RAG-Thief: Scalable Extraction of Private Data from Retrieval-Augmented Generation Applications with Agent-based Attacks”**  (arxiv 2024)  
​	*Changyue Jiang et al.* [Paper](https://arxiv.org/pdf/2411.14110)

#### Tool
##### Attack
##### Defense
##### Evaluation

### Extrinsic Trustworthiness
#### Agent-to-Agent
##### Attack
##### Defense
##### Evaluation

#### Agent-to-Environment
##### Physical Environment
##### Digital Environment

#### Agent-to-User

## 🔍 Comparison with Previous Surveys
| Survey             | Object      | Multi-Dimension | Modular | Technique      | MAS |
|:--------------------:|:-------------:|:-----------------:|:---------:|:-----------------:|:------:|
| [Liu et al.](https://arxiv.org/pdf/2308.05374)  | LLM         | ✅              | ❌       | Atk/Eval        | ❌    |
| [Huang et al.](https://mosis.eecs.utk.edu/publications/lichao2024trustllm.pdf)   | LLM         | ✅              | ❌       | Eval            | ❌    |
| [He et al.](https://arxiv.org/pdf/2407.19354)   | Agent       | ❌              | ❌       | Atk/Def         | ❌    |
| [Li et al.](https://arxiv.org/pdf/2401.05459)    | Agent       | ✅              | ❌       | Atk             | ❌    |
| [Wang et al.](https://arxiv.org/pdf/2409.14457)   | Agent       | ❌              | ❌       | Atk             | ❌    |
| [Deng et al.](https://dl.acm.org/doi/pdf/10.1145/3716628)   | Agent       | ❌              | ✅       | Atk/Def         | ✅    |
| [Gan et al.](https://arxiv.org/pdf/2411.09523?)    | Agent       | ✅              | ❌       | Atk/Def/Eval    | ❌    |
| **TrustAgent (Ours)**  | LLM + Agent | ✅              | ✅       | Atk/Def/Eval    | ✅    |

## 📥 Citation
If you find this survey useful for your research, please cite us:
```bibtex
@article{yu2025survey,
  title={A Survey on Trustworthy LLM Agents: Threats and Countermeasures},
  author={Yu, Miao and Meng, Fanci and Zhou, Xinyun and Wang, Shilong and Mao, Junyuan and Pang, Linsey and Chen, Tianlong and Wang, Kun and Li, Xinfeng and Zhang, Yongfeng and others},
  journal={arXiv preprint arXiv:2503.09648},
  year={2025}
}
```

## 📢 Contributing
We welcome contributions! Feel free to submit **issues** or **pull requests** to improve the repository.

## 📧 Contact
For any questions or discussions, please reach out to the authors:
- **Miao Yu**: fishthreewater@gmail.com
- **Xinfeng Li**: lxfmakeit@gmail.com
- **Qingsong Wen**: qingsongedu@gmail.com
