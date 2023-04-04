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
      <h2> 2023.02.25. HTML. CSS . REPEAT.</h2>
      <hr>
      <h2>2023.02.26. HTML.CSS.REPEAT.</h2>
<hr>
<h2>2023.02.27. HTML/CSS </h2>
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="keywords" content="">
    <meta name="description" content="">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>layout</title>
    <link href="./styles/reset.css" rel="stylesheet" type="text/css">
    <link href="./styles/design2.css" rel="stylesheet" type="text/css">
</head>
<body>
    <div class="wrap">
        <div class="a">A</div>
        <div class="b">B</div>
        <div class="c">c</div>
    </div>
    <div class="next"></div>
</body>
</html>
<hr>
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="keywords" content="">
    <meta name="description" content="">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>layout2</title>
    <!-- FAVICON -->
    <link href="./styles/reset.css" rel="stylesheet" type="text/css">
    <link href="./styles/design3.css" rel="stylesheet" type="text/css">
    <!-- 폰트어썸 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css" integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <header>
        <h1>logo</h1>
        <form>form</form>
        <div class="lnb">
            <a href="#">로그인</a>
            <a href="#">가입</a>
        </div>
    </header>
    <main>
        <dl class="path">
            <dt class="skip">현재페이지경로</dt>
            <dd><span class="awesome">웹접근성이란</span>웹접근성개요</dd>
            <dd class="blog">네이버 <span class="awesome">블로그</span> 내 블로그</dd>
        </dl>
    </main>
</body>
</html>
<hr>
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="keywords" content="">
    <meta name="description" content="">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>0227-3</title>
    <link href="./styles/reset.css" rel="stylesheet" type="text/css">
    <link href="./styles/design4.css" rel="stylesheet" type="text/css">
</head>
<body>
    <div class="wrap">
        <a href="#" class="a">A</a>
        <a href="#" class="b">B</a>
        <a href="#" class="c">C</a>
        <a href="#" class="d">D</a>
    </div>
</body>
</html>
<hr>
.path {
    width: 50vw; /* 퍼센트로 하면 가변형이 됨 */height: 100vh;
    background-color:lightgray;
}
.path dl {background-color: yellow;} /* 블록이므로 크기는 부모의 100%를 가진다, 여기서는 div 기준 100%, 높이는 무조건 내용 만큼만 인식함 */
.path dl dt {} /* 스킵 할 거면 숨겨도 됨 */
.path dl dd {background-color: pink;} /* 블록이므로 크기는 부모의 100%를 가진다, 여기서는 dl 기준 100%, 높이는 무조건 내용 만큼만 인식함 */
.path dl dd i {} /* 수식해주는 것이므로 클래스 이름을 따로 안 적어도 됨, 아니면 공통되는 .fa-solid로 변경해도 됨 */
.path dl dd span {
    background-color: aqua;
    display:inline-block;
    margin:5px 10px 30px 0;
/*     margin-left:20px;
    margin:0 0 0 20px; */
}
.path dl dd a {
    background-color:lime;
/*     width:120px; 크기를 쓰기보다는 패딩을 더 많이 씀*/
    padding:10px 30px 10px 0;
    display:inline-block;
}
.path dl dd .noto {font-family: 'Noto Sans KR', sans-serif;}
.path dl dd .nanum {font-family: 'Nanum Gothic', sans-serif;}
<hr>
.wrap {
    background-color: aquamarine;
    width:500px;
}
    /* 자식에 float 적용 시 생기는 부모 오류해결법 */
    /* 1. 높이강제부여 */
    /* height:100px; */
    /* 2. 자식 높이 재인식 */
    /* overflow:fidden; */
    /* 3. 가상자식생성 */
    /* 선택자 추가 */
.wrap::after {clear:both; display:block; content:'d';}
    /* 존재하지 않는 태그를 생성하는 명령 */
.wrap .a {
    border:5px solid red;
    float:left;}
.wrap .b {
    border:5px solid blue;
    float:right;}
.wrap .c {
    border:5px solid green;
    float: left;
    /* clear:both; *//* 이전 형제 float 위치 제거->새로운 행 선언 */
}
.wrap .a, .wrap .b, .wrap .c {width:100px; height:100px; background-color: yellow;}
.next {
    width: 500px; height:250px;
    background-color:gold;
}
<hr>
header {
    background-color: aqua;
    /* height:100px; */
    /* overflow:hidden; */
    }
header::after {clear:both; content:''; display:block;}
header h1 {
    background-color: gray;
    float: left;}
header form {
    background-color: greenyellow;
    float: left;
}
header .lnb {background-color: pink;
    float:right;}
header .lnb a {}
header h1, header form, header .lnb {width:100px; height: 100px;}
main {}
main .path {}
main .path dt {}
main .path dd {}
main .path dd span {}
main .path dd span::after {
    display:inline; content:'\f105';
}
main .path .blog span::after {
    display:inline; content:'\f30b';
}
<hr>
# 22일차

### CSS

.skip 안 보이게 처리하는 키워드

.skip {display:none;}

