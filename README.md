## Voynich_Manuscript_Decipherment_reveals_ByzantineOrthodoxGrimoire
The *Yarman Mapping* using CSS and Oxygen XML editor reveals that the [@*Voynich Manuscript*](https://en.wikipedia.org/wiki/Voynich_manuscript) is likely a **spell book**, or a **black magic chant book** choke full of *macaronic Greek* pronunciations of the name of **Jesus Christ (S.A.W.)**, where His Christian epithets like *YIOS* and associations like *THEO* are acrostically used as syllabic content to sometimes constitute his flexed out and musicologically suggestive repetitious name that is chaotically laid out across regular-sized word-blocks for hunderds of pages, as preliminarily tackled here [@Updated Full Voynich Revelation](https://www.youtube.com/watch?v=VnYrOcyYjLU&amp;t=16s) and here [@Voynich is a BLACK MAGIC BOOK!!](https://www.youtube.com/watch?v=kRqcrFLZz6o&amp;t=130s).


# The Yarman Mapping: Voynich Manuscript TEI/CSS Transliteration & Byzantine Greek Grimoire Hypothesis

**Author:** Prof. Dr. Ozan Yarman (Istanbul University);
**Discovery & Calibration Window:** November 1–19, 2026;
**Repository Base:** Adapted from the [newtfire/voynichTEI](https://github.com/newtfire/voynichTEI) TEI/XML corpus and related files;
**Documentation:** [@OzanYarman on YouTube](https://www.youtube.com/@OzanYarman) | [@OzanYarman on WordPress](https://ozanyarman.com/wpress/parapharnalia/comment-page-2/#comment-109) | [Voynich Ninja Thread #6302](https://www.voynich.ninja/thread-6302.html).

---

## Overview

This repository houses, besides the requisite and wonderful *`EVA2.tff`* font by the late Gabriel Landini (who passed away on 19 October 2025, as announced by his colleague Rasha Abu Eid of the University of Birmingham on 20 October 2025), the **`evaFontCSS.css`** custom stylesheet, alongside the updated TEI/XML files `herbal.xml`, `ZL3b-n.xml`, and `ZL3b-n_updated.xml` files, as well as their rendered PDF outputs `herbal.pdf`, `ZL3b-n.pdf`, and `ZL3b-n_updated.pdf`. When loaded in **Oxygen XML Editor** over *Extensible Voynich Alphabet (EVA)* transcriptions (`EVA2.ttf`), for which the user must navigate to *Options>Preferences>Document Type Associations>Create New TEI Association* under the said Editor IN ORDER TO CORRECTLY REINTERPRET AND REPARSE THE MENTIONED XML FILES, the stylesheet executes a deterministic, nested `oxy_replace()` pipeline that converts Voynichese glyphs into **Mathematical Sans-Serif Unicode** (`U+1D5A0`–`U+1D5FF`) characters.

Rather than treating Voynichese as standard vernacular prose, the *Yarman Mapping* models the 15th-century codex as a **Byzantine Greek Orthodox grimoire / mnemonic ritual book** (analogous to an Arabic *Jifr* in a Middle Eastern Islamic context). Under this hypothesis, the scribe seems to have prosodically adapted the opening structure of the **Great Doxology**, and embedded historical Christian *Nomina Sacra* (`𝖨𝖧𝚺`, `𝖨𝚺`) alongside three more of the five **ΙΧΘΥΣ** (*ICHTHYS*) acrostic/rebus roots (`𝖳𝖧𝖤𝖮𝖴`, `𝖸𝖨𝖮𝖲`, `𝖷𝖱𝖨𝖲𝖳𝖮𝖴`) into continuous, block-chopped phonetic vocalizations of the name of Jesus (*Iesous*) and His epithets across hundreds of folios.

---

## Chronological Evolution of Yarman's Hypotheses (Nov 1–19, 2026)

1. **Phase 1 — Byzantine Liturgical Chant Book & *Ison* Drone Conjecture (Nov 1–8, 2026)**
   - *Videos:* [A Voynich Discovery?](https://www.youtube.com/watch?v=IH_GbDw_Y24) | [The awaited Voynich Breakthrough?](https://www.youtube.com/watch?v=IH_GbDw_Y24) | [Full Voynich Decipherment](https://www.youtube.com/watch?v=sUEUlEpmugc);
   - Initial BBEdit/Oxygen XML calibrations seemed to reveal recurring Latin (*Gloria*, *Gratia*) and Greek theological roots (*Doxa*, *Kyrie*, *Iesous*, *Christos*, *Eleison*) that anyway lacked standard noun declensions and verb conjugations. These were interpreted by Yarman as uninflected "sacramental word blocks" functioning as a shorthand prompt sheet for Byzantine modal chant (*Octoechos*) over an *ison* drone.
2. **Phase 2 — The "Medici Youth" Pedagogical Scrapbook & "Breve Glue" (Nov 8–13, 2026)**
   - *Videos:* [Refined Full Voynich Decipherment](https://www.youtube.com/watch?v=I3Mr4IMzasw) | [Updated Full Voynich Revelation](https://www.youtube.com/watch?v=VnYrOcyYjLU);
   - To account for the manuscript's excessive lexical redundancy, the high-frequency EVA glyph `a` was mapped by Yarman to a Unicode breve (`˘`) that acted as a silent consonantal slurring separator comparable to the Turkish soft G (*ğ*).
3. **Phase 3 — The Folio `f49v` Cyclamen Key & Grimoire Identification (Nov 14–16, 2026)**
   - *Videos:* [Voynich is a BLACK MAGIC BOOK!!](https://youtube.com) | [Voynich Manuscript a Grimoire!!](https://youtube.com);
   - Trying to calibrate the *Yarman Mapping* against the 26-character vertical marginal column of *Folio `f49v`* with respect to the way it was accompanied by handwritten Arabic numerals (`1–5`) (the Cyclamen/Lunaria page) yielded a devotional/incantatory reading centered on *IHS* and *Kyrie* (*"Show Mercy, Lord"*), which helped Yarman reframe the luxury vellum codex as a wealthy patron's esoteric ritual grimoire.
4. **Phase 4 — Acrostic/Rebus Subversion & Technical Audit Refinements (Nov 16–19, 2026)**
   - *Documents:* Files appearing in *Overview*;
   - Refinement of the theological mechanics: rather than a literal sentence-by-sentence translation of *"Glory to God in the highest,"* the opening (`f1r`) was changed by Yarman to directly start with **`𝖨𝖧𝚺`** (*IHS*) and weaved lookalikes of **ΙΧΘΥΣ** (*ICHTHYS*) theological components (`𝖳𝖧𝖤𝖮𝖴` = *of God*, `𝖸𝖨𝖮𝖲` = *Son*, `𝖷𝖱𝖨𝖲𝖳𝖮𝖴` = *of Christ*) into an iotacized phonetic stream.

---

## Core Structural & Philological Anchor Points

### 1. Historical *Nomina Sacra* & ΙΧΘΥΣ Acrostic Roots

The current stylesheet assigns two historically attested Greek manuscript
abbreviations for **Ἰησοῦς** (*Iesous*), alongside four of the five constituent
roots of the early Christian **ΙΧΘΥΣ** acrostic:

| EVA Input | Rendered Output | Historical / Philological Parallel | `ZL3b-n_updated.pdf` | `Herbal.pdf` |
| :--- | :--- | :--- | :---: | :---: |
| `f`   | **`𝖨𝖧𝚺`**   | Three-letter *Nomen Sacrum* **ΙΗϹ** (IHS) | 245 | 84 |
| `ckh` | **`𝖨𝚺`**    | Two-letter contracted *Nomen Sacrum* **ΙϹ** (IS) | 904 | 308 |
| `cth` | **`𝖳𝖧𝖤𝖮𝖴`** | Greek **ΘΕΟΥ** (*Theou* — "of God") | 927 | 532 |
| `kch` | **`𝖳𝖧𝖤𝖮𝖲`** | Greek **ΘΕΟΣ** (*Theos* — "God") | 1,053 | 517 |
| `cph` | **`𝖸𝖨𝖮𝖲`**  | Greek **ΥΙΟΣ** (*Huios* — "Son") | 212 | 98 |

> **Note on ΙΧΘΥΣ.** Four of the five acrostic constituents are instantiated:
> Ι (Ἰησοῦς → `𝖨𝖧𝚺`, `𝖨𝚺`), Χ (Χριστός → `𝖷𝖱𝖨𝖲`, `𝖷𝖱𝖨𝖲𝖳𝖮𝖴`), Θ (Θεοῦ → `𝖳𝖧𝖤𝖮𝖴`)
> and Υ (Υἱός → `𝖸𝖨𝖮𝖲`). The fifth, **Σ (Σωτήρ, "Savior")**, has no rule in
> v1.0 and is therefore *not* claimed. The parallel is offered as a partial
> structural analogy, not a complete acrostic.

**Counting method.** Figures are overlapping substring counts on the NFKC-
normalised PDF text layer, obtained by direct count of the normalised strings
(`IHΣ`, `IΣ`, `THEOU`, `THEOS`, `YIOS`, `YIOU`, `KYRIE`). They are counts of
rendered output, **not** independently established Greek words.

Two limitations are stated explicitly:

1. A stem can also arise by concatenation across glyph boundaries — e.g.
   `tch` → `THEO` followed by `r` → `S` yields the string `THEOS` without `kch`
   being present. The figures are therefore upper bounds on rule firings.
2. `IΣ` is a clean count in v1.0, because Greek Σ is emitted only by `ckh` and
   `f`, and `IΣ` is not a substring of `IHΣ`. This does **not** hold for scripts
   that case-fold Σ to Latin `s`, where `is` matches inside hundreds of strings.

**File overlap.** `ZL3b-n.pdf` and `ZL3b-n_updated.pdf` return identical counts
for IHS, IS, THEOS, THEOU and YIOS (245 / 904 / 1,053 / 927 / 212), differing
only in YIOU (0 vs 1) and KYRIE (0 vs 10), with the latter attributable to the
`⟦alternative / alternative⟧` rendering of `<choice>` elements. They are the
same manuscript content and **must not be summed or treated as independent
witnesses**. `Herbal.pdf` overlaps both.

### 2. Opening Sequence (`f1r`, Line 1 — `ZL3b-n_updated.pdf`)
- **Raw EVA:** `fachys.ykal.ar.ataiin.shol.shory.cthores.y.kor.sholdy ... sory.ckhar.or`
- **Current CSS Output:** `𝖨𝖧𝚺˘𝗈𝗂𝖲𝗂𝗈𝖾.𝗂𝗈𝗂𝗒˘𝖲𝗈.˘𝖲.˘𝗂𝖲˘𝗒𝖾𝗈𝖲.𝗈𝗂𝖾𝖲𝗈.𝗈𝗂𝖾𝖲𝗂𝗈.⟦𝖳𝖧𝖤𝖮𝖴 / 𝗂𝖾𝗂𝖲𝗂𝖾⟧𝖲𝗂𝗍𝗁𝖾.𝗂𝗈.𝗂𝗒𝗂𝖾𝖲.𝗈𝗂𝖾𝖲𝗈𝖾𝗒𝗂𝗈 ... 𝖾𝗂𝖾𝖲𝗂𝗈.𝖨𝚺˘𝖲.𝗂𝖾𝖲 ...`
- **Structure:** Immediately begins with the sacred abbreviation **`𝖨𝖧𝚺`** (*IHS*), followed by breve-separated phonetic punctuations and not-anymore-so-uncertain `<choice>` readings that are cleanly rendered inside `⟦ ... / ... ⟧` brackets.

### 3. Folio `f49v` (Cyclamen / Lunaria) 26-Mark Vertical Key
On folio `f49v` (`Herbal.pdf` p. 74, corresponding to p. 96 of the original digitized pagination), a vertical column of 26 Voynichese characters, a vertical column of 26 Voynichese characters runs down the left margin, along with handwritten Arabic numerals `1–5` right next to them that correspond to the first paragraph's second, third, fourth, fifth, and sixth lines, respectively. Under the current `evaFontCSS.css` rules, the 26-mark column renders deterministically without rearrangement:

```text
f  -> 𝖨𝖧𝚺
o  -> 𝗂𝖾
r  -> 𝖲
y  -> 𝗂𝗈
e  -> 𝗂𝗍𝗁
Œ  -> 𝖾𝗅
k  -> 𝗂𝗒
s  -> 𝖾
p  -> 𝖲𝗈𝗎
o  -> 𝗂𝖾
À  -> 𝖪𝖸𝖱𝖨
y  -> 𝗂𝗈
e  -> 𝗂𝗍𝗁
Œ  -> 𝖾𝗅
¤  -> 𝖾𝗂
p  -> 𝖲𝗈𝗎
o  -> 𝗂𝖾
À  -> 𝖪𝖸𝖱𝖨
y  -> 𝗂𝗈
e  -> 𝗂𝗍𝗁
Œ  -> 𝖾𝗅
d  -> 𝖾𝗒
y  -> 𝗂𝗈
e  -> 𝗂𝗍𝗁
k  -> 𝗂𝗒
y  -> 𝗂𝗈
```

where Yarman interprets `𝖲𝗈𝗎` as either `𝖲𝗈𝗎` or `𝖲𝗈𝗇`, and `𝗂𝗍𝗁` as either (𝗂 + 𝗍𝗁) or as (𝗂 + 𝖲) depending on the circumstance. As such, this new arrangement spells out: ``IHΣ, IESIOIS ELIYESON! IE KYRIIOIS ELEISON! IE KYRIIOIS ELEIOI THIYIO!``


**Applied vocalization rules stated in full:**
1. Marks 5, 13, 20 (`e`): `𝗂𝗍𝗁` read as (𝗂 + 𝖲) → `iS`. Three substitutions, −3 characters.
2. Mark 24 (`e`): `𝗂𝗍𝗁` read literally as (𝗂 + 𝗍𝗁), retained across the unit boundary.
3. Mark 22 (`d`): `𝖾𝗒` read as `e`, the `y` elided in cantillation. One elision, −1 character.
4. `𝖲𝗈𝗎` transformed to `Son` twice.

Net: 61 → 57 characters. Rules 1 and 2 are the alternatives declared above.
Rule 3 is an elision and is stated here explicitly rather than applied silently.

### Phonological note

Byzantine *itacism* merged ι, η, υ, ει and οι to /i/. The digraph **ου was not
affected**: it remained /u/ from Koine through the Byzantine period into Modern
Greek. Ἰησοῦς is therefore /i.iˈsus/ in the fifteenth century, while Κύριος is
/ˈkirios/, with /i/ from the bare upsilon. An earlier formulation of this
hypothesis stated that Ἰησοῦς was pronounced /i.iˈsis/; that was incorrect and
is withdrawn.

The present hypothesis does **not** claim that the Name is spelled contiguously
as ΙΗΣΟΥΣ anywhere in the codex. The exact-string count for `IISOUS` is **zero**
in both PDFs, and the broad `isos` skeleton is *not* enriched relative to a
first-order null (668 observed vs 2,030 simulated in ZL3b; 70 vs 480 in Herbal;
lower-tail p = 0.0099 in both). No enrichment of `isos` over `isis` is claimed,
nor is that the purpose at this stage.

The claim is instead **distributive and cantillatory**: that the syllabic
material of the Name is spread across the regular word-blocks and reassembled
in performance, with the sacred abbreviations `𝖨𝖧𝚺` / `𝖨𝚺` and the epithets
`𝖸𝖨𝖮𝖲` / `𝖳𝖧𝖤𝖮𝖴` supplying iotic and sibilant content. This is a claim about
vocalization, not about orthography. It cannot be tested by contiguous sub-
string statistics, and it requires the vocalization rules to be written out
in full and frozen before any blind reconstruction is attempted.

### A possible author's name as a plausible conjecture

The four-glyph sequence `çèéê` occurs once in the corpus at **f68r2, line 31**.
This location coincides with astronomical drawings, with a large circle filled
with stars, each with a label; and at the top, within the large circle, is a
smaller circle with a moon in the middle, and a ring of Voynich text around the
circumference. At the bottom, within the large circle, is a smaller circle with
a sun in the middle and a ring of Voynich text around the circumference. Here,
the stylesheet assigns it the output `𝗈𝗎𝗂-𝗒𝗂-𝖺𝗇-𝗇𝗂𝖲`, vocalized *Ou-i-yi-an-nis*,
which admits reading as a macaronic **Ἰωάννης / Ioannes / Johannes / Γιάννης**.
The ending `-αν-νις` corresponds to the Greek -άννης, and the initial cluster
admits both Io- and Yi-.

**This is a speculation.** The sequence is a *hapax legomenon*, whose value was
assigned by the author of this stylesheet rather than derived from independent
constraints. A rule that fires exactly once cannot be tested, and unique four-
glyph sequences are common in the codex. It is recorded as a conjecture, and
is excluded from all counts and all statistical tests. So, it is not advanced
to support any other claim in this repository.

> **Withdrawn substitution.** Earlier revisions assigned `sh` → `𝖸𝖨𝖮𝖴`, yielding
> 4,539 occurrences in the ZL corpus. In v1.0 `sh` → `𝗈`, and `𝖸𝖨𝖮𝖴` is produced
> by the rare ligature `¢ˆ` (1 occurrence in each PDF). The figure 4,539 does
> not only apply to v1.0 and is withdrawn. `𝖪𝖸𝖱𝖨𝖤` (vocative) occurs 10 times in
> `ZL3b-n_updated.pdf` and 4 times in `Herbal.pdf`.

---

## Technical Architecture (`evaFontCSS.css`)

1. **Collision-Free Math Unicode Isolation:** Every substitution maps raw ASCII/extended-Latin EVA characters into the `U+1D5A0` Mathematical Sans-Serif Unicode block. Because target characters occupy a distinct Unicode plane from source EVA characters, earlier `oxy_replace()` outputs are never re-triggered by subsequent rules.
2. **XPath 2.0/3.0 Editorial Filtering:**
   ```xpath
   string-join(
     for \$n in node()[not(self::comment())][not(local-name() = 'comment')]
     return if (local-name(\$n) = 'choice')
       then concat('⟦', string-join(\$n/*[local-name() = 'unclearAlt'] ! string-join(descendant-or-self::text()[not(ancestor::*[local-name() = 'comment'])], ''), ' / '), '⟧')
       else string-join(\$n/descendant-or-self::text()[not(ancestor::*[local-name() = 'comment'])], ''),
   '')
   ```
   This ensures editorial `<comment>` tags (such as `"bar over o"` or `"corr?"`) are excluded from transliteration while preserving `<unclearAlt>` variants.

---

## Coding Roadmap

Based on independent technical audits conducted up until November 19, 2026, the following refinements had been done for the freezing of **v1.0** of the Yarman mapping for blind statistical testing:

- [x] **Explicit Long-Ligature Handling:** Priority rules work for gallows and special ligatures (`cth`, `ckh`, `cfh`, `cph`, `c„h`, `cÄh`, `cØh`, `c‹h`) at the top of the `oxy_replace` stack, so they are not misprocessed due to the stripping of their vital sub-characters by a shorter segmentation hunt during the operational cascade.
- [x] **Transcription Braces & Apostrophes:** Editorial apostrophes (`'`) were converted along with the Voynichese letters, and curly-brace ligature wrappers (`{cto}`) were isolated in order that the transcription formatting of the characters would not leak into the phonetic output.
- [x] **Unicode Normalization:** Wrapping the relevant `oxy` string in `Math Unicode` led to the direct substititon of Voynichese letters without any misplacement or dissasociation due to the cascading operation during the execution of the code.
- [x] **Non-Breaking Separators:** Standard spaces inside multi-word sacred outputs like `𝖧𝖠𝖦𝖨𝖮𝖴 𝖯𝖭𝖤𝖴𝖬𝖠𝖳𝖮𝖲` were replaced by Math Unicode dashes to preserve 1-to-1 token boundaries during statistical scans.
- [x] **Separation of Layers in Publication:** Vividly distinguishing between (a) the deterministic CSS transliteration outputs and (b) the interpretive hypotheses regarding *Octoechos* musical cantillation and grimoire/ritual usage can now be tackled thanks to the pristine latinized display on screen.

---

## Usage Instructions

1. Clone this repository or download `evaFontCSS.css`, `EVA2.ttf`, and the updated XML files (`herbal.xml`, `ZL3b-n.xml`, and `ZL3b-n_updated.xml`);
2. Ensure `EVA2.ttf` and `evaFontCSS.css` reside in the same directory as the `.xml` files;
3. Open `herbal.xml`, `ZL3b-n.xml`, and/or `ZL3b-n_updated.xml in **Oxygen XML Editor** and switch to **Author Mode** to view the live, automated transliteration.

---

## Citation & Attribution

When referencing this substitution table, Oxygen XML stylesheet, or the accompanying Byzantine Greek mnemonic/grimoire hypothesis, please cite:

> Yarman, Ozan (2026). *The Yarman Mapping: Automated TEI/CSS Transliteration of the Voynich Manuscript* or **Voynich_Manuscript_Decipherment_reveals_ByzantineOrthodoxGrimoire**, Istanbul University.


---


# Chronological Recount: Prof. Dr. Ozan Yarman’s Voynich Decipherment Journey

Prof. Dr. Ozan Yarman’s decipherment journey across his YouTube channel and Oxygen XML Editor experiments evolved through four distinct phases between **November 1 and November 19, 2026**, culminating in his claim that the Voynich Manuscript is a **Byzantine Greek "Black Magic Book" (Grimoire)** built around an acrostic and rebus-style stretching of the name of Jesus.

Drawing directly from the video explanations on his YouTube channel, here is the chronological recount of how his methodology and conclusions developed:

---

### Phase 1: The Monastic Hymn & Chant Book Hypothesis (Nov 1–8, 2026)

* **Software Pipeline:** In his initial breakthrough videos, Yarman introduced his dual-software workflow: calibrating character mappings in **BBEdit** and executing nested `oxy_replace` CSS rules inside **Oxygen XML Editor** over TEI-encoded Extensible Voynich Alphabet (EVA) files in XML format.
* **Liturgical Interpretation:** Observing recurring Greek-sounding roots (*Doxa*, *Kyrie*, *Christos*, *Eleison*), he initially concluded the manuscript was an uninflected **Eastern Orthodox liturgical chant book** written by mountain-dwelling monks. Because the output lacked standard Greek noun declensions and verb conjugations, he proposed it was a shorthand prompt sheet meant to be sung over an *ison* drone in the Byzantine modal (*Octoechos*) tradition, where the glyphs themselves acted as hidden musical notation.

---

### Phase 2: The "Medici Youth" Pedagogical Scrapbook (Nov 8–13, 2026)

* **Revisiting the Grammar Gap:** Yarman later on addressed the manuscript's high word repetition and missing grammatical endings by shifting the historical context.
* **The "All Work and No Play" Analogy:** Comparing the obsessive textual repetition to Jack Nicholson’s typing in *The Shining*, he hypothesized that the codex was a **15th-century "scrapbook" or grammar workbook** belonging to a wealthy youth (possibly of the Medici family) studying under a Byzantine Greek tutor following the decline of Constantinople. Under this view, the tutor wrote down raw sacramental roots (in `#Abjad` style) for the student to complete with proper Greek inflections.
* **Introducing the Breve (`˘`):** To align the opening lines of folio `f1r` with the Great Doxology (*"Doxa en hypsistois Theo"*), he converted the high-frequency EVA character `a` into a silent consonantal slurring marker—a breve (`˘`)—likened to the Turkish soft G (*ğ*).

---

### Phase 3: The Cyclamen Marginalia & "Black Magic Book" Pivot (Nov 14–16, 2026)

* **The `f49v` Key:** In his later videos Yarman anchored his calibration to the vertical column of glyphs accompanied by handwritten Arabic numerals (`1, 2, 3, 4, 5`) on the Cyclamen plant folio (`f49v`).
* **Deciphering the Incantation:** Reading that marginal sequence as the superseded *"IHS, ISSEIS, ELEYZOIS KYRIEIS! ELEIZOIS KYRIEIS! ELEYISEI!"* (O Jesus, Jesus, Mercy Lord! Mercy Lord! Show Mercy!), he concluded that the expensive calfskin manuscript was not a student's drill book, but a **Christianized *Jifr* or Byzantine Greek grimoire**. He proposed its purpose was occult and ritualistic: casting blessings or curses, enchanting botanical remedies or poisons, and consulting the stars for fortune.

---

### Phase 4: The Acrostic, Rebus & Macaronic Stretching of "Jesus" (Nov 16–19, 2026)

* **Subverting the Great Doxology:** In his final calibration of `evaFontCSS.css` as shared on [Voynich Ninja Thread #6302](https://www.voynich.ninja/thread-6302.html) and as documented in his November 19 technical notes, Yarman refined how the opening text works. Rather than a straightforward liturgical translation of *"Glory to God in the highest,"* he argued the author **prosodically usurped** the Great Doxology's rhythm to disguise an opening built on the *Nomina Sacra* **`𝖨𝖧𝚺`** (*IHS* / Jesus).
* **Acrostic & Rebus Embedding (`THEO` and `YIOU`):** Drawing parallels to the early Christian **ΙΧΘΥΣ** (*ICHTHYS*) acrostic, Yarman demonstrated how his Oxygen XML transformation embeds uppercase theological roots—specifically **`𝖳𝖧𝖤𝖮` / `𝖳𝖧𝖤𝖮𝖲`** (God) and **`𝖸𝖨𝖮𝖴` / `𝖸𝖨𝖮𝖲`** (Son)—directly inside continuous, block-chopped phonetic strings (`𝗂𝗈𝖲`, `𝖾𝗈`, `𝗂𝗍𝗁`).
* **Hundreds of Pages of Macaronic Incantation:** Using Math Unicode characters (`U+1D5A0` block) in Oxygen XML to prevent secondary substitution collisions, the resulting PDFs render hundreds of folios as an unbroken, hypnotic vocalization where the Greek name of Jesus (*Iesous*) and His epithets are stretched, re-spelled, and punned across word boundaries—serving both as **occult camouflage** against uninitiated readers and as a **mnemonic/musicological framework** for ritual chanting.
