# About branch

## Branch는 무엇인가?

![Alt text](branch.png)

- 독립적으로 작업을 진행하기 위한 개념
- `master branch`란 모든 레퍼지토리의 기본 혹은 메인
`master branch`에서 파생된 다른 `branch`에서 수정사항을 만든 후에 `master`에 병합

## Branch 생성
1. `git branch <branch name>`으로 Branch 생성
2. `git branch`로 현재 위치한 브랜치 확인
3. `git switch <branch name>`으로 Repository에 브랜치 생성
4. `git push origin <branch name>`으로 레퍼지토리에 브랜치 생성
5. `pull requests`로 branch 내용 master로 합병 가능

*합병한 브랜치는 삭제하는 것이 일반적*


# How to share

## want to invite

1. `Repository` 생성
2. Setting- Collaborators- Add People

## clone으로 내려받기
1. `Repository` code copy
2. open `Git Bash`
3. write
```shell
git clone <remote url>
```
4. `code`에서 열기

- 수정 후 add - commit - push 일련의 과정 실행


---
# HOW TO PULL REQUEST

## Forking

1. `Fork` 하고 싶은 `Repository` 확인
2. 오른쪽 상단 `Fork` 선택 - `Create Fork`


## clone git
1. `clone` 으로 내려받는 과정 실행
- 자신의 repo로 생성되었는지 확인 후 자신의 repo code로 실행

## pull request
1. `Repository` 상단 `Pull requests` 선택
2. `New pull requeset` 선택
3. ← 화살표 좌측은 pull 할 대상의 repo
화살표 우측은 자신의 repo로 설정한 뒤 pull

- 이후 합병을 진행하고 싶으면 `merge`를 통해 합병을 진행