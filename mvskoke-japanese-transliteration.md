# Mvskokē ⇄ Japanese Transliteration System

A working reference for a bidirectional Mvskokē (Muskogee Creek) ↔ Japanese katakana
transliteration and dictionary project. Compiled from ongoing development work.
Source dictionary base: Loughridge, Robert McGill — *English and Muskokee Dictionary* (1890, 241 pp).

Status: **living document** — rules have been repeatedly tightened against native-speaker
corrections rather than complicated. Treat unresolved items (flagged below) as open questions.

---

## 1. Core Phonology Rules (locked)

| Symbol | Value | Notes |
|---|---|---|
| **v** | short "uh" (as in *bus*, "Kung fu") → **ウ** | NOT the same as "a" — confirmed minimal pair (see §5) |
| **a** | "ah" → **ア** | distinct phoneme from v |
| **e** | "eh" → **エ** | |
| **i** | "ee" → **イー** (already long in Mvskokē) | |
| **o** | "oh" → **オ** | |
| **u** | "oo" → **ウー** (long) | |
| **ē** | long "ay" → **エー** | |
| **ā** | long "ah" → **アー** | |
| **ō** | long "oh" → **オー** | |
| **r** | lateral fricative "thl" — always a full consonant, never elided | closest Japanese anchor: the ス in アスリート. **No katakana equivalent** — this is the one true friction point between the systems |

### Consonants (base values before positional rules)
| Mvskokē | Katakana row | Notes |
|---|---|---|
| p | パ行 | voiceless base |
| t | タ行 | voiceless base |
| k | カ行 | voiceless base |
| s | サ行 | |
| h | ハ行 | |
| m | マ行 | |
| n | ナ行 | |
| l | ラ行 | rare in Mvskokē |
| w | ワ | |
| y | ヤ行 | |
| c | チャ行 | usually "ch" |
| ts | ツ | percussive, apostrophe-marked, single articulation |

### Positional (sandhi) rules — the engine
| Rule | Trigger | Example |
|---|---|---|
| p → b | between vowels | Tofv'mpé → トフンベー |
| t → d | between vowels | Catv → チャドゥ, moto → モドー |
| k → g | between vowels | Mvskokē → ムスゴギー |
| m → ン | before p/b | Hómpetv → ホンベドゥ; Tofv'mpé → トフンベー |

This is structurally the same phenomenon as Japanese **連濁** (rendaku) — same cognitive move, independent origin.

### Special markers
| Marker | Function | Japanese equivalent |
|---|---|---|
| `'` apostrophe | syllable boundary / preserves articulation | visual only |
| `'J` | sub-syllabic intensifier (command/urgency) | ッ (sokuon) |
| doubled consonant (kk, tt, pp) | **blocks** intervocalic voicing | ッ before the consonant |

**Reversibility note:** because the m→ン rule fires natively in both languages, round-trips like
Tofv'mpé → トフンベー → Tofv'mpé lose no information. English-into-katakana transliteration loses
information constantly; Mvskokē-into-katakana is close to a lossless rewrite in a different script.
The one systemic exception is r/thl.

---

## 2. Dual-Mode Rule for Shared Letters (r, and stop-voicing)

Discovery: the *script* is bilingual, not the rule. Which phonology applies depends on
**which language is being read**, exactly like katakana-for-foreign vs. hiragana-for-native
in Japanese itself — same letterforms, different phonetic job depending on context.

- Reading **Mvskokē** written in the shared script → r = thl, always, in all positions. Full stop-voicing rules (t→d, k→g, p→b) apply throughout.
- Reading **Japanese** written in the shared script → r = Japanese flap (ら行).
- Confirmed empirically: a Japanese name like 佐藤 (Satō), when rendered *in Mvskokē script*, is read with Mvskokē phonology — the t **does** become d (Sado), because the reader's ear runs Mvskokē rules on Mvskokē-alphabet text regardless of the word's origin language. This was the resolved "residual friction point" — not the liquid, but stop voicing.

---

## 3. Master Vocabulary (Loughridge-sourced, corrected)

### Animals (動物)
| Mvskokē | Katakana | Meaning |
|---|---|---|
| Efv | エフ | dog |
| Pósé | ボセー | cat |
| Fuswv | フスウ | bird |
| Cúfé | チューフェー | rabbit |
| Nokusé | ノクーセー | bear |
| Éco | エーチョ | deer |
| Cétto | チェット | snake |
| Locv Rakko | ロチャ・スラッコ | (big) turtle — note: coincidentally lands close to ラッコ, Japanese for "sea otter" (via Ainu) |

