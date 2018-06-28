# Course 4: Statistical Learning
This repository will house all the materials for the first course in the data science specialization using R, developed for the UO COE.

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

* * *

# Syllabus
## EDLD XXX: Statistical Learning (CRN: XXXXX; 3 credit hours)
* **Term:** Fall 2018
* **Time:** MW, 10-11:50 
* **Classroom:** 115 ED
* **Instructor:** Daniel Anderson, PhD
	+ *email:* (preferred contact method) [daniela@uoregon.edu](mailto:daniela@uoregon.edu)
	+ *phone:* 541-346-3317
	+ *office:* 175 Lokey


# Course Overview
This is the fourth course in a five course *data science in educational research* specialization. Statistical learning is a field that ties together statistical theory and practice with the methods of machine learning that have emerged in the last several decades. The primary goal of these methods is to create models capable of prediction.

# Student Learning Objectives
By the end of this course students will be able to 

- Describe the framework of statistical learning (i.e. supervised vs. unsupervised learning) and map a data analytical question to a location in this framework.
- Outline the different capabilities of statistical learning models  (predictive, inferential, descriptive/explorative) and be able to discern which is needed in a particular scenario.
- Discuss the bias-variance tradeoff in supervised learning and apply the concept in making decisions about model selection.
- Apply tools of cross validation and regularization to guard against overfitting a model.
- Construct a supervised learning model drawn from the following list of methods. For each method, they will be able to link the research question to appropriate methods, understand the principles at work in each method, implement the method in R, and interpret the output and how it bears on the research question.
    - Supervised Learning:
        - Linear regression
        - Penalized regression (ridge, lasso)
        - CART
        - Random Forests
        - Boosted Trees
    - Classifiation:
        - Logistic regression
        - Discriminant analysis
        - k-Nearest Neighbor
        - CART
        - Random Forests
- Apply multiple regression techniques to a real data set and evaluate/synthesize the results is a sytematic manner.
- Apply multiple classification techniques to a real data set and evaluate/synthesize the results in a systematic manner.
- Recognize when a data set might benefit from a dimension reduction technique, implement that technique, and interpret the output.
- Implement clustering techniques (k-means, hierarchical clustering), describe the similarities and differences in their approach, and use a scree plot to discern the scale of clustering.

# Course Reading List And Other Resources
All course readings are freely available online or will be provided by the instructor. 

