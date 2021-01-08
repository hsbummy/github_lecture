## 준비사항

* git 로컬 저장소

  * 루트 커밋이 반드시 있어야함

* 기본 작업 완료

  * ```bash
    $ git 파일명
    $ git add .
    $ git commit -m '커밋메시지'
    ```

  * 

# branch

## 기본 명령어

* 기본 명령어

```bash
$ git branch 브랜치 이름
```

* 브랜치 이동

```bash
$ git checkout 브랜치이름
$ git switch 브랜치이름 #최근 명령어
```

* 브랜치를 생성 및 이동

```bash
$ git checkout -b 브랜치이름
```

* 브랜치 목록

```bash
$ git branch
```

* 브랜치 병합

```bash
(master) $ git merge 브랜치드이름
```

#### 주의!!! master로 브랜치이름을 merge 하는 것

* 브랜치 삭제

```bash
$ git branch -d 브랜치이름
```





