---
layout: home
permalink: /
author_profile: true
---

<style>

  /* 프로필 영역 스타일 */
  .profile-container {
    display: flex;
    align-items: flex-start; /* 상단 정렬 */
    margin-bottom: 30px;
    margin-top: 20px;
  }

  .profile-container img {
    border-radius: 20%; /* 둥근 이미지 */
    width: 165px; /* 프로필 사진 크기 */
    height: 210px;
    margin-right: 20px;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2); /* 그림자 추가 */
  }

  .profile-details {
    font-size: var(--profile-font-size, 18px);
    line-height: 3; /* 줄 간격 */
  }

    .profile-details strong {
    font-weight: bold; /* 강조 */
  }

  .profile-details span {
    display: block; /* 각 항목을 블록으로 나눔 */
    margin-bottom: 8px; /* 항목 간격 */
  }

  /* 인용구 스타일 */
  .blockquote {
    font-size: 32px;
    line-height: 2.4;
    font-style: italic;
    color: #888;
    text-align: center;
    position: relative;
    margin: 40px 0;
  }

  .blockquote::before,
  .blockquote::after {
    content: '"';
    font-size: 48px;
    color: #aaa;
    position: absolute;
  }

  .blockquote::before {
    top: -10px;
    left: -20px;
  }

  .blockquote::after {
    bottom: -10px;
    right: -20px;
  }

  /* 카테고리 스타일 */
  .category-container {
    display: flex;
    justify-content: space-around; /* 균등 배치 */
    align-items: center;
    gap: 20px; /* 간격 조정 */
    margin-top: 40px;
    padding: 20px;
  }

  .category-item {
    text-align: center;
    font-size: 18px;
    color: #ffffff; /* 텍스트 색상 */
    border-radius: 10px; /* 둥근 테두리 */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* 그림자 효과 */
    padding: 20px 30px; /* 내부 여백 */
    transition: transform 0.3s ease, box-shadow 0.3s ease; /* 마우스 효과 */
    width: 150px; /* 고정 너비 */
  }

  .category-item:hover {
    transform: scale(1.05); /* 확대 효과 */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4); /* 그림자 강조 */
  }

  .category-item a {
    text-decoration: none;
    color: #ffffff; /* 텍스트 색상 */
    font-size: 20px; /* 텍스트 크기 */
    font-weight: bold;
    display: block;
  }

  .category-item a span {
    font-size: 48px; /* 아이콘 크기 */
    display: block;
    color: #f39c12; /* 아이콘 색상 (오렌지톤) */
    margin-bottom: 10px; /* 아이콘과 텍스트 사이 간격 */
</style>

<div class="profile-container">
  <img src="/images/2023-09-26-first/증명사진20241125.jpg" alt="Profile Picture">
  <div class="profile-details">
    <strong>이름:</strong> 김태정<br>
    <strong>직책:</strong> 석사과정 및 예비창업자<br>
    <strong>공식 이메일:</strong> ktaejung@chungbuk.ac.kr<br>
    <strong>약력:</strong> 충북대학교 졸업, ROBOTICS 연구실 석사과정
    
  </div>
</div>

<div class="blockquote">
  Consistency alone makes you a capable person.
</div>

<div class="category-container">
  <div class="category-item">
    <a href="/categories/research/">
      <span>📝</span>
      Research
    </a>
  </div>
  <div class="category-item">
    <a href="/categories/startup/">
      <span>📈</span>
      Startup
    </a>
  </div>
  <div class="category-item">
    <a href="/categories/daily/">
      <span>☀️</span>
      Daily
    </a>
  </div>
</div>

