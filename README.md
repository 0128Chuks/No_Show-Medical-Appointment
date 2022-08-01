# No_show Medical Appointment in Brazil 

### Chukwuma Anthony Nwachukwu

## Dataset after cleaning

The cleaned dataset is named no_show_cleaned.csv, it contains several new features that was obtained from feature engineering plus some older ones that was cleaned. The original dataset was obtained from [kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments/download?datasetVersionNumber=5) whereas the one used here was a cleaned version of it.


### Column Description:

- **gender** - Male or Female . Female is the greater proportion, woman takes way more care of they health in comparison to man.

- **appointment_date**  - The day of the actuall appointment, when they have to visit the doctor.

- **schedule_date** - The day someone called or registered the appointment, this is before appointment of course.

- **Age** - How old is the patient.

- **hospital_locations** - Where the appointment takes place.

- **Scholarship** - True of False if they have one or not

- **hypertension** - True or False if they have one or not

- **diabetes** - True or False if they have one or not

- **Alcoholism** - True or False if they have one or not

- **Handcap** - - 1 or more illness with 0= none and 4 meaning max

- **SMS_received** - True or False if they have one or not

- **No-Show** - True or False, if they have one or not.

- **appointment_day**- day of the week the appointment 

- **days_before_visit** - The day difference between schedule and appointment day.

- **day_range** -  A category assigned to days_before_visit based on certain ranges.
 - Late - any days_before_visit below 0
 - Same_day -  - any days_before_visit = 0
 - Short  - any days_before_visit 1-3
 - Week  - any days_before_visit 4-7
 - Fortnight - any days_before_visit 7-14
 - Monthly  - any days_before_visit 14-30
 - Quarterly - any days_before_visit 30-90
 - Semester  - any days_before_visit > 90


I changed all the column names to lowercase and used underscore to seperate athe column names that were made up of more than two words. This was done for easy accessing of the columns when coding.


## Summary and Conclusion

> I noticed that age and gender plays a bigger role to a patient showing up for medical appointments or not, also hospital location also makes up a significant role to patients showing up as well.

> I noticed that patients that have appointments on weekdays tends to show up more than those that schedule theirs on weekends.

> Day_range like *same_day* has more patients showing up for appointments and mostly comprises of pregnant patient that give birth(age=0).



```python

```
