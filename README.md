# git
``` 스스로 공부한 내용이라 잘못된 부분이 있을 수 있습니다. ```

- git bash 다운로드

  - git bash를 다운한다.
  - [git bash 다운로드 링크](https://gitforwindows.org/)

<hr>


- git 명령어 (로컬환경)
  - git init : git을 생성
   ![gitinit](C:\Users\Intae\Learn-git_20200720\images\gitadd.PNG)

  - git config --global user.email 'e-mail' : git 계정 메일을 변경
   ![gitemail](./images/gitemail.png)

  - git config --global user.name 'e-mail' : git 계정 이름을 변경<br>
   ![gitname](./images/gitname.png)  

  - git add [filename] :  변경 및 생성된 파일 및 폴더 선택<br>
   ![gitadd](./images/gitadd.png)

  - git commit -m '**content**'<br> : add로 선택한 내용에 대해 저장<br>
   ![gitcommit](./images/gitcommit.png)

  - git status<br>
   ![gitstatus](./images/gitstatus.png)

  - git branch : 로컬 repository에 있는 branch 확인<br>
   ![gitbranch](./images/gitbranch.png)
  
  - git branch [branch_name] : branch name으로 새로운 branch 생성<br>
   ![gitbranchname](./images/gitbranchname.png)

  - git checkout [branch_name] : branch 변경<br>
   ![gitcheckout](./images/gitcheckout.png)
  
  - git reset --hard [revision번호] : git log의 commit 시점으로 이동<br>

- git 명령어 (서버 <-> 로컬)
  - git clone [url] : github 서버에 있는 repository를 복사<br>
  ![gitclone](./images/gitclone.png)
  
  - git push origin master : 로컬에서 변경된 내용을 서버로 전송<br>
  ![gitpush](./images/gitpush.png)

  - git pull : 서버에서 변경된 내용을 로컬로 복사<br>
  ![gitpull](./images/gitpull.png)
  