# Final-Project-Heart-Failure-Prediction
![image.png](heart.png)

Heart Failure Prediction
The task of this project is to analyze dataset containing different characteristics of 918 patients to predict heart failures using Python, Machine Learning and data visualization tools. Utilize machine learning model to create a model to assess the likelihood of a possible heart disease event.

**Understanding the terms/characteristics in the dataset**

**ChestPainType** - TA: Typical Angina - substernal chest pain precipitated by physical exertion or emotional stress and relieved with rest or nitroglycerin; ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic.
ATYPICAL(ATA)=not representative of a type, group, or class.
TYPICAL(TA)= REPRESENTATIVE OF TYPE, GROUP
NAP- Non-cardiac chest pain (NCCP) is a term used to describe chest pain that resembles heart pain (also called angina)
ASY=The resulting shortfall in oxygen-rich blood to your heart muscle can cause the chest discomfort known as angina.
This pain may spread to your shoulders, arms, neck, or jaw. But here's a little-known fact: some of the time,
ischemia causes no symptoms. And this so-called silent ischemia is surprisingly common.


**RestingBP** - Blood pressure is a measure of the force that your heart uses to pump blood around your body. Resting blood pressure in mm Hg/ millimeters of mercury. A normal reading would be any blood pressure below 120/80 mm Hg and elevated 120 to 129 mm Hg – systolic< 80 mm Hg – diastolic

**Cholesterol** - Total or serum cholesterol measured in milligrams (mg) of cholesterol per deciliter (dL) of blood. To come up with the serum cholesterol we need to add your HDL and LDL cholesterol levels, plus 20 percent of your triglycerides, to calculate your serum cholesterol levels. Below 200 mg/dL - is desirable/normal; 200-239 mg/dL - borderline high; 240 mg/dL and above - high.

**RestingECG** - The normal range of the ECG differed between men and women: heart rate 49 to 100 bpm vs. 55 to 108 bpm, P wave duration 81 to 130 ms vs. 84 to 130 ms, PR interval 119 to 210 ms vs. 120 to 202 ms, QRS duration 74 to 110 ms vs.
What is LVH on an ECG? Left ventricular hypertrophy (LVH), also known as an enlarged heart, is a condition in which the muscle wall of heart's left pumping chamber (ventricle) becomes thickened (hypertrophy). Modified Cornell Criteria: Examine the R wave in aVL. If the R wave is greater than 12 mm in amplitude, LVH is present. Sokolow-Lyon Criteria: Add the S wave in V1 plus the R wave in V5 or V6. If the sum is greater than 35 mm, LVH is present. The ST segment encompasses the region between the end of ventricular depolarization and beginning of ventricular repolarization on the ECG. In other words, it corresponds to the area from the end of the QRS complex to the beginning of the T wave. The ST segment is the interval between the end of the QRS complex (J point, or ST junction) and the beginning of the T wave. In the limb leads, the ST segment is isoelectric in about 75 percent of normal adults. 19. ST segment elevation or depression up to 0.1 mV generally is considered within normal limits. The resting ECG is a simple, quick and painless test. The resting ECG can detect certain heart conditions such as hypertrophy of heart, ischemia, myocardial infarction, sequelae of myocardial infarction, cardiac arrhythmias, etc. The test takes about 5 minutes and no preparation is necessary. 

**MaxHR** - Maximum Heart Rate: The increase in the cardiovascular risk, associated with the acceleration of heart rate, was comparable to the increase in risk observed with high blood pressure. An increase in heart rate by 10 beats per minute was associated with an increase in the risk of cardiac death by at least 20%, and this increase in the risk is similar to the one observed with an increase in systolic blood pressure by 10 mm Hg.

Oldpeak