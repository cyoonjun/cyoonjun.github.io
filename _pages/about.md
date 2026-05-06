---
permalink: /
title: false
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
  @media (min-width: 1024px) {
    .home-main,
    .selected-pubs {
      max-width: 50rem;
    }
  }

  .home-landing {
    margin-top: 1rem;
  }

  .home-hero {
    display: block;
  }

  .home-main p {
    color: #2f343b;
    font-size: 1.01rem;
    line-height: 1.8;
    margin-bottom: 1.45rem;
  }

  .home-section-title {
    margin: 2rem 0 1rem;
    padding-bottom: 0.7rem;
    border-bottom: 1px solid var(--global-border-color);
    color: #6b7280;
    font-size: 1.3rem;
    font-weight: 800;
    letter-spacing: 0.06em;
    text-transform: uppercase;
  }

  .news-list {
    display: grid;
    gap: 1rem;
  }

  .news-item {
    display: grid;
    grid-template-columns: 110px minmax(0, 1fr);
    gap: 1.5rem;
    align-items: start;
  }

  .news-date {
    color: #6b7280;
    font-size: 0.98rem;
    white-space: nowrap;
  }

  .news-text {
    color: #2f343b;
    font-size: 1rem;
    line-height: 1.65;
  }

  .selected-pubs {
    margin-top: 3rem;
  }

  .pub-entry {
    margin: 0 0 1.5rem 0;
    padding: 0.9rem 1.1rem;
    border-left: 4px solid #d7dce2;
  }

  .pub-entry:last-child {
    margin-bottom: 0;
  }

  .pub-entry-title {
    color: inherit;
    font-size: 1em;
    line-height: 1.5;
    font-weight: 700;
    margin-bottom: 0;
  }

  .pub-entry-authors {
    margin-top: 0.35rem;
    color: inherit;
    font-size: 1em;
    line-height: 1.6;
  }

  .pub-entry-meta {
    margin-top: 0.2rem;
    color: #4a5568;
    font-size: 1em;
  }

  .pub-entry-links {
    margin-top: 0.45rem;
    font-size: 0.95rem;
  }

  @media (max-width: 900px) {
    .home-main p {
      font-size: 0.98rem;
      line-height: 1.75;
    }
  }

  @media (max-width: 640px) {
    .news-item {
      grid-template-columns: 1fr;
      gap: 0.35rem;
    }

    .pub-entry-title {
      font-size: 1em;
    }
  }
</style>

<div class="home-landing">
  <div class="home-hero">
    <section class="home-main">
      <p>
        I am a PhD student in Computer Science at Yonsei University, where I conduct research in the
        <a href="https://ai-isl.yonsei.ac.kr" target="_blank">Artificial Intelligence and Information Systems Lab</a>
        under the supervision of Professor Albert No.
        My research focuses on efficient large language models, with particular interest in quantization and low-rank adaptation.
        I am broadly interested in model compression, and my work revisits assumptions that have long been treated as standard practice.
      </p>

      <h2 class="home-section-title">News</h2>
      <div class="news-list">
        <div class="news-item">
          <div class="news-date">Jul 2026</div>
          <div class="news-text">
            One paper was accepted to <strong>ICML 2026</strong>.
          </div>
        </div>

        <div class="news-item">
          <div class="news-date">Apr 2026</div>
          <div class="news-text">
            One paper was accepted to <strong>ICLR 2026</strong>.
          </div>
        </div>

        <div class="news-item">
          <div class="news-date">Jun 2025</div>
          <div class="news-text">
            One paper was accepted to <strong>ICML 2025 TTODLer-FM Workshop</strong> as an <strong>oral</strong>.
          </div>
        </div>

        <div class="news-item">
          <div class="news-date">May 2025</div>
          <div class="news-text">
            One paper was accepted to <strong>ACL 2025 Findings</strong>.
          </div>
        </div>
      </div>
    </section>
  </div>

  <section class="selected-pubs">
    <h2 class="home-section-title">Selected Publications</h2>

    <div class="pub-entry">
      <div class="pub-entry-title">Preserve-Then-Quantize: Balancing Rank Budgets for Quantization Error Reconstruction in LLMs</div>
      <div class="pub-entry-authors"><strong>Yoonjun Cho*</strong>, Dongjae Jeon*, Soeun Kim, Moongyu Jeon, Albert No<sup>†</sup></div>
      <div class="pub-entry-meta"><em>ICML 2026</em></div>
      <div class="pub-entry-links"><a href="https://arxiv.org/abs/2602.02001" target="_blank">[arXiv]</a></div>
    </div>

    <div class="pub-entry">
      <div class="pub-entry-title">Assigning Distinct Roles to Quantized and Low-Rank Matrices Toward Optimal Weight Decomposition</div>
      <div class="pub-entry-authors"><strong>Yoonjun Cho</strong>, Soeun Kim, Dongjae Jeon, Kyelim Lee, Beomsoo Lee, Albert No<sup>†</sup></div>
      <div class="pub-entry-meta"><em>ACL 2025 Findings</em></div>
      <div class="pub-entry-links"><a href="https://arxiv.org/abs/2506.02077" target="_blank">[arXiv]</a></div>
    </div>

    <p class="pub-entry-links">* equal contribution &nbsp;&nbsp; <sup>†</sup> corresponding author</p>
  </section>
</div>
