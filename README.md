# productivity_tracker
#OVERVIEW
A simple, beginner-friendly, Python-based weekly productivity tracker that helps the user track their productivity by collecting tasks, arranging them in priority order, and providing a weekly report. The report includes feedback and tips for the user, which help them improve and be more productive.
Planning weekly tasks, prioritizing work and being productive at the same time is hectic and many face difficulties to do so. This program gives a simple solution to these by giving the following features:
•adds weekly tasks
•sets deadline
•marks completed tasks
•sorts tasks according to the deadline
•calculates productivity
•gives small tips and motivations to keep going
#OBJECTIVES
•To build a productivity tracker tool using python
•To apply basic concepts learned in the flipped course
•To display a weekly report based on user's performance
#FEATURES
1) Task input system:
•User can input the deatils of his tasks.
•Each task has task name, deadline,priority.
2) Sorting based on deadline:
•All tasks are sorted automatically using
tasks=sorted(tasks, key=lambda x:x["deadline"])
3) Priority color coding:
   High=Red, Medium=Blue, Low=Magenta
4) Calculation of productivity:
   Productivity is calculated using
   (tasks completed / total tasks)*100
5) Rating system
   Rating and message are displayed with colors based on performance of user.
6) Tips to improve
7) Weekly report output
   The output includes name of the user, total, completed and remaining tasks, productivity percentage, ratings, color coded task list and timline.
#SCREENSHOTS
All related screenshots are stored in /screenshots folder.
