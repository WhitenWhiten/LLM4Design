# Replication Manual for the Paper: *Using LLMs in Software Design: A Study of GitHub and A Practitioner Survey*

This repository provides the replication package for the paper: *Using LLMs in Software Design: A Study of GitHub and A Practitioner Survey*. The work contains two sub-studies: a mining study and a survey study, and the files related to the two parts are stored in the two folders of this repository, `Mining` and `Survey`. In the following two sections, we present the way to replicate the results of the two studies separately.

## 🛠️ Mining Study

In the mining study, we compiled an original data source by integrating conversation data collected from previous research with newly acquired conversation data, which is packaged and stored in `Mining/raw conversation data.zip`. After manual labeling, conversations related to software design were selected (n=291), from which 376 tasks were further identified and stored in `mining/valid conversations data.zip`. For each identified task, we label it for our RQ1 (What specific design tasks have been supported by LLMs?) and RQ2 (How LLMs are used in software design?). Eventually, we extracted four valid data items for futher analysis: `Task types`, `Number of Rounds`, `Purpose of Prompt`, `Level of Design`, and the data items extracted are stored in `Mining/extracted data items.xlsx`.  For the data analysis of RQ1 and RQ2, the Constant Comparative method should be adopted. Three key steps are needed for conducting the Constant Comparative process: initial coding, focused coding, and theoretical coding. We have elaborated on this process in the "mining study design" subsection of the "study design" section in our paper, which can serve as a reference for replication.

## 🙂 Survey Study

In the survey study, We designed a questionnaire based on the results of the Mining study and created an email template to invite participants to the survey study, both of which are stored in `Survey/Questionnaire.pdf` and `Survey/e-mail template.docx`. The survey questions encompass demographic inquiries (SQ1\~SQ3), as well as questions designed to validate the findings of RQ1 and RQ2 from the mining study (SQ4\~SQ7), in addition to those aimed at exploring RQ3 and RQ4 (SQ8\~SQ11) . Potential participants were sourced from LinkedIn and GitHub, from whom we collected their email addresses and subsequently reached out using the aforementioned email template. The replies are stored in `Survey/Reply.xlsx`. The responses from the survey study serve two purposes: firstly, to validate the findings of the mining study by conducting statistical analyses on SQ4 to SQ7 and comparing them with the conclusions drawn from RQ1 and RQ2 of the mining study; secondly, to investigate RQ3 and RQ4, which necessitates the application of the Constant Comparative method once more. This process is elaborately detailed in the "survey study design" subsection under "study design" section in the paper, providing a reference for replication.

## 📁 Repository Structure

```plaintext
├── Mining        
│ ├── extracted data items.xlsx
│ ├── raw conversation data.zip
│ ├── valid conversations data.zip
├── Survey
│ ├── e-mail template.docx
│ ├── Questionnaire.pdf
│ ├── Reply.xlsx
└── README.md
```

## 📝 Citation

```bibtex
@article{LLM4Design,
  author = {Wang, Yifei and Li, Ruiyin and Liang, Peng and Cai, Yangxiao and Li, Zengyang and Shahin, Mojtaba},
  title = {{Using LLMs in Software Design: A Study of GitHub and A Practitioner Survey}},
  journal={arXiv preprint arXiv:xxxx.xxxxx},
  year={2025}
}
```
