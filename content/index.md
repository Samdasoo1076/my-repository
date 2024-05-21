# Welcome to my Flowershow site!

# 테스트 용으로 하나 해봄
## 한 줄 요약 : 함수의 실행 문맥을 나타내는 키워드

---
## **this** 키워드 사용하기
```js
function sayHello() {
    console.log("Hello, " + this.name + "!")
}
 
var person = {
    name: "이지민",
    sayHello: sayHello
};
var person2 = {
    name: "리짜이밍",
    sayHello: sayHello
};
person.sayHello();
person2.sayHello();

//Hello, 이지민!
//Hello, 리짜이밍!

```
