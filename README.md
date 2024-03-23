# Investigate a dataset for No-Show appointments

## About

This project aims to investigate why patients in Brazil not showing up for their appointment.

## Data source

The data used to conduct the investigation can be found at [kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

Data table contain the following:

01 - PatientId:

* Identification of a patient.

02 - AppointmentID:

* Identification of each appointment.

03 - Gender

* Male or Female.

04 - AppointmentDay

* The day of the actuall appointment, when they have to visit the doctor.

05 - ScheduledDay

* The day someone called or registered the appointment, this is before appointment of course.

06 - Age

* How old is the patient.

07 - Neighbourhood

* Where the appointment takes place.

08 - Scholarship

* True of False . Observation, this is a broad topic, consider reading this article [Bolsa Família](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia)

09 - Hipertension

* True or False

10 - Diabetes

* True or False

11- Alcoholism

* True or False

12 - Handcap

* True or False

13 - SMS_received

* Messages sent to the patient.

14 - No-show

* Yes or No.

## Data Anayalsis Process

* Data Wrangling (Collect, Clean)
* Exploratory Data Analysis (EDA)

## Create a Conda virtual environment

```bash
#!/bin/bash
conda create --name investigate_a_dataset python=3.8

```

## Activate the virtual environment

```bash
#!/bin/bash
conda activate investigate_a_dataset
```

## Clone the repository

In the virtual environment created in the previous step, type the following commands

```bash
#!/bin/bash
git clone https://gitlab.com/fmsaibi/investigate-a-dataset-no-show-appointments.git
cd investigate-a-dataset-no-show-appointments
```

## Install dependencies

In the virtual environment created in the previous step, type the following commands

```bash
#!/bin/bash
conda install --file requirements.txt
```

## Run the application

To run Jupyter Notebook server and access the file, run the following command

```bash
#!/bin/bash
jupyter notebook
````
