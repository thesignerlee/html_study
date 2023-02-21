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
