# 3th hour 

how to know the difirace between woring tree and staging tree  <br>
by "git diff" <br>

and when get diff between staging and repo
we use "git diff --staged"

to show the diff in one step use ==> <br>
"git show >first 5 char from cha of commit< " we can get cha form "git log" <br>

to make a tracked file to untracked we use  <br>

"rm --cached >file name < "<br>

to cancel a modify form file we use <br>
"git restore >file name <" ==> actually git is restore the file from satging<br>

and use "git restore --staged >file name <" form repo <br>

when i want back to another commit we use "hit reset head~>number of back <"<br>

then the commit will be on staginf tree but if set it direct to working tree 
we use  "--hard" 
