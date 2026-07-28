# Smart Trainer Calendar Power BI Report

## Project Overview

This project is an interactive Power BI report designed to support trainer scheduling, availability tracking and workforce planning.

The report converts daily trainer calendar data into a structured planning solution where users can monitor trainer availability, confirmed engagements, tentative bookings, preparation work, internal work, leave and weekly offs in one place.

## Objective

The objective of this project is to create a clear and practical scheduling report that helps in understanding:

* Which trainers are available for assignment
* Which trainers are already engaged
* Which dates are reserved or tentative
* Which trainers are on leave or weekly off
* How trainer workload and utilisation are distributed
* How scheduling decisions can be made faster and more effectively

## Tools Used

* Power BI
* DAX
* Power Query
* Data Modelling
* Calendar Visual
* Slicers and Interactive Filters
* Excel

## Report Pages

The Power BI report includes four main pages:

1. Trainer Workforce Overview
2. Trainer Calendar
3. Trainer 360 Profile
4. Schedule Control Centre

## Key Features

### 1. Trainer Workforce Overview

The overview page provides a high-level summary of trainer workforce status.

It includes:

* Total trainers
* Engaged days
* Available days
* Leave days
* Trainer utilisation percentage
* Monthly workforce status
* Overall schedule distribution
* Specialisation-wise workload and utilisation
* Trainer profile summary

### 2. Trainer Calendar

The Trainer Calendar page provides a monthly view of trainer schedules.

It tracks different trainer statuses such as:

* Available
* Engaged
* Reserved
* Preparation
* Internal Work
* On Leave
* Weekly Off

This page helps users quickly identify whether a trainer is available, occupied, reserved or blocked on a specific date.

### 3. Trainer 360 Profile

The Trainer 360 page provides a detailed profile view of a selected trainer.

It includes:

* Trainer name
* Specialisation
* Base city
* Experience
* Rating
* Contact details
* Engaged days
* Available days
* Leave days
* Total engagements
* Trainer utilisation percentage
* Monthly workload chart
* Engagement type mix

### 4. Schedule Control Centre

The Schedule Control Centre provides a detailed operational view of trainer schedules.

It includes:

* Calendar date
* Day name
* Calendar status
* Booking status
* Client organisation
* Training programme
* Engagement type
* Project status
* Delivery mode
* Venue city

This page helps review confirmed, tentative, open and blocked schedules in a structured format.

## Key Measures

The report uses DAX measures for dynamic and responsive analysis.

Key measures include:

* Total Trainers
* Engaged Days
* Available Days
* Leave Days
* Internal Work Days
* Total Engagements
* Capacity Days
* Trainer Utilisation %

## Trainer Utilisation Logic

Trainer utilisation is calculated by comparing engaged days with working capacity days.

Working capacity excludes non-working days such as weekly offs and leave.

This helps show how much of a trainer’s workable capacity is actually used for confirmed engagements.

## Data Model

The report is built using a simple data model with fact and dimension tables.

Main tables used:

* Fact_TrainerCalendar
* Dim_Date
* Dim_Trainer

Relationships:

* Dim_Date is connected with Fact_TrainerCalendar using Calendar Date
* Dim_Trainer is connected with Fact_TrainerCalendar using Trainer ID

This model allows the report to respond correctly to slicers, filters and date selections.

## Screenshots

### Trainer Workforce Overview

![Trainer Workforce Overview](Trainer%20Workforce%20Overview.PNG)

### Trainer Calendar

![Trainer Calendar](Trainers%20calender.PNG)

### Trainer 360 Profile

![Trainer 360 Profile](Trainers%20360%20performance%20profile.PNG)

### Schedule Control Centre

![Schedule Control Centre](Trainer%20schedule%20control.PNG)

## Files Included

* `Trainers calendar diviya.pbix` — Power BI report file
* `Trainer calendar Power bi.xlsx` — Excel data file
* `Trainer Workforce Overview.PNG` — Overview page screenshot
* `Trainers calender.PNG` — Trainer Calendar page screenshot
* `Trainers 360 performance profile.PNG` — Trainer 360 page screenshot
* `Trainer schedule control.PNG` — Schedule Control page screenshot
* `README.md` — Project documentation

## Repository Structure

```text
Smart-Trainer-Calendar-PowerBI/
│
├── README.md
├── Trainers calendar diviya.pbix
├── Trainer calendar Power bi.xlsx
├── Trainer Workforce Overview.PNG
├── Trainers calender.PNG
├── Trainers 360 performance profile.PNG
└── Trainer schedule control.PNG
```

## Learning Outcomes

Through this project, I improved my understanding of:

* Power BI report design
* Data modelling
* DAX measures
* Date table usage
* Calendar-based reporting
* Slicer interactions
* Workforce planning analysis
* Schedule control logic
* Business-focused data storytelling

## Conclusion

This project helped me understand how Power BI can be used not only for reporting, but also for practical workforce planning and schedule management.

The report supports faster, clearer and more informed decision-making by bringing trainer availability, workload, engagement status and schedule control into one interactive solution.

## Note

This repository uses sample or dummy data for portfolio demonstration purposes. Any confidential, internal or sensitive information has been removed.
