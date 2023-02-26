<h1>반응형 웹디자인&웹퍼블리셔 양성과정 버전기록</h1>
<p>ex) 날짜 - 제목 - 요약</P>
<h2>23.02.13 시작 - HTML</h2>
<p>H1~H6, p, br, inline, block</p>
<p>H1~H3은 검색키워드로 활용가능하다. H4~H6 꼭 필요한 경우만 이용하거나 권장안함</p>
<p>block과 inline태그는 의미에 맞게 외부/내부 구조로 구성해서 사용해야 한다.(의미 중첩되지 않도록)</P>
<hr>
<h2>23.02.14 - HTML - 0214_start 업로드, 문서태그+내비게이션 개념</h2>
  <p>&lt;<strong>strong</strong>&gt;,&lt;<em>em</em>&gt;,&lt;sub&gt;,&lt;sup&gt;,&lt;s&gt;,&lt;del&gt;,&lt;blockquote(hr)&gt;,&lt;q&gt;,&lt;code&gt;, &lt;address&gt;,&lt;hr&gt;</P>
<p>gnb, lnb, snb, fnb, breadcrumbs</p>
<blockquote cite="https://webty.tistory.com/85"></blockquote> 유나쌤 블로그 참고 - https://webty.tistory.com/85
<hr>
<h2>23.02.14 - HTML - 0215_first 업로드, 목록태그</h2>
<ul>
  <li><p>ul,ol,li 순서 있는 목록 없는 목록 구분 확실히 해야함.</p></li>
  <li><p>li의 <em>형제태그는</em> li만 올 수 있으니 나머지 태그는 그 자식, 자손태그에 삽입해야한다.</p></li>
  <li><p>ul을 기재할 때 L과 I를 헷갈리지 않게 써야 한다.</p></li>
  <li><p>OL를 부모로 둔 LI는 번호가 자동으로 매겨진다.</p></li>
  <li> 이중구조로 li를 추가할 때 li 옆으로 ul을 추가해야 하는 걸 주의해야 한다. </li>
  <li> 이중구조로 li를 추가할 때 추가한 ul이 부모 li의 오른쪽에 위치해 있는지를 확인해야 한다. </li>
  <li> 리스트를 구분할 때 사용한다. 퍼블리싱을 하는데 매우 많이 사용되는 태그 </li>
</ul>
<dl>
   <dt>정의형 목록</dt>
      <dd> dl 안에는 dt(제목)과 dd(내용)이 포함되어 있다.</dd>
      <dd> 정의형 목록 작성의 좋은점 </dd>
      <dd>UL-Li는 다른 구성이 됨, 추가 그룹을 만들어야 함</dd>
      <dd>dl-dt는 묶음으로 구성이 됨, 추가 그룹을 만들 필요 없음</dd>
  <dd>쇼핑몰에서 물건을 볼 때 가격이나 사이즈, 색상을 고르는 칸에서 주로 사용하거나 전자사전에서 제목과 내용을 구분 지을 때 사용한다.</dd>
</dl>
<hr>
<h2>23.02.16 - HTML - 0216_dldtdd 업로드, main, div</h2>
<main>
<div class="study">
  <h2>23.02.16 - HTML - 시맨틱태그, 그룹태그 </h2>
  <dl>
    <dt>가장 많이 쓰게 될 div 태그</dt>
    <dd>div - 프레임의 그룹 역할 담당, 그룹, div만은 새폴더 개념으로 이름을 가지고 있지 않음. 별도의 이름 선언을 반드시 해야 함.</dd>
    <dd>위치에 맞게 이름 쓰는 게 편함</dd>
    <dd> &lt;ex&gt; title_path_top → 테이틀 있고 내용 있음</dd>
    <dd>contents → 내용 묶음</dd>
    <dd>_btm → 아래</dd>
    <dd>class - 태그의 이름</dd>
    <dd>추후 skip이라는 이름을 주면 CSS에서 해당 skip과 관련된 태그를 보이지 않게 처리할 수 있음.</dd>
  </dl>
</div>
</main>
<hr>
<h2>23.02.17 - HTML - div, img, video, ../, ./ alt의 의미, a href, 하이퍼링크</h2>
<dl>
  <dt>a 태그는 html4까지는 인라인 태그.></dt>
  <dd>5부터 상황에 따라 블록이나 인라인 어디에도 쓸 수 있게 됨</dd>
