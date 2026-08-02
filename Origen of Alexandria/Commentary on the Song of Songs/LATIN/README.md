# Origen, *Commentary on the Song of Songs* (Rufinus's Latin) — Latin source

This folder holds the **Latin source text** of Origen's *Commentarium in Canticum
Canticorum*, in the Latin translation made by **Rufinus of Aquileia** (c. 410). It is a stripped, OCR-corrected plaintext base from which a
fresh English translation (Step 2, in the main repo) is made.

## Files
- `prologue_latin.txt` — the Prologue.
- `book1_latin.txt` … `book4_latin.txt` — Books I–IV (`== LIBER PRIMUS ==` … `QUARTUS`).

Total ≈ 51,200 words. Each biblical lemma (the Song-of-Songs phrase Rufinus quotes before
expounding it) is on its own line wrapped in guillemets, `» … «`; the text between lemmata
is the running commentary.

## Base text
**Migne, *Patrologia Graeca* 13** (J.-P. Migne, 1862), which reprints **C. Delarue's**
pre-critical text of Rufinus's translation (Delarue d. 1763). Digital source: the
public-domain DjVu OCR of Migne PG at the Internet Archive item
**`patrologia-graeca_202105`, volume 13** (`https://archive.org/details/patrologia-graeca_202105`),
the Song-of-Songs Commentary occupying roughly Migne coll. 61–198.

### Why Migne PG 13 rather than Baehrens GCS 33
The modern critical edition is W. A. Baehrens, *Origenes Werke* VIII (GCS 33, 1925), also
public domain (`https://archive.org/details/GCS33`). But its only digital text is a
**Fraktur OCR so corrupt it is unusable** as a base (multiple errors per line). Migne PG 13
is set in roman type and its OCR is far cleaner, and it is the same source family used by the
sibling *Commentary on Romans* in this repository (Migne/Delarue). GCS 33 was therefore used
only as an **independent cross-reference** to resolve doubtful readings and reconstruct
scrambled reading order — Migne's wording was preferred throughout; Baehrens variants were
**not** imported wholesale.

## Processing (how the plaintext was produced)
1. **De-columnization.** Migne prints two columns per page, and the flat DjVu OCR interleaves
   them, destroying reading order. The columns were therefore restored **from the DjVu XML
   using per-word pixel coordinates** (`13_djvu.xml`): words were split into left/right
   columns at the page gutter (~53% of page width), ordered top-to-bottom within each column,
   left column then right, page by page. This yields correct reading order.
2. **Stripping.** Removed running heads (column numbers, `ORIGENIS IN CANTICUM CANTIC.`,
   book running-heads), marginal quarter-column letters (A/B/C/D/E), page-bottom
   scripture-reference footnotes, Delarue's editorial `(N)` footnote blocks, in-body
   footnote-anchor numbers, and **all Greek catena (Procopius) fragments** together with their
   editorial intro tags and Latin translation-parallels.
3. **OCR correction.** Repaired OCR damage to the obviously-intended Latin. Orthography:
   æ/œ ligatures spelled out as **ae/oe**; consonantal **j/v** kept (Migne style); the proper
   name *Salomon* retained. Words hyphenated across column/page breaks were rejoined. The text
   was **not** paraphrased, abridged, reordered, or emended — OCR repair only. The one word
   the first pass could not recover (Book III, a tree-name at Song 2:5, garbled in the PG 13
   OCR as *gopéw*) was resolved on a second pass: Migne prints the Greek σμύρνην ("myrrh-tree,"
   confirmed by Baehrens GCS 33's parallel *smyrnen*), rendered here in Latin as *myrrhen* to
   match the *myrrhin/myrrha* of the surrounding lemma and keep the file Greek-free.

### One patched passage
The Prologue's opening paragraph (Migne coll. 61–62, *"Epithalamium libellus hic … ad
coniunctam sibi animam vel ecclesiam"*) is **absent from the PG 13 scan**. It was supplied,
OCR-corrected, from Baehrens GCS 33 and is marked with an inline
`<!-- … supplied from Baehrens GCS 33 -->` comment in `prologue_latin.txt`.

## Scope — the text is intrinsically incomplete
Rufinus translated only part of Origen's commentary: **it runs to Song of Songs 2:15**
(*"Capite nobis vulpes pusillas …"*) and stops. `book4_latin.txt` accordingly ends there
(*"… proficiet in virtutibus, et florebit in fide. Amen."*, a terminus confirmed against
Baehrens GCS 33), immediately before Migne's Greek *Excerpta Procopiana*, which are not part
of this work and are not included. This endpoint is a feature of Rufinus's translation, **not
a dropped section.**

## Licensing
Migne (d. 1875), Delarue (d. 1763), and Baehrens (d. 1929) are all long in the public domain,
as are the Internet Archive scans used. A fresh English translation from this base is clean to
publish; credit Migne PG 13 (Delarue) + the digital sources above.
