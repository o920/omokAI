# 오목 인공지능 게임

#### 기간 : 2019년 4~6월 (약 1개월)<br/>목적 : '인공지능' 수업 과제<br/>인원/역할 : 개인 <br/>의의 : 첫 인공지능 프로젝트, 알파고의 알고리즘 구현<br/>한계 : PyQT에 미숙하여 UI가 잘 실행되지 않음<br/>


#### 사용 언어 : Python<br/>구현 환경 : Visual Code 1.34.0

#### Detail
* 평가함수 직접 작성
* 알파고 알고리즘 구현
  > Min-Max Algorithm, Alph-Beta Pruning

#### 사용 모듈
pygame, sys, random, numpy, copy, enum
* Pygame 
  > pygame 모듈은 파이썬 언어를 통해서 게임을 만들 수 있도록 지원해주는 모듈이다. <br/>
  > Prompt 창에 ‘pip install pygame’ 명령어를 사용하여 설치할 수 있다.
* Sys 
  > 명령행 인자를 처리할 때, 인자들을 sys 모듈의 속성에 리스트로 저장되게한다. <br/>
  > 파이썬 표준 라이브러리에 있으므로 따로 다운로드 받을 필요는 없다.
* Numpy 
  > 행렬 즉 배열의 정의와 계산을 위해서 사용하는 모듈이다. <br/>
  > 이 모듈은 ‘python -m pip install (파일 경로)’ 명령어를 사용하여 설치할 수 있다.
* Copy 
  > 객체나 변수를 복사해낼 수 있는 모듈이다. 파이썬 표준 라이브러리에 있으므로 따로 다운로드 받을 필요는 없다. <br/>
  > Copy모듈 에서도 deepcopy를 import했다. Deepcopy를 하고 나면 원래의 객체나 변수를 수정하여도 copy한 객체나 변수는 변하지 않는다.
* Enum 
  > 서로 관련 있는 상수들을 모아서 클래스처럼 명칭의 집합으로 정의할 수 있는 모듈이다. <br/>
  > ‘conda install -c menpo enum’ 명령어를 통해서 설치했다.
