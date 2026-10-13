---
layout: post
title: "矽谷軟體工程師的日常工作內容"
date: 2015-12-30
description: "2015 年底加入 SolarCity 後的工程師日常：第一天的裝備、Grid System 團隊分工、sprint 與 standup 的節奏、每天用的工具、當面試官的初體驗，以及公司的各種小福利。"
lang: zh
permalink: /zh/blog/day-in-the-life/
topics: [career, silicon-valley]
featured: false
translation_ref: day-in-the-life
---

* 目錄
{:toc}

2015 進入最後幾天，在做 2016 新年計畫的同時，也回顧反省我的 2015 年。總結來說，今年是個冒險挑戰的一年，從東岸馬里蘭搬到加州追尋夢想，過程有各種酸甜苦辣，箇中滋味可能真的要親身經歷才能體會。許多朋友認為我當初決定辭職很冒險，應該要邊上班邊找工作慢慢計畫，但是我知道我不像大學（或更早開始學程式）的朋友有時間慢慢來，半路出家自學的我已經落後很多了，在我評估後決定要做的計畫，我就要破釜沉舟地賭上所有籌碼去完成，當然失敗的話就是花光所有積蓄而什麼都沒達成。

如果你看了我的[前幾篇找工作的文章](/zh/blog/job-hunting-in-america/)的話，你就知道我的找工作歷程比我一開始想像的更刺激，從以前只能偷偷羨慕矽谷各大科技公司的工作環境及工作內容，到我實際來敲 Google、Facebook、Apple、Amazon、Yahoo、PayPal、Uber、Box、SolarCity... 的門面試，這些知名公司經過精心設計的面試本身就是個讓人享受的過程，藉由和頂尖工程師的面試洗禮讓我更了解我的優勢及劣勢，也更加確認這是我想追求的道路。

最後我加入的 Elon Musk 的公司：SolarCity，對於有環境科學背景以及重視環境保護的我，能在全美知名且成長快速的太陽能公司做軟體工程師真是對我再好不過的選擇了！

之前請大家幫忙寫問卷的文章收到許多朋友建議，最多人想看的內容就是矽谷工程師的日常工作情況，well... 之前我在 Virginia 的 startup 上班，而目前我只在一間矽谷的公司工作，我就先把今年我體悟的矽谷工作的新奇之處和大家分享。

## 拿到 offer 後，立場完全反轉

當我通過最後的 onsite interview 後，如果公司要給我工作，這時候就很有趣了，我們雙方的立場和申請工作時完全相反了，公司會希望我趕快簽下 offer，各種 offer 問題都能快速得到解答，HR 態度從本來就不錯變得超好，並且以各種誘因動之以情，在經歷找工作的持續壓力後，可以享受被反向追求的感覺，是很過癮的。

## 第一天的裝備

第一天上班拿到的裝備是 Apple 當下最高階的 15 吋 Macbook Pro，以前常常看到矽谷科技公司的 job opening 就會說會帶你去 Apple Store 買你想要的任何裝備，我老闆給我 Mac 時也說我可以挑任何裝備（Boss: Oh... I forgot to ask you, but you definitely can get a Windows laptop...），不過已經用習慣 mac 的我當然是心甘情願的趕緊收下來用。

## 我的團隊：Grid System

我是隸屬 SolarCity software engineering 部門的 Grid System（電力網絡）team，我們 Grid System 可以再細分成 Embedded、Infrastructure、Controls & Analytics、Business Application & Data Transfers、及 Customer Applications。我是在 Customer Application 組，主要負責前端的開發（及一點點後端）。大公司的好處是每個部分的職權分得很細，不會像 startup 要做 end to end 的開發，我的工作如果要後端的 data，可以直接去找相關負責的組員來提供。

上班一開始我看到我的 team 30 幾個人的 mac 會想公司真是大手筆阿，但是真的開始工作後每天 mac 隨時有一堆 tasks，又開個 VM 及其他有的沒的，電腦跑起來有時也是頓頓的，如果是稍微低階一點的配備應該會更慢吧。我想現在矽谷公司應該都會給軟體工程師最高配備的筆電，工程師每天開發的速度加快一點，累積下來省下的時間，比筆電省幾百塊美金對公司更有效益。

除了 Mac 外，我也得到 2 台 27 吋 Asus 的螢幕，一個 Mac Docking Station 讓我的 mac 可以快速連上所有外接裝備，以及我自己在 Amazon 挑的鍵盤滑鼠。我的桌子不是自動的 standing desk，但是也是 standing desk 的高度，配上我選的舒適電腦椅。我估計這些林林總總的東西加起來，onboard 一個工程師大概要 4~5 千美金吧，矽谷公司給軟體工程師的預算及照顧是很不錯的。

## 兩週一個 sprint 的工作節奏

