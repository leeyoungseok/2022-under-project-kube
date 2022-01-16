# 2022-under-project-kube
2022년 학부 졸업프로젝트3 

* * *
# 제목: Kubernetes기반 Private Google Colab 웹 서비스 개발
* * *

# 주제
Tensorflow/Pytorch 등의 AI 실습을 Private Cloud에서 실행할 수 있는 Google Colab 서비스 개발

# 주요내용 
+ Google Colab: 웹 브라우저에서 Python, Tensorflow를 Google Cloud 또는 자기 컴퓨터 자원으로 사용하는 Jupyter
+ 문제점: Google Colab은 Google Cloud 또는 자기 컴퓨터만 활용가능함. 회사에서는 Private Linux cloud를 구축해서 사용할 수 있음. 
+ Private Linux Cloud: GPU를 포함한 리눅스 클라우드를 구축하여 Google Colab과 같은 Web Browser에서 프로그래밍할 수 있는 기능 개발
+ 클라우드 자원 관리 공개 SW: 클라우드 자원관리 공개 SW로 Google Kubernetes가 표준화되어 사용되고 있음.  

# 필요기술
+ Google Colab 지식: Google Colab으로 Python, Tensorflow 프로그래밍 
+ 프론트엔드개발: Google Colab과 같은 Jupyuter 기반 웹 IDE 
+ 백엔드개발: tensorflow, jupyter server, web server, DB, cloud 활용 서버 개발
+ 공개SW Kubernetes : Kubernetes 공개SW 이용 클라우드 관리
+ 리눅스: 서버 관리 및 Kubernetes 활용을 위한 리눅스 필수


# 예상결과
Private Google Coalb 서비스


# 신청방법 및 선정결과
1. 아래 신청사유 적어서 'Pull Request'를 요청
2. 신청한 조가 2개 이상일 경우 평가 후 결과 발표 ('merge')

## 신청사유(자유양식)  

## 지원동기  

- 신청 사유  

팀원 모두 '컴퓨터그래픽스' 교과목을 통해 Google Colab을 통한 python 및 tensorflow 사용 경험이 있고, 공개소프트웨어실습 과목을 수강하며 오픈소스 기여방법 및 오픈소스 개발 시 고려사항 등 오픈소스를 사용하는데에 필요한 주의사항을 배웠습니다.  
Google Colab을 사용하여 개발하면서 팀프로젝트를 수행할 때 여러명이 함께 같은 공간을 사용하여 개발하면 좋을 것 같다는 생각을 했었고, 이 프로젝트의 목표와 일치하여 신청하게 되었습니다. 또한 팀원 모두 Docker 특강을 듣는 등 Docker, Kubernetes, Cloud에 대해 관심이 있으며 이번 프로젝트가 저희에게 좋은 기회가 될 것 같습니다.

- 우리 팀이 잘 할 수밖에 없는 이유
 1. 같은 팀원으로 팀프로젝트를 여러번 수행하여 **팀워크**가 좋고 **의사소통**이 원활합니다.
 2. 학교에서 열리는 행사에 꾸준히 참여하는 **성실함**과 배우고자 하는 열정을 가지고 있습니다.
 3. 새로운 기술을 배움에 거침없고 **적극적인 자세**를 가지고 있습니다.
 4. 팀원 모두 부지런하고 성실한 성격으로, 주어진 시간내에 **책임감**있게 일을 해낼 수 있습니다.

## 팀원소개

### 팀원1

**자기소개**  
저는 웹서비스 및 Backend 개발과 DevOps에 흥미가 있는 학생입니다.   
Docker를 이용해 웹서비스 서버 배포 경험이 있고 클라우드에 대해 더 깊게 배워보고 싶어 해당 프로젝트에 지원하게 되었습니다. 또한 습득력이 빠르고 새로운 기술을 배우는 것에 대한 열정을 가지고 있습니다.  
리눅스 개발환경에 대해 잘 알고 있으며 '기계학습' 과목과 '컴퓨터그래픽스' 과목을 통해 Google Colab 사용 경험이 있습니다. 또한 쿠버네티스를 이번 기회를 통해 배우며 성실히 진행해보고싶습니다! 감사합니다.


**관심 분야**
: `Backend` , `Cloud` 


**이력**  
2021.06 -2021.07 :  2021 하계 실리콘밸리 온라인 인턴십 수료


**프로젝트 경험**

1. 2020.07-2020.09 `MorningCoding`
  - 설명 : 잠금화면에서 Java, Python, C 중 선택한 언어로 코딩문제를 풀 수 있는 안드로이드 앱 개발 
  - 기술 스택 : Java, SQLite

2. 2020.09-2020.12 `InMyStyle`
  - 설명 : 검색 기반 스타일 공유 및 쇼핑몰 추천 사이트 
  - 기술 스택 : HTML, JavaScript, CSS, JQuery, PHP

3. 2021.07-2021.07 `MarkAble`
  - 설명 : 스타트업 대표님과 협업하여 진행한 주제인 상표 등록 가능성을 예측하는  웹서비스 개발 및 배포 
  - 기술 스택 : React, Python, Flask, MongoDB, ElasticSearch, Docker, Gunicorn, prometheus, grafana, AWS S3, EC2 