<dl>
  <h3><a href=" "> 링크 주소 속성</h3>
    <p>href 속성 안 값은 링크 목적지 주소를 정확히 입력해야 합니다.</p>
    <ul>
      <li>링크주소는 일반적으로 '절대경로', '상대경로' 로 나뉩니다.</li>
      <li>링크주소로 메일, 전화번호를 작성할 수도 있습니다.</li>
      <li>메일은 mailto:메일아이디@메일주소 로 작성합니다.</li>
      <li>전화번호는 tel:국가번호.전화번호앞자리.전화번호뒷자리로 작성합니다.</li>
      <li><a href="mailto:abc@google.com">메일보내기</a></li>
    </ul>
    <dl>
      <dt>연속적으로 제목이 등장하면 목록 개념</dt>
      <dd>li의 경우 내용이고 h1이 제목을 담당하기에 h2 대신에 li가 들어가도 무방함</dd>
      <dd>li는 a의 부모</dd>
      <dd>1개와 a가 사용될 때에는 일반적으로 a가 자식</dd>
      <dd>2개와 a가 사용될 때에는 a가 부모가 될 때가 많음 - 쇼핑몰에서 많이 사용하는 기능 - 두 개의 아이템을 클릭해도 같은 사이트로 이동하게 만들고 싶을 때.</dd>
      <dd>a를 사용할 때에는 href를 꼭 안에 넣어야 함.</dd>
    </dl>
<hr>
23.02.20-Table
<hr>
<table>
  <thead>
     <tr>
       <th>구분</th>
       <th>태그명</th>
       <th>의미</th>
    </tr>
  </thead>
 <tbody>
   <tr>
     <td rowspan="3">block</td>
     <td>&lt;tr&gt;</td>
     <td>&lt;가로행 태그&gt;</td>
   </tr>
   <tr>
     <!--td-->
     <td>&lt;td&gt;</td>
     <td>&lt;내용(열)태그&gt;</td>
   </tr>
   <tr>
     <!--td-->
     <td>&lt;th&gt;</td>
     <td>&lt;제목(열)태그&gt;</td>
   </tr>
  </tbody>
<hr>
  <body>
    <table>
        <thead>
            <tr>
                <th scope="col">업체</th>
                <th scope="col">요금제명</th>
                <th scope="col">데이터</th>
                <th scope="col">음성</th>
                <th scope="col">문자</th>
                <th scope="col">월 정액<br>(부가세 포함금액)</th>
                <th scope="col">상세</th>
                <th scope="col">비교</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th scope="row">Amobile</th>
                <td><span>추천</span><br>요금폭탄방지 매일 2GB</td>
                <td><em>11GB</em><br>(초과시 매일<br>2GB+3MB 속도로<br>무제한 이용)</td>
                <td>기본제공(영상/부가 300분)</td>
                <td>기본제공</td>
                <td>월<em>20,900</em>원</td>
                <td><span>가입하기</span></td>
                <td><span>선택하기</span></td>
            </tr>
            <tr>
                <th scope="row">Amobile</th>
                <td><span>추천</span>A<br>데이터 무제한</td>
                <td><em>15GB</em><br>(초과시 3Mbps 속도<br>로 무제한 이용)</td>
                <td>100분</td>
                <td>100건</td>
                <td>월<em>16,500</em>원</td>
                <td><span>가입하기</span></td>
                <td><span>선택하기</span></td>
            </tr>
            <tr>
                <th scope="row">smarttel</th>
                <td><span>추천</span><br>스마트 톡(Talk)</td>
                <td><em>100MB</em><br>(초과시 400Mbps 속<br>도로 무제한 이용)</td>
                <td>50분</td>
                <td>-</td>
                <td>월<em>6,000</em>원</td>
                <td><span>가입하기</span></td>
                <td><span>선택하기</span></td>
            </tr>
            <tr>
                <th scope="row">yeoyou</th>
                <td><span>추천</span><br>여유 100</td>
                <td><em>100MB</em><br>데이터 차단기능/차<br>단시 100MB이용불<br>가</td>
                <td>100분</td>
                <td>100건</td>
                <td>월<em>3,300</em>원</td>
                <td><span>가입하기</span></td>
                <td><span>선택하기</span></td>
            </tr>
        </tbody>
    </table>
