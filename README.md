#  Investigate a Dataset - [No-show appointments]
This project is affiliated with Udacity Data Analyst Nanodegree

In this project, I Investigated and analyzed a Medical appointment Dataset following through the 6 data analytics process using Python, NumPy, Pandas, Matplotlib, Seaborn tools in a Jupyter notebook, after which I drew insightful and valuable conclusions from the dataset and excellently communicated project findings.
###  Dataset Description
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

###  Data Dictionary

* PatientId: Identification of a patient
* AppointmentID: Identification of each appointment
* Gender: Male or Female
* ScheduledDay: the day when the patient called or registered the appointment
* AppointmentDay: the day of the actual appointment, when they have to visit the doctor
* Age: How old is the patient
* Neighbourhood: Where the appointment takes place
* Scholarship: True of False
* Hipertension: True or False
* Diabetes: True or False
* Alcoholism: True or False
* Diabetes: True or False
* SMS_received: True or False
* No-show: True or False

##  Question(s) for Analysis
* Q1: does age affect attendance rate?
* Q2: what factors affect patients' attendance the most?
* Q3: which age category is affected the most by chronic diseases?
* Q4: does age and chronic diseases affect attendance rate?
* Q5: does age and gender affect attendance rate?
* Q6: does neighbourhood affect attendance rate?
* Q7: does neighbourhood & sms_received affect attendance?
* Q8: does neighbourhood & age affect attendance

## Conclusions
* nearly 25% of patients miss their appointment
* age has a clear influence on attendance rate (most showed patients are between 0 ~ 10 years old)
* more females booked for appointment compared to their male counterparts (64% of females showed up for their appointment)
* 90% of patients who attended has no scholarship which clearly shows that scholarship has no effect on attendance rate
* 66% of patients who did not receive sms has attended (that may indicate that we need to work more on sms campaign)
* adults and seniors are more affected by chronic diseases (hypertension and diabetes)
* there's no correlation between chronic diseases and patients' attendance
* neighbourhood has a great effect on attendance (JARDIM CAMBURI has most patients no. and showing rate as well)
* no. of showing patients from specific neighbourhood is affected by receiving sms and age

## Limitations
* The female gender might be oversampled in this dataset.
* no_show column may cause confusion because the values inside it are reversed with the negation in the column name.
* most columns take only two values 0 or 1 which made the deep investigation and the discovering the correlation is difficult.
* we don't have enough details for certain factors to draw conclusions like sms_ received example; the data shows that patients who did not show up are more likely to receive an sms.This may seem counter intuitive, but we do not have information on the conditions of when the sms was sent.
* some of the independent variables like gender can not be used singularly to predict whether a patient will show up, combining them with other independent variables may give them some predictive power or effect on the dependent variable.
* having additional data of population of each neighborhood can help in making better assumptions of the neighborhoods and appointments
