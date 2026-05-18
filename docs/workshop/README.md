## Suggestions
- local development on ODU and UMD clusters
- VS Code session
- heavy runs + SLURM + VS Code
-  


# Undergraduate Research Computing Workshop

This folder contains Google Colab-ready Jupyter notebooks for an undergraduate research computing workshop.

## Suggested location

Place these files in:

```text
./docs/workshop/
```

This keeps the workshop materials close to the repository documentation while separating them from source code.

## Sessions

1. Introduction to Colab and Research Computing
2. Python Foundations for Research
3. Git and GitHub Fundamentals
4. Unit Testing and Continuous Integration
5. Running a Real Research Repository
6. Scientific Visualization and Data
7. Contributing to Research Code

## Suggested repository layout

```text
repo/
├── docs/
│   └── workshop/
│       ├── README.md
│       ├── 01_intro_to_colab_and_research_computing.ipynb
│       ├── 02_python_foundations_for_research.ipynb
│       └── ...
├── examples/
├── src/
├── tests/
├── README.md
└── requirements.txt
```

## Colab badge template

Replace `ORG`, `REPO`, and notebook filename:

```markdown
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ORG/REPO/blob/main/docs/workshop/NOTEBOOK_NAME.ipynb)
```

## Teaching recommendation

Use each notebook as a guided 60–90 minute session. Ask students to save a personal copy, complete the exercises, and submit either a short reflection or a small pull request.
