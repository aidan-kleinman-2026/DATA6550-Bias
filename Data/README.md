📊 FairFace Dataset

This project uses the FairFace dataset, a large-scale face image dataset designed to support research on fairness and bias in facial recognition systems. FairFace provides balanced labels across race, gender, and age, making it well-suited for bias analysis and evaluation.

Due to GitHub storage and file count limitations, the FairFace image files are not included in this repository. However, all analysis code assumes the dataset is available locally in the structure described below.

🔽 Dataset Access

To reproduce our analysis:

1. Download the FairFace dataset from Kaggle:  
   https://www.kaggle.com/datasets/ghaidaalatoum/fairface

2. Extract the downloaded files into the `Data/` directory of this repository.

3. Verify that your local directory structure matches the following:

```text
Data/
├── train/
├── val/
├── fairface_label_train.csv
└── fairface_label_val.csv
```

📝 Notes
	•	The train/ and val/ directories contain the image files used for model training and evaluation.
	•	The CSV files provide demographic labels associated with each image.
	•	All scripts in the Code/ and Analysis/ directories assume this directory structure.
