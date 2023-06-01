# Database_Design_Finalexam
데이터베이스설계 기말고사 정리입니다.

(sql 과제 3-1 ~ 3-50)![image](https://github.com/chihyeonWON/Database_Design_Finalexam/assets/58906858/16eeaa85-88de-4263-8e19-d486f6b4cd71)


[관계대수 연산자](https://inpa.tistory.com/entry/DB-%F0%9F%93%9A-%EA%B4%80%EA%B3%84-%EB%8C%80%EC%88%98-%EA%B4%80%EA%B3%84-%ED%95%B4%EC%84%9D-SQL-%F0%9F%95%B5%EF%B8%8F-%EC%A0%95%EB%A6%AC)   
![image](https://github.com/chihyeonWON/Database_Design_Finalexam/assets/58906858/85755f18-53ee-4d71-b3b9-bb259899d84f)
```
세타 조인은 두 릴레이션에서 공통된 애트리뷰트를 기준으로 비교 연산자(=,<>,<=,<,>=,>)를 사용하여 조건을 만족하는 튜플들을 결합하는 것이다.
동등 조인은 세타 조인 중에서 비교 연산자가 =인 조인이다.
즉, 두 릴레이션에서 공통된 애트리뷰트의 값이 같은 튜플들을 결합하는 것을 말한다.
```
![image](https://github.com/chihyeonWON/Database_Design_Finalexam/assets/58906858/45d0e3e8-999a-4fdf-bda1-0f1bd62050c8)
```
동등 조인의 결과 릴레이션에서 조인 애트리뷰트를 제외한 조인 (중복 필드 제거)
```

## 집계함수 종류
![image](https://github.com/chihyeonWON/Database_Design_Finalexam/assets/58906858/8677ebff-e7e8-43f7-8c99-41b336dd7460)

## 외부 조인
![image](https://github.com/chihyeonWON/Database_Design_Finalexam/assets/58906858/84015d74-8e7d-4a92-9802-03a57c7d4896)


## 셀렉션 시그마(Selection)
![image](https://github.com/chihyeonWON/Database_Design_Finalexam/assets/58906858/c6557ec1-f1c8-4889-bf86-fc6c5b83960d)
```
A, B가 릴레이션 R의 속성일 때, 세타 : 비교연산자
세타<조건> (R)

셀렉트의 결과
선택조건을 만족하는 릴레이션의 수평적 부분집합 (조건을 만족하는 행을 추출)
Horizontal subset
```
## 프로젝션 파이(Projection)
![image](https://github.com/chihyeonWON/Database_Design_Finalexam/assets/58906858/b236e591-d70a-48be-b87e-b05ceaba1ba3)
![image](https://github.com/chihyeonWON/Database_Design_Finalexam/assets/58906858/d8666824-1205-4121-b548-300da469990c)
```
릴레이션의 속성 추출 연산
단항 연산자
형식 : 파이<속성리스트>(R)
릴레이션의 수직적 부분집합(Vertical subset)
```
## 합집합
![image](https://github.com/chihyeonWON/Database_Design_Finalexam/assets/58906858/188c8f02-11a0-4808-9aa6-ba4f1913c9be)
```
두 개의 릴레이션을 합하여 하나의 릴레이션을 반환
```

## 디비전
![image](https://github.com/chihyeonWON/Database_Design_Finalexam/assets/58906858/a1088651-8f96-4ffc-9f29-8c982c1749c7)
```
릴레이션의 속성 값의 집합으로 연산을 수행함
형식 R / S
```