[블록과 인라인 요소의 특징](https://webty.tistory.com/62)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/af7def3c-2327-4dcc-bb44-58bf220a943d/Untitled.png)

첫 번째 화살표는 이전 형제가 인라인

두 번째 화살표는 이전 형제가 블록이라 아래로 내려감

사용자의 선택영역을 조금이라도 넓히기 위해 NAV의 패딩 공간을 넓힌다.

a는 HTML적인 의미로 인라인/블록의 의미를 가지고 있지만 CSS에서는 인라인으로 인식

viewport - 내가 보고 있는 화면을 인식, 전체 화면 아님 -VH(높이) vw(너비) - 100%와 그리 다르지는 않음

---

[float 기본과 활용](https://webty.tistory.com/63)

## float 위치 설정

- 같은 부모 안 형제 요소(인라인 또는 블록)에 작성하여 위치를 설정합니다.
- center값은 없으며 좌우로만 배치할 수 있습니다.
- right 값을 2번 이상 사용 시 순서가 역순이 됩니다. ex) 123 => 321

```css
float:left
float:right
float:none; 해제코드
```

그룹 선택자 만들기 - 콤마를 붙여서 옆에 새로 하나 작성하기

EX) .wrap {}

.wrap .a {}

.wrap .b {}

→ .wrap . a, .wrap .b {}

형제의 위치를 옮기고 싶으면 부모의 크기를 바꿔야 한다.

```css
.wrap {background-color: aquamarine}
.wrap .a {
    border:5px solid red;
    float:left;}
.wrap .b {
    border:5px solid blue;
    float:right;}
.wrap .a, .wrap .b {width:100px; height:100px; background-color: yellow;}
```

형제 좌우 상태에서 wrap의 크기를 조절

---

CSS 3에서는 Float(오래돼서 문제가 있는 요소)가 그대로 있음, 문제가 있음

float란 블록요소의 흐름을 변경하기 위해 사용하는 **레이아웃 배치 CSS 속성**

웹 페이지에서 좌/우로 배치되는 레이아웃을 제작 시 사용한다.

HTML4 이전 버전부터 사용하던 레이아웃 개념으로 호환성(익스플로러에서만 사용되었기 때문에 호환성이라는 말은 이제 쓰이지 않음)이 높다.

float의 **부유**개념 -적용시 배경색이 사라지는 이유

부모의 높이는 크기가 따로 안 들어가면 자식의 크기만큼 인식함

자식이 위로 올라가면서 float의 값이 0처리

다음 형제가 존재할 경우 float 값이 0이 되어버리면 다른 형제에게 올라간다.

자식하고 상관없이 크기를 유지할 수 있게 만드는 장면이 필수

float는 가출한다는 개념. 가출했으면 잡아오기.

다른 애를 데려오거나 float를 잡아오거나 하는 장면을 반드시 삽입해야 함

overflow - 넘치는 영역을 숨겨라 - 위치를 재인식하면서 안쪽에 있는 부분만 숨겨라.

위치를 인식해서 정말 나갔는지 인식

.wrap::after {clear:both; display:block; content:'C';}

이 때 C는 CSS에서 만든 가상의 자식이다. 그래서 상황에 따라서 쓰고 보통은 비워둠.

다른 형제에 float가 있는데 자기 혼자만 float가 안 적혀 있을 경우 형태값이 유지되지 않음

CSS는 html 태그와는 달리 속성 값에 따라 디자인에 필요한 새로운 순서를 재창조할 수 있음.

left는 두 번 이상 써도 역순이 안 되므로 두 번 이상 써도 됨

