# ECMAScript6
What is ECMAScript6 


<a href="https://github.com/ngio/ECMAScript6/blob/master/let.js">let.js</a>

<a href="https://github.com/ngio/ECMAScript6/blob/master/const.js">const.js</a>

 ECMAScript 6 is also known as ES6 and ECMAScript 2015.

 Some people call it JavaScript 6.

 This chapter will introduce some of the new features in ES6.

- JavaScript let
- JavaScript const
- JavaScript Arrow Functions
- JavaScript Classes
- Default parameter values
- Array.find()
- Array.findIndex()
- Exponentiation (**) (EcmaScript 2016)



ES 2015 (ES 6)


1. let, const 키워드 추가
기존의 변수는 함수 scope를 가진 var 키워드를 이용하여 선언하였다. 때문에 block scope 를 가진 let과 const 키워드를 추가하였다. 기존에는 상수형 키워드가 없어 CONST_TEST와 같이 대문자로 상수임을 표시했다면, ES 6부터 const 키워드가 추가되어 값의 변경을 통제한다.

2. arrow 문법 지원
arror 문법은 두 가지의 장점을 제공한다. 첫 번째는 익숙하면 편하고 간결해진 코드를 작성할 수 있다. 두 번째는 this 를 바인딩하지 않는다. (다르게 말하면, this는 해당 scope의 this와 같다.)
두 번째 this를 바인딩 하지 않는다는 코드로 설명하겠다. 우선 아래 코드를 보자. test 객체에 name변수와 fn이라는 메소드를 두었다. 아래 test.fun으로 메소드를 실행한다.

3. iterator / generator 추가
위 arrorw에서 샛길로 빠져서 더 새진 않겠습니다. 이 둘은 따로 공부해서 글을 쓸 정도로 내용이 깊고 많습니다.

4. module import / export 추가
사실 저는 익숙하고 당연하게 import / export를 써 왔는데 도입된 시점이 그리 오래되지 않았다는 것에 잠깐 놀라네요.

5. Promise 도입
자바스크립트의 비 동기 callback hell을 해결해 줄 기법이 추가 되었습니다.

ECMA 2017 (ES 8)

사실 ECMA 2017 까진 정리하지 않으려 했는데, 보던 중 반가운 기능이 추가되어 소개 합니다.

async — await

위에서 ES6에서 callback hell을 해결하기 위해 Promise가 도입되었다고 했는데 async-await도 Promise처럼 callback 을 해결할 뿐만 아니라 좀 더 직관적이고 단순하게 코드를 만들 수 있습니다. 
