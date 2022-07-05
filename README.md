### portfolio-company-web

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

<!-- 그외의 폴더 : member company -->
<!-- login.html join.htm : header-sub.html headerTop-sub.html footer-sub.html -->
<!-- ../ 을 이용 -->

<!-- href img-src 상대경로 잡는법 -->
<!-- 1.   ./index01.html      ./img/logo.png   현재폴더 -->
<!-- 2.   ../index01.htl      ../img/logo.png  ../img/member/login.gif 상위폴더에서 -->
<!-- 3.   /index01.html       /img/logo.png  프로젝트 시작폴더 - 라이브서버이용 -->
<!-- 4.    index01.html       img/logo.png 현재폴더 -->
```
