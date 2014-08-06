seoul_cityhall
==============

서울시청 홈페이지 마크업

```
<!DOCTYPE html>
<!--[if IE 6]> <html class="no-js lt-ie10 lt-ie9 lt-ie8 ie6" lang="ko-KR"> <![endif]-->
<!--[if IE 7]> <html class="no-js lt-ie10 lt-ie9 lt-ie8 ie7" lang="ko-KR"> <![endif]-->
<!--[if IE 8]> <html class="no-js lt-ie10 lt-ie9 ie8" lang="ko-KR"> <![endif]-->
<!--[if IE 9]> <html class="no-js lt-ie10 ie9" lang="ko-KR"> <![endif]-->
<!--[if !IE]><!--> <html class="no-js" lang="ko-KR"> <!--<![endif]-->
<head>

<!-- 언어 인코딩 설정 -->
<meta charset="UTF-8">

<!-- MSIE 호환성 보기 : 최신 브라우저로 적용 -->
<meta http-equiv="X-UA-Comaptible" content="IE=Edge">

<!-- 문서 제목 -->
<title>서울특별시 - 함께 만드는 서울, 함께 누리는 서울</title>

<!-- SEO: 검색 엔진 최적화 -->
<meta name="description" content="">
<meta name="keywords" content="">
<meta name="author" content=""><!-- humans.txt 처리 권장 -->

<!-- 모바일 -->
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">

<!-- 스타일 호출 -->
<link rel="stylesheet" href="./_/css/style.css">

<!-- 파비콘 -->
<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">

<!-- 홈버튼(터치 아이콘) -->
<link rel="apple-touch-icon" href="apple-touch-icon.png">

<!-- 모더나이저 호출 = http://mordenizr.com/ -->
<script src="./_/js/vender/modernizr.custom.js"></script>

<!-- jQuery 호출 = http://jquery.com/ -->
<!-- IE 8- : jQuery 호출 / 마이그레이션 / 로컬 데이터 호출 -->
<!--[if lt IE 9]>
<script src="http://code.jquery.com/jquery.min.js"></script>
<script>window.jQuery||document.write('<script src="./_/js/vender/jquery.min.js"><\/script>')</script>
<![endif]-->

<!-- IE 9+ : jQuery 2 호출 / 로컬 데이터 호출 -->
<!--[if gte IE 9]><!-->
<script src="http://code.jquery.com/jquery-2.1.1.min.js"></script>
<script>window.jQuery||document.write('<script src="./_/js/vender/jquery-2.1.1.min.js"><\/script>')</script>
<!--<![endif]-->

<!-- jQuery Migrate 호출 : 호환성 유지 -->
<!-- <script src="http://code.jquery.com/jquery-migrate-1.2.1.min.js"></script> -->

</head>

<body>

<!-- 브라우저 업그레이드 권장 -->
<!--[if lt IE 9]>
<p class="chromeframe">사용 중이신 브라우저는 오래된 버전의 브라우저이기에 보안 및 성능 문제가 있습니다. <a href="http://www.whatbrowser.org/intl/ko/" target="_blank">빠르고 안전한 최신 브라우저로 업그레이드</a> 하시면 보다 빠르고 안전하게 웹을 이용하실 수 있습니다.</p>
<![endif]-->

<div id="page">
<!-- 시작: #header -->    
    <div id="header">
       <a href="#"><h1><img src="./_/images/seoul_logo.gif" alt="서울특별시 로고"></h1></a>
       <ul class="gnb_top">
           <a href="#">
              <li>서비스 맵</li>
               <li>마이서울</li>
               <li>모바일서울</li>
               <li>라이브서울</li>
               <li>전자우편</li>
               <li>로그인</li>
               <img src="./_/images/icon/icon_new.gif" alt="네비게이션 스토리인서울 new"><li>스토리인서울</li>
           </a>
       </ul>
       <ul class="gnb">
          <a href="#"> 
              <li>서울소개</li>
               <li>뉴스.소식</li>
               <li>시민참여</li>
               <li>전자민원 응답소</li>
               <li>정보소통광장</li>
               <li>분야별정보</li>
          </a>
       </ul>
       <div class="sns lang">
           <a href="#"><img src="./_/images/icon/top_icon_sns.png" alt="트위터 아이콘"></a>
           <a href="#"><img src="./_/images/icon/top_icon_sns.png" alt="페이스북 아이콘"></a>
<!--           <a href="#">English</a>-->
       </div>
<!--
       <div class="unite_search">
           <span>통합검색</span>
       </div>
-->
        
    </div>
<!-- 끝: #header -->

<!-- 시작: .hotissue -->
    <div class="hotissue">
      <ul>
          <li class="issue_left">
              <li>
                  <span>서울 날씨 <strong>약한비계속</strong></span>
                  <strong>22.6</strong>
                  <a href="#"><em>자세한 날씨보기</em></a>
              </li>
              <p>08월 07일 목요일 02시 01분</p>
              <li>
                  <li>
                      <a href="#">
                         <span>미세먼지 평균농도</span>
                         <strong>32</strong>
                      </a>
                  </li>
                  <li>
                      <a href="#">
                         <span>대기환경지수</span>
                          <strong>보통</strong>
                      </a>
                  </li>
                  <li>
                      <a href="#">
                         <span>한남대교 78km/h</span>
                          <strong>소통원활</strong>
                      </a>
                  </li>
              </li> 
          </li>
          <li class="issue_main">
              <a href="#"><img src="./_/images/hotissue/hotissue_ucc.jpg" alt="핫이슈 부분 UCC홍보 이미지"></a>
              <a href="#" class="left"><img src="./_/images/hotissue/btn_hot_left.png" alt="핫이슈 메인 홍보 이미지 이전보기 버튼"></a>
              <a href="#" class="right"><img src="./_/images/hotissue/btn_hot_right.png" alt="핫이슈 메인 홍보 이미지 다음보기 버튼"></a>
          </li>
          <li>
              <div class="thumb">
                  <a href="#"><img src="./_/images/hotissue/sub_right_info.jpg" alt="정책 박람회 대학생 서포터즈"></a>
                  <a href="#"><img src="./_/images/hotissue/sub_right_info2.jpg" alt="서울의 여름나기"></a>
                  <a href="#"><img src="./_/images/hotissue/sub_right_info3.jpg" alt="서울시 공무원 권위적 행태 개선"></a>
              </div>
          </li>
          <li>
              <img src="./_/images/hotissue/prayfor.jpg" alt="세월호 사고 희생자의 명복을 빕니다">
          </li>
      </ul>  
    </div>
<!-- 끝: .hotissue -->

<!-- 시작: #main -->
    <div id="main">
       <!-- 시작: .service -->
        <div class="service">
            <ul class="service">
                <li>
                    <strong>[서울톡톡]</strong>
                    <span>바이러스 대유행, 안심해도 될</span>
                    <img src="./_/images/service_virus.jpg" alt="서울톡톡 입국시 발열 기침 인후통 설사 복통의 증상이 나타나면 검역관에게 신고하세요">
                </li>
                <li>
                    <strong>[정보]</strong>
                    <span>서울생활 꿀팁! 온라인 생활백서</span>
                    <img src="./_/images/service_info.jpg" alt="정보 서울시민을 위한 생활 깨알팁 ">
                </li>
                <li>
                    <strong>[소통방통]</strong>
                    <span>중소기업 직장 어린이집 대폭</span>
                    <img src="./_/images/service_commu.jpg" alt="중소기업 직장 어린이집 대폭 확대">
                </li>
            </ul>
            <ul class="service_menu">
                <li>부서안내</li>
                <li>청사안내</li>
                <li>이슈와 논란</li>
                <li>전체 사이트</li>
                <li>재난유형별 행동요령</li>
                <li>천만상상 오아시스</li>
                <li>서울특별시의회</li>
                <li>서울특별시교육청</li>
            </ul>
            
        </div>
        <div class="service_search">
<!--
            <div class="search_top">
                <h2>서비스 찾기</h2>
                <div class="search_box">
                    
                </div>
                <h2>추천 검색어</h2>
            </div>
-->
           <div class="search_bottom">
               <a href="#">서울안전누리<img src="./_/images/search_bottom_ui/seoul_safety.gif" alt=""></a>
               <a href="#">공공서비스예약<img src="./_/images/search_bottom_ui/service_reservation.png" alt=""></a>
               <a href="#">보육포털서비스<img src="./_/images/search_bottom_ui/baby_care.png" alt=""></a>
               <a href="#">토지정보시스템<img src="./_/images/search_bottom_ui/land_info_service.png" alt=""></a>
               <a href="#">일자리플러스센터<img src="./_/images/search_bottom_ui/workplus.png" alt=""></a>
               <a href="#">부동산정보<img src="./_/images/search_bottom_ui/house_info.png" alt=""></a>
               <a href="#">서울관광정보<img src="./_/images/search_bottom_ui/sightseeing_info.gif" alt=""></a>
               <a href="#">서울문화포털<img src="./_/images/search_bottom_ui/seoul_culture.gif" alt=""></a>
               <a href="#">평생학습포털<img src="./_/images/search_bottom_ui/study.png" alt=""></a>
               <a href="#">서울시보<img src="./_/images/search_bottom_ui/seoul_news.png" alt=""></a>
           </div>
        </div>
        <!-- 끝: .service -->
        
        <!-- 시작: .information -->
        <div class="information">
            <ul>
                <li class="online_commu">
                    <h2>온라인 시장실</h2>
                    <a href="#"><img src="./_/images/online_communication.png" alt="박원순 서울시장 현장 시장실 1년간의 이야기"></a>
                    <ul class="list">
                        <a href="#">
                           <li>라이브원순</li>
                            <li>원순씨 희망일기</li>
                            <li>원순씨에게 바랍니다</li>
                            <li>매니페스토 공약</li>
                            <li>정책토론회</li>
                        </a>
                    </ul>
                    <a href="#"><img src="./_/images/btn_online_mayor.gif" alt="현장시장실 버튼"></a>
                    <a href="#"><span>바로가기</span></a>
                </li>
                <li class="about">
                   <h2>알림창</h2>
                   <ul>
                       <a href="#">
                          <li>민원사무서식 다운로드</li>
                           <li>서울의 인구는? <strong>서울통계 보기</strong></li>
                           <li>서울사진은행 와우서울</li>
                           <li>반부패,청렴시책</li>
                           <li>서울 인포그래픽스로 보기</li>
                           <li>어린이 홈페이지 꾸러기세상</li>
                      </a>
                      <div class="more">
                          <span>1/1</span>
                     <a href="#"><img src="./_/images/btn_event_prev.gif" alt="알림창 더보기 이전버튼"></a><!--     배경이미지로 틀 들어감-->
                          <a href="#"><img src="./_/images/btn_event_next.gif" alt="알림창 더보기 다음버튼"></a>
                      </div>
                   </ul> 
                </li>
                <li class="banner">
                    <a href="#"><img src="./_/images/banner_hospital.jpg" alt="환자 안심병동 운영"></a>
                    <div class="more">
                        <span>1/13</span>
                        <a href="#"><img src="./_/images/btn_event_prev.gif" alt="배너 이전보기"></a>
                        <a href="#"><img src="./_/images/btn_event_next.gif" alt="배너 다음보기"></a>
                        <a href="#"><img src="./_/images/information_icon.png" alt="배너 그림으로 보기 아이콘"></a>
                        <a href="#"><img src="./_/images/information_icon.png" alt="배너 리스트 목록으로 보기 아이콘"></a>
                    </div>
                </li>
            </ul>
        </div>
        <!-- 끝: .information -->
        
        
    </div>
    
</div>
<!-- 끝: #page -->

<!-- 스크립트 실행 파일 호출 -->
<!-- <script src="./_/js/application.js"></script> -->
</body>
</html>
```
