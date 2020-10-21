<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" width="250" />
</p>

## ✈️ Node.js 튜토리얼

[생활코드 WEB2 링크](https://opentutorials.org/course/3332)

### 🛫 Description

JavaScript를 이용해서 Node.js를 제어해 동적으로 HTML 코드를 생성하는 웹애플리케이션을 만드는 방법에 대한 튜토리얼

튜토리얼은 기본 설치방법, node.js runtime 사용법, node.js로 간단한 CRUD 기능을 수행하는 페이지 제작 등을 다룬다

### 🛫 Requirements

-   Node.js version : 12.19.0 [# Node.js v12.19.0 Docs API](https://nodejs.org/dist/latest-v12.x/docs/api/)
-   pm2 version : 4.5.0 [# node.js 프로세스 관리자](https://pm2.keymetrics.io/)

```bash
# pm2 간단 사용법
pm2 start main.js --watch
pm2 monit
pm2 list
pm2 log
pm2 stop main.js
```

```bash
# npm 기본 명령어
npm init # package.json 생성

npm install -S sanitize-html
# -S: project only  / -g: global # node_modules(dir) 생성
# package.json -> dependencies 에 install 한 패키지 버전 정보 생성
```

<!-- ![nodejs](https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg =250x) -->
