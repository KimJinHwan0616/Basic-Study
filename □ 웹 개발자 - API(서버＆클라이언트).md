># API *(Application Programming Interface)*
>서버＆클라이언트에서 `데이터`를 `요청＆응답`하기 위한 `신호` 체계
>
>### XML, JSON, YAML
>### AJAX
>### DOM

---

## XML *(eXtensible Markup Language)*
`데이터`를 `HTML`로 표현하는 형식
```angular2html
가독성↓
주석O

예) <name>이름</name><location>위치</location><birth>생년월일</birth>
```

## JSON *(JavaScript Object Notation)*
`데이터`를 `자바스크립트 사전`으로 표현하는 형식
```angular2html
가독성↑
주석X

예) {"name": "이름", "location": "위치", "birth": "생년월일"}
```

---

## YAML *(Yaml Ain't Markup Language)*
`데이터`를 `사람이 이해하기 쉬운 형태`로 표현하는 형식
```angular2html
가독성↑↑

예) 
name: 이름
location: 위치
birth: 생년월일
```

---

## AJAX *(Asynchronous Javascript And Xml)*
`데이터`를 `자바스크립트`로 `서버`에 `비동기 방식`으로 `요청`하는 것
```angular2html
동기 방식: 서버로 요청햇을 때, 응답이 돌아와야 다음 동작 실행

비동기 방식: 서버로 요청했을 때, 응답 상태와 상관없이 다음 동작 실행
예) 검색어 자동완성, 장바구니 아이템 추가, ...
```

+ ### DOM *(Document Object Model)*
    `자바스크립트`로 `HTML 요소`를 제어할 수 있는 `객체`
    ```
    예) body, head, div, img, ...
    
                 Document
                    │
                   html
        ┌───────────┴───────────┐
      head                     body
                                │
                       ┌────────┼────────┐
                       h1      input    button  
    ```
