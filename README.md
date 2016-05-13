#Welcome to my data sets
I made these files to play with [Tableau software](http://www.tableau.com/), but feel free to use with any other software.

Most files are available in CSV and/or JSON format.

If you find something useful, please [let me know](http://alexandre-mille.com/#Contact).

Current Project(s) :
+ [MLS Salaries](https://github.com/alexmille/DataSets/tree/master/MLS-Salaries)

_______

#MLS Salaries
Major League Soccer players salaries from 2007 until 2015 :
+ Source : [Major League Soccer Players Union website](https://www.mlsplayers.org/salary_info.html)
+ Raw data extracted from pdf files with [Tabula](http://tabula.technology/)
+ Cleaned with [OpenRefine](http://openrefine.org/) and Excel

##Available Files :
###Salaries
+ [salaries.csv](https://github.com/alexmille/DataSets/blob/master/MLS-Salaries/salaries.csv)
+ [salaries.json](https://github.com/alexmille/DataSets/blob/master/MLS-Salaries/salaries.json)

**Example :**

|Header              |Example           |Description                                                           |
|--------------------|------------------|----------------------------------------------------------------------|
|SalaryShortClub     |SEA               |Team (Seattle in example). **Foreign Key** (PK in **mlsTeams** table) |
|SalaryLastName      |Doe               |Last Name                                                             |
|SalaryFirstName     |John              |First Name                                                            |
|SalaryName          |John Doe          |First & Last Name concatenated                                        |
|SalaryPos           |GK                |Position (goalkeeper in example)                                      |
|SalaryBaseSalary    |200000.00         |Annual salary (in USD)                                                |
|SalaryCompensation  |250000.00         |Annual salary including bonuses (in USD)                              |
|SalaryDate          |July 10, 2008     |                                                                      |
|SalaryYear          |2008              |                                                                      |
|SalaryMonth         |July              |                                                                      |
|SalaryMonthYear     |Jul-08            |                                                                      |
|Designated Player   |Designated Player |Acts as a flag. Blank if not a designated player                      |
|Remarks             |                  |Additional information                                                |

###Teams
+ [mlsTeams.csv](https://github.com/alexmille/DataSets/blob/master/MLS-Salaries/mlsTeams.csv)
+ [mlsTeams.json](https://github.com/alexmille/DataSets/blob/master/MLS-Salaries/mlsTeams.json)

**Example :**

|Header              |Example           |Description                                                           |
|--------------------|------------------|----------------------------------------------------------------------|
|Short               |CHV               |Team (Chivas in example). **Primary Key** (FK in **mlsTeams** table)  |
|Team                |Chivas USA        |Team Full Name                                                        |
|City                |Carson            |Where are they playing ?                                              |
|State               |California        |In which State ?                                                      |
|Country             |USA               |US or Canada ?                                                        |
|Stadium             |StubHub Center    |Current Stadium                                                       |
|StadiumLatitude     |33.8643414        |Stadium Latitude                                                      |
|StadiumLongitude    |-118.2611082      |Stadium Longitude (but you guessed it, didn't you ?)                  |
|Conference          |Western Conference|East side Vs West side                                                |
|Joined              |2005              |When did this team joined the League ?                                |
|Active              |N                 |Is this team still active ? Y for yes, N for no                       |
|Defunct             |2014              |This team ceased to exist that year                                   |
