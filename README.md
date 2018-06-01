Hana's personal CV
==================

Introduction
------------

您好，感謝您撥冗檢閱我的個人履歷。

如果我能符合您的期望，請發郵件、Hangout、或是透過社群平台傳訊息給我（聯絡方式在頁尾）；如果願意的話，再遞給您其他聯絡方式。

About Me
--------

#### Beginning

真實姓名為<b>吳聖謙</b>，男，現年 21 歲，居於<b>台灣新北市板橋區</b>，免役，是即將踏入社會的新鮮人。

從國中開始對電腦軟體技術萌生興趣，中學畢業順利考上<b>大安高工資訊科</b>，之後便一頭栽了進去，對科技和軟體產生狂熱般的興趣。

除了導師引領進門，更多的時間花在自主學習，因為它對我而言充滿了好奇與驚艷，而不只是糊口的技能。

#### Continue?

……令人遺憾的是，我沒有如預期般考上理想的大學。我錄取了位在台灣中部的<b>勤益科技大學資訊工程系</b>。

這所科技大學令人失望，課程內容與教材沒有追上時代腳步就算了，教授教學品質參差不齊、課堂學習風氣差、同儕好玩不好學等成了主因，勸我主動離開這裡。

最終我主動申請退學，結束了長達兩年半與同學和教授相處的時光。學業結束後，趁著比同儕多出將近十一個月自由之身，返家填補自己挖的坑，學我想學，為自己創造價值。

#### Now

今年年初，處理完兵役問題後，我處在「得要找工作」和「我還想學」懸念之間；隨著畢業潮即將到來，我決定遞出自己的履歷，踏出成為社會人的第一步。

Personality
-----------

個性稍微內向、有些怕生；不太擅長專業領域外的話題，但喜歡交朋友，認識前後的我完全不是同一人。

喜歡與人來往，雖然不太擅長，但更討厭獨處；比起面對面，螢幕與鍵盤更能闡述我的心情；喜歡顔文字。

好奇心旺盛，學習能力強；充足的基礎令我能快速掌握新工具（語言）。

喜歡新科技，開始接觸新的技術能總是令我睡不著覺。

Work Experience
---------------

尚無工作經驗，熱烈求職中 :fire:

Recent Activity
---------------

