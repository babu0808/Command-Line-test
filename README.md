# Command-Line-test
Command line test is a project based on bash scipts .sh
LS Project
 Command Line Test
1.print 3 options for user
1.sign up
2.sign in
3.Exit
1.sign up:
sign-up successfully
1.sign up
2.sign in
3.exit
--> echo $user_name >> user_name.csv
then again print that 3 options-->
so that user can select sign in
option.
2.sign in:
--> user_arr=(`cat user.csv`)
1.read user name
2.store all user names from user_name.csv file
3.check user_name = user_arr[i]
if matches-> print error. then again ask
user name.
if no->store user name in user_name.csv file
for password and conf. password
4.check both passwords are matching or not.
 if yes->then print
--> password_arr=(`cat password.csv`)
pooja
anjali
megha
ram
123_p
an_789
megha@
1234_r
user_name.csv password.csv
1.read user name
2.check with user names store in file
if [ user_name = user_arr[i] ]
-> if no matches: then ask for user name again.
store all previous passwords in arr
-> matches: then ask for password
3.check i'th index password is matching with
entered password or not.
-->not matching then print error, ask for user
 name again.
--> matches then print
sign in successfully
then conduct the test.
3.Exit:
in this part give a command--> Exit
 that will terminate the process.
--> -s(option to read in hidden mode).
if no matches-> ask for password again.
Test Conduction:
once the sign in process is complete then ,
a
b
c
a
d
b
a
c
a
b
c
question.csv correct_ans.csv user_ans.csv
create a file for storing some 10 questions, one for correct answers, and onther for storing
 the user entered answers.
1.Take the test
2.exit
1.Take the test:
once you print sign in successfull, print 2 options for user
for i in 5 5 50
do
head -i file | tail -5
for j in `10 -1 1`
do
read -t 1 option
done
done
1.print first question on the screen from file
use loop to print one by one.
2.after printing que. run a loop to read answer
from the user in 10 sec.
3.read in -t 1 for setting timer.
4.then check condition whether user has entered
 any input or not.
-> if yes then break the loop
-> no then store "e" in option
then store the option in user_ans.csv file one by one.
5.after reading user answer for 10 questions,
then evaluate:
print first question then
 by comparing user_ans and correct_ans
by storing those two file content into two arrays.
if both will match--> print
correct answer
and count for correct answers
if option is "e" then print
Timed out
if no matches then print
Wrong answer
Like that print each question again with the result.
--> at Last print the obtained marks
obt.marks/total marks
1.what is the command for read?
a)echo
b)read
c)ls
d)cat
2.what is the command for print?
a)ls
b)read
c)echo
d)cat
Sample result:
1.what is the command for read?
a)echo
b)read
c)ls
d)cat
Correct Answer
2.what is the command for print?
a)ls
b)read
c)echo
d)cat
Wrong Answer
Total morks obtained: 8/10
No match
Entered then
opt=ent. opt
Not entered then
opt=e
Print each question along with result
Evaluate all answers
Read user name
Read password
Read conf. password
yes
no match
Sign in successfully
sign-up successfully.
 Not
 Found
Not
Found
yes
Read username
Read password
1.take the test
2.Exit
Print question
Read option
1.sign-up
2.sign-in
3.exit
Wrong answer
Timed out
correct answer
Exit
Exit