</body>
<hr>
  <h2>23.02.21-HTML-form</h2>
  <form action="#" method="get">
    <fieldset>
      <legend>form 퀴즈</legend>
      <span>다음 중 label for와 연관된 input 속성은?</span><br>
      <label><input type="radio" name="quiz" value="id">1. id</label><br>
      <label><input type="radio" name="quiz" value="class">2. class</label><br>
      <label><input type="radio" name="quiz" value="name">3. name</label>
      <span>다음 중 autofocus가 사용될 수 없는 input 속성은?</span><br>
      1. <dd><input type="text" autofocus placeholder="아이디를 입력하세요" name="user_id" maxlength="7"></dd><br>
      2. <dd><input type="number" autofocus placeholder="아이디를 입력하세요" name="user_id" maxlength="7"></dd><br>
      3. <dd><input type="tel" autofocus placeholder="아이디를 입력하세요" name="user_id" maxlength="7"></dd><br>
      <fieldset>
        </form>
<hr>
      <h2>2023.02.22.total review</h2>
<hr>
<h2>2023.02.23.HTML -> CSS</h2>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700&display=swap');


html, body, h1, h2, h3, h4, h5, h6,
p, ul, ol, li, blockquote, dl, dt, dd, address, video,
strong, em, del, sup, sub, s, q, code, img, a
table, tr, th, td, thead, tbody, tfoot,
form, fieldset, legend, label, input, textarea, option, select, button,
header, main, footer, article, section, aside, nav, figure, figcaption,
div, span {
    /* 글꼴적용방법1. 사용자 컴퓨터에 내장된 글꼴 불러오기*/
    /* (위)주의사항 : 해당 글꼴이 접속한 사용자에게 없을 경우 글꼴이 임의의 다른 글꼴로 대체될 수 있다. */
    /* font-family : '맑은 고딕',sans-serif; */
    /* font-family : '궁서체',serif; */

    /* 글꼴적용방법2. 웹 주소 글꼴을 가져오는 방법 */
    font-family: 'Noto Sans KR', sans-serif;
    margin : 0; padding : 0;
    font-size : 1.0rem;
    font-weight : normal;
    font-style : normal;
    line-height : 1.0;
    list-style : none;
}
a {text-decoration : none; color: #000;}
table, tr, th, td {border-collapse:collapse;}
button {cursor:pointer; border : none; background : none;}
<hr>
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="keywords" content="">
    <meta name="description" content="">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>경영이념 | SPC삼립</title>
    <!-- 외부스타일시트, 링크 연결하는 파일은 목적에 따라 구분되게끔 되어있다. 리셋이 메인보다 반드시 밑에 있어야 한다. 디자인이 리셋 되어버리기 때문-->
    <link href="./styles/main.css" rel="stylesheet" type="text/css">
    <link href="./styles/reset.css" rel="stylesheet" type="text/css">
</head>
<body>
    <header>
        <h1><a href="#"><img src="./images/logo.png" alt="SPC삼립"><!-- alt SPC삼립에 로고라는 설명을 더 붙이지 말 것 --></a></h1>
        <nav>
            <a href="#">COMPANY</a>
            <a href="#">BRANDS</a>
            <a href="#">IR</a>
            <a href="#">SNS</a>
            <a href="#">RECRUIT</a>
        </nav>
        <div class="lnb"><!-- lnb, right_lnb, right_menu, user_menu, user_lnb -->
            <a href="#">CUSTOMER</a>
            <a href="#">검색</a>
        </div>
    </header>
    <main>
        <div class="bg">
            <dl class="top">
                <dt>현재 페이지 경로</dt>
                <dd>HOME <span>Company</span> SPC삼립 소개 <em>경영이념</em></dd>
            </dl>
        </div>
        <div class="bg_w">
            <div class="title">
                <h1>경영이념</h1>
                <p>반세기 역사와 전통을 지닌 듬직한 기업 SPC삼립 입니다.</p>
            </div>
        </div>
        <div class="bg">
            <div class="contents">
                <p>SPC삼립은 반세기 역사와 전통을 지닌 전문 종합식품기업입니다.<br>
                1945년 창사 이래 지금까지 국민 식생활개선에 맞추어<br>
                소비자와 함께 하는 식품기업으로 성장해온 SPC삼립.<br>
                지난 반세기 동안 축적해온 경험과 기술을 바탕으로 소비자들에게<br>
                최상의 품질을 지닌 제품과 서비스를 제공하기 위해 최선의 노력을 다하고 있습니다.</p>
            </div>
        </div>
        <div class="bg_w">
            <div class="contents">
                <h2>VISION 2025</h2>
                <p>Best Bakery, Food, Service로<br>Happy Life를 창조</p>
                <h2>VISION</h2>
                <p>Top 3 종합식품기업<br>글로벌 식품회사로서 디지털 유통 혁신 선도</p>
            </div>
        </div>
        <div class="bg">
            <div class="contents">
                <h2>GOAL</h2>
                <ul>
                    <li>매출 2.7조</li>
                    <li>영업이익 5%</li>
                    <li>기업가치 2.5조</li>
                </ul>
                <h2>STRATEGY</h2>
                <ul>
                    <li>
                        <h3>Value Up</h3>
                        <p>브랜드 및 고부가 제품 라인업 강화</p>
                    </li>
                    <li>
                        <h3>Expansion</h3>
                        <p>카테고리 확대/글로벌 확장</p>
                    </li>
                    <li>
                        <h3>pioneer</h3>
                        <p>유통/제품 혁신을 통한 시장 선도</p>
                    </li>
                    <li>
                        <h3>Focus</h3>
                        <p>핵심 역량의 집중, 통한 시장 선도</p>
                    </li>
                    <li>
                        <h3>Smart&aggressive</h3>
                        <p>개인과 조직의 창의적 혁신, 도전적 성장</p>
                    </li>
                </ul>
            </div>
        </div>
    </main>
    <footer>
        <div class="ft_top">
            <div class="ft_left">
                <a href="#">개인정보처리방침</a>
                <a href="#">거래희망회사 사전등록</a>
                <a href="#">동반성장</a>
            </div>
            <div class="ft_right">
                <a href="#">FAMILY SITES</a>
                <a href="#">SITE MAP</a>
            </div>
        </div>
        <address>고객센터 전화번호 080-739-8572 (월~금 09:00~17:00)<br>
        경기도 시흥시 공단1대로 101(정왕동) (주)SPC삼립 대표이사 황종현</address>
        <p>&copy; SPC Samlop. All right reserved</p>
    </footer>
</body>
</html>
<!-- 
    레이아웃 태그 : header, section, main, nav, artile, footer, figure, div, span
    제목 태그 : h1~h6, dt
    목록 태그 : ol-ul-li
    내용 태그 : p, dd
    인라인 태그 : em, strong, sup, sub, q, del, s, br, code
-->
<!-- 작업 파일 확장자에 따른 폴더 분류
    프로젝트명/images (jpg, png, gif, svg)
    프로젝트명/video (mp4, mp3, ogg)
    프로젝트명/styles - (CSS)
    프로젝트명/script - 자바 스크립트 (js)
    html 파일은 프로젝트명 내부에
    바로 보이는 위치에 생성한다 (별도 폴더 생성x)
    ★항상 처음 생성하는 html파일명은
    index.html로 제작해야 한다. (규칙)
-->
main .bg {background-color : #f1f1f1;}
<hr>
      <h2>2023.02.24.CSS</h2>
      CSS

---

링크 중에 리셋을 앞에 둘 것. 뒤에 두면 리셋을 해버리기 때문.

개별로 폰트를 넣어주려면 디자인 CSS에

한꺼번에 입혀주려면 리셋 CSS에 넣는다

px은 고정값이라 기기에 따라 크기가 커지고 작아짐, em은 상대적인 값이라 변환 가능

em의 문제 - 상대적이기 때문에 부모의 폰트값에도 영향을 미침

1.0em이 16px인 이유는 바디 기준으로 16px이 설정되어 있기 때문에

em이 아니라 rem이라고 쓰는 이유 - 부모의 상대 크기를 인식하는 게 아니라 body의 값을 항상 인식하게 하기 위해

rem 단위를 쓰는 게 권장됨

---

### line-height 행간

```css
line-height:1.5;
line-height:150%;
line-height:150px;
```

### letter-spacing 자간

```css
letter-spacing:0;
letter-spacing:-0.5px;
letter-spacing:-0.05em;
```

여기는 em을 많이 씀

기본적으로 -0.0부터 쓰고 그 다음에 숫자가 달라짐

-.0.02는 피그마에서 -2%의 값

```css
font-family : '맑은 고딕',sans-serif; /* 15px */
    font-size : 0.938rem;
    line-height:1.5;
    letter-spacing:-0.02em; /* figma -2% */
```

주로 이 4가지 기능을 기본으로 씀

### word-spacing 단어와 단어 사이 간격

```css
word-spacing:1px;
word-spacing:-0.05em;
```

자간과 다르게 기본적으로 -가 아니라 + 0.0~으로 시작함

text-transform:lowercase;

대문자를 소문자로

text-transform:uppercase;

소문자를 대문자로

text-transform:capitalizee;

맨앞만 글자 대문자로

text-decoration:underline;

밑줄표시

font-style:italic;

기울기

text-decoration:line-through;

취소선

같은 그룹이 있다면 먼저 쓰고 이름 있는 것을 나중에 쓰는 게 좋음

font-weight 폰트 굵기

클래스가 들어간 것도 같은 값이면 이름만 가진 같은 것이다.

같은 값에 행간이나 크기 조절이 되어 있으면 클래스에 개별로 처리할 필요가 없음

---

### FAVICON - 탭에 페이지를 구별하기 위해 만든 이미지

외울 필요 없이 복사해서 사용 가능

<link rel="shortcut icon" href="파비콘.ico 경로" type="image/x-icon">
<link rel="icon" href="파비콘.ico 경로" type="image/x-icon">

---

웹페이지에서 선 긋기

상하좌우에 선을 긋고 좌우의 선을 지우는 방법

처음부터 상하에만 선을 긋는 방법

제목을 한 칸 띄면 아예 새로운 이름으로 하겠다는 거 “X X”는 이름 두 개 “X”는 이름 하나

---

인라인 블록은 인라인과 블록 속성을 다 가지고 있다는 점

## display 요소 표시 속성 ( block / inline / inline-block )

HTML이 가지는 기본 요소의 속성을 다른 속성으로 변경 시 또는 요소를 숨기거나 표시할 경우 사용합니다.

크기나 여백을 사용할 때는 그 대상이 블록/인라인 어느쪽에 해당되는 대상인지를 먼저 체크하고

그에 따른 속성과 값을 배치해야 합니다.

그 때 필요에 따라 display라는 CSS 속성이 사용됩니다.(필수가 아닌 상황에 따른 선택적 속성)

```css
display:none;
display:inline;
display:block;
display:inline-block;
```

## block 요소 특징

ex) h1~6, p, div, blockquote, dl, dt, dd, ol, ul, li, header, footer, nav, main, section, article, video, iframe, table, tr, td, th, thead, tbody, tfoot, hr, form, filedset 등

- 기본 너비 100%를 가지고 있습니다.
- 크기, 여백 적용이 가능합니다.
- 너비100%와는 별도로 항상 줄바꿈이 이루어집니다.

## inline 요소 특징

ex) a, img, span, em, strong, i, del, s, q, code, button, input, select, option, legend, label, br 등

