---
layout: page
title: Doctor pitch Tech stack
permalink: /about/
---

먼저

 더 좋은 개발을 하고자 하는 욕심에
개발스택안내 및 개발을 보여드리는 부분의 지연에 대해

 진심으로 사과드립니다.


저희측에서 개발을 다 해놨지만
  서버사용량 및 높은 트래픽에 대한
 대응을 위해 여러 작업을 하던 도중에

 서버 사용량 트래픽 대응에 대한 작지않은 이슈가 있었습니다.
이 사항에 대해선 밤낮없이 고쳐봐도 꽤 오래 시간이 걸렸던 것 같습니다.

현재 이 글을 작성하는 시간엔 이러한 큰 이슈들을 해결하면서 앞으로도
서비스가 되면서 일어날 가능성이 있는 자잘한 버그 이슈들까지 모두 해결했습니다.


 해당 부분에대해선 다시 한번 고개숙여 사과드립니다.


<br><br><br>





## Doctor pitch 기술스택
### 프론트엔드 Service
<div style="display: flex; justify-content: space-between; max-width: 600px; margin: 20px;">
     <div style="width: 200px; height: 150px;">
        <img src="/public/img/icon_flutter_dk-blue.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>  
     <div style="width: 200px; height: 150px;">
        <img src="/public/img/dart.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>
         <div style="width: 200px; height: 150px;">
        <img src="/public/img/nestjs.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>

 <div style="width: 200px; height: 150px;">
        <img src="/public/img/gradle.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>
    
</div>

<div style="display: flex; justify-content: space-between; max-width: 600px; margin: 20px;">
     <div style="width: 200px; height: 150px;">
        <img src="/public/img/figma.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>
     <div style="width: 200px; height: 150px;">
        <img src="/public/img/android.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>
     <div style="width: 200px; height: 150px;">
        <img src="/public/img/swift.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>

          <div style="width: 200px; height: 150px;">
        <img src="/public/img/grunt.jpg" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>

    
</div>

- Flutter, Dart, Nest.js, Gradle, Figma, Android, Swift, Grunt
    
<br>






### 백엔드 Service

<div style="display: flex; justify-content: space-between; max-width: 600px; margin: 20px;">
  
    <div style="width: 200px; height: 150px;">
        <img src="/public/img/dart.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>
        <div style="width: 200px; height: 150px;">
        <img src="/public/img/node js.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>
    <div style="width: 200px; height: 150px;">
        <img src="/public/img/gradle.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>
</div>



<div style="display: flex; justify-content: space-between; max-width: 600px; margin: 20px;">
    <div style="width: 200px; height: 150px;">
        <img src="/public/img/firebase.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>
     <div style="width: 200px; height: 150px;">
        <img src="/public/img/firebase cloudstorage.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>

       <div style="width: 200px; height: 150px;">
        <img src="/public/img/firebase auth.png" alt="alt text" style="width: 100%; height: 100%; object-fit: contain;  padding: 5px;" />
    </div>
</div>

- Dart, Node.js, Gradle, Firebase, Firebase, Firebase Auth,  Firebase Clode Storage






<!-- The rest of the content remains the same as provided -->


<br>
<br>

### 백엔드 서버부문 안내도

> 저희가 제작한 닥터피치에서 어떻게하면 최소한의 서버비용으로 최소한의 효율을 낼지 저희 개발팀에 대한 고충을 나타냅니다


저희 개발팀에서 최대한 효율적이며 서비스상 비용이 가장많이 나올 수 밖에 없는 부분을 최소한으로 하고자 많은 고민을 했었습니다.


저희 개발팀이 생각했을때 개발에 가장 중요한 부분은 서버의 안정성과 갑자기 많은 유저가 들어와도 , 서버의 사용량이 높아져도 서버가 터지지 않고 

최대한 안정적으로 유저들의게 서비스를 제공하는것 이라고 생각합니다. 

이부분에 대하여 많이 고민해본결과
현재 만들어진 어플리케이션이 최대한 효율적으로 많은 사용자들의게 서비스를 제공하기 위해서 저희가 사용을 결정한 서버 BackEnd는 Firebase 였습니다. 
<br><br><br>

### 유저관리방식
> Firebase를 통해 유저를 관리합니다. KaKao로그인 및 자신의 이메일을 이용하여 회원가입이 가능하며, 관리자페이지를통해 해당 유저의 계정을 바꿔준다던지, 회원탈퇴를 시켜준다던지 계정을 정지할 수 있는 기능을 지원합니다. ( 구글로그인을 통해 관리가 용이합니다 )

![alt text](/public/img/authScreen.png)

<br>
사이트를 이용하여 사용자의 이메일 주소 , 전화번호 또는 사용자 UID를 통해 유저를 쉽게 검색할 수 있는 시스템이며 이를통해 사용자 관리또한 용이하게 가능합니다.

<br><br>

### 데이터 관리
> Firebase를 통해 데이터를 관리합니다.


![alt text](/public/img/DB.png)

<br>
해당 사진은 저희 회사에서 닥터피치를 개발하면서 설계한 데이터베이스 구조입니다. Firebase는 NoSQL 방식으로
Chating, Doctors, Events, FreeTalks(게시판), Hospitals, prepays,
users,reviews,TempReplies(댓글) 등여러가지 컬렉션을 통해 서비스가 동작될 최대한의 효율을 이끌어내기 위해 노력했습니다.

FireBase에서 정확한 데이터의 통계와 서버사용량 , 유저 관리 등을 용이하게 할 수 있습니다. 

이 사항은 저희가 생성한 GoogleID를 제공해드리겠습니다.

 로그인하셔서 직접 들어가셔서 확인가능합니다.





<br>
<br>
<br>



### 병원 및 의사등록에 대한 고충
> 저희 개발팀은 의사와 병원의 효율적인 등록을 위해 노력했습니다 

![alt text](/public/img/scrennshot.png)


해당 사항은 위 사진과 같이 이메일로 받아서 직접 등록하는 방식을 채택하게 되었습니다.

 현재 바비톡과 같이 관리자 페이지를 제작하는 사항에 있어서는 저희가 저번에 이메일로 말씀드린 대로 개발 계약을 진행될때 확인이 안됐던 부분이라 
 
 진행을 원하시면 조금더 업데이트를 통한 개발이 필요해 보입니다.
 따라서 현재는 감사하게도 제공주신 사이트를 통해 이메일로 등록할 수 있는 몇가지 목록들을 정리할 수 있었습니다.
 


#### 바비톡 관리자 홈페이지에서 등록할 수 있는 사항 
  - 의사 등록
  - 병원 이벤트 등록
  - 병원 등록

해당 사항들은 바비톡 사이트에서 등록하는 방식으로 이부분은 이메일로 정보를 보내어 등록을 진행 할 수 있게끔 했습니다. 바비톡 사이트에서 요구하는 정보들 

( ex:) 의사면허증 , 병원 이벤트 사진 메인사진 ) 등등의 여러가지 옵션들은 저희측에서 나중에 관리자페이지를 제작하게된다면

 제작에 용이하도록 변수나 시스템 설정까지 모두 완료한 상태이며 현재도 해당 사항들은 정보를 입력할때 사용할 수 있게끔 하였습니다.

 해당 정보들은 이메일등을 이용하여 아까말씀드린 Firebase에서 쉽게 정보를 입력하여 등록할 수있습니다.
 
  ( Firebase에서 등록하게 되면 의사 , 이벤트 페이지 등등이 바로바로 동기화됩니다. )
