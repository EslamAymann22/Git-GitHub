# tools 

* we use "git add ." --> to add all file and changes to staging tree <br> 
* ~   ~  "git cinfig --list" to know data of user <br>
* ~   ~  "git mkdir >name of folder<" to make new folder <br>
* ~   ~  "git inti" to make folder to repo<br>
* ~   ~  "git status" to know status of files in my repo<br>
* ~   ~  "ls "to show content in working tree   <br>
* ~   ~  "git ls-files "to show content in staging(index) tree   <br>
*         =>> use -s to show with size <br>
*         =>> use -t to show with type <br>
*        =>> use -p to show with content <br>
*         another things in the git help <br>

* we can use "git status -s"==> is more simple<br>
* we use "git commit -m ">message<" " to commit files from staging to git with message <br>

* how to know the difirace between woring tree and staging tree  <br>
by "git diff"<br>

* and when get diff between staging and repo
we use "git diff --staged"

* to show the diff in one step use ==> <br>
"git show >first 5 char from cha of commit< " we can get cha form "git log" <br>

* to get diff between 2 commits we use <br>
"git diff  "<br>

* to make a tracked file to untracked we use  <br>

"rm --cached >file name < "<br>

* to cancel a modify form file we use <br>
"git restore >file name <" ==> actually git is restore the file from satging<br>

* and use "git restore --staged >file name <" form repo <br>

* when i want back to another commit we use "hit reset head~>number of back <"<br>

then the commit will be on staginf tree but if set it direct to working tree 
we use  "--hard" 

* to make a specific commit to marked or i mean give it a name <br>

* we use "git tag -a > nickname < -m > short message < "<br>