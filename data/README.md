# AIDev Dataset Information

This project does not include the raw AIDev dataset files because they are very large and exceed GitHub's storage limits.  
Instead, all data is downloaded directly from HuggingFace at runtime.

---

## Dataset Source

The AIDev dataset is publicly available at:

https://huggingface.co/datasets/hao-li/AIDev

It contains three primary components:

- **`all_pull_request.parquet`** — pull request metadata  
- **`all_repository.parquet`** — repository-level metadata  
- **`all_user.parquet`** — contributor information  

These files include timestamps, repository statistics, account metadata, and PR text fields.

---

## How the Project Loads the Data

Our analysis scripts access the dataset directly using Python:

```python
import pandas as pd

all_pr_df = pd.read_parquet("hf://datasets/hao-li/AIDev/all_pull_request.parquet")
all_repo_df = pd.read_parquet("hf://datasets/hao-li/AIDev/all_repository.parquet")
all_user_df = pd.read_parquet("hf://datasets/hao-li/AIDev/all_user.parquet")
