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
    <td class="2023-11-01">
      <div class="day">
        <h2 class="date">01</h2>
        <label class="DONE"><input type="checkbox" checked>[07:40] 아침 : 커피 & 음악감상</label>
        <div class="↑ DONE"></div>
        <label class="TODO"><input type="checkbox" c hecked>아침 : 커피 & 음악감상</label>
        <div class="↑ TODO"></div>
        <div class="graph" style="--index: 10; --size-w: 18em; --size-head: 0em; --size-tail: 100px; --color-bg: #A3B6C9; --color-txt: #FFFFFF;">
          <div class="graph-head"></div>
          <p class="graph-title">● 포트폴리오 사이트</p>
          <div class="graph--tail"></div>
        </div>
        <div class="graph" style="--index: 0; --size-w: 16em; --size-head: 0em; --size-tail: 0em; --color-bg: #FFD400; --color-txt: #000000;">
          <div class="graph--head"></div>
          <p class="graph-title">● vanilla-tilt 포팅</p>
          <div class="graph-tail"></div>
        </div>
      </div>
    </td>
    <td class="20xx-xx-02">
      <div class="day">
        <h2 class="date">02</h2>
        <div class="date weekend">~ 공휴일 ~</div>
        <label class="DONE"><input type="checkbox" checked>[07:40] 아침 : 커피 & 음악감상</label>
        <div class="↑ DONE"></div>
        <div class="↑ TODO"></div>
        <div class="graph" style="--index: 10; --size-w: 18em; --size-head: 0em; --size-tail: 100px; --color-bg: #A3B6C9; --color-txt: #FFFFFF;">
          <div class="graph-head"></div>
          <p class="graph-progress">● 포트폴리오 사이트</p>
          <div class="graph--tail"></div>
        </div>
      </div>
    </td>
  </tr>
</table>
