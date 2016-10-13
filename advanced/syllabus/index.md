---
layout: wide
title: Syllabus - Advanced Responsive Web Design
---

## Kent State University CCI Course 40095-003/50095-003

<dl class="detail-listing detail-listing--syllabus group">
  <div class="detail-list__column">
    <dt>Instructor Name:</dt>
    <dd>Christopher Hallahan</dd>
    <dt>Instructor Email:</dt>
    <dd><a href="mailto:challahan@ideabasekent.com">challahan@ideabasekent.com</a></dd>
    <dt>Terms:</dt>
    <dd>Spring 2017</dd>
    <dt>Undergrad:</dt>
    <dd>CCI 40095-003 - 21393</dd>
  </div>
  <div class="detail-list__column">  
    <dt>Grad:</dt>
    <dd>CCI 50095-003 - 21394</dd>
    <dt>Day/Time:</dt>
    <dd>Thursdays, 2:30 p.m. - 5:00 p.m.</dd>
    <dt>Room:</dt>
    <dd><a href="http://www.ideabasekent.com/directions">IdeaBase</a>, Downtown Kent</dd>
  </div>
</dl>

### About This Course

Course description goes here.

#### Topics

Just a few of the topics planned to be covered in the Responsive Web Design course include:



### Prerequisites
Sophomore standing.  This course has no other prerequisites, however you must be proficient in basic web and computer applications.  You will be expected to write HTML, CSS and light JavaScript code (familiarity with these will be helpful, but is not necessary).  You will also be working in vector-based editing tools to help prototype visual designs.  Success in this course will depend on your willingness to try learn new skills and collaborate with others from different backgrounds to solve complex problems.

### Subject to Change Statement
The syllabus and course schedule may be subject to change. Changes will be communicated via email. It is the responsibility of students to check email messages and course announcements to stay current in the course.

### Course Goals

In this course, students will:



### Learning outcomes

Most importantly, by the end of this course, students will be able to:



### Course Textbook and Materials

No required textbooks.

This course will also make use of video tutorials from Lynda.com (available at no charge to students taking this course), as well as free online readings and videos.

### Class Structure


### Preparing for Class
Students are expected to come to class prepared.  This means:

* Familiarization with the required readings or videos.
* Readiness to participate in class discussions and activities.
* Participating in class discussions and hands-on activities.
* Completing assignments on time and submitting them properly to GitHub each week.

