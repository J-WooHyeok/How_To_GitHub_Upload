# 1. 깃허브에 원격저장소(repository) 만들기
<br/>
<img width="656" alt="스크린샷 2024-07-03 오전 11 16 31" src="https://github.com/J-WooHyeok/How_To_GitHub_Upload/assets/114277865/e488ceb8-fbcc-4f2c-8f12-ba0b99897654">
<br/>
<hr/>
주소 복사해두기
<br/>
<img width="827" alt="스크린샷 2024-07-03 오후 1 28 04" src="https://github.com/J-WooHyeok/How_To_GitHub_Upload/assets/114277865/2058c748-9d65-4ad1-8d31-fad2821aa9f1">

# 2. 올리고싶은 파일에서 우클릭 -> 폴더에서 새로운 터미널 열기
<br/>
<img width="280" alt="스크린샷 2024-07-03 오후 1 18 05" src="https://github.com/J-WooHyeok/How_To_GitHub_Upload/assets/114277865/64784df5-4e75-4ce2-a89c-a0dfcd222391">

# 3. "git init" [깃허브 저장소 초기화]
<br/>
<img width="567" alt="스크린샷 2024-07-03 오후 1 19 20" src="https://github.com/J-WooHyeok/How_To_GitHub_Upload/assets/114277865/1b7c6d3f-03e2-4b80-8db1-82e70a1d2a13">

# 4. "git add" [폴더 / 파일 추가]
> __git add.__ <br/>
> 모든 파일 올리기<br/>
> __git add 파일명/폴더명__<br/>
> 올리고싶은 파일 올리기<br/>
<br/>
<img width="471" alt="스크린샷 2024-07-03 오후 1 20 45" src="https://github.com/J-WooHyeok/How_To_GitHub_Upload/assets/114277865/bf60e1ef-45d9-4e87-996e-27d565e80537">

# 5. git commit -m "커밋로그 or 설명 메시지" [커밋 남기기]
보통 변경사항등을 로그로 남김 ex) UI_account_mod
<br/>
<img width="444" alt="스크린샷 2024-07-03 오후 1 25 09" src="https://github.com/J-WooHyeok/How_To_GitHub_Upload/assets/114277865/6acab076-9d2a-4f44-aaf8-ce8e1bf9fdb3">

# 6. git remote add origin 주소 [repository와 해당 폴더 연결] / git remote -v [연결상태 확인]
<br/>
<img width="568" alt="스크린샷 2024-07-03 오후 1 30 23" src="https://github.com/J-WooHyeok/How_To_GitHub_Upload/assets/114277865/01ed14f3-a62c-4b87-90bc-20227b50e8b8">

# 7. git push origin main [push하기]

# 8. ! [rejected] error: failed to push some refs to ~~~ 에러가 날 경우
깃의 원격저장소와 현재 로컬저장소가 동기화되어 있지 않기때문에 나타나는 문제이다.

__git push origin +main__<br/>
__강제push__<br/>
변경 내용만 반영되는 것이 아니라, 소스 "전체"가 push되어버린다. (기존 데이터 손실 위험)<br/>
<img width="478" alt="스크린샷 2024-07-03 오후 1 43 07" src="https://github.com/J-WooHyeok/How_To_GitHub_Upload/assets/114277865/0e6dffbd-c803-4bea-ab75-68b296ed32be">





