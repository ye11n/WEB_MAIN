# HTML 프로젝트 - 깃허브
새로운 시작! 웹 서비스 개발의 세계로 떠나보아요~
## Getting Started
This project is a starting point for a Web application.
- [프로젝트 메인 주소](https://github.com/ye11n/WEB_MAIN)
## 2주차 수업 메인화면 개발 완료! (문제 포함)

## 3주차 수업 부트스트랩 적용 완료! (문제 제외)
문서 시작
<!DOCTYPE html>

타이틀 제목
<title>

문서 몸체
<body>

문장 정렬
<p>

문장 크기
<h 숫자>

이미지 삽입
<img>

밑줄
<u>

## 4주차 수업 부트스트랩 PART2 적응 완료! (문제 제외)

## 4주차 수업 자바스크립트 적응 완료! (문제 제외)
메타 태그의 추가 위치는?
<head>

하이퍼링크
<body>

Link와 하이퍼링크의차이점은?
link : Head 안에 외부 자원 연결
하이퍼링크 : <body> 태그에서 주로 사용

Bootstrap 연동에 추가된 태그 3가지
meta, css, script

기본 레이아웃 영역을 무엇이라 하는가?
<div>

디자인 템플릿 지정에 필요한 것은?
css

표 병합을 위한 속성2가지는?
rowspan(세로), colspan(가로로)

## 5주차 – 자바스크립트(검색창 공백/비속어 검사)
자바스크립트를 추가하는 태그는?
//<script>

파일로 작성된 자바스크립트는 어디에 추가되는가?
head

자바스크립트가 제어하는 트리구조 문서를 무엇이라 하는가?
DOM트리

자바스크립트 변수 선언 방식 3가지
var 변수명 = 값
let 변수명 = 값
const 변수명 = 값

ES6 표준 이후 안전성을 위해 추가된 변수 선언 방식은?
let, const

문서의 최상위 문서의객체의 이름은?
document

문서의 객체 식별자를인식하는 메서드는?
getElementByld

마우스 이벤트 중 더블클릭의 이름은?
dbclick

## 6주차 – 로그아웃 화면(메인화면으로 이동), 소스코드 정리
JS의 참조 데이터 타입은? 2개 이상
null, string, Boolean, nember,symbol, undefied

Undefied 데이터 타입의 특징은?
원시타입

문자열과 변수를 조합하여 출력하는 방법을무엇이라 하는가?
템플릿 리터럴

Get / post 2가지 전송방식의 핵심 차이점은?
get : url 상에 정보 담음/눈에보임/2048자까지/일반페이지 접속속
post : body에 정보 담음/눈에안보임/2GB까지/로그인에 유리/정보 저장할 때 이유

페이지 요청에 Utf-8 인코딩 처리 전용 함수는?
request.setCharacterEncoding("UTF-8")

페이지 로딩과 동시에js를 호출하는 속성은?
<body onload="함수명()">

상대경로를 지정하는경우 상위 폴더를 지정하는 방법은?
../

자바스크립트의 핵심타이머 함수는?
setTimeout()

## 9주차
Es6 버전 화살표 함수에서 사용 제한된 함수는?
생성자 함수

기존 function이나 var등 선언 위치에 상관없이 인식하는 기능은?
호이스팅

Form 전송 시에 get 방식으로 url에 파라미터를 전송하기 위한 추가속성은?
method="get"

Label 태그의 주요 기능은 무엇인가?
폼 요소의 이름 정의

입력 값의 공백을 제거하는 함수 이름은?
trim()

Form도 이름을 지정하여 하나의 식별자로 정의할 수 있는가?
가능하다(name속성)

자바스크립트 내부에서submit 하는데 html에서 버튼의 type은?
type="button"

값 비교에 ===는 무엇을 더 검사하는가?
값, 데이터 타입

## 10주차
쿠키 저장소 대신 사용할 수 있는 영구적인 저장소는?
로컬 스토리지

자바스크립트에서 지원하는 쿠키 객체의 이름은?
document.Cookie

쿠키를 삭제하려면 무엇을 수정해야 하는가?
expries 값 과거로 설정

쿠키를 설정할 때 보안옵션 설정은?
Samesite, secure, HttpOnly

다른 도메인에서 쿠키전송을 차단 하는 정책을 무엇이라 하는가?
Samesite 정책

쿠키 내부의 키(KEY)에저장할 수 있는 데이터타입/자료구조는?
문자열(string)

## 11주차
getElementById를 대체할 수 있는 이 함수는?
querySelector()

세션 스토리지 객체의이름은?
sessionStorage

세션 스토리지에 저장된 모든 정보를 삭제하는 함수는?
sessoinStorage.removeItem("")

기존 쿠키와 세션의 저장 유지하는 방법에 차이점은?
쿠키는 클라이언트에 저장, 세션은 서버에 저장

세션 스토리지의 자료구조의 구성은?
키,값 형태로 문자열만 저장 가능

세션 스토리지는 쿠키에 비해 안전한가?
안전하다 : 세션은 서버에 저장되어 쿠키보다 비교적 안전함함

## 12주차

## 13주차
JS 모듈 시스템의 함수에 대한 접근 제한의 특징은?
모듈 내 선언된 변수나 함수는 기본적으로 외부에서 접근 불가

JS의 OOP 기법의 생성자의 역할은?
클래스 인스턴스 생성 : 객체의 초가값 설정 및 메소드 바인딩

모듈 시스템에서 HTML코드 내 직접 함수 호출방법은 없는가?
없다 : 모듈은 스코프 제한

한글, 영문, 특수문자 등복잡한 문자 조합을 위한 조합식을 무엇이라하는가?
정규표현식(RegExp)

리스너에 등록된DOMContentLoaded의호출 시점은?
문서의 DOM트리가 완성되었을 때 (리소스 로딩 전)

특정 객체로 마우스 포인터를 자동으로 이동하는 함수는?
element.focus() : 정확한 이동은 x
