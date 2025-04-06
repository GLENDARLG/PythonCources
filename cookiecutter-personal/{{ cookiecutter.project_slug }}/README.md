#{{ cookiecutter.project_name }}
By: {{ cookiecutter.project_author_name }}

Project Description:: {{ cookiecutter.project_description }}

## License


## Estructure
{{ cookiecutter.project_slug }}
    ├── data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jvelezmagic-initial-data-exploration`.
    │
    ├── .gitignore         <- Files to ignore by `git`.
    │
    ├── environment.yml    <- The requirements file for reproducing the analysis environment.
    │
    └── README.md          <- The top-level README for developers using this project.