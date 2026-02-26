# vosslab-webwork-pg-set

vosslab-webwork-pg-set is a repository of WeBWorK `PG` and `PGML` problems for biochemistry coursework, intended for instructors and course staff who manage custom problem sets in a WeBWorK deployment.

## Documentation

- [docs/INSTALL.md](docs/INSTALL.md): Prerequisites and minimal install steps for loading these problems into WeBWorK.
- [docs/USAGE.md](docs/USAGE.md): Primary workflow for selecting, assigning, and validating problems.

## Quick start

1. List available problems:
   `rg --files problems`
2. Choose a file from `problems/biochemistry/topicXX/`.
3. Copy it into your WeBWorK course templates area, keeping directory structure intact.
4. Add it to an assignment and preview in WeBWorK.

## Related repositories

- [../biology-problems](../biology-problems): Biology problem generators and source content.
- [../biology-problems-website](../biology-problems-website): Website/docs surface for biology problem content.
- [../webwork-pg-renderer](../webwork-pg-renderer): Local renderer tooling for WeBWorK PG/PGML preview and checks.
- [../webwork-pgml-opl-training-set](../webwork-pgml-opl-training-set): PGML/OPL training and reference problem set.
- [../qti_package_maker](../qti_package_maker): QTI export/package tooling used with problem pipelines.
- [../ADAPT-WeBWorK-Handbook](../ADAPT-WeBWorK-Handbook): Handbook and guidance for ADAPT/WeBWorK workflows.

## Status

This repository is an active question bank and should be validated in your target WeBWorK environment before course release.
