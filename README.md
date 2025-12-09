## Data Versioning (Task 2)

This project uses DVC to version-control the raw insurance dataset.

- Raw data: `data/raw/insurance_data.csv` (tracked by DVC)
- Local DVC remote: `../dvc_storage`

To pull the data:

```bash
dvc pull
