# :ballot_box_with_check: 논리 연산자(Logical Operator)
> ### & : 비트 연산자
> 비트의 논리 합을 하는 연산자　
[⇒비트 연산자 참고 사이트](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Operators/Bitwise_AND)

<br>

> ### && : 논리곱 연산자
> &&는 모든 조건이 참이어야 true
```javascript
true  && true  === true
true  && false === false
false && true  === false
false && false === false
```

<br>

> ### || : 논리합 연산자
> ||는 둘 중 하나가 참이면 true
```javascript
true  || true  === true
true  || false === true
false || true  === true
false || false === false
```

<br>

> ### << , >> : 비트 이동 연산자
> 왼쪽, 오른쪽으로 비트를 밀어내는 연산자

<br>

> ### ! , !! : 부정 연산자
> ! : 입력값을 boolean으로 변환하는데 true면 false로, false면 true로 값을 반대로 반환 <br>
> !! : boolean 타입으로 명시적으로 형 변환
* 여기서 `boolean` 이란? `boolean` 타입에 해당하는 값은 `true`, `false` 두 가지 밖에 없음(참, 거짓)　
[⇒ boolean 타입 참고 사이트](https://helloworldjavascript.net/pages/150-boolean.html)

<br>

> ### ? : 옵셔널 체이닝
> 객체 속성이 없는 경우, typeError가 발생하지 않고 undefined가 반환됨
* 여기서 `undefined` 이란? 값이 대입되지 않은 변수 혹은 속성을 반환

<br>

> ### ?? : Null 병합 연산자
> 앞에 오는 값이 null 또는 undefined면 뒤에 오는 값을, 아니면 null 또는 undefined를 반환
* 여기서 `null` 이란? 객체가 없음　
[⇒ null 과 undefined 참고 사이트](https://helloworldjavascript.net/pages/160-null-undefined.html)

###### Reference Site <br> https://im-designloper.tistory.com/86
<br><br>

# :ballot_box_with_check: 산술 연산자(Arithmetic Operator)
<br>

| Command | Description |
|:---:|:---|
| ++ | increment |
| -- | decrement |
| == | equal to |
| === | exactly equal to |
| != | not equal |
| !== | not equal (different value or different type) |
###### Reference Site <br> http://jun.hansung.ac.kr/cwp/Javascript/JavaScript%20Operators.html 
<br><br>

# :ballot_box_with_check: 연산자 우선순위(Operator Precedence)
###### http://www.tcpschool.com/javascript/js_operator_arithmetic
