# Dataset

The NephroPatch machine-learning experiments use the **Chronic Kidney Disease Dataset** cited in the project research paper:

Rabie El Kharoua (2024), *Chronic Kidney Disease Dataset*, Kaggle.

The original project reports 1,659 records.

## Expected local filename

Place the downloaded CSV here as:

`Chronic_Kidney_Disease_data.csv`

The raw CSV is intentionally excluded from Git by `.gitignore`. This keeps the repository lightweight and avoids redistributing a third-party dataset.

The notebooks load the dataset using a relative path, so they work across operating systems instead of relying on the original Windows-specific file path.
