# 로봇 운영체제 ROS

## ***<ROS란?>***

open-source기반

meta-operating system

**your robot**

**로봇 소프트웨어를 만들기 위한 프레임워크**

## ***<소프트웨어 프레임워크>***

노드간에 메시지 교환 방법으로 복잡한 프로그램을 잘게 나눠 공동 개발 가능

명령어 도구, 시각화 도구 Rviz, GUI 도구 모음 rqt, 3차원 시뮬레이터 Gazebo지원

로보틱스에서 많이 사용되는 모델링, 센싱, 인식, 내비게이션, 매니퓰레이션 기능 지원

**로보틱스 생태계 생성!**

## ***<ROS는 새로운 os인가?>***

ROS = Robot Operating System

ROS는 메타운영체제(Meta-Operating System)이다

### **메타운영체제**

정의된 용어는 아니지만, 어플리케이션과 분산 컴퓨팅 자원간의 가상화 레이어로 분산 컴퓨팅 자원을 활용하여, 스케쥴링 및 로드, 감시, 에러 처리 등을 실행하는 시스템이라고 볼 수 있다.

전통적인 운영체제가 아니고, 전통적인 운영체제를 이용하고 있다.

로봇 응용 소프트웨어 개발을 위한 필수 기능들을 라이브러리 형태로 제공하고 있다.

로봇 소프트웨어 프레임워크를 기반으로 **생태계**를 갖추고 있다.

이기종 디바이스 간의 통신 지원

## ***<ROS를 사용 가능한 운영체제>***

### 기존 전통적인 운영체제

Ubuntu, OS X, Windows, Fedora, Gentoo, OpenSUSE, Debian, Raspbian, Arch, QNX Realtime OS..

스마트폰 운영체제인 Android, iOS 의 경우, 부분적 사용 가능

OS를 탑재할 수 없는 마이크로 컨트롤러 유닛의 경우, 시리얼 통신, 블루투스, LAN 경유로 통신할 수 있는 라이브러리 제공

기본적으로는 **Ubuntu**, OS X 에서 구동하는 것을 추천! (ROS 2.0은 3대 OS 모두 지원)

### ***<ROS의 생태계>***

ROBOT, SENSOR (로봇, 센서 회사) <-> ROS <-> APP (개발자, 유저)

### ***<ROS 특징>***

#### 통신 인프라

노드 간 데이터 통신을 제공

통상적 미들웨어로 지칭되는 메시지 전달 인터페이스 지원

**메시지 파싱 기능**

**메시지의 기록 및 재생**

**메시지 사용으로 인한 다양한 프로그래밍 언어 사용 가능**

**분산 매개 변수 시스템**

#### 로봇 관련 다양한 기능

**로봇에 대한 표준 메시지 정의**

**로봇 기하학 라이브러리**

**로봇 기술 언어**

**진단 시스템**

**센싱/인식**

**내비게이션**

**매니퓰레이션**

#### 다양한 개발 도구

**Conmmand-Line Tools**

**RViz**

**RQT**

**Gazebo**