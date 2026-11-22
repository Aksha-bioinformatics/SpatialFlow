# SpatialFlow — Software and System Environment

## Original Environment — Ubuntu 20.04
- OS: Ubuntu 20.04.6 LTS
- Environment: Windows Subsystem for Linux 2 (WSL2)
- Kernel: 6.18.58.1-microsoft-standard-WSL2
- Git: 2.25.1
- Python: 3.8.10
- Java: Not installed at initial assessment
- Nextflow: Not installed at initial assessment
- CPU cores visible to WSL: 12
- RAM visible to WSL: 3.7 GiB
- Swap: 1.0 GiB

## Active Development Environment — Ubuntu 24.04
- OS: Ubuntu 24.04.5 LTS
- Environment: Windows Subsystem for Linux 2 (WSL2)
- Git: 2.43.0
- Python: 3.12.3
- Java: OpenJDK 21.0.13.1
- Nextflow: 26.10.7, build 15252
- CPU cores visible to WSL: 12
- RAM visible to WSL: 3.7 GiB
- Available RAM at assessment: 3.3 GiB
- Swap: 1.0 GiB

## Verification
- Java verified using: java -version
- Nextflow verified using: nextflow -version
- Nextflow execution tested using: nextflow run hello
- Hello workflow result: 4 of 4 tasks completed successfully.

## Pending Software
- Python virtual environment
- Scanpy
- Squidpy

## Resource Considerations
- WSL exposes approximately 3.7 GiB RAM.
- Pipeline execution will be configured conservatively.
- WSL filesystem availability does not necessarily represent free space on the Windows drive.
