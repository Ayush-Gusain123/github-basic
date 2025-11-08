1)'git init'=>powers your folder tobe managed by git, and initialised a new empty repoit .
it also create  a.git folder that has all the relevent logic to manage version of your code.
2)'working area ->there can be bunch of file that not currently handled by git..
 it means that changes done or to ne done in those files are not managed by git yut.
 a file which is in working area is consideredto be not in the staging area.when  we do git status and we see abunch 
 if untracked files these are actually called to be in the wokring area,.
 3)stagging area->what all files are going to be part of next version that we create
 this stagging area is the place where git know  what changes will be done from the last version to the next version 
 4)repository area->this area actually contains the details of all you perivious registered version .
 and the files in this area git already manages them and known their version history 
 5)git add<file>->moves files from working to stagging area
 6) gir rm --cached<files>->moves files back from syagging area to woking area
 7) commit-> it is a particular version of the project it capture the snapshort
  of the project staged cahnges and create a version out of it
  8) git commit->registered staging changes to comit;
  9)git log->list down alll the comiy of all repo. if u want to exit out of git log prompt press'q'
  10)git restore<file>-> it remove all the file changes from the stagging area to comiited.
ayush 1
  ayush
  piyush
  gusain