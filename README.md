# Database
# how to restore out data to github

June@DESKTOP-GV9J5V8 MINGW64 ~/Desktop/2022-1/biodatabase/biodatabase (master)
$ git init
Initialized empty Git repository in C:/Users/chan/Desktop/2022-1/biodatabase/biodatabase/.git/

June@DESKTOP-GV9J5V8 MINGW64 ~/Desktop/2022-1/biodatabase/biodatabase (master)
$ git add .
warning: LF will be replaced by CRLF in GSE176348.top.table.tsv.
The file will have its original line endings in your working directory

June@DESKTOP-GV9J5V8 MINGW64 ~/Desktop/2022-1/biodatabase/biodatabase (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   GSE176348.top.table.tsv
        new file:   log_FC_up_down_list.txt
        new file:   log_FC_up_down_list.xlsx
        new file:   midterm_report.hwp
        new file:   midterm_report.pptx
        new file:   new.xlsx
        new file:   sample_down.xlsx
        new file:   sample_up.xlsx
  
June@DESKTOP-GV9J5V8 MINGW64 ~/Desktop/2022-1/biodatabase/biodatabase (master)
$ git commit -m "first upload"
[master (root-commit) b3754a1] first upload
 8 files changed, 37023 insertions(+)
 create mode 100644 GSE176348.top.table.tsv
 create mode 100644 log_FC_up_down_list.txt
 create mode 100644 log_FC_up_down_list.xlsx
 create mode 100644 midterm_report.hwp
 create mode 100644 midterm_report.pptx
 create mode 100644 new.xlsx
 create mode 100644 sample_down.xlsx
 create mode 100644 sample_up.xlsx
  
June@DESKTOP-GV9J5V8 MINGW64 ~/Desktop/2022-1/biodatabase/biodatabase (master)
$ git remote add origin http://github.com/river6907/Database.git

June@DESKTOP-GV9J5V8 MINGW64 ~/Desktop/2022-1/biodatabase/biodatabase (master)
$ git push -u origin master
warning: redirecting to https://github.com/river6907/Database.git/
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 16 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (10/10), 14.62 MiB | 4.36 MiB/s, done.
Total 10 (delta 0), reused 0 (delta 0), pack-reused 0
To http://github.com/river6907/Database.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
 
  
// finish -> check repositary
