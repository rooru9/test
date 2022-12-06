<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Le jour 코딩</title>
    <script src="./jquery-3.6.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.js"></script>
    <script src="./scroll.js" defer></script>
    <script src="./lejour.js" defer></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css"/>
    <link rel="stylesheet" href="./scroll.css">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="./tablet.css" media="all and (min-width:768px) and (max-width:1024px)">
    <link rel="stylesheet" href="./phone.css" media="all and (max-width:768px)">
</head>
<body>
    <div class="top">
        <a href='#' target="_top">↑</a>
    </div>
    <header>
        <nav>
            <div class="inner">
                <a href="#" class="logo"><img src="./image/logo.svg" alt=""></a>
                <div class="gnb">
                    <ul>
                        <li><a href="#">brand story</a></li>
                        <li class="sub"><a href="#">product</a></li>
                        <li><a href="#">contents</a></li>
                        <li><a href="#">review</a></li>
                        <li><a href="#">Q&A</a></li>
                        <li><a href="#">notice</a></li>
                        <li><a href="#">event</a></li>
                        <li><a href="#">membership</a></li>
                    </ul>
                </div>
                <div class="gnb_right">
                    <select name="lag" id="lag">
                        <option value="kor">korean</option>
                        <option value="eng">english</option>
                    </select>
                    <ul class="top_nav">
                        <li><a href="#">login</a></li>
                        <li><a href="#">join</a></li>
                        <li><a href="#">cart <img src="./image/cart.png" alt="장바구니"></a></li>
                        <li class="search"><a href="#"><img src="./image/search.png" alt="돋보기"></a></li>
                    </ul>
                </div>
            </div>
            <div class="snb">
                <div class="slide_menu">
                    <ul>
                        <li class="main_tit">
                            <a href="#">Product</a>
                        </li>
                       <li class="title">
                            <a href="#">Le Jour SET</a>
                        </li>
                        <li>
                            <a href="#">세탁세제&섬유연제</a>
                        </li>
                        <li>
                            <a href="#">주방용품</a>
                        </li>
                        <li class="title">
                            <a href="#">Le Jour PRODUCT</a>
                        </li>
                        <li>
                            <a href="#">세탁세제&섬유유연제</a>
                        </li>
                        <li>
                            <a href="#">주방/탈취 용품</a>
                        </li>
                        <li>
                            <a href="#">욕실용품</a>
                        </li>
                        <li>
                            <a href="#">세탁 보조제</a>
                        </li>
                        <li>
                            <a href="#">기프트 액세서리</a>
                        </li>
                        <li class="title">
                            <a href="#">Le Jour COSMETICS</a>
                        </li>
                        <li>
                            <a href="#">로션/크림</a>
                        </li>
                    </ul>
                    <p>
                        <img src="./image/nav_img.jpg" alt="">
                    </p>
                </div>
            </div>
        </nav>
    </header>
    <div class="main-slider">
        <ul class="swiper-wrapper">
            <li class="swiper-slide"><img src="./image/slide1.jpg" alt=""></li>
            <li class="swiper-slide"><img src="./image/slide2.jpg" alt=""></li>
            <li class="swiper-slide"><img src="./image/slide3.jpg" alt=""></li>
            <li class="swiper-slide"><img src="./image/slide4.jpg" alt=""></li>
            <li class="swiper-slide"><img src="./image/slide5.jpg" alt=""></li>
        </ul>
    </div>
    <main>    
        <div class="event">
            <div class="event_content">
                <h1>join us</h1>
                <p>회원가입시 적립금 2,000원을 드려요</p>
            </div>
            <div class="event_content">
                <h1>review</h1>
                <p>리뷰를 남겨주시면 적립금을 드려요</p>
            </div>
            <div class="event_content">
                <h1>contents</h1>
                <p>다양한 콘텐츠를 통해서 Le Jour의 따뜻함을 느껴보세요</p>
            </div>
        </div>
        <section>
            <h1>Le Jour's selection</h1>
            <div class="cate">
                <a href="javascript:void(0);" class="active">세트</a>
                <a href="javascript:void(0);">세제</a>
                <a href="javascript:void(0);">섬유유연제</a>
                <a href="javascript:void(0);">주방/탈취용품</a>
                <a href="javascript:void(0);">욕실용품</a>
                <a href="javascript:void(0);">세탁보조제</a>
                <a href="javascript:void(0);">로션/크림</a>
                <a href="javascript:void(0);">기프트액세서리</a>
            </div>
            <div class="menu_list">
                <ul>
                    <li>
                        <a href="#">
                            <img src="./image/main_001.png" alt="">
                            <div class="txt">
                                <p>Le Jour Family Set</p>
                                <p>르주르 패밀리 세트</p>
                                <p class="price"><span>102,000원</span>91,800원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_002.png" alt="">
                            <div class="txt">
                                <p>Le Jour Baby Set</p>
                                <p>르주르 베이비 세트</p>
                                <p class="price"><span>53,000원</span>49,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_003.png" alt="">
                            <div class="txt">
                                <p>Le Jour Single Set</p>
                                <p>르주르 싱글족 세트</p>
                                <p class="price"><span>49,000원</span>45,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_004.png" alt="">
                            <div class="txt">
                                <p>Le Jour Kitchen Set</p>
                                <p>르주르 키친 세트</p>
                                <p class="price"><span>32,000원</span>30,000원</p>
                            </div>
                        </a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <a href="#">
                            <img src="./image/main_011.png" alt="">
                            <div class="txt">
                                <p>Le Jour Laundry Detergent For Adult</p>
                                <p>르주르 일반 액체세제</p>
                                <p class="price">24,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_012.png" alt="">
                            <div class="txt">
                                <p>Le Jour Laundry Detergent For Baby</p>
                                <p>르주르 유아 액체세제</p>
                                <p class="price">26,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_013.png" alt="">
                            <div class="txt">
                                <p>Le Jour Washing Powder For Adult</p>
                                <p>르주르 일반 가루세제</p>
                                <p class="price">18,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_014.png" alt="">
                            <div class="txt">
                                <p>Le Jour Washing Powder For Baby</p>
                                <p>르주르 유아 가루세제</p>
                                <p class="price">19,000원</p>
                            </div>
                        </a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <a href="#">
                            <img src="./image/main_021.png" alt="">
                            <div class="txt">
                                <p>Le Jour Febric Conditioner For Adult</p>
                                <p>르주르 일반 섬유유연제</p>
                                <p class="price">25,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_022.png" alt="">
                            <div class="txt">
                                <p>Le Jour Febric Conditioner For Baby</p>
                                <p>르주르 유아 섬유유연제</p>
                                <p class="price">27,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_023.png" alt="">
                            <div class="txt">
                                <p>Pure Febric Conditioner For Baby</p>
                                <p>구연산 유아 섬유유연제(코튼캔디)</p>
                                <p class="price">27,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_024.png" alt="">
                            <div class="txt">
                                <p>Pure Febric Conditioner For Baby(Unscented)</p>
                                <p>구연산 유아 섬유유연제(무향)</p>
                                <p class="price">27,000원</p>
                            </div>
                        </a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <a href="#">
                            <img src="./image/main_031.png" alt="">
                            <div class="txt">
                                <p>Le Jour Dress Perfume</p>
                                <p>르주르 드레스 퍼퓸(프렌치 라벤더)</p>
                                <p class="price">15,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_032.png" alt="">
                            <div class="txt">
                                <p>Le Jour Dress Perfume</p>
                                <p>르주르 드레스 퍼퓸(플뢰르 코롱)</p>
                                <p class="price">15,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_033.png" alt="">
                            <div class="txt">
                                <p>Le Jour Dishwasher Detergent</p>
                                <p>르주르 식기세척기 세제(코랄 허니)</p>
                                <p class="price">17,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_034.png" alt="">
                            <div class="txt">
                                <p>Le Jour Kitchen Cleaner</p>
                                <p>르주르 키친 워싱 클리너</p>
                                <p class="price">15,000원</p>
                            </div>
                        </a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <a href="#">
                            <img src="./image/main_041.png" alt="">
                            <div class="txt">
                                <p>Le Jour Hand Wash</p>
                                <p>르주르 핸드워시</p>
                                <p class="price">18,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_042.png" alt="">
                            <div class="txt">
                                <p>Le Jour Toilet Cover Cleaner</p>
                                <p>르주르 토일렛 커버 클렌저</p>
                                <p class="price">10,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_043.png" alt="">
                            <div class="txt">
                                <p>Le Jour Bathroom Cleaner</p>
                                <p>르주르 욕실 클렌저</p>
                                <p class="price">17,000원</p>
                            </div>
                        </a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <a href="#">
                            <img src="./image/main_051.png" alt="">
                            <div class="txt">
                                <p>Le Jour Washing Machine Cleaner</p>
                                <p>르주르 세탁기 클렌저</p>
                                <p class="price">13,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_052.png" alt="">
                            <div class="txt">
                                <p>Le Jour Boil-Wash Cleaning</p>
                                <p>르주르 삶는 클리닝</p>
                                <p class="price">14,000원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_053.png" alt="">
                            <div class="txt">
                                <p>Le Jour Filter Sheets</p>
                                <p>르주르 필터 시트</p>
                                <p class="price">38,000원</p>
                            </div>
                        </a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <a href="#">
                            <img src="./image/main_061.png" alt="">
                            <div class="txt">
                                <p>Le Jour Baby Lotion</p>
                                <p>르주르 베이비 로션</p>
                                <p class="price"><span>21,000원</span>16,800원</p>
                            </div>
                        </a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <a href="#">
                            <img src="./image/main_071.png" alt="">
                            <div class="txt">
                                <p>Le Jour Shopping Bag + Le Jour Gift Box</p>
                                <p>르주르 쇼핑백 + 르주르 기프트박스</p>
                                <p class="price"><span>5,000원</span>4,500원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_072.png" alt="">
                            <div class="txt">
                                <p>Le Jour Shopping Bag</p>
                                <p>르주르 쇼핑백</p>
                                <p class="price">1,500원</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="./image/main_073.png" alt="">
                            <div class="txt">
                                <p>Le Jour Gift Box</p>
                                <p>르주르 기프트박스</p>
                                <p class="price">3,500원</p>
                            </div>
                        </a>
                    </li>
                </ul>                
            </div>
            <div class="more"><p>more view</p></div>
        </section>
        <div class="slider event_slide">
            <ul class="swiper-wrapper">
                <li class="swiper-slide"><img src="./image/e_slide01.jpg" alt=""></li>
                <li class="swiper-slide"><img src="./image/e_slide02.jpg" alt=""></li>
                <li class="swiper-slide"><img src="./image/e_slide03.jpg" alt=""></li>
            </ul>
            <div class="swiper-button-next"></div>
            <div class="swiper-button-prev"></div>
        </div>
        <section>
            <h1>Review</h1>
            <div class="review">
                <ul class="swiper-wrapper">
                    <li class="swiper-slide">
                        <p class="photo"><img src="./image/review1.jpeg" alt=""></p>
                        <div class="review-txt">
                            <p class="review-con">
                                기다리고 기다리던 필터가 나왔네요. 비싸지만 궁금해서 구매해봤어요. 제품력은 진짜 최고네요!! 향을 표현하고 싶은데 말로는 표현이 안되요 건조기 시트로 많은 제품을 써보진 않았지만 처음 맡아본 향이에요 고급진향이에요
                            </p>
                            <ul>
                                <li>
                                    <p>
                                        Le Jour Filter Sheets
                                    </p>
                                    <p>르주르 필터 시트</p>
                                </li>
                                <li>★★★★★</li>
                            </ul>
                        </div>
                    </li>
                    <li class="swiper-slide">
                        <p class="photo"><img src="./image/review2.jpeg" alt=""></p>
                        <div class="review-txt">
                            <p class="review-con">
                                세정력도 좋고 향도 강하지 않아서 좋아요:) 추가 구매예정입니다.
                            </p>
                            <ul>
                                <li>
                                    <p>
                                        Le Jour Dish Washing Detergent
                                    </p>
                                    <p>르주르 주방세제</p>
                                </li>
                                <li>★★★★★</li>
                            </ul>
                        </div>
                    </li>
                    <li class="swiper-slide">
                        <p class="photo"><img src="./image/review3.jpeg" alt=""></p>
                        <div class="review-txt">
                            <p class="review-con">
                                뽀득뽀득 잘 씻기는 르주르 주방세제 쓸 때마다 너무 만족하면서 써요^^
                            </p>
                            <ul>
                                <li>
                                    <p>
                                        Le Jour Dish Washing Detergent
                                    </p>
                                    <p>르주르 주방세제</p>
                                </li>
                                <li>★★★★★</li>
                            </ul>
                        </div>
                    </li>
                    <li class="swiper-slide">
                        <p class="photo"><img src="./image/review4.jpeg" alt=""></p>
                        <div class="review-txt">
                            <p class="review-con">
                                상자가 예쁘고 튼튼해요 상자에 간단히 메모도 작성할 수 있어서 좋네요
                            </p>
                            <ul>
                                <li>
                                    <p>
                                        Le Jour Shopping Bag + Le Jour Gift Box
                                    </p>
                                    <p>르주르 쇼핑백 + 르주르 기프트박스</p>
                                </li>
                                <li>★★★★★</li>
                            </ul>
                        </div>
                    </li>
                    <li class="swiper-slide">
                        <p class="photo"><img src="./image/review5.jpeg" alt=""></p>
                        <div class="review-txt">
                            <p class="review-con">
                                너무 좋아요 향도 좋고 배송도 빠르구!! 자주 이용할 것 같아용. 용량이 쪼꼼 아쉽긴하네요ㅠ
                            </p>
                            <ul>
                                <li>
                                    <p>
                                        Le Jour Hand Wash
                                    </p>
                                    <p>르주르 핸드워시</p>
                                </li>
                                <li>★★★★★</li>
                            </ul>
                        </div>
                    </li>
                    <li class="swiper-slide">
                        <p class="photo"><img src="./image/review6.jpeg" alt=""></p>
                        <div class="review-txt">
                            <p class="review-con">
                                우아 이거 향이 다 했어요! 공중화장실 말고 세척, 소독해야 하는 곳에도 사용하고 있어요!
                            </p>
                            <ul>
                                <li>
                                    <p>
                                        Le Jour Toilet Cover Cleaner
                                    </p>
                                    <p>르주르 토일렛 커버 클렌저</p>
                                </li>
                                <li>★★★★★</li>
                            </ul>
                        </div>
                    </li>
                </ul>
            </div>
            <div class="swiper-button-next"></div>
            <div class="swiper-button-prev"></div>
        </section>
        <section>
            <h1>#Instagram</h1>
            <ul class="insta">
                <li><a href="#"><img src="./image/insta1.jpg" alt=""></a></li>
                <li><a href="#"><img src="./image/insta2.jpg" alt=""></a></li>
                <li><a href="#"><img src="./image/insta3.jpg" alt=""></a></li>
                <li><a href="#"><img src="./image/insta4.jpg" alt=""></a></li>
                <li><a href="#"><img src="./image/insta5.jpg" alt=""></a></li>
                <li><a href="#"><img src="./image/insta6.jpg" alt=""></a></li>
            </ul>
        </section>
    </main>
    <footer>
        <section>
            <div class="foot-top">
                <div class="foot-left">
                    <div class="notice">
                        <ul>
                            <li>NOTICE</li>
                            <li class="notice-slide">
                                <p>[NOTICE] ★ 르주르 대한아토피협회 추천 제품으로 선정</p>
                                <p>[NOTICE] ★ 택배비 인상 안내</p>
                                <p>[NOTICE] ★ 르주르 오프라인 입점 안내</p>
                                <p>[NOTICE] ★ 르주르 홈페이지 리뉴얼로 인한 안내사항</p>
                                <p>[NOTICE] ★ 루즈르 2022 올해의 브랜드 대상 영유아세제 부분 수상</p>
                            </li>
                        </ul>
                    </div>
                    <div class="info">
                        <div class="cs-box">
                            <ul>
                                <li>고객센터</li>
                                <li>1522-8625</li>
                                <li>운영시간 AM 10:00 - PM 06:00 (주말 및 공휴일 휴무)</li>
                                <li>점심시간 PM 12:00 - PM 01:00</li>
                            </ul>
                        </div>
                        <div class="ac-box">
                            <ul>
                                <li>계좌안내</li>
                                <li>국민 670701-04-220781</li>
                                <li>예금주 르주르(주)</li>
                                <li class="btn-box">
                                    <p class="qna">Q&A</p>
                                    <p class="faq">FAQ</p>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="foot-right">
                    <a href="#">
                        <img src="./image/foot-right.png" alt="">
                    </a>
                </div>
            </div>
        </section>
        <section class="foot-bottom">
            <div class="fnb">
                <ul>
                    <li>
                        <a href="#"><img src="./image/logo.svg" alt=""></a>
                        <p class="copyright">Copyright© All right reserved by Le Jour</p>
                    </li>
                    <li>
                        <p class="foot-tit">CUSTOMER CENTER</p>
                        <p>반품주소 : 광주광역시 광산구 수완로 73번길 17, 4층(수완동, 리코빌딩)</p>
                        <p>고객센터 : 1522-8625</p>
                        <p>팩스번호 : 0504-035-3865</p>
                        <p>운영시간 AM 10:00 - PM 06:00 (주말 및 공휴일 휴무)</p>
                        <p>점심시간 PM 12:00 - PM 01:00</p>
                        <p>BANKINFO : 국민은행 670701-04-220781</p>
                        <p>예금주 : 르주르(주)</p>
                    </li>
                    <li>
                        <p class="foot-tit">LINKS</p>
                        <p><a href="#">이용약관</a></p>
                        <p><a href="#">개인정보 취급방침</a></p>
                        <p><a href="#">이용안내</a></p>
                    </li>
                    <li>
                        <p class="foot-tit">CS CENTER</p>
                        <p><a href="#">공지사항</a></p>
                        <p><a href="#">FAQ</a></p>
                        <p><a href="#">Q&A</a></p>
                    </li>
                    <li>
                        <p class="foot-tit">ACCOUNT</p>
                        <p><a href="#">로그인</a></p>
                        <p><a href="#">회원가입</a></p>
                        <p><a href="#">아이디/비밀번호 찾기</a></p>
                        <p><a href="#">멤버쉽</a></p>
                    </li>
                    <li>
                        <p class="foot-tit">OUR STORY</p>
                        <p><a href="#">브랜드스토리</a></p>
                        <p><a href="#">콘텐츠</a></p>
                    </li>
                </ul>
            </div>
            <div class="ft-company">
                <p>르주르주식회사 | 대표자 : 김건우</p>
                <p>개인정보취급관리자 : 김종석 | 이메일 : <a href="#">lejour90@naver.com</a></p>
                <p>주소 : 광주광역시 광산구 수완로73번길 17 3층 301호(수완동, 리코빌딩) | 사업자등록번호 : 412-87-00709 <a href="#" class="license">사업자번호조회></a> | 통신판매업신고번호 : 제2017-광주광산-0506호</p>
                <div class="ft-sns">
                    <ul>
                        <li><a href="#"><img src="./image/sns_insta.png" alt=""></a></li>
                        <li><a href="#"><img src="./image/sns_facebook.png" alt=""></a></li>
                        <li><a href="#"><img src="./image/sns_youtube.png" alt=""></a></li>
                    </ul>
                </div>
                <div class="ft-certify"></div>
            </div>
        </section>
    </footer>
</body>
</html>
