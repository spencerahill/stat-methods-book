# Syllabus

## EAS 42000/A4200: Statistical Methods in Earth and Atmospheric Sciences
Note that, although the undergraduate (42000) and Master's (A4200) sections of this course have different names ("Statistical Methods" and "Quantitative Data Analysis" respectively), the two are taught together and other than the title are completely identical.  For brevity I'll refer to both just as "Statistical Methods in Earth and Atmospheric Sciences."

## Course Information
- **Class Times**: Mondays and Wednesdays, 2:00-3:15pm; full schedule [here](./schedule).
- **Location**: Marshak 1128.  Be advised, I have no control over the thermostat, and depending on the day it can be very cold, very warm or in between!  Plan accordingly.
- **Course Website**: [https://spencerahill.github.io/stat-methods-course](https://spencerahill.github.io/stat-methods-course)
- **Instructor**: [Spencer Hill](https://www.ccny.cuny.edu/profiles/spencer-hill), Assistant Professor, CCNY Dept. of Earth and Atmospheric Sciences
- **Email**: [shill1@ccny.cuny.edu](mailto:shill1@ccny.cuny.edu)
- **Office Hours**: Tuesdays, 1:30 to 2:30pm, and by appointment, Marshak 733.

## Course Description
This course aims to provide you with a comprehensive understanding of statistical methods and other tools for quantitative data analysis in the Earth and Atmospheric Sciences.  We will explore topics including descriptive statistics, probability, and time series analysis, among others.  We will provide the necessary theoretical foundations for each technique introduced, but the bigger emphasis is on actually implementing and using them: by semester's end, you should be equipped with a functioning "toolbox" of statistical/quantitative tools that you both understand conceptually and can actually apply to problems you face in your research or other coursework. 

## Grading

:::{warning}
Your grade will be determined by your performance in this class, and nothing else.  Requests at the end of a semester to change your grade because of, for example, a minimum GPA requirement for a scholarship or fellowship you're on, will not be granted.  Whatever rides on your grade in this class, it's your responsibility to execute. 
:::

Your grade (A+ through F) will be based on the following four categories: homework, participation, two midterm exams, and a final project.  The percentage breakdown of the total into each category is listed in the table below, followed by more in-depth explanations of each category.

There is no pre-set distribution of grades or "curve" across the class: you are not competing against your classmates, and my ideal scenario would be where every student excels and gets an A or A+.  The final grades will be curved, however, in the sense that an A grade won't necessarily fall into the standard 90-100% numerical score range, etc.  Why?  Since this is the first time the course is being taught, it's possible that scores will be higher or lower than the standard ranges (90-100% for A, 80-90% for B, etc.) overall, and at the end of the semester I will adjust all grades in the class accordingly.  But every grade will be shifted in the same direction by this process: again, you will *not* be penalized/rewarded based on how other students perform, and so it's only to your benefit to communicate with your classmates and try to help each other out. 

```{list-table}
:header-rows: 1
:name: grading

* - Category
  - Percentage
* - Homework 
  - 20%
* - Participation
  - 10%
* - Midterms
  - 40% (25% Midterm #1, 15% Midterm #2)
* - Final project
  - 30% (15% submitted report; 15% in-class presentation)
```

(syllabus:hw)=
### Homework (20%)
There will be homework assignments most weeks.  These will be submitted as [Jupyter Notebooks](https://jupyter.org/).  More instructions will follow.  (Don't worry if you've never used Jupyter before; one of the earliest class sessions will be devoted to getting everybody spun up on it.)

The due date and time for each homework assignment will be announced when the assignment is given out to you.  An assignment is considered on time as long as you submit it before the specified time on the specified day.  For each 24 hour period it is late, 10% is subtracted from the grade you'd receive otherwise.  So, for example, two days late = 20% deducted.

You automatically get one no-questions-asked extension over the course of the semester that can be for up to five days from the standard due date.  You can pick any assignment to apply this to; just email me prior to the due date to cash it in.  You can request extensions after the due date, but you will still be docked the points according to how late the request was made.  For example, suppose the assignment was due Monday, and you were behind on it, and then on Wednesday something comes up that will prevent you from finishing it until Friday.  If you make your request that day, then you can earn a maximum score of 80%. 

For extensions after this "freebie", please email me or talk to me before/after class or during office hours *as soon as possible*, including an explanation for why you need it.  These will be considered on a case-by-case basis.  I ask that you act in good faith, and only request one when there are genuinely circumstances beyond your control (illness, emergency), rather than you just got kind of busy that week.  In return, I promise to listen to all of your requests in good faith!  Don't forget that all the assignments *combined* are only worth 20% of your grade...one bad score won't wreck you.


### Participation (10%)
I will track in-class participation over the course of the semester.  This includes attending lectures, raising your hand to ask questions or to answer questions posed to the class, and meaningfully engaging with your classmates during breakout segments of class.

It can be daunting to ask questions or volunteer an answer...but learning to overcome this fear and be willing to ask for help or risk being "wrong" is crucial!  Both for your own intellectual development and for the class atmosphere.  This is meant to be a very active and interactive course, not a one-way lecture.  That requires your active participation.

In terms of the grade, this determination of participation is inherently subjective to some extent.  So, for example, you won't help yourself out by simply raising your hand constantly and asking questions just for the sake of asking them...the adage "quality over quantity" applies here.  That said, if you rarely come to class, are checked out doing things on your phone or laptop the whole time, and never ask a question or offer an answer, that's not good.

Note that I see this primarily as an opportunity to bump grades slightly up (from say a B+ to an A-), not down.  At the end of the day, if you get excellent scores on your assignments, midterms, and final project, but don't participate all that much, I wouldn't bump your grade down on that basis alone.  More realistic is if you did say B-grade work over the semester, but were otherwise a very active participant, I'd use that to justify bumping you up from a B to a B+.

### Midterms (40% total; 25% midterm 1, 15% midterm 2)
There will be two midterms, the first covering material from roughly the first 60% of the semester, and the second covering roughly the remaining 40% (and only that 40%; the second exam is not cumulative).  These will be open-note but in-person, pencil-and-paper *only* exams (no calculators, computers, phones, etc.).

While the course strives to provide you a practically useful toolbox above all else (as described above), no technique for analyzing your data will actually be helpful if you don't genuinely *understand* what it is doing.  In the era of ChatGPT and related tools (more on that below), in-person, pencil-and-paper exams are the best way of determining your level of understanding.  There will be more information closer to each exam regarding the specific material covered and what you can expect from the exam more generally.

The course [schedule](./schedule) is subject to change, but the initial planned midterm dates are **Wednesday, October 25th**, and **Monday, December 11th**.

### Final project (30% total; 15% submitted report; 15% in-class presentation)
In the final project, you will apply some of the statistical methods learned throughout the course to a real-world problem in Earth and Atmospheric Sciences of your choosing.  In consultation with the professor, you will select a topic of interest; then you will conduct data analysis, write a final report (in the form of a self-contained, fully executable Jupyter Notebook), and present your findings to the class.  

The grade will be based on the final report and presentation, both equally weighted.  The presentations will be split over two class periods, tentatively scheduled for **Monday, December 4th** and **Wednesday, December 6th**.  More information on the presentation format and expectations will come later in the semester. 

## Course materials

This is a zero-cost class: there are no required textbooks to buy, and all the software that we will use is free and open-source.  (You do need a computer, however.  If you do not have one, see the "Laptop loaner program" information further below.)

That said, there are many great resources available to you that will further assist you.  See the [Resources](./resources) page of this course website for a list of some recommendations.

The resource that I will draw on most directly is the textbook [*Statistical Methods for Climate Scientists*](https://ccny.textbookx.com/institutional/index.php?action=browse#/books/3839701/) by Timothy DelSole and Michael Tippett.  But again, this is NOT required.


## Academic Integrity

When it comes to academic integrity, the watchword for this course is **respect**.  I (Prof. Hill) bring the utmost respect to this course and to each of you.  Regarding the course, I believe this material is important and fascinating and deserves the utmost care and attention.  Regarding each of you, I am very grateful that you have chosen to take this course, and my aim over the course of the semester is to repay your trust in me as an instructor by delivering an engaging and useful course.  That means (among other things) listening to your questions and concerns as well as fostering an intellectually stimulating and maximally supportive classroom environment.

I ask in return that you pay due respect to the course material, your classmates, and myself.  Among other things, that includes following the CCNY Student Code of Conduct, the CCNY policies on Plagiarism and Academic Integrity, and my own rules regarding ChatGPT and related tools.  Please continue reading for more on each of these. 

### Student Code of Conduct

All student members of the College community are expected to conduct themselves in a manner that demonstrates mutual respect for the rights and personal/academic well-being of others, preserves the integrity of the social and academic environment, and supports the mission of the College.  The College has an inherent right to address behavior that impedes, obstructs, or threatens the maintenance of order and attainment of the aforementioned goals by violating the standards of conduct set forth in the University student conduct policies noted below as well as other policies that may established by the respective Schools, Global Sites, and administrative offices of the University.  

The goals of the [CCNY Community Standards](https://www.ccny.cuny.edu/studentaffairs/community-standards) are:

1. To promote a campus environment that supports the overall educational mission of the University
2. To protect the University community from disruption and harm
3. To encourage appropriate standards of individual and group behavior
4. To foster ethical values and civic virtues
5. To foster personal learning and growth while at the same time holding individuals and groups accountable to the standards of expectations established by the Code of Conduct

[Article XV](https://policy.cuny.edu/bylaws/article-xv/)

### Plagiarism and Academic Integrity

Plagiarism is copying and using other people’s words without proper acknowledgment or citation as it is indicated in the CUNY Policy on Academic Integrity.  All writing submitted for this course is understood to be your original work written.  Plagiarism is unacceptable and has serious consequences that can include a failing grade.  In cases where I detect academic dishonesty (the fraudulent submission of another’s work, in whole or part, as your own), you may be subject to a failing grade for the project or the course, and in the worst case, to academic probation or expulsion. You are expected to read, understand, and adhere to [CCNY’s Policy on Academic Integrity](http://www.cuny.edu/about/administration/offices/legal-affairs/policies-resources/academic-integrity-policy/).

### (LLM snippets added starting spring 2024)
From Mollick and Mollick 2024: "Although the AI's output might be deemed 'good enough,' students should hold themselves to a higher standard".  More generally. LLMs raise the stakes for the students.  If it's helpful, flip your perspective on its head.  You might think "ChatGPT let's me get off easier; I can get the same results with less effort."  Instead, in this class at least, it's basically the opposite: "ChatGPT means that the expectations are that much higher: the instructor expects me to use AI tools to do even better than I could have otherwise.  Mediocre work that I don't really understand or believe in will be graded harshly, and the bar for high-quality work has been raised even higher."  That might seem unfair.  But it's the reality of the world we're in, right now in the Fall of 2025.  It is meant to be *motivating*: just how far can you go?

Types of risk associated with LLM outputs (c.f. Mollick and Mollick 2024):

1. **Confabulation risks**: a.k.a. "hallucination" a.k.a. "making stuff up."  Depending on the context, these can be very easy or *very difficult* for you to spot.  **You are responsible for verifying all LLM outputs.**
2. **Bias risks**: Based on their training data and their fine-tuning, LLMs can be biased in various ways: gender bias, other identity-based bias, political and viewpoint bias.  This can be quite difficult to spot.  For this course on statistical methods, such issues likely won't be hugely important.  Regardless, it's important to be aware of this more generally.   
3. **Privacy risks**: Assume that anything you feed into an LLM will be later used to train future generations of the same LLM or other LLMs.  The legal status here is all shaky.  Note that doesn't necessarily mean that any humans will be reading your individual ChatGPT sessions.
4. **Instructional risks**: an LLM might teach you material in ways that differs from how it's being taught in this class.  E.g. using different notation or slightly different definitions.  Separately, there's the single biggest danger in my mind, of you using it as a crutch that replaces your learning rather than a booster that acclerates it.

There are also bigger-picture concerns one might reasonably have:

1. **AI alignment**: Will we all be turned into paperclips?
2. **Ethics** (training, job displacement):
3. **Environmental impact**:

I approach teaching broadly as follows “We now see that our mission is not instruction but rather that of producing learning with every student by whatever means work best” (Barr & Tagg, 1995, p. 13)

### ChatGPT and other AI tools

`With great power comes great responsibility.` --Spider Man

(Just in case you're not familiar, [ChatGPT](https://chat.openai.com) is an artificial intelligence (AI) tool (specifically, a "large language model" or LLM) that is extremely powerful.  In response to questions written in plain english, it can for example write whole essays, generate snippets of computer code, or explain technical concepts.  There are other similar LLM tools available as well, but for brevity I'll use ChatGPT as shorthand for any such tool.)

We live now firmly in the "ChatGPT" era.  There's no getting around it. 

Specifically for this course on Statistical **Methods**---where we're building up a toolkit of techniques you can use in your research and other courses---ChatGPT represents in some ways a master tool, a way to very rapidly learn about new tools, or clarify confusion about one or the other, or generate code that helps you implement a new one.  Moreover, ChatGPT and related models will only get better as we move into the future, making them more and more powerful.  It's not hard to imagine a future, even within the next few years, where even highly technical work like research in the Earth Sciences becomes more than anything simply telling an LLM what you want it to do.

Setting that aside and returning to the present, for learning and teaching this presents a double-edged sword.  On the one hand, I encourage you to use ChatGPT in whatever capacity that is helpful to your **learning**.  In fact there will be some class time during the semester devoted specifically to teaching you how to use it effectively.  On the other hand, in this and other courses, having a tool that can churn out a decent essay, spit out the computer code, or solve the calculation you've been assigned, can be a serious crutch.  You simply will not learn the material if you just ask ChatGPT to do it for you.  (One potentially useful indicator that it's becoming a crutch is: (a) you use ChatGPT on your homework assignments AND (b) you score much worse on the in-class, pencil-and-paper midterms than you do on the homework assignments.)

For those reasons, I will permit and even encourage you to use ChatGPT in any assignments I give you.   And I'm not going to ask you to disclose if you used it, or if you worked with another student (which you're always free to do), etc.  (This does not apply to in-class exams, quizzes, etc. for which I will explicitly state that you are not to use it.)

If you use ChatGPT as a crutch, to get to the right answer but without thinking critically, and that leads you to get an "A", then to me, that's your loss.  Conversely, if you take a puritan stance and refuse to use this new generation of tools, which very much *are* the future, and that hinders your ability to keep up with your peers, then likewise that's your loss.  But if you approach ChatGPT and the course material with curiosity and respect, using it as a tool to help you connect with the material *even more deeply than you could otherwise*, then that's your gain and my gain.

Let's be excited about these powerful new tools, but let's be even more excited about growing your own intellectual capacity!

## CCNY resources available to you

### AccessAbility Center / Student Disability Services

The [AccessAbility Center/Student Disability Services](https://www.ccny.cuny.edu/accessability) ensures equal access and full participation to all of City College's programs, services, and activities by coordinating and implementing appropriate accommodations. If you are a student with a disability who requires accommodations and services, please visit the office in NAC 1/218, or contact AAC/SDS via email ([disabilityservices@ccny.cuny.edu](mailto:disabilityservices@ccny.cuny.edu), or phone (212-650-5913 or TTY/TTD 212-650-8441).

### CCNY Writing Center

The [CCNY Writing Center](https://www.ccny.cuny.edu/writing) offers a supportive learning environment where students can have one-on-one tutoring sessions with writing consultants.  It is a great resource for you to obtain extra help as you write and revise your papers.  They DO NOT proofread your papers, but offer assistance on improving certain aspects of them.  They also offer ESL tutoring.  To set up an appointment visit their [online booking system](https://www.ccny.cuny.edu/writing/appointments-walk-sessions), or call 212-784-6065.  I strongly advise you contact them as soon as possible, even if you don’t have anything specific you need assistance with yet.

### SEEK Peer Academic Learning Center

NAC 4/224

Phone: 212-650-5786 | Email: [seekpals@ccny.cuny.edu](mailto:seekpals@ccny.cuny.edu)

Offers counseling and peer tutoring for students in need of academic and financial support who have registered for the SEEK Program.

### Benny's Food Pantry

As a student, you are welcome to visit [Benny’s Pantry](https://www.ccny.cuny.edu/bennysfoodpantry) whenever you or someone you care for is in need. Benny’s serves as a resource to anyone who finds themselves in need throughout the year. 

In addition to providing food assistance, Benny’s Pantry is a gateway to connect students and their families, faculty, and staff to critical support services such as: 

- SNAP benefits;
- Emergency grants through referrals to the Colin Powell School (for CPS Majors), OIAC, or Student Affairs, depending on the type of need; 
- Emergency housing referrals; 
- Job preparation and training through referrals to our CPDI team;
- Health workshops and nutrition training, co-sponsored as part of our World Food Day Initiatives and food pantry demo days throughout the year.

### Service Desk

The [CCNY Service Desk](https://www.ccny.cuny.edu/it/help) is IT’s point of contact for students who need help with services such as Blackboard, CUNYfirst, and Citymail. 

### Laptop Loaner Program

The City College Office of Information Technology provides a [laptop loaner program](https://portal.ccny.cuny.edu/depts/oit/cuny_loaner/login.php) for current CCNY students. The program is funded by the CCNY Student Technology Fee. The laptops are internally equipped with WiFi for use where wireless access exists. Wireless networking is available throughout much of the campus. All laptops are loaded with MS Office, Adobe Acrobat, as well as other CCNY-approved software. This program is designed for experienced computer users who are able to use the installed applications. Please note: you must be logged into WiFi for some software to be fully operational.

### Other Student Resources

There are many more services available to you listed on [this website](https://ourtlc.commons.gc.cuny.edu/syllabus-statements/#other_student_resources).  They include:

- [CCNY Navigate](https://www.ccny.cuny.edu/ccny-navigate)
- [Tutoring Services](https://www.ccny.cuny.edu/academics/tutoring)
- [International Student and Scholar Services](https://www.ccny.cuny.edu/isss)
- [LGBTQ+ Student Center](https://www.ccny.cuny.edu/lgbtq-student-center)
- [Counseling Center](https://www.ccny.cuny.edu/counseling)
- [Gender Resources](https://www.ccny.cuny.edu/health-wellness/gender-resources)
- [Office of Diversity and Compliance](https://www.ccny.cuny.edu/affirmativeaction)
- [The Psychological Center](https://www.thepsychologicalcenter.org/)
- [Emergency Grants](https://www.ccny.cuny.edu/health-wellness/emergency-grants-program)
- [Housing Insecurity and Homelessness Resources](https://www.healthycuny.org/resources-housing-homelessness)
- [Reduced Cost Transportation](https://www1.nyc.gov/assets/fairfares/downloads/pdf/application/Fair-Fares-Application-English.pdf)
- [CARE (Communication, Action, Response, Evaluation) Team](https://www.ccny.cuny.edu/studentaffairs/care-team)
- [City College Immigration Center](https://www.ccny.cuny.edu/we-are-one-ccny/city-college-immigration-center)
- [Career and Professional Development Institute](https://www.ccny.cuny.edu/cpdi)
- [CCNY Child Development Center](https://www.ccny.cuny.edu/cdc)
- [Student Health Services](https://www.ccny.cuny.edu/shs)