### Course Schedule
This course will be divided into four parts.  Readings, lecture notes and information on preparing for class will be posted to the [class website](http://www.rwdkent.com).

Please see the [Detailed Course Schedule](http://www.rwdkent.com/advanced/schedule) for specific dates, times and assignments.



<div class="page-break"></div>

### Assignments
Student learning will be assessed through three types of work: in-class participation, in-class quizzes, short assignments and a multi-stage small group/individual project.

<dl>
  <dt>Graduate Students</dt>
  <dd>Graduate student assignments may include a more challenging component than undergraduate assignments to support advanced mastery of the subject.  When working in collaboration with an undergraduate student, only the graduate student is required to complete this component of the assignment.</dd>
</dl>

There are **100** total possible points for the semester.


<div class="table-float">

<h4>Mini Assignments</h4>

<table>
<thead>
  <th style="text-align:left;">Assignment</th>
  <th style="text-align:left;">Points</th>
</thead>
<tbody>
{% assign items = site.assignments | sort: 'date' %}
{% for item in items %}
	{% if item.type == 'mini' and item.semester == 'fall-2016' %}  
	<tr>
		<td>
			<a href="{{ item.url }}">{{ item.title }}</a>
		</td>
		<td>
			{{ item.points }}
		</td>
	</tr>
	{% endif %}
{% endfor %}
	<tr>
		<td><strong>TOTAL</strong></td>
		<td><strong>45</strong></td>
	</tr>
</tbody>
</table>
</div>

<div class="table-float">
<h4>Semester Project Assignments</h4>
<table>
<thead>
  <th style="text-align:left;">Assignment</th>
  <th style="text-align:left;">Points</th>
</thead>
<tbody>
{% assign items = site.assignments | sort: 'date' %}
{% for item in items %}
	{% if item.type == 'project' and item.semester == 'fall-2016' %}  
	<tr>
		<td>
			<a href="{{ item.url }}">{{ item.title }}</a>
		</td>
		<td>
			{{ item.points }}
		</td>
	</tr>
	{% endif %}
{% endfor %}
	<tr>
		<td><strong>TOTAL</strong></td>
		<td><strong>55</strong></td>
	</tr>
</tbody>
</table>
</div>

### Attendance Policy

We'll be covering many topics during class, as well as working in groups on exercises to help you master web design techniques.  Therefore, attending each of the 15 classes is crucial.  I will allow **two missed classes** for the semester.  All subsequent absences will only be accepted for the following reasons:  sickness (with medical note only), athletic event (with coach's note), religious observation, military responsibility (with documentation) and death in the family (with documentation).  

Students who miss more than two classes without proper documentation will receive a 0 for their class participation grade for the semester.

If you miss class, you are still responsible for contacting the instructor to see what was assigned that day, as well as meeting all assignment deadlines.

Some assignments, such as in-class presentations, testing and quizzes, require attendance in order to receive full credit for the assignment.

### Late Submissions
The assignments deadlines are to help you manage the workload and stay on track with the course. If an assignment will be late, students must contact the instructor and explain. Kent State accepts the following reasons for late assignments: sickness with medical note, athletic event (with coach’s note), religious observation, military responsibility (with documentation), death in the family (with documentation).

My policy for late assignments has 3 rules:

* Late assignments will be accepted so long as you contact the instructor to indicate that it will be late and provide an explanation.
* Late assignments must be submitted within 1 week of the original due date, without penalty, so long as the student meets the first rule. After 1 week the assignment will be marked as 0.
* An additional extension may be possible in exceptional circumstances, with documentation. This requires a face-to-face conversation between the student and the instructor.

### Group Work

This class uses team-based learning for part or all of the semester.  Students must agree to follow the [Group Rules & Expectations](../groups/policies) throughout the course of the project.

### Grading

Final letter grades will be assigned on the basis of the following table.  Graduate student assignments will take into account additional advanced components (described within the assignment), differing from undergraduate assignments.

| Letter       | Percentage  |
| :------------- | :-------------|
| A |  93% or higher |
| A- |  90-92% |
| B+ |  87-89% |
| B |  83-86% |
| B- |  80-82% |
| C |  70-79% |
| D |  60-70% |
| F |  < 60% |


### Hardware & Software

* Although a laptop is not required, if you have a laptop you are encouraged to bring it to class, as it may be helpful for following along in class.  You’ll also be viewing and testing your work on multiple devices, so phones and tablets are encouraged.
* Computers will be provided for in-class work, but you may be asked to share with another student.  Students will also be permitted to work on these computers outside of class, when needed.
* We will be using a variety of free and paid software programs and tools.
* Paid software may only be used on university-owned computers and will be provided at no charge.  If you would like to use paid software on your personal computer, you will need to purchase a license.
* Software programs and tools to be used in the course include: Sketch, Illustrator, Atom, GitHub, web browsers and Google Drive.

<div class="page-break"></div>

### Communicating with the Instructor

My office hours for this semester are:

* Tuesdays: 4:30 - 5:30 p.m.
* By Appointment

#### Email
My email address is [challahan@ideabasekent.com](mailto:challahan@ideabasekent.com).  Here is my email policy:

* I will usually respond within 24 hours during the week (Mon-Fri). Do not expect an immediate response.
* I typically check email in the afternoons or evenings, not in the mornings.
* I may not respond to email on weekends.

### University Policies and Procedures
The following policies and procedures apply to students enrolled at Kent State University. For a complete listing of university policies, please visit the Policy Register page on the Kent State University website.

#### Course enrollment and withdrawal
University policy requires all students to be officially registered in each class they are attending. Students who are not officially registered for a course by published deadlines should not be attending classes and will not receive credit or a grade for the course. Each student must confirm enrollment by checking his/her class schedule (using Student Tools in FlashFast) prior to the deadline indicated. Registration errors must be corrected prior to the deadline.

Every class has its own schedule of deadlines and considerations. To view the add/drop schedule and other important dates for this class, go to Student -> Resources -> Courses and Registration in FlashLine. Choose View or Print Course Schedule and Purchase Textbooks.  To see the deadlines for this course, click on the CRN. The add/drop schedule and important dates may also be found on the Drop or Add a Course link. Click on the green clock next to the course under Registration Deadlines.

#### Incomplete grades
The administrative mark of IN (Incomplete) may be given to students who are unable to complete the work due to extenuating circumstances. To be eligible, undergraduate students must be currently passing and have completed at least 12 weeks of the semester. Graduate students must be currently earning a C or better grade and are unable to complete the required work between the course withdrawal deadline and the end of classes. The time line shall be adjusted appropriate for summer sessions and flexibly scheduled courses.  Appropriate documentation is generally required to support the extenuating circumstance. The student must initiate the request for the Incomplete mark from the instructor, and it is the responsibility of the student to arrange to make up the incomplete work. Incomplete grades must be made up within one semester (not including summer sessions) for undergraduate students and one calendar year for graduate students. Unless the course is completed or an extension is granted, incomplete grades will automatically lapse to the grade designated on the Incomplete Mark Form at the end of one semester for undergraduate students and at the end of one year for graduate students.

#### University use of electronic mail
A university-assigned student email account shall be an official university means of communication with all students at Kent State University. Students are responsible for all information sent to them via their university-assigned email account. If a student chooses to forward information in their university email account, he or she is responsible for all information, including attachments, sent to any other email account. To stay current with university information, students are expected to check their official university email account and other electronic communications on a frequent and consistent basis. Recognizing that some communications may be time-critical, the university recommends that electronic communications be checked minimally twice a week.

#### Plagiarism and academic integrity
Students enrolled in the university, at all its campuses, are to perform their academic work according to standards set by faculty members, departments, schools and colleges of the university; and cheating and plagiarism constitute fraudulent misrepresentation for which no credit can be given and for which appropriate sanctions are warranted and will be applied. For more information: http://www.kent.edu/plagiarism.

#### Students with disabilities
(Revised 6/01/07) University policy 3342-3-01.3 requires that students with disabilities be provided reasonable accommodations to ensure their equal access to course content. If you have a documented disability and require accommodations, please contact the instructor at the beginning of the semester to make arrangements for necessary classroom adjustments. Please note, you must first verify your eligibility for these through Student Accessibility Services (contact 330-672-3391 or send us an e-mail at sas@kent.edu or visit http://www.kent.edu/sas for more information on registration procedures).

#### Student survey of instruction evaluation
It is a standard practice of Kent State University to distribute and administer to the learners a confidential and anonymous questionnaire at the completion of the course. The results will be forwarded to the Instructor only at the completion of the class and the submission of all grades. The Instructor will then incorporate the feedback received in future course offerings and in his continual improvement of the course. Please candidly and honestly describe your opinions of the strengths and weakness you experienced as a learner in the course.

#### Notice of my copyright and intellectual property rights
Any intellectual property displayed or distributed to students during this course (including but not limited to powerpoints, notes, quizzes, examinations) by the professor/lecturer/instructor remains the intellectual property of the professor/lecturer/instructor. This means that the student may not distribute, publish or provide such intellectual property to any other person or entity for any reason, commercial or otherwise, without the express written permission of the professor/lecturer/instructor.

<a href="/advanced" class="button small">Return to Class</a>
