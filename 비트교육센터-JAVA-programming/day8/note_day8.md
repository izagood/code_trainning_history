# day8

## ArrayList < E >
  
벡터와 달리 스레드 동기화 기능 없음
  다수 스레드가 동시에 ArrayList에 접근할 때 동기화되지 않음
  개발자가 스레드 동기화 코드 작성
  
## Iterator < E >
순서가 없는 객체들을 반복하여 돌릴 수 있다.

객체.iterator();


## HashMap < key, value >
순서 없이 들어감

## 제네릭

제네릭 -> < >

class 파일이 기계어로 컴파일 되고 실질적으로 실행이 될때 타입이 확정됨.
class 파일이 JVM에서 실행될 때 < E >의 타입이 확정이 됨.

## GUI 라이브러리

### awt
GUI 껍데기

기존의 os의 도움을 받아서 만듬

컨테이너
Panel, Frame, Applet, Dialog, Window

### swing
JVM 에서 돌아간다
awt가 os의 도움을 받아야해서 느리고 os에 따라 모양이 다른다

그래서 추가적으로 라이브러리가 만들어졌다.

컨테이너 = 컴포넌트를 담을 수 있는 클래스
JPanel, JFrame, JApplet, JDialog, JWindow

최상위 컨테이너(독립적으로 pop-up 될 수 있음)
JFrame, JDialog, JApplet

## JavaFX
swing이 너무 무겁기 때문에 모바일에서 사용하기 위해 JavaFX가 최근에 주로 쓰인다.

## FileIO
파일 입력 출력하는 동작

## 조언
가장 빠르게 실력이 상승하는 방법

메모장 어플리케이션 -> 그것에 맞는 클래스를 공부 -> 완성

실제로 프로젝트를 완성해 보아야 한다.
