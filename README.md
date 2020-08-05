# 코딩 인터뷰

## 필요 기술

node.js react

## 들어가기 앞서

- src/App.js, cons 상수로 쿠폰 정보가 들어 있습니다.

- 각 키별 정보는 아래와 같습니다.

```javascript
{
    brand: '이디야', // 브랜드 이름
    sellCount: 30, // 일일 판매 개수
    name: '아메리카노', // 해당 쿠폰 이름
}
```

- src/App.js 에서 함수형, 클래스형 컴포넌트 중에 선택해서 코딩해 주세요.

- 터미널에서 yarn dev 를 실행하면 localhost:3000 에서 앱을 확인할 수 있습니다.

- 추가 라이브러리 사용엔 제한이 없습니다.

## SPEC

1. cons 에 있는 데이터로 각 브랜드별 버튼을 생성

   1.1 버튼엔 브랜드 이름이 들어가야함

2. 각 브랜드 버튼을 클릭하면 해당 브랜드 쿠폰들을 표시

   2.1 쿠폰은 일일 판매 개수가 높은 순으로 정렬