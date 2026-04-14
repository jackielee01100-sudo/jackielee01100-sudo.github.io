---
layout: page
title: Introduction
icon: fas fa-tasks
order: 1
---

<div class="custom-timeline">
  <div class="timeline-group">
    <div class="timeline-year">2026</div>
    <div class="timeline-content">

      <div class="timeline-item">
        <div class="item-date">1 DEC</div>
        <div class="item-text"><span class="license">[License]</span> 정보보안기사 : Korean License (Engineer information security)</div>
      </div>

      <div class="timeline-item">
        <div class="item-date">30 NOV</div>
        <div class="item-text"><span class="license">[License]</span> CFA Lv1 : Chartered Financial Analyst</div>
      </div>

      <div class="timeline-item">
        <div class="item-date">29 NOV</div>
        <div class="item-text"><span class="license">[License]</span> ADP : Korean License (Advanced Data Analytics Professional)</div>
      </div>

      <div class="timeline-item">
        <div class="item-date">28 NOV</div>
        <div class="item-text"><span class="license">[License]</span> 리눅스마스터1급 : Korean License (Linux Master Advanced/Grade 1)</div>
      </div>

      <div class="timeline-item">
        <div class="item-date">01 Oct</div>
        <div class="item-text"><span class="project">[Project]</span> App/Web for explaining nutritional supplement </div>
      </div>

       <div class="timeline-item">
        <div class="item-date">30 SEP</div>
        <div class="item-text"><span class="license">[License]</span> DAP : Korean License (Data Architecture Professional)</div>
      </div>
      
       <div class="timeline-item">
        <div class="item-date">01 SEP</div>
        <div class="item-text"><span class="license">[License]</span> SQLP : Korean License (SQL Professional) </div>
      </div>

      <div class="timeline-item">
        <div class="item-date">01 June</div>
        <div class="item-text"><span class="ha">[Honors & Awards]</span> World Quant Ranking 10 </div>
      </div>

      <div class="timeline-item">
        <div class="item-date">01 May</div>
        <div class="item-text"><span class="project">[Project]</span> App/Web for investment simulation </div>
      </div>
      
    </div>
  </div>

  <div class="timeline-group">
    <div class="timeline-year">2022</div>
    <div class="timeline-content">
      <div class="timeline-item">
        <div class="item-date">01 JAN</div>
        <div class="item-text"><span class="career">[Career]</span> 백엔드 개발자로서의 새로운 도전 시작 (4년 차)</div>
      </div>
    </div>
  </div>

  <div class="timeline-group">
    <div class="timeline-year">2014</div>
    <div class="timeline-content">
      <div class="timeline-item">
        <div class="item-date">01 MAR</div>
        <div class="item-text"><span class="career">[Career]</span> 해외영업 매니저 입사 (글로벌 비즈니스 8년)</div>
      </div>
    </div>
  </div>
</div>

<style>
  .custom-timeline {
    margin: 2rem 0;
    padding-left: 1rem;
  }

  .timeline-group {
    position: relative;
    padding-bottom: 1.5rem;
  }

  /* 세로 선: 모든 그룹을 관통 */
  .timeline-group::before {
    content: '';
    position: absolute;
    left: 4.5rem; /* 연도와 텍스트 사이 정중앙 */
    top: 0;
    bottom: 0;
    width: 2px;
    background-color: var(--main-border-color, #ececec);
  }

  /* 연도 스타일 */
  .timeline-year {
    font-size: 1.5rem;
    font-weight: 800;
    margin-bottom: 1.5rem;
    color: var(--heading-color);
    position: relative;
    z-index: 2;
  }

  /* 연도 옆 동그라미 */
  .timeline-year::after {
    content: '';
    position: absolute;
    left: 4.5rem;
    top: 50%;
    transform: translate(-50%, -50%);
    width: 12px;
    height: 12px;
    background-color: var(--main-wrapper-bg);
    border: 3px solid var(--main-border-color, #ececec);
    border-radius: 50%;
  }

  .timeline-content {
    padding-left: 0;
  }

  .timeline-item {
    display: flex;
    align-items: flex-start;
    margin-bottom: 2rem;
    position: relative;
    z-index: 2;
  }

  /* 날짜 스타일: 선의 왼쪽에 배치 */
  .item-date {
    min-width: 4rem;
    text-align: right;
    font-size: 0.85rem;
    font-weight: 600;
    color: var(--text-muted-color);
    padding-top: 0.2rem;
  }

  /* 텍스트 내용 스타일: 선의 오른쪽에 배치 */
  .item-text {
    margin-left: 2rem; /* 선과의 간격 */
    line-height: 1.6;
    flex: 1;
  }

  /* 마지막 그룹의 선 제거 (선택 사항) */
  .timeline-group:last-child::before {
    bottom: 50%;
  }
  
  .project {
  color: #ff0000;
  font-weight: bold;
  margin-right: 5px;
}

    .license {
  color: #3498db;
  font-weight: bold;
  margin-right: 5px;
}

    .career {
  color: #008000;
  font-weight: bold;
  margin-right: 5px;
}

      .ha {
  color: #800080;
  font-weight: bold;
  margin-right: 5px;
}

</style>
