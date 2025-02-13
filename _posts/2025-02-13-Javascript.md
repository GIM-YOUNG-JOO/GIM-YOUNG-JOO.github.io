---
title: "Javascript 02/13"
excerpt: "Web"
tags:
  - Web
  - JavaScript
comments: true
---


### Naming Convention
* Coding Conventions 중 하나로, 소스 코드와 문서에 있는 변수 이름, 타입, 함수 등의 식별자에 사용되는 문자열을 선택하기 위한 여러가지 규칙  
프로젝트, 프로그래밍 언어, 개발 도구 등에 따라 사용되는 종류가 다름

| 종류 | 설명 | 예제 |
|--------------|------|------|
| PascalCase | 각 단어의 첫 글자를 대문자로 작성 | `UserProfile`, `GetUserData` |
| camelCase | 첫 단어는 소문자로 시작하고 이후 단어의 첫 글자는 대문자로 작성 | `userProfile`, `getUserData` |
| snake_case | 모든 단어를 소문자로 작성하고 언더스코어(`_`)로 구분 | `user_profile`, `get_user_data` |
| kebab-case | 모든 단어를 소문자로 작성하고 하이픈(`-`)으로 구분 | `user-profile`, `get-user-data` |


### JavaScript Map의 주요 특징
* 키로 모든 데이터 타입을 사용 가능
* 입력 순서 유지
* size 속성 제공
* 키 조회 속도가 빠름
* 반복 메서드(keys(), values(), entries()) 제공

![homework7]({{ site.url }}{{ site.baseurl }}/assets/images/homework7.png)