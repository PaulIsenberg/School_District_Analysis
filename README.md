# School_District_Analysis
Module 4 coursework Python and Jupyter
## CHALLENGE
This challenge assignment had us modify the PyCitySchools statistical analysis to account for removing suspect test scores from one school in the district. Replacing the math and reading scores for the Thomas High School Ninth Grade class was necessitated by test score irregularities.  As such, those scores are omitted from the attached analysis, but the students were not.  Removing the scores had some noticable impact on the statistics for school and district averages.  Some of those are highlighted below.

##
The Thomas High School summary showed only a slight deterioration in the Average Math Score, from 83.42 to 83.35 because the 9th grade average math (83.59) had been slightly above the school average.  Reading actually increased slightly from 83.85 to 83.89 because the 9th grade average reading (83.73) had been below the school average.  Passing percentages are adversely affected because each 9th grade student is still counted in the district totals but no longer contributing and passing grades.  Thomas High school passing percentage (scores above 70%) fell from 93% to 67% for math, and 97% to 70% for reading, with the overal passing percentage for the school dropping from 91% to 65%.

Thomas High School is one of our smaller schools at only 1,635 students (436 in 9th grade vs. 11,408 9th graders district wide).  The district has 39,168 students.  Impact of this event to our district overall numbers is negligible.  Average math score dropped from 79 to 78.9 and average reading score remains at 81.9 with rounding.  Math passing percentage (based on a passing score of 70) dropped from 75 to 74, while reading passing percentage dropped from 86 to 85.  Overall passing percentage dropped from 65 to 64.  Again, the relative small quantity mitigated the drop in district-wide numbers.

## 
Prior to the suspect scores being removed Thomas had the 2nd highest overall passing rate (91%).  Removing the 461 scores for 9th grade dropped Thomas to 8th overall (65%), out of 15 schools in the district.

Charter schools make up a small minority in our district.  As such, the Thomas 9th grade scandal had a compounded impact on district-wide charter school scores.  While both the average math and average reading scores remain uncanged the percent passing dropped noticeably.  Math dropped from 94 to 90.  Reading dropped from 97 to 93.  Overall dropped from 90 to 87.

Similarly the medium school bin was likewise impacted with percentage passing math, reading, and overall falling from 94 to 88, 97 to 91, and 91 to 85, respectively.  Again, because the 9th grade scores were relatively close to the mean the average math and average reading scores are minimally impacted, with no statistically significant change in their values.

Thomas High School spends $638 per student.  Within the medium-high expenditure bin the scandal impact again had no measurable impact to average scores, but the removal of a number of passing grades resulted in percentage passing math, reading, and overall falling from 73 to 67, 84 to 77, and 63 to 56, respectively.
