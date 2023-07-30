# 깃 명령어

## 파일관리

```shell
git init
```
- `git directory`를 생성하는 명령어


```shell
git add .
```
- `working directory`에 있는 파일, 폴더를 `staging area`에 추가
- add 하기 전엔 파일이 저장이 되어있는지 확인하기
- 스테이지에 올리기

```shell
git commit -m `message`
```
- `staging area`에 올라간 파일들의 스냅샷을 찍어 `git directory`에 저장
- 일반적으로 `-m` 옵션을 넣어서 커밋메세지를 추가하여 등록

```shell
git push origin master
```
- `master` 브랜치를 원격저장소 `origin`으로 업로드하는 명령어

```shell
git pull origin master
```
- 원격 저장소에서 마지막 코드 상태를 다운로드

```shell 
git clone <remote url>
```
- 원격 저장소에 있는 레포를 현재 폴더에 저장

## 설정

```
git status
```
- 현재 상태를 체크하는 명령어

```shell
git config
```
- git 설정을 하는 명령어

- 일반적으로 `--global` 옵션으로 최초 1번만 실행

- `git config --global user.email 'your@email.com'`
    - `git config --global user.email`을 통해 값 확인

    **name도 같은 방식으로**

```shell
git remote
```

- `git remote add origin <remote url>` 로 리모트 저장소 주소를 추가하는 명령어
