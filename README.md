#Laby
#Name of repo: Laby
Tasks:
1. Each programming task requires using at least one new pattern.
2. Code should be well commented (method descriptions, hard reading and big
code…).
3. There should not be dead code.
4. All entities should have meaningful names.
Tool requirements
1. Command line with input parameters
a. -sf, --seqfile - SF location
b. -s, --sequence - sequence formula when file not provided
c. -n, --number - sequence elements quantity to generate
d. -h, --help - user help
e. -v, --version - tool version
Note: If Both parameters are present (-sf, --seqfile and -s, --sequence) then new SF
should be generated.
2. Can load file with sequence description from Table 1. Tasks by students
3. Can generate sequence into .csv file.
Required steps for all tasks except task# 1,4:
1. Add/modify UTs where applicable.
2. Create/Modify the ci script to build, test and run project.
3. Commit changes to feature/develop/<task number>.
4. Update README with details:
∙ how to build project;
∙ how to run project;
∙ Version number.
5. Create GIT TAG:
<PROJECT NAME>_<task number>_<VERSION>_ww<YYWWD>
∙ YY – current year;
∙ WW – work week;
∙ D – current day number of weak.
6. Create pull request with name <task number> and submit author as reviewer.
7. After the reviewer approved – merge into the develop branch.
Acceptance criteria:
Project in the develop branch.
