---
title: Institutions
date: 2025-12-18
type: page
---

<style>
/* 页面主标题居中 */
.article-container h1 {
  text-align: center;
}

/* 整个机构部分 */
.institution-section {
  text-align: center;
  margin-bottom: 3rem;
}

/* 分组标题：取消加粗，减小字号 */
.institution-title {
  font-size: 1.5rem;
  font-weight: normal;
  margin-bottom: 1.2rem;
}

.institution-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
}

.institution-card {
  width: 180px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.institution-card img {
  max-width: 100%;
  max-height: 100px;
  object-fit: contain;
}

/* 无 logo 的卡片：稍微收紧顶部空白 */
.institution-card.no-logo {
  padding-top: 0.5rem;
}

.institution-name {
  margin-top: 0.5rem;
  font-size: 1rem;
}

/* 机构名链接样式 */
.institution-name a {
  color: inherit;
  text-decoration: none;
}

.institution-name a:hover {
  text-decoration: underline;
}
</style>

<div class="institution-section">
  <div class="institution-title">Founding Institutions</div>
  <div class="institution-grid">
    <div class="institution-card">
      <img src="/images/institutions/fdu.jpg" alt="Fudan University logo">
      <div class="institution-name">
        <a href="https://www.fudan.edu.cn" target="_blank" rel="noopener">
          Fudan University
        </a>
      </div>
    </div>
    <div class="institution-card">
      <img src="/images/institutions/mq.png" alt="Macquarie University logo">
      <div class="institution-name">
        <a href="https://www.mq.edu.au" target="_blank" rel="noopener">
          Macquarie University
        </a>
      </div>
    </div>
    <div class="institution-card">
      <img src="/images/institutions/pku.jpg" alt="Peking University logo">
      <div class="institution-name">
        <a href="https://www.pku.edu.cn" target="_blank" rel="noopener">
          Peking University
        </a>
      </div>
    </div>
  </div>
</div>

<div class="institution-section">
  <div class="institution-title">Partner Entities</div>
  <div class="institution-grid">
    <!-- 无 logo 的机构：直接移除 img -->
    <div class="institution-card no-logo">
      <div class="institution-name">
        <a href="https://www.mq.edu.au/research/research-centres-groups-and-facilities/centres/minds-and-intelligences" target="_blank" rel="noopener">
          Minds and Intelligences Research Centre
        </a>
      </div>
    </div>
    <div class="institution-card">
      <img src="/images/institutions/partner2.jpg" alt="Partner 2 logo">
      <div class="institution-name">
        <a href="https://example.com" target="_blank" rel="noopener">
          Partner 2
        </a>
      </div>
    </div>
  </div>
</div>
