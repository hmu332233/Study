## github 브런치 가져오기


- #### 브런치 목록
  - `git branch` 로컬저장소 브런치 목록
  - `git branch -r` 원격저장소 브런치 목록
  - `git branch -a` 모든 브런치 리스트

- #### 브런치 가져오기
  - `git checkout -b 생성할브런치이름 원격브랜치이름`  
    ex) `git checkout -b develop origin/develop`  
    <br/>
  - `git checkout -t origin/develop` 위와 같은 기능을 한다.

- #### 참고
  - 원격 저장소의 브랜치를 전부 가져오지 못했을 경우에  
    `git fetch origin`를 입력하면 가져올 수 있다.
  - 그 이후에 위의 작업을 하면 정상적으로 브런치를 가져올 수 있다

- #### 참고사이트
  - [git에서 원격저장소의 branch 가져오기](https://blog.outsider.ne.kr/641)
