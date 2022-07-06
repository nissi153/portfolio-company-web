### portfolio-company-web

자바 백엔드 개발자로 취업하기 위한 포폴 제작
전형적인 회사 홈페이지 만들기

![캡처](https://user-images.githubusercontent.com/36612384/177496819-496bec16-7223-42e7-a72f-8086cfde9450.PNG)

프론트엔드
- HTML5/CSS3/JS
- flexgrid
- jQuery/JS Plugins
- Bootstrap4 
- 반응형 웹제작(PC,모바일)

백엔드
- 자바 / JSP / JSTL&EL
- SpringBoot Framework / Mybatis F/W
- Oracle 11g express DBMS


```
상대경로 잡기

<!-- index.html -->
<!-- .  : 루트 / -->
<!-- ..  : 사용할 수 없는 경로 -->
<!-- login.html -->
<!-- . : /member -->
<!-- .. : 루트 / -->

<!-- 루트폴더 -->
<!-- index.html => header.html headerTop.html main.html footer.html -->
<!-- ./ 를 이용 -->

<!-- 그외의 폴더 : member company business product community -->
<!-- login.html join.htm : header-sub.html headerTop-sub.html footer-sub.html -->
<!-- ../ 을 이용 -->

<!-- href img-src 상대경로 잡는법 -->
<!-- 1.   ./index01.html      ./img/logo.png   현재폴더 -->
<!-- 2.   ../index01.htl      ../img/logo.png  ../img/member/login.gif 상위폴더에서 -->
<!-- 3.   /index01.html       /img/logo.png  프로젝트 시작폴더 - 라이브서버이용 -->
<!-- 4.    index01.html       img/logo.png 현재폴더 -->
```
