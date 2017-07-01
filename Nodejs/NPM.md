### 유용한 NPM 모음

- #### uglify-js
  - 불필요한 들여쓰기나 띄어쓰기를 없애 용량을 줄여준다.
  - [사이트](https://www.npmjs.com/package/uglify-js)

test.js
```js
function hello(name){
  console.log('Hi,' + name);
}
```

```bash
$ uglifyjs test.js
>> function hello(name){console.log("Hi,"+name)};

$ uglifyjs test.js -m
>> function hello(l){console.log("Hi,"+l)};
>> 변수 이름조차 짧게 줄여준다

$ uglifyjs test.js -o test.min.js -m
>> test.min.js로 실행결과를 저장해준다
```