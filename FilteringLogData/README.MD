# Overview
Organisations use Indicator of Compromises (IoC) to identify that a security incident has occurred.  Log data is one of the indicators that may potentially help with identifying that a security incident has occurred or is occuring. Log data is usually stored in a database. SQL (Structured Query Language) can help the organisation to filter the log data from a database, thus, helping with identifying and investigating a breach.

Information Nugget: SIEM (Security Information & Event Management) tools can be used to ingest (consume) log data from various security controls and which can further allow to paint the picture of the organisation's security posture. 

## Steps I took to complete the activity:
1. Firstly, I examined what type of data is available within the database using [Table Format](/FilteringLogData/TableFormats.pdf) document.
2. Then I used SQL, to investigate the log-in activity of employees after office hours (0900-1800).
3. After this, I investigated my colleague’s alert on 2022-05-09.
4. Finally, I ran the SQL query to make the list of machines from various departments that require an update and document the process in [Filtering Log Data](/FilteringLogData/FliteringLogData.pdf) file.

## Case Study
You are a security professional at a large organisation based in Mexico. Part of your job is to investigate security issues to help keep the system secure. You recently discovered some potential security issues that involve login attempts and employee machines.
A member of your team tells you that they noticed a similar unusual login activity on 2022-05-09 and would like you to investigate it further. 
Your team noticed that some machines in some department needed an update. The team wants to perform security updates on employee machines in the Marketing department in East block, Sales, Finance departments. Therefore, they would like you to make a list of all the machines within these departments.
