#  git 초기화 
    git init
    git config --global user.name "kchstar_outlook_com"
    git config --global user.email "kchstar@outlook.com"
# REMOTE 경로 재 설정
    $ git remote set-url origin https://github.com/kchair777/inbrozz_demo.git
    $ git add * / git add --all / git add . 
    $ git commit -m "first commit"[Git] 로컬 저장소에 Commit하기
    [Git] 로컬 저장소에 Commit하기

    $ git branch 
        ex) main
        ex) origin 
    $ git remote add origin https://github.com/kchstar/react-hooks-demo_2.git
    $ git push -u origin main (x)
    $ git push --set-upstream main main
    $ git log (반영사항 확인)
        git log나가기 = Q
    $ git reset a6f30a --hard (commit:6자리 / 이전상태로 되돌리기)

# (use "git add <file>..." to include in what will be committed)
    ex) git add * (all)
    ex) git add README.md

# git 명령어 
    $ git branch -v
    $ git 
# coding중간에 commit 순서
    $ git add .
    $ git commit -m 'commit '
    $ git push -u origin main    

# warning: in the working copy of 'git_command.md', LF will be replaced by CRLF the next time Git touches it
    LF(Line-Feed) 커서 위치는 그대로 두고 종이의 한라인 위로 올리는 동작 
    CR(Carriage-Return) 커서위치를 맨앞으로 옮기는 동작
    CRLF(Carriage-Return + Line-Feed) 두 동작을 합쳐서 커서를 다음라인 맨앞으로 옮겨주는 동작
        $ git config --global core.autocflf true

# Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
     (commit or discard the untracked or modified content in submodules)
        modified:   ../react-hooks-demo (modified content)
    $ ls
    $ rm -rf .git 
    $ git status
    $ git add .
    $ git commit -m '1st'
    $ git push -u origin main

# error: remote origin already exists.

# warning: adding embedded git repository: react-hooks-app_movie
    $ git rm --cached react-hooks-app_movie
    