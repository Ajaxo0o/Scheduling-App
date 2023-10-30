# Scheduling-App
## Project Overview:
This app/website is designed to help our substitute coordinator at school organize a schedule for teachers to cover other teachers who are out for the day. 
In this specific use case; 
  - A teacher has 4 blocks to cover each day.
  - Each teacher has 3 blocks where they are teaching a subject and one block for planning. 
  - Each block is 90 minutes.
This means when a teacher is out for the day, and needs coverage, there are 3 teaching blocks where students are present that must be covered.
Considering each teacher has a planning block, 3 teachers who's planning blocks line up with the coverage need could be used to cover for the absent teacher. 

## This app will: 

  - Store all teacher names and planning periods for the semester. 
  - Allow the user to enter the teacher’s name who needs coverage and the app will identify which planning he/she has and which 3 blocks need to be covered.

With the teacher data entered and the blocks that need coverage identified, the app will create a list of teachers who are available to cover each block according to their data that was retrieved from an array of names and planning periods.
The user will be able to see a drop down list of teachers who are available for each block that needs a sub, then will be able to click on one of the names so that that name will fill that position. Then, will be able continue to do the same for the other two blocks that need coverage.
The user will then do this for each teacher who needs coverage for the day and names that were used to cover one teacher will be removed from the array so the user doesn’t accidentally assign a teacher to more than one class for coverage that day.
When the list of teachers is populated, the user will be able to send a print request to print out the list.
