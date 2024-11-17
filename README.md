# predict-weight-dataset
This dataset contains details about 100 participants' health information

**Understanding Supervised Learning** Supervised learning involves predicting an outcome based on labeled data. Initially, I considered this dataset for supervised learning (Regression) applications, particularly for analyzing participants' weight based on health information.

**Dataset Description**
1. Participant ID: Unique ID of the participant 
2. Age: Participant's age.
3. Gender:  Participant's gender(M/F) the weight is changed as per age and gender of participant 
4. Current Weight (lbs): the current weight of the participant. The weight is measured in pounds.
5. BMR (Calories): Basal Metabolic Rate, calculated using the Mifflin-St Jeor equation, representing the number of calories burned at rest.
6. Daily Calories Consumed: This refers to the participant's intake per day.
7. Daily Caloric Surplus/Deficit: The difference between calories consumed and BMR, indicates whether the participant is in a caloric surplus or deficit.
8. Weight Change (lbs): the change in weight over a specified duration, based on caloric surplus/deficit.
9. Duration (weeks): The period over which weight change is measured, ranging from 1 to 12 weeks. 
10. Physical Activity Level: Self-reported level of physical activity, categorized as Sedentary, Lightly Active, Moderately Active, or Very Active.
11. Macronutrient Breakdown: Composition of the participant's diet, expressed as percentages of carbohydrates, proteins, and fats.
12. Sleep Quality: Self-reported quality of sleep, categorized as Poor, Fair, Good, or Excellent, which can affect weight management.
13. Stress Level: A numerical score (1-10) indicating the participant's perceived stress level, as stress can influence eating behaviors and weight.
14. Final Weight (lbs): the final weight of participant.

**Objective** The goal of this analysis is to identify the weight of participants. While the "Final Weight (LBS)" column is our main focus, we may also explore how other features relate to it, noting that they can be considered independent variables in this context.

**Understanding Data Relationships** **Dependent vs. Independent Variables:** Dependent Variable: In this case, the "Final Weight (LBS)" column, which we aim to analyze or predict. Independent Variables: Other features such as participant ID, age, Gender, Current Weight (lbs), BMR (Calories), Daily Calories Consumed,
Daily Caloric Surplus/Deficit,  Weight Change (lbs), Duration (weeks), Physical Activity Level, Macronutrient Breakdown, Sleep Quality, Stress Level, Final Weight (lbs)
