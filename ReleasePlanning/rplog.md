# Release Planning Assignment
#### Large Scale Requirements Engineering (PA2521)
#### Akshay Kumar Magapu
#### akma15@student.bth.se

#### Release Planning assignment is about analysing the requirements and assigning these to a suitable release plans using requirement engineering techniques. This log consists of my activity in this release planning assignment.

## Week 46

# Work done :white_check_mark:

Started tracking issues commented on Course Chatroom #69 issue which is "Is this chatroom only for students or between teacher and students?"
The issue is clarified with both the participants can chat together or can have a private chat.

Lesson Learnt <br>
L1: As the requirements does not contain clear enough information to implement, so there is a need of these requirements to be clarified.

## Week 47

# Workdone :white_check_mark:

Started commenting on other issues to get clarification. these are the issues where i commented and get clarified:<br>
1. Personal Profile #16 <br>
What options the personal profile should provide? Which information should be visible to other users and which information should not (for example personal number should not be visible) ?
2. System Users #18<br>
Can user register account in the system or administration provides the login details to the user so that new account creation feature is not needed.<br>
Got clarified that both procedures can be applied to create an acoount for user.<br>
3.First login #63<br>
User can edit the information in profile anytime whenever the user likes. So it does not mean user has an incomplete profile. But sensitive information like personal number changing should be restricted based on number of changes.<br>
4.Change Privileges for Course Participators #60<br>
What privileges are available to a participator and who can change these privileges?<br>
Got clarified that there are other clarifications for this issue.<br>
5.Streaming Video #73<br>
The teacher can upload the videos in YouTube as a private video and embed the link in the course section. So it will be easy and users without link cannot see as the video is set as private.<br>
Got clarified that we cannot use any third party application as for privacy issues.<br>
6.RTF files #72<br>
The format the system accepts must be checked before uploading the file. So there must be a list of file formats mentioned in the system so user can know which file can be uploaded and which cannot be.<br>
7. Secure Product #3<br>
So system manager have information about what everyone is doing, as this have privacy issues. So there should be a limit like messages between teacher and student should not be visible to others.<br>
8.Market #6<br>
Why the present market want to change to this system as there are many course management systems available to the universities?<br>
Got clarified that we should not consider why but to do the given requirement so the changes required for other countried have to be known.<br>
9. Course Information #8<br>
Does the users provided with an option to register for other courses?<br>
Got clarified that by having an option so i need to add requirements for this option.<br>
10.Usable Product #10<br>
So non-functional requirements are need to be considered, are these taken during the planning or added during development?<br>
Got clarified that the non-functional requirements also to be consider during this phase only.<br>
11. User Calendar #2<br>
As the calendar is to know the events dates and classes dates, integrating the calendar with the user mobile calendar helps the user. So restriction of calendar access to only system is not a good idea.<br>
Got clarification as it is required and i need to add requirements for this and also security requirements.<br>
Made duplicates of issues #54, #29, #14 to issue #55 but got clarified that these are clarifications of the main issue. So clarification labels are assigned to these issues. <br>

## Week 48

# Workdone :white_check_mark:

Linked depedencies of issues #65,#17,#36 to issue #9.<br>

Discussed in the group discussion forum about priortization as: I am familiar with planning poker, also we can use use-case points estimation technique as it is based on requirements and formula based approach without an expert opinion.
Replys came as whether planning poker is suitable for 5000 requirements. <br>

Lesson Learnt <br>
L2: The dependencies should be considered as it helps to know which requirements can be implemented without any other requirements and which need to implemented combinedly.
L3: As planning poker is not suitable for that many requirements, other techniques are to be evaluated which can be useful for large scale requirements.

## Week 49

# Work done :white_check_mark:

