# SpatialFlow — Project Development Log

## 2026-11-22 — Initial Environment and Repository Setup

### Project
- Name: SpatialFlow
- Aim: A Reproducible Nextflow Pipeline for Spatial Transcriptomics Analysis.
- Development environment: Local Windows laptop using WSL2 and Ubuntu.
- Project directory: ~/bioinformatics/SpatialFlow

### Repository Setup
- Initialized local Git repository.
- Configured Git username and GitHub noreply email.
- Created GitHub repository:
  https://github.com/Aksha-bioinformatics/SpatialFlow
- Default branch: main
- Added README.md.
- Created initial commit and pushed it to GitHub.
- Created project directories:
  data/, scripts/, results/, docs/, workflows/,
  modules/, config/, tests/
- Added .gitignore.

### Verified System Environment
- Ubuntu 20.04.6 LTS
- WSL2 kernel: 6.18.58.1-microsoft-standard-WSL2
- Git: 2.25.1
- Python: 3.8.10
- Java: Not installed
- CPU cores visible to WSL: 12
- RAM visible to WSL: 3.7 GiB
- Swap: 1.0 GiB
- Available WSL filesystem space: 953 GB

### Pending
- Review and update the Ubuntu environment.
- Install a compatible Java version.
- Install and verify Nextflow.
- Set up a reproducible Python environment.
- Select and document a public spatial transcriptomics dataset.
- Develop and test the analysis workflow.

### Reproducibility Note
Only verified commands, versions, dataset details, outputs, and
analysis results will be recorded as completed project steps.

## 2026-11-22 — Migration to Ubuntu 24.04 and Nextflow Setup

### Migration
- Installed Ubuntu 24.04.5 LTS as a separate WSL2 distribution.
- Preserved the existing Ubuntu 20.04 distribution.
- Exported Ubuntu 20.04 backup to:
  C:\Users\abdul\Ubuntu-20.04-backup.tar
- Backup export completed successfully.
- Existing SpatialFlow repository remains in Ubuntu 20.04 pending transfer.

### Active Development Environment
- Ubuntu 24.04.5 LTS
- Git 2.43.0
- Python 3.12.3
- OpenJDK 21.0.13.1
- Nextflow 26.10.7 (build 15252)
- CPU cores visible to WSL: 12
- RAM visible to WSL: 3.7 GiB
- Available RAM at verification: 3.3 GiB
- Swap: 1.0 GiB
- Available filesystem space: 954 GB

### Nextflow Installation
- Downloaded using the official Nextflow installation script:
  curl -fsSL https://get.nextflow.io | bash
- Installed executable at ~/.local/bin/nextflow
- Added ~/.local/bin to PATH through ~/.bashrc.
- Verified using: nextflow -version

### Execution Test
- Command: nextflow run hello
- Example repository: nextflow-io/hello
- Revision: 3c2cdc9823
- Executor: local
- Result: 4 of 4 tasks completed successfully.
- Output included Ciao, Hola, Hello, and Bonjour world.

### Pending
- Commit and push the updated project structure and documentation.
- Clone the repository into Ubuntu 24.04.
- Configure a Python virtual environment.
- Install and verify Scanpy and Squidpy.
- Select a public spatial transcriptomics dataset.
- Develop the SpatialFlow Nextflow workflow.
