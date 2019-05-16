# Introduction
This dataset contains information from 110527 medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. 

# Data
A number of characteristics about the patient are included in each row. 
-  PatientId: Identification of a patient
-  AppointmentID: Identification of each appointment
-  Gender: Male or Female
-  ScheduledDay: What day the patient set up their appointment.
-  AppointmentDay: The day of the actual appointment, when the patient has to visit the doctor
-  Age: How old is the patient 
-  Neighbourhood: Indicates the location of the hospital.
-  Scholarship: 0 or 1; 1 indicates that the patient is in the Bolsa Familia program
-  Hipertension: 0 or 1; 1 indicates that the patient has hipertension
-  Diabetes: 0 or 1; 1 indicates that the patient has diabetes
-  Alcoholism: 0 or 1; 1 indicates that the patient has problem of alcoholism
-  Handcap: 0 0r 1; 1 indicates that the patient is handicapped
-  SMS_received: 0 or 1; 1 indicates that a SMS was received 
-  No_show "No" indicates that the patient showed up to their appointment and "Yes" that the patient didn't show up for the appointment 

# Objective

- Data analysis to answer the following questions:

 1. Is the proportion of No Shows significantly less for appointments booked on the same day? 
 2. Does the rate of no show vary according to age group? 
 3. Do certain neighbourhoods have higher number of no shows than others? Which are the top 5 neighbourhoods for no shows? 
 4. Does the day of the week of the appointment influences the patient not showing up for the appointment? 
 5. Does the no_show rate increase as lag increases? 
 6. Understand what factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

# Highlights
- Feature engineering for age groups, day of week;
- Extensive data visualization - countplot, heatmap, histogram, correlation heatmap
- Logistic Regression coefficients interpretation
- Recursive Feature Elimination
- ROC Curve
