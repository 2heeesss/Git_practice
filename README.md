# Git_practice

20.5.25
### 환경설정
<br>
git config --global user.name (내 깃헙 이름) <br>
git config --global user.email (내 깃헙 메일주소) <br>

### 저장소 동기화                                                <br>
동기화 시킬 폴더를 하나 생성                                           <br>
cd Desktop/Education                     //내가 동기화 시킬 폴더로 이동<br>
git clone (Create repo 하고 나오는 주소 적기)                                     <br>

### 파일 올리기                                                  <br>
git add .                                //폴더에 있는 모든 파일 업로드 <br>
git commit -m "my first commit"                                   <br>
git push                                                         <br>    


### DS Store 삭제하기
지우기 테스트
```
git rm --dry-run .DS_Store
```

진짜 지우기
```
git rm --dry-run .DS_Store
```

```
git add -A
git commit -m "Remove DS_Store file"
git push
```