[폰트어썸](https://webty.tistory.com/153)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bc41b635-c7a7-4b96-92cf-990915cf3b3b/Untitled.png)

C와 D를 이렇게 배치시키려면

C를 clear:both;처리 후에 float:left, B를 float:rightfmf tkdydgksek
<hr>
<h2>2023.02.28.CSS.</h2>
<hr>
      <h2>2023.03.01.css.</h2>
<hr>
      <h2>2023.03.02.css.</h2>
      /* all_layout */
/* main .bg_path .top,
main .bg_w .itle,
main .bg_.contents,
main .bg_w_.contents, */
header, /* 헤더는 한 줄 */
main > div > *,
footer .ft_top,
footer address,
footer > p {
/*     border: 5px solid red; */
    width:1200px; margin:0 auto;
} /* 푸터는 세 줄이라 따로따로 감싸주기 위해 */
/* header 백 자가 쉽게 넘어가기 때문에 주석을 달아둬야 함-------------*/ /* 1200너비 */
main > div > * {
    text-align:center;
}
header {
    height:92px;
}/* 헤더에만 height가 들어간다고 생각 */
header h1 {
    float:left;
    padding-top:5px;
margin-right:30px;}
header h1 a {}
header h1 a img {
    width:60px;}
header nav {float:left;
    line-height:92px;}
header nav a {
    font-size:1.063rem;
    padding-left:30px;}
header nav .active {padding:0; color:#36b4e5;}
header .lnb {
    float:right;
    line-height:92px;
    margin-left:300px;}
header .lnb a {}
header .lnb a:nth-child(2):before {
    content:'|';
    display:inline;
    padding-left: 10px;
    margin-right: 10px;
}
/* main----------- */
main {}
/* 공통 배경 */
main .bg {background-color : #f1f1f1;
    padding: 50px 0;}
main .bg_w {margin:50px 0;}
/* 현재페이지경로 */
main .border {
/*     border-top:1px solid #aaa;
    border-bottom:1px solid #aaa; 상하에만 선 입히는 방법 */
    border:1px solid #aaa;
    border-left:none; border-right:none; /* 두께를 한 번만 고치면 되기에 유지보수 측면으로 이 방법이 많이 쓰임 */
}
main .bg_path {background-color:#f1f1f1;}
main .bg_path .top {padding:20px 0;}
main .bg_path .top dt {}
main .bg_path .top dd {text-align:right;}
main .bg_path .top dd span {}
main .bg_path .top dd em {}
/* 경영이념 제목 */
main .bg_w .title {}
main .bg_w .title h1 {font-size:2.5rem;
margin-bottom:15px;}
main .bg_w .title p {}
/* 경영이념 내용 */
main .bg .contents {}
main .bg .contents p {line-height:1.5;}
/* 경영이념 vision */
main .bg_w .contents {}
main .bg_w .contents h2 {font-size:1.375rem;
color:#36b4e5;
margin-bottom:30px;}
main .bg_w .contents p {
    font-size:1.938rem;
    line-height:1.5;
    letter-spacing:-0.01em;
}
main .bg_w .contents p:nth-child(2) {
    margin-bottom:100px;
}
/* 경영이념 GOAL, STRATEGY */
main .bg .contents h2 {
    font-size:1.25rem;
    margin-bottom : 30px;}
main .bg .contents ul {
    /* overflow:hidden; 바깥쪽으로 나간 영역을 숨겨라라는 뜻, 그림자를 입히면 이것 때문에 그림자가 빠져 나온 것으로 보임 */
    display:inline-block;/* float 오류 방식을 디스플레이로도 방지할 수 있음 float의 부모 높이 0 처리 오류해결방법으로 display:inline-block도 가능하다. */
}
main .bg .contents h2:nth-child(3){
    margin-top:100px;
}
main .bg .contents .goal_list {}
main .bg .contents .goal_list li {
    width: 250px; height: 250px;
    border-radius:50%;
    line-height:250px;
    /* float:left; */
    display:inline-block; /* 인라인 블록으로 정렬시키기, 위치는 인라인이라 정렬도 인라인으로 먹는 것 */
    box-shadow:0 0 10px gray;
    margin-left:-10px;
}
main .bg .contents .strategy_list {}
main .bg .contents .strategy_list li {
    width: 180px; height: 180px;
    border-radius:50%;
    padding:60px 20px 0;
    /* display:inline-block; -> 사용시 내용 개수에 차이가 생기기 때문에 인라인 블록을 쓰면 안 됨, 인라인은 내용의 개수만큼 인식하므로*/
    float:left;
    /* box-shadow:x y blur color; */
    box-shadow:0 0 10px gray;
}
main .bg .contents ul li {
    font-size:1.5rem;
    background-color:#fff;
}
main .bg .contents ul .first {
    background-color: #36b4e5;
    }
main .bg .contents ul .mid {width: 150px; height: 150px;}
main .bg .contents ul .last {
    background-color:#f3c300;
    }
main .bg .contents ul li h3 {font-size: 1.063rem;}
main .bg .contents ul li p {line-height:18px;}
/* footer----------- */
footer {padding:50px 0%;}
footer .ft_top {overflow:hidden;}
footer .ft_top .ft_left {float:left;}
footer .ft_top .ft_left a {font-weight:700;}
footer .ft_top .ft_right {float:right;}
footer .ft_top .ft_right a {
    border:1px solid #aaa;
    display:inline-block;
    padding:10px 20px;
    
}
footer address {line-height:1.5;}
footer address+p {padding-top:15px;}
      <spc>
main {
    width:850px;
    margin: 0 auto;
    border: 1px solid gainsboro;
}
main .top {
height:100px; width:850px;
border-bottom: 1px solid gainsboro;
}
main .top h1 {
    float:left;
    font-size:20px;
    line-height:100px;
    margin-left:25px;
    word-spacing:-0.02em;
}
main .top dl {}
main .top dl dd {float:right;
    line-height:100px;
    margin-right:25px;
}
main .top dl .fa-sharp {margin-right:15px;}
main .top dl dd span {}
main .top dl dd em {
    font-weight:700;
    word-spacing:-0.02em;}
main section {
    padding: 100px 25px;
    /* 배경이미지 속성 */
    background-image:url(../images/bg.png);
    background-size:50%; /* w h */
    background-repeat:no-repeat;/* 기본repeat */
    background-position:right top;/* x y 순서 -가 올라가는 것 +가 내려가는 것*/
}
main section h2 {
    font-size:17px;
    color:purple;
    font-weight:700;
    word-spacing:-0.02em;}
    main section h2 .fa-circle-dot {margin-right: 15px;}
main section p {line-height:25px; padding:50px 0px 0px 0px; word-spacing:-0.02em;}
main section p em {color:green;}
main section h2+p, main section p em {font-size:30px; line-height:40px;}
main section h2+p {margin-left:25px;}
     <wah>
 #t {
    width:1200px;
    border-top: 3px solid #333;
    margin:50px auto 0;}
#t thead {
    background-color: #fafafa;
    border-bottom:1px solid #e5e5e5;}
#t thead tr {}
#t thead tr th{line-height: 1.3;
    padding: 30px 0;}
#t thead tr th span {color:#999;}
#t thead tr:first-child th:last-child {border-bottom:1px dashed #999;}
#t thead tr:first-child th:first-child {
    background-image:url(../images/pay_table_02.png);
    background-repeat:no-repeat;
    background-position:center;
}
#t tbody {}
#t tbody tr {}
#t tbody tr th {}
#t tbody tr td {}
#t tbody tr th, #t tbody tr td {
    text-align: center; padding: 25px 0;
    border-bottom: 1px solid #e5e5e5;
}
#t tbody tr td em {}
#t tbody tr td em span {
    color:#ec018c;}
