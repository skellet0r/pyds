[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/[gh-user]/[repo-name]/master)

# [Insert Project Title]

[Insert brief overview/background]

## Components

- [Charter](docs/project/charter.md): formally outlines this project covering the scope of what the project
  will achieve, as well as the people involved, milestones, and the intended course of action 
- [Conclusion/Exit Report](docs/project/exit-report.md): covers the results/findings of this project
- [Data](data/): data used for this project is stored here, if the data is too large to be stored in the git repo
  directions on how to acquire the data will be provided
- [Data Info](docs/data/): any documentation related to or received with the data
- [Notebooks](notebooks/): jupyter notebooks used for research, analysis, modeling and et cetera
- [Project Environment](environment.yml): environment file for use with the anaconda environment manager

## Technologies

- [Anaconda](https://www.anaconda.com/)
- [Python](https://www.python.org/)
- [Reveal.js](https://github.com/hakimel/reveal.js)
  - To add Reveal.js -> `git subtree add -P docs/slides https://github.com/hakimel/reveal.js.git master --squash`
  - To push slides to origin/gh-pages -> `git subtree push -P docs/gh-pages origin gh-pages`

## Quick Start

> For a quick/temporary cloud-hosted instance of this project, click the `launch binder` tag

For a local instance of this project follow the steps below.

1. Clone this repository

```shell
$ git clone [Insert Project Github URL] && cd [Project Name]
```

2. Initialize the environment

```shell
$ conda env create -f environment.yml
```

3. Activate the environment

```shell
$ conda activate [Insert Project Name]
```

4. Enjoy 😃


## Findings

[Insert Findings]

## Recommendations

[Insert Project Recommendations]

## Next Steps

[Insert Next Steps]
