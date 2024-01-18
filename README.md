Project_2_PCOS Readme

Introduction

This repository contains the code and documentation for Project_2_PCOS, focused on predicting Polycystic Ovary Syndrome (PCOS) and visualizing the results in Tableau. The dataset is obtained from Kaggle and consists of two dataframes: one for PCOS patients named "PCOS_data_without_infertility_new" and another for infertility patient information with fewer variables named "pcos_infertility."



Goals


Goal 1: Determine the correlation between infertility and PCOS

- Tableau Visualization:

		- Create a Tableau dashboard showcasing patient information, emphasizing PCOS and infertility cases.
		- Utilize dynamic filters for exploring data based on different parameters.

- Statistical Analysis:

		- Conduct statistical tests (e.g., chi-square test) to assess the association between PCOS and infertility.
		- Visualize the correlation matrix between PCOS and infertility using Tableau.




Goal 2: Identify important variables in diagnosing PCOS


- Tableau Visualization:

		- Develop visualizations in Tableau (e.g., correlation plots, box plots) to identify variables strongly correlated with 		PCOS.
		- Use histograms to illustrate the distribution of important variables.

- Feature Importance:

		- Apply machine learning models with feature importance outputs (e.g., logistic regression coefficients) to identify 			crucial variables.




Goal 3: Select the best model for PCOS prediction


- Tableau Visualization:

		- Construct a Tableau dashboard presenting model evaluation metrics (e.g., recall, precision, F1-score) for different 			models.

- Model Evaluation:

		- Evaluate multiple models (e.g., logistic regression, KNN) using relevant metrics.
		- Choose the model with the highest recall, considering the imbalanced nature of the data.


Final DataFrame and Tableau Visualization

 - Tableau Dashboard:

		- Integrate the final dataframe into Tableau for comprehensive visualization.
		- Develop interactive dashboards allowing users to explore various features and their relationships.
		Storytelling:








Data Frame Glossary

Patient File No. : This is the report number which has data for a particular patient
PCOS : Polycystic ovary syndrome (PCOS) is a hormonal disorder common among women of reproductive age, we would like to determine whether the patient has this syndrome or not
Age (yrs) : Age of patient in years
Weight (Kg) : Weight of patient in kg
Height(Cm) : Height of patient in centimeter
BMI : Body mass index of the patient
Blood Group : Blood Group of the patient A+ = 11, A- = 12, B+ = 13, B- = 14, O+ =15, O- = 16, AB+ =17, AB- = 18 (total 8 blood groups)
Pulse rate(bpm) : It is the heart rate of patient in beats per minute. Resting heart rate for adults ranges from 60 to 100 beats per minute
RR (breaths/min) : It is the respiration rate. Normal respiration rates for an adult person at rest range from 12 to 16 breaths per minute.
Hb(g/dl) : Hemoglobin levels in gram per deciliter. For women, a normal level ranges between 12.3 gm/dL and 15.3 gm/dL.
Cycle(R/I) : ....
Cycle length(days) : This represents length of menstrual cycle. The length of the menstrual cycle varies from woman to woman, but the average is to have periods every 28 days.
Marraige Status (Yrs) : Years of marriage
Pregnant(Y/N) : If the patient is pregnant
No. of aborptions : No. of aborptions, if any. There are total 541 values out of which 437 patients never had any abortions.
I beta-HCG(mIU/mL) : this is case 1 of beta hcg
II beta-HCG(mIU/mL) : this is case 2 of beta hcg (please note: An beta hCG level of less than 5 mIU/mL is considered negative for pregnancy, and anything above 25 mIU/mL is considered positive for pregnancy) (also the unit mIU/mL is mili International Units per miliLiter)
FSH(mIU/mL) : Its full form is Follicle-stimulating hormone. During puberty: it ranges from 0.3 to 10.0 mIU/mL (0.3 to 10.0 IU/L) Women who are still menstruating: 4.7 to 21.5 mIU/mL (4.5 to 21.5 IU/L) After menopause: 25.8 to 134.8 mIU/mL (25.8 to 134.8 IU/L)
LH(mIU/mL) : It is Luteinizing Hormone.
FSH/LH : Ratio of FSH and LH
Hip(inch) : Hip size in inches
Waist(inch) : Waist Size in inches
Waist:Hip Ratio : Waist by hip ratio
TSH (mIU/L) : It is thyroid stimulating hormone. Normal values are from 0.4 to 4.0 mIU/L
AMH(ng/mL) : It is Anti-Mullerian Hormone.
PRL(ng/mL) : This represents Prolactin levels.
Vit D3 (ng/mL): Vitamin D levels. Normal vitamin D levels in the blood are 20 ng/ml or above for adults.
PRG(ng/mL): Progesterone levels
RBS(mg/dl): This value is obtained by doing Random Blood Sugar (RBS) Test.
Weight gain(Y/N): Is there been a weight gain
hair growth(Y/N): Is there been a hair growth