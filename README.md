# Auto_System_Time-Updater_Windows



#Whats The Problem?

When my old laptop's CMOS  batteries drained on every startup my pc time needs to be updated manually. Major problem with wrong time and date is chrome does not allow https usage and shows <strike>https</strike>




#Solution

I created a .cmd file containing following command



w32tm /resync



And I just scheduled a task to run that .cmd file on every startup because the command needed admin privileges to run this command.
the updatetime.cmd is included in repository

#How to schedule task ?

go to link

http://windows.microsoft.com/en-in/windows/schedule-task#1TC=windows-7

and it works well unless you have a net connection.