我們的工作流程和大部分矽谷公司差不多是 Agile software development，每 2 周是一個 sprint，週三會有 sprint planning 規劃接下來兩週的任務，下下週的週二有 demo time 讓每個人展現自己的工作成果給全 team 組員，選週三開始及週二結束是因為週一開始週五結束常常會有人放假會錯過，周間開始及結束比較不會有組員人數出席不足問題。

每天早上 10 點有 stand up meeting，meeting 一開始會有個暖身遊戲，我常被笑整天一直玩一直玩... 暖身完 meeting 主要要向大家報告我昨天做了什麼，今天預計要做什麼，有什麼 block 阻礙我今天的開發工作。meeting 報告完大家就回到位子開始工作了。

## 每天用到的工具

而基本上我們每天用到的工具有：

- **Bitbucket**：程式碼管理平台，我們 project 的 source code、commit 及 pull request 都在這裡交流。其他公司可能會用的對應平台是 [Github](https://github.com/)。
- **JIRA**：sprint 中各個 tasks 都在這裡，提供每個人追蹤工作進度的地方。如果你們是用 Github 的話，可以使用 waffle.io 來追蹤進度。
- **Slack**：團隊溝通平台，藉由各種主題的 channel 讓相關人員溝通交流，大幅度減少 email 的使用。
- **Zoom**：video meeting 工具，各個會議室也有 id 可以很方便的從遠端連上加入會議。每天早上的 stand up meeting 如果遠端工作的人員就加入 zoom meeting 參加。

## 每兩週和老闆的 30 分鐘

每兩週我的直屬老闆會和我有 30 分鐘的 meeting，主要是看看我過得如何，有沒有什麼建議或不滿，或是工作內容希望做什麼調整，短中期的規劃等等... 這個部分讓我覺得 SolarCity 蠻注重員工心理狀態的，我的幾個建議後來也有被採用，讓我有得到重視的感覺。

## 換我坐到面試桌的另一邊

從上個月開始，我也開始幫忙面試候選人，當面試官面試人是個有趣的體驗，在桌子另一側問問題總是可以看到許多之前我是候選人看不到的點。當我們 team 面試完候選人後，我們會開會討論候選人的表現，主要是看 3 個部分：communication, culture, and technical skills。我們希望找到至少有一部分超好讓我們有深刻印象，其他部分也是中上等級。目前為止我參與的面試都還沒有人被發 offer（其中有的候選人還有 UC CS 學位）。我之前以為矽谷公司都很缺人，很常發出 offer 搶人，但我的 team 認為如果候選人沒有到達標準的話，也寧缺勿濫，就算要面試半年才找到人也沒關係，讓我了解到實力還是得到工作最重要的關鍵。

## 一天的工作節奏

我每天的工作時間大概是 9 點到 6 點，因為我們 standup meeting 是 10 點，所以很多組員快 10 點才出現，其實沒有人會管我們幾點到公司、在公司工作多久等等。畢竟 coding 在家也是可以做，我的直屬老闆因為在公司太多人要找他了，所以他不時會在家或是躲到某一間會議室專心工作。

我們每個人大部分時間就是面對電腦螢幕的開發工作，完成一個 task 就提交 pull request 給組員 review。Pull request 被批准後就可以 merge 到 dev branch 等下一個 release 時 merge 到 master branch。而 merge 完的 task 就會給 QA 測試，我們有時候也會幫同組的組員在相對沒有那麼 customer facing 的 task 做測試。

## SolarCity 的小福利

最後提一下 SolarCity 幾個有趣的小部分，我們會議室的所有桌子都是太陽能板當桌面，讓大家即使沒有自己裝太陽能板，也可以天天看得到、摸得到。我們沒有免費的午餐，但是有免費的早餐 cereal、各種零食、碳酸飲料、咖啡及茶，水果一週有 2~3 天會提供，最近大家都有點吃膩零食了，希望公司會常常換種類。每週有免費 meditation 及健身 bootcamp 可以參加。整體來說 SolarCity 員工平均年齡還算蠻低的，男女比例也差不多是 1：1（軟體部門比例就差蠻多的），上班氣氛很歡樂，常常有 happy hour，team outing 及 holiday 活動，大家認真上班之餘也是會放鬆娛樂的。

## You are supposed to struggle

我之前常常聽到一句話可以總結軟體工程師的每天工作情況——"**You are supposed to struggle!**"，大部分時間我們軟體工程師被大大小小的難題困擾著，常常抓破頭皮 google 也找不出問題所在。不過另一方面，這也是軟體工程師有趣的地方，面對各種挑戰及解開的過程、做出最後的成果都像是在創造新的事物。After all, a software engineer is kind of like a magician. :)

---

*本文原發表於舊站「半路出家軟體工程師在矽谷」（2015 年 12 月 30 日）。該站現已下線，全文由 Wayback Machine 備份保存，搬到本站時做了輕度編輯。*
