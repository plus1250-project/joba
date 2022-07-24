# :loudspeaker: 트렌드를 JOBA

## :radio: 프로젝트 주제
기사 산업군 분류와 키워드 분석을 통한 산업군 트렌드 분석

## :hourglass: 프로젝트 기간
`2022년 5월 23일 ~ 2022년 7월 24일`

## :high_brightness: 팀 소개

**팀명: +125°** &#x1F321;&#xFE0F;   
**팀장: 김영애**  
:cyclone: 김영애 : 데이터 ETL, 데이터 파이프라인 설계 및 구축  
:ocean: 김종원 :  백엔드 , 프론트엔드 ,docker 구축  
&#x1F9A6; 양지현 :  데이터 ETL , 프론트엔드  
:hamster: 오다솔 :  백엔드  
 :runner: 이동빈 :  데이터 ETL, AI 
 
## :movie_camera: 기능 구현 
![image](https://user-images.githubusercontent.com/97663140/180639315-e8f00d35-d429-495d-8456-4dea82bee7a1.png)
![image](https://user-images.githubusercontent.com/97663140/180639326-ec6096b5-c7b3-4111-97d6-94ac4c923af3.png)
![image](https://user-images.githubusercontent.com/97663140/180639332-63aa98ea-00e4-4c62-b220-6a4f0372dedf.png)
![image](https://user-images.githubusercontent.com/97663140/180639340-1b1f22df-b8dc-4088-b35c-89a08b21d332.png)
![image](https://user-images.githubusercontent.com/97663140/180639348-c41a65b2-fd27-4367-a1e4-0639bef93f6a.png)
![image](https://user-images.githubusercontent.com/97663140/180639353-a4ce9d09-e268-413d-b039-9ea6b100a8be.png)
![image](https://user-images.githubusercontent.com/97663140/180639359-e9808afe-6a67-4a17-8c1b-1a3230d18d57.png)



## :wrench: 기술 스택
### 인프라 구축
<img src="https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white">  
<img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/RedHat-EE0000?style=for-the-badge&logo=redhat&logoColor=white">
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
<img src="https://img.shields.io/badge/Apache%20Tomcat-F8DC75?style=for-the-badge&logo=Apache%20Tomcat&logoColor=white">

### 데이터 파이프라인
<img src="https://img.shields.io/badge/Apache%20Hadoop-66CCFF?style=for-the-badge&logo=Apache%20Hadoop&logoColor=white">
<img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=Apache%20Spark&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white">
<img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apache%20Airflow&logoColor=white">

### 백엔드
<img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white">
<img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot">

### 프론트엔드
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=Redux&logoColor=61DAFB">

## :bomb: 이슈

### 데이터 
1. KoBERT 정확도 
- 계획대로 훈련 데이터 셋을 생성하여 훈련을 시켰을 때, 정확도가 기대에 미치지 못하는 문제 발생.
- 훈련 데이터의 양을 늘리고 하이퍼 파라미터를 조정함으로써 해결하였음. 
2. 키워드 추출
- 기사 안의 명사를 카운팅하는 워드 카운트를 실행하였을 때 의미없는 단어들이 상위권에 위치하는 문제 발생.
- 키워드 추출 모델인 KeyBERT를 사용하여 기사 하나당 키워드 하나를 추출하도록 변경하여 카운팅하여 해결.
### 웹 
1. state 관리 
- 부모자식 컴포넌트 간의 state 관리는 props로 가능하지만, 관계가 없는 컴포넌트는 state 관리가 어려운 문제
- Redux를 사용하여 state를 관리함으로써 해결하였음. 
2. JWT 
- :3 


## :thought_balloon: 앞으로 개선 사항 
1. Airflow 자동화 구축
-  HDFS와 모델을 연결
2. 프론트 도커라이징
3. 로그인 Redis 활용 토큰 관리  


<i class="devicon-pytorch-plain-wordmark"></i>


## :scroll: WIKI 
<a href="https://github.com/plus1250-project/joba/wiki/1.-%EA%B0%9C%EC%9A%94">
    <img src="https://img.shields.io/badge/-JOBA%20WIKI-CDDEFF?style=for-the-badge&labelColor=EEF2FF"
/>
</a> 

