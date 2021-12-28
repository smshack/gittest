# hello git

# 절차
1. git 가입
2. github 저장소 생성
3. github 저장소 클론
4. 내 컴퓨터 내 문서 아래에 생성된 프로젝트 디렉토리에서 파일 생성 및 작업 완료
5. 커밋할 파일들을 선택해서 스테이징에 올리기(add)
6. 커밋하기(commit)
7. 푸시 하기(push)
8. github.com/내아이디/내프로젝트 링크를 통해 정상적으로 업로드 되어 있는지 확인


# 1. git이란
```
형상 관리 시스템(Verson Control System) 의 한 종류입니다. 
주로 개발자들이 프로그램과 관련된 파일들을 저장하는 데 사용합니다.
 게임의 세이브 포인트와 유사한데, 언제든지 저장 시점으로 되돌아 갈 수 있습니다. 
 여기서는 세 가지 기본 기념만 배우려 합니다.
```

## 커밋 (commit)
게임의 세이브에 해당하는 행동을 git에서는 커밋이라고 합니다. 다시 말해서 여러분은 언제든지 커밋한 시점으로 되돌아 갈 수 있습니다 . 커밋을 하려면 저장을 원하는 파일들을 묶어서 커밋 명령을 수행하면 됩니다.
## 스테이지에 올린다 (add)
앞에서 커밋하기 전에 저장을 원하는 파일들을 묶는 일을 해야 한다고 했습니다. 이 작업을 스테이지에 파일을 올린다라고 합니다. 혹은 줄여서 간단히 'add'라고도 합니다.
## github에 업로드 (push)
커밋을 하면 이제 현재 작업 내용의 세이브 데이터가 내 컴퓨터에 저장됩니다. 이걸 github에 업로드하면 마치 요즘 유행하는 스팀이나 PS4, 각종 모바일 게임의 원격 저장과 비슷한 일을 합니다. 다른 사람이랑 공유할 수도 있고, 내 컴퓨터의 데이터가 날아가도 안전하게 다시 복구할 수 있습니다. github에 업로드하는 걸 git에서는 "push"라고 합니다.

# git 명령어 요약
- clone: 원격 저장소 복사
- add: 스테이지 영역에 작업 파일 추가
- commit: 세이브, 스테이지 영역의 파일들을 가지고 커밋(= 세이브)를 만들수 있다
- push: 원격 저장소에 커밋을 업로드한다.

# 2. 마지막 커밋으로 돌아가기
- git reset 명령어
```
git log
git reset HEAD
```

# 3. 브랜치의 개념
## 파일의 내용 되돌리기
- 브랜치란: 기존 내용을 유지한 채로 새로운 내용을 추가하고 싶을 때 사용한다
- checkout: 특정 브랜치(혹은 커밋) 으로 돌아가고 싶을 때 사용


## 4. 추가된 내용입니다
충돌 시켜 보자