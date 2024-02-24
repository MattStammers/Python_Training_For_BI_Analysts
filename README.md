# Python Training For BI Analysts 👀🎂✨

Python Training for NHS BI Analysts. 🎁

By Matt Stammers 🐱‍💻, Richard Finley 🐱‍🐉 and Tin Lam 🐱‍🚀.

## Introduction

Across the NHS analysts everywhere are starting to grapple with python. Because this is a difficult journey I created an online guide last year to try and help newcomers to get the hang of it (for a different project): 😉

[See Guide](https://mattstammers.github.io/hdruk_avoidable_admissions_collaboration_docs/how_to_guides/new_to_python/)

Because python is a powerful scripting language it is a great place for BI analysts to start to level up their capabilities. This training session provides a toy app and examples to help with that process. 🙌

## File Structure

```
├── README.md
├── requirements.txt
├── Pipfile
├── pipfile.lock
├── LICENSE
├── .gitignore
├── .secrets.baseline
├── .pre-commit-config.yaml
├── .flake8
└── notebooks
    ├── eda_explosion.ipynb
    ├── process.ipynb
    ├── uhs-press-release-text-analysis.ipynb
└── data
    └── no_shows.zip
```

## Explainer

- We will explain the file structure during the training. It looks complex but this is necessary to keep you from accidentally comitting secrets to git (even internally) 🐱‍🏍

- Ordinarily data would not be committed in a repository but it is necessary for this toy app. Normally, you should add your /data directory to the gitignore file so you don't accidentally commit it to the repo. To make sure this is enabled call:

```bat
pre-commit install
```

before using git to commit any work. Then the hooks will protect you from accidentally committing a secret. You can add exceptions such as the lockfile or tests to the yaml file 😎 (Yaml is just a heirarhical set of instructions).

- Either the Pipenv or requirements.txt files can be used to set up the python environment

## Enjoy

Ask questions, play with it and learn. The more you experiment the better you will get 🐱🐱‍👤

## Credits

The data is courtesy of: [Kaggle Dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments) thanks to [JoniaRoba](https://www.kaggle.com/joniarroba) used according to the following license.

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: https://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
