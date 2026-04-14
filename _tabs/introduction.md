---
layout: page
title: introduction
icon: fas fa-tasks
order: 3
---
<div id="archives" class="pl-xl-2">
  <div class="year lead">2026</div>
  <ul class="list-unstyled">
    <li>
      <span class="date day">17</span>
      <span class="date month">Mar</span>
      <span class="ml-3"><strong>[Project]</strong> OARecorder MVP 완료 및 블로그 런칭</span>
    </li>
  </ul>

  <div class="year lead">2022</div>
  <ul class="list-unstyled">
    <li>
      <span class="date day">01</span>
      <span class="date month">Jan</span>
      <span class="ml-3"><strong>[Career]</strong> 백엔드 개발자로서의 새로운 도전 시작 (4년 차)</span>
    </li>
  </ul>

  <div class="year lead">2014</div>
  <ul class="list-unstyled">
    <li>
      <span class="date day">01</span>
      <span class="date month">Mar</span>
      <span class="ml-3"><strong>[Career]</strong> 해외영업 매니저 입사 (글로벌 비즈니스 8년)</span>
    </li>
  </ul>
</div>

<style>
  /* 1. 컨테이너 설정: 전체적인 왼쪽 여백 확보 */
  #archives {
    padding-left: 1.5rem;
    margin-top: 2rem;
  }

  /* 2. 연도 스타일: 선 위에 동그라미가 위치하도록 조정 */
  #archives .year {
    position: relative;
    font-size: 1.5rem;
    font-weight: 700;
    margin: 3rem 0 1.5rem -0.5rem; /* 선 위치에 맞게 왼쪽으로 살짝 이동 */
    display: flex;
    align-items: center;
  }

  /* 3. 세로 선: ul 태그의 왼쪽 테두리를 사용해 끊김 없이 연결 */
  #archives ul {
    list-style: none;
    padding-left: 1.5rem;
    border-left: 2px solid var(--main-border-color, #ececec); /* 테마 색상 사용 */
    margin-left: 0.45rem; /* 연도 동그라미 중심에 맞춤 */
    margin-bottom: 2rem;
  }

  /* 4. 리스트 항목: 선에서 뻗어나오는 점(옵션) 혹은 간격 유지 */
  #archives li {
    position: relative;
    display: flex;
    align-items: center;
    padding: 1.2rem 0;
  }

  /* 5. 날짜와 텍스트 정렬 */
  #archives .date {
    display: flex;
    align-items: baseline;
    min-width: 4.5rem;
    color: var(--text-muted-color);
  }

  #archives .day {
    font-size: 1.1rem;
    font-weight: 600;
    margin-right: 0.4rem;
  }

  #archives .month {
    text-transform: uppercase;
    font-size: 0.8rem;
  }

  /* 텍스트 내용 간격 */
  .ml-3 {
    margin-left: 1.5rem !important;
  }

  /* 연도 옆 동그라미 아이콘 위치 고정 */
  #archives .year::after {
    content: '';
    position: absolute;
    left: 0.35rem; /* 세로 선(border-left)의 위치와 일치시켜야 함 */
    width: 12px;
    height: 12px;
    background: var(--main-wrapper-bg);
    border: 3px solid var(--main-border-color, #ececec);
    border-radius: 50%;
    z-index: 1;
  }
</style>
