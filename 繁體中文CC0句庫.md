---
slideOptions:
  allottedMinutes: 8
---
# 國台語 CC0 句庫 & 錄音資料庫

## Traditional Chinese (Mandarin) & Taiwanese (Minnan) CC0 corpus and voice database

- 國語錄音： https://commonvoice.mozilla.org/zh-tw/listen
- 台語錄音： https://commonvoice.mozilla.org/nan-tw/listen
- 語音資料庫下載： https://commonvoice.mozilla.org/nan-tw/datasets
- 國台語句庫： [github.com/moztw/cc0-sentences](https://github.com/moztw/cc0-sentences/)
- 統計／清理工具： [github.com/irvin/voice-text-tools](https://github.com/irvin/voice-text-tools)

---

![](https://sch001.g0v.tw/dash/org/g0v-jothon/prj/3UfZN402G205ov0CO104l+vAs/upload/5e71dd7bba039e59d38205965b1f6b7c.png)

###### tags: `Common Voice`,`CC0-Corpus`

---

搜集整理無版權限制的繁體中文句子，建立 CC0 授權、不限定任何用途的語料庫，作為正體中文專案的基礎建設

---

- 提案者
    - Irvin @moztw.org

- 主要貢獻者
    - [MozTW](https://moztw.org) 社群 [Common Voice 專案貢獻者](https://t.me/moztwcv)
    - [G0v Slack](https://join.g0v.tw/) #rand0m 成員

---

## 緣起 🎤

Mozilla 在 2018 年發起 [Common Voice](https://commonvoice.mozilla.org/zh-TW) 錄音專案，希望能收集世界各種語言的聲音，建立 CC0 授權（無任何版權限制）的語音資料庫（Speech Corpus），提供<u>語音辨識</u>、<u>語音合成</u>等 AI 及聲音相關技術的開發與研究

---

想要邀請公眾錄音來收集 CC0（*無任何版權限制*）的聲音，需要準備 CC0（*無任何版權限制*）的句子。因此我們[從 2018/6 開始](https://github.com/mozilla/common-voice/tree/main/server/data/zh-TW)，搜集了兩千句繁體中文的句子，並啟動該專案的中文錄音。

經過社群成員協力蒐集一組基本的語句資料，台語在 [2022/2 開始開放錄音](https://hackmd.io/@moztw/commonvoice8)。

----

- 國語錄音： https://commonvoice.mozilla.org/zh-tw/listen
- 台語錄音： https://commonvoice.mozilla.org/nan-tw/listen

![Common Voice 網頁抓圖](https://i.imgur.com/GXnZcPd.jpg)


----

https://commonvoice.mozilla.org/datasets

國語錄音進度
![國語錄音時數105小時、驗證時數66小時](https://i.imgur.com/fBm7YZp.png)

台語錄音進度
![台語錄音時數5小時、驗證時數1小時](https://i.imgur.com/o4NQw8w.png)

(2022/4/9)


---

## 市面上的現有中文語料庫

- [中央研究院漢語平衡語料庫](http://asbc.iis.sinica.edu.tw/) (1990-)
    - 19,247 篇文章；1,396,133 句數
    - [版權資訊](http://www.teldap.tw/copyright.html)、[授權條件與價格](http://www.aclclp.org.tw/use_asbc_c.php)
- [LIVAC 漢語共時語料庫](http://www.livac.org/index.php?lang=tc) (1995-)
    - 源自香港城市大學，[版權資訊1](http://www.livac.org/intro.php?lang=tc)、[2](http://www.chilin.hk/?page_id=25626)
- [北京大學現代漢語語料庫](http://ccl.pku.edu.cn:8080/ccl_corpus/)
    - 581,794,456 字[*](https://languageresources.github.io/2018/03/07/%E5%B4%94%E6%AC%A3%E7%AD%89_CCL%E8%AF%AD%E6%96%99%E5%BA%93/)
- [台文語音合成語料庫](http://www.aclclp.org.tw/use_mat_c.php#tat)
    - ...確實僅用於學術、教育及公益研究，*不作營利及商業用途*。
- [其他各語系語料](https://languageresources.github.io/)

---

### 現有語料庫的問題

💼 限非商業使用／🏫 限學術研究用／💰 價格

![](https://i.imgur.com/SziNGcM.png =500x)

（圖片來源：[中華民國語言計算機學會 「中央研究院漢語平衡語料庫」 申請說明](http://www.aclclp.org.tw/use_asbc_c.php)）

---

#### 用途限制

- 建立台灣口語語音辨識模型？
- 語音合成台灣的虛擬偶像？
- DeepSpeech 語音轉文字
- AI Labs 雅婷逐字稿 服務
- G0v／公民專案
    - 識字專案、假文專案…

#### 身份限制

- 非營利組織？社會企業？
- 提供台灣在地服務的商業公司？

## 📵 以上用途皆不適用！

---

稅金資助建立的資料庫，為何要限制國人的使用？

> Public Money, Non-Public Data?

---

## 建立 CC0（公眾授權）國台語句庫 ＆ 語音庫

要開放公眾錄音，必須先蒐集一批無版權問題的句子

![](https://i.imgur.com/kr494Sd.png)

---

## 句庫收錄的原則

- 以台灣當代口語為主，結構簡單的句子
- 無任何版權、使用限制
- 易於存取：直接以 TXT 檔形式置於 Github 

---

## 資料來源

- 社群捐贈文章、小說散文作品
- 對話紀錄（g0v #rand0m 頻道為主）
- 政治人物（公務人員）講稿 & 政府新聞稿
- 曲名、書名、鄉鎮縣市地理資訊
- 國台語老師捐贈日常對話的教材
- …還有許多可能性

---

## 句庫資料現況 📈

### 國語
- 24,244 句
- 3,495 不重複字
    - 涵蓋 *83.8%* 常用字（教育部 2015 常用字 P99.75，3011/3593）
- 1,040 發音
    - 涵蓋 *66.37%* 中文發音（根據注音輸入表計算，1,040/1,567 音）


（[統計至 2022/3/9 資料](https://github.com/moztw/cc0-sentences/commit/c397d2b3a836075e51dc1bfd45aef5c27f17d1e3)）

### 台語
- 20,279 句
- （其他統計資料：待你來協助建制）


---

## 句庫範例用途

可用於⋯⋯

- 🔈 收集語音的專案： 運用句子錄音
- 🎒 教育應用相關： 識字測驗
- 📚 字典 / 語言學領域： 作為例句、語言研究分析素材
- 📐 UX 相關專案： 假文產生器素材

不限定任何用途，許許多多意想不到的應用方式

---

## 目前挑戰

- 📒 語料來源
    - 非主要問題（[sayit.pdis](https://sayit.pdis.nat.gov.tw/)、政府訪談稿、#rand0m 頻道⋯⋯）
    - 資料來源類型侷限，需要更多口語對話紀錄（eg., Line 紀錄）

- 🧑‍💻 參與人力
    - 斷句，截斷過長複合句
    - 去除可識別化資訊
    <!--- 一小時可以整理數百至數千句-->

---

## 發展方向 🗂️

- 建立流程文件
    - 語料處理方法、捐獻資料方法
- 定期舉辦 workshop 招募更多成員
    - 隔週三 working night
- 統計工具
    - 上傳句子時，自動計算字數、句數、涵蓋範圍 (國語 done! 台語 todo!)

---

## 進一步發展 📤

- 收集客語 & 原住民語語料
    - 你會講會寫嗎？
    - 「沒有人」可以幫忙，就等你動手！
- 與現有學術單位的合作
    - 開放中研院資料集

---

## 歡迎參與 🤗

- 資料處理
    - 整理來源文本，放入句庫
- 程式
    - node.js script： 統計與分析工具
- 語言學
    - 有多好、多重複、多完整、缺什麼字詞
    - 用用看
- 錄因
    - [聽/錄台語](http://commonvoice.mozilla.org/nan-tw)
    - [聽/錄國語](http://commonvoice.mozilla.org/zh-tw)
- 行銷
    - 協調宣傳
    - 新聞稿
    - 合作事宜

---

## 這邊參加

- G0v Slack: [join.g0v.tw](https://join.g0v.tw) #rand0m
- Telegram: [t.me / moztwCV](https://t.me/moztwCV)

[![hackmd-github-sync-badge](https://hackmd.io/gJM-G1JQTpm1cWLzi3ox7g/badge)](https://hackmd.io/gJM-G1JQTpm1cWLzi3ox7g)

<!--

# 專案目標、受眾與獨特性：

為了解決任何繁體中文相關的專案遇到的「沒有無版權限制的繁體中文語句文本資料庫」的困難，我的專案提供「大量無版權問題的繁體中文句子」，可以做到「不受任何限制的運用」。

我的專案跟「現有的任何繁體文本資料庫」，在「版權限制」（市面上的文本資料庫均使用「非商業性」或「限學術使用」授權）上不同，因此具有不可取代性。

-->