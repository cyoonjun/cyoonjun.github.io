---
permalink: /
title: false
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
  .home-landing {
    margin-top: 1rem;
  }

  .home-hero {
    display: block;
  }

  .home-main p {
    font-size: 1.18rem;
    line-height: 1.85;
    margin-bottom: 1.8rem;
  }

  .home-section-title {
    margin: 2rem 0 1rem;
    padding-bottom: 0.7rem;
    border-bottom: 1px solid var(--global-border-color);
    color: #667085;
    font-size: 1.55rem;
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
    color: #667085;
    font-size: 1.05rem;
    white-space: nowrap;
  }

  .news-text {
    font-size: 1.12rem;
    line-height: 1.7;
  }

  .selected-pubs {
    margin-top: 3rem;
  }

  .pub-entry {
    padding: 1.2rem 0 1.5rem;
    border-bottom: 1px solid var(--global-border-color);
  }

  .pub-entry:last-child {
    border-bottom: 0;
  }

  .pub-entry-title {
    font-size: 1.55rem;
    line-height: 1.4;
    font-weight: 800;
    margin-bottom: 0.45rem;
  }

  .pub-entry-authors {
    color: #4b5563;
    font-size: 1.05rem;
    line-height: 1.7;
  }

  .pub-entry-meta {
    margin-top: 0.45rem;
    font-size: 1.08rem;
  }

  .pub-entry-links {
    margin-top: 0.45rem;
    font-size: 1rem;
  }

  @media (max-width: 900px) {
    .home-main p {
      font-size: 1.08rem;
      line-height: 1.75;
    }
  }

  @media (max-width: 640px) {
    .news-item {
      grid-template-columns: 1fr;
      gap: 0.35rem;
    }

    .pub-entry-title {
      font-size: 1.28rem;
    }
  }
</style>

<div class="home-landing">
  <div class="home-hero">
    <section class="home-main">
      <p>
        I am a PhD student at Yonsei University, advised by <a href="https://albertno.github.io/" target="_blank">Albert No</a>.
        My research focuses on efficient large language models, with particular interest in quantization and low-rank adaptation.
        I am broadly interested in model compression, and my work revisits assumptions that have long been treated as standard practice.
      </p>

      <h2 class="home-section-title">News</h2>
      <div class="news-list">
        <div class="news-item">
          <div class="news-date">2026</div>
          <div class="news-text">
            <strong>Preserve-Then-Quantize: Balancing Rank Budgets for Quantization Error Reconstruction in LLMs</strong>
            was accepted to <strong>ICML 2026</strong>.
          </div>
        </div>

        <div class="news-item">
          <div class="news-date">Apr 2026</div>
          <div class="news-text">
            <strong>A2D: Any-Order, Any-Step Safety Alignment for Diffusion Language Models</strong>
            was accepted to <strong>ICLR 2026</strong>.
          </div>
        </div>

        <div class="news-item">
          <div class="news-date">Jun 2025</div>
          <div class="news-text">
            <strong>Preserve then Quantize: Dominant-Subspace Guided Low-Rank Reconstruction</strong>
            was accepted to <strong>ICML 2025 TTODLer-FM Workshop</strong> as an <strong>Oral</strong>.
          </div>
        </div>

        <div class="news-item">
          <div class="news-date">May 2025</div>
          <div class="news-text">
            <strong>Assigning Distinct Roles to Quantized and Low-Rank Matrices Toward Optimal Weight Decomposition</strong>
            was accepted to <strong>ACL 2025 Findings</strong>.
          </div>
        </div>
      </div>
    </section>
  </div>

  <section class="selected-pubs">
    <h2 class="home-section-title">Selected Publications</h2>

    <div class="pub-entry">
      <div class="pub-entry-title">Preserve-Then-Quantize: Balancing Rank Budgets for Quantization Error Reconstruction in LLMs</div>
      <div class="pub-entry-authors"><strong>Yoonjun Cho</strong>, Dongjae Jeon, Soeun Kim, Moongyu Jeon, Albert No</div>
      <div class="pub-entry-meta"><em>ICML 2026</em></div>
      <div class="pub-entry-links"><a href="https://arxiv.org/abs/2602.02001" target="_blank">[arXiv]</a></div>
    </div>

    <div class="pub-entry">
      <div class="pub-entry-title">A2D: Any-Order, Any-Step Safety Alignment for Diffusion Language Models</div>
      <div class="pub-entry-authors">Wonje Jeung*, Sangyeon Yoon*, <strong>Yoonjun Cho</strong>, Dongjae Jeon, Sangwoo Shin, Hyesoo Hong, Albert No</div>
      <div class="pub-entry-meta"><em>ICLR 2026</em></div>
      <div class="pub-entry-links"><a href="https://arxiv.org/abs/2509.23286" target="_blank">[arXiv]</a></div>
    </div>

    <div class="pub-entry">
      <div class="pub-entry-title">Assigning Distinct Roles to Quantized and Low-Rank Matrices Toward Optimal Weight Decomposition</div>
      <div class="pub-entry-authors"><strong>Yoonjun Cho</strong>, Soeun Kim, Dongjae Jeon, Kyelim Lee, Beomsoo Lee, Albert No</div>
      <div class="pub-entry-meta"><em>ACL 2025 Findings</em></div>
      <div class="pub-entry-links"><a href="https://arxiv.org/abs/2506.02077" target="_blank">[arXiv]</a></div>
    </div>
  </section>
</div>
