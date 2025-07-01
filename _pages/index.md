---
layout: home
permalink: /
author_profile: true
---

<style>
  /* 프로필 영역 스타일 */
  .profile-container {
    display: flex;
    align-items: flex-start;
    margin-bottom: 30px;
    margin-top: 20px;
    flex-wrap: wrap; /* 모바일에서 줄바꿈 가능 */
  }

  .profile-container img {
    border-radius: 20%;
    width: 150px; /* 프로필 사진 크기 조정 */
    height: auto; /* 비율 유지 */
    margin-right: 20px;
    margin-bottom: 20px; /* 모바일에서 간격 추가 */
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  }

  .profile-details {
    font-size: var(--profile-font-size, 18px);
    line-height: 1.8; /* 줄 간격 */
    flex: 1; /* 내용이 사진 옆에 자연스럽게 위치 */
  }

  .profile-details strong {
    font-weight: bold;
  }

  .profile-details span {
    display: block;
    margin-bottom: 8px;
  }

  /* 인용구 스타일 */
  .blockquote {
    font-size: 24px; /* 크기 조정 */
    line-height: 1.6;
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
    flex-direction: column; /* 세로로 배치 */
    align-items: center; /* 가운데 정렬 */
    gap: 20px; /* 간격 추가 */
    margin-top: 40px;
    padding: 20px;
  }

  .category-item {
    text-align: center;
    font-size: 16px;
    color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    padding: 20px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    width: 80%; /* 세로 배치에서 중앙에 적절한 너비 */
  }

  .category-item:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
  }

  .category-item a {
    text-decoration: none;
    color: #ffffff;
    font-size: 18px;
    font-weight: bold;
    display: block;
  }

  .category-item a span {
    font-size: 36px; /* 아이콘 크기 조정 */
    display: block;
    color: #f39c12;
    margin-bottom: 10px;
  }

  /* 반응형 스타일 */
  @media (max-width: 768px) {
    .profile-container {
      flex-direction: column; /* 모바일에서 세로 배치 */
      align-items: center; /* 가운데 정렬 */
    }

    .profile-container img {
      margin-right: 0; /* 마진 제거 */
    }

    .category-item {
      width: calc(100% - 40px); /* 모바일에서 전체 너비 사용 */
    }

    .blockquote {
      font-size: 20px; /* 모바일에서 크기 줄임 */
    }
  }
</style>

<div class="profile-container">
  <img src="/images/블로그메인사진2.jpg" alt="Profile Picture">
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
