<h1>2023. 11</h1>

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

  .xxxx-xx-x {
    background-color: #D5E1DF;
  }

  .week {
    width: 18em;
    min-width: 18em;
    max-width: 18em;
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

    z-index: var(--index);
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

  .graph--head {
    position: absolute;
    top: 0;
    right: 0;
    height: 1.6em;
    width: var(--size-head);
    border-radius: 0 0.8em 0.8em 0.8em;
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

  .graph--tail {
    position: absolute;
    top: 0;
    right: 0;
    height: var(--size-tail);
    width: 1.6em;
    border-radius: 0 0.8em 0 0;
    background: var(--color-bg);
  }

  .graph-progress {
    width: 100%;
    text-align: center;
  }
</style>

<table>
  <tr><th class="week weekend"> Sun </th><th class="week"> Mon </th><th class="week"> Tue </th><th class="week"> Wed </th><th class="week"> Thu </th><th class="week"> Fri </th><th class="week weekend"> Sat </th></tr>
  <tr>
    <td class="xxxx-xx-x" colspan="3" style="">
    <td class="2023-11-01"><div class="day"><h2 class="date">01</h2><label class="DONE"><input type="checkbox" checked>[07:40] 아침 : 커피 & 음악감상</label><label class="DONE"><input type="checkbox" checked>[15:08] 바닐라 틸트 적용</label><div class="↑ DONE"></div><div class="↑ TODO"></div><div class="graph" style="--index: 10; --size-w: 18em; --size-head: 0em; --size-tail: 2.5rem; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-title">● 포트폴리오 프론트 페이지</p><div class="graph--tail"></div></div><div class="graph" style="--index: 0; --size-w: 16em; --size-head: 0em; --size-tail: 0em; --color-bg: #FFD400; --color-txt: #000000;"><div class="graph--head"></div><p class="graph-title">● vanilla-tilt 포팅</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-11-02"><div class="day"><h2 class="date">02</h2><label class="DONE"><input type="checkbox" checked>[07:40] 아침 : 커피 & 음악감상</label><div class="↑ DONE"></div><label class="TODO"><input type="checkbox" c hecked>알고리즘 풀이</label><div class="↑ TODO"></div><div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph--head"></div><p class="graph-progress">20 %</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-11-03"><div class="day"><h2 class="date">03</h2><label class="DONE"><input type="checkbox" checked>[07:40] 아침 : 커피 & 음악감상</label><label class="TODO"><input type="checkbox" checked>[10:00] 알고리즘 : BJ 1244</label><label class="TODO"><input type="checkbox" checked>[12:00] 점심 : 짜장라면</label><label class="TODO"><input type="checkbox" checked>[18:00] 저녁 : 떡국</label><div class="↑ DONE"></div><div class="↑ TODO"></div><div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-progress">21%</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-11-04"><div class="day"><h2 class="date weekend">04</h2><label class="DONE"><input type="checkbox" checked>[07:40] 아침 : 커피 & 음악감상</label><label class="TODO"><input type="checkbox" checked>[10:00] 추도예배</label><label class="TODO"><input type="checkbox" checked>[12:00] 할아버지 백세연</label><label class="TODO"><input type="checkbox" checked>[12:30] 점심 : 계룡스파텔</label><label class="TODO"><input type="checkbox" checked>[15:00] 대청소</label><label class="TODO"><input type="checkbox" checked>[17:00] 가구 분해 청소</label><label class="TODO"><input type="checkbox" checked>[18:00] 저녁 : 굴비</label><div class="↑ DONE"></div><div class="↑ TODO"></div><div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-progress">22 %</p><div class="graph-tail"></div></div></div></td>
  </tr>
    <td class="2023-11-05"><div class="day"><h2 class="date weekend">05</h2><label class="DONE"><input type="checkbox" checked>[10:00] 아침 시리얼</label><label class="DONE"><input type="checkbox" checked>[12:30] 점심 : 안성탕면</label><label class="DONE"><input type="checkbox" checked>[15:00] 메일함 정리</label><div class="↑ DONE"></div><div class="↑ TODO"></div><div class="graph" style="--index: 10; --size-w: 18em; --size-head: 18em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph--head"></div><p class="graph-progress">23 %</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-11-06"><div class="day"><h2 class="date">06</h2><div class="↑ DONE"></div><div class="↑ TODO"></div><div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;"><div class="graph-head"></div><p class="graph-progress">24 %</p><div class="graph-tail"></div></div></div></td>
    <td class="2023-11-07">
      <div class="day">
        <h2 class="date">07</h2>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;">
          <div class="graph--head"></div>
          <p class="graph-progress">25 %</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="2023-11-08">
      <div class="day">
        <h2 class="date">08</h2>
        <label class="DONE"><input type="checkbox" checked>[10:00] 아침 시리얼</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;">
          <div class="graph--head"></div>
          <p class="graph-progress">26 %</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="2023-11-09">
      <div class="day">
        <h2 class="date">09</h2>
        <label class="DONE"><input type="checkbox" checked>[12:00] 점심 : 진라면</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;">
          <div class="graph--head"></div>
          <p class="graph-progress">27 %</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="2023-11-10">
      <div class="day">
        <h2 class="date">10</h2>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;">
          <div class="graph--head"></div>
          <p class="graph-progress">28 %</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="2023-11-11">
      <div class="day">
        <h2 class="date weekend">11</h2>
        <label class="DONE"><input type="checkbox" checked>[14:00] 블루 자이언트 영화 관람</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 1.6rem; --color-bg: #A3B6C9; --color-txt: #FFFFFF;">
          <div class="graph--head"></div>
          <p class="graph-progress">29 %</p>
          <div class="graph--tail"></div>
        </div>
      </div>
    </td>
  </tr>
  <tr>
    <td class="2023-11-11">
      <div class="day">
        <h2 class="date weekend">11</h2>
        <label class="DONE"><input type="checkbox" checked>[14:00] 블루 자이언트 영화 관람</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--index: 10; --size-w: 18em; --size-head: 18em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;">
          <div class="graph--head"></div>
          <p class="graph-progress">30 %</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="2023-11-12">
      <div class="day">
        <h2 class="date">12</h2>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;">
          <div class="graph-head"></div>
          <p class="graph-progress">31 %</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="2023-11-13">
      <div class="day">
        <h2 class="date">13</h2>
        <label class="DONE"><input type="checkbox" checked>[14:00] 블루 자이언트 영화 관람</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--index: 10; --size-w: 18em; --size-head: 21em; --size-tail: 0; --color-bg: #A3B6C9; --color-txt: #FFFFFF;">
          <div class="graph-head"></div>
          <p class="graph-progress">32 %</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
  </tr>
</table>