#t tbody tr td em, #t tbody tr td em span {font-weight: 700;}

/* table {border-top: 1px solid black;
}
tr {border-bottom: 1px dashed #e5e5e5;}
#t {width:1200px;
text-align:center;}
#t thead {}
#t thead tr{background-color: #fafafa;
    background-image:url(../images/pay_table_02.png);
    background-repeat:no-repeat;
    background-position:50px 40px;
    height:80px;}
#t thead tr th{line-height: 25px;}
#t thead tr th span {color:#999;}
#t tbody {}
#t tbody tr {height:60px;}
#t tbody tr th {}
#t tbody tr td {}
#t tbody tr td em {}
#t tbody tr td em span {
    color:#ec018c;}
#t tbody tr td em, #t tbody tr td em span {font-weight: 700;} */
       <table 1>
   /* 15=0.938rem, 13=0.813rem, 20=1.250rem */
#t2 {
    width:1200px;
    margin: 50px auto;
    border-top: 3px solid #333;
}
#t2 thead {}
#t2 thead tr {border-bottom:1px solid #e5e5e5;}
#t2 thead tr th {
    font-size:15px;
    padding: 30px 0;
    background-color:#f5f5f5;
    text-align: center;}
    #t2 thead tr th span {font-size: 0.813rem}
#t2 tbody {}
#t2 tbody tr {border-bottom:1px solid #e5e5e5;}
#t2 tbody tr, #t2 tbody tr th {padding:30px 0;}
#t2 tbody tr th {
    font-size:20px;
    font-weight:800;
    padding:60px 0;}
    #t2 tbody tr th:first-child {font-weight:700;}
    #t2 tbody tr th:nth-child(2) {text-align:left;}
#t2 tbody tr td {
    line-height: 1.5;
    text-align: center;}
#t2 tbody tr th span {
    background-color:#c286ff;
    color:#fff;
    border-radius: 8px;
    padding: 3px;
    display:inline-block ;}
#t2 tbody tr td span {
    background-color: #c286ff; border-radius: 25%;
    color:white;
    }
#t2 tbody tr td em {color:#ec048c; font-weight:700;}
/* /*     /* 15=0.938rem, 13=0.813rem, 20=1.250rem */
/* #t2 {
    width:1200px;
    margin: 0 50px auto;
    border-top: 3px solid #333;
}
#t2 thead {}
#t2 thead tr {border-bottom:1px solid #e5e5e5;}
#t2 thead tr th {
    font-size:15px;
    padding: 25px 0;
    text-align: center;}
#t2 tbody {}
#t2 tbody tr {border-bottom:1px solid #e5e5e5;}
#t2 tbody tr th {
    font-size:20px;
    font-weight:800;
    padding:60px 0;}
#t2 tbody tr td {
    line-height: 1.5;
    text-align: center;}
#t2 tbody tr td span {
    background-color: #c286ff; border-radius: 25%;
    color:white;
    }
#t2 tbody tr td em {}
#t2 tbody tr td:nth-child(2) {text-align:left;}
#t2 tbody tr td:nth-child(6) em {color:#ec048c;}
#t2 tbody tr td:nth-child(7) span {
    background-color:white;
    border: 1px solid black;
    border-radius: 0%;
    color:black;
    padding:5px;}
    #t2 tbody tr td:nth-child(8) span{
    border-radius: 0%; padding: 5px;
    } */
      <table 2 wrong>
        /* 2.5rem, 1.5rem, 1.125, 1rem, 0.875rem,0.75rem */
/* #555; #eee; #ff7f50; #1e61a8; */
/* 전체 */
/* all-layout */
/* header,main {width:1080px; margin:0 auto;}
header {background-color:lightyellow;}
main {background-color: lightgray; overflow:hidden;}
main aside {background-color: lightblue; width:200px; float:left;}
main .container {background-color:lightgreen width:848px; float:right;} */
/* header,main {
    width:1080px; height:100px;
    margin: 10px auto 0;
    background-color: #fff;} */
    /* 검색어 */
