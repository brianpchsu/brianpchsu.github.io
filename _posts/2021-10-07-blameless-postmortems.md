---
layout: post
title: "不指責人的事後檢討"
date: 2021-10-07
description: "一場讓全球服務中斷的大事故，在矽谷的文化裡不會變成獵巫大會。這篇記錄敝司的 SEV 制度與不指責人的檢討會：與其指責犯錯的人，不如找出讓一個錯誤能直達 production 的系統問題。"
lang: zh
permalink: /zh/blog/blameless-postmortems/
topics: [career]
featured: true
translation_ref: blameless-postmortems
---

* 目錄
{:toc}

本週一敝司出了個大事故，許多服務用戶都連不上，但反常的是，連員工要連內網的各種服務也都上不了，僅能使用 email 聯絡。事故發生的細節可以參考工程部落格的文章（More details about the October 4 outage）。

看到一些人分享到說這麼大的全球事故，公司損失慘重，造成的人要被 fired 了等言論，這應該是比較不了解矽谷的文化才會這樣猜測（當然我也不確定是不是大部分矽谷公司都是這樣 XD）。

## SEV 與不指責人的檢討會

在敝司，嚴重事故叫做 SEV（Site EVent），依照嚴重程度分不同等級，這次影響全球事故的是最高級。事件發生過程中相關組的 oncall 或是可以提供幫助的工程師會加入協助處理。在事件修復後，會開一個檢討會 SEV Review，會議中不是要秋後算賬，而是要看從事件中學習到什麼，未來如何加強系統、流程，預防同樣的事情再次發生，或是發生類似的事情可以怎麼樣更快的復原。如果一個工程錯誤可以造成系統出錯，是因為我們系統的 review process 不夠？Integration tests 或是模擬測試沒有抓到問題？Roll out 的太快讓錯誤直接影響很多使用者？還是有其他之前系統沒有考慮到的因素？又或是整個流程本來就容易讓人為錯誤直接到 production？如果一個工程師一個錯誤就可以讓整個網站掛點，那是不是駭客攻擊也可以有達到一樣的損失？會議中不會有人指責為什麼造成事故的工程師寫那樣的 code/script，因為那沒有任何幫助，而且出錯通常都是一系列的問題造成的結果，事件發生後的指責文化也會阻礙未來大家的創新嘗試。

前 VP Vijaye 也寫了一篇他的 Blameless SEV review 心得及有趣的親身故事，有興趣的讀者可以看 [Blameless SEV review](https://www.linkedin.com/posts/vijaye_blameless-sev-review-at-facebook-whenever-activity-6851577359695527936-F4U0/)。

你們公司的事後檢討是怎麼樣呢？歡迎分享！

#我自己也造成過一個SEV

---

*本文原發表於舊站「半路出家軟體工程師在矽谷」（2021 年 10 月 7 日）。該站現已下線，全文由 Wayback Machine 備份保存，搬到本站時做了輕度編輯。*
