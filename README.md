<h1>2024. 2</h1>

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
    background-color: #000000;
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
    <td class="xxxx-xx-x" colspan="4">
    <td class="2024-02-01"><div class="day"><h2 class="date">01</h2></td>
    <td class="2024-02-02"><div class="day"><h2 class="date">02</h2></td>
    <td class="2024-02-03"><div class="day"><h2 class="date weekend">03</h2></td>
  </tr>
  <tr>
    <td class="2024-02-04"><div class="day"><h2 class="date weekend">04</h2></td>
    <td class="2024-02-05"><div class="day"><h2 class="date">05</h2></td>
    <td class="2024-02-06"><div class="day"><h2 class="date">06</h2>
      <label class="DONE"><input type="checkbox" checked>[17:20] 유품 공구 정리</label>
      <div class="↑ DONE"></div>
      <label class="TODO"><input type="checkbox" c hecked>블로그 : C++</label>
      <label class="TODO"><input type="checkbox" c hecked>알고리즘</label>
      <div class="↑ TODO"></div>
    </td>
    <td class="2024-02-07"><div class="day"><h2 class="date">07</h2>
      <label class="DONE"><input type="checkbox" checked>10:00 | 밥솥 AS</label>
      <label class="DONE"><input type="checkbox" checked>12:30 | 스타벅스 커피 타임</label>
      <label class="DONE"><input type="checkbox" checked>13:30 | 점심 : 치킨</label>
      <label class="DONE"><input type="checkbox" checked>20:00 | 유희왕 마스터듀얼 25주년</label>
      <div class="↑ DONE"></div>
      <label class="TODO"><input type="checkbox" c hecked>블로그 : C++</label>
      <label class="TODO"><input type="checkbox" c hecked>알고리즘</label>
      <div class="↑ TODO"></div>
    </td>
    <td class="2024-02-08"><div class="day"><h2 class="date">08</h2></td>
    <td class="2024-02-09"><div class="day"><h2 class="date">09</h2><div class="date weekend">~ 설 연휴 ~</div></td>
    <td class="2024-02-10"><div class="day"><h2 class="date weekend">10</h2>
      <div class="date weekend">~ 설 연휴 ~</div>
      <label class="DONE"><input type="checkbox" checked>18:00 | 저녁 : 설날 가족 회식</label>
      <div class="↑ DONE"></div>
      <label class="TODO"><input type="checkbox" c hecked>블로그 : C++</label>
      <label class="TODO"><input type="checkbox" c hecked>알고리즘</label>
      <div class="↑ TODO"></div>
    </td>
  </tr>
</table>
