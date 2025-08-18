---
layout: page
title: Books
permalink: /books/
hide_title:
---

<style>
  .book-list {
    counter-reset: book-counter;
    list-style-type: decimal;
    padding-left: 0;
  }

  .book-list li {
    display: flex;
    align-items: flex-start;
    gap: 12px;
    margin-bottom: 20px;
    list-style: none;
  }

  .book-list li::before {
    content: counter(book-counter) ".";
    font-weight: 700;
    font-size: 1.05rem;
    line-height: 1.2;
    width: 2.2ch;               /* 번호 폭 고정으로 정렬 예쁨 */
    text-align: right;
    margin-right: 6px;
    align-self: center;         /* 번호 세로 가운데 */
    flex: 0 0 auto;
  }

  .book-cover {
    width: 5%;
    height: auto;
    min-width:100px;
    max-width:500px;
    margin-right: 20px;
  }

  .book-info {
    flex: 1;
    max-width: 2000px;
  }
</style>

<ol class="book-list";>
  <li>
    <img src="../images/ISBN_9791194145226.jpg" alt="Image" class="book-cover">
    <div class="book-info">
      챗GPT를 활용한 영어과학논문작성법 (개정판)<br>
      <b>곽수빈</b>, 최용호, 김현동, 남윤재, 마주호, 김준석 | <em>지오북스</em> | 2025. 04. 01. | ISBN: 9791194145226
    </div>
  </li>

  <li>
    <img src="../images/ISBN_9791191346626.jpg" alt="Image" class="book-cover">
    <div class="book-info">
      챗GPT를 활용한 영어과학논문작성법<br>
      <b>곽수빈</b>, 최용호, 김준석 | <em>지오북스</em> | 2023. 07. 01. | ISBN: 9791191346626
    </div>
  </li>

  <li>
    <img src="../images/9791191346572.jpg" alt="Image" class="book-cover">
    <div class="book-info">
      다상 유체 유동에 대한 상태장 모델링과 멀티그리드 수치기법<br>
      <b>곽수빈</b>, 강승윤, 황영진, 함석준, 이경규, 최용호, 김준석 | <em>지오북스</em> |  2023. 02. 28. | ISBN: 9791191346572
    </div>
  </li>

  <li>
    <img src="../images/9791191346374.jpg" alt="Image" class="book-cover">
    <div class="book-info">
      MATLAB 활용 수치해석<br>
      김준석, <b>곽수빈</b>, 이채영, 황영진, 강승윤, 함석준, 이경규 | <em>지오북스</em> | 2022. 04. 01. | ISBN:  9791191346374
    </div>
  </li>

  <li>
    <img src="../images/9791191346077.jpg" alt="Image" class="book-cover">
    <div class="book-info">
      코딩수학 파이썬 1<br>
      김상권, 김현동, <b>곽수빈</b>*, 황영진, 김준석 | <em>지오아카데미</em> | 2021. 09. 01. | ISBN: 9791191346077
    </div>
  </li>

  <li>
    <img src="../images/9791191346091.jpg" alt="Image" class="book-cover">
    <div class="book-info">
      수학적 모델링 콘텐츠 파이썬 1<br>
      김준석, 김상권, 이채영, 최용호, <b>곽수빈</b>, 황영진 | <em>지오북스</em> | 2021. 09. 01. | ISBN: 9791191346091
    </div>
  </li>

  <li>
    <img src="../images/9791191346046.jpg" alt="Image" class="book-cover">
    <div class="book-info">
      텐서플로 25시간만에 배우는 머신러닝 예제<br>
      김상권, 김현동, <b>곽수빈</b>, 한현수, 장한별, 김준석 | <em>지오아카데미</em> | 2021. 05. 01. | ISBN: 9791191346046
    </div>
  </li>

  <li>
    <img src="../images/9791187541943.jpg" alt="Image" class="book-cover">
    <div class="book-info">
      보르노이 다이어그램<br>
      김준석, <b>곽수빈</b>, 김상권, 윤성하, 김현동, 문현, 이채영 | <em>지오북스</em> | 2020. 11. 01. | ISBN: 9791187541943
    </div>
  </li>

  <li>
    <img src="../images/9791187541882.jpg" alt="Image" class="book-cover">
    <div class="book-info">
      파이썬 활용 산업응용수학의 기본<br>
      김준석, 김상권, 이채영, 정다래, 최용호, <b>곽수빈</b> | <em>지오북스</em> | 2020. 09. 10. | ISBN: 9791187541882
    </div>
  </li>

</ol>

<div style="text-align: right; font-size: 0.9em; color: gray;">
Last updated: {{ site.time | date: "%Y-%m-%d" }}
</div>
