@article{wang2023defecthunter,
  title={Defecthunter: A novel llm-driven boosted-conformer-based code vulnerability detection mechanism},
  author={Wang, Jin and Huang, Zishan and Liu, Hengli and Yang, Nianyi and Xiao, Yinhao},
  journal={arXiv preprint arXiv:2309.15324},
  year={2023}
}


# Abstract:
One of the most pressing threats to computing systems is software vulnerabilities, which can compromise both hardware and software components. Existing methods for vulnerability detection remain suboptimal. Traditional techniques are both time-consuming and labor-intensive, while machine-learning-based approaches often underperform when applied to complex datasets, due to their inability to capture high-dimensional relationships. Previous deep-learning strategies also fall short in capturing sufficient feature information. Although self-attention mechanisms can process information over long distances, they fail to capture structural information. In this paper, we introduce DefectHunter, an innovative model for vulnerability identification that employs the Conformer mechanism. This mechanism fuses self-attention with convolutional networks to capture both local, position-wise features and global, content-based interactions. Furthermore, we optimize the self-attention mechanisms to mitigate the issue of excessive attention heads introducing extraneous noise by adjusting the denominator. We evaluated DefectHunter against ten baseline methods using six industrial and two highly complex datasets. On the QEMU dataset, DefectHunter exhibited a 20.62\% improvement in accuracy over Pongo-70B, and for the CWE-754 dataset, its accuracy was 14.64\% higher. To investigate how DefectHunter comprehends vulnerabilities, we conducted a case study, which revealed that our model effectively understands the mechanisms underlying vulnerabilities.
