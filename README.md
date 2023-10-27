<h1>2023. 10</h1>

<style>
  @font-face {
  font-family: KyoboHandwriting;
  src: url(assets/fonts/KyoboHandwriting2020pdy.ttf);
  }

  * {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
    font-family: KyoboHandwriting;
    font-weight: bold;
    position: relative;
    /*variable*/
    --color-red: #FF8E99;
  }

  .week {
    width: 20em;
    min-width: 20em;
    max-width: 20em;
    text-align: center;
  }

  .weekend {
    color: var(--color-red);
  }

  .day {
    height: 30em;
    display: flex;
    flex-direction: column;
  }

  .date {
    text-align: center;
  }

  .DONE {
    display: flex;
    justify-items: center;
    gap: 0.5em;
  }

  .TODO {
    display: flex;
    justify-items: center;
    gap: 0.5em;
  }

  .↑ {
    flex-grow: 1;
  }

  .graph {
    position: relative;
    padding-left: 0.5em;
    padding-right: 2em;
    height: 1.6em;
    width: var(--size-w);

    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin-top: 0.2em;
    border-radius: 0.8em;
    background: var(--color-bg);
    color: var(--color-txt);
  }

  .graph-head {
    position: absolute;
    top: 0;
    right: 0;
    height: 1.6em;
    width: var(--size-head);
    border-radius: 0.8em 0.8em 0.8em 0;
    background: var(--color-bg);
  }

  .graph-tail {
    position: absolute;
    bottom: 0;
    right: 0;
    height: var(--size-tail);
    width: 1.6em;
    border-radius: 0 0 0.8em 0;
    background: var(--color-bg);
  }

  .graph-progress {
    width: 100%;
    text-align: center;
  }
</style>

