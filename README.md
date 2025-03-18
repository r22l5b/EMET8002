java c
EMET8002 Case Studies in Applied Economic 
Analysis and Econometrics 
Semester 1 2025 
Computer Lab in Week 5 This   week   we   continue   to   use   the   2015   Programme   for   International   Student   Assessment   (PISA)   dataset   for   our   analysis.   PISA   assesses   skills   of   15-year-old   students   across   many   countries and involves data on student performance (reading, mathematics and science   knowledge), as well as parent, school and teacher questionnaires. The data is publicly available   and   can   be   downloaded   from   the   PISA   website   under   the   section   “SPSS   (TM)   Data   Files   (compressed)” (https://www.oecd.org/pisa/data/2015database/). However, these are large files   and   take   some   time   to   download   and   convert   to   Stata   format.   Therefore,   we   have prepared   a   smaller   merged   dataset   of the   Student   and   School   questionnaire   data   files   which   now   only   includes   the relevant   variables.   You   can   download   this   data   (“Week4_PISA_data.dta”)   from   Wattle.
Question 1: Multinomial Logit Regression 
We will run multinomial logit models with the following categorical variable as the   dependent variable: “org_type” (“What kind of   organisation runs your   school?”).
(a)   Exclude missing values for the following variables: repeated, school_size, age,   male,   international_lan, mother_edu, father_edu, quiet_study, good_listener, add_math, class_size, computer.
(b)   Tabulate the variable “org_type”. How do you interpret the output? Create   a   label   for   the variable and values of   “org_type” to make interpretation easier and   tabulate   the same variable again.   [Hint   1   : -1 is coded for   missing   data,   1   means   “A   church   or   other   religious organisation”, 2 means “Another not-for-profit organisation”,   and 3   means “A   for-profit   organisation”; Hint   2: type   in “help   label” in   Stata   for   more suggestions].
(c)   Run a multinomial logit regression with “org_type” as the dependent variable   and the   following   independent   variables: “male”, “age”, “international_lan”, “mother_edu”,         “father_edu”.   Since   the   independent   variables   may   contain   missing   values, include dummy variables that are equal to   1 if   there is   a missing   value   and   0   otherwise.   [Hint:   see “help mlogit” for   suggestions] 
(d)   Why does   Stata omit the following two dummy variables: “male_m”   and   “age_m”?
Run the multinomial logit regression from part c without these two dummy variables.
(e)   Calculate the relative   risk ratios. How do you interpret the output?   [Hint: see   “help   mlogit” for suggestions]
(f)    Calculate predicted probabilities for a student to be at   a   church   school,   at   a not-for- profit organisation and at a for-profit organisation   if   they   are   (i) male   and   15 years old, (ii) female and   15 years old, (iii)   male   and   16   years   old,   and   (iv)   female   and   16 years old. How do you interpret the output?   [Hint: see   “help   margins”   for   suggestions]
(g)   Compute the marginal effects for the “male” variable   for each of   the three possible outcomes   ofthe   dependent   variable   (church   school, not   代 写EMET8002 Case Studies in Applied Economic Analysis and Econometrics Semester 1 2025 Week 5
代做程序编程语言for   profit   organisation,   or   for    profit organisation). How do you interpret the estimated coefficients?   [Hint:   see   “help   margins” for suggestions] 
(h)   How are predicted probabilities and marginal effects related?
Question 2: Ordered Logit Regression For this question we use the variable “good_listener” as our dependent variable.   This   is   a categorical variable   which ranges between   1 and 4 with   1 being a poor listener and   higher   values indicating higher listening abilities.
(a)   Explain how this dependent variable is different from “org_type” in   Question   1   and   why we would use an ordered logit regression in this case.
(b)   Tabulate the variable “good_listener” and interpret   the table. What does the value   -1   mean?
(c)   Run an ordered logit regression with “good_listener” as the   dependent variable   and
the following independent variables: “male”, “class_size”, “computer”, “international_lan” and “age”. How   do   you   deal   with   missing   values   in   the   dependent and independent variables? Interpret the output.   [Hint: see “help ologit”   for suggestions]
(d)   Compute odds ratios for the same regression as in part   c.   How   do you   interpret the   output?   [Hint: see “help ologit” for   suggestions]
(e)   Calculate   predicted   probabilities   for   each   of   the   four   possible   outcomes   of “good_listener” for   males   versus   females. Interpret   the   output.
(f)    Do a Brant test to check if   the assumption of   proportional   odds   that   is   required   for   an   ordered logit model holds. Would you still use an ordered logit model?   What   are   the      alternatives?   [Hint: see “help brant” for suggestions. Most likely, you will need   to install the package spost13_ado.pkg, which you can find by typing “findit   spost13_ado” in   Stata] 
Question 3: Preparation for Research Project [not required for problem set] 
We strongly recommend that you have chosen a paper by now, as the research   proposal is due at the end of   week 6, and the   data   collection process   can   also take   some   time.   Students are also expected to have started the data application   process by   now.   If   you   are unsure   of   the process, ask   for help. 
(a)   Will you need any additional data for your extension?   This   is   optional,   as   some   extensions can be done using the same data as   for your replication.
(b)   In small groups, discuss what extensions you are   planning   for your research projects   and why they are meaningful, interesting and worth investigating.   Give feedback   to each other about ways to improve the motivation of   your extensions.
(c)   Discuss the ethical issues and errors associated with the use   of   AI-assisted technologies. Note that for this course, the use of AI tools constitutes a breach of academic integrity. (The only exception is when   students use   Chat   GPT   or   other AI tools when proof-reading, in which case this needs to be disclosed   in   a   statement   at the end of   your assignment, and you may be asked to   provide   drafts   from before   and   after   the   proof-read). If   you   are   unsure   of   what   is   appropriate, ask   for   help.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
