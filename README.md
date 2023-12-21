<h1 align="center">📋 copier-meta-copier</h1>
<p align="center">
  <i><a href="https://github.com/copier-org/copier">Copier</a> template for <a href="https://github.com/worldworm/copier-showcase/blob/main/types/meta.md">copier-meta</a> projects.</i>
</p>


<!-- Place https://shields.io/ badges here -->


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
copier copy --trust "https://github.com/worldworm/copier-meta-copier.git" /new/project/path
```

### Update
To update a template after creating a project, run:
```bash
copier update --trust -a .project/.copier-answers.meta-copier.yml /some/project/path
```

## Explore more Copier templates
In addition to this template, there are a number of other Copier templates available. For an overview of all available templates, visit the [Templates Showcase repository](https://github.com/worldworm/copier-showcase).

---
<p align="center">
  <i>© <a href="https://github.com/worldworm">worldworm</a> 2023</i><br>
  <i>Licensed under <a href="https://github.com/worldworm/copier-meta-copier/blob/main/LICENSE">MIT</a></i><br>
</p>
