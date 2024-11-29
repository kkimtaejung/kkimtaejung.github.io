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
    justify-content: center;
    gap: 50px;
    margin-top: 30px;
  }

  .category-item {
    text-align: center;
    font-size: var(--font-size, 18px);
  }

  .category-item a {
    text-decoration: none;
    color: #aaa;
    font-size: var(--category-text-size, 32px); /* 텍스트 크기 조정 가능 */
    font-weight: bold;
    transition: color 0.3s;
  }

  .category-item a:hover {
    color: #005f99;
  }

  .category-item a span {
    font-size: 96px;
    display: block;
    color: #666;
    margin-bottom: 10px;
  }
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
