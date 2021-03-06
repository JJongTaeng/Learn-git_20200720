# git
``` 스스로 공부한 내용이라 잘못된 부분이 있을 수 있습니다. ```

- git bash 다운로드

  - git bash를 다운한다.
  - [git bash 다운로드 링크](https://gitforwindows.org/)

<hr>


- git 명령어 (로컬환경)
  - git init : git을 생성<br>
   ![gitinit](./images/gitinit.PNG)

  - git config --global user.email 'e-mail' : git 계정 메일을 변경<br>
   ![gitemail](./images/gitemail.PNG)

  - git config --global user.name 'e-mail' : git 계정 이름을 변경<br>
   ![gitname](./images/gitname.PNG)  

  - git add [filename] :  변경 및 생성된 파일 및 폴더 선택<br>
   ![gitadd](./images/gitadd.PNG)

  - git commit -m '**content**'<br> : add로 선택한 내용에 대해 저장<br>
   ![gitcommit](./images/gitcommit.PNG)

  - git status<br>
   ![gitstatus](./images/gitstatus.PNG)

  - git branch : 로컬 repository에 있는 branch 확인<br>
   ![gitbranch](./images/gitbranch.PNG)
  
  - git branch -d [branchname] : branch 삭제
  
  - git branch [branch_name] : branch name으로 새로운 branch 생성<br>
   ![gitbranchname](./images/gitbranchname.PNG)

  - git checkout [branch_name] : branch 변경<br>
   ![gitcheckout](./images/gitcheckout.PNG)
  
  - git reset --hard [revision번호] : git log의 commit 시점으로 이동(변경 이후의 로그 삭제)<br>
  - git reset --soft [revision번호] : git log의 commit 시점으로 이동(변경 이후의 로그가 삭제되지 않음)<br>

- git 명령어 (서버 <-> 로컬)
  - git clone [url] : github 서버에 있는 repository를 복사<br>
  ![gitclone](./images/gitclone.PNG)
  
  - git push origin master : 로컬에서 변경된 내용을 서버로 전송<br>
  ![gitpush](./images/gitpush.PNG)

  - git pull : 서버에서 변경된 내용을 로컬로 복사<br>
  ![gitpull](./images/gitpull.PNG)
  