# GIT

## ㅁ 초기화

- 계정 등록
```sh
git config --global user.name "내 닉네임"
git config --global user.email "내 이메일"
```

- 저장소 만들기
```sh
mkdir "프로젝트 이름"
cd "프로젝트 이름"
git init
```

---

<br>

## ㅁ 버전 관리

### 기본
- 변경내용을(새로 생긴 파일 포함)
     ```
    git add
    ```
    로 stage에 올리기

    <br>
- stage 
    ```
    git commit  
    ```
    으로 stage된 파일들 커밋 (버전 추가)

    <br>
- repository  
    ```
    git push
    ```
    로 커밋된 내용들 저장소에 반영

---
<br>

- 깃 상태 정보 보기
```sh
git status
```
- 프로젝트에 포함되어 있지만 추적되고 있지 않다는 뜻
- ```git add``` 필요
```sh
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        TEST/
```


- add 된 후에 수정되었음.
- 또 ```git add``` 필요
```sh
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
```

---

