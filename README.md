# TrustAgent: A Survey on Trustworthy LLM Agents

## 📌 Introduction
With the rapid evolution of Large Language Models (LLMs), LLM-based agents and Multi-agent Systems (MAS) have significantly expanded the capabilities of AI ecosystems. However, this advancement has introduced more complex trustworthiness issues. This repository provides an overview of our survey paper **"A Survey on Trustworthy LLM Agents: Threats and Countermeasures"** and offers insights into threats, defenses, and evaluation techniques for LLM agents.

## 📄 Survey
**Title:** A Survey on Trustworthy LLM Agents: Threats and Countermeasures  
**Authors:** Miao Yu, Fanci Meng, Xinyun Zhou, Shilong Wang, et al.  
**Institution:** Squirrel AI Learning, Salesforce, The University of North Carolina, Nanyang Technological University, Rutgers University  
**Link:** [arXiv / Paper URL](https://arxiv.org/pdf/2503.09648)

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

## 🔍 Comparison with Previous Surveys
| Survey | Object | Multi-Dimensional | Modular | MAS Support |
|--------|--------|------------------|---------|-------------|
| Liu et al. | LLM | ✅ | ❌ | ❌ |
| He et al. | Agent | ✅ | ✅ | ❌ |
| **TrustAgent (Ours)** | LLM + Agent | ✅ | ✅ | ✅ |

## 📥 Citation
If you find this survey useful for your research, please cite us:
```bibtex
@misc{yu2025surveytrustworthyllmagents,
      title={A Survey on Trustworthy LLM Agents: Threats and Countermeasures}, 
      author={Miao Yu and Fanci Meng and Xinyun Zhou and Shilong Wang and Junyuan Mao and Linsey Pang and Tianlong Chen and Kun Wang and Xinfeng Li and Yongfeng Zhang and Bo An and Qingsong Wen},
      year={2025},
      eprint={2503.09648},
      archivePrefix={arXiv},
      primaryClass={cs.MA},
      url={https://arxiv.org/abs/2503.09648}, 
}
```

## 📢 Contributing
We welcome contributions! Feel free to submit **issues** or **pull requests** to improve the repository.

## 📧 Contact
For any questions or discussions, please reach out to the authors:
- **Miao Yu**: fishthreewater@gmail.com
- **Xinfeng Li**: lxfmakeit@gmail.com
- **Qingsong Wen**: qingsongedu@gmail.com
