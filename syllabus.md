---
layout: page
title: "&#x1F4DC; Syllabus"
nav_order: 2
description: >-
    Course policies and information.
---

{: .warning } 
⚠️ The content on this page is subject to change until this banner is removed.

# Syllabus
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## About &#x1F9D0;

Hi! Welcome to Data 6 Fall 2026! We’re excited to have you on board this semester. This course is specifically designed without any prerequisites or assumed prior knowledge of computer science or statistics. Along the way, you’ll gain practical experience working with data and using Python code to extract useful insights from real-world data sets. Even if this is the last data science class you ever take, we hope you’ll learn useful skills that you can apply to your own major or field of study.

### Course Description
<!--Data 6 is an introduction to computational thinking and quantitative reasoning, designed to prepare students for further coursework in data science, computer science, and statistics. This course emphasizes the use of computation to gain insight about quantitative problems with real data from the social sciences.-->

This foundational Data Science course is an introduction to computational thinking as applied to the fundamentals of quantitative social inquiry. You will learn to apply critical concepts and skills in computer programming to conduct quantitative social science research in various contexts, including economic outcomes, public health, environmental justice, privacy, bioethics, and social networks. Understand the process of using data for quantitative analysis and how to develop a variety of figures, combined with text, to communicate their findings. The focus is on data exploration and identifying patterns relevant to social concepts, rather than inferences and predictions.

