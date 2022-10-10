# refactoring-study

[**리팩터링 2판**](http://www.yes24.com/Product/Goods/89649360) 책을 읽고 정리하는 공간입니다.

## 작성 가이드
* 매주 Issues 탭에 해당 주차의 범위를 이슈로 발행합니다.
* 해당 이슈 아래에 본인이 정리한 글의 링크를 걸어주시면 됩니다. (공유가능한 플랫폼이면 어떤 플랫폼이든 상관없음)

## 일정
(발표 순서 : 권동희 -> 정서원 -> 김유진 -> 한문규)
* 1주차(2022/05/24) : [**1장 리팩터링: 첫 번째 예시**](https://github.com/hmg0616/refactoring-study/issues/1), 발표자 : 권동희
* 2주차(2022/06/07) : [**2장 리팩터링 원칙**](https://github.com/hmg0616/refactoring-study/issues/2), 발표자 : 김유진
* 3주차(2022/06/20) : [**3장 코드에서 나는 악취**](https://github.com/hmg0616/refactoring-study/issues/3), 발표자 : 권동희
* 4주차(2022/07/05) : [**4장 테스트 구축하기**](https://github.com/hmg0616/refactoring-study/issues/4), 발표자 : 김유진
* 5주차(2022/07/19) : [**6장 기본적인 리팩터링(6.1 ~ 6.7)**](https://github.com/hmg0616/refactoring-study/issues/5), 발표자 : 권동희
* 6주차(2022/07/26) : [**6장 기본적인 리팩터링(6.8 ~ 6.11)**](https://github.com/hmg0616/refactoring-study/issues/6), 발표자 : 정서원
* 7주차(2022/08/10) : [**7장 캡슐화**](https://github.com/hmg0616/refactoring-study/issues/9), 발표자 : 한문규
* 8주차(2022/08/31) : [**8장 기능이동(8.1 ~ 8.5)**](https://github.com/hmg0616/refactoring-study/issues/10), 발표자 : 정서원
* 9주차(2022/09/20) : [**8장 문장 슬라이드하기(8.6 ~), 9장 데이터 조직화**](https://github.com/hmg0616/refactoring-study/issues/11), 발표자 : 한문규
* 10주차(2022/10/04) : [**10장 조건부 로직 간소화**](https://github.com/hmg0616/refactoring-study/issues/12), 발표자 : 정서원
* 11주차(2022/10/11) : [**11장 API 리팩터링(~11.8)**](https://github.com/hmg0616/refactoring-study/issues/13), 발표자 : 김유진
* 11주차(2022/10/11) : [**11장 API 리팩터링(11.9~) ~ 12장 상속 다루기(~12.3)**](https://github.com/hmg0616/refactoring-study/issues/14), 발표자 : 한문규
* 11주차(2022/10/11) : [**12장 상속 다루기(12.4~)**](https://github.com/hmg0616/refactoring-study/issues/15), 발표자 : 권동희

> 종료 후 책거리 및 추후 스터디 진행 도서 선정 예정

## 일정 안지킨 사람
* 5주차(2022/07/19) : 김유진

## 목차
* CHAPTER 01 리팩터링: 첫 번째 예시
```
1.1 자, 시작해보자!
1.2 예시 프로그램을 본 소감
1.3 리팩터링의 첫 단계
1.4 statement() 함수 쪼개기
1.5 중간 점검: 난무하는 중첩 함수
1.6 계산 단계와 포맷팅 단계 분리하기
1.7 중간 점검: 두 파일(과 두 단계)로 분리됨
1.8 다형성을 활용해 계산 코드 재구성하기
1.9 상태 점검: 다형성을 활용하여 데이터 생성하기
1.10 마치며
```

* CHAPTER 02 리팩터링 원칙
```
2.1 리팩터링 정의
2.2 두 개의 모자
2.3 리팩터링하는 이유
2.4 언제 리팩터링해야 할까?
2.5 리팩터링 시 고려할 문제
2.6 리팩터링, 아키텍처, 애그니(YAGNI)
2.7 리팩터링과 소프트웨어 개발 프로세스
2.8 리팩터링과 성능
2.9 리팩터링의 유래
2.10 리팩터링 자동화
2.11 더 알고 싶다면
```

* CHAPTER 03 코드에서 나는 악취
```
3.1 기이한 이름
3.2 중복 코드
3.3 긴 함수
3.4 긴 매개변수 목록
3.5 전역 데이터
3.6 가변 데이터
3.7 뒤엉킨 변경
3.8 산탄총 수술
3.9 기능 편애
3.10 데이터 뭉치
3.11 기본형 집착
3.12 반복되는 switch문
3.13 반복문
3.14 성의 없는 요소
3.15 추측성 일반화
3.16 임시 필드
3.17 메시지 체인
3.18 중개자
3.19 내부자 거래
3.20 거대한 클래스
3.21 서로 다른 인터페이스의 대안 클래스들
3.22 데이터 클래스
3.23 상속 포기
3.24 주석
```

* CHAPTER 04 테스트 구축하기
```
4.1 자가 테스트 코드의 가치
4.2 테스트할 샘플 코드
4.3 첫 번째 테스트
4.4 테스트 추가하기
4.5 픽스처 수정하기
4.6 경계 조건 검사하기
4.7 끝나지 않은 여정
```

* CHAPTER 05 리팩터링 카탈로그 보는 법
```
5.1 리팩터링 설명 형식
5.2 리팩터링 기법 선정 기준
```

* CHAPTER 06 기본적인 리팩터링
```
6.1 함수 추출하기
6.2 함수 인라인하기
6.3 변수 추출하기
6.4 변수 인라인하기
6.5 함수 선언 바꾸기
6.6 변수 캡슐화하기
6.7 변수 이름 바꾸기
6.8 매개변수 객체 만들기
6.9 여러 함수를 클래스로 묶기
6.10 여러 함수를 변환 함수로 묶기
6.11 단계 쪼개기
```

* CHAPTER 07 캡슐화
```
7.1 레코드 캡슐화하기
7.2 컬렉션 캡슐화하기
7.3 기본형을 객체로 바꾸기
7.4 임시 변수를 질의 함수로 바꾸기
7.5 클래스 추출하기
7.6 클래스 인라인하기
7.7 위임 숨기기
7.8 중개자 제거하기
7.9 알고리즘 교체하기
```

* CHAPTER 08 기능 이동
```
8.1 함수 옮기기
8.2 필드 옮기기
8.3 문장을 함수로 옮기기
8.4 문장을 호출한 곳으로 옮기기
8.5 인라인 코드를 함수 호출로 바꾸기
8.6 문장 슬라이드하기
8.7 반복문 쪼개기
8.8 반복문을 파이프라인으로 바꾸기
8.9 죽은 코드 제거하기
```

* CHAPTER 09 데이터 조직화
```
9.1 변수 쪼개기
9.2 필드 이름 바꾸기
9.3 파생 변수를 질의 함수로 바꾸기
9.4 참조를 값으로 바꾸기
9.5 값을 참조로 바꾸기
9.6 매직 리터럴 바꾸기
```

* CHAPTER 10 조건부 로직 간소화
```
10.1 조건문 분해하기
10.2 조건식 통합하기
10.3 중첩 조건문을 보호 구문으로 바꾸기
10.4 조건부 로직을 다형성으로 바꾸기
10.5 특이 케이스 추가하기
10.6 어서션 추가하기
10.7 제어 플래그를 탈출문으로 바꾸기
```

* CHAPTER 11 API 리팩터링
```
11.1 질의 함수와 변경 함수 분리하기
11.2 함수 매개변수화하기
11.3 플래그 인수 제거하기
11.4 객체 통째로 넘기기
11.5 매개변수를 질의 함수로 바꾸기
11.6 질의 함수를 매개변수로 바꾸기
11.7 세터 제거하기
11.8 생성자를 팩터리 함수로 바꾸기
11.9 함수를 명령으로 바꾸기
11.10 명령을 함수로 바꾸기
11.11 수정된 값 반환하기
11.12 오류 코드를 예외로 바꾸기
11.13 예외를 사전확인으로 바꾸기
```

* CHAPTER 12 상속 다루기
```
12.1 메서드 올리기
12.2 필드 올리기
12.3 생성자 본문 올리기
12.4 메서드 내리기
12.5 필드 내리기
12.6 타입 코드를 서브클래스로 바꾸기
12.7 서브클래스 제거하기
12.8 슈퍼클래스 추출하기
12.9 계층 합치기
12.10 서브클래스를 위임으로 바꾸기
12.11 슈퍼클래스를 위임으로 바꾸기
```

* 부록
```
부록 A 리팩터링 목록
부록 B 악취 제거 기법
```
