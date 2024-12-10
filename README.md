# **Gym Members Exercise Dataset**

## About Dataset
This dataset provides a detailed overview of gym members' exercise routines, physical attributes, and fitness metrics. It contains 973 samples of gym data, including key performance indicators such as heart rate, calories burned, and workout duration. Each entry also includes demographic data and experience levels, allowing for comprehensive analysis of fitness patterns, athlete progression, and health trends.

### Key Features:

Age: Age of the gym member.
Gender: Gender of the gym member (Male or Female).
Weight (kg): Member’s weight in kilograms.
Height (m): Member’s height in meters.
Max_BPM: Maximum heart rate (beats per minute) during workout sessions.
Avg_BPM: Average heart rate during workout sessions.
Resting_BPM: Heart rate at rest before workout.
Session_Duration (hours): Duration of each workout session in hours.
Calories_Burned: Total calories burned during each session.
Workout_Type: Type of workout performed (e.g., Cardio, Strength, Yoga, HIIT).
Fat_Percentage: Body fat percentage of the member.
Water_Intake (liters): Daily water intake during workouts.
Workout_Frequency (days/week): Number of workout sessions per week.
Experience_Level: Level of experience, from beginner (1) to expert (3).
BMI: Body Mass Index, calculated from height and weight.

# Exercise:

## Basic Data Exploration
1. Load the dataset into a DataFrame and display the first five rows.
2. Check the data types of all columns and identify if any require transformation.
3. Find the total number of gym members (rows) and features (columns) in the dataset.

## Statistical Insights
1. What is the average weight and height of gym members?
2. Find the maximum, minimum, and average session duration.
3. Determine the mean and standard deviation of calories burned across all sessions.
   
## Filtering and Conditional Selection
1. List all members who are beginners (Experience_Level == 1) and burn more than 500 calories per session.
2. Retrieve the details of members whose BMI is classified as overweight (BMI > 25).
3. Select members with an average heart rate (Avg_BPM) higher than 150 and perform cardio workouts.

## GroupBy and Aggregation
1. Calculate the average calories burned for each workout type.
2. Find the maximum BMI for each experience level.
3. Determine the total number of workout sessions per week for each gender.

## Data Transformation
1. Add a new column Calories_per_Hour, calculated as Calories_Burned / Session_Duration.
2. Create a column BMI_Category that categorizes members as Underweight, Normal weight, Overweight, or Obese based on their BMI.
3. Normalize the Calories_Burned column to a scale of 0–1.

## Advanced Analysis
1. Find the correlation between Calories_Burned and other numerical features.
2. Identify any outliers in the Max_BPM column using statistical methods like the Interquartile Range (IQR).
3. Plot the relationship between Workout_Frequency and Fat_Percentage to analyze trends.

## Custom Challenges
1. Determine the percentage of gym members who perform strength training and have a fat percentage below 20%.
2. For each experience level, find the average water intake and plot it as a bar chart.



