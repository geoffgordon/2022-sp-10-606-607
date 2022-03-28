<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
    max-width: 40em;
}
h1 {
    text-align: center;
}
img {
    margin-left: auto;
    margin-right: auto;
    display: block;
    background: lightgray;
}
.vspace {
    height: 3em;
    width: 0em;
}
.question {
    background: lightblue;
    color: #222;
    padding: .5em;
    border: 0.5px solid black;
}
p {
    margin-top: 1em;
    margin-bottom: 1em;
}
.markdown-body blockquote p {
    margin: 0em;
}
.credit {
    text-align: right;
    font-size: 70%;
    margin-bottom: 0.5em;
}
svg {
    margin: auto;
    display: block;
}
circle {
    fill: steelblue;
}
.menu {
    position: sticky;
    top: 0em;
    left: 0em;
    right: 0em;
    background: lightgray;
    padding: 0.5em;
    text-align: center;
    border: 0px;
    margin: 0px;
    margin-bottom: 1em;
    font-size: 120%;
}
</style>
</head>

[Info](#) &nbsp;&nbsp;
[Support](#support) &nbsp;&nbsp;
[Schedule](#course-schedule) &nbsp;&nbsp;
[Tech](#technology) &nbsp;&nbsp;
[Grading](#grading) &nbsp;&nbsp;
[Integrity](#academic-integrity-policies)
{.menu}

# Mathematical Foundations for ML

# Computational Foundations for ML

UPDATE: ~~For the first two weeks of the semester, classes will be remote via Zoom. To get the Zoom link, please log into Piazza or Canvas (see the [Technology](#technology) section below for links).~~ CMU is returning to in-person classes on 1/31/22. {.question}


## Overview

* Course numbers: 10-606 and 10-607
* Time: MWF 3:05-4:25pm
* Location: online for first two weeks, then GHC 4101 for mini 3, then CUC McKenna for mini 4
* Instructor: [Geoff Gordon](https://www.cs.cmu.edu/~ggordon/)
* TAs: Aditya Paul, Xiaoyu Xu, Aishwarya Jadhav
* Office hours: posted on Piazza
* Textbook: there is no required text for the course, but we'll provide links to required and suggested readings
* Resources: we'll use Piazza for discussion and announcements, Canvas for a gradebook, Zoom for online lectures, and various tools for assignment submission; see the [Technology](#technology) section below. Your first step should be to join Piazza via the link in the Technology section.

## Description

These mini courses provide a place for students to practice the necessary mathematical and computational background for further study in machine learning, particularly for taking 10-601 and 10-701. Topics covered include 
* 10-606: probability (random variables, modeling with continuous and discrete distributions), linear algebra (inner product spaces, linear operators), and multivariate differential calculus (partial derivatives, matrix differentials). 
* 10-607: computational complexity, analysis of algorithms, proof techniques, optimization, dynamic programming, recursion, and data structures. 

The courses assume some background in each of the above, but will review and give practice in each. (They do not provide from-scratch coverage of all of the above, which would be impossible in the available time.) Some coding will be required: the courses will provide practice with translating the above mathematical and computational concepts into concrete programs.

Most students take both mini courses, but this is not required. 10-606 is not a prerequisite of 10-607.

## Prerequisites

For both minis, we'll assume you know Calculus I and basic linear algebra, including matrix multiplication and solving systems of linear equations. We'll assume that you've worked with probabilities, including conditional probabilities and Bayes rule. We'll assume some programming experience, specifically experience in Python or enough experience to learn Python quickly, as assignments will be in Python.

For 10-607: 10-606 is recommended.

For the above topics, we intend to give complete definitions and/or resources to learn from, but often we will go over them quickly: we expect that most people will know a lot of the definitions, and will be willing to work outside of class to understand the ones they don't know. So, for each topic that you're less familiar with, you should expect to do some extra work; if you're unfamiliar with several of them, that will make it hard to keep up.

It is your responsibility to understand and follow these pre-requisites! Even if CMU’s registration system does not prevent you from registering for this course, it is still your responsibility to make sure you have all of these prerequisites before you register.

## Support
Take care of yourself. Do your best to maintain a healthy lifestyle this semester by eating well, exercising, avoiding drugs and alcohol, getting enough sleep, and taking some time to relax. This will help you achieve your goals and cope with stress.

You may find CMU's [Student Academic Success Center](https://www.cmu.edu/student-success/) helpful as well in achieving your goals: they offer free coaching, workshops, and other support on learning, communication, and scholarship.

If you have a disability and require accommodations, please contact Catherine Getchell, Director of Disability Resources, 412-268-6121, getchell@cmu.edu. If you have an accommodations letter from the Disability Resources office, I encourage you to discuss your accommodations and needs with me as early in the semester as possible. I will work with you to ensure that accommodations are provided as appropriate.

All of us benefit from support during times of struggle. You are not alone. There are many helpful resources available on campus and an important part of the college experience is learning how to ask for help. Asking for support sooner rather than later is often helpful.

If you or anyone you know experiences any academic stress, difficult life events, or feelings like anxiety or depression, we strongly encourage you to seek support. Consider reaching out to a friend, faculty or family member you trust for help getting connected to the support that can help. And, Counseling and Psychological Services (CaPS) is here to help: call 412-268-2922 and visit their website at http://www.cmu.edu/counseling/. 

If you or someone you know is feeling suicidal or in danger of self-harm, call someone immediately, day or night:
* CaPS: 412-268-2922
* Re:solve Crisis Network: 888-796-8226

If the situation is life threatening, call the police:
* On campus: CMU Police: 412-268-2323
* Off campus: 911.

If you have questions about any of the above, or about any of your coursework, please let the instructors know.

### Diversity

**We must treat every individual with respect. Each of us is responsible for creating a safer, more inclusive environment.**

We are diverse in many ways, and this diversity is fundamental to building and maintaining an equitable and inclusive campus community. Diversity can refer to multiple ways that we identify ourselves, including but not limited to race, color, national origin, language, sex, disability, age, sexual orientation, gender identity, religion, creed, ancestry, belief, veteran status, or genetic information. Each of these diverse identities, along with many others not mentioned here, shape the perspectives our students, faculty, and staff bring to our campus. We, at CMU, will work to promote diversity, equity and inclusion not only because diversity fuels excellence and innovation, but because we want to pursue justice. We acknowledge our imperfections while we also fully commit to the work, inside and outside of our classrooms, of building and sustaining a campus community that increasingly embraces these core values.


Unfortunately, incidents of bias or discrimination do occur, whether intentional or unintentional. They contribute to creating an unwelcoming environment for individuals and groups at the university. Therefore, the university encourages anyone who experiences or observes unfair or hostile treatment on the basis of identity to speak out for justice and support, within the moment of the incident or after the incident has passed. Anyone can share these experiences using the following resources:

* Center for Student Diversity and Inclusion: csdi@andrew.cmu.edu, (412) 268-2150
* Report-It online anonymous reporting platform: [reportit.net](http://reportit.net), username: tartans, password: plaid

## Course schedule

Tentative schedule, subject to change. Typically two days per week will be lectures, and one will be some other activity like a lab or quiz; see below for details.


### Mini 4 (10-607):

| Day | Date | Unit | Lecture | Info |
-|-|-|-|-
M | 3/14 | Overview, optimization | Gradient descent ([notes](gradient.pdf), [slides](01-intro.pdf)) | see 10-606 notes on calculus from 2/7 &ff
W | 3/16 | Optimization | GD, SGD ([slides](02-gradient.pdf)) | see Boyd & Vandenberghe sec 9.3; [Mitliagkas notes](http://mitliagkas.github.io/ift6085-2019/ift-6085-lecture-5-notes.pdf)
F | 3/18 | . | Lab 0: Python | optional
M | 3/21 | Logic | Propositional logic ([notes](proplogic.pdf), [slides](03-logic.pdf)) | Lab 0 due 
W | 3/23 | Logic | Predicate logic ([notes](predlogic.pdf), [slides](04-logic.pdf)) | .
F | 3/25 | . | Lab 1: optimization | .
M | 3/28 | Logic | Quantifiers, induction | HW1 out, Lab 1 due
W | 3/30 | Logic | Proof examples | .
F | 4/1 | . | Lab 2: logic | .
M | 4/4 | Complexity | Analyzing complexity | Lab 2 due 
W | 4/6 | . | Overflow/review period | HW1 due
F | 4/8 | . | no class, Carnival | .
M | 4/11 | . | Quiz I (in class) | .

(more to come)

{.vspace}

### Mini 3 (10-606):

| Day | Date | Unit | Lecture | Info |
-|-|-|-|-
W | 1/19 | . | Overview; start on data types ([notes](datatypes.pdf), [slides](01-intro-datatypes-inked.pdf)) | .
F | 1/21 | . | Lab 0: Python | optional
M | 1/24 | Data types | Sets; functions ([slides](02-datatypes-inked.pdf)) | .
W | 1/26 | Linear algebra | Vectors, matrices ([notes](linear-algebra.pdf), [slides](03-vector-spaces-inked.pdf)) | suggested reference [Strang](https://math.mit.edu/~gs/linearalgebra/); another suggestion is Horn & Johnson, *Matrix Analysis*
F | 1/28 | . | Lab 1: data types | HW1 out
M | 1/31 | Linear algebra | Linear systems ([slides](04-linear-systems-inked.pdf)) | Lab 1 due
W | 2/2 | Linear algebra | Linear systems and regression ([notes](linear-algebra-2.pdf), [slides](05-linear-systems-inked.pdf)) | .
F | 2/4 | . | Lab 2: linear algebra | .
M | 2/7 | Matrix calculus | Derivatives and differentials ([notes](calc-review.pdf), [notes2](function-space.pdf), [slides](06-algebra-calculus.pdf)) | suggested reference [Matrix Cookbook](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf); Lab 2 due
W | 2/9 | . | Overflow and review period ([notes](matrix-differential.pdf), [slides](07-review-and-differentials.pdf)) | HW1 due
F | 2/11 | . | Quiz 1 (in class) | .
M | 2/14 | Matrix calculus | Calculating differentials ([slides](08-matrix-differentials.pdf)) | suggested references [Magnus & Neudecker](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119541219), [Minka's notes](https://tminka.github.io/papers/matrix/); <br> HW2 out
W | 2/16 | Matrix calculus | Lagrange multipliers, nonlinear systems ([notes](nonlinear.pdf), [slides](09-working-with-differentials.pdf)) | .
F | 2/18 | Matrix calculus | Nonlinear systems and Newton's method ([slides](10-nonlinear.pdf)) | .
M | 2/21 | . | Lab 3: calculus | .
W | 2/23 | Probability | Random variables and distributions ([notes](probability.pdf), [notes2](random-variable.pdf), [slides](11-probability.pdf)) | Lab 3 due
F | 2/25 | Probability | Mean and variance; Bayes rule ([notes](mean-variance.pdf), [notes2](evidence.pdf), [slides](12-rand-var.pdf)) | .
M | 2/28 | . | Lab 4: probability | HW2 Q1, Q2 due
W | 3/2 | . | Overflow and review period ([slides](13-evidence.pdf)) | Lab 4 due, HW2 Q3 due
F | 3/4 | . | Quiz 2 (in exam room) | .


## Technology

Whether in person or remote, you will need a device during class. For most in-person classes a phone should suffice. For some activities you'll need a bigger screen and a keyboard; this includes all labs, and we'll warn about other such activities in advance. You will need a modern browser on your device (a recent version of Chrome, Firefox, Safari, or Edge). Please use your devices only to engage with the class material.

We'll use [Piazza](https://piazza.com/cmu/spring2022/1060610607) for class-related discussion. Please post to Piazza instead of emailing the professor or TAs: you'll likely get an answer faster, and other students will be able to benefit as well. (If necessary, you can post privately, so that only the professor and TAs can see your question.)

You can see your grades for the course so far in [Canvas](https://canvas.cmu.edu/courses/27578). For assignments submitted through other tools (see below) it may take a little while before your submission and grade appear in Canvas.

We'll use [Gradescope](https://www.gradescope.com) for submission of written assignments. Registered students should launch Gradescope via Canvas (there's a tab for this on the left-hand navigation menu in Canvas); this lets us link your Canvas and Gradescope accounts.

You will need to scan papers for submission. For legibility, simply taking a photo won't work: instead you need an app that rectifies, crops, and adjusts contrast. There are many available, some of which are free and high quality, including Scannable, Adobe Scan, and Office Lens. The Wirecutter has some [reviews](https://www.nytimes.com/wirecutter/reviews/best-mobile-scanning-apps/).

All required code submissions will be in Python. You may want a Python installation locally on your device, but submissions will be online via browser-based tools (see below). If you use a local installation, be careful of version mismatches, package availability, etc.; the behavior of your code in our system is what you'll be graded on, and TAs may not be able to help diagnose version-related differences.

For most code submissions we plan to use [repl.it](https://repl.it/). This is a web-based tool that lets you edit, run code, check it against our submission criteria, and submit. Please follow the instructions given on Piazza and Canvas to let us know your repl.it account name, so that we can give credit.

Another useful resource is [Google Colab](https://colab.research.google.com), which lets you run Python code in your browser via a notebook interface. They have a free plan (and are happy to charge you for higher resource limits). We don't plan to use Colab for any official submissions, but it can be a great way to try stuff out.

## Grading

For each mini, grading divides as follows:
* Labs (do these at least mostly during the corresponding class period, finish and submit by the beginning of the next class period): 4 labs, total 40% of grade
* Participation (unannounced small questions during class, grading based on completion rather than correctness): total 10% of grade
* Homework assignments: 2 HWs, total 30% of grade. 
* Quizzes (in class or during exam period): 2 quizzes, total 20% of grade. All quizzes are cumulative, i.e., cover everything in the mini so far.

All of these assignments may have both programming and written parts, and may emphasize things like implementation of specific algorithms, design of end-to-end systems, core concepts, derivations, or real-world applications.

See below for our late policies. If not otherwise covered by a late policy, and if late submission is allowed, you'll lose 25% of the credit on an assignment for each day or fraction of a day past the deadline.

You are expected to participate synchronously in class. Missing a small number of classes for good reasons is OK, and you don't need prior permission.

You are required to attend the labs (except Lab 0, which is optional). If you have to miss a lab, please contact us ahead of time; you'll still need to complete the lab separately and submit by the deadline.

You are required to attend the quizzes. The last quiz in each mini will be during the final exam period scheduled by the registrar, which may be at a different time of day than the class itself.

For regrade requests: if you think there may be an error in your grade, please use the same tool that you originally submitted with to request a regrade (e.g., Gradescope for written submissions), or contact us privately through Piazza if the tool doesn't support regrades. Please include details of the suspected error. We'll look at the assignment again, and your grade may either increase or decrease. In general you will need to submit regrade requests within 72 hours of when we return a graded assignment (independent of any deadline listed in any specific tool), but we might announce a different deadline for individual assignments.

### Audit and Pass/Fail

We are happy to allow auditing if there is space in the course. You will need to register for the course and then have the instructor fill out an audit form. Check with the registrar for applicable deadlines. In order to receive an audit pass, auditors must complete 75% of the participation exercises per mini, and must achieve a score of 75% or more on at least two labs per mini. (For both of the above, any optional assignments do not count in the total.) Auditors are also welcome to submit homeworks and quizzes for grading.

We are also happy for you to take the course as Pass/Fail. Instructor permission is not required. What grade is the cutoff for Pass will depend on your program or department. Be sure to check with your program or department as to whether you can count a Pass/Fail course toward your degree requirements.


### Late policy

We have several built-in ways to give flexibility in due dates for students who need it. These policies are intended for situations that are impossible to plan for, such as illness. For plannable conflicts such as conference deadlines, trips, and assignments from other classes, you should submit early instead of late. (We do recognize though that multiple plannable conflicts can combine to create an unplannable conflict.)

The late policies are separate from any disability accommodations. If you have a disability and require accommodations, please see the [Support](#support) section above.

For health-related problems that require additional flexibility beyond what we've built in, please contact your [student affairs college liaison](https://www.cmu.edu/student-affairs/resources/index.html#liaisons). The liaison will help preserve your privacy and ensure that we can provide appropriate accommodations.

If you need additional flexibility that's not covered by the built-in policies, health, or disability accommodations, please contact us directly.

Here are the policies for each assignment type:

* Participation: it's impossible to submit these late, since the point of these exercises is in-class interaction. Instead, for flexibility in case of illness etc., we'll give full participation credit even if you miss up to 10% of submissions. 
* Labs and homeworks: you will have 4 late days to use over the course of the mini. You may use at most two late days on each assignment. One late day allows you to delay the deadline (without penalty) by up to 24 hours; there are no fractional late days. Late days are only for labs and homeworks.
* Quizzes: we expect you to reschedule any outside commitments in order to attend quizzes. But we recognize that in some cases there may be an immovable or unplannable conflict. In these cases we may be able to arrange an alternate time. The alternate time may be earlier or later than the main class's time, at our sole discretion, so plan ahead to give as much notice as possible to allow scheduling.


### Grading cutoffs

We plan to use the following cutoffs:

Score | Grade
-|-
≥ 90% | A
≥ 80% | B
≥ 70% | C
≥ 60% | D
lower | R

Some programs use +/- grades as well as full letter grades. If your program is one of these, the cutoffs are at intervals of 3 and 7 percentage points within each letter grade. So, within the A grade, cutoffs are

Score | Grade
-|-
≥ 97% | A+
≥ 93% | A
≥ 90% | A-

and similarly for B, C, D.

We may be more generous than the above cutoffs, but we will not be less generous.

## Academic Integrity Policies
Read this carefully!
(Adapted from Roni Rosenfeld’s 10-601 Spring 2016 Course Policies.)

### Collaboration among Students
The purpose of student collaboration is to facilitate learning, not to circumvent it. Studying the material in groups is strongly encouraged. It is also allowed to seek help from other students in understanding the material needed to solve a particular homework problem, provided no written notes (including code) are shared, or are taken at that time, and provided learning is facilitated, not circumvented. The actual solution must be done by each student alone.

The presence or absence of any form of help or collaboration, whether given or received, must be explicitly stated and disclosed in full by all involved. Specifically, each assignment solution must include answering the following questions:

Did you receive any help whatsoever from anyone in solving this assignment? Yes / No.

If you answered ‘yes’, give full details: ____________
(e.g. “Jane Doe explained to me what is asked in Question 3.4”)

Did you give any help whatsoever to anyone in solving this assignment? Yes / No.

If you answered ‘yes’, give full details: _____________
(e.g. “I pointed Joe Smith to section 2.3 since he didn’t know how to proceed with Question 2”)

Did you find or come across code that implements any part of this assignment ? Yes / No. (See below policy on “found code”)

If you answered ‘yes’, give full details: _____________
(book & page, URL & location within the page, etc.).

If you gave help after turning in your own assignment and/or after answering the questions above, you must update your answers before the assignment’s deadline, if necessary by emailing the course staff.

Collaboration without full disclosure will be handled severely, in compliance with CMU’s Policy on Academic Integrity.

### Previously Used Assignments
Some of the homework assignments used in this class may have been used in prior versions of this class, or in classes at other institutions, or elsewhere. Solutions to them may be, or may have been, available online, or from other people or sources. It is explicitly forbidden to use any such sources, or to consult people who have solved these problems before. It is explicitly forbidden to search for these problems or their solutions on the internet. You must solve the homework assignments completely on your own. We will be actively monitoring your compliance. Collaboration with other students who are currently taking the class is allowed, but only under the conditions stated above.

### Policy Regarding “Found Code”:
You are encouraged to read books and other instructional materials, both online and offline, to help you understand the concepts and algorithms taught in class. These materials may contain example code or pseudo code, which may help you better understand an algorithm or an implementation detail. However, when you implement your own solution to an assignment, you must put all materials aside, and write your code completely on your own, starting from scratch. Specifically, you may not use any code you found or came across. If you find or come across code that implements any part of your assignment, you must disclose this fact in your collaboration statement.

### Duty to Protect One’s Work
Students are responsible for pro-actively protecting their work from copying and misuse by other students. If a student’s work is copied by another student, the original author is also considered to be at fault and in gross violation of the course policies. It does not matter whether the author allowed the work to be copied or was merely negligent in preventing it from being copied. When overlapping work is submitted by different students, both students will be punished.

To protect future students, do not post your solutions publicly, neither during the course nor afterwards.

### Penalties for Violations of Course Policies
All violations (even the first one) of course policies will always be reported to the university authorities (your Department Head, Associate Dean, Dean of Student Affairs, etc.) as an official Academic Integrity Violation and will carry severe penalties.

The penalty for the first violation is a one-and-a-half letter grade reduction. For example, if your final letter grade for the course was to be an A-, it would become a C+.

The penalty for the second violation is failure in the course, and can even lead to dismissal from the university.

## Previous versions

Here are some websites from previous versions of the course. Each one has some useful slides, lecture notes, and problem examples.

* 10-600, Geoff Gordon, [Fall 2016](https://piazza.com/class/irw2quha2lr1td?cid=6) (this was the original course number for 10-606 and 10-607)
* 10-606, Geoff Gordon, [Fall 2017](https://piazza.com/class/j1z1bzwb6tb7cd?cid=8)
* 10-607, Geoff Gordon, [Fall 2017](https://piazza.com/class/j1z1bzwb6tb7cd?cid=397)
* 10-606 and 10-607, Matt Gormley, [Fall 2018](https://www.cs.cmu.edu/~mgormley/courses/606-607-f18/index.html)
* 10-606 and 10-607, Leila Wehbe, [Summer 2020](https://www.cs.cmu.edu/~lwehbe/10606607_M20/#description)
* 10-606, Pat Virtue, [Fall 2021](https://www.cs.cmu.edu/~10606/#overview)
* 10-607, Pat Virtue, [Fall 2021](https://www.cs.cmu.edu/~10607/#overview)

## Note to people outside CMU
Please feel free to reuse any of these course materials that you find of use in your own courses. We ask that you retain any copyright notices, and include written notice indicating the source of any materials you use.
