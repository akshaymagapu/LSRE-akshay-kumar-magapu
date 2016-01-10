# Release Planning Assignment
#### Large Scale Requirements Engineering (PA2521)
#### Akshay Kumar Magapu
#### akma15@student.bth.se

### Release Planning assignment is about analysing the requirements and assigning these to a suitable release plans using requirement engineering techniques. This log consists of my activity in this release planning assignment.

## Week 46

# Work done :white_check_mark:

Started tracking issues commented on Course Chatroom #69 issue which is "Is this chatroom only for students or between teacher and students?"
The issue is clarified with both the participants can chat together or can have a private chat.

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
Made duplicates of issues #54, #29, #14 to issue #55 but got clarified that these are clarifications of the main issue.<br>

## Week 48

# Workdone :white_check_mark:

Linked depedencies of issues #65,#17,#36 to issue #9.<br>

Discussed in the group discussion forum about priortization as: I am familiar with planning poker, also we can use use-case points estimation technique as it is based on requirements and formula based approach without an expert opinion.
Replys came as whether planning poker is suitable for 5000 requirements. <br>

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
4. created a new issue that is a sub-requirement to RTF file upload.
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




## Week 50

# Work done :white_check_mark:

##Assigned myself to the following areas:

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
* Account activity #79
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
This technique is to categorize the requirements into critical, standard and optional. So based on these the requirements can be prioritized for release planning.<br>

The grouping technique is considerable technique when compared to other in large scale requirements. As in AHP the numer of comparisons increase it increases the complexity, while 100 dollar test has less probability while assigning 100 dollars to all requirements, topten requirements are not that much suitable in large scale if we consider 5000 requirements it is not a best method, Ranking may be the option but while giving ranks we need to fix whether we need to consider detail or abstract level requirements, whereas in grouping we need to classify requirements under critical, standard and optional as it is simple to do even in the case of large scale requirements. So i suggest to use grouping technique and we will discuss and group the given issues into following classifications for this release planning assignment.

## Labels

Assigned labels to the issues and i confused for the label clarification where i thought if we link sub-requirements to a requirement it gives more clarification so i added clarification label. But after a question raised by mickesv, i got clarity that the label should reflect the requirement only. So i changed the labels where i added clarification unnecessarily and also i added feature label to the feature requirements and enhancement label to the requirements which enhance the present functionality and bug label to some requirements.<br>

##Dependencies
For dependencies, we need to see the interdependencies between requirements so that the release plan can consist of a deliverable which will function, whereas if we did not consider the dependency then it may cause that a particular release plan may not consist a functional deliverable. I studied an article regarding this interdependencies, <br>
Carlshamre, Pär, et al. "An industrial survey of requirements interdependencies in software product release planning." Requirements Engineering, 2001. Proceedings. Fifth IEEE International Symposium on. IEEE, 2001. <br>
In this there are six types of interdependencies, they are AND, OR, REQUIRES, TEMPORAL, ICOST, CVALUE.
By this we need to take the top 20 prior requirements we need to find the interdependencies between them using above.

## New issues created are:

1.Register for exams #111 <br>
Students can register for exams based on their course.<br>
2. Database for projects #110 <br>
Students can retrieve the thesis articles and other projects that are carried out by final-year students. <br> 







