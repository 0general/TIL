## ◼ git branch -v   
> #### branch 확인


## ◼ git branch <name>
> #### branch 만들기


## ◼ git checkout <branch_name>
> #### branch 전환


## ◼ git merge <branch_name>
> #### branch 병합  
> <br>  
> 현재 branch에 이름이 <branch_name>인 branch의 변경사항이 반영됨  
> ※ HEAD-내가 현재 작업중인 branch를 가리킴  


## ◼ git branch -d <branch_name>
> #### branch 삭제


## ◼ git branch -M <edited name>
> #### branch 이름 바꾸기


## ◻ git remote add <별칭> <원격 저장소 주소>
> ####원격 저장소와 로컬 저장소 연동
> add 는 원격저장소를 등록한다는 의미  
>별칭은 보통 origin을 많이 쓴다.  


## ◻ git remote -v
> #### 연동 확인


## ◻ git push <remote_repo_name> <branch_name>
> #### 원격저장소에 변경사항 저장
> <remote_repo_name> : 원격 저장소 이름 → 별칭이 origin이면 origin을 쓴다.    
> <branch_name> : 반영할 변경사항이 있는 branch   
>ex) git push origin main  


## ◻ git clone <repo_uri> <directory>
> ####원격 저장소에서 로컬로 가져오기
> <repo_uri> : 원격 저장소 주소  
> <directory> : 저장하고자 하는 directory folder. <directory를>적지 않으면 현재 폴더로 연결된다.  
> <br>
> ※ 원격 저장소의 성격이 private이라면 인증받은 사용자임을 명시해줘야만 성공할 수 있다.   
> &nbsp;&nbsp; 주소의 // 뒤에 '유저명@'을 붙인다.  
> ex) git clone https://caiasoso@blablah.github.io 