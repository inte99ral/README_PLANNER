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

  .xxxx-xx-xx {
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
    <td class="xxxx-xx-xx" colspan="5">
    <td class="2024-03-01"><div class="day">
      <h2 class="date weekend">1</h2>
      <div class="date weekend">~ 삼일절 ~</div>
      <label class="TODO"><input type="checkbox" checked>07:20 | 건국전쟁 영화관람</label>
      <label class="TODO"><input type="checkbox" checked>12:00 | 점심 : 두부김치</label>
      <label class="TODO"><input type="checkbox" checked>13:00 | 눈마사지</label>
      <label class="TODO"><input type="checkbox" checked>14:00 | 음악 감상</label>
      <label class="TODO"><input type="checkbox" checked>18:30 | 저녁 : 열라면</label>
      <label class="TODO"><input type="checkbox" checked>20:00 | 서류 작업</label>
      <div class="↑ DONE"></div>
      <div class="↑ TODO"></div>
    </td>
    <td class="2024-03-02"><div class="day">
      <h2 class="date weekend">2</h2>
      <label class="DONE"><input type="checkbox" checked>10:00 | 꿀잠</label>
      <label class="DONE"><input type="checkbox" checked>12:30 | 친구 약속</label>
      <label class="DONE"><input type="checkbox" checked>13:00 | 점심 : 센세이 라멘</label>
      <label class="DONE"><input type="checkbox" checked>14:00 | 오락실</label>
      <label class="DONE"><input type="checkbox" checked>16:00 | 음악 감상</label>
      <label class="DONE"><input type="checkbox" checked>18:30 | 저녁 : 된장찌개 백반</label>
      <label class="DONE"><input type="checkbox" checked>20:00 | 서류 작업</label>
      <div class="↑ DONE"></div>
      <div class="↑ TODO"></div>
    </td>
  </tr>
</table>
