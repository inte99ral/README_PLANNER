<h1>2024. 3</h1>

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
  <tr>
    <td class="2024-03-03"><div class="day">
      <h2 class="date weekend">3</h2>
      <label class="DONE"><input type="checkbox" checked>10:00 | 꿀잠</label>
      <label class="DONE"><input type="checkbox" checked>12:30 | 코딩</label>
      <label class="DONE"><input type="checkbox" checked>13:00 | 점심 : 신라면</label>
      <label class="DONE"><input type="checkbox" checked>16:00 | 서류 작업</label>
      <label class="DONE"><input type="checkbox" checked>17:20 | 주말 청소</label>
      <label class="DONE"><input type="checkbox" checked>18:30 | 저녁 : 삼겹살 데이 삼겹살</label>
      <label class="DONE"><input type="checkbox" checked>20:00 | 알고리즘 공부</label>
      <div class="↑ DONE"></div>
      <div class="↑ TODO"></div>
    </td>
    <td class="2024-03-04"><div class="day">
      <h2 class="date">4</h2>
      <label class="DONE"><input type="checkbox" checked>08:00 | 아침 : 시리얼 & 커피</label>
      <label class="DONE"><input type="checkbox" checked>10:00 | 알고리즘 공부</label>
      <label class="DONE"><input type="checkbox" checked>12:30 | 점심 : 왕뚜껑 봉지라면</label>
      <label class="DONE"><input type="checkbox" checked>14:00 | 눈마사지</label>
      <label class="DONE"><input type="checkbox" checked>18:30 | 저녁 : 된장찌개 & 소시지 구이</label>
      <label class="DONE"><input type="checkbox" checked>20:00 | 알고리즘 공부</label>
      <label class="DONE"><input type="checkbox" checked>21:27 | g++ 디버깅</label>
      <label class="DONE"><input type="checkbox" checked>23:11 | 기타 정비</label>
      <div class="↑ DONE"></div>
      <div class="↑ TODO"></div>
    </td>
    <td class="2024-03-05"><div class="day">
      <h2 class="date">5</h2>
      <label class="TODO"><input type="checkbox" checked>10:00 | 늦잠</label>
      <label class="TODO"><input type="checkbox" checked>11:00 | c++ 공부 : 헤더 정리</label>
      <label class="TODO"><input type="checkbox" checked>12:00 | 아점 : 왕뚜껑 쿠지라이식</label>
      <label class="TODO"><input type="checkbox" checked>15:00 | c++ 공부 : 리눅스 쉘 스크립트</label>
      <label class="TODO"><input type="checkbox" checked>18:00 | 저녁 : 두부 김치 & 계란후라이</label>
      <label class="TODO"><input type="checkbox" checked>20:00 | 기타 연습</label>
      <div class="↑ DONE"></div>
      <label class="TODO"><input type="checkbox" c hecked>오전 칼기상</label>
      <label class="TODO"><input type="checkbox" c hecked>운동</label>
      <label class="TODO"><input type="checkbox" c hecked>언리얼 공부</label>
      <div class="↑ TODO"></div>
    </td>
    <td class="2024-03-06"><div class="day">
      <h2 class="date">5</h2>
      <div class="↑ DONE"></div>
      <label class="TODO"><input type="checkbox" c hecked>삼성</label>
      <label class="TODO"><input type="checkbox" c hecked>알고리즘</label>
      <label class="TODO"><input type="checkbox" c hecked>TH3 세팅</label>
      <div class="↑ TODO"></div>
    </td>
  </tr>
</table>
