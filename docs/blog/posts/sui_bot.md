---
date:
  created: 2025-02-10
  updated: 2025-02-10
pin: true
links:
  - Homepage: index.md
  - Blog index: blog/index.md
categories:
  - project
tags:
  - sui
  - tech
authors:
  - shirakoslurper
---

# Sui Bot

The single most intensive project I've undertaken is [arbisui](https://github.com/shirakoslurper/arbisui), a Sui DEX arbitrage bot.

To be honest, the codebase is a mess outside of the tooling, and things could be done a hell of a lot better. However, I think I did a fair bit of pioneering on the chain, though I didn't take it to the massive profit finish line.

I was somewhat familiar with MEV and on-chain arbitrage due to sort of finding myself in the right Twitter circles and Discords, and though I'd always wanted to try, it felt a bit daunting to my very junior engineer self - increasingly more so since competition on the big chains included the known big quant firms and whatnot.

I hadn't really done much in terms of completing projects, and though I had a CS degree almost tucked into my belt, my lack of professional experience and exposure meant there was nothing compensating for that. But the folks in the field said sometimes "easier" money comes around. New chains pop up with smaller but less competitive opportunities, the tradeoff being that you have to "eat glass" and work around lack of dev-tooling, documents, young badly-written protocols, node access, infrastructure, etc. Enter uncharted territory, a good place to skill up.

But, oof, lotsa stuff had to be done. 

This will be more of a listing of problems I semi-dealt with. "Semi" because I solved them up to the point of the existing infrastructure not supporting more complete solutions by the time I dropped the project. The problems have been sort of glossed over on the github readme. 

TBC...

> Will be coming around to complete this but there's mounds and mounds of notes.

<!-- ## 1) Fetching Data

To make a trade you need data. You need prices, liqudity, and tick data (if protocols require it) pre market for all the markets you want to cover.

> Understanding this requires a bit of familiarity with Uni V2 and V3 DEXes.

Sui's relational data scheme was very, very not friendly to this. 

For Uni V2 style protocols, a single contract held all the information. No problem.
For Uni V3 based contract, however

## 2) Keeping Orderbooks -->

