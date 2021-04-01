# git을 사용하면서
git 명령어와 커밋 컨벤션에 관한 리드미 입니다.
## Create repository
- 터미널 안에서 동기화 폴더로 이동 <br>
```cd Desktop/Education```
- 동기화 진행하기 <br>
```git clone (create repo 후 생성된 주소 기입)```

## Upload file
- 파일 업로드
  - 특정파일 업로드<br>
  ```git add example.html```
  - 모든 파일 업로드<br>
  ```git add .```
- 커밋 작성하기
  - 커밋 컨벤션<br>
  ```git commit -m "Add example.html"```
  

## Remove file
- 파일 삭제하기
  - git, 로컬 디렉토리에서 삭제
  ```
  git rm example.css
  git commit -m "Remove example.css for ~~~"  
  ```
  - git에서만 삭제(로컬은 그대로)
  ```
  git rm -cached example.js
  git commit -m "Remove example.js"
  ```
  
