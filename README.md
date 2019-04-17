# 알고리즘 공부

- **problem 폴더**에 주차별 문제가 주어집니다.

- **자신의 ID 폴더**에 자신이 해결한 답을 올립니다. 
  (코드만 올려도 되고, 어떻게 해결했는지 로직을 같이 올려도 됩니다)
  
  <img width="1237" alt="스크린샷 2019-04-17 오전 10 43 09" src="https://user-images.githubusercontent.com/45627868/56255059-55442600-60fe-11e9-84fa-45f1477cd33f.png">   

> **자신의 ID 폴더(gyu)** 에 **주차별 폴더**를 만들고 **주차별 PS 코드 또는 답안**을 올리시면 됩니다.
  
`이때, 반드시 자신의 브런치로 올리셔야 합니다.`
  

## git 사용 법

```shell
git remote update
# git 원격서버 업데이트 

git branch -r
# 원격 브런치를 확인함

git checkout gyu
# 원래는 브런치가 있어야 하지만 브런치를 생성하지 않고 할 경우 
# 원격에 있는 브런치와 동기화됨

# 이제 자신 작업수행
- 폴더 만들기(/ps/) <- 각주차별/ps/ 밑에 생성
- PS 답안 업데이트

git add .
git commit -m "message"

git push origin gyu
# gyu는 자신의 branch 이름으로 변경
```
