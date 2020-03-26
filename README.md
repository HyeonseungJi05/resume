# Resume

## Language
##### C : 가장 자신있는 언어입니다. 4년정도 사용하고 있으며 OS/소켓 프로그래밍 등에 사용해왔습니다.
##### Python : 3년정도 사용해왔습니다. 머신러닝 및 간단한 코드 작성에 사용하고 있습니다.
##### C++ : 1년정도 사용해왔습니다. 최근에 주로 사용하고 있습니다.
##### Javascript : 1년정도 사용했습니다. 파이썬과 마찬가지로 간단한 코드 작성에 사용하고 있습니다.

##### CUDA : 잠깐 사용하였습니다.

## Web
##### 1. 사용자 입력을 차트로 보여주는 웹 페이지 작성
######  Language : vue.js, D3.js, Tomcat, 아파치 http 서버, MariaDB, Docker
######  아파치 http 서버를 통해 웹서버를 올린 뒤 MariaDB로 DB를 구축했습니다. 
######  DB는 예제로 받은 DB가 있어 이를 MariaDB에 등록하는 과정을 거쳤고 이를 Tomcat과 연동시켰습니다. 사용자는 원할 경우 자신의 데이터 외에도 서버에서 가공된 데이터를 불러와 차트를 볼 수 있도록 하였습니다. 
######  vue.js와 D3.js는 입력에 따라 변하는 차트를 만들기 위해 사용했습니다.
######  마지막으로 완성된 페이지를 배포하는 이미지를 만들어 Dockerhub에 업로드하였습니다.


## Machine Learning
##### 1. 드론에서 촬영한 이미지를 활용한 Object Detection
##### Language : Python, Tensorflow object detection api, SSD lite Mobilenet V2, SSD Mobilenet V3
##### 드론의 임베디드 환경을 고려하여 Intel Neural Compute Stick을 사용했습니다. 공중 촬영한 이미지로 사람을 인식할 수 있습니다.

##### 2. 영화 댓글의 긍/부정 분석
##### Language : Python, KoNLPy
##### 영화 댓글을 입력으로 받으면 댓글의 긍정(ex. 좋아요!)와 부정(ex. 재미없어요..)을 분석해줍니다. Naïve Bayes Classification를 기초로 형태소 분석기를 통해 형태소를 분리하여 입력값으로 넣었습니다.

##### 3. 스포츠 영상의 추천서비스
##### Language : Python, buffalo 등
##### 미디어다음 스포츠영상을 추천하는 서비스의 성능 개선


## Computer Vision
##### Language : OpenCV
##### 1. 패턴인식 : OpenCV를 사용한 패턴인식을 해본 적이 있습니다.
##### 2. 이미지 이진화를 활용한 물체 회피 : 비교적 단순한 이미지 같은 경우 이미지 이진화를 통해서 물체의 형태를 파악, 이를 회피할 수 있는 코드를 만들었습니다.

## Network
##### 1. 오목
##### Language : C
##### 1:1 오목 프로그램을 만들었습니다.

##### 2. Middleware
##### Language : Python
##### Publisher와 Subscriber를 중재해주는 Middleware를 만들었습니다. 다중 중재(Multiple Publisher - Multiple Subscriber)가 가능합니다.

##### 3. Wireshark 활용
#####   1) Wireshark를 활용해서 워게임의 문제들을 해결한 적이 있습니다 (http://xcz.kr/START/prob/prob13.php)

## OS(xv6)
##### 1. 스케줄러 개선
##### Language : C
##### xv6의 Round Robin을 MLFQ+Stride로 만들었습니다.

##### 2. Thread
##### Language : C
##### xv6에 없는 Thread 기능을 추가, 일부 함수를 새로 만들었습니다.

##### 3. 파일처리
##### Language : C
##### xv6에서도 1GB 이상의 대용량의 파일을 처리할 수 있도록 구조를 수정하였습니다.

## Reversing
##### 1. Linux binary file
##### ollydbg를 사용해 binary file을 적절하게 수정하여 사용할 수 있습니다.
##### reversing.kr에서 9개 정도의 문제를 해결하였습니다.
##### Linux binary file의 경우 초~중급 정도의 리버싱 실력이 있다고 생각합니다.
