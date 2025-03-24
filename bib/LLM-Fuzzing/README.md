# Here are all Papers you want!

## [SOSP'24]If At First You Don’t Succeed, Try, Try, Again...? Insights and LLM-informed Tooling for Detecting Retry Bugs in Software Systems

[paper](https://dl.acm.org/doi/pdf/10.1145/3694715.3695971)
[code](https://github.com/bastoica/wasabi/)
[slides](https://bastoica.github.io/files/talks/2024_sosp_talk.pdf)
### Abstract
Retry—the re-execution of a task on failure—is a common mechanism to enable resilient software systems. Yet, despite
its commonality and long history, retry remains difficult to
implement and test.
Guided by our study of real-world retry issues, we propose
a novel suite of static and dynamic techniques to detect retry
problems in software. We find that the ad-hoc nature of retry
implementation poses challenges for traditional program
analysis but can be well suited for large language models;
and that carefully repurposing existing unit tests can, along
with fault injection, expose various types of retry problems

