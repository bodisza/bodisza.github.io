---
layout: about
title: about
permalink: /
subtitle: PhD Candidate in Finance · Vienna Graduate School of Finance

profile:
  align: right
  image: aron_bodisz_professional_photo.jpg
  image_circular: false # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  .jm-section { clear: both; padding-top: 0.4rem; scroll-margin-top: 70px; }
  .jm-section h2 { font-size: 1.05rem; font-weight: 500; text-transform: uppercase; letter-spacing: 0.08em; color: var(--global-text-color-light); border-bottom: 1px solid var(--global-divider-color); padding-bottom: 0.4rem; margin: 1.6rem 0 1rem; }
  .jmp-card { border: 1px solid var(--global-divider-color); border-top: 4px solid var(--global-theme-color); border-radius: 8px; background: var(--global-card-bg-color); padding: 1.4rem 1.5rem 1.2rem; }
  .jmp-tag { display: inline-block; font-size: 0.75rem; font-weight: 600; letter-spacing: 0.08em; text-transform: uppercase; color: var(--global-theme-color); margin-bottom: 0.35rem; }
  .jmp-title { font-size: 1.45rem; line-height: 1.3; font-weight: 500; margin: 0 0 0.3rem; color: var(--global-text-color); }
  .jmp-meta { color: var(--global-text-color-light); font-size: 0.92rem; margin: 0 0 1rem; }
  .jmp-grid { display: block; }
  .jmp-grid > div { max-width: 620px; margin: 1.4rem auto 0; }
  .jmp-abstract { font-size: 0.97rem; line-height: 1.6; margin: 0; text-align: left; }
  .jmp-fig { margin: 0; }
  .jmp-fig img { display: block; width: 100%; height: auto; background: #fff; border: 1px solid var(--global-divider-color); border-radius: 6px; padding: 14px 16px; }
  .jmp-fig figcaption { font-size: 0.85rem; color: var(--global-text-color-light); margin-top: 0.6rem; line-height: 1.45; text-align: center; }
  .paper { margin: 0 0 1.3rem; }
  .paper-title { font-size: 1.08rem; font-weight: 500; margin: 0; color: var(--global-text-color); }
  .paper-meta { font-size: 0.92rem; color: var(--global-text-color-light); margin: 0.15rem 0 0.35rem; }
  .paper details summary { cursor: pointer; font-size: 0.88rem; color: var(--global-theme-color); width: max-content; }
  .paper details p { font-size: 0.93rem; line-height: 1.55; margin: 0.5rem 0 0; }
  .refs { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 1rem 1.5rem; font-size: 0.9rem; line-height: 1.45; }
  .refs p { margin: 0; }
  .refs b { font-weight: 500; }
  .refs .muted { color: var(--global-text-color-light); }
  @media (max-width: 576px) {
    .post .profile { width: 38% !important; float: right !important; margin: 0 0 0.6rem 0.9rem !important; }
  }
  @media (max-width: 720px) {
    .jmp-grid, .refs { grid-template-columns: 1fr; }
    .jmp-card { padding: 1.1rem 1rem 1rem; }
    .jmp-title { font-size: 1.25rem; }
    .jmp-fig img { padding: 6px; }
  }
</style>

I am on the 2026–2027 academic job market.

I am a PhD candidate in Finance at the [Vienna Graduate School of Finance (VGSF)](https://www.vgsf.ac.at/), supervised by [Nikolaus Hautsch](https://homepage.univie.ac.at/nikolaus.hautsch/). In fall 2026, I was a visiting PhD student at the Haskayne School of Business, University of Calgary, hosted by [Alfred Lehar](https://profiles.ucalgary.ca/alfred-lehar). My research areas are market microstructure, market design, and decentralized finance (DeFi).

<div class="jm-section" id="job-market-paper">
  <h2>Job Market Paper</h2>
  <div class="jmp-card">
    <span class="jmp-tag">Job Market Paper</span>
    <h3 class="jmp-title">Absorbing the Tail: How Automated Market Makers Affect Limit Order Book Liquidity</h3>
    <p class="jmp-meta">Single-authored</p>
    <div class="jmp-grid">
      <p class="jmp-abstract">The coexistence of an automated market maker (AMM) with a limit order book (LOB) that trades the same asset raises depth at the top of the book. In a model of competitive liquidity supply, the AMM's fixed pricing function lets its liquidity providers (LPs) break even on average over the orders they serve, while LPs on the LOB break even on the marginal unit at each price. When the AMM has a cost advantage over the LOB, it offers better execution than the LOB for orders above a size cutoff and absorbs the largest orders, which carry the most information. LPs on the LOB thus face less informed order flow and post more depth at every price they quote. On Uniswap v3 and Binance, the AMM's share of orders rises with order size, reaching about 86% in the largest size bin on ETH–USDC. The launch of PancakeSwap v3, an AMM on Binance's blockchain, raised depth at Binance's best bid and ask by about 57% relative to Coinbase's, and the gain shrinks farther down the book, as the model predicts.</p>
      <div>
        <figure class="jmp-fig">
          <img src="/assets/img/jmp_tail_absorption.png" alt="Model figure: markup against order size. Orders below a cutoff execute on the order book, larger orders on the AMM. The order book with an AMM charges a lower markup than the order book alone; the gap is the tail-absorption gain." loading="lazy">
          <figcaption>Small orders execute on the order book, large orders on the AMM. With the tail absorbed, the order book charges a lower markup at every size. Adapted from Figure 8 of the paper.</figcaption>
        </figure>
      </div>
    </div>
  </div>
</div>

<div class="jm-section">
  <h2>Working Papers</h2>
  <div class="paper">
    <p class="paper-title">The DeFi Dilemma</p>
    <p class="paper-meta">with <a href="https://homepage.univie.ac.at/nikolaus.hautsch/">Nikolaus Hautsch</a> and <a href="https://voigtstefan.me">Stefan Voigt</a></p>
    <details>
      <summary>Abstract</summary>
      <p>Blockchains let decentralized finance (DeFi) settle transactions without trusted intermediaries through two building blocks: pre-trade transparency of pending transactions and transaction-fee-based priority. We show that these features expose rent-generating transactions to front-running risk, deterring the transactions on which market efficiency depends. Using block-level data on cross-DEX arbitrage across Uniswap V2 and Sushiswap from December 2020 to November 2024, we find that the atomic arbitrage transaction submitted to the public mempool realizes at most 7% of the profit available net of transaction fees. The price differences nonetheless close within a block or two, through dark pools and trades hedged on other venues. When the randomly drawn validator of the next block cannot include dark pool transactions, they stay open one block longer. Overcoming these inefficiencies requires reintroducing centralized intermediation, which undermines the foundational premise of DeFi.</p>
    </details>
  </div>
  <h2>Work in Progress</h2>
  <div class="paper">
    <p class="paper-title">What Drives Stablecoin Yields in DeFi Lending Markets?</p>
    <p class="paper-meta">with Yuan Chen and Min Yang</p>
  </div>
</div>

<div class="jm-section">
  <h2>References</h2>
  <div class="refs">
    <p><b>Nikolaus Hautsch</b> (Supervisor)<br><span class="muted">University of Vienna</span><br><a href="mailto:nikolaus.hautsch@univie.ac.at">nikolaus.hautsch@univie.ac.at</a></p>
    <p><b>Alfred Lehar</b><br><span class="muted">Haskayne School of Business, University of Calgary</span><br><a href="mailto:alehar@ucalgary.ca">alehar@ucalgary.ca</a></p>
    <p><b>Stefan Voigt</b><br><span class="muted">University of Copenhagen</span><br><a href="mailto:stefan.voigt@econ.ku.dk">stefan.voigt@econ.ku.dk</a></p>
    <p><b>Christian Westheide</b><br><span class="muted">Stockholm Business School, Stockholm University</span><br><a href="mailto:christian.westheide@sbs.su.se">christian.westheide@sbs.su.se</a></p>
  </div>
</div>