### Family (家族)
| Mvskokē | Katakana | Meaning |
|---|---|---|
| Erke | エスルケ | father *(r=thl retained)* |
| Et'ské | エツケー | mother |
| Hopüewv | ホピューウ | child *(open item — ü rendering unconfirmed, see §7)* |
| Eppúce | エップーチェ | son |
| Héssé | ヘーセー | friend |

### Nature (自然)
| Mvskokē | Katakana | Meaning |
|---|---|---|
| Hvsē | フセー | sun *(minimal pair with hasē — see §5)* |
| Hvréssé | フスレーセー | moon |
| Sūtv | スートゥ | sky |
| Uéwv | ウェーウ | water |
| Eto | エドー | tree |
| Hótvlé | ホトゥレー | wind |
| O'Skë | オスケ | rain |

### Body (体)
| Mvskokē | Katakana | Meaning |
|---|---|---|
| Féké | フェーケー | heart |
| E'kv | エク | head |
| En'ké | エンケー | hand |
| Ellé | エッレー | foot |
| Cükwv | チュクウ | mouth |
| Catv | チャドゥ | blood *(intervocalic t→d)* |

### Cherry blossom set — morphology find
| Mvskokē | Katakana | Meaning |
|---|---|---|
| Tofv'mpé | トフンベー | cherry |
| Pv'kpvké | ブクブケー | blossom/flower |
| Tofv'mpé Pv'kpvké | トフンベー・ブクブケー | cherry blossom (桜) |
| Pvkánv | ブカヌ (or ブカーヌ — length unconfirmed) | peach |
| Pvkánuce | ブカヌチェ (or ブカーヌチェ) | plum |

**Finding:** *Pvk-* functions as a recurring morpheme meaning "the flowering thing" —
fruits are named as children of the blossom. Structurally parallel to how kanji radicals
(e.g. 木) cluster semantically related characters. Supports a "spoken kanji" thesis for
Mvskokē morphology generally.

---

## 4. Calendar (12 months)

Mvskokē months run on a **little/big (-cusé / -rakko) paired system** — 8 paired months
completing seasonal cycles, 4 solo months marking singular seasonal events. This is the
same descriptive-seasonal logic as Japanese 和風月名 (wafū getsumei).

| # | Mvskokē | Katakana | Meaning | Type |
|---|---|---|---|---|
| 1 (Jan) | Rv'fo-cusé | スルフォ・チューセー | little winter | pair |
| 2 (Feb) | Hótvlé-hv'sé | ホートゥレー・フセー | wind moon | solo |
| 3 (Mar) | Tasáhcucé | タサーチューチェー | little spring | pair |
| 4 (Apr) | Tasáhcé-rakko | タサーチェー・スラッコ | big spring | pair |
| 5 (May) | Kē-hv'sé | ケー・フセー | mulberry moon | solo |
| 6 (Jun) | Kv'co-hv'sé | クチョ・フセー | blackberry moon | solo |
| 7 (Jul) | Hiyucé | ヒユーチェー | little harvest | pair |
| 8 (Aug) | Hiyo-rakko | ヒヨ・スラッコ | big harvest | pair |
| 9 (Sep) | Oto-wóskucé | オド・ウォースクーチェー | little nut | pair |
| 10 (Oct) | Oto-wóskv-rakko | オド・ウォースク・スラッコ | big nut | pair |
| 11 (Nov) | Ehólē | エホーレー | frost | solo |
| 12 (Dec) | Rv'fo-rakko | スルフォ・スラッコ | big winter | pair |

**Convergent naming finding:** Ehólē ("frost month") = 霜月 (shimotsuki), the old Japanese
name for November, also literally "frost month." Independent convergence, not shared origin.

"Month" itself: **Hvs'e-hv'mken** = "one moon" — structurally identical to 一ヶ月/一月.

---

## 5. Numbers

**Base-5-inside-base-10 finding:** numbers 6–9 are literally "n + 5":

| n | Mvskokē | Structure |
|---|---|---|
| 1 | Hvmken | |
| 2 | Hokkolen | |
| 3 | Tutcenen | |
| 4 | Osten | |
| 6 | Epáken | 1 + 5 |
| 7 | Kulvpáken | (kul ← 2) + 5 |
| 8 | Cenvpáken | (cen ← 3) + 5 |
| 9 | Ostvpáken | (ost ← 4) + 5 |
| 100 | Cukpé-hvmken | "one hundred" |
| 1000 | Cukpé-rakko | "big hundred" — same -rakko morpheme as the calendar |

The number system and calendar run on the same little/big derivational engine.

---

