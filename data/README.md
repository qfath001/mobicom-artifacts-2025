# Data (SCVIC-APT-2021)

We use two CSVs:
- `Training.csv`
- `Testing.csv`

## Where to get the files
Download both from the official folder shared by the authors:  
https://drive.google.com/drive/folders/1XIlVteHaHFqBXqNApYGb3RoHcBkqpRoR

## Where to put the files
Do **not** commit these CSVs to Git (they’re large and are ignored via `.gitignore`).

- **Colab:** Upload to Google Drive under a folder you choose, e.g.:
  `MyDrive/mobicom-artifacts-2025/data`
- **Local:** Place the CSVs in a local `data/` folder next to this repo.

## Local/runtime layout (on your machine or Colab Drive)
# CSVs live here when you run the notebook (NOT committed to Git)
mobicom-artifacts-2025/
├─ notebooks/
│  └─ MOBICOM_CODE.ipynb
├─ data/
│  ├─ Training.csv
│  └─ Testing.csv
└─ ...


