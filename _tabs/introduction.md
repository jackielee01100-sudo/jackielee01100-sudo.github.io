---
layout: page
title: introduction
icon: fas fa-tasks
order: 3
---
<style>
  /* 전체 타임라인 컨테이너 */
  #archives {
    position: relative;
    padding-left: 2rem;
    border-left: 2px solid #dfdfdf; /* 왼쪽 전체를 관통하는 기본 선 */
    margin-left: 1rem;
  }

  /* 연도 제목 스타일 */
  #archives .year {
    position: relative;
    margin-top: 2.5rem;
    margin-bottom: 1.5rem;
    font-weight: 700;
    left: -2.6rem; /* 선 위로 위치 조정 */
    background: white; /* 선과 겹치는 부분 가리기 */
    padding: 5px 0;
    width: fit-content;
  }

  /* 연도 옆의 동그란 아이콘 */
  #archives .year::before {
    content: '';
    position: absolute;
    left: 2.15rem;
    top: 50%;
    transform: translateY(-50%);
    width: 12px;
    height: 12px;
    border-radius: 50%;
    background: white;
    border: 3px solid #dfdfdf;
    z-index: 1;
  }

  /* 리스트 항목 스타일 */
  #archives ul {
    margin-bottom: 0;
  }

  #archives li {
    display: flex;
    align-items: center;
    position: relative;
    padding: 1rem 0; /* 항목 간 간격을 균일하게 */
    line-height: 1.5;
  }

  /* 날짜와 텍스트 정렬 */
  #archives .date {
    display: flex;
    align-items: baseline;
    min-width: 4rem;
    color: #6c757d;
  }

  #archives .day {
    font-size: 1.1rem;
    font-weight: 600;
    margin-right: 0.3rem;
  }

  #archives .month {
    text-transform: uppercase;
    font-size: 0.8rem;
  }

  .ml-3 {
    margin-left: 1.5rem !important;
  }
</style>