header,main {width:1080px; margin: 0 auto;}
header {padding:20px 0;}
header .firstfrm {
    border: 3px solid #1e61a8;
    background-color: #fff;
    border-radius: 5px;
    width:435px;
    margin:0 auto;
}
header .firstfrm fieldset {}
header .firstfrm fieldset .skip {}
header .firstfrm fieldset input {
    width:90%; float:left; border:0; padding-top:10px;
}
header .firstfrm fieldset button {
    background-color: #1e61a8;
    color: #fff; width:30px; height:30px;
    float:right;
}
header .firstfrm fieldset button::after {
    content:'\f002';
    display: block;
}
/* 바디 */
main {overflow:hidden;}
/* 왼쪽 */
main aside {width: 200px; float:left; margin-right:32px;}
main aside h2 {
    font-size:1.5rem; margin-bottom: 30px;
    font-weight:700;
    text-align: center;
    color:#1e61a8;}
main aside .menu {}
main aside .menu a {
    display:block; padding:20px 0 20px 10px;
    border-top: 1px solid #eee;
    font-weight: 700;
}
main aside .menu a:last-child {border-bottom:1px solid #eee;}
main aside .menu .active {
    background-color: #1e61a8;
    color:#fff;
}
/* 오른쪽 */
main .container {
    width:848px; float:left;}
main .container .title_path {
    overflow:hidden;
    background-color: #eee;
    border-bottom:1px solid #888;
    padding:20px 15px;}    
main .container .title_path h1 {
    float: left;
    font-weight: 700;}
main .container .title_path dl {float: right;}
main .container .title_path dl .skip {}
main .container .title_path dl dd {font-size: 0.875rem;}
main .container .title_path dl dd::before {content:'\f015'; display:inline-block; font-weight:600;}
main .container .title_path dl dd span {}
main .container .title_path dl dd,
main .container .title_path dl dd span {font-size:0.875rem;}
main .container .title_path dl dd span::before,
main .container .title_path dl dd span::after {content:'\f104'; display:inline-block; font-weight:600;}
/* member login */
main .container .contents {padding:25px;}
main .container .contents .login_box {background-image: url(../images/bg.png);
    background-repeat: no-repeat;
    background-position: 90% 35%;
    width:720px; margin: 30px auto 50px; padding: 30px 0 30px 30px;
    background-color: #eee; border: 1px solid #888;}
main .container .contents .login_box h2 {}
main .container .contents .login_box h2 span {color:#1e61a8;}
main .container .contents .login_box h2,main .container .contents .login_box h2 span {font-size: 2.5rem; letter-spacing:-0.03em;}
main .container .contents .login_box > p {color:#888; padding:20px 0;}
/* 로그인 창 */
main .container .contents .login_box .lastfrm {}
main .container .contents .login_box .lastfrm fieldset { margin: 15px;
    width:720px;}
main .container .contents .login_box .lastfrm fieldset legend {}
main .container .contents .login_box .lastfrm fieldset ul {float:left;}
main .container .contents .login_box .lastfrm fieldset ul li {}
main .container .contents .login_box .lastfrm fieldset ul li:first-child {margin-bottom:18px;}
main .container .contents .login_box .lastfrm fieldset ul li span {display: inline-block; width:70px;}
main .container .contents .login_box .lastfrm fieldset ul li input {width:285px;}/* 인풋은 인라인이지만 크기를 인식함 */
main .container .contents .login_box .lastfrm fieldset p {float:left; margin-left:10px;}
main .container .contents .login_box .lastfrm fieldset p button {
    width:75px; height:67px;
    background-color: #1e61a8; color:#fff;}
main .container .contents .login_box .join_search {margin:20px 0 0 70px;}
main .container .contents .login_box .join_search a {
    background-color: #555; color: #fff;
    display: inline-block; padding: 15px 10px;
}
main .container .contents .top_link {
    float:right;
    background-color: #eee; display:inline-block;
    width:50px; height:50px; border-radius:50%;
    text-align: center; line-height: 50px;
}
main .container .contents .top_link::before {
    content:'\f077'; display:inline; font-weight:600;
}
/* main-right 웹 콘텐츠 명언 */
main .container .contents .button_text {
    clear:both; background-color:#eee;
    border:1px solid #888;
    padding:25px 0 25px 100px;
}
main .container .contents .button_text p {line-height:1.8;}
main .container .contents .button_text p em {color:#ff7f50;}
main .container .contents .button_text p,
main .container .contents .button_text p em {font-size:0.875rem;}
/* 먼저 온 텍스트보다 나중에 온 텍스트에게 값을 주는 게 더 낫다 */

/* 2.5rem, 1.5rem, 1.125, 1rem, 0.875rem,0.75rem */
/* #555; #eee; #ff7f50; #1e61a8; */
/* header {}
header .fristform {}
header .firstform fieldset {}
header .firstform fieldset legend {}
header .firstform fieldset legend input {}
header .firstform fieldset legend button {}
header .firstform fieldset legend button img {}
main {}
main aside {}
main aside h2 {}
main aside .menu {}
main aside .menu a {}
main .container {}
main .container .title_path {}
main .container .title_path h1 {}
main .container .title_path dl {}
main .container .title_path dl dt {}
main .container .title_path dl dd {}
main .container .title_path dl dd img {}
main .container .title_path dl dd span {}
main .container .contents {}
main .container .contents .login_box {}
main .container .contents .login_box h2 {}
main .container .contents .login_box h2 span {}
main .container .contents .login_box p {}
main .container .contents .login_box form {}
main .container .contents .login_box form fieldset {}
main .container .contents .login_box form fieldset legend {}
main .container .contents .login_box form fieldset ul {}
main .container .contents .login_box form fieldset ul li {}
main .container .contents .login_box form fieldset ul li span {}
main .container .contents .login_box form fieldset ul li input {}
main .container .contents .login_box form fieldset p {}
main .container .contents .login_box form fieldset p button {}
main .container .contents .login_box .join_search {}
main .container .contents .login_box .join_search a {}
main .container .contents .login_box img {}
main .container .contents a {}
main .container .contents .button_text {}
main .container .contents .button_text p {}
main .container .contents .button_text p em {} */


/* 
header,main {
    width:1080px; height:100px;
    margin: 10px auto 0;}
    /* 검색어 */
/* header {
    background-color: yellow;
}
header .fristform {}
header .firstform fieldset {width:435px;
border: 3px solid #1e61a8;
border-radius: 3px;}
header .firstform fieldset .skip {}
header .firstform fieldset .skip input {width:435px;}
header .firstform fieldset .skip button {}
header .firstform fieldset .skip button .fa-magnifying-glass {} */
/* 바디 */
/* main {} */
/* 왼쪽 */
/* main aside {width: 200px; float:left;}
main aside h2 {
    font-size:40px; padding-bottom: 20px;
    border-bottom:1px solid #333;
    text-align: center;
    color:#1e61a8;}
main aside .menu {}
main aside .menu a {display:block; line-height: 50px;}
main aside .menu a:nth-child(2) {background-color: #1e61a8;
color:white;} */
/* 오른쪽 */
/* main .container {width:848px; float:right; background-color: greenyellow;
    background-image: url(../images/bg.png);
    background-repeat: no-repeat;
    background-position: top right;
}
main .container .title_path {padding: 15px;}    
main .container .title_path h1 {
    float: left;
    font-weight: 800;
    display: block;}
main .container .title_path dl {}
main .container .title_path dl .skip {}
main .container .title_path dl dd {font-size: 0.875rem;
    float: right;}
main .container .title_path dl dd i {margin:5px;}
main .container .contents {}
main .container .contents .login_box {background-color: #555;} */
/* member login */
/* main .container .contents .login_box h2 {}
main .container .contents .login_box h2 span {color:#1e61a8;}
main .container .contents .login_box h2,main .container .contents .login_box h2 span {font-size: 2.5rem; display: inline-block;}
main .container .contents .login_box p {} */
/* 로그인 창 */
/* main .container .contents .login_box form {}
main .container .contents .login_box form fieldset { margin: 15px;
    width:720px;} */
/* main .container .contents .login_box form fieldset legend {}
main .container .contents .login_box form fieldset ul {display: inline-block;}
main .container .contents .login_box form fieldset ul li {}
main .container .contents .login_box form fieldset ul li span {}
main .container .contents .login_box form fieldset ul li input {}
main .container .contents .login_box form fieldset p {}
main .container .contents .login_box form fieldset p button {
    width:75px; height:67px;
    background-color: #1e61a8; color:white;}
main .container .contents .login_box .join_search {}
main .container .contents .login_box .join_search a {
    background-color: black;
    color:white}
main .container .contents .login_box img {float:right;}
main .container .contents a {width: 12px; height: 12px; float:right;
background-color: #eee; border-radius: 50%;}
main .container .contents .button_text {}
main .container .contents .button_text p {}
main .container .contents .button_text p em {}  */
<br>
        <h2>2023.03.03.CSS.</h2>
<br>
        <h2>2023.03.04.css.</h2>
        .notice {
    width:495px; background-color:aqua;
    border:1px solid #ccc; border-radius:10px;
    padding: 25px 20px 40px 25px;
    position: relative;
}
.notice h2 {
    font-size: 1.2rem;
    font-weight: 700;;
    letter-spacing: -0.02em;
    margin-bottom: 30px;
}
.notice .more {
    position:absolute; right: 20px; top:25px;
}
.notice ul {
    background-color: yellow;
    margin-left:100px;/* textalign은 공간을 정렬하는 것뿐이라 쓰는 건 안 됨 */
}
.notice ul li {padding:7px 0; position:relative;}
.notice ul li::after {clear:both; content:''; display:inline-block;}
.notice ul li::before {
    content:''; display:inline-block;
    width:4px; height:4px;background-color:gray;
    position:absolute;
    left:-5px; top:13px;
}
.notice ul li a {
    float:left;
    background-color: lime;
    width:60%; /* 부모를 기준으로 50% */
    white-space:nowrap;/* 한 줄 처리해라 (개행x) */
    overflow:hidden; /*정해진 크기 안에서만 보이기*/
    text-overflow:ellipsis; /*외부처리를 말줄임... */
}
.notice ul li span {float:right;}
footer {padding: 30px;} 
footer a {margin-right:10px;}
footer a:nth-child(3) {color:#1f8ce6;}
footer a::after {
    /* content:'|'; display:inline; padding-left:10px; */
    /* 위 방법 단점:글자크기보다 작거나 크게 할 수 없다. (디자인 다양성 부족) */
    width:1px; height:15px; background-color: red; content:''; display:inline-block;
    position:relative; right:-7px; top:2px;
}
footer a:last-child::after {display:none;}
/* footer a:last-child::after {content:'';} */
        
   text-overflow:ellipsis;
    white-space:nowrap;
    overflow:hidden;
        
        글제목이 정해진 레이아웃보다 커져서 넘칠 때 - 말줄임으로 처리하기 - 너비를 정해주기 - 정해진 너비를 넘치면 줄이라고 코드로 지시
<hr>
        <h2>2023.03.05.CSS.REPEAT</h2>
        <hr>
        <h2>2023.03.06.CSS.REPEAT</h2>
        <p>포지셔닝, FLEX, STICKY</P>
<hr>
         <h2>2023.03.07.CSS.REPEAT</h2>
        반응형웹, flex, grid / CSS에서 가장 어려운 것

카카오엔터프레이즈 개발

헤더

width:100% - 블록의 디폴트 값이라 안 적어도 될 것 같음

height: 스크롤 내려도 고정되어 있어서 필요할 것 같음 px 단위로

display: flx 써야 할 것 같음

영역 구분용으로 배경 색깔 깔기, 배경 색을 줘서 색깔 파악하는 게 중요

flex-flow:row nowrap; 적용하기 nowrap은 줄바꿈 안 하는 것

justify-content:space-around; 를 사용하면 여백이 많이 남음

space-between;으로 끝으로 보낸 다음에 padding 0 25px; 처리

한 줄이므로 align-items: center;로 중앙으로 옮기기

padding-top을 사용하면 정확하지 않음

로고가 너무 크므로 조절, 이미지 자체에 퍼센트를 줘서 따라가게 하고 실제 크기는 부모에게 준다.

img에 width:100%, 이미지를 가변형으로 만들기

실제 크기는 부모인 a에게 줘야 하는데 줘도 변화하지 않음. a가 CSS에서 인라인이기 때문.

그리고 a의 부모인 h1에게 주는 게 나음, 실제 크기는 h1이 작아지지만 img가 가변형이기 때문에 자동으로 따라감

앞으로 img는 가변형으로 만들고 부모님한테 원하는 크기를 써서 맞춰주기

메뉴와 메뉴 사이에 공백을 주기 위해 margin-left:25px;를 준다.

하지만 맨 왼쪽에 불편한 공백이 남음

맨 처음 a에게 마진 없애주기 기존 선택자에 새로 추가해서 margin-left:0;

a글자 색을 #eee; lnb에 #fff;

노토 산스 글꼴을 리셋에 메인으로 연결

폰트 어썸에서 아이콘 가져와서 배치하기

리셋에 "Font Awesome 5 Free","Font Awesome 5 Brands” 기재되어 있나 확인하기

폰트 웨이트 600을 기재해서 굵기 잡아주고 color #17a2b8 쓰기, 폰트 어썸은 폰트로 인식하기 때문에

글자와 이미지가 붙어 있으므로 margin이나 padding으로 배치하기

글자에 커서 가져다대면 색깔 바꾸는 법은 자바가 아니라 CSS라도 가능

.lnb에 #fff로 폰트색 만들고

.lnb:hover {} 생성 후 #ff0 색깔 만들기

header의 배경색 주기

반투명한 배경색 색깔 - background:; - 이미지나 그런 것 다 통합으로 쓰겠다는 속성

background:rgba(0,0,0,0.5);

헤더 고정하게 position:fixed;와 좌표 배치

width:100%;을 헤더에 넣어줘야함

fixed를 사용하면 개층 순서를 지정 안 해둬서 가끔 a를 누를 수 없는 버그가 생김.

z-index:9999;를 추가해서 순위 높이기, 부유하고 있는 속성에는 항상 z-index를 사용하기 픽시드 앱솔루트 스티키 같은 것.

---

동영상 너비를 맞추기 위해 width:100%; 추가

동영상의 높이를 맞추기 위해 .visual에 높이값을 추가하고(700px;) visual 밖으로 나간 동영상을 자르기 위해서 overflow:hidden으로 가려주기 - 이렇게 비디오를 삽입하게끔 되어 있음.

이 때 ai 이미지가 안 보이게 됨. ai 이미지는 영상 끝난 다음 위치에 있음. 영상과 이미지가 형제이기 때문에.

.ai에 position:;absolute 추가, 좌표는 left:0; top:0; 당장 위치를 모르므로 추가해보기

현재 body를 부모로 인식한다.

하지만 visual의 가운데에 이미지를 두고 싶으므로 position: relative를 비주얼에 넣어서 기준을 만들기

px의 위치는 보고 있는 비주얼에 따라 애매하게 달라지므로 %를 선택하기

대상의 기준점은 항상 왼쪽 상단에 위치해 있음.

왼쪽 50%, 탑 50%을 사용하면 정중앙이 아니라 정중앙을 기점으로 이미지가 생성되기 때문에 우측 하단으로 옮겨짐.

좌측의 절반을 옮기고 위로 절반 옮기기 위해서는 transform:translate(-50%,-50%); 채택 첫 번째가 X축, 두 번째가 Y축

대상을 가운데로 보낼 때 정해진 옵션

```css
left: 50%; top: 50%;
    transform:translate(-50%,-50%);
```

이미지는 아무것도 안 해도 됨.

이미지의 크기를 변동하고 싶으면 이미지는 width:100%;를 주고 .ai에 원하는 너비값을 입히기

메인에 f8f9fa 배경값 적기

.board의 너비값은 1140px; margin:0 auto;로 블록을 가운데로

바깥쪽 너비는 큰 픽셀로 진행할 거지만 그 안은 %로 진행할 것

A마다 2%의 간격

a의 width를 32%로 설정하면 2%의 여백이 자동으로 남겨지므로 마진 같은 걸 쓸 필요 없음.

메인의 모든 자식들에게 마진 바텀으로 떨구기

반응형 웹을 배우지 않은 상황이라 화면을 떨어뜨려서 볼 것

여러 줄 할 때 말줄임표 적는 법

```css
/* 여러줄 말줄임 처리 */
    white-space:wrap;
    overflow:hidden; text-overflow:ellipsis;
    /* + 추가할 것 */
    -webkit-line-clamp: 5;/* 동작 안 할 경우 붙이는 접두사, 몇 개를 추가할 거냐 */
    -webkit-box-orient: vertical;/* 수직으로 간다, 호리젠탈도 있음 */
```

이미지가 크다고 이미지 크기를 조정하는 게 아니라 부모 크기를 조정하는 것이다.

일전에 main > * 를 적용했는데 보드와 갤러리 사이에 공백이 안 떨어짐. margin 0 auto; 때문. 50 auto로 바꾸면 됨.

---

개발자 도구 보기

f 12 눌러서 elements만 보면 됨

중복된 값이 있으면 나중에 선택된 값이 우선순위가 되고 그 이전 것은 취소됨

틀린 부분이 있으면 노란색 경고 표시가 뜸

틀린 부분을 도구에 찾을 수 없으면 선택자를 잘못 썼다는 뜻

취소선은 순위에서 밀렸다는 뜻
<br>
         <h2>2023.03.08 CSS. flex.seoul</h2>
         [스프라이트 이미지(sprite image) 이해와 적용](https://webty.tistory.com/183)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4c98aff2-ca29-4769-8e64-6fa9a434c31e/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0815b439-6083-402c-88eb-83cdb6452757/Untitled.png)

[스프라이트 만들기](https://www.toptal.com/developers/css/sprite-generator)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8177d04d-7243-415c-81ba-af0e4a1a6bcb/Untitled.png)

텍스트 안 보이게 하기 - 화면 밖으로 빼버리기 (CSS)

이미지를 1번에 클릭하고 드래그하기

text-indent:-9999px; 화면 밖으로 내어쓰기

```html
/* background 개별속성 */
            /* background-color:aqua;
            background-image: url(./images/icon_controls/css_sprites.png);
            background-repeat: no-repeat;
            background-position:0 -3px; */
            /* background 통합속성 */
            /* background:color image repeat position */
```

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fe2ff9f9-b20c-4531-b820-c7d5a15d4bc3/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3f0414d3-9400-44c0-a522-801c0ceca7ec/Untitled.png)

값이 틀리지 않았음에도 아이콘이 사라졌을 때

백그라운드 속성이 겹쳐서. 색깔, 이미지, 반복을 적지 않았기 때문.

관리자 도구 위쪽에 올라온 게 높은 속성

값을 기준으로 보는 게 아니라 속성을 우선으로 본다.

background-position이라고 개별값을 넣어야 중첩되지 않음.

---

link 치고 탭 누르면 자동으로 링크 태그 완성됨 - 앱앱기능

h1 같은 태그도 탭을 누르면 됨

id를 붙일 때에도

h1#title 치고 탭 누르면 자동으로 id 완성됨 클래스도 마찬가지

자식 넣으려고 하면 꺽쇠를 넣는다. h1>a를 하고 탭 누르면 됨

형제는 태그+태그

자식 다섯을 만들고 싶으면 *5

조합해서 자식을 정하고 그 자식의 개수를 5개로 만들고 싶을 때 h1>p*5

header>h1+nav+div.lnb

### 

### 포지션 쓸 때 a 블록으로 만드는 거 반드시 주의할 것. 꼭 만들어야 함. display:block;이나 인라인 블록으로 꼭 만들어야 함.

포지셔닝 할 때 피그마로 만들고 위치 확인하면서 디테일 하나하나 체크하면서 하기
         <hr>
         <h2>2023.03.09.CSS.flex.trasnform.transition</h2>
  <hr>
         <h2>2023.3/10.CSS.flex.tranfrorm.transtition, clonecoding 6 footer, exam</h2>
<hr>
         <h2>2023.03.11.css.flex.transform. repeat</h2>
         <hr>
         <h2>2023.03.12.css.flex.transform.repeat </h2>
<hr>
<h2>2023.03.13.css.git.</h2>
<hr>
         <h2>2023.03.14.css.git.naver.</h2>
<hr>
<h2>2023.03.16.css.git.figma.scss.</h2>
<hr>
         <h2>2023.03.17.css.landing.page.반응형 웹. 미디어 쿼리.</h2>
         <hr>
         <h2>2023.03.18.GTQ 자격증 연습</h2>
<hr>
         <h2>2023.03.19.sunday. nintendo main page</h2>
<hr>
<h2>2023.03.20.자바스크립트 처음 배우는 </h2>
<hr>
         <h2>2023.03.24.friday.GTQ.JAVA.</h2>
         <hr>
         <h2>2023.03.25.gtq test</h2>
<hr>
         <h2>2023.03.26. rest.</h2>
<hr>
<h2>2023.03.27.start.</h2>
<hr>
<h2>2023.03.28.CSS. 반응형웹 2차 </h2>
<hr>
         <h2>2023. 03. 29. CSS 반응형웹 3차, 포트폴리오 예제 완료, 아이나라 클론코딩</h2>
<hr>
<h2>2023.03.30.CSS.3D</h2>
<hr>
<h2>2023.03.31.CSS.3D2회차,SAPPUN</h2>
<hr>
         <h2>2023.04.01.웹디자인기능사 필기</h2>
         <hr>
         <h2><b>2023.04.02.sunday</b></h2>
<hr>
         <h2>2023.04.03.java, css, sappun, mouseover, mouseout </h2>
<hr>
         <h2>2023.04.04.java, css, java, sappun, 매체객체 </h2>
