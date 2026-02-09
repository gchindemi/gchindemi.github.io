---
layout: page
permalink: /repositories/
title: repositories
description: A selection of open-source projects I have contributed to.
nav: true
nav_order: 4
---

<style>
.repo-cards {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
  gap: 1.25rem;
  margin-top: 1rem;
}

.repo-card {
  background: var(--global-card-bg-color);
  border: 1px solid var(--global-divider-color);
  border-left: 3px solid var(--global-theme-color);
  border-radius: 6px;
  padding: 1.25rem 1.25rem 1rem;
  transition: box-shadow 0.2s ease, transform 0.15s ease;
  display: flex;
  flex-direction: column;
}

.repo-card:hover {
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
  transform: translateY(-2px);
}

html[data-theme="dark"] .repo-card:hover {
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.3);
}

.repo-card__header {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  margin-bottom: 0.6rem;
}

.repo-card__icon {
  color: var(--global-theme-color);
  font-size: 1.2rem;
  flex-shrink: 0;
}

.repo-card__name {
  font-size: 1.05rem;
  font-weight: 600;
  margin: 0;
  line-height: 1.3;
}

.repo-card__name a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.repo-card__name a:hover {
  text-decoration: underline;
}

.repo-card__desc {
  color: var(--global-text-color-light);
  font-size: 0.92rem;
  line-height: 1.5;
  margin: 0 0 0.75rem;
  flex-grow: 1;
}

.repo-card__meta {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 0.75rem;
  font-size: 0.82rem;
  color: var(--global-text-color-light);
}

.repo-card__lang {
  display: inline-flex;
  align-items: center;
  gap: 0.35rem;
}

.repo-card__lang-dot {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  display: inline-block;
  flex-shrink: 0;
}

.repo-card__role {
  display: inline-flex;
  align-items: center;
  gap: 0.3rem;
  font-size: 0.78rem;
  background: var(--global-bg-color);
  border: 1px solid var(--global-divider-color);
  border-radius: 999px;
  padding: 0.15rem 0.6rem;
  color: var(--global-text-color-light);
  white-space: nowrap;
}

.github-profile {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  margin-top: 0.5rem;
  padding: 0.6rem 1.2rem;
  border: 1px solid var(--global-divider-color);
  border-radius: 6px;
  color: var(--global-text-color);
  text-decoration: none;
  font-size: 0.95rem;
  transition: border-color 0.2s ease, color 0.2s ease;
}

.github-profile:hover {
  border-color: var(--global-theme-color);
  color: var(--global-theme-color);
  text-decoration: none;
}

.github-profile i {
  font-size: 1.3rem;
}
</style>

<div class="repo-cards">

  <div class="repo-card">
    <div class="repo-card__header">
      <i class="fa-brands fa-github repo-card__icon"></i>
      <h5 class="repo-card__name">
        <a href="https://github.com/BelloneLab/lisbet" target="_blank" rel="noopener noreferrer">BelloneLab/lisbet</a>
      </h5>
    </div>
    <p class="repo-card__desc">
      LISBET Is a Social BEhavior Transformer — social behavior classification using self-supervised learning.
    </p>
    <div class="repo-card__meta">
      <span class="repo-card__lang">
        <span class="repo-card__lang-dot" style="background-color: #3572A5;"></span>
        Python
      </span>
      <span class="repo-card__role"><i class="fa-solid fa-code-branch"></i> Core contributor</span>
    </div>
  </div>

  <div class="repo-card">
    <div class="repo-card__header">
      <i class="fa-brands fa-github repo-card__icon"></i>
      <h5 class="repo-card__name">
        <a href="https://github.com/BlueBrain/BluePyOpt" target="_blank" rel="noopener noreferrer">BlueBrain/BluePyOpt</a>
      </h5>
    </div>
    <p class="repo-card__desc">
      Blue Brain Python Optimisation Library — evolutionary algorithms for neuron model parameter optimization.
    </p>
    <div class="repo-card__meta">
      <span class="repo-card__lang">
        <span class="repo-card__lang-dot" style="background-color: #3572A5;"></span>
        Python
      </span>
      <span class="repo-card__role"><i class="fa-solid fa-code-branch"></i> Contributor</span>
    </div>
  </div>

</div>

---

<p style="margin-bottom: 0.25rem; color: var(--global-text-color-light); font-size: 0.95rem;">Find more on</p>
<a class="github-profile" href="https://github.com/gchindemi" target="_blank" rel="noopener noreferrer">
  <i class="fa-brands fa-github"></i> <strong>gchindemi</strong>
</a>