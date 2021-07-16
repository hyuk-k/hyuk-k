# GIt

버전을 통한 코드 관리 도구



# Scm & VCS

- SCM : Source Code Management (소스 코드 관리)
- VCS : Version Control System (버전 관리 시스템)

# Git

- 버전 관리 도구
  - 변경 이력 트랙킹
  - 언제든 특정 시점으로 이동 가능
- 백업도구
- 협업도구

# Git 버전관리

> 중요 : GIt은 폴더 단위로 코드를 관리
>
> 커밋==버전생성==스냅샷 촬영==현재상태 저장

# git init

특정 폴더를 git으로 관리 시작

-  (master) 프롬프트에 표시
- .git 폴더 생성
  - .git 폴더 삭제 시 git 관리 중지

# git status

git에게 상태 확인

- git init 직후

```
On branch master : master라고 하는게 branch에 ㅇ있어

No commits yet : 아직 commit 없어

nothing to commit (create/copy files and use "git add" to track) : commit 할 게 없어 (트래킹 하고 싶으면 `git add` 명령어를 사용해)
```

- a.txt 파일 생성 직후

```
$ git status
On branch master

No commits yet

Untracked files: 추적되지 않은 파일이 있어
  (use "git add <file>..." to include in what will be committed)
        a.txt : 될 수 있게 포함하고 싶으면 git add <파일명>을 사용해

nothing added to commit but untracked files present (use "git add" to track)
```



# git add [파일명]

staging area (스냇샵 무대)에 파일 추가



# git commit -m "커밋 메시지"

- 버전을 생성
- 커밋(버전) 구성요소
  - 해시(Hash)
  - 작성자
  - 날짜
  - 커밋메세지:버전에 대한 설명

# git log

- 버전(커밋)들의 히스토리(로그)

  # git config