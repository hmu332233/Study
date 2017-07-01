### NPM

- Node Package Manager
- 타인의 모듈을 가져다 쓰는 방법
- https://www.npmjs.com/

- #### NPM 독립적인 앱 설치
  - npm을 프로젝트에 상관없이 독립적인 앱으로 사용하고 싶을 때에는 다음과 같이 한다.
```bash
$ npm install [packagename] -g
```

- #### NPM 모듈 설치
  - npm을 프로젝트에서 모듈로서 사용하기 위해서는 다음과 같이 한다.
```
$ npm init
name : 프로젝트이름
version : 버전..
description : 프로젝트의 설명
entry point : 어떠한 .js가 프로젝트를 구동하는 js파일인가
test command : 어떤 명령을 입력하면 테스트를 실행시킬 것인가
git repository : 깃 저장소 주소
... 생략(package.json에서 추후에 변경 가능)

$ npm install [packagename]
```
  - 다음과 같이 하면 dependencies가 동시에 수정된다
  - 일단은 `--save`를 붙여서 하는걸 추천한다
```
$ npm install [packagename] --save
```
  - 이후 다음과 같이 사용한다
test.js
```js
const name = require('name')
```