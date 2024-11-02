#  Toktalk

<p align="center">
비대면 심리 상담 서비스 <br>
Toktalk!</p>

<p align="center">
    <img src="https://toktalk-storage.s3.ap-northeast-2.amazonaws.com/image/toktalk.png" width="400"/>
</p>

<p align="center">
    <strong>Toktalk</strong>은 우울증을 호소하지만 대면 상담을 꺼려하는 사람들을 위해, <br> 시간과 장소에 구애 받지 않고 
비대면으로 심리 상담을 받을 수 있는 서비스를 제공합니다.
</p>

<br> 
<br> 
  
## 🚩 개요
- 프로젝트 이름 : Toktalk
- 프로젝트 기간 : 2024.09.23 ~ 2024.10.18

<br>


## ✨기술스택

### 공통
<img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white"> <img src="https://img.shields.io/badge/Socket.io-010101?&style=for-the-badge&logo=Socket.io&logoColor=white"> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" width="90" height="25" style="margin-bottom: 20px; display: block;" />
<br>
    
### 백엔드
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"> 
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)

![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![SpringSecurity](https://img.shields.io/badge/SpringSecurity-6DB33F.svg?style=for-the-badge&logo=SpringSecurity&logoColor=white)

<img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=for-the-badge&logo=Amazon AWS&logoColor=white"> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white">
<img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">

![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Windows](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=macos&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
<br>

### 프론트엔드
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/reactnative-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
<br>
<br> 


## 📖 개발 문서

### 사용자 기능 정의서
[Toktalk-사용자기능정의서](https://docs.google.com/spreadsheets/d/1hTXPtqSm0-TfreD6YDV7OjoGXLJM5EcBrwWiUu-YdOE/edit?gid=0#gid=0)

### ERD
[Toktalk-ERD](https://dbdiagram.io/d/66d67b36eef7e08f0e7ce579)

### API 명세서
[Toktalk-API명세서](https://docs.google.com/spreadsheets/d/1LRlVrv9YjJwhcFjobObjsSQG63fPyL1gVmaUg4kTPy0/edit?gid=254563277#gid=254563277)

<br>
<br>

> ### 주요 기능
**1. 회원가입 및 로그인**
- 필수 정보 입력
- 아이디 검증, 닉네임 검증
- PASS 인증
- 자격증, 경력사항 입력(상담사)

**2. 우울증 자가 진단** 
- 로그인시 우울증 자가 진단 실행
- 마이 페이지에서 재진단 가능  

**3. 상담 예약** 
- 상담사를 조회하여 상담사 선택
- 상담 방식 선택, 상담사 일정 확인
- 날짜 및 시간 선택, 상담 내용 작성
- 토스페이먼츠를 통한 결제
- 상담 일정 하루 전까지 취소 가능

**4. 실시간 채팅** 
- 상담 조회후 채팅방 활성화
- 실시간 1:1 채팅을 통한 상담
- 상담 종료시 채팅방 비활성화

**5. 알림 기능**
- 상담사
- 회원이 상담 예약 시
- 회원이 상담 취소 시
- 회원이 리뷰 작성 시
  
- 회원
- 상담사가 예약 취소 시
- 상담사가 채팅방 활성화 시
- 상담사가 리포트 작성 시 

**6. 마이 페이지**
- 상담사
- 프로필 수정
- 예약된 상담 조회
- 일정 관리

- 회원
- 상담 내역 조회
- 우울증 자가 진단 조회

<br><br>

## 🙏Team List

|**[고경범](https://github.com/KoKyungBeom)(팀장)**|**[황진혁](https://github.com/JINHYEOKKK)**|**[조한재](https://github.com/whgkswo)**|**[은하늘](https://github.com/skyla00)**|
|:--:|:--:|:--:|:--:|
|<img src="" width="150px" height="150px">|<img src="" width="150px" height="150px"> | <img src="" width="150px" height="150px"> | <img src="" width="150px" height="150px">|

<br>

> ### 역할 분담
<img src = "" />

## 🔍Page Preview

| 회원가입 및 로그인 | 오늘의 기분 등록(회원) |
| :---: | :---: |
| <img src="" width="400" height="200"/> | <img src="" width="400" height="200"/> |

|  우울증 자가 진단(회원)  | 상담 예약(회원) |
| :---: | :---: |
| <img src="" width="400" height="200"/> | <img src="" width="400" height="200"/> |

| 상담 취소(회원) | 리뷰 작성(회원) |
| :---: | :---: |
| <img src="" width="400" height="200"/> | <img src="" width="400" height="200"/> |

| 프로필 수정(상담사) | 프로필 사진 변경(상담사) |
| :---: | :---: |
| <img src="" width="400" height="200"/> | <img src="" width="400" height="200"/> |

| 요금 관리(상담사) | 기본 일정 관리(상담사) |
| :---: | :---: |
| <img src="" width="400" height="200"/> | <img src="" width="400" height="200"/> |

| 특정일 일정 관리(상담사) | 채팅(회원,상담사) |
| :---: | :---: |
| <img src="" width="400" height="200"/> | <img src="" width="400" height="200"/> |

| 채팅방 닫기(상담사) | 리포트 작성(상담사) |
| :---: | :---: |
| <img src="" width="400" height="200"/> | <img src="" width="400" height="200"/> |


<br> 
<br> 



    
