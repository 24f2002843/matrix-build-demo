# Matrix Build Demo Repository

This repository demonstrates a GitHub Actions matrix build strategy with parallel execution and artifact management.

## Workflow Features

- **Matrix Strategy**: Builds across 3 operating systems and 3 Node.js versions (9 total combinations)
- **Parallel Execution**: All matrix jobs run simultaneously
- **Artifact Management**: Each job generates and uploads unique build artifacts
- **Step Identifier**: Includes the required `matrix-987e3c6` identifier step

## Matrix Configuration

- **Operating Systems**: ubuntu-latest, macos-latest, windows-latest
- **Node.js Versions**: 18, 20, 22
- **Artifact Prefix**: `build-987e3c6-`

## Artifacts Generated

Each matrix job creates:
- `build-info.json` - Build metadata in JSON format
- `build-output.txt` - Simple build output
- Platform-specific artifacts
- Node.js version configuration files

## Contact

Email: 24f2002843@ds.study.iitm.ac.in
