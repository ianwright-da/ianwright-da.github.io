---
layout: project
type: project
image: "../img/pacing-tracker/pacing-tracker-header.png"
title: "Classroom Pacing Tracker Using Google Sheets"
date: 2022
published: true
labels:
  - Excel
  - Google Suite
  - Vlookup
  - Pivot Table

summary: "A task management and dashboard system for teachers and students to manage workflow in a self-paced classroom."
---
<figure class="float-end pe-4">
  <img width="500px"  
      src="../img/pacing-tracker/student-checklist.PNG" >
  <figcaption class="figure-caption text-right">Student Checklist</figcaption>
</figure>


The [evidence suggests](https://www.edweek.org/teaching-learning/kids-are-behind-in-math-because-of-covid-19-heres-what-research-says-could-help/2020/12) that students' math skills were especially affected by the pandemic. Addressing this problem is challenging for teachers because these adverse effects tend to be unevenly distributed, with some students emerging from the pandemic nearly unaffected and and others in the same courses several grade leveles behind. I taught math in Chicago Public Schools throughout the pandemic and the following years, and it was clear to me that my students needed a nontraditional approach to best overcome these challenges.


Inspired by the [Modern Classrooms Project](http://wwww.modernclassrooms.org), I implemented a self-paced structure where students progressed at their own pace through elearning content I had created. This quickly became logistically challenging as students progressed at very different rates, and I needed a tracking system for both me and my students to make it easier to navigate classroom workflow. 

The system is built in Google Sheets using advanced formulas to leverage direct integration with Google Classroom and ensure compatibility with the native ChromeOS on school devices. Students use a simple checklist to track learning tasks (pictured above).

As students complete and check off tasks, the tracker spreadsheet automatically imports these updates and updates a whole class view:

<img class='center' width="900px" src="../img/pacing-tracker/pacing-tracker.PNG">

This view includes a list of students by task and gives students immediate feedback about whether they are meeting pacing expectations to be on track for the next deadline. It also makes it readily apparent which students are making progress and which are not by using a javascript add-on to get the time of a student's last completed task. Overall functionality required an elaborate series of imports, look-ups, and pivot tables (a blank copy of the spreadsheet is included below).

Design goals were as follows:
* Provide a low-lift means for students to track their progress
* Provide a clear student-facing whole class tracker to facilitate collaboration between students and teacher intervention
* Use unversal design principles to minimize cognitive lift in navigating the system so that students can focus on learning
* Provide tools for teachers to monitor student progress and give feedback.

<b>[Click Here](https://drive.google.com/drive/folders/1mfJtkdESCexzCsZykBuYFlu7Bjjvs0bF?usp=sharing) to view blank copies of the student-checklist and classroom tracker sheets.</b>
<hr>