Started adding new requirements to enhance the present requirements. <br>
1. Register option for courses #74 <br>
Through this participant can register to the courses that are displayed in course dashboard. 
This requirement is a further clarification of issue #8. <br>
2. Linked two issues that are related  #12 #21 <br>
Linking provides to access requirements of a feature from referenced issues.
3. Created a new issue: Sign Up for participants #75 <br>
Through this, the user can register an account in the system. Clarification to #18. <br>
4. created a new issue that provides bugfix to RTF file upload.
Supportable formats #76 <br>
A list of supportable formats needs to be displayed where there is a upload button. So users of the system can easily know which format files to upload. Clarification to #72. <br>
5. Added sub-requirements #30 #31 to issue #15. <br>
This provides further clarification of the given requirement. <br>
6. Created a new issue: Search option #77 <br>
Users can search to find what information they need. <br>
7. Linked the issues to #42 for further clarification: Link to this requirement news items: #14 #55, Course participators: #36 #65 , Privilidges: #60 . <br>
8. Personalised Views #2
Linked the sub-requirements to this requirement #40 for further clarification.
9. Linked two requirements #32 #34 as these two describes how to handle the social security number. <br>
10. Linked the similar functionality requirements #67 #68 as these two describes the contents of the message and what features to be included while replying the message. <br>
11. Added a new issue : Account activity #79 <br>
This provides the activity of account i.e. if a user login to account from a new device or system it should send an alert to user mail so the unauthorized access can be notified. <br>
Also linked it to issue #3 which is the main requirement to this sub-requirement. <br>
12. Clarified a comment regarding which mail server to be used in issue #79. <br>
we can use SMTP mail server that we use for our course management system or if there is any other one add requirement and link it. <br>
13. created a new issue: Literature databases #94 <br>
The user should have access to literature database like IEEE from course management system itself. <br>
14. Created a new issue: Course feedback #96 <br>
Students can provide their feedback to the course through this feature. <br>
15. Teacher timetable and meeting #97 <br>
It provides user to access the timetable of teacher and book an appointment with teacher/lecturer. <br>


Many requirements with dependencies are linked here as some requirements REQUIRES another requirement to function[2]. Also created new feature requirements and new bug solving requirements in this week. As new features can be suggested through market trend and what customer wants which will be unique from other market products.

Lesson Learnt: <br>
L4: The requirements can be arrived in market driven development like a bunch of requirements but from these bunch of requirements which are more suitable and market trend are need to be identified [5] and these also need to be valued by customer then only it can be success.

## Week 50

# Work done :white_check_mark:

## Assigned myself to the following areas:

* Registration
    + Register for exams #111
    + Register option for courses #74
* Databases
    + Database for projects #110
    + Literature databases #94
    + Access to edit user database #53
* Schedule and meeting
    + Teacher timetable and meeting #97
* Course
    + Course feedback #96
    + Course information #21
    I selected these two, as by receiving the feedback on the course, i can change the course scope.
* Format
    + Supportable formats #76
    + RTF files #72
* Signup
    + Signup for participants #75
    + System users #18

## Read the following article for prioritizing the requirements.
Berander, Patrik, and Anneliese Andrews. "Requirements prioritization." Engineering and managing software requirements. Springer Berlin Heidelberg, 2005. 69-94.<br>

To prioritize the requirements we can use following techniques:
1.AHP (analytical hierarchy process)
This technique is to compare all possible pairs of requirements and find which requirements have high priority. The disadvantage is for more number of requirements we need to do more number of comparisons.
2.100 dollar test
This technique is to distribute the given 100 dollars(for example) to the requirements and prioritize based on distribution. The disadvantage is one can give more amount to selected requirements.
3.Top ten estimation
This technique is to pickup ten requirements by each member and prioritize based on that.
4.Ranking
This technique is to rank the requirements so that the requirements with rank 1 are most important.
5.Grouping (critical, standard, optional)
This technique is to categorize the requirements into critical, standard and optional. So based on these the requirements can be prioritized for release planning. <br>

The grouping technique is considerable technique when compared to other in large scale requirements. As in AHP the numer of comparisons increase it increases the complexity, while 100 dollar test has less probability while assigning 100 dollars to all requirements, topten requirements are not that much suitable in large scale if we consider 5000 requirements it is not a best method, Ranking may be the option but while giving ranks we need to fix whether we need to consider detail or abstract level requirements, whereas in grouping we need to classify requirements under Must have, Should have, Could have, Wont as it is simple to do even in the case of large scale requirements. So i suggest to use grouping technique and we will discuss and group the given issues into following classifications for this release planning assignment.

## Labels

Assigned labels to the issues and i confused for the label clarification where i thought if we link sub-requirements to a requirement it gives more clarification so i added clarification label. But after a question raised by mickesv, i got clarity that the label should reflect the requirement only. So i changed the labels where i added clarification unnecessarily and also i added feature label to the feature requirements and enhancement label to the requirements which enhance the present functionality and bug label to some requirements.<br>

Lesson learnt:
L5: The requirements are to be labelled so that these can be easily identified whether they are to be clarified, bug, feature etc. and also obsolete requirements[6] can also be easily recognized.
L6: There are tools avilable for release planning, but as we did in GitHub there may be some less features. But release planning tools(RE management tools) provide organizing requirements and allocating effort for the requirement and dividing them into different release plan and have a nice interface than GitHub.

## Dependencies
For dependencies, we need to see the interdependencies between requirements so that the release plan can consist of a deliverable which will function, whereas if we did not consider the dependency then it may cause that a particular release plan may not consist a functional deliverable. I studied an article regarding this interdependencies [2], <br>
In this there are six types of interdependencies, they are AND, OR, REQUIRES, TEMPORAL, ICOST, CVALUE.
By this we need to take the top 20 prior requirements and we need to find the interdependencies between them using above types.

