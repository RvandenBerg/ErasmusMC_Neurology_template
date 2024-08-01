# Erasmus MC Neurology template repository

This simple project structure template repository is adapted from the [Simple Python Project](https://github.com/UtrechtUniversity/simple-python-template) template used at Utrecht University, which in turn is based on the [Good Enough Project](https://github.com/bvreede/good-enough-project) Cookiecutter template by Barbara Vreede (2019). The directory structure was altered to match the SOP Scientific Integrity: Storing Research Data used at the Department of Neurology of the Erasmus MC, Rotterdam.


## Usage

Click "Use this template" at the top of this page to create a new repository with the same folder structure.

## Project Structure

The project structure distinguishes three kinds of folders:
- read-only (RO): not edited by either code or researcher
- human-writeable (HW): edited by the researcher only.
- project-generated (PG): folders generated when running the code; these folders can be deleted or emptied and will be completely reconstituted as the project is run.


```
├── 1-Researchplan
│   ├── 1-Proposals           <- Research / grant proposals (HW)
│   ├── 2-Finance             <- Budget information (HW)
│   └── 3-Reports             <- Reports required by grant agency (HW)
├── 2-Informed_consent
│   ├── 1-EthicsApproval      <- METC / non-WMO approval forms (HW)
│   └── 2-ConsentForms        <- If required, patient informed consent forms (HW)
├── 3-Experiments
│   ├── 0-Protocol            <- Data analysis protocol and log (HW)
│   ├── 1-Inputs              <- Contains a description of the sources of the data (HW)
│   ├── 2-Data                <- Raw project data, ignored by git (RO)
│   ├── 3-DataAnalysis        <- Intermediate data, ignored by git (PG)
│   └── 4-Outputs             <- Final datasets used for modelling / machine learning, ignored by git (PG)
├── 4-Metadata                <- Description of datasets and variables (HW)
├── 5-Analysis_files          <- Source code for this project (HW)
├── 6-Analysis_results        <- Output of analysis (PG)
├── 9-Publications
│   ├── 1-Presentations       <- Presentation source and output, e.g. PPT / LaTeX (HW) 
│   └── 2-Publications        <- Manuscript source and output, e.g. Word, LaTeX (HW)
├── .gitignore                <- Git ignore file, optimized for Python project (HW)
├── LICENSE                   <- MIT License, replace if required (HW)
├── README.md                 <- This readme file (HW)
└── requirements.txt          <- File with overview of Python packages required for project (PG)


```

## Add a citation file
Create a citation file for your repository using [cffinit](https://citation-file-format.github.io/cff-initializer-javascript/#/)

## License
This project is licensed under the terms of the [MIT License](/LICENSE).
