<p align="center">
  <img width="150" align="center" src="https://user-images.githubusercontent.com/58170545/128740164-436adc63-0497-4f2d-b6c4-9ce43b71fba0.png" alt="incar"/>
</p>

<div align="center" style="font-weight:bold;">INCAR : 인하대 카풀 어플 개발</div>
<br>

* 개요 <br>
학교 게시판 '인하광장'에서 인하대 카풀 어플이 있었으면 좋겠다는 게시글에서 아이디어를 얻어 프로젝트를 진행하게 되었습니다.
학생, 교직원이 학교 근처에 거주하는 경우보다 그렇지 않은 경우가 많기에 자차를 사용하는 학교 내부인이 빈좌석을 공유하는 것을 목표로 하였습니다.
운전자, 탑승자 모두 게시글을 작성하여 카풀이 이루어지도록 어플을 설계하였습니다.
<br>
 
## 📋 Description

| 항목          | 내용                                                      |
| ------------- | --------------------------------------------------------- |
| 프로젝트명    | INCAR                                                     |
| 프로젝트 목적 | 인하대 학생들의 더 편한 학교생활을 위한 인하대 전용 카풀 앱 개발 |
| 기간          | 2019.06 ~ 2021.03 (10개월)                                |
| 팀원          | 김진우 박주원 조민경 홍다솔                               |
<br>

## 📁 Document Structure

```
├─ INCAR
│  ├─ INCAR_server
│  │      ├─ README.md
│  │      └─ WER-INF
 |    |              ├─ web.xml
│  │      └─ WebContent/META-INF
 |    |              ├─ MANIFEST.MF
 |    |       └─ src
 |    |              ├─ main/java/ac/inhaventureclub
 |    |                       ├─ controller
 |    |                       └─ repository
 |    |                       └─ service
 |    |                       └─ serviceImpl
 |    |                       └─ util
 |    |                       └─ vo
 |    |                       └─ websocket
 |    |                       └─ IncarServerApplication.java
 |    |                       └─ ServletInitializer.java
 |    |              └─ test/java/ac/inhaventureclub 
 |    |                       ├─ IncarServerApplicationTests.java
 |    |       └─ .gitignore
 |    |       └─ build.gradle
 |    |       └─ gradlew
 |    |       └─ gradlew.bat
 |    |       └─ settings.gradle      
│  ├─ INCAR_client
│  │      ├─ README.md
│  │      └─ 등등
│  └─ README.md
│

```
<br>

### 🛠 기능

1. 회원가입
- 인하대학교 학생, 교직원만 가입가능하도록 인증(메일 발송 확인)
- 이메일:ID = 1:1

2. 프로필
- 운전자, 탑승자 두가지 모드 설정
- 개인 프로필 사진, 프로필 메세지 설정

3. 게시판
- 현재 시간을 기준으로 이후 게시물들만 게시
- 시간에 따른 게시글 정렬
- 출발, 도착 위치별 검색

4. 게시글
- 날짜, 시간, 위치, 가격 선택
- 게시글에서 요청 가능
- 요청 수락시 리뷰, 별점 작성

5. 개인 게시글 관리 탭
- 모드별 요청 받은 게시글, 요청한 게시글 확인 
- 작성된 리뷰, 별점 확인
- 게시글로 연결된 사용자간 채팅
<br>


### ✨ Demo

0. 전체 Demo
<center>
<img src="https://user-images.githubusercontent.com/58170545/128745216-6d944bf7-0916-4cbb-b5e7-657658ffb60c.gif" width="40%" height="40%"/>
</center>

1. 회원가입
<center>
<img src="https://user-images.githubusercontent.com/58170545/128745365-780ab1e7-14de-483f-8690-9f384e300052.gif" width="40%" height="40%" />
</center>

2. 로그인
   (gif)

3. 글 등록하기
   (gif)

<br>

### ✨ INCAR DB 구조
<br>

<center>
<img src="https://user-images.githubusercontent.com/58170545/128822226-d4192b0b-47df-497b-8f18-68c8151e3997.png"/>
</center>
<br>

## ✨ Tech Stack

1. **Frontend**
   - Android Studio
2. **Backend**
   - Spring
   - Spring Boot
   - Spring MVC
   - Spring Data JPA
3.  **Cloud**
    - AWS EC2
    - AWS RDS
4. **Configuration Management**
   - GitLab
   - Notion
   
## 🤝 Contributing

| <img src="https://avatars.githubusercontent.com/u/53468768?v=4" alt="img" style="zoom:25%;" /> | <img src="https://avatars.githubusercontent.com/u/58173061?v=4" alt="@ka-yeon" style="zoom:25%;" /> | <img src="https://avatars.githubusercontent.com/u/58170545?v=4" alt="Avatar" style="zoom:25%;" /> | <img src="https://avatars.githubusercontent.com/u/81455416?v=4" alt="img" style="zoom:25%;" /> |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|             [jinwoo](https://github.com/iv-club)             |            [juwon](https://github.com/juwon0605)             |            [mim](https://github.com/ChoMinkyung)             |             [dazory](https://github.com/dazory)              |

## 📝 Contact

> If you have any questions, please email below. <br>
>
> - jinwoo: 12161550@inha.edu
> - mim: 12181837@inha.edu
> - juwon: devprofessionalism@gmail.com
> - dazory: 12181851@inha.edu
