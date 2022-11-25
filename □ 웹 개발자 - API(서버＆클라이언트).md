># API *(application programming interface)*
>서버＆클라이언트에서 `데이터`를 `요청＆전송`하기 위한 `신호` 체계
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
비동기 방식: 웹 사이트를 `새로고침` 하지 않고 서버에서 데이터를 전송하는 방식
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