### Books (required)
- James, Gareth et. al. (2017). *[An Introduction to Statistical Learning with R](http://www-bcf.usc.edu/~gareth/ISL/)*. New York, NY: Springer.

### Books (not required, but possibly helpful)
* Diez, D and Barr, C and Cetinkaya-Rundel, M (2014). *[OpenIntro Introductory Statistics with Randomization and Simulation](https://www.openintro.org/stat/textbook.php?stat_book=isrs)*.
* Hastie, T et. al. (2009). *[Elements of Statistical Learning](http://web.stanford.edu/~hastie/ElemStatLearn/)*. New York, NY: Springer.
* Kuhn, M and Johnson, Kjell (2014). *[Applied Predictive Modeling in R](http://appliedpredictivemodeling.com/user2014/)*, New York, NY: Springer.

### Resources
#### [DataCamp](https://www.datacamp.com)
We will have a class subscription to [DataCamp](https://www.datacamp.com). This means all the courses they offer (which is a lot) are available to you. I encourage you to explore the website and play around.

# Weekly Schedule (Topics, Assignments, and Readings)


|  **Week** | **Theme** | **Topics** | **Lab** | **PS Assigned** | **PS Due** | **Reading** |
|  ------ | ------ | ------ | ------ | ------ | ------ | ------ |
|  1a | Foundations of Statistical Learning | Guess my age: human vs statistical learning |  | PS1 |  | ISLR 1-16 |
|  1b |  | Estimating f, Bias-Variance Tradeoff | Lab 1 |  | PS1 | ISLR 29-36 |
|  2a | Linear Regression | Simulation and Decomposition, estimation and inference for SLR |  | PS2 |  | ISLR 59-68 |
|  2b |  | Extending the linear model I: adding variables, polynomial, interactions, assessing fit. | Lab 2 |  |  | ISLR 69-74, 79-96 |
|  3a |  | Extending the linear model II: diagnostics, outliers, transformations, multicollinearity | Lab 3 |  | PS2 | ISLR 96-104 |
|  3b |  | Review regression competition, model selection, penalized regression |  |  |  | ISLR 203-228 |
|  4a | Classification | Logistic regression |  |  |  | ISLR 127-138 |
|  4b |  | Discriminant analysis (LDA, QDA) |  | PS3 |  | ISLR 138-142 |
|  5a |  | Classification errors, ROC | Lab 4 |  | PS4 | ISLR 142-154 |
|  5b | Resampling Methods | Crossvalidation (validation set, LOOCV, k-fold) |  |  |  | ISLR 175-186 |
|  6a |  | Bootstrap | Lab 5 |  |  | ISLR 187-197 |
|  6b | Trees | Regression and classification trees |  |  |  | ISLR 303-316 |
|  7a |  | Bagging, random forests |  | PS 5 |  | ISLR 316-321 |
|  7b |  | Boosting | Lab 6 |   | PS 5 | ISLR 316-324 |
|  8a | Dimension Reduction | Principle component analysis fundamentals |  |  |  | ISLR 374-385 |
|  8b |  | Principle component analysis image reconstruction |  |  |  |  |
|  9a | Clustering | k-means clustering, hierarchical clustering | Lab 7 |  |  | ISLR 404-413 |
|  9b | Special Topics | Support vector machines |  | PS6 |  | ISLR 337-355 |
|  10a | Final Presentations | Student presentations day 1 |  |  | PS6 |  |
|  10b |  | Student presentations day 2 |  |  |  |  |
|  11 | No class: Final papers due |  |  |  |  |  |

* * *

# Assessment

### Attendance (10%)
A critical component of learning data science includes receiving structured feedback as you problem-solve coding and data issues. Each lab will be introduced and begun in class, so that as a group we can talk through the task at hand. Supporting your classmates is also important, and so attendance during final presentations is mandatory.

### Problem Sets (20%)
The problem sets allow you to think through the concepts introduced in class and through the reading. Most are short answer, some require mathematics and coding.

### Labs (30%)
There are 7 labs during the course, which must be submitted to the instructor prior to the start of the following class. These labs will be scored on a "best honest effort" basis, which generally implies zero or full credit (i.e., the assignment was or was not fully completed). However, many of the labs require students complete specific portions before moving on to the next sections. If you find yourself stuck and unable to proceed, **please contact the instructor for help rather than submitting incomplete work**. Contacting the instructor is part of the "best honest effort", and can result in full credit for an assignment even if the the work is not fully complete.


## Final Project
The final project in this class is a group project to develop a series of predictive models for a real world data set in order to answer a question of interest. Ideally, students would work with a dataset that includes variables they are interested in using beyond just this class; however, if students do not have access to data, the instructor will provide one. **Students who do not have access to data should plan to meet with the instructor as soon as possible so a dataset can be provided**. Additionally, the dataset must be able to be shared publicly, as the full project will be required to be housed on GitHub and be fully reproducible. If making your data publicly available is a problem for you, please contact the instructor as soon as possible. We can work together to either find a dataset that will work for you, or simulate a dataset that is similar to the data you'd like to work with in reality (and then all your code should work for the real dataset, but you can share the simulated data with your classmates). Students are required to work in groups of 2-4 people. The final assignment is assigned during the first class, and groups must be finalized by the end of Week 2 (at which point students who have not self-selected into groups will be randomly assigned).

### Outline (5%)
A basic outline of the final project is due at the end of Week 5. The outline should include the motivating research question, a description of the data to be used, a discussion of what preparatory work will need to be done, and an indication of the methods that will be applied. The outline is intended to be low-stakes and is primarily designed to be a means for you to obtain feedback on the feasibility of the project and areas to consider. 


### Final Project Presentation (10%)
Each group will present on their final project during Week 10, which is expected to still be in progress. These presentations are expected to be informal, and emphasis what learning occurred during the project. The final presentation should be equal parts “journey” and substantive findings/conclusions/results. Students are expected to present for approximately 10 minutes each (20-40 minutes per group), although the time may change depending on the enrollment of the class.


### Final Paper (25%)
The purpose of the final paper is to allow students an opportunity to demonstrate all the skills they have learned throughout the course. The final paper will be a reproducible and dynamic APA manuscript produced with R Markdown via the [*{papaja}*](https://github.com/crsh/papaja) package. This paper will be assessed based on the following criteria.

* Writing is clear and comprehensive: (25%)
* Document is fully reproducible: (15%)
* At least two visualizations as part of EDA: (15%)
* Demonstrate appropriate use of multiple predictive techniques: (25%)
* Comparison and sythesis of results for multiple techniques: (10%)
* Interpretations of the results in the context of the research question: (10%)

The document should be structured according to the following template.

#### Abstract
A brief overview of the area that you'll be investigating, the research question(s) of interest, your approach to analysis, and the general conclusions.

#### Introduction
Overview of the setting of the data, existing theories/models, and your research questions.

#### The Data
Where does the data come from? How many observations? How many variables? What does each observation refer to (what is the observational unit)? What sorts of data processing was necessary to get the data in shape for analysis?

#### Exploratory Data Analysis
Explore the structure of the data through graphics. Here you can utilize both traditional plots as well as methods from unsupervised learning.

#### Modeling
Construct (descriptive and/or predictive) (classification and/or regression) models that address your research questions. You are encouraged to fit many different classes of models and see how they compare in terms the bias/variance tradeoff (do you have a Rashomon effect going on?). Also be sure to guard against overfitting through cross-validation or shrinkage/penalization (don't forget about ridge regression and the lasso).

This will be the most extensive section and will include your results as well.

#### Discussion
Review the results generated above and sythensize them in the context from which the data originated. What do the results tell your about your original research question? Are there any weaknesses that you see in your analysis? What additional questions would you explore next?

#### References
At minimum, this will contain the full citation for your data set. If you reference existing analyses, they should be cited here as well.


# Grading Components
|  **Lower percent** |**Lower point range**  | **Grade** | **Upper point range**  | **Upper percent**|
|  :------: | :------   | :-:| :-------: | ----:|
|  0.97     | (451 pts) | A+ |           |      |
|  0.93     | (432 pts) | A  | (451 pts) | 0.97 |
|  0.9      | (418 pts) | A- | (432 pts) | 0.93 |
|  0.87     | (405 pts) | B+ | (418 pts) | 0.9  |
|  0.83     | (386 pts) | B  | (405 pts) | 0.87 |
|  0.8      | (372 pts) | B- | (386 pts) | 0.83 |
|  0.77     | (358 pts) | C+ | (372 pts) | 0.8  |
|  0.73     | (339 pts) | C  | (358 pts) | 0.77 |
|  0.7      | (325 pts) | C- | (339 pts) | 0.73 |
|           |           | F  | (325 pts) | 0.7  |

# Student Engagement Inventory
Graduate: 1 credit hour = 40 hours of student engagement (3 credit hours = 120 hours of student engagement) 

| **Educational activity** | **Hours student engaged** | **Explanatory comments (if any):**                                                                               |
| :----------------------- | :-----------------------: | :--------------------------------------------------------------------------------------------------------------- |
| Course attendance        |            26.5             | 20 meetings, at 80 minutes per meeting                                                                           |
| Assigned readings        |            27             | Weekly readings are assigned, and are expected to take roughly as long to complete as the in-seat time per week. |
| Projects                 |            33.5             | Final project, as described above                                                                                |
| Homeworks                |            33           | 7 labs, at approximately 3 hours per lab spent out of class (21 hours), plus 6 problem sets, at approximately 2 hours each (12 hours) |
| Total hours:             |            120            |                                                                                                                  |

# Attendance and Absence Guidelines
Attendance at all class and discussion groups is expected and required, as described above.

Students must contact the instructor in case of illness or emergencies that preclude attending class sessions. Messages can be left on the instructor's voice mail or e-mail at any time of the day or night, prior to class. If no prior arrangements have been made before class time, the absence will be unexcused. Excused absences will involve make-up assignments, with make-up assignment procedures to be discussed in class on the first day. 

If you are unable to complete an assignment due to a personal and/or family emergency, you should contact your instructor or discussion leader as soon as possible. On a case-by-case basis, the instructor will determine whether the emergency qualifies as an excused absence. 

# Expected Classroom Behavior
Students are expected to participate in classroom activities. If use of digital devices or engagement in other non-class activities during class for purposes not regarding classroom activities is critically necessary, the student should engage in these activities while on break, or check with the instructor to arrange for a 10-minute break for unusual circumstances, but only if critically necessary. 

# Course Policies 
## Diversity, Equity and Inclusion
It is the policy of the University of Oregon to support and value equity and diversity and to provide inclusive learning environments for all students.  To do so requires that we: 

* respect the dignity and essential worth of all individuals. 
* promote a culture of respect throughout the University community. 
* respect the privacy, property, and freedom of others. 
* reject bigotry, discrimination, violence, or intimidation of any kind. 
* practice personal and academic integrity and expect it from others. 
* promote the diversity of opinions, ideas and backgrounds which is the lifeblood of the university.

In this course, class discussions, projects/activities and assignments will challenge students to think critically about and be sensitive to the influence, and intersections, of race, ethnicity, nationality, documentation status, language, religion, gender, socioeconomic background, physical and cognitive ability, sexual orientation, and other cultural identities and experiences. Students will be encouraged to develop or expand their respect and understanding of such differences.

Maintaining an inclusive classroom environment where all students feel able to talk about their cultural identities and experiences, ideas, beliefs, and values will not only be my responsibility, but the responsibility of each class member as well. Behavior that disregards or diminishes another student will not be permitted for any reason. This means that no racist, ableist, transphobic, xenophobic, chauvinistic or otherwise derogatory comments will be allowed. It also means that students must pay attention and listen respectfully to each other’s comments.

## Documented Disability
Appropriate accommodations will be provided for students with documented disabilities. If you have a documented disability and require accommodation, arrange to meet with the course instructor within the first two weeks of the term. The documentation of your disability must come in writing from the Accessible Education Center in the Office of Academic Advising and Student Services.  Disabilities may include (but are not limited to) neurological impairment, orthopedic impairment, traumatic brain injury, visual impairment, chronic medical conditions, emotional/psychological disabilities, hearing impairment, and learning disabilities. For more information on Accessible Education Center, please see http://aec.uoregon.edu 

## Mandatory Reporting of Child Abuse
UO employees, including faculty, staff, and GEs, are mandatory reporters of child abuse. This statement is to advise you that that your disclosure of information about child abuse to a UO employee may trigger the UO employee’s duty to report that information to the designated authorities. Please refer to the following links for detailed information about mandatory reporting:
http://hr.uoregon.edu/policies-leaves/general-information/mandatory-reporting-child-abuse-and-neglect

## Reporting Title IX Experiences
Any student who has experienced sexual assault, relationship violence, sex or gender-based bullying, stalking, and/or sexual harassment may seek resources and help at safe.uoregon.edu. To get help by phone, a student can also call either the UO’s 24-hour hotline at 541-346-7244 [SAFE], or the non-confidential Title IX Coordinator at 541-346-8136. From the SAFE website, students may also connect to Callisto, a confidential, third-party reporting site that is not a part of the university. 

Students experiencing any other form of prohibited discrimination or harassment can find information at aaeo.uoregon.edu or contact the non-confidential AAEO office at 541-346-3123 or the Dean of Students Office at 541-346-3216 for help. As UO policy has different reporting requirements based on the nature of the reported harassment or discrimination, additional information about reporting requirements for discrimination or harassment unrelated to sexual assault, relationship violence, sex or gender based bullying, stalking, and/or sexual harassment is available at http://aaeo.uoregon.edu/content/discrimination-harassment 

Specific details about confidentiality of information and reporting obligations of employees can be found at https://titleix.uoregon.edu. 

## Academic Misconduct Policy
All students are subject to the regulations stipulated in the UO Student Conduct Code http://conduct.uoregon.edu). This code represents a compilation of important regulations, policies, and procedures pertaining to student life. It is intended to inform students of their rights and responsibilities during their association with this institution, and to provide general guidance for enforcing those regulations and policies essential to the educational and research missions of the University.  

## Conflict Resolution 
Several options, both informal and formal, are available to resolve conflicts for students who believe they have been subjected to or have witnessed bias, unfairness, or other improper treatment. 

It is important to exhaust the administrative remedies available to you including discussing the conflict with the specific individual, contacting the Department Head, or within the College of Education, you can contact the Associate Dean for Academic Affairs and Equity (Krista Chronister, 346-2415, kmg@uoregon.edu). Outside the College, you can contact: 
* UO Bias Response Team: 346-3216 http://bias.uoregon.edu/whatbrt.htm 
* Affirmative Action and Equal Opportunity: 346-3123 http://aaeo.uoregon.edu/

## Grievance Policy
A student or group of students of the College of Education may appeal decisions or actions pertaining to admissions, programs, evaluation of performance and program retention and completion. Students who decide to file a grievance should follow the student grievance procedure, or alternative ways to file a grievance outlined in the Student Grievance Policy (https://education.uoregon.edu/academics/student-grievance) or enter search: student grievance.

## In Case of Inclement Weather 
In the event the University operates on a curtailed schedule or closes, UO media relations will notify the Eugene-Springfield area radio and television stations as quickly as possible. In addition, a notice regarding the university’s schedule will be posted on the UO main home page (in the “News” section) at http://www.uoregon.edu. Additional information is available at http://hr.uoregon.edu/policy/weather.html.

If an individual class must be canceled due to inclement weather, illness, or other reason, a notice will be posted on Canvas or via email. During periods of inclement weather, please check Canvas and your email rather than contact department personnel. Due to unsafe travel conditions, departmental staff may be limited and unable to handle the volume of calls from you and others.

## Course Incomplete Policy
Students are expected to be familiar with university policy regarding grades of “incomplete” and the time line for completion. For details on the policy and procedures regarding incompletes, Please see: https://education.uoregon.edu/academics/incompletes-courses


