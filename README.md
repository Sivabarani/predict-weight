# predict weight dataset

This dataset contains detailed health information for 100 participants. The weight of participants in this dataset is calculated based on their daily diet habits, lifestyle choices, and physical activity levels. 

**Understanding Supervised Learning:**
Supervised learning involves predicting an outcome based on labeled data, where both the input features and the output are known. This dataset is used for supervised learning (specifically regression), where the "Final Weight" column is the outcome we aim to predict based on the other health-related features.

**Dataset Description**
1. Participant ID:
   A unique identifier assigned to each participant to track their data.

2. Age:
   The participant’s age, which can affect weight changes. Older participants may experience slower metabolism rates, influencing weight gain or loss.

3. Gender:
   The participant’s gender (M/F). Weight can be influenced by biological differences between genders, with males and females often having different caloric requirements and    fat distribution patterns.

4. Current Weight (lbs):
   The weight of the participant at the start of the data collection, measured in pounds. This serves as a reference point for tracking weight change over time.

5. BMR (Calories): 
The Basal Metabolic Rate, calculated using the Mifflin-St Jeor equation. It estimates the number of calories burned at rest, which serves as a baseline for understanding how many calories the body needs to function in a state of rest.
_Note:_ BMR is the amount of energy (calories) your body needs to maintain basic physiological functions while at rest

7. Daily Calories Consumed:
The number of calories the participant consumes on a daily basis. This is a key determinant of weight changes, as consuming more calories than the body burns can lead to weight gain, while a calorie deficit can lead to weight loss.

8. Daily Caloric Surplus/Deficit:
This is the difference between the calories consumed and the participant's BMR. A positive surplus indicates weight gain, while a negative deficit suggests weight loss. It is essential in predicting changes in body weight.
_Note:_
Caloric Surplus: A state where the number of calories consumed exceeds the number of calories the body needs. This results in weight gain because the excess calories are stored as fat.
Caloric Deficit: A state where the number of calories consumed is less than the body needs. This results in weight loss, as the body uses stored fat to make up the difference.

10. Weight Change (lbs):
The amount of weight the participant gains or loses during the tracking period, in pounds. This is typically calculated by considering the caloric surplus or deficit over time.

11. Duration (weeks):
The period over which weight change is observed, measured in weeks. Weight change is often tracked over a period of several weeks to understand trends and determine the effectiveness of diet or lifestyle changes.

12. Physical Activity Level:
The level of physical activity reported by the participant. Categories include Sedentary, Lightly Active, Moderately Active, and Very Active. Higher activity levels generally contribute to higher energy expenditure, influencing weight management.

13. Sleep Quality:
A self-reported measure of the participant's sleep quality, categorized as Poor, Fair, Good, or Excellent. Poor sleep quality can affect metabolism and appetite, contributing to weight gain or loss over time.

14. Stress Level:
A score (1-10) indicating the participant’s perceived stress level. High stress can lead to emotional eating, hormonal changes, and other factors that contribute to weight fluctuations.

15. Final Weight (lbs):
The participant's weight at the end of the study or data collection period. This is the target variable we aim to predict, and it may be influenced by all other features in the dataset.

**Objective:**
The goal of this analysis is to predict the final weight of participants. While the "Final Weight (lbs)" column is the target variable, the dataset also provides an opportunity to explore the relationships between other health-related features (independent variables).

**Understanding Data Relationships: Dependent vs. Independent Variables:**

**1. _Dependent Variable:_** The "Final Weight (lbs)" column is the outcome we are trying to predict.
**2. _Independent Variables:_** All other columns are considered independent variables that may influence the final weight, including Participant ID, Age, Gender, Current Weight, BMR, Daily Calories Consumed, Caloric Surplus/Deficit, Weight Change, Duration, Physical Activity Level, Sleep Quality, and Stress Level.
