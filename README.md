## Learning Basic Vue
> https://www.youtube.com/playlist?list=PLB7CpjPWqHOtYP7P_0Ls9XNed0NLvmkAh  

# 기초 개념 정리

## computed 속성
선언형 프로그래밍 방식.  
종속 대상에 따라 저장(캐싱)한다.  
computed 속성을 가지면 Date.now()는 절대 업데이트되지 않는다.

## watch 속성
명령형 프로그래밍 방식.  
감시할 데이터를 지정하고 그 데이터가 바뀌면 이런 함수를 실행하게 한다.
```
watch: {
    // 이때, message 는 data 의 이름과 같다.
    message(newVal, oldVal) {
        console.log(newVal, oldVal);
    }
}
```

## template
React의 Fragment 와 비슷한 기능을 한다. 

## v-if, v-else, v-else-if
조건부 렌더링

## v-show
'display: none' 스타일 속성 토글.  
자주 바뀌는 컴포넌트에 사용.

# v-for
배열의 엘리먼트와 객체의 속성을 나열할 수 있음.