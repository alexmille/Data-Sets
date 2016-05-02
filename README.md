#Data Sets
I made these files for my experiments with [Tableau software](http://www.tableau.com/), but feel free to play with any other software. 

Most files are available in CSV and/or JSON format and under the _WTFPL_ license.

If you find something useful, please [let me know](http://alexandre-mille.com#contact).

Current Projects :
+ [MLS Salaries](https://github.com/alexmille/DataSets/tree/master/MLS-Salaries)
+ James Bond Movies

_______

##MLS Salaries
Major League Soccer players salaries from 2007 until 2015 :
+ Source : [Major League Soccer Players Union website](https://www.mlsplayers.org/salary_info.html)
+ Raw data imported with [Tabula](http://tabula.technology/) 
+ Cleaned with [OpenRefine](http://openrefine.org/) and Excel

###Available Files :
####Salaries
+ [salaries.csv](https://github.com/alexmille/DataSets/blob/master/MLS-Salaries/salaries.csv)
+ [salaries.json](https://github.com/alexmille/DataSets/blob/master/MLS-Salaries/salaries.json)

**Example :**

|Header              |Example           |Description                                                           |
|--------------------|------------------|----------------------------------------------------------------------|
|SalaryShortClub     |SEA               |Team (Seattle in example). **Foreign Key** (**mlsTeams** table PK)    |
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

####Teams
+ [mlsTeams.csv](https://github.com/alexmille/DataSets/blob/master/MLS-Salaries/mlsTeams.csv) 
+ [mlsTeams.json](https://github.com/alexmille/DataSets/blob/master/MLS-Salaries/mlsTeams.json) 