- 인라인 태그 내 내용(텍스트 및 이미지)의 크기만큼만 인식합니다.
- 크기를 적용할 수 없습니다.
- 여백(margin, padding)이 적용은 되나 크기 적용불가 특징으로 인해 주변 요소와 겹침현상이 발생합니다.
- 줄바꿈이 되지 않고 옆으로 나열됩니다.

## inline-block 요소 특징

- CSS display 명령으로 적용할 수 있습니다.
- 크기, 여백 적용이 가능합니다.
- 줄바꿈이 되지 않고 옆으로 나열됩니다.
- 인라인-블록 요소 사이 기본 공백이 포함됩니다.

margin - 해당 오브젝트의 바깥쪽을 벌려라

padding - 너비는 그대로, 패딩값이 더해지면 그 부분에 기존 높이나 넓이에 더해진다.

box-sizing:border-dox; 원래 값을 계산해서 넣어주는 옵션, 고정됨, 여백이 안 들어가는 데가 없고 그 때마다 많이 쓸 거임. 리셋에 넣는 게 좋음.

*- 전체 선택자, 전체에 적용하라는 뜻 * box-sizing:border-dox; 박스 사이징을 전체에 적용해라

padding, margin은 누구를 기준으로 하느냐에 따라 값을 주는 대상과 수치가 달라짐

CSS에서는 h1의 경우 그 글자만큼의 크기만 가진다

```css
/*margin: 요소와 요소 사이를 떨어뜨릴 때 */
/* padding:요소와 그 안 내용 사이를 떨어뜨릴 때 */
```

박스 둥글게 만들기 - 원형 레이아웃을 넣고 싶을 때

처음부터 원으로 만드는 게 아니라 사각형 상태에서 둥글게 만들어줘야 함. 250 크기의 네모라면 125만큼 둥글어짐.

width:250px; height:250px;

_border-radius:125px; = border-radius:50%;

단 상자의 크기가 일정해야 함

포토샵에서 이미지 조절할 때에도 크기 조절

CSS에서 할 때에도 가로세로 중에 한 가지 값만 쓰면 나머지 값도 자동으로 조절됨 동시에 줘서는 안 됨
      <hr>
      <h2> 2023.02.26. HTML. CSS . REPEAT.</h2>
      <hr>
      <h2>2023.02.26. HTML.CSS.REPEAT.</h2>