This paper solves the issue of dependencies between requirements as these are important to determine interdependencies between requirements so it will be easy to divide requirements into milestones.

## New issues created are:

1.Register for exams #111 <br>
Students can register for exams based on their course.<br>
2. Database for projects #110 <br>
Students can retrieve the thesis articles and other projects that are carried out by final-year students. <br> 

## Week 52

# Work done :white_check_mark:

Articles which i read and helpful for release planning assignment are:

[1]. Berander, Patrik, and Anneliese Andrews. "Requirements prioritization." <br>

Summary is provided above.

[2].An industrial survey of requirements interdependencies in software product release planning." <br>

# Brief Summary

Identifying requirements interdependencies is a complex task as only 20% of requirements are responsible for the interdependencies. In this paper, the authors aim is to know the nature of interdependencies and classify them to support for release planning. A survey is conducted with five different companies, which consists small, medium and large scale companies. In each company the requirements manager (here requirements manager can be a product manager, project manager, requirements engineer) asked to select top 20 requirements that are higher priority and from these the dependency between each pair of requirements is needed to be found.  If any pair consists of interdependencies, then the type need to be specified. There are types of interdependencies which are AND, OR, REQUIRES, TEMPORAL, ICOST, CVALUE. The RM's have authority to add new relationship between requirements but in this survey there is no new relationships between requirements are identified. The results show that the most common type is value related which consists of ICOST and CVALUE. These are the requirements which may affect the cost or value of another requirement. Then the functional related type is there for other two companies which are AND and REQUIRES, the AND means the pair of requirements needs each requirement to function whereas in REQUIRES one requirement needs another requirement but not vice-versa. The most interesting aspect here is that market or product oriented cases have value related interdependencies are more common whereas in bespoke development projects the functional related interdependencies are most common. Then only a few requirements have no relationship with other requirements and few requirements responsible for large interdependency relationships. Then these interdependencies are visualized approach to managing these requirements. By this the singular requirements that are not dependant on any other requirements can be easily spotted. Also requirements that are having the most number of interdependencies are also easily identified and lastly the requirements that are free can be scheduled to any increment. The most important is to identify the highly dependent requirements so that the number of pairwise matchings can be reduced, and also 69-79% of all dependencies can be covered through these. The selection of requirements for each release plan should be considered in a way such that there should be less number of interdependencies between iterations. SO identifying the interdependencies leads to select the requirements with more dependencies in the same release. This is said to be low coupling between requirements so that each release can have a deliverable that will function. So this strategy reduces the release coupling. There is further research needed like knowing the relationship between already implemented requirements and new requirements.


[3]. Ruhe, Günther, and Moshood Omolade Saliu. "The art and science of software release planning." .

# Brief Summary

 In this paper, to improve the release planning process the authors tried to integrate two approaches. In one approach communication, knowledge of human, and negotiation of conflicts are included which is art of release planning. In another approach a solution is generated by applying a formalized problem to computational algorithm which is science of release planning.
   Basically, organizations do not use a sound model or methodology they just select requirements and assign in release planning in a informal way. So there is no exact information about how to perform release planning process effectively.
   Agile methodology also takes this art approach to involve humanistic characteristic but it does not provide how to select features when multiple stakeholder exists. The optimization model authors presented here has the flexibility in number of releases in which, a decision variable consists of set of features and the goal is to assign these set of features to some release options.
   Coupling relation exist between features in which two features need to be released combined and a precedence relation in which a sequence of releases to be done.
   Each release plan should satisfy the resources available. Stakeholders are prioritized by using a ordinal scale (1-9). Features are also prioritized by using ordinal scale (1-9) and urgency of feature whether to release first or later release.
   Finally, an objective function is assumed in which average of stakeholders, feature prioritization is used to maximize function in every release plan and satisfy resource constraint which comes under modelling phase.
   So based on these, a set of good alternatives can be achieved by solving the linear programming problem in which a good solution is considered only if it is 95% of object function value which is exploration phase.
   A human expert evaluates the alternatives and selects a best one which is a consolidation phase.
   As by integrating these two approaches, best features like formalization of problem, sophisticated method, human intuition, and evaluation of alternative solution leads to improvement in release planning process.
   
 
 [4]. Regnell, Björn, and Sjaak Brinkkemper. "Market-driven requirements engineering for software products." .
 
 This article discusses about the process of market-driven requirements. In this the roadmapping concept is useful for this release planning assignment. A document which consists of product releases in the future is saidto be roadmap. As in this article the authors discussed there are four phases in roadmapping. The roadmap process consists of four phases, they are: initiation, preparation, finalization and follow-up phases.<br>
