# Replication Package for the Paper: *Using LLMs in Software Design: An Empirical Study of GitHub and A Practitioner Survey*

This repository provides the replication package for the paper: *Using LLMs in Software Design: An Empirical Study of GitHub and A Practitioner Survey*. The work contains two sub-studies, a mining study and a survey study, and the files related to the two parts are stored in the two folders of this repository, `Mining Study` and `Survey Study`. In the following two sections, we describe the artifacts that support the replication of the two studies separately.

## 🛠️ Mining Study

In the mining study, we compiled an original data source by integrating conversation data collected from previous research with newly acquired conversation data. The 3,217 raw conversations are packaged in `Mining Study/raw conversation data.zip`. After screening the dataset, 291 conversations were identified as related to software design. From these 291 conversations, we extracted 376 task-level analysis units for RQ1 (What specific software design tasks have been supported by ChatGPT?) and RQ2 (How ChatGPT is used in software design?); these task-level conversation snippets are stored in `Mining Study/valid conversations data.zip`. The initial coding results for the 376 task-level units are stored in `Mining Study/data_extraction.xlsx`, which contains the preliminary labels for `Task Type`, `Number of Rounds`, `Purpose of Prompt`, and `Level of Design`. The focused coding results and aggregated count tables used for analysis are stored in `Mining Study/data_analysis.xlsx`. For the qualitative analysis of RQ1 and RQ2, the Constant Comparative method should be adopted. Three key steps are needed for conducting the Constant Comparative process: initial coding, focused coding, and theoretical coding. We have elaborated on this process in the "mining study design" subsection of the "study design" section in our paper, which can serve as a reference for replication.

## 🙂 Survey Study

In the survey study, we designed a questionnaire based on the results of the mining study and created an email template to invite participants, which are separately stored in `Survey Study/Questionnaire.pdf` and `Survey Study/Survey Invitation email Template.docx`. The survey questions encompass demographic inquiries (SQ1\~SQ3), questions for validating the findings of RQ1 and RQ2 from the mining study (SQ4\~SQ7), open-ended questions on benefits and limitations (SQ8 and SQ9), a further-comment question (SQ10), and an administrative question on receiving the study findings (SQ11). The collected responses are stored in `Survey Study/Responses.xlsx`, which contains 65 valid participant responses in an analysis-ready format together with the structured answers, the four-bin `Q5` responses used for SQ5/Table 5, and the coded topic columns used in the study. For the qualitative analysis of RQ3 and RQ4, the initial coding results derived from SQ8 and SQ9 are stored in `Survey Study/data_extraction.xlsx`, and the focused coding results together with summary count tables are stored in `Survey Study/data_analysis.xlsx`. The survey responses serve two purposes: firstly, `Survey Study/Responses.xlsx` provides the source data for the descriptive statistics reported for SQ4 to SQ7; secondly, the open-ended responses for SQ8 and SQ9 support another round of Constant Comparative analysis for RQ3 and RQ4. This process is elaborately detailed in the "survey study design" subsection under the "study design" section in the paper, providing a reference for replication.

## 📁 Repository Structure

```plaintext
├── Mining Study                              # Files related to the mining study
│ ├── raw conversation data.zip               # Raw conversation dataset used for screening
│ ├── valid conversations data.zip            # 376 task-level conversation snippets extracted from 291 screened design-related conversations 
│ ├── data_extraction.xlsx                    # Initial coding results for the identified design tasks
│ ├── data_analysis.xlsx                      # Focused coding results and summary tables for RQ1 and RQ2
├── Survey Study                              # Files related to the survey study
│ ├── Questionnaire.pdf                       # Questionnaire used in the survey study
│ ├── Survey Invitation email Template.docx   # E-mail template for inviting survey participants
│ ├── Responses.xlsx                          # 65 valid survey responses in analysis-ready form
│ ├── data_extraction.xlsx                    # Initial coding results for open-ended survey responses
│ ├── data_analysis.xlsx                      # Focused coding results and summary tables for RQ3 and RQ4
└── README.md                                 # Description of this replication package
```

## 📝 Citation

```bibtex
@article{LLM4Design,
  author = {Wang, Yifei and Li, Ruiyin and Liang, Peng and Cai, Yangxiao and Li, Zengyang and Shahin, Mojtaba and Khan, Arif Ali},
  title = {{Using LLMs in Software Design: An Empirical Study of GitHub and A Practitioner Survey}},
  journal = {ACM Transactions on Software Engineering and Methodology},
  year={2026}
}
```
