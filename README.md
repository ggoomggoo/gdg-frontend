# Boot Camp: 초보 개발자를 위한 웹 프론트엔드 개발 101

[https://festi.kr/festi/gdg-korea-2016-devfest-seoul/program/92/](https://festi.kr/festi/gdg-korea-2016-devfest-seoul/program/92/)

[https://festi.kr/festi/gdg-korea-2016-devfest-seoul/](https://festi.kr/festi/gdg-korea-2016-devfest-seoul/)

## index

* session
    - **초보 개발자를 위한 웹 프론트엔드 개발 101**
        + 도창욱 님 / GDG Korea WebTech
        + [http://www.slideshare.net/cwdoh/frontend-101-intro](http://www.slideshare.net/cwdoh/frontend-101-intro)
    - **HTML CSS 101**
        + 조은 님 / 우아한형제들
        + [https://drive.google.com/file/d/0B6UpaSZyNjEmd1BMMFRIR043aE0/view](https://drive.google.com/file/d/0B6UpaSZyNjEmd1BMMFRIR043aE0/view)
    - **Hitchhiker's guide to the front end development **
        + 김정윤 님 / 11번가 | 모바일
        + [http://www.slideshare.net/cwdoh/frontend-101-intro](http://www.slideshare.net/cwdoh/frontend-101-intro)

## content

### 초보 개발자를 위한 웹 프론트엔드 개발 101

* version constrol
    - git
* 프로젝트 구조
    - sample
        + boilerplate
* 궁금한것이 있을땐?
    - not W3Schcool
        + W3FOOLS
    - MDN
        + mozilar
    - Web Fundamentals
        + google
    - W3C
    - techhtml.github.io
    - webplatform.org
    - HTML5 ROCKS
        + died...
* magic googlings
    - site:
* caniuse.com
    - browser
* 3..개발 프로세스
    - 회사 개발 블로그
    - 커뮤니티 활동
    - 의존성
        + $include, import, _
    - lib
        + moments.js
    - CDN
        + https

### HTML CSS 101

* ~~앞부분 내용 누락(Wanted resume clinic 참석)~~
* html
    - label
        + for == input id
    - a
        + href
            * '#': 자기 참조
            * 공란: 예전브라우저 find 다이얼로그
    - span: like div
* css
    - 레이아웃
        + 엔티티코드 <>
        + 중앙정렬
            * width: 선언하지 않으면 브라우저는 전체를 다 차지하려고함
            * margin: auto;
        + 다단박스
            * flex
                - display: flex;
                - flex: 1;
                - IE 미지원
                - CSS3
            * float
                - 픽셀이 1이라도 다를경우 깨짐
                    + sub 픽셀
    - 문자
        + generic-font
            * 혼합
                - 고딕, 명조체
                - 산세리프
        + font-weight
            * 100~900
    - 색상
        + hash
        + rgba
            * a: alpha
            * 투명도: 오파시티
            * IE9~
    - sites
        + css-tricks.com
            * ex) flexbox
        + mdn
        + http://alistapart.com/
            * 개발 패러다임 글들이 많이 올라옴

### Hitchhiker's guide to the front end development

* 11번가 메인페이지
    - 17개 탭
    - 리퀘스트 수가 많음
* webpack
    - map file
        + *.js.map: budle 정보 보관
* sass
    - variable
    - mixin
    - vender
        + -webkit-*
    - @extend
    - @import
        + unified
    - map file
* image 최적화
    - metapicz
        + metadata 삭제
    - tinypng
        + 압축
* task runner
    - tasks
        + js, css, image
    - grunt
    - gulp
        + vs grunt
            * pipeline
                - like chaining
    - npm script
* build
    - src
    - disk
    - skpui
* cloud IDE
    - goorm.io
* example
    - spinner
        + https://github.com/poohding/spinner
        + https://github.com/poohding/spinner/releases