## 6. Minimal Pair (phonology proof)

| Mvskokē | Katakana | Meaning |
|---|---|---|
| Hvsē | フセー | sun |
| Hasē | ハセー | old / ancient |

Single vowel (v vs. a) changes meaning entirely — proof that v and a are distinct
phonemes, not orthographic variants. (Earlier draft work had mistakenly conflated them;
corrected across all vocabulary sets above.)

---

## 7. Greetings / Common Phrases (Mvskokē script rendering Japanese)

| Mvskokē script | Japanese | Meaning |
|---|---|---|
| Ohayō | おはよう | good morning |
| Konnēcēwa | こんにちは | hello / good day |
| Oyasumē | おやすみ | good night |
| Oyasumēnasaē | おやすみなさい | good night (polite) |
| Sumēmasen | すみません | excuse me / sorry |
| Sayonara | さようなら | goodbye |
| Ja'ne | じゃあね | see you (casual) |
| Ohēsashēburē | お久しぶり | long time no see |
| Arikkatō | ありがとう | thank you (doubled k blocks double-voicing) |
| Mattane | またね | see you again (doubled t blocks voicing) |
| Ettadakēmasu | いただきます | (before eating) |
| Hajēmemashēte / Hajēmemashēttē | はじめまして | nice to meet you |

**Open item:** 御 (go-) prefix words (e.g. ございます) start with word-initial g, which
Mvskokē has no native letter for (g only ever emerges intervocalically from k). Unresolved
workaround.

### Mvskokē phrases → Japanese (reverse direction)
| Mvskokē | Katakana | Japanese meaning |
|---|---|---|
| Mvto | ムァトー (Matoō) | thank you |
| Cufe Vpvnkedv | クフェ ヴプンケドゥ (Kufe Vupunkedu) | 踊るウサギ (Dancing Rabbit) |

---

## 8. Personal / Proper Names Worked Through

| Source name | Mvskokē script | Katakana | Notes |
|---|---|---|
| Cufe Haco | Chōfī Hajo | チョーフィ・ハジョ | intervocalic c-voicing applies to "Haco" |
| Muskogee | — | マスコギー (Masukogī) | standard ethnographic-text form |
| 黒崎一護 (Kurosaki Ichigo) | Ker'is'sakē Ecē'ko | — | Japanese-mode r |
| 佐藤 (Satō) | Sato | reads as "Sado" in Mvskokē-mode (see §2) | |
| 雨竜 (Amaryū?) | Uerue | — | |
| 桜 (Sakura) | Sak'erv | — | |
| 松本行弘 (Matsumoto Yukihiro / Matz) | Mah'ts'u'moto Yu'kē'hēro | — | can compound to **Mah'ts'u'Yukē'hēro** as a title, per Mvskokē conjunction patterns |

### Cufe Haco — semantic/title renderings
| Register | Japanese | Reading |
|---|---|---|
| raw/frenzied | 狂兎 | Kyōto |
| military-title fit (preferred) | 猛兎 | Mōto |
| shogunate-rank style | 兎将 / 猛兎将 | Toshō / Mōtoshō |

---

## 9. Open Questions / Unresolved Items

- **Hopüewv** (child) — the ü in Loughridge's orthography is unconfirmed; rendered as ホピューウ but pronunciation not fully verified against native speech.
- **Pvkánv / Pvkánuce** — whether the á is long (バー) or short stress-only mark (per Loughridge's usual convention) is unresolved; affects ブカヌ vs. ブカーヌ.
- **Tasáhcé** — whether "áh" is a long vowel or the h is doing consonantal work.
- **Oto-wóskucé** — whether the w is fully pronounced (ウォー) or soft/near-silent (オー).
- **Word-initial g** (Japanese ご-/御- prefix) has no native Mvskokē letter; g only exists intervocalically. No resolution yet.

---

## 10. Project Notes

- The transliteration is regular enough (~8–10 rules) to be **programmatically generated** as a first-draft pass over the full 241-page Loughridge dictionary, with human verification of edge cases afterward — a natural fit for a JRuby script feeding a Ruby-based dictionary tool (Mvskokē word in → Mvskokē + IPA + katakana + gloss out).
- Live-tested with native Japanese speakers on X with successful bidirectional reading (katakana read back correctly; Mvskokē-script Japanese greetings understood).
- Thesis under development for conference/CFP framing: Mvskokē morphology functions like "spoken kanji" — recurring root morphemes (Pvk-, -cusé/-rakko) that classify semantic fields and compound productively, structurally parallel to kanji radicals and Japanese descriptive month-naming (和風月名).
