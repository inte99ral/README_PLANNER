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

  .graph-tail-t {
    stroke: "#000000"
  }
</style>
<table>
  <tr>
    <th class="week weekend"> Sun </th><th class="week"> Mon </th><th class="week"> Tue </th><th class="week"> Wed </th><th class="week"> Thu </th><th class="week"> Fri </th><th class="week weekend"> Sat </th>
  </tr>
  <tr>
    <td class="2023-10-1"><div class="day"><h2 class="date weekend">1</h2><label><input type="checkbox" checked>[12:00] 브런치 커피 & 음악 타임</label><label><input type="checkbox" checked>[15:00] 청소</label><label><input type="checkbox" checked>[16:00] 서피스 프로 7 윈도우 재설치</label><label><input type="checkbox" checked>[18:00] 저녁 : 양념게장</label><label><input type="checkbox" checked>[21:00] Java 17 로 버전 업</label><div class="↑ DONE"></div><label><input type="checkbox" c hecked> vanilla-tilt ts 포팅</label><label><input type="checkbox" c hecked> 알고리즘 풀이</label><div class="↑ TODO"></div><div class="graph" style="--size-w: 18em; --size-head: 0em; --size-tail: 1.8em; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-title">● 포트폴리오 사이트</p><p class="graph-progress">10 %</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-10-2"><div class="day"><h2 class="date weekend">2</h2><label><input type="checkbox" checked>[12:00] 점심 : 양념게장</label><label><input type="checkbox" checked>[13:00 ~] 게임 스프라이트 만지기</label><div class="↑ DONE"></div><label><input type="checkbox" c hecked> vanilla-tilt ts 포팅</label><div class="↑ TODO"></div><div class="graph" style="--size-w: 18em; --size-head: 21.6em; --size-tail: 0em; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-title"></p><p class="graph-progress">10 % - 보류</p><div class="graph-tail"></div></div><div class="graph" style="--size-w: 18em; --size-head: 0em; --size-tail: 0em; --color-bg: #FFD400; --color-txt: #000000;"><div class="graph-head"></div><p class="graph-title">● vanilla-tilt 포팅</p><p class="graph-progress">0 % - 보류</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-10-3"><div class="day"><h2 class="date weekend">3</h2><label><input type="checkbox" checked>[12:00] 점심 : 양념게장</label><label><input type="checkbox" checked>[16:00] 뮤즈 대쉬</label><label><input type="checkbox" checked>[20:00] 듀얼 악귀 지옥의 마탄환 쇼</label><div class="↑ DONE"></div><div class="↑ TODO"></div><img class="sticker" src="./assets/images/2023-10-03.jpg" style="position: absolute; bottom: 2.5rem; right: 0; height: 10rem"></div></td>
    <td class="2023-10-4">
      <div class="day">
        <h2 class="date">4</h2>
        <label><input type="checkbox" checked>[08:00] 모닝 커피 & 음악듣기</label>
        <label><input type="checkbox" checked>[13:00] 점심 : 신라면 feat.참치</label>
        <label><input type="checkbox" checked>[20:00] 듀얼 악귀 지옥의 마탄환 쇼</label>
        <label><input type="checkbox" checked>[22:00] 뮤즈 대쉬</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <img class="sticker" src="./assets/images/2023-10-04.png" style="position: absolute; bottom: 2.5rem; right: 0; height: 10rem">
      </div>
    </td>
    <td class="2023-10-5">
      <div class="day">
        <h2 class="date">5</h2>
        <label><input type="checkbox" checked>[07:30] 모닝 커피 & 음악듣기</label>
        <label><input type="checkbox" checked>[08:00] 플래너 그래프 수정</label>
        <label><input type="checkbox" checked>[13:00] 점심 : 감자칩 바베큐맛</label>
        <label><input type="checkbox" checked>[15:00] 파일 다시 다운</label>
        <label><input type="checkbox" checked>[17:00] 저녁 : 삼계탕</label>
        <label><input type="checkbox" checked>[19:00] 플레이리스트 정리</label>
        <div class="↑ DONE" style="flex-grow: 1;"></div>
        <div class="↑ TODO"></div>
      </div>
    </td>
    <td class="2023-10-6">
      <div class="day">
        <h2 class="date">6</h2>
        <label><input type="checkbox" checked>[07:30] 모닝 커피 & 음악듣기</label>
        <label><input type="checkbox" checked>[12:00] 점심 : 치킨</label>
        <label><input type="checkbox" checked>[17:00] 저녁 : 치킨 + 포도</label>
        <div class="↑ DONE" style="flex-grow: 1;"></div>
        <label><input type="checkbox" c hecked> vs code c++ 빌드 오류 해결</label>
        <label><input type="checkbox" c hecked> 알고리즘</label>
        <label><input type="checkbox" c hecked> 서피스 세팅</label>
        <div class="↑ TODO"></div>
      </div>
    </td>
  </tr>
</table>