4. 2021.09-2021.12 `SDD`
  - 설명 : 커스텀 및 저장이 가능한 인공위성 영상 산출물 전시 사이트 
  - 기술 스택 : React, Python, Flask, MySQL, AWS S3 


**개인 사용 가능 언어 및 기술**  
- Java, SpringBoot, JavaScript, Python, Docker , MySQL, MongoDB, SQLite, OracleDB



### 팀원2

**자기소개**   
 웹서비스 및 Frontend에 흥미가 있습니다. JavaScript, Java, Python이 주력 언어이고, Vanila Javascript 및 프레임워크를 사용해서 웹서비스를 개발한 경험이 있습니다. 현재 Javascript에 대해 자세히 공부하고 싶어 'nomad coder'의 강의를 듣고 공부하고 있으며 Java로 알고리즘을 공부하고 있습니다.  
'운영체제 및 실습' 교과목에서 리눅스를 사용해 실습을 해본 경험이 있고 이 프로젝트를 하게 된다면 리눅스를 익숙하게 쓸 수 있도록 열심히 연습하겠습니다.

**관심 분야**
: `frontend`

**이력**  
2019.07 - 2019.08 : 실리콘밸리 단기연수 수료  
2021.06 - 2021.07 :  2021 하계 실리콘밸리 온라인 인턴십 수료 


**프로젝트 경험**
1. 2019.07-2019.09 `albaJava`
- 설명 : javafx를 이용해 만든 구인 구직 App
- 기술 스택 : Java

2. 2020.07-2020.09 `MorningCoding`
- 설명 : 잠금화면에서 Java, Python, C 중 선택한 언어로 코딩문제를 풀 수 있는 안드로이드 앱 개발 
- 기술 스택 : Java, SQLite

3. 2020.09-2020.12 `궁동,어디가지?`
- 설명 : 궁동에 있는 카페, 음식점을 소개하는 웹페이지
- 기술 스택 : Html, Css, Javascript, Php

4. 2021.07-2021.07 `QUIZMAKER`
  - 설명 : 학습지 이미지 데이터에서 문항정보를 추출해 표로 보여주는 플랫폼.  
          스타트업 대표님과 협업하여 진행한 주제로 웹서비스 개발 후 배포 
  - 기술 스택 : React, Gunicorn, PyTorch, Flask, MongoDB, Prometheus, Grafana, Docker, EC2, Yolov5, AWS S3

5. 2021.09-2021.12 `SDD`
  - 설명 : 커스텀 및 저장이 가능한 인공위성 영상 산출물 전시 사이트 
  - 기술 스택 : React, Python, Flask, MySQL, AWS S3 

**개인 사용 가능 언어 및 기술**  
- Javascript, Java, Python, Html, Css, React, OracleDB, Docker

### 팀원3

**자기소개**  
저는 웹, 앱 개발에 대한 흥미가 있어 다양한 경험을 통해 관련지식을 배워나가려고 노력하는 학생입니다. 이러한 지식을 바탕으로 3학년 때는 주어진 요구사항에 맞는 웹사이트를 개발하고 cloud를 사용하여 배포하는 WNC 프로그래밍 대회를 운영하고 평가하였으며 이 과정에서 웹 개발의 전반적인 지식을 다질 수 있었습니다. 또한 Google Colab에서 python, tensorflow을 많이 사용해봤고, 리눅스 사용 경험이 있기 때문에 프로젝트 참여 시 이를 잘 적용할 것입니다. 다양한 오픈소스 사용 경험이 있기에 kubernetes 역시 잘 활용할 수 있습니다. 협동적인 팀원들과 해당 프로젝트에 참여하여 열심히 완성해보고 싶습니다.

**관심분야**
: `backend` `Android 앱`

**이력**  
2021.01 - 2021.12 : ADMIN 동아리 임원(교육부장)
2021.09 - 2021.12 : 컴퓨터프로그래밍2(Java & Android) 튜터
2021.09 - 2021.09 : 제5회 생각하는 프로그래밍 대회 개최
2021.11 - 2021.11 : Web aNd Cloud 프로그래밍 대회 개최
2022.01 - 2022.02 : AI*SW 글로벌 인재 프로그램 퍼듀대학교 파견  

**프로젝트 경험**
1. 2020.06 - 2020.08 `MaskKeeper`  
  - 설명 : 머신러닝 모델을 통해 마스크 착용 여부를 판별하는 웹앱 개발  
  - 기술스택 : HTML, javascript, css, JQuery  

2. 2020.09 - 2020.12 `StructureVisu`  
  - 설명 : 자료구조 삽입, 삭제, 수정 과정에 대한 시각화 사이트  
  - 기술스택 : HTML, javascript, css, JQuery, PHP  

3. 2021.09 - 2021.12 `Part-time Job App`  
  - 설명 : 단기 아르바이트를 위한 구인 구직을 도와주는 웹앱 개발 및 배포  
  - 기술스택 : HTML, javascript, css, JQuery, firebase  

**개인 사용 가능 언어 및 기술**
- Java, SpringBoot, JavaScript, Python, OracleDB, Firebase
