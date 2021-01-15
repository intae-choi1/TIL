# 대상이 되는 폴터(TIL) 아무것도 없는 버전
# git init (터미널에서)
# 대상이 되는 폴더를 git으로 관리하기 시작하겠다!

# git status 어떤 변경사항이 있는지 알아보기 위한 명령어

# untracked files 아직 변경사항이 관리되고 있지 않은 파일들
# stage 단계 - 변경사항이 관리되기 시작하는 단계    stage에 파일을 올리려면? git add 파일명  ex: git add git.md

# git config --global user.name 이름
# git config --global user.email 이메일  이걸 미리 설정해놓고
# git commit -m '전달할 메세지' 
# 

#  기록확인은 git log     git log --oneline(옵션)
# 맨처음 폴더 git이 관리할건지 아닐지를 결정. 
#### 1. git init - 폴더당 1번
#### 만약에 master가 보인다면 init하지 말것
#### 2. 뭔가 파일을 기록하고 싶다면 
####  2-1 git add 파일명  2-2 git commit - m '커밋메세지'
#### 3. 수정했다면 2-1, 2-2 반복 




# 원격(remote) 저장소

- 폴더 단위로 관리됨

내 컴퓨터의 저장소 -> github의 내가 만든 원격 저장소



원격 저장소를 지정: origin이라고 하겠다. 그 주소는 https://github.com/intae-choi1/TIL.git

```python
$ git remote add origin https://github.com/intae-choi1/TIL.git
```



```shell
$ git push origin master
```