The initiation phase consists of forming a team for roadmapping, then knowing the strategies and pre-conditions for the roadmapping and setting a context.<br>
The preparation phase consists of themes priortizing and selecting and then determining a schedule and creating a roadmap.<br>
The finalization phases consists of validating the roadmap created in the above phase and demontrating this roadmap to the internal and external of the project teams.<br>
Then the final phase is follow-up phase in which the feedback can be collected and any changes or updates can be done to the roadmap.<br>


# About work done and release planning assignment

In this week we did prirotizing the requirements, as we planned a meeting for release planning assignment. In this meeting, we discussed regarding the technique for priortization and criteria on which basis to be priortized. The technique used for priortizing the requirements is grouping technique in which MoSCoW method is used. That is requirements are categorized into Must have, Should have, Could have, Wont have. The criteria used for priortizing is customer value for the requirements. Also the release planning is based on some concept in Art and Science of release planning article. That is Goal for milestone is considered for priortizing the requirements. Then the requirements which need for further implementation also considered i.e. for example to have a login feature there must be system user id available. So system user id is priortized before then login is priortized.

Then the issues are assigned by each member based on their interest. Then labels are classified again as there may be wrong labels assigned. After these the milestones are also assigned to the requirements by the member who is responsible/assignee for the requirement. <br>

As i assigned 13 issues to myself the milestones and labels are assigned by me. They are as follows in the below link. <br>
https://github.com/mickesv/LSRE-ReleasePlanningProject/issues/assigned/akshaymagapu  <br>

As members said the milestones will be assigned by their own to their assigned issues, so i only assigned milestones to the 13 issues which are assigned to me.

And for each milestone there is a goal and the issues assigned for each milestone can viewed in the following document: <br>
https://drive.google.com/file/d/0Bz_7Gx1hn6L9ZmhOalZhbEx0NjQ/view?usp=sharing   <br>
The list in the above document consists of the issue number in the GitHub. <br>
As these are categorized into Must, Should, Could, Wont for each milestone. As this is the way of roadmapping the product, as it consists of different milestones and features which are added to the product in future can be known through this document.

* The priortization issue is solved by the article [1] so that the techniques used for priortization are noted and the best suitable one is selected. Even though the grouping technique is suitable for priortization but without dependenices of requirement it may contain some wrong categorization so this problem can be mitigated through knowing the dependencies between requirements. <br>

* The dependencies issues can be solved by the article [2] as there are several types of dependencies and by following this we can make effective release planning. Eventhough for this release planning assignmenet the interdependencies are not determined in this way, just dependencies are determined. So if this technique is used it would be more effective. The problem with this technique is that this is a complex task for determing the pairwise assessment of requirements as for large scale there is a need of knowing interdependencies between more than 20 requirements so this method may be very complex to implement. <br>

* The purpose of each release plan issue is solved by article [3] as setting goal for each milestone(release plan) simplifies the distribution of requirements. The problem is the goal should be very detailed enough so that the abstract goal can be not implemented. So this can be mitigated by defining a detailed goal for each release plan[3]. <br>

* The roadmapping concept is learned from the article [4] it explains clearly about what is roadmap and uses of it. So for this release planning roadmapping is done as the six milestones are created between dec 2015 to nov 2016. 

By this release planning assignment, i understand that each release plan should have a goal that is improvement from before release plan.Also release planning is not an easy task there are certain things to be considered like dependencies, different levels of requirements, vague requirements. As i felt that the release planning assignment should need more active participation from all the members so that it can be very effective to do the release planning.

# References

[1] Berander, Patrik, and Anneliese Andrews. "Requirements prioritization." Engineering and managing software requirements. Springer Berlin Heidelberg, 2005. 69-94.

[2] An industrial survey of requirements interdependencies in software product release planning." Requirements Engineering, 2001. Proceedings. Fifth IEEE International Symposium on. IEEE, 2001.

[3] Ruhe, Günther, and Moshood Omolade Saliu. "The art and science of software release planning." Software, IEEE 22.6 (2005): 47-53.

[4] Regnell, Björn, and Sjaak Brinkkemper. "Market-driven requirements engineering for software products." Engineering and managing software requirements. Springer Berlin Heidelberg, 2005. 287-308.

[5] Khurum, Mahvish, Khurum Aslam, and Tony Gorschek. "A method for early requirements triage and selection utilizing product strategies." Software Engineering Conference, 2007. APSEC 2007. 14th Asia-Pacific. IEEE, 2007.

[6] Wnuk, Krzysztof, Tony Gorschek, and Showayb Zahda. "Obsolete software requirements." Information and Software Technology 55.6 (2013): 921-940.
