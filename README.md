OMR Computer Training Analysis 2026

A data analysis and Power BI dashboard project on computer training institutes along the OMR (Old Mahabalipuram Road), Chennai. It covers institutes from Perungudi to Kelambakkam and compares them on courses, trainers, ratings, placements, enquiries and social media presence.

Project Files
File	Description
OMR_Plan.docx	Project plan: sheet structure, columns and purpose of each table
OMR_Project_Power_BI_Dashboard_Design.docx	Dashboard design: pages, KPI cards, charts and slicers
OMR_Institudes_Final_Data.xlsx	Final dataset (10+ sheets)
omr_institutes.pbix	Power BI report (open with Power BI Desktop)
Dataset Overview

The Excel workbook is organised like a small relational database:

Sheet	Contents
Area	OMR areas and zones (North / Central / South OMR)
Institude	Institute details: address, phone, website, established year, Google rating, review count
Course_Category	Course categories
Course	Courses offered by each institute, with category and ranking
Institute_course	Course-to-category master list
Trainer	Trainer name, subject, qualification, experience, employment type, certification
Promotion	Website, Instagram link, follower count, date of last post
Review	Rating, review count, platform
Placement	Placement support, interview and resume support, placement percentage, companies
Enquiry	Enquiry date, source, student type, status

Coverage: about 68 institutes and 360+ course records across 9 OMR areas.

Dashboard Pages (Power BI)
Executive Overview: total institutes, courses, trainers, enquiries, average rating, placement support %
Institute Analysis: institutes by area and zone, ratings, review counts
Course Analysis: courses by category, courses per institute, fees and duration
Trainer Analysis: trainers by subject, qualification, experience and employment type
Placement and Promotion: placement support and social media reach
Enquiry Analysis: enquiry sources, student types and status

See OMR_Project_Power_BI_Dashboard_Design.docx for the full layout.

How to Use
Download or clone this repository.
Open omr_institutes.pbix in Power BI Desktop.
If prompted, point the data source to OMR_Institudes_Final_Data.xlsx (Transform data, then Data source settings).
Refresh the data.
Tools Used
Microsoft Excel (data collection and cleaning)
Power BI Desktop (data model, DAX, dashboards)
Notes
Ratings and review counts come from public listings such as Google, so they may change over time.
The sheet Trainer_Details_Dammy is sample or placeholder data.
