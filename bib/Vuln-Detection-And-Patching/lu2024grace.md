@article{lu2024grace,
  title={GRACE: Empowering LLM-based software vulnerability detection with graph structure and in-context learning},
  author={Lu, Guilong and Ju, Xiaolin and Chen, Xiang and Pei, Wenlong and Cai, Zhilong},
  journal={Journal of Systems and Software},
  volume={212},
  pages={112031},
  year={2024},
  publisher={Elsevier}
}


# Abstract:
Software vulnerabilities inflict considerable economic and societal harm. Therefore, timely and accurate detection of these flaws has become vital. Large language models (LLMs) have emerged as a promising tool for vulnerability detection in recent studies. However, their effectiveness suffers when limited to plain text source code, which may ignore the syntactic and semantic information of the code. To address this limitation, we propose a novel vulnerability detection approach GRACE that empowers LLM-based software vulnerability detection by incorporating graph structural information in the code and in-context learning. We also design an effective demonstration retrieval approach that identifies highly relevant code examples by considering semantic, lexical, and syntactic similarities for the target code to provide better demonstrations for in-context learning. To evaluate the effectiveness of GRACE, we conducted an empirical study on three vulnerability detection datasets (i.e., Devign, Reveal, and Big-Vul). The results demonstrate that GRACE outperforms six state-of-the-art vulnerability detection baselines by at least 28.65% in terms of the F1 score across these three datasets. Therefore, our study highlights the effectiveness of integrating graph structural information and in-context learning in LLMs for vulnerability detection. These findings motivate further investigation into tailoring such approaches for specific vulnerability types or adapting them to other security tasks.


