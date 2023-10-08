# Data_analysis_haberman
* Finding out, how many patients survived the cancer after the year of surgery let us define and understand the variables first.

## Objective of the data analysis on Haberman's Data set:
* Identify and analyze if there are any possibilities of identifying similrities in determining the factors which led to the survival or death of patients after undergoing operation.
* Perform Exploratory Data Analysis(EDA) on the given data.
* Perform Univaraite analysis(PDF, CDF, Boxplot, Voilin plots) to understand which features are useful towards classification.
* Perform Bi-variate analysis (scatter plots, pair-plots) to see if combinations of features are useful in classfication.


## KPI's
* Age: Age of the patient at the time of study
* Year: Year of operation of the patient.
* Nodes: The lymph nodes are small bean like organs found in the human body. Preserence of cancerous cells in the lymph nodes under the arm may suggest that there might be possibility of breast cancer in the patient.
* Status: The status indicates survival rate of the patient who has been through surgery and has surviced more than 5 years. In the data set, the number '1' indicates that the patient survived the surgery and '2' indicates that the patient died within 5 years of surgery.

## Final Observations:
### Summary of Univariate Analysis - CDF and PDF
* We can see that the death of patients is affected mainly by preserence of more number of Lymph nodes.
* We can also see some relation with the age being a factor which will may affect the survival of a patient.
* Summary and Observations of Box Plot and violin plot
* The increase in nodes can significantly increase the rate of death, there are significantly more yellow points above the line where the nodes are more than 10, although there are points which are overlapping.
* There are more chances of death of patient if the nodes are more than 5 and the age of the patient crosses the age of 45. This is the best outcome which helps analyse the data. Since the nature of data depends greately on various factors, this is the best of analysis.

### Pair Plot and Scatter Plot Observations
* The scatter plot and pair plot, although show no clear indications, and overlapping of a lot of points is observed, it can be seen in the third plot, {Age vs Node} of Pair plot, that the survival rate is maximum in the patients with nodes numbering between 0 and 1
​
