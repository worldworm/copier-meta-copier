<h1 align="center">📋 copier-meta-copier</h1>
<p align="center">
  <i><a href="https://github.com/copier-org/copier">Copier</a> template for <a href="https://github.com/worldworm/copier-showcase/blob/main/types/meta.md">copier-meta</a> projects.</i>
</p>


<!-- Place https://shields.io/ badges here -->
[![GitHub repo stars](https://img.shields.io/github/stars/worldworm/copier-meta-copier)](https://github.com/worldworm/copier-meta-copier)
[![License](https://img.shields.io/badge/license-MIT-green?logo=opensourceinitiative&logoColor=fff)](https://github.com/worldworm/copier-meta-copier/blob/main/LICENSE)
[![GitHub last commit (main)](https://img.shields.io/github/last-commit/worldworm/copier-meta-copier/main)](https://github.com/worldworm/copier-meta-copier/commits/main/)
[![GitHub release](https://img.shields.io/github/v/release/worldworm/copier-meta-copier)](https://github.com/worldworm/copier-meta-copier/releases/latest)
[![GitHub commits since latest release](https://img.shields.io/github/commits-since/worldworm/copier-meta-copier/latest/main)](https://github.com/worldworm/copier-meta-copier/releases/latest)
[![Copier supported version](https://img.shields.io/badge/Copier-v9-blue)](https://github.com/copier-org/copier)


## Features
- precreated copier.yml
- [shared-config](https://github.com/worldworm/copier-shared-config) include
- answers-file suffix


## Requirements
First install copier:<br>
([from the official installation documentation](https://copier.readthedocs.io/en/stable/#installation))
```bash
pip install copier
```


## Usage
Make sure the requirements are met, then:
```bash
copier copy --trust "https://github.com/worldworm/copier-meta-copier.git" .
```

### Update
To update a template after creating a project, run:
```bash
copier update --trust -a .project/.copier-answers.meta-copier.yml .
```


## Explore more Copier templates
In addition to this template, there are a number of other Copier templates available. For an overview of all available templates, visit the [Templates Showcase repository](https://github.com/worldworm/copier-showcase).

---
<p align="center">
  <i>© <a href="https://github.com/worldworm">worldworm</a> 2023-2024</i>
  <br><i>Licensed under <a href="https://github.com/worldworm/copier-meta-copier/blob/main/LICENSE">MIT</a></i>
</p>
