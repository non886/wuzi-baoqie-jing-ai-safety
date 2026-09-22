# 己所不欲，勿勸他人：《無字寶篋經》的菩薩戒總持原則與 AI 安全
# "What You Yourself Do Not Desire, Do Not Urge Upon Others": The Bodhisattvas' Master Principle of Śīla in the *Wuzi Baoqie Jing* and Its Bearing on AI Safety

> 分析《佛說無字寶篋經》（T17, no. 828，梵文 *Āryānakṣarakaraṇḍakavairocanagarbha-nāma-mahāyānasūtra*，藏譯 Toh 259）「己所不欲，勿勸他人」一段，探討其作為 AI 安全（AI alignment）價值層參考的可能性與局限[cite: 3]。
>
> An analysis of the "one dharma" passage in the *Fo shuo Wuzi Baoqie Jing* 佛說無字寶篋經 (T17 no. 828 / Toh 259) and its implications, possibilities, and limitations for AI safety and alignment[cite: 3].

---

## Contents / 目錄

- [完整分析（中文正文）](essay.md) — Full Analysis (Chinese)[cite: 3]
- [Full Analysis (English)](essay-en.md) — 英文版完整分析[cite: 3]
- [授權條款 / License](LICENSE.md)[cite: 3]

---

## Abstract / 摘要

### 中文摘要
佛陀在《無字寶篋經》中不列具體戒條，而是給出菩薩「日夜防護」的一條總持原則：「己所不欲，勿勸他人」，並從「自愛推及他愛」與「眾生皆為樂求」兩層推導證成，宣稱持此一法即護持如來一切戒藏[cite: 3]。本文結合 DILA 經錄與 84000（Toh 259）最新文獻考據（包含大英圖書館藏 Or.15010 梵文殘片資訊），提出以下論證：

1. **機制導向**：此原則是黃金法則式的互惠倫理，其價值在於生成規範的機制，而非靜態規範清單[cite: 3]；
2. **三層對應**：平行經文《大乘遍照光明藏無字法門經》（T829）將其擴展為對應「十善業道」的十項，涵蓋身、口、意三層——結構上類似一張行為、語言、動機三層的 AI 風險清單[cite: 3]；
3. **對 AI 安全的啟示**：以可推廣的深層原則取代無窮的列舉式禁令（對應 Value Learning 與 Constitutional AI 憲法 AI 思路）[cite: 3]；
4. **局限性**：AI 無「己」故原則必須轉譯為「人類所不欲承受者，勿使施加於人」；偏好歧異需鎖定共通底線；能力規模與治理問題非倫理原則所能涵蓋[cite: 3]。

### English Abstract
In the *Fo shuo Wuzi Baoqie Jing* (T17 no. 828; Toh 259; Sanskrit: *Āryānakṣarakaraṇḍakavairocanagarbha-nāma-mahāyānasūtra*), the Buddha delivers a single master principle guarded day and night by bodhisattvas: *"what you yourself do not desire, do not urge upon others."*[cite: 2, 3] Incorporating philological research from DILA and 84000 (including surviving Sanskrit fragments in British Library Or.15010), this essay examines its application to contemporary AI safety[cite: 3]:

1. **Mechanism over list**: Its primary value lies in being an inner mechanism that generates norms rather than a static list of prohibitions[cite: 3].
2. **Three-layer structure**: The parallel text (T829) maps the principle onto the ten wholesome actions across physical, verbal, and mental domains, functioning as a three-layer AI risk map[cite: 3].
3. **Implications for AI alignment**: It suggests moving from endless enumerative blocklists toward generalizable deep value learning and Constitutional AI (CAI)[cite: 3].
4. **Limitations**: Since AI lacks a "self", it must be translated into "what humans do not wish to endure, do not cause AI systems to impose upon them."[cite: 3] Systemic capability scaling and governance fall outside the scope of a single ethical principle[cite: 3].

---

## Textual & Philological References / 經文與文獻考證

* **Sanskrit Title / 梵文題名**: *Āryānakṣarakaraṇḍakavairocanagarbha-nāma-mahāyānasūtra* (*Anakṣarakaraṇḍakavairocanagarbha*)
* **Tibetan Translation / 藏譯本**: Toh 259 (Kangyur / 甘珠爾): `འཕགས་པ་ཡི་གེ་མེད་པའི་ཟ་མ་ཏོག་རྣམ་པར་སྣང་མཛད་ཀྱི་སྙིང་པོ་ཞེས་བྱ་བ་ཐེག་པ་ཆེན་པོའི་མདོ།`
* **Sanskrit Manuscript Status / 梵文寫本現況**: No complete Sanskrit text survives. A Sanskrit manuscript fragment corresponding to Toh 259 (folios 263b.2–264a.3) is preserved in the British Library (Stein collection, Or.15010). / 目前尚無完整梵文寫本，但在大英圖書館藏斯坦因梵文寫本（Or.15010，原混編於《金剛經》寫本中）發現一葉零碎殘片，精確對應本經末段。

---

## Keywords / 關鍵字

AI safety / AI alignment / Value Learning / Constitutional AI / Golden Rule / Wuzi Baoqie Jing / Ten Wholesome Actions / Buddhist Ethics / Toh 259 / Or.15010
AI 安全 / AI 對齊 / 價值對齊 / 憲法 AI / 黃金法則 / 無字寶篋經 / 十善業 / 佛教倫理 / 梵文殘片[cite: 3]

---

## Disclaimer / 聲明

- **Interpretive Mappings / 詮釋性映射**：
  本文中 AI 安全相關的對應與類比為作者的詮釋性映射，非經文本身的宣稱[cite: 3]。
  The correspondences to AI safety are the author's interpretive claims, not assertions made by the sūtra itself[cite: 2, 3].

---

## Citation Format / 引用格式

作者（non886）。〈己所不欲，勿勸他人：《無字寶篋經》的菩薩戒總持原則與 AI 安全〉。GitHub repository[cite: 3].
Author (non886). *"What You Yourself Do Not Desire, Do Not Urge Upon Others": The Bodhisattvas' Master Principle of Śīla in the Wuzi Baoqie Jing and Its Bearing on AI Safety*. GitHub repository.

`URL: https://github.com/non886/wuzi-baoqie-jing-ai-safety/` [cite: 3]
