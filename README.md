# Whole-Body Signatures of Speech Planning & Production

## Conda Environment

Install [Miniconda](https://docs.conda.io/projects/miniconda/en/latest/) or Anaconda, then open Anaconda Prompt or PowerShell and run:

```powershell
cd G:\whole-body-speech-planning
conda env create --name nemo --file environment.yml
conda activate nemo
```

Verify that the environment is active:

```powershell
conda env list
python --version
```

The environment uses Python 3.10 and includes the project dependencies, including CUDA-enabled PyTorch. GPU use requires a compatible NVIDIA driver.

If the `nemo` environment already exists, update it with:

```powershell
conda env update --name nemo --file environment.yml --prune
conda activate nemo
```

When finished, leave the environment with:

```powershell
conda deactivate
```

