# 개발규격

## 프론트엔드

|대상|예시|상세|
|----|----|----|
|파일명|`Manager.js`, `ClientRouterPage.js`, `Manager.css.js`| 모든단어의 첫글자는 대문자 이후 소문자 / style 파일명 : 기능명.css.js|
|함수명|`function Helloworld ()`|`_` 금지, `-` 금지, 첫 단어의 첫 자는 대문자, 이후 단어는 소문자|
|변수명|`var setUseState;`|첫단어는 소문자 두 번째 단어 이후의 첫글자는 대문자 |


## 백엔드

|대상|예시|상세|
|------|----|----|
|파일명|`QRrouter.ts`, `index.ts`| 단어의 첫글자 대문자 ( index, config 제외 )|
|함수명|`function helloWorld ()`|`_` 금지, `-` 금지, <br> 첫 단어 소문자, 이후 단어 첫글자 대문자|
|변수명|`var setUseState`, `type ErrorBody`|첫단어는 소문자 <br> 두 번째 단어 이후의 첫글자는 대문자 <br> type, interface 제외 |
|에러구조|`code: 0,`<br>`type : "BAD_REQUEST_ERROR",`<br>`message: "Missing param",`|첫단어는 소문자 두 번째 단어 이후의 첫글자는 대문자 type, interface 제외 |
|파라미터구조|`id : 1`|소문자 |


## 공통

|대상|예시|상세|
|----|----|----|
|브랜치|`feature-loging-show`|`feature-` + 기능명|