This class serves a different purpose than several other classes that may sound similar. Specifically:
* [**Data 4AC**](https://cdss.berkeley.edu/dsus/hce/data-4ac-data-and-justice) (Data and Justice) introduces students to justice within computing and data in American society, effectively fulfilling the [American Cultures](https://undergraduate.catalog.berkeley.edu/earning-your-degree/university-campus-requirements/american-cultures) campus requirement. Both courses focus on introductory data science principles with real-world data, though Data 4AC emphasizes social science tools and theory to analyze case studies, while Data 6 emphasizes computational thinking.
* [**Data 8**](https://www.data8.org/) (Foundations of Data Science) is the first required course for the UC Berkeley Data Science major and minor. While some topics may be similar, Data 6 does not cover nearly as much statistics and inference. Instead, we dive deeper into the mechanics of Python and how to use Python to generate insights from data using real-world data sets. After taking Data 6, you will be more than well-equipped to take (and succeed in) Data 8.
* [**CS 10**](https://cs10.org/sp25/) (The Beauty and Joy of Computing) is a similar class to Data 6 in that it is intended as an introduction to computing that assumes no prior experience with programming. However, CS 10 focuses less on Python and data science, and more on abstract ideas in computer science. It is a fantastic alternative (or complement) to Data 6.
* [**CS 61A**](https://cs61a.org/) (Structure and Interpretation of Computer Programs) and [**Data C88C**](https://cs88-website.github.io/sp25/) (Computational Structures in Data Science) also teach Python, but serve a slightly different purpose than Data 6 — namely, these courses are designed to introduce students to computer science, not to computing *in* data science. They cover the Python language in far greater detail than we will, but they do not cover how to work with real-world data. After taking Data 6, you will be more than well-equipped to adapt to the faster pace of CS 61A and Data C88C.

### Course Materials and Resources

All web platforms are available on our course website: [{{site.url}}{{ site.baseurl }}/]({{site.url}}{{ site.baseurl }}/)

* **Course Website**: The day-to-day happenings of the course (and links to all the platforms below) can be found on our front page. Consult the [front page]({{site.url}}{{ site.baseurl }}/) for a schedule of course topics, assignments, and due dates. Consult the [Calendar]({{site.url}}{{ site.baseurl }}/calendar_dynamic) page for the times/locations for all weekly engagements.
* **Edstem**: This will be our main Q&A platform, where you can ask (and answer) questions and see announcements. The front page has a button to our [course EdStem](https://edstem.org/us/courses/{{ site.ed_course_id }}/discussion).

Ed is a formal, academic space. Posts in this forum must relate to the course and be in alignment with [Berkeley’s Principles of Community](https://diversity.berkeley.edu/principles-community) and the [Berkeley Campus Code of Student Conduct](https://conduct.berkeley.edu/code-of-conduct/). We expect all posts to demonstrate appropriate respect and consideration for others. Please be friendly and thoughtful; our community draws from a wide spectrum of valuable experiences. Posts that violate these standards will be removed.

* **DataHub**: This is where you will complete Python assignments on Jupyter Notebooks, an interactive scientific notebook popular in data science applications and Data courses. Access via [https://datahub.berkeley.edu/](https://datahub.berkeley.edu/) or by clicking coding books on the front page.
* **Gradescope**: This is where you will submit all assignments, including weekly reading assignments. The front page has a button to our [course Gradescope](https://www.gradescope.com/courses/{{ site.gradescope_course_id }}).
* **Google Drive**: Lecture resources are on Google Slides (accompanied by notebooks you can access on DataHub). You will occasionally need to submit surveys via Google Forms.
* **bCourses**: At the moment, there's not much here. We also won't plan much here, so please contact staff via Ed or email.

### Support

You are not alone in this course! The staff and instructors are here to support you as you learn the material. It’s expected that some aspects of the course will take time to master, and the best way to master challenging material is to ask questions. For questions, use [Ed](https://edstem.org/us/courses/{{ site.ed_course_id }}/discussion), not bCourses. We will also hold in-person office hours that offer drop-in help on assignments and course material. Instructor "Tea Hours" are for advising and are also drop-in (welcome!). See our [Calendar]({{site.url}}{{ site.baseurl }}/calendar_dynamic) for office hour times.

We are a much smaller course than many of the Data Science classes you may encounter at Berkeley. Use this fact to your advantage! The instructors, TA, and UCS1 are here to support you, so please lean on your course staff if you need more support in the class or have any questions/concerns.

## Course Components	&#x1F4D2;

### Lecture

* **Lecture**: Lectures are held in-person Mondays - Thursdays in Social Sciences Building 60 and will not be recorded. We will begin at [Berkeley Time](https://www.sfgate.com/bayarea/article/Berkeley-Time-10-minutes-late-university-policy-13182558.php) (10 minutes after the hour), and **attendance is mandatory**. Lectures aim to introduce new ideas and concepts in programming and data science. All lecture resources (slides, code, notes) will be linked on the course website. We recommend skimming the notes beforehand if you can.

Monday lectures will be held from 10AM to 12PM. 

<!-- TODO: Are we keeping quick checks -->
During each lecture, there will be a few points at which we stop and ask you to answer a short question. We call these questions **Quick Checks**. They serve two purposes:
* For us to gauge how well the class understands the material we’re currently covering
* For you to gauge how well you understand the material we’re currently covering

**Quick Checks are graded on completion, not correctness.** It’s not important to get these questions right on your first try – but it’s important to try them. You will be given time in lecture to answer them. These checks are how we measure attendance.

You have **1 lecture drop**, meaning you can miss 1 lecture without penalty, after the first lecture. This drop is not intended to be a “free-pass” to skip a lecture: please reserve them for unexpected personal or family emergencies, sickness, etc. When calculating grades, we will automatically drop the lowest lecture attendance from your grade.

### Lab

Lab notebooks will give you an opportunity to apply the concepts you learn in lecture to real-world data and to practice coding in Python. We will be working on the lab notebooks together during the two lab sections, which will either be held from 9AM to 11AM in Undergraduate Academic Building 313 or 12PM to 2PM in Undergraduate Academic Building 117 depending on which section you are registered to. We aim to finish the bulk of the lab (if not all of it). Labs will be released on Fridays and due the same day at 11:59 pm.

**60% of lab credit will be attendance-based. The remaining 40% of credit will be awarded for submitting the lab to Gradescope by the 11:59 pm deadline with all public test cases passing.** To earn attendance credit, students must attend the entire discussion and lab section unless they have approval from their Graduate Student Instructor (GSI) to arrive late or leave early. Failure to attend the entire section without prior communication will result in losing attendance credit for that week.

You have **1 lab drop** to use in the event of extenuating circumstances that prevent them from completing the assignment. To use a lab drop, you must message your TA at least one hour prior to the start of your lab, informing them that you will not be in attendance. Note that like lecture drops, lab drops are expected to be used only in the case of illness, emergencies, or other circumstances that prevent you from attending.
<!--TODO: Not sure if keeping this: When calculating grades, we will automatically drop your lowest lab score. For specific concerns related to your lab section, contact your TA. -->

### Readings

Readings are designed to complement the lecture content and prepare you for discussion in section. Readings will generally be lecture notes and, occasionally, external readings with a focus on ethical and social issues. Submit the weekly reading assignment on Gradescope for credit. Reading assignments will be released Monday evenings and due **Thursday at 11:59PM**, the evening before discussion section. 
<!--[Update 7/31] You will have **1 reading drop**, meaning your lowest reading assignment will be automatically dropped from your grade.-->

### Discussion
Each Friday, we will have a two hour discussion section led by your [uGSI]({{site.url}}{{ site.baseurl }}/staff) which is **mandatory to attend**.

Discussions across the term will be separated into two "tracks". Social sciences and technical discussions.

In social sciences sections, we will discuss ethical and social issues in computing and data. To prepare for these discussions, you will be asked to complete some short prep work consisting of a few short readings. It is important to come prepared by completing the readings as we hope to have you drive our discussions. We encourage you to ask questions, raise new points, connect to past readings, and make connections to your own experiences. We further encourage no use of technology during these sections so that you can dedicate your attention to the discussion at hand.

Sometimes, discussion topics will include content covering sensitive issues, like racial bias in algorithms or the implications of data-driven policing and sentencing decisions. These issues are important to discuss because they are real-world consequences of data science and algorithms. Part of being a good data scientist is understanding the impact of your work, and working to mitigate the disparate impacts that data science might have on different populations of people. We always welcome feedback on how we approach and talk about these topics as instructors.

Technical sections will focus more on practicing the syntax and concepts that we introduce during lecture. The problems in section are good preparation for similar (and harder) problems you will see on your homework assignments! Section materials will be released Thursdays evenings each week.

### Assignments
You learn data science by **doing** data science, not by just listening to lectures or reading a textbook. As such, homework assignments will be your primary source of learning in this class.

#### Homework Assignments

Homework assignments will consist mainly of programming problems that challenge you to apply the skills you learned in recent lectures to accomplish tasks involving real data. The homeworks use autograder tests that will tell you if you are on the right track. There are additional autograder tests that will not be visible to you that we will use to grade your work, so don’t assume that just because the public autograder tests are passing that your answers are all correct. **Always remember to double check your code!** Most homeworks will also include a few written response problems, where you will have to type your answer in text. These problems will be manually graded by a human on course staff, and often there is no single ‘right’ solution. We are mainly looking for you to show understanding of what you are doing and to explain your reasoning behind certain answers.

Homework assignments will generally be released Mondays and due the following Wednesday at **11:59PM**. Access homework by clicking a homework link on the front page, which will bring you to your own copy of the homework notebook in DataHub, which allows you to work on the homework online. Once you’re done with the homework, you will run the very last cell in the notebook to generate a `.zip` file, which you will then upload to the [course Gradescope](https://www.gradescope.com/courses/{{ site.gradescope_course_id}}) so that we can grade it. We will go over this process in more detail in lecture.

#### Projects

A few assignments will be "projects" where you will analyze real-world datasets. The experience of solving the problems in this project will prepare you for exams (and life in a data scientist role). On each project, you may work with a single partner; your partner must be from the lab you enrolled in. You will generally have a little over a week to complete projects; projects share the same weekly deadlines as homework assignments unless otherwise stated.

Don’t share your code with anybody but your partner. You are welcome to discuss questions with other students but don’t share the answers. If someone (who is not your partner) asks you for the answer, resist! Instead, you might demonstrate how you would solve a similar problem.

The projects can seem long and difficult, but you are not alone! Come to office hours, post on Ed, and talk to your classmates. If you want to ask about the details of your solution to a problem, make a private Ed post and the staff will respond. If you’re ever feeling overwhelmed or don’t know how to make progress, email your TA or tutor for help. You can find contact information for the staff on the course website. We highly recommend starting early.

### Quizzes and Exams
There are 2 in-class quizzes and one final exam. The final exam is required for a passing grade. The below quiz dates are tentative:

* Quiz 1: Monday at 10AM, September 28th, in-class
* Quiz 2: Monday at 10AM, October 19th, in-class
* Final Exam: Friday at 10AM, December 18th, in-class

There will not be alternate exams. All exams will be held in-person. More details about quizzes and exams will be posted ot Ed.

## Policies &#x1F4D1;

### Grading

Here's how we will calculate your final grade:

| **Component** | **Weight** | **Notes** |
| Surveys | 2.5% | 3 course surveys |
| Lecture Attendance| 2.5% | 13 lectures, 1 drop |
| Readings | 7.5% | 13 readings, 1 drop |
| Discussion Attendance | 2.5% | Weekly discussion section|
| Lab | 10% | 13 labs, 1 drop |
| Homework | 20% | 5 homework assignments, 4% each|
| Projects | 20% | - Project 1 (5%) <br/> - Project 2 (5%) <br/> - Final Project (10%) |
| Exams | 35% | - Quiz 1 (5%) <br/> - Quiz 2 (5%) <br/> - Final (20%)|


We will share information later in the semester regarding grade bins for letter grades. Please consult Berkeleytime for historical distributions of grade bins (our bins will most likely resemble those of the Fall 2025 semester)!

Grades for Homeworks, Projects, and Labs will be posted on Gradescope within a timely manner after the assignment’s due date. It is up to you to check the solutions and request a regrade request before the regrade deadline on Gradescope (48 hour regrade window). Any regrade request past the deadline will not be looked at; this is to enforce the same deadline across all students, so again: please do not delay reviewing your work.

### Submitting Assignments

All assignments (homework, labs, and projects) will be submitted on Gradescope. Please refer to [this tutorial](https://drive.google.com/file/d/1JU-p1qYKEFQBRoI6p24tx_-Cj0dySN9h/view) for submitting assignments.

We understand that the submission process is new for many students taking the course. To account for this, we will do our best to accommodate submission-related issues (submitting to the wrong assignment, not saving files correctly, autograder timing out) up until the fourth week of the course. After the fourth week, it is your responsibility to confirm you have submitted your work correctly. We reserve the right to impose penalties for having to resubmit students’ work beyond this point.

### Late Submissions
The deadline for all assignments in this course is 11:59PM PT for programming assignments (lab, homework, project assignments) and reading assignments (Gradescope "quizzes"). Submissions after this time will be accepted for 24 hours and will incur a 20% penalty. Any submissions later than 24 hours after the deadline will not be accepted. 

<!--*Exceptions:* Lab, Homework, and Projects have a 24 hour grace period, meaning you can submit the assignment up to 24 hours late with _no penalty_ to your grade. Lab and Homework submissions will not be accepted after the grace period (24 hours from original deadline). Projects will be accepted up to 24 hours after the grace period (48 hours from original deadline), however any submission after the grace period will incur a 20% penalty.-->

**Extensions**: We understand that life happens and want to provide you with the support you need. We don't want to penalize you because of circumstances that are out of your control. If you have an ongoing situation that prevents you from completing course content, please contact the course instructors and/or TA. This includes assignment extension requests, in which case you must notify us within 24 hours before the deadline. Only request an extension if you have used up your assignment drop. As long as your request is within reason, there's a good chance of it being granted, in which case we will add the extension to your submission on Gradescope. Please note that unless there are extenuating circumstances, we will not approve extensions beyond 48 hours - this is to help you stay on track and prevent assignments from piling up.

### Accommodations

We honor and respect the different learning needs of our students, and are committed to ensuring you have the resources you need to succeed in our class. If you need religious or disability-related accommodations, if you have emergency medical information you wish to share with us, or if you need special arrangements in case the building must be evacuated, please share this information with us as soon as possible.

**DSP**: We will provide appropriate accommodations to all students enrolled in Berkeley’s Disabled Students Program (DSP). To ensure that you receive the appropriate accommodations, have your DSP specialist submit a letter confirming your status and accommodations.

If you’re not enrolled in DSP, or are in the process of being onboarded by DSP, you may still be eligible for accommodations. We also aim to provide fair and appropriate accommodations to any students who, because of extenuating circumstances, may need them. Please reach out to us in this case.

**Religious Observance**: If you require accommodation for religious observance, please contact us at least a week before the deadline in question to make arrangements.

**Privacy**: All accommodations-related materials for this course are kept in a repository separate from the rest of the course materials that is visible only to the instructors and TA.

### Academic Honesty and Learning Collaboratively
This may be the first class you take at UC Berkeley --— we know that taking your first class can be stressful. But the main point of this class (and of data science in general) is to try things out and learn from your mistakes, not necessarily to get everything right on the first try. This class is designed to encourage you to learn through exploration, so we hope you focus on learning skills that you might use later, instead of focusing on getting a good grade.

Data science is a collaborative activity. As such, we encourage you to discuss homework and lab assignments at a high level with other students. With that said, you must write all code and solutions individually in your own words. **Rather than copying someone else's work, ask for help.** You are not alone in this course! We're here to help you succeed, and if you invest the time to learn the materal and complete the assignments, you won't need to copy any answers. If you use code you found online, please cite it in a comment and briefly explain what the code does.

Make a serious attempt at every assignment yourself. If you get stuck, read the textbook and go over the lectures and lab discussion. After that, go ahead and discuss any remaining doubts with others, especially the course staff. That way, you will get the most out of the discussion. It is important to keep in mind the limits of collaboration. As noted above, you and your peers are encouraged to discuss course content and approaches to problem solving. But you cannot share your code or answers with other students. Doing so is considered academic misconduct, and it won’t help your peers either. Sharing answers will set them up for trouble on upcoming assignments and exams.

**You are not permitted to turn in answers or code that you have obtained from any generative AI tools, including but not limited to ChatGPT, Claude, and Gemini.** Not only does such copying count as academic misconduct, but it also circumvents the pedagogical goals of an assignment. You must solve problems with the resources made available in the course. You should never look at or have solutions in your possession from another student or another semester. Late in the semester, we will have an opportunity to learn how to use generative AI tools for coding _constructively_ later in the semester. Until then, please ask us questions about appropriate use and prioritize getting familiar with the code first.

Please read Berkeley’s [Code of Conduct](https://conduct.berkeley.edu/code-of-conduct/) carefully. Penalties for academic misconduct in Data 6 are severe and include reporting to the [Center for Student Conduct](https://conduct.berkeley.edu/). They might also include an F in the course or even dismissal from the university. It’s just not worth it!

## Campus Resources &#x1F3EB;

### Technology Resources
Since all Data 6 material is accessible online, there are no requirements in terms of specific computer hardware. All you need is a laptop with internet and a web browser (Google Chrome or Firefox tend to work best). If you looking to purchase, rent, or borrow a laptop for college, Prof. Lisa Yan put together this [helpful guide](https://docs.google.com/document/d/1avUDkT5yvW_XycvVYP9LevJP791a9CdxuCAzQB1tYfc/edit?usp=sharing).

Here are a few helpful resources when it comes to technology:
* Read this [Berkeley IT website](https://technology.berkeley.edu/wi-fi) to learn how to connect to the campus WiFi network, Eduroam.
* **Device lending options**: The [Student Technology Equity Program](https://studenttech.berkeley.edu/step) provides free laptop loans for students.

### Data Science Student Climate
[Data Science Undergraduate Studies](https://cdss.berkeley.edu/dsus) faculty and staff are committed to creating a community where every person feels [respected, included, and supported](https://data.berkeley.edu/equity-inclusion). We recognize that incidents may happen, sometimes unintentionally, that run counter to this goal. There are many things we can do to try to improve the climate for students, but we need to understand where the challenges lie. If you experience a remark, or disrespectful treatment, or if you feel you are being ignored, excluded or marginalized in a course or program-related activity, please speak up. Consider talking to your instructor, but you are also welcome to contact Executive Director Christina Teller at [cpteller@berkeley.edu](mailto:cpteller@berkeley.edu) or report an incident anonymously through this [online form](https://docs.google.com/forms/d/e/1FAIpQLSfBwaUe7VMQz6VzkYFvf4KYwNSTve9iJlBSQyAmsXoSE0LnWw/viewform).


We are committed to creating a learning environment welcoming of all students that supports a diversity of thoughts, perspectives and experiences and respects your identities and backgrounds (including race, ethnicity, nationality, gender identity, socioeconomic class, sexual orientation, language, religion, ability, and more.) To help accomplish this:

* If your name and/or pronouns differ from those that appear in your official records, please let us know.
* If you feel like your performance in the class is being affected by your experiences outside of class (e.g., family matters, current events), please don’t hesitate to come and talk with us. We want to be resources for you.

#### Be Aware of Your Actions

Sometimes, the little things add up to creating an unwelcoming culture to some students. For example, you and a friend may think you are sharing in a private joke about other races, genders, or cultures, but this can have adverse effects on classmates who overhear it. There is a great deal of research on something called “stereotype threat,” which finds simply reminding someone that they belong to a particular culture or share a particular identity (on whatever dimension) can interfere with their course performance.

Stereotype threat works both ways: you can assume that a student will struggle based on who they appear to be, or you can assume that a student is doing great based on who they appear to be. Both are potentially harmful.

Bear in mind that diversity has many facets, some of which are not visible. Your classmates may have medical conditions (physical or mental), personal situations (financial, family, etc.), or interests that aren’t common to most students in the course. Another aspect of professionalism is avoiding comments that (likely unintentionally) put down colleagues for situations they cannot control. Bragging in open space that an assignment is easy or “crazy,” for example, can send subtle cues that discourage classmates who are dealing with issues that you can’t see. Please take care, so we can create a class in which all students feel supported and respected.

#### Be an Adult

Beyond the slips that many of us make unintentionally are a host of behaviors that the course staff, department, and university do not tolerate. These are generally classified under the term harassment; sexual harassment is a specific form that is governed by federal laws known as Title IX.

UC Berkeley’s [Title IX website](https://ophd.berkeley.edu/) provides many resources for understanding the terms, procedures, and policies around harassment. Make sure you are aware enough of these issues to avoid crossing a line in your interactions with other students. For example, repeatedly asking another student out on a date after they have said no can cross this line.
Your reaction to this topic might be to laugh it off, or to make or think snide remarks about “political correctness” or jokes about consent or other things. You might think people just need to grow a thicker skin or learn to take a joke. This isn’t your decision to make. Research shows the consequences (emotional as well as physical) on people who experience harassment. When your behavior forces another student to focus on something other than their education, you have crossed a line. You have no right to take someone else’s education away from them.

This issue is very important to your instructors. Therefore, if we cannot appeal to your decency and collegiality, let us at least appeal to your self-interest. Do not mess around on this matter. It will not go well for you.


#### Issues with Course Staff

Professionalism and respect for diversity are not just matters between students; they also apply to how the course staff treat the students. The staff of this course will treat you in a way that respects our differences. However, despite our best efforts, we might slip up, hopefully inadvertently. If you are concerned about classroom environment issues created by the staff or overall class dynamic, please feel free to talk to us about it. The instructors and DSUS welcome any comments or concerns regarding conduct of the course and the staff.

### Additional Campus Resources

* [University Health Services](https://uhs.berkeley.edu/)
* [UHS Counseling and Psychological Services](https://uhs.berkeley.edu/caps)
* [UC Berkeley Sexual Violence Services](https://svsh.berkeley.edu/)
* [Campus Academic Accommodations Hub](https://evcp.berkeley.edu/programs-resources/academic-accommodations-hub)
* [ASUC Student Advocate's Office](https://advocate.berkeley.edu/)
* [Basic Needs Center](https://basicneeds.berkeley.edu/)
* [Student Learning Center](https://slc.berkeley.edu/)

---

## Acknowledgments 🙏

Data 6 has been taught by many instructors: Jedi Tsang, Atticus Ginsborg, Edwin Vargas Navarro, James Weichert, Jonathan Ferrari, Will Furtado, Suraj Rampure, Ian Castro, and Isaac Merritt. Data 6 and Data 94 are loosely based on Data C6, taught by Ian Castro in Summer 2020 at UC Berkeley, which in turn was based on Data 8R, taught by Henry Milner in Summer 2017, also at UC Berkeley. These classes were based on [Data 8](https://data8.org/) at UC Berkeley.