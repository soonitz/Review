# :ballot_box_with_check: null

- 어떤 값이 *의도적*으로 비어있음을 표현
- 변수가 아무런 객체를 가리키지 않음을 표현

```javascript
typeof null          // "object" (하위호환 유지를 위해 "null"이 아님)
typeof undefined     // "undefined"
null === undefined   // false
null  == undefined   // true
null === null        // true
null == null         // true
!null                // true
isNaN(1 + null)      // false
isNaN(1 + undefined) // true
```

###### Reference Site <br> https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Operators/null
