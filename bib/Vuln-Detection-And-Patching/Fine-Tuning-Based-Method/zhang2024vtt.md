@article{zhang2024vtt,
  title={VTT-LLM: Advancing Vulnerability-to-Tactic-and-Technique Mapping through Fine-Tuning of Large Language Model},
  author={Zhang, Chenhui and Wang, Le and Fan, Dunqiu and Zhu, Junyi and Zhou, Tang and Zeng, Liyi and Li, Zhaohua},
  journal={Mathematics},
  volume={12},
  number={9},
  pages={1286},
  year={2024},
  publisher={MDPI}
}

# Abstract:
Vulnerabilities are often accompanied by cyberattacks. CVE is the largest repository of open vulnerabilities, which keeps expanding. ATT&CK models known multi-step attacks both tactically and technically and remains up to date. It is valuable to correlate the vulnerability in CVE with the corresponding tactic and technique of ATT&CK which exploit the vulnerability, for active defense. Mappings manually is not only time-consuming but also difficult to keep up-to-date. Existing language-based automated mapping methods do not utilize the information associated with attack behaviors outside of CVE and ATT&CK and are therefore ineffective. In this paper, we propose a novel framework named VTT-LLM for mapping Vulnerabilities to Tactics and Techniques based on Large Language Models, which consists of a generation model and a mapping model. In order to generate fine-tuning instructions for LLM, we create a template to extract knowledge of CWE (a standardized list of common weaknesses) and CAPEC (a standardized list of common attack patterns). We train the generation model of VTT-LLM by fine-tuning the LLM according to the above instructions. The generation model correlates vulnerability and attack through their descriptions. The mapping model transforms the descriptions of ATT&CK tactics and techniques into vectors through text embedding and further associates them with attacks through semantic matching. By leveraging the knowledge of CWE and CAPEC, VTT-LLM can eventually automate the process of linking vulnerabilities in CVE to the attack techniques and tactics of ATT&CK. Experiments on the latest public dataset, ChatGPT-VDMEval, show the effectiveness of VTT-LLM with an accuracy of 85.18%, which is 13.69% and 54.42% higher than the existing CVET and ChatGPT-based methods, respectively. In addition, compared to fine-tuning without outside knowledge, the accuracy of VTT-LLM with chain fine-tuning is 9.24% higher on average across different LLMs.