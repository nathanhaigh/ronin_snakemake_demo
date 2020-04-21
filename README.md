# Demonstration Snakemake Workflow for Ronin/AWS Slurm-based Auto-scaling Cluster

This workflow provides the necessary Slurm profile, cluster configuration files and test dataset to demonstrate how Snakemake can be run on a Ronin/AWS Slurm-based auto-scaling cluster.

## Authors

* Nathan S. Watson-Haigh (@nathanhaigh)

## Usage

### Step 1: Install workflow

```bash
git clone https://github.com/nathanhaigh/ronin_snakemake_test
cd ronin_snakemake_test
```

### Step 2: Execute workflow

```bash
snakemake --profile profiles/slurm
```

# Acknowledgements

The test workflow is copied from: https://github.com/snakemake-workflows/ngs-test-data