<table>
  <tr>
    <th class="week weekend"> Sun </th><th class="week"> Mon </th><th class="week"> Tue </th><th class="week"> Wed </th><th class="week"> Thu </th><th class="week"> Fri </th><th class="week weekend"> Sat </th>
  </tr>
  <tr>
    <td class="2023-10-1"><div class="day"><h2 class="date weekend">1</h2><label><input type="checkbox" checked>[12:00] 브런치 커피 & 음악 타임</label><label><input type="checkbox" checked>[15:00] 청소</label><label><input type="checkbox" checked>[16:00] 서피스 프로 7 윈도우 재설치</label><label><input type="checkbox" checked>[18:00] 저녁 : 양념게장</label><label><input type="checkbox" checked>[21:00] Java 17 로 버전 업</label><div class="↑ DONE"></div><label><input type="checkbox" c hecked> vanilla-tilt ts 포팅</label><label><input type="checkbox" c hecked> 알고리즘 풀이</label><div class="↑ TODO"></div><div class="graph" style="--size-w: 18em; --size-head: 0em; --size-tail: 1.8em; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-title">● 포트폴리오 사이트</p><p class="graph-progress">10 %</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-10-2"><div class="day"><h2 class="date weekend">2</h2><label><input type="checkbox" checked>[12:00] 점심 : 양념게장</label><label><input type="checkbox" checked>[13:00 ~] 게임 스프라이트 만지기</label><div class="↑ DONE"></div><label><input type="checkbox" c hecked> vanilla-tilt ts 포팅</label><div class="↑ TODO"></div><div class="graph" style="--size-w: 18em; --size-head: 21.6em; --size-tail: 0em; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-title"></p><p class="graph-progress">10 % - 보류</p><div class="graph-tail"></div></div><div class="graph" style="--size-w: 18em; --size-head: 0em; --size-tail: 0em; --color-bg: #FFD400; --color-txt: #000000;"><div class="graph-head"></div><p class="graph-title">● vanilla-tilt 포팅</p><p class="graph-progress"></p><div class="graph-tail"></div></div></div></td>
    <td class="2023-10-3"><div class="day"><h2 class="date weekend">3</h2><label><input type="checkbox" checked>[12:00] 점심 : 양념게장</label><label><input type="checkbox" checked>[16:00] 뮤즈 대쉬</label><label><input type="checkbox" checked>[20:00] 듀얼 악귀 지옥의 마탄환 쇼</label><div class="↑ DONE"></div><div class="↑ TODO"></div><img class="sticker" src="./assets/images/2023-10-03.jpg" style="position: absolute; bottom: 2.5rem; right: 0; height: 10rem"></div></td>
    <td class="2023-10-4"><div class="day"><h2 class="date">4</h2><label><input type="checkbox" checked>[08:00] 모닝 커피 & 음악듣기</label><label><input type="checkbox" checked>[13:00] 점심 : 신라면 feat.참치</label><label><input type="checkbox" checked>[20:00] 듀얼 악귀 지옥의 마탄환 쇼</label><label><input type="checkbox" checked>[22:00] 뮤즈 대쉬</label><div class="↑ DONE"></div><div class="↑ TODO"></div><img class="sticker" src="./assets/images/2023-10-04.png" style="position: absolute; bottom: 2.5rem; right: 0; height: 10rem"></div></td>
    <td class="2023-10-5"><div class="day"><h2 class="date">5</h2><label><input type="checkbox" checked>[07:30] 모닝 커피 & 음악듣기</label><label><input type="checkbox" checked>[08:00] 플래너 그래프 수정</label><label><input type="checkbox" checked>[13:00] 점심 : 감자칩 바베큐맛</label><label><input type="checkbox" checked>[15:00] 파일 다시 다운</label><label><input type="checkbox" checked>[17:00] 저녁 : 삼계탕</label><label><input type="checkbox" checked>[19:00] 플레이리스트 정리</label><div class="↑ DONE" style="flex-grow: 1;"></div><div class="↑ TODO"></div></div></td>
    <td class="2023-10-6"><div class="day"><h2 class="date">6</h2><label><input type="checkbox" checked>[07:30] 모닝 커피 & 음악듣기</label><label><input type="checkbox" checked>[12:00] 점심 : 치킨</label><label><input type="checkbox" checked>[17:00] 저녁 : 치킨 + 포도</label><div class="↑ DONE" style="flex-grow: 1;"></div><div class="↑ TODO"></div></div></td>
    <td class="2023-10-7"><div class="day"><h2 class="date weekend">7</h2><label><input type="checkbox" checked>[12:30] 꿀잠</label><div class="↑ DONE" style="flex-grow: 1;"></div><div class="↑ TODO"></div></div></td>
  </tr>
  <tr>
    <td class="2023-10-8"><div class="day"><h2 class="date weekend">8</h2><label><input type="checkbox" checked>[12:30] 대청소</label><label><input type="checkbox" checked>[15:00] 창고 정리</label><label><input type="checkbox" checked>[20:00] 선풍기 청소</label><div class="↑ DONE" style="flex-grow: 1;"></div><div class="↑ TODO"></div></div></td>
    <td class="2023-10-9"><div class="day"><h2 class="date weekend">9</h2><div class="date weekend">~ 한글날 ~</div><label><input type="checkbox" checked>[8:30] 꿀잠</label><label><input type="checkbox" checked>[9:00] 창고 정리</label><label><input type="checkbox" checked>[10:00] 방 청소</label><label><input type="checkbox" checked>[12:00] 점심 : 죽</label><label><input type="checkbox" checked>[15:00] 세입자 전자레인지 설치 & 방 체크</label><label><input type="checkbox" checked>[16:00] 구두 & 운동화 A/S</label><label><input type="checkbox" checked>[17:30] 저녁 : 트레이더스 피자</label><div class="↑ DONE" style="flex-grow: 1;"></div><div class="↑ TODO"></div></div></td>
    <td class="2023-10-10"><div class="day"><h2 class="date">10</h2><label><input type="checkbox" checked>[07:40] 아침 : 커피 & 음악감상</label><div class="↑ DONE"></div><div class="↑ TODO"></div><div class="graph" style="--size-w: 18em; --size-head: 0em; --size-tail: 0em; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-title">● 포트폴리오 사이트</p><div class="graph-tail"></div></div><div class="graph" style="--size-w: 18em; --size-head: 0em; --size-tail: 0em; --color-bg: #FFD400; --color-txt: #000000;"><div class="graph-head"></div><p class="graph-title">● vanilla-tilt 포팅</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-10-11"><div class="day"><h2 class="date">11</h2><label><input type="checkbox" checked>[11:00] 낮잠 참기 대실패</label><label><input type="checkbox" checked>[13:30] 은행 업무</label><label><input type="checkbox" checked>[14:00] 점심 : 피자</label><label><input type="checkbox" checked>[18:30] 저녁 : 육계장</label><label><input type="checkbox" checked>[21:30] 꿀잠</label><div class="↑ DONE"></div><div class="↑ TODO"></div><div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-progress">10 %</p><div class="graph-tail"></div></div><div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #FFD400; --color-txt: #000000;"><div class="graph-head"></div><p class="graph-progress">10 %</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-10-12"><div class="day"><h2 class="date">12</h2><label class="DONE"><input type="checkbox" checked>[08:33] 모닝 커피와 음악</label><label class="DONE"><input type="checkbox" checked>[14:41] 서피스 세팅</label><label class="DONE"><input type="checkbox" checked>[18:50] 창고 1층 정리</label><label class="DONE"><input type="checkbox" c hecked>[20:30] vs code c++ 빌드 오류 해결</label><div class="↑ DONE"></div><div class="↑ TODO"></div><div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-progress">10 %</p><div class="graph-tail"></div></div><div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #FFD400; --color-txt: #000000;"><div class="graph-head"></div><p class="graph-progress">10 %</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-10-13"><div class="day"><h2 class="date">13</h2><label class="DONE"><input type="checkbox" checked>[08:33] 모닝 커피와 음악</label><label class="DONE"><input type="checkbox" checked>[10:30] 블로그 글 초본</label><label class="DONE"><input type="checkbox" checked>[12:30] 점심 : 비빔면</label><label class="DONE"><input type="checkbox" checked>[14:30] H.C.proj 로고 초안</label><div class="↑ DONE"></div><div class="↑ TODO"></div><div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-progress">11 %</p><div class="graph-tail"></div></div><div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #FFD400; --color-txt: #000000;"><div class="graph-head"></div><p class="graph-progress">15 %</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-10-14"><div class="day"><h2 class="date weekend">14</h2><label class="DONE"><input type="checkbox" checked>[10:30] 꿀잠</label><label class="DONE"><input type="checkbox" checked>[12:30] 점심 : 두부 김치</label><label class="DONE"><input type="checkbox" checked>[15:00] 주간 집 청소</label><label class="DONE"><input type="checkbox" checked>[17:00] 대형 폐기물 처분</label><label class="DONE"><input type="checkbox" checked>[19:20] 저녁 : 후라이드 ZIP 치킨</label><label class="DONE"><input type="checkbox" checked>[20:00] 페그오</label><label class="DONE"><input type="checkbox" checked>[21:00] 블로그 글 정리</label><div class="↑ DONE" /></div><label class="TODO"><input type="checkbox" c hecked>넥슨</label><div class="↑ TODO"></div><div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-progress">12 %</p><div class="graph-tail"></div></div><div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #FFD400; --color-txt: #000000;"><div class="graph-head"></div><p class="graph-progress">16 %</p><div class="graph-tail"></div></div></div></td>
  </tr>
  <tr>
    <td class="2023-10-15"><div class="day"><h2 class="date weekend">15</h2><label class="DONE"><input type="checkbox" checked>[08:30] 꿀잠</label><label class="DONE"><input type="checkbox" checked>[12:30] 점심 : 남은 치킨</label><label class="DONE"><input type="checkbox" checked>[16:00] 변기 청소</label><div class="↑ DONE"></div><label class="TODO"><input type="checkbox" c hecked>넥슨</label><div class="↑ TODO"></div><div class="graph" style="--size-w: 18em; --size-head: 18em; --size-tail: 0em; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-progress">12 %</p><div class="graph-tail"></div></div><div class="graph" style="--size-w: 18em; --size-head: 18em; --size-tail: 0em; --color-bg: #FFD400; --color-txt: #000000;"><div class="graph-head"></div><p class="graph-progress">16 %</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-10-16"><div class="day"><h2 class="date">16</h2><div class="↑ DONE"></div><div class="↑ TODO"></div><img class="sticker" src="./assets/images/2023-10-04.png" style="position: absolute; bottom: 2.5rem; right: 0; height: 10rem"></div></td>
    <td class="2023-10-17"><div class="day"><h2 class="date">17</h2><label class="DONE"><input type="checkbox" checked>[08:30] 모닝 커피</label><label class="DONE"><input type="checkbox" checked>[10:30] 인터폰 주문</label><label class="DONE"><input type="checkbox" checked>[12:30] 점심 : 푸라면</label><label class="DONE"><input type="checkbox" checked>[16:43] 블로그 글</label><label class="DONE"><input type="checkbox" checked>[17:50] 저녁 : 김치볶음밥</label><div class="↑ DONE"></div><div class="↑ TODO"></div></div></td>
    <td class="2023-10-18"><div class="day"><h2 class="date">18</h2><label class="DONE"><input type="checkbox" checked>[08:30] 모닝 커피</label><label class="DONE"><input type="checkbox" checked>[10:00] 인터폰 주문 수정</label><label class="DONE"><input type="checkbox" checked>[11:00] 보험비 처리</label><label class="DONE"><input type="checkbox" checked>[12:30] 점심 : 푸라면 참치볶음</label><div class="↑ DONE"></div><div class="↑ TODO"></div></div></td>
    <td class="2023-10-19"><div class="day"><h2 class="date">19</h2><label class="DONE"><input type="checkbox" checked>[08:00] 모닝 커피 & 음악 감상</label><label class="DONE"><input type="checkbox" checked>[10:00] 플래너 템플릿 변경</label><label class="DONE"><input type="checkbox" checked>[12:00] 점심 : 비빔면 & 참치 & 초콜릿</label><div class="↑ DONE"></div><div class="↑ TODO"></div></div></td>
    <td class="2023-10-20"><div class="day"><h2 class="date">20</h2><label class="DONE"><input type="checkbox" checked>[12:00] 점심 : 츄러스</label><label class="DONE"><input type="checkbox" checked>[14:00] 인터폰 설치</label><div class="↑ DONE"></div><div class="↑ TODO"></div></div></td>
    <td class="2023-10-21"><div class="day"><h2 class="date weekend">21</h2><label class="DONE"><input type="checkbox" checked>[12:00] 주말 꿀잠</label><label class="DONE"><input type="checkbox" checked>[13:00] 점심 : 초콜릿 무스 초코칩 컵케익</label><label class="DONE"><input type="checkbox" checked>[14:00] 블로그 정리</label><label class="DONE"><input type="checkbox" checked>[16:00] 페그오</label><label class="DONE"><input type="checkbox" checked>[18:00] 저녁 : 바삭한 김치전</label><label class="DONE"><input type="checkbox" checked>[21:00] 우분투 서버 공부</label><div class="↑ DONE"></div><div class="↑ TODO"></div></div></td>
  </tr>
  <tr>
    <td class="2023-10-22">
      <div class="day">
        <h2 class="date weekend">22</h2>
        <label class="DONE"><input type="checkbox" checked>[12:00] 주말 꿀잠</label>
        <label class="DONE"><input type="checkbox" checked>[13:00] 점심 : 과자와 우유</label>
        <label class="DONE"><input type="checkbox" checked>[14:00] 주말 청소 & 분리수거</label>
        <label class="DONE"><input type="checkbox" checked>[15:30] 티타임</label>
        <label class="DONE"><input type="checkbox" checked>[18:30] 저녁 : 카레</label>
        <label class="DONE"><input type="checkbox" checked>[20:00] 알고리즘 풀이</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
      </div>
    </td>
    <td class="2023-10-23">
      <div class="day">
        <h2 class="date">23</h2>
        <label class="DONE"><input type="checkbox" checked>[07:30] 모닝 커피</label>
        <label class="DONE"><input type="checkbox" checked>[12:00] 점심 : 짜파게티 & 소세지</label>
        <label class="DONE"><input type="checkbox" checked>[15:30] 티타임</label>
        <label class="DONE"><input type="checkbox" checked>[20:00] c++17 문법을 위해 minGW -> w64로 교체 준비중</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--size-w: 18em; --size-head: 0em; --size-tail: 0em; --color-bg: #9BD0B7; --color-txt: #000000;">
          <div class="graph-head"></div>
          <p class="graph-title">● minGW-w64</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="2023-10-24">
      <div class="day">
        <h2 class="date">24</h2>
        <label class="DONE"><input type="checkbox" checked>[07:30] 모닝 커피</label>
        <label class="DONE"><input type="checkbox" checked>[12:00] 점심 : 치킨</label>
        <label class="DONE"><input type="checkbox" checked>[18:00] 저녁 : 카레 남은 것</label>
        <label class="DONE"><input type="checkbox" checked>[20:00] 간식 : 커피 & 초콜릿</label>
        <label class="DONE"><input type="checkbox" checked>[22:00] c++ 공부</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #9BD0B7; --color-txt: #000000;">
          <div class="graph-head"></div>
          <p class="graph-progress">20 %</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="2023-10-25">
      <div class="day">
        <h2 class="date">25</h2>
        <label class="DONE"><input type="checkbox" checked>[07:30] 모닝 커피</label>
        <label class="DONE"><input type="checkbox" checked>[10:30] 손글씨연습</label>
        <label class="DONE"><input type="checkbox" checked>[12:30] 점심 : 짜장라면에 계란후라이</label>
        <label class="DONE"><input type="checkbox" checked>[14:00] gcc 에러 확인</label>
        <label class="DONE"><input type="checkbox" checked>[16:00] 저녁 : 등뼈묵은지찜</label>
        <label class="DONE"><input type="checkbox" checked>[21:00] 듀ㅡ얼</label>
        <div class="↑ DONE"></div>
        <label class="TODO"><input type="checkbox" c hecked>링피트</label>
        <label class="TODO"><input type="checkbox" c hecked>알고리즘</label>
        <div class="↑ TODO"></div>
        <div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #9BD0B7; --color-txt: #000000;">
          <div class="graph-head"></div>
          <p class="graph-progress">80 %</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="2023-10-26">
      <div class="day">
        <h2 class="date">26</h2>
        <label class="DONE"><input type="checkbox" checked>[07:30] 아침 : 시리얼</label>
        <label class="DONE"><input type="checkbox" checked>[07:30] 점심 : 요거트</label>
        <label class="DONE"><input type="checkbox" checked>[18:30] 저녁 : 등뼈묵은지찜</label>
        <label class="DONE"><input type="checkbox" checked>[20:00] 알고리즘 : BJ1000</label>
        <div class="↑ DONE"></div>
        <label class="TODO"><input type="checkbox" c hecked>링피트</label>
        <div class="↑ TODO"></div>
        <div class="graph" style="--size-w: 18em; --size-head: 24em; --size-tail: 0em; --color-bg: #9BD0B7; --color-txt: #000000;">
          <div class="graph-head"></div>
          <p class="graph-progress">100 %</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="2023-10-27">
      <div class="day">
        <h2 class="date">27</h2>
        <label class="DONE"><input type="checkbox" checked>[07:30] 아침 : 오예스</label>
        <label class="DONE"><input type="checkbox" checked>[10:00] 링피트</label>
        <label class="DONE"><input type="checkbox" checked>[12:30] 점심 : 안성탕면</label>
        <label class="DONE"><input type="checkbox" checked>[14:00] 머리깎기</label>
        <label class="DONE"><input type="checkbox" checked>[20:30] 저녁 : 치즈스파게티</label>
        <label class="DONE"><input type="checkbox" checked>[23:00] 마스크팩</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
      </div>
    </td>
  </tr>
</table>
