This set of input files were used for the simulations presented in the manuscript. Specifically, Projects_tasks.xlsx presents the 10 projects that must be scheduled. These projects comprise of 26 tasks, with a total of 240 FTEs (person-weeks), and the organization has 8 teams available that can work on these tasks. Further, each row represents a project with its score and set of tasks (along with the teams suitable to perform each task) that must be performed for that project. For example, to schedule project 1, two tasks must be performed, that require 7 and 10 person-weeks by teams 1, and 2, respectively.

Further, the files Personnel_cassign.xlsx, Personnel_rassign.xlsx, and Personnel_fassign.xlsx present the organization structure for scenarios Cassign, Rassign, and Fassign, respectively. In scenario Cassign the organization consists of 25 people assigned to the aforementioned 8 teams, and the current team configuration of the organization is presented in Personnel_cassign.xlsx (i.e., the number of people assigned to each team, as well as all the properties concerning each team). Further, in scenario Rassign (Personnel_rassign.xlsx), 17 people are assigned to the aforementioned teams, as 1 person from each team can potentially be reassigned. Finally, in scenario Fassign (Personnel_fassign.xlsx), 0 personnel are allocated to any team, all personnel can be reassigned by the proposed approach. Also, for each team f, the following information is provided (in each different column):

• Number of people in team (TM_f): The number of people assigned to team f (existing persons, without any new assignments).

• Priority: The priority that each team has when performing a task in a project. For example, if teams f_1 and f_3 must both work on a project, team f_1 must finish at most a% (equal to 75% for the simulations shown in our manuscript) of its task for team f_3 to start working on its own designated task. Also, tasks performed by teams f_7 and f_8 (that do not have a priority value) can be implemented without any task interdependencies. 

• TMH_f: The maximum number of people that can concurrently work on a task per team. 

• beta_f: The ratio of the number of people per task. This value is used within the proposed approach to determine the number of tasks (projects) that team f can work on per time slot. For example, if there is a total of 6 team members (existing and new assignments) allocated to team f , and beta_f = 3, then this specific team can work on at most 6/3=2 tasks (projects) per time slot.



