---
type: slide
slideOptions:
  allottedMinutes: 1
  overview: true
---

# 用臺灣話來貢獻語音資料庫
## Common Voice 語音資料庫
## 華語、台語CC0句庫

- https://github.com/moztw/cc0-sentences/
- https://commonvoice.mozilla.org

Note:

逐家好，咱今仔日欲用短短的時間，來紹介開放語音資料庫 Common Voice，嘛順紲講台語語言資料的現況
我的台語無偌好，但是這擺亦是欲來配合這主題，試看覓用台灣話來佮逐家分享


---

## Irvin Chen

Contributor of Mozilla & MozTW.org, Mozilla Taiwan Community

Note:

自我介紹一下，Mozilla 志工, Firefox 火狐狸hôo-lî的推廣者，摩茲工寮顧門的志工

---

## 摩茲工寮 moztw.space

Free & Open hackerspace

![](https://i.imgur.com/ThLWCe9.png =500x)
![](https://i.imgur.com/5mE8hw9.png =500x)


Note:

免費閣開放的公家所在

歡迎逐家每禮拜五暗時來摩茲工寮，維基百科Uî-ki-pah-kho 佮 Mozilla 社群siā-kûn 做伙團聚thuân-tsū
若是有想要辦什麼活動、講演káng-ián，也可以到我們的的網站來申請


---

- commonvoice.mozilla.org
    - [華語錄音](https://commonvoice.mozilla.org/zh-tw/listen) 
    - [台語錄音](https://commonvoice.mozilla.org/nan-tw/listen)
    - [語音資料庫下載](https://commonvoice.mozilla.org/nan-tw/datasets)
- https://github.com/moztw/cc0-sentences/
    - [華語、台語 CC0 句庫](https://github.com/moztw/cc0-sentences/)
    - [統計 & 清理工具](github.com/irvin/voice-text-tools)

Note:

這個專案四個主要的功能所在
Common Voice 的網站有包含台語錄音、華語錄音、語音資料庫的下載（táng-lóo）

另外用來予人錄音的華語佮台語詞句sû-kù，阮是整理在 Github 頂頭
配合的資料統計與清理的家私

這馬臺灣的語言的部份，已經有臺灣華語佮台語的錄音矣，嘛有相關的文字形式的句庫

---

![screenshot of common voice](https://i.imgur.com/Cb305vy.png)

Note:

這是 Common Voice 的頭頁，上頂懸正手頂仔的所在會當換語言，圖倒爿是收集講話聲音，正爿是驗證逐家貢獻的聲音，共錄音檔播送出來。


---

![languages that available in common voice](https://i.imgur.com/BBqXDei.png =700x)

Note:

Common Voice 這馬有 99 種語言，有較濟人講的語言親像英文法國話，嘛有較少人講的像國際話

---

![screenshot of cc0 corpus github repo](https://i.imgur.com/Sf6Nb4g.png)

Note:

這是 CC0 詞句庫的形體，一條一條的詞句，華語差不多有2萬4千條，台語有一萬九千條

---

![logo of alexa, cortana, siri and ok google](https://i.imgur.com/rzT2FTa.png)

> 人：「Hey Siri, 明仔載會落雨袂？」

> Siri：「我不太清楚你想表達什麼。」

Note:

是按怎我們要來做這個專案跟大家推廣
現代大家手頭的手機仔，無論你是 Andorid 抑 Apple，都會使用聲音來控制，毋過這馬可能你問講「Hey Siri，明仔載落雨袂？」
伊會應講「我聽無矣」

現代科技進步，咱人會當講話來控制機器，查今仔日天氣啥款。進前有蘋果的新聞，講𪜶欲開發的會當聽有臺語的 Siri，若是推出，你會當對恁的蘋果手機仔問天氣啥款
毋過這馬可能你問講「Hey Siri，明仔載落雨袂？」
伊會應講「我聽無矣」

---

![Freeing Speech: (Open Corpus) Taiwnaese Mandarin & Taigi CC0 Corpus > (Open Speech Data) Common Voice > (Open STT/TTS) DeepSpeech / Coqui > Bring Diversity to Speech > Enriching Global Community](https://i.imgur.com/oJ0mH0N.png)

Note:

如果有一天，咱會當用台語來佮手機對話，會使予更多人用習慣的母語來互動，更加便利生活。

Common Voice 整個計畫是想欲促進語言相關的技術，頭起先愛有句庫、連後逐家來錄音，收集唸文句的聲音檔，才會當訓練聽有語音的模型，發展做咱人會當用的語言輸入辨識 piān-sik技術

---

### 市面上的中文語料庫
```
政府（國科會／科技部）多年來補助了非常多錢…
```
- [中央研究院漢語平衡語料庫](http://asbc.iis.sinica.edu.tw/) (1990-)
    - 19,247 篇文章；1,396,133 句數
    - [版權資訊](http://www.teldap.tw/copyright.html)、[授權條件與價格](http://www.aclclp.org.tw/use_asbc_c.php)
- [LIVAC 漢語共時語料庫](http://www.livac.org/index.php?lang=tc) (1995-)
    - 源自香港城市大學，[版權資訊1](http://www.livac.org/intro.php?lang=tc)、[2](http://www.chilin.hk/?page_id=25626)
- [北京大學現代漢語語料庫](http://ccl.pku.edu.cn:8080/ccl_corpus/)
    - 581,794,456 字[*](https://languageresources.github.io/2018/03/07/%E5%B4%94%E6%AC%A3%E7%AD%89_CCL%E8%AF%AD%E6%96%99%E5%BA%93/)
- [台文語音合成語料庫](http://www.aclclp.org.tw/use_mat_c.php#tat)
- 「北科大/交大『民視台語語料庫』」(2020/12)
- [其他各語系語料](https://languageresources.github.io/)

Note:

來看目前的中文語音資料庫的形狀hîng-tsōng
，有中國的，有臺灣中研院tiong-gián-īnn
的平衡語料庫，嘛有香港的。擱有最新的北科交大2020年12月上新聞「民視台語語料庫」

---

### 現有語料庫的共通問題

💼 限非商業使用／🏫 限學術研究用／💰 價格

![](https://i.imgur.com/SziNGcM.png =500x)

（圖片：[中華民國語言計算機學會 「中央研究院漢語平衡語料庫」 申請說明](http://www.aclclp.org.tw/use_asbc_c.php)）

Note:

這是中研院平衡語料庫的申請的說明，限制非商業使用，限制學術研究使用，上重要是有價數kè-siàu

---

#### 限制身份與用途

- 蘋果開發台語 Siri
- 語音合成台灣的虛擬偶像
- Mozilla 製作國語辨識
- Coqui 語音合成模型
- AI Labs 雅婷逐字稿
- 更多 G0v／公民專案
- 非營利組織？社會企業？提供在地服務的商業公司？

📵 皆不適用！

Note:

有使用限制的狀況之下，遮所寫的應用，親像蘋果台語Siri，抑是公民團體的專案，攏無法度用！

---

稅金資助的資料庫，為何限制對國人有益的用途？

> Public Money, Non-Public Data?

Note:

這就予咱想問，為何用政府對民眾收的sè-kim，建立的資料庫，有遮濟限制，甚至國人嘛無法度用

<!-- --- -->

<!-- 
## 發展方向 🗂️

- 建立流程文件
    - 語料處理方法、捐獻資料方法
- 定期舉辦 workshop 招募更多成員
    - 隔週三 working night
- 統計工具
    - 上傳句子時，自動計算字數、句數、涵蓋範圍 (國語 done! 台語 todo!)
 -->

---

## 起源

Mozilla 在 2017 年發起 [Common Voice](https://commonvoice.mozilla.org/zh-TW) 語音資料庫專案，邀請大家一同錄音，建立各語言的語音資料庫，並採 CC0 授權（無任何版權限制）釋出，以促進 <u>語音辨識</u>、<u>語音合成</u> 等相關科技的開發與研究。

Note:

Common Voice 是對 2017 年起頭的，欲相招逐家來參與錄音，建立種種語言的語音資料庫，濟濟的資料用 CC0 授權，白話講就是無任何版權的限制，來促進(tshiok-tsìn) 語言辨識、語言合成等等技術的開發佮研究

---

## 歡迎參與 🤗

Note:

歡迎來加入錄音跟收集 siu-tsi̍p 詞句行列hâng-lia̍t

---

### 錄音

🎙 [錄華語](http://commonvoice.mozilla.org/zh-tw) | [錄台語](http://commonvoice.mozilla.org/nan-tw)

![](https://i.imgur.com/oxwe5zn.png)

*自己錄錄
也揪更多人來錄！*

Note:

逐家來幫贊錄音！相招親情朋友來錄

---

[DEMO 錄音](https://commonvoice.mozilla.org/nan-tw)

Note:

咱來來示範錄音

---

## 目前錄音成果 📈

![華語錄音時數110小時, 驗證63%](https://i.imgur.com/17iqmPP.png =500x) 
![臺語錄音時數10小時, 驗證20%](https://i.imgur.com/p6Dfdmk.png =500x)

Note:

這會當看著這馬錄音的成果，華語總錄音時數 110 點鐘；台語有錄10點鐘，經過檢驗20%

---

華語：<!-- 台灣志工最初搜集了[兩千句繁體中文的句子](https://github.com/mozilla/common-voice/tree/main/server/data/zh-TW)，-->於 2018/7 啟動華語錄音。

台語：<!--又經過四年努力，-->於 [2022/2 開放台語錄音](https://hackmd.io/@moztw/commonvoice8)。

Note:

雖然台語佮華語攏是臺灣日常時咧講的語言，毋過你會當看著台語晚四年才開始的

---

## 為什麼台語花了四年？

想透過錄音建立 CC0（*無任何版權限制*）的語音資料庫，需要準備 CC0（*無任何版權限制*）的句子。

=> 找無現成可用的句子！

Note:

詞句
因為無準備好，無任何版權限制的詞句

---

## 語料庫資料現況 📈

現在有多少句子？句子多完整？

<!-- 

搜集整理無版權限制的繁體中文句子，建立 CC0 授權、不限定任何用途的語料庫，作為正體中文專案的基礎建設
 -->
 
Note:
 
聽到遮，你應該好玄hònn-hiân有偌濟文句？字詞有偌加圇ka-nn̂g

---

### 華語

- 24,244 句
- 3,495 不重複字
    - 涵蓋 83.8% 常用字（教育部 2015 常用字 P99.75，3011/3593）
- 1,040 發音
    - 涵蓋 66.37% 中文發音（根據注音輸入表計算，1,040/1,567 音）

（[統計至 2022/3 資料](https://github.com/moztw/cc0-sentences/commit/c397d2b3a836075e51dc1bfd45aef5c27f17d1e3)）

Note:

這馬臺灣華語有 24,000 詞句，3,495 無仝的字，差不多是捷用字的 83%, 1,040 的發音


---

### 台語

- 約 21,400 詞／句
<!-- （其他統計資料：仍待開發） -->

Note:

台語的部份是 21,400 詞句，其他的統計資料需要有人鬥跤手
來想欲按怎算，參考華語的工具開發出來

---

<!-- ## 建立 CC0（公眾授權）國台語句庫 -->

<!-- 要開放公眾錄音，必須蒐集無版權問題的句子
 -->
### 句庫收錄的原則

- 以台灣當代口語、日常對話為主
- 結構簡單
- 無任何版權、使用限制
<!-- - 易於存取：直接以 TXT 檔形式置於 Github  -->

Note:

句庫的收錄原則是當代的，日常的對話，文句的結構是簡單的，嘛愛無任何版權

---

### 目前詞句來源


- 個人捐贈文章、小說散文作品
- 對話紀錄（g0v #rand0m 頻道為主）
- 政治人物（公務員）講稿 & 政府新聞稿
- 曲名、書名、地名
- iTaigi 愛台語網站

目前資料來源較單一，希望更多口語化的句子
- 亟需**台語日常對話**句子（教材？）

Note:

個人的文章bûn-tsiong、對話記錄、政治人物公務員的講稿káng-kó抑是新聞稿;歌曲名、書名、地號名

歡迎有熟似si̍k-sāi教台語的先生(sian-senn)的人，會當走傱tsáu-tsông問看覓，是毋是會當捐教材予 Common Voice 來用，予 Common Voice 有閣較口語的文句

---

<!-- ### 句庫範例用途

可用於⋯⋯

- 🔈 收集語音的專案： 運用句子錄音
- 🎒 教育應用相關： 識字測驗
- 📚 字典／語言學領域： 作為例句、語言研究分析素材
- 📐 UX 相關專案： 假文產生器素材

> 沒有任何限制，就能產生更多意想不到的用途
-->
<!-- Note:

收來的句庫會當用來語言專案、捌字的測驗、字詞的領域，UX 的，親像假文章產生器

-->

---

### 其他參與方向

- 文本處理（對話紀錄、新聞稿）
    - 截斷過長複合句
    - 去除可識別化資訊<!--- 一小時可以整理數百至數千句-->
- 語言學、資料統計
    - 開發統計與分析工具 (node.js scripts)
    - 有多好、多重複、多完整、缺什麼字詞
- 人工智慧
    - 下載語音資料庫用用看
- 宣傳協力、洽談合作

Note:

整個 Common Voice 計畫需要有人做資料處理，語言學gí-giân-ha̍k、統計資料，人造智慧jîn-tsō-tì-huì
。接接機關佮老師嘛真重要

---

## 更多語言 📓

- 收集客語 & 原住民語語料
    - 你會講會寫嗎？
    - 「沒有人」有能力幫忙，等你動手！
<!-- - 與現有學術單位的合作
    - 開放中研院資料集 -->
- 協助聯絡
    - 台語客語老師、語言教材作者 

Note:

嘛是有可能開別个臺灣語言的站，親像 Hakka fa，原住民guân-tsū-bîn族的濟濟語言。協助聯絡華語、台語老師敢會當捐教材資料

---

<!--## 這邊參加-->

![](https://i.imgur.com/Z5qDiUx.png)

- G0v Slack: [join.g0v.tw](https://join.g0v.tw) #rand0m
- Telegram: [t.me / moztwCV](https://t.me/moztwCV)
- Line: [cvline.moztw.space](https://cvline.moztw.space)

[![hackmd-github-sync-badge](https://hackmd.io/gJM-G1JQTpm1cWLzi3ox7g/badge)](https://hackmd.io/gJM-G1JQTpm1cWLzi3ox7g)

Note:

咱演講到遮，這是咱 Common Voice 臺灣的聯絡管道，有 Line 佮 Telegram 群組，歡迎加入，毋知影有啥物問題無

<!--

# 專案目標、受眾與獨特性：

為了解決任何繁體中文相關的專案遇到的「沒有無版權限制的繁體中文語句文本資料庫」的困難，我的專案提供「大量無版權問題的繁體中文句子」，可以做到「不受任何限制的運用」。

我的專案跟「現有的任何繁體文本資料庫」，在「版權限制」（市面上的文本資料庫均使用「非商業性」或「限學術使用」授權）上不同，因此具有不可取代性。

-->
<!-- 

- 主要貢獻者
    - [MozTW](https://moztw.org) 社群 [Common Voice 專案貢獻者](https://t.me/moztwcv)
    - [G0v Slack](https://join.g0v.tw/) #rand0m 成員

 -->
 ###### tags: `Common Voice`,`CC0-Corpus`
