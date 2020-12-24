---
slideOptions:
  allottedMinutes: 8
---
# 繁體中文 CC0 句庫 
## Trad. Chinese CC0 Corpus

- 句庫： [github.com/irvin/cc0-sentences](https://github.com/irvin/cc0-sentences/)
- 統計／清理工具： [github.com/irvin/voice-text-tools](https://github.com/irvin/voice-text-tools)

---

![](https://sch001.g0v.tw/dash/org/g0v-jothon/prj/3UfZN402G205ov0CO104l+vAs/upload/5e71dd7bba039e59d38205965b1f6b7c.png)

###### tags: `CommonVoice`,`CC0-Corpus`

---

搜集整理無版權限制的繁體中文句子，建立 CC0 授權、不限定任何用途的語料庫，作為正體中文專案的基礎建設

---

- 提案者
    - Irvin @moztw.org

- 主要貢獻者
    - [MozTW](https://moztw.org) 社群 Common Voice 專案貢獻者
    - [G0v Slack](https://join.g0v.tw/) #rand0m 成員

---

## 緣起 🎤

Mozilla 在 2018 年發起 [Common Voice](https://commonvoice.mozilla.org/zh-TW) 錄音專案，計畫收集各語言的聲音，建立 CC0 語音資料庫（Speech Corpus），提供<u>語音辨識</u>、<u>語音合成</u>等 AI 及聲音相關應用

---

想要透過<u>錄音</u>來收集 CC0（*無任何版權限制*）的聲音，需要 CC0（*無任何版權限制*）的句子。

因此我們[從 2018/6 開始](https://github.com/mozilla/common-voice/tree/main/server/data/zh-TW)，搜集了兩千句中文句子，以啟動該專案的中文錄音。

此一份資料衍生成本專案

----

https://commonvoice.mozilla.org/

![Common Voice 網頁抓圖](https://i.imgur.com/pQklPwM.png)

----

https://commonvoice.mozilla.org/zh-TW/datasets

![Common Voice 繁體中文資料量現況](https://i.imgur.com/OipVeDC.png)

---

## 現有中文語料庫

- [中央研究院漢語平衡語料庫](http://asbc.iis.sinica.edu.tw/) (1990-)
    - 19,247 篇文章；1,396,133 句數
    - [版權資訊](http://www.teldap.tw/copyright.html)、[授權條件與價格](http://www.aclclp.org.tw/use_asbc_c.php)
- [LIVAC 漢語共時語料庫](http://www.livac.org/index.php?lang=tc) (1995-)
    - 源自香港城市大學，[版權資訊1](http://www.livac.org/intro.php?lang=tc)、[2](http://www.chilin.hk/?page_id=25626)
- [北京大學現代漢語語料庫](http://ccl.pku.edu.cn:8080/ccl_corpus/)
    - 581,794,456 字[*](https://languageresources.github.io/2018/03/07/%E5%B4%94%E6%AC%A3%E7%AD%89_CCL%E8%AF%AD%E6%96%99%E5%BA%93/)
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

#### 身份限制

- 非營利組織？社會企業？
- 提供台灣在地服務的商業公司？

---

## 📵 以下用途皆不合法？

- Mozilla DeepSpeech 語音轉文字
- AI Labs 雅婷逐字稿 服務
<!-- - G0v／公民專案
    - 識字專案
    - 假文專案 -->

---

稅金資助建立的資料庫，為何要限制國人的使用？

> Public Money, Non-Public Data?

---

## 建立繁體中文 CC0 句庫

![](https://i.imgur.com/kr494Sd.png)

---

## 屬性

- 以台灣當代口語為主，結構簡單的句子
- 無任何版權、使用限制
- 易於存取：直接以 TXT 檔形式置於 Github 

---

## 資料來源

- 社群捐贈文章、小說作品
- 對話紀錄（g0v #rand0m 為主）
- 政治人物講稿
- 政府新聞稿

---

## 資料現況 📈

- 11,917 句／112,721 字
- 不重複用字：3,137 字

（[統計](https://github.com/irvin/cc0-sentences/blob/master/README.md#phonetic-coverage)至 [2020/12/3 資料](https://github.com/irvin/cc0-sentences/commit/0ce78f4616198663c2556014ff35ecb1ea2b3dd7)）

---

### 涵蓋範圍 📈

- 字數
    - 涵蓋 ~~72.4%~~ **78.2%** 常用字
教育部 2015 常用字 P99.75，2811/3593
- 發音
    - 涵蓋 ~~63.7%~~ **64.6%** 中文發音
根據注音符號表，1,012/1,567 音

---

## 用途

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

## 開發方向 🗂️

- 建立流程文件
    - 語料處理方法、捐獻資料方法
- 定期舉辦 workshop 招募更多成員
    - 隔週三 workday、隔四週週六 workshop
- 統計工具
    - 上傳句子時，自動計算字數、句數、涵蓋範圍

---

## 進一步發展 📤

- 收集台語 & 原住民語語料
    - iTaigi、萌典資源
- 建立可自行上傳、捐獻語料的機制
    - eg., 捐出你的 Line 對話
- 建立可直接取用句子的 API
    - 取得 X 個隨機句子、包含 Y 字的句子
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
- 行銷
    - 協調宣傳、合作事宜

---

## Join

- G0v Slack: [join.g0v.tw](https://join.g0v.tw) #rand0m
- Telegram: [t.me / moztwCV](https://t.me/moztwCV)

<!--

# 專案目標、受眾與獨特性：

為了解決任何繁體中文相關的專案遇到的「沒有無版權限制的繁體中文語句文本資料庫」的困難，我的專案提供「大量無版權問題的繁體中文句子」，可以做到「不受任何限制的運用」。

我的專案跟「現有的任何繁體文本資料庫」，在「版權限制」（市面上的文本資料庫均使用「非商業性」或「限學術使用」授權）上不同，因此具有不可取代性。

-->