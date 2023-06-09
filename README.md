# Synthetic Healthcare Data Generation
This project utilizes a Generative Adversarial Network (GAN) to generate synthetic healthcare data based on the Synthea dataset. The Synthea dataset contains synthetic healthcare records designed to mimic real-world patient data.

## Dataset
The dataset used is the Synthea dataset, specifically the synthea_sample_data_csv_apr2020.zip archive. It consists of various CSV files representing different aspects of patient records.

## Methodology
**Exploratory Data Analysis (EDA):** Analyzing the structure and statistical properties of the dataset.

**Data Preprocessing:** Cleaning, handling missing values, normalizing numerical features, and encoding categorical variables.

**GAN Training:** Training the GAN to generate realistic synthetic patient records.

**Discriminator Training: **Fine-tuning the discriminator to improve differentiation between real and synthetic data.

**Statistical Analysis:** Evaluating the statistical properties of the generated data for validation.

## Project Structure
csv/: Contains the original Synthea dataset files.
data/: Holds the preprocessed dataset for GAN training.
models/: Stores the trained GAN and discriminator models.
results/: Contains the evaluation metrics and generated data.
notebooks/: Includes Jupyter notebooks for EDA, preprocessing, GAN training, and analysis.

## Results and Evaluation
The quality and utility of the generated synthetic data are assessed by comparing it with the original Synthea dataset using accuracy, precision, recall, and statistical similarity metrics.



## Conclusion
This project demonstrates the generation of realistic synthetic healthcare data using a GAN implemented with Keras. The combination of EDA, data preprocessing, GAN training, and statistical analysis provides a comprehensive approach for generating high-quality synthetic patient records. The generated data can be used for research, analysis, and development of healthcare solutions while ensuring patient privacy.