主要開發環境已從 Vim 8 轉為 NeoVim 2.2。[Wiki](https://github.com/shirohana/environment/wiki/NeoVim)

目前正在（剛開始）替家裡開的安親美語班重構收費系統。其主要功能為：

- 開立收費三聯單；透過串接 CLI Application 將 DOM 轉換成 pdf 利於列印
- 學生與教師管理、項目與課程管理，並依照學生所數年級、班別等建立關聯性自動完成表單
- 自訂學生收費單樣板
- 項目預置內容 (template string)；例 `%m 月份教材費` -> `6 月份教材費`、`%+1M～%+2M月代訂餐費` -> `七～八月代訂餐費`等
- 班主任、教師、工讀生權限組
- 圓餅圖、柱狀圖、項目利潤、收支月結報表

此次重構環境將由 PHP + MySQL 轉為 Node.js + MongoDB，基本上是砍掉重練……這樣算是重構嗎？

<!-- 正以 [Flow](https://flow.org) 重構既有專案。 -->

<!-- 接下來準備轉戰 Jest (from AVA)、Circle CI (from Travis CI) 和深入 Docker。 -->

Achievement
-----------

[![Codewars badge][codewars-badge]][codewars]

最近在玩 C++ 拿 Codewars 練手，所以解題紀錄都是初級 C++；論解題難度和數量最高的是 CoffeeScript。

[codewars-badge]: https://www.codewars.com/users/Shirohana/badges/micro
[codewars]: https://www.codewars.com/users/Shirohana

Skills
------

#### Languages

> JavaScript
>
> - 熟練使用語言特性 (Prototype Chain, Method Chaining, ESNext Proposals, etc.)
> - 熟悉 Node.js 和 Browser API (DOM)
> - 熟悉 JavaScript Design Pattern 和 MVC Architectures
> - 熟悉 Vue.js and related modules (`vuex`, `vue-router`, Nuxt.js, etc.)
> - 熟悉 JavaScript Unit-Test Frameworks like [AVA](https://github.com/avajs/ava)
> - Training [Flow](https://flow.org)
> - 曾分別使用 Coffee Script 和 TypeScript 一段時間；現以 ES7 + Babel 為主
> - 熟悉 Webpack 和 Gulp
> - 熟悉 NPM modules 管理 (Semantic Versioning)
> - 熟悉 OOP 以及 `this`
> - 熟悉 FP；FP + pipeline operator = :fire:
> - 該踩的地雷大致上都踩過了
> - Contributor of [Nuxt.js](https://github.com/nuxt/nuxt.js)

> CSS3
>
> - 熟悉 CSS 絕大部分屬性
> - 小至按鈕樣式大至切版皆能獨立完成
> - 了解好的 Stylesheets 該如何維護
> - 熟悉 UI 設計準則；善於創造 user-friendly UI，致力提升 UX
> - 了解 Material Design
> - 精通 Stylus (Sass, Scss 無礙）
> - 熟悉 RWD
> - 熟悉 CSS 架構模式 (OOCSS, SMACSS, BEMCSS)；Stylus + BEM = :fire:
> - Contributor of [Bulma.css](https://github.com/jgthms/bulma)

> HTML5
>
> - 熟悉 HTML5 語意化標籤
> - 精通 Jade (Pug)

#### Data Querying Language

> NoSQL
>
> - 熟悉 MongoDB；但無海量資料處理經驗
> - 了解如何寫出有效率的 Aggregation
> - 了解 Embedded Document 策略以及設計資料結構
> - 了解 Sharding 和 Replication 運作原理，但無異地使用經驗
> - 熟悉 Mongoose

> SQL
>
> - 熟悉 PostgreSQL (MySQL) 和 SQLite
> - 熟悉 RDBMS
> - 熟悉多級正規化以及聯合查詢
> - 熟悉 SQL Shell 及 Eloquent ORM

#### Common

> Git
>
> - 熟練使用 Git (CLI the `porcelain` part)
> - 熟悉分支策略、多源 (remote) 管理
> - 熟悉 Git Flow 和 GitHub Flow
> - 有許多 Contribution (Issues/PRs on GitHub) 經驗
> - 具 [Monorepo](https://github.com/babel/babel/blob/master/doc/design/monorepo.md) 實戰經驗
> - 曾翻譯 [Keep a Changelog](https://keepachangelog.com/zh-TW/1.0.0/) ([olivierlacan/keep-a-changelog#202](olivierlacan/keep-a-changelog/pull/202))

> Regular Experience
>
> - 精通
> - 了解如何寫出有效率的正規表示式，知曉不同語言使用上的限制

> Miscs
>
> - 熟悉 Linux 常用指令和參數 (Mac && ArchLinux user)
> - 熟悉 CLI 介面 (Oh-My-Zsh user)
> - 熟悉 SSH/Tmux 等遠端工具
> - Vimer、Junior VimScripter ([my VIM wiki](https://github.com/shirohana/environment/wiki/NeoVim))
> - 熟悉自動化腳本與工具 (Makefile, Gulp)
> - 熟悉 CI Tools (`Travis CI`)
> - 熟悉 Code Coverage Tools (`istanbul` with `codecov`)
> - 具 Nginx 配置經驗 (Multi Virtual Host、Multi Sub-domain Configuration, Reverse Proxy, etc.)，能配置 [SSL Labs](https://www.ssllabs.com) 評價 A+ 之伺服器
> - 具 [Let's Encrypt](https://letsencrypt.org) 配置經驗，能在多個 Subdomain auto renew
> - 熟悉設計 RESTful API
> - 熟悉 Software Design Patterns

Projects
--------

#### 個人網站

> [https://www.shirohana.me](https://www.shirohana.me)
>
> 伺服器以 Node.js 開發，並透過 Nginx 做 Reverse Proxy 架在防火牆內。
>
> 目前暫時性停止更新與維護，[Recent Activity](#recent-activity) section 寫著是什麼插了隊。
>
> 前後端技術包含：
> - SPA + SSR
> - Vue series: vue, vuex, vue-router, nuxt, ...
> - Several preprocessors: Pug, Stylus, Babel(ESNext)
> - Complete RWD (until 4K)
> - Full site over SSL (difference certificate per sub-domain)
> - Google Analytics
> - Google reCAPTCHA
> - Connect to local mongoDB (in container) with Mongoose
> - ...

#### Dynapi (重構中)

> [https://github.com/shirohana/dynapi](https://github.com/shirohana/dynapi)
>
> 所見即所得 Node.js API 開發利器，根據檔案結構動態生成路由，透過 `Middleware`、`Parameter`、以及 `ErrorCatcher`
> 建立清晰的事件流，輕易打造出易於維護的後台。ESNext 完整支援。

#### Bulma.stylus

> [https://github.com/shirohana/bulma.stylus](https://github.com/shirohana/bulma.stylus)
>
> 以 [Stylus](http://stylus-lang.com) 完整重構 [Bulma.css](https://bulma.io)

#### Simple Notepad Example

> [\[Demo\]](https://shirohana.github.io/simple-notepad-example/)
> [https://github.com/shirohana/simple-notepad-example](https://github.com/shirohana/simple-notepad-example)
>
> 去年寫給朋友的朋友的簡易筆記本範例。

#### Alfred3 Youtube Control

> [https://github.com/shirohana/alfred3-youtube-control](https://github.com/shirohana/alfred3-youtube-control)
>
> 以 AppleScript 開發的 Alfred workflow

#### CodePens

- Draw an `osu!` logo in CSS: [https://codepen.io/shirohana/pen/pLBRyj](https://codepen.io/shirohana/pen/pLBRyj)

Contributions
-------------

#### Keep a Changelog

> [https://keepachangelog.com/zh-TW/1.0.0](https://keepachangelog.com/zh-TW/1.0.0/)
>
> 翻譯為繁體中文。[PR](https://github.com/olivierlacan/keep-a-changelog/pull/202)

#### Nuxt.js

> [https://github.com/nuxt/nuxt.js](https://github.com/nuxt/nuxt.js)
>
> 從數百 stars 看著它長成 12k star 的熱門專案，儘管貢獻微乎其微，但仍持續關注著。

#### See more on Hana's GitHub...

Contact
-------

Email Address: [shirohana0608@gmail.com](mailto:shirohana0608@gmail.com)

Facebook: [https://www.facebook.com/shiro.hana.0608](https://www.facebook.com/shiro.hana.0608)

Discord: `Hana Shiro#2858`

Website (延遲開發): [https://www.shirohana.me](https://www.shirohana.me)

