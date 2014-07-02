===========
Future work
===========

Many new features can be added in future in this project.The edx software which we used in our project , didn't have any hint option.The frequency with which a student uses hint can be of great help in determining whether a student is gaming or not.For example , if a student is using hints in all questions , that means he is gaming and is doing the course on;y get a certificate.Another case can be , how quickly is he taking hint on a particular question.It is apparent that if he is quickly clicking on hint button to get the next hint , he is not utilizing previous hints to answer the question.Secondly if we could utilize the actual database of edx  then we would have many other information such as how total number of module in  a course , which video is related to which set of questions.These things could help us determine which student watched video first and which student attempted questions first.This could be of great use.Thirdly , we have not taken into account the fact that a student could have watched same video many times.We are simply taking sum of the time , a student has actually watched videos.We can also include factors such as hoe many times a video has been loaded by that student and how what is the maximum length of video which he has seen.This should be updated only when that student watches that video which exceeds that time.
Next thing is that we have used WEKA software to implement machine learning.Our next aim is to write programs of machine learning on our own so that it will apply to our case in the best way.And the last thing is the intervention.The system which which we have designed is runtime.That is the log entries are parsed as they are coming into the log file.So we can determine at that particular time that these students are gaming the system and we can take some actions against only those students.We are looking forward in future to implement this system and turn this system to a fully working system , which can practically be applied to ITS in order to control the gaming of the systems.


==========
Conclusion
==========

We have designed a system , which given the log entries of edx , can determine whether a student  is gaming or not.This system , if implemented by ITS will help them in creating trustworthy courses.ITS can ensure that certificates are assigned to only those students who have completed their course honestly without gaming.The system can be of great use in future and will surely find its place in ITS.This project can be improved greatly , if we can utilize many other information of edx database.We are looking in future to implement many more features as well as include the interventions in the proper way doc.

==========
References
==========

| 1. Off-Task Behavior in the Cognitive Tutor Classroom: When Students “Game the System”
|    Ryan Shaun Baker, Albert T. Corbett,Kenneth R. Koedinger, Angela Z. Wagner Human-Computer Interaction Institute, Carnegie Mellon University Pittsburgh, PA, USA
|    http://www.columbia.edu/~rsb2162/p383-baker-rev.pdf

| 2. Detecting Student Misuse of Intelligent Tutoring Systems
|    Ryan Shaun Baker, Albert T. Corbett, Kenneth R. Koedinger Human-Computer Interaction Institute, Carnegie Mellon University, 5000 Forbes Avenue, Pittsburgh, PA, 15217, USA
|    http://www.columbia.edu/~rsb2162/BCK2004MLFinal.pdf

| 3. Apache Hive documentation
|    https://cwiki.apache.org/confluence/display/Hive/Home#Home-UserDocumentation

| 4. Apache Hadoop documentation
|    http://hadoop.apache.org/docs/r0.18.2/

| 5. Apache Sqoop documentation
|    http://sqoop.apache.org/docs/1.4.1-incubating/

| 6. Setting up single node and multi node cluster on ubuntu platform using hadoop
|    http://www.michael-noll.com/tutorials/running-hadoop-on-ubuntu-linux-multi-node-cluster/

| 7. Habits of Effective Sqoop Users
|    Kate Ting, Customer Operations Engineer, kate@cloudera.com
|    sqoop_meetup_kate_ting_110711.pdf

| 8. Edureka video tutorials
|    2013-12-09 08.04 Big Data and Hadoop class 1.mp4
|    2013-12-10 08.03 Big Data and Hadoop class 2.mp4
|    Module-1 Assignment - Number of Data Node Calculation.pdf

| 9. Edx database schema and log events format
|    Student Information and Progress Database:
|    http://edx.readthedocs.org/projects/devdata/en/latest/internal_data_formats/sql_schema.html
|    Tracking log:
|    http://edx.readthedocs.org/projects/devdata/en/latest/internal_data_formats/tracking_logs.html#video

| 10. Book: Hadoop - The Definitive Guide
