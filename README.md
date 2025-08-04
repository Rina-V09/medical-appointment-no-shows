# Data Cleaning — Medical Appointment No Shows

## 🎯 Objective
Clean and preprocess the raw Medical Appointment No Shows dataset from Kaggle, making it ready for analysis by removing inconsistencies, handling missing data, fixing formats, and standardizing values.

## 🛠 Tools
- Python (Pandas, Matplotlib)

## 📂 Repository Structure
medical-appointment-no-shows/
├── data/
│ ├── medical_appointment_no_shows.csv
│ └── medical_appointment_no_shows_cleaned.csv
├── scripts/
│ └── clean_medical_appointment.py
├── screenshots/
│ ├── before_cleaning.png
│ └── after_cleaning.png
└── README.md


## ✅ Cleaning Steps
- Normalized column names to lowercase with underscores.
- Standardized `gender` to uppercase (`M`, `F`).
- Converted date columns to datetime format.
- Converted `no_show` to binary (1 = yes, 0 = no).
- Removed duplicate rows.
- Ensured numeric columns are correct types.
- Removed invalid ages (negative values).
- Saved cleaned dataset as `medical_appointment_no_shows_cleaned.csv`.


## 🧾 Author
Rina Kumari — Master of Computer Applications
