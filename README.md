About Dataset
Overview
The Student Social Media & Relationships dataset contains anonymized records of students’ social‐media behaviors and related life outcomes. It spans multiple countries and academic levels, focusing on key dimensions such as usage intensity, platform preferences, and relationship dynamics. Each row represents one student’s survey response, offering a cross‐sectional snapshot suitable for statistical analysis and machine‐learning applications.

Scope & Coverage
Population: Students aged 16–25 enrolled in high school, undergraduate, or graduate programs.
Geography: Multi‐country coverage (e.g., Bangladesh, India, USA, UK, Canada, Australia, Germany, Brazil, Japan, South Korea).
Timeframe: Data collected via a one‐time online survey administered in Q1 2025.
Volume: Configurable sample sizes (e.g., 100, 500, 1,000 records) based on research needs.
Data Collection & Methodology
Survey Design: Questions adapted from validated scales on social‐media addiction (e.g., Bergen Social Media Addiction Scale) and relationship conflict indices.

Recruitment: Participants recruited through university mailing lists and social‐media platforms, ensuring diversity in academic level and country.

Data Quality Controls:

Validation: Mandatory fields and range checks (e.g., usage hours between 0–24).
De‐duplication: Removal of duplicate entries via unique Student_ID checks.
Anonymization: No personally identifiable information collected.
Key Variables
Variable	Type	Description
Student_ID	Integer	Unique respondent identifier
Age	Integer	Age in years
Gender	Categorical	“Male” or “Female”
Academic_Level	Categorical	High School / Undergraduate / Graduate
Country	Categorical	Country of residence
Avg_Daily_Usage_Hours	Float	Average hours per day on social media
Most_Used_Platform	Categorical	Instagram, Facebook, TikTok, etc.
Affects_Academic_Performance	Boolean	Self‐reported impact on academics (Yes/No)
Sleep_Hours_Per_Night	Float	Average nightly sleep hours
Mental_Health_Score	Integer	Self‐rated mental health (1 = poor to 10 = excellent)
Relationship_Status	Categorical	Single / In Relationship / Complicated
Conflicts_Over_Social_Media	Integer	Number of relationship conflicts due to social media
Addicted_Score	Integer	Social Media Addiction Score (1 = low to 10 = high)
Potential Analyses
Correlation Studies: Examine associations between daily usage hours and mental‐health score or sleep hours.
Predictive Modeling: Build classifiers to predict relationship conflicts based on usage patterns and platform type.
Clustering: Identify user segments (e.g., “high‐usage high‐stress” vs. “moderate‐usage balanced”) across countries.
Limitations
Self‐Report Bias: All measures are self‐reported and may be subject to social‐desirability effects.
Cross‐Sectional Design: One‐time survey prevents causal inference.
Sampling Variability: Recruitment via online channels may underrepresent students with limited internet access.
