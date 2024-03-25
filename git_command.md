

$ npm i react-router-dom

$ nvm list available

$ nvm install 16.20.2 
    For my case, I had to downgrade from node v18 to v16. 
$ npm i express@

# How to install nvm on MAC 
$nvm list availbale
# zsh: command not found: nvm 오류해결법
    열심히 뒤지던 중, bash shell에서는 nvm 명령어를 제대로 인식하지만, mac의 default shell인 zsh에서는 nvm을 인식하지 못하는 문제가 있을 수 있다는 정보를 찾아냈다.
    $ :qa(빠저나가기)
    $ git clone https://github.com/nvm-sh/nvm.git ~/.nvm
    $ source ~/.nvm/nvm.sh

# 사용하려는 버전을 다음 명령어에  
    $ nvm use 16.18.1
# Error 발생시 
    fatal: not a git repository (or any parent up to mount point /Volumes)
    Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).

# 이메일을 벨리드하지않거나 && 이메일의 길이가 0보다 클때 두가지사항을 만족할때 에러 내용을 뛰어준다. 
     {
        !emailValid && email.length > 0 && (
        <div>올바른 이메일읃 입력해주세요. </div>
     )}