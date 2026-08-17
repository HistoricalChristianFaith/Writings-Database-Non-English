# Origen, *Homilies on 1 Samuel (1 Kingdoms)* — source texts

Origen preached many homilies on 1 Samuel (= 1 Kingdoms / 1 Kings in the LXX and
Vulgate tradition). Only a small amount survives: **two complete homilies** plus
**catena fragments**. This folder gathers the original-language source texts for all of
them, as the base for a fresh English translation. 

## What survives, and what is here

| Piece | On | Language | File |
|-------|-----|----------|------|
| **Homily I** — *De Helcana et Phenenna* | 1 Sam 1–2 (Elkanah, Peninnah, Hannah, Samuel, Eli, Hophni, Phinehas) | **Latin** (Rufinus) | `LATIN/Homily 1 - De Helcana et Phenenna (PG12 Latin).txt` |
| **Homily II** — *De engastrimytho* ("Witch of Endor") | 1 Sam 28:3–25 | **Greek** | `GREEK/Homily on 1 Sam 28 - De engastrimytho (Klostermann GCS6).txt` |
| **Fragments** on the books of Kingdoms | 1–2 Sam, 1–2 Kings (catenae) | **Greek** | `GREEK/Fragments on Kingdoms - catena Samuel-Kings (Klostermann GCS6).txt` |
| **Fragment** on Hannah's song | 1 Sam 2 (from the Canticum catena) | **Greek** | `GREEK/Fragment on 1 Sam 2 - Cantica catena (Klostermann GCS6).txt` |

The *De engastrimytho* is Origen's primary text for the reading that the apparition
at Endor really was Samuel — the treatise **Eustathius of Antioch** wrote against
(*De engastrimytho adversus Origenem*, [issue #140](https://github.com/HistoricalChristianFaith/Writings-Database/issues/140)).
Klostermann's apparatus (preserved in the Greek file) records Eustathius's parallels
line by line.

## The Greek pieces (collated against GCS 6)

Base text: **Erich Klostermann, *Origenes Werke* III = GCS 6** (J. C. Hinrichs, 1901) —
the same critical edition/volume as the sibling *Homilies on Jeremiah* already in this
repository. Digital source: the **First1KGreek** project (OpenGreekAndLatin), TEI XML,
which is a clean Unicode transcription of Klostermann:

- De engastrimytho — `tlg2042.tlg013`
- Fragments (Samuel/Kings catena) — `tlg2042.tlg014`
- Fragment (Cantica catena) — `tlg2042.tlg015`
  (`https://github.com/OpenGreekAndLatin/First1KGreek`, `data/tlg2042/…`)

Processing: TEI converted to plaintext; sections marked `[§N]`, catena fragments `[Frag N]`
with their biblical lemma on the following `<< … >>` line; Klostermann page breaks kept as
`[p.N]`; editorial supplements `⟨…⟩`; manuscript sigla kept as `# ms:` lines. Klostermann's
**apparatus criticus** (testimonia + variant readings from cod. Monacensis etc.) is
preserved verbatim in a trailing `APPARATUS` block, keyed to his printed line numbers.
For fully line-numbered text, see the First1KGreek XML linked in each file header.

**Collation status.** The First1KGreek transcription carried OCR/markup artifacts into the
reading text, so the two larger Greek pieces were **collated character-by-character against
the GCS 6 page images** (archive.org `origenes-werke.-bd-3-1901`; leaf = printed page + 52,
confirmed on the running heads):

- **De engastrimytho** (pp. 283–294) and the **Samuel–Kings catena fragments**
  (pp. 295–303) were repaired against the print — inherited quote-mark damage (`»…«` opens/
  closes dropped or rendered as `‘`, `<`, `>`, `((`), missing/added parentheses and editorial
  brackets, wrong breathings and accents (standalone `ὀ`→`ὁ`, `ἠ`→`ἡ`, `ὄτι`→`ὅτι`,
  `ὐμῶν`→`ὑμῶν`, etc.), doubled or dropped words, stray Latin letters, and the `| |`
  placeholder (restored to Klostermann's marginal-reference bar `‖`). The badly garbled last
  page of the *De engastrimytho* (§10) and two garbled passages of the catena were
  re-transcribed from the print.
- The **Cantica fragment** (p. 304) was essentially clean; only a couple of spots
  (`ὄτι`→`ὅτι`, `ὔψωσις`→`ὕψωσις`, a dropped final `ς`) were corrected against the print.

Klostermann's **apparatus criticus** blocks were deliberately left **verbatim** (German,
Fraktur-garble and all) — out of scope; only the Greek reading text above each block was touched.

## The Latin homily (collated against PG 12)

Base text: **Migne, *Patrologia Graeca* 12, coll. 995–1012** (C. Delarue's pre-critical
text, 1733). Digital source: the public-domain scan of the Internet Archive item
**`patrologia-graeca_202105`, vol. 12** (djvu pages `12_0504`–`12_0512`). Running heads,
marginal quarter-column reference letters, scripture-reference marks, page numbers, and
Delarue's `(N)` footnote anchors were stripped; hyphenation across line/column/page breaks
was rejoined; the previous work's parallel Greek column (bleeding onto p. 504) was excluded;
æ/œ spelled out as ae/oe.

**STATUS — collated.** The file has been **read directly from the PG 12 page images** and
OCR-corrected (the old u/n, `c`/`e`, and *ae*-for-`z` errors fixed; consonantal j/v kept in
Migne's style; proper names kept as Migne prints them — Helchana, Phenenna, Ophni, Phinees).
The `[§N]` section markers now number the 19 sections in their true order (Migne's printed
digits misprint several — §1 as "4", §3 as "9", §11 as "41", etc.). **Baehrens GCS 33** page
images were used only as an independent cross-reference (its Fraktur OCR is unusable);
Migne's wording is preferred. Not paraphrased, reordered, abridged, or emended — OCR repair
only. Scriptural quotations are wrapped in `« »`; curly single quotes `‘ ’` mark Origen's
name-glosses. Delarue's textual footnotes (manuscript variants) are kept in a trailing
`APPARATUS` block.

## Other witnesses for the cleaning / cross-reference stage

- **Baehrens, *Origenes Werke* VIII = GCS 33** (1925) — the modern critical edition of
  the Latin (`https://archive.org/details/GCS33`). Note: its only digital OCR is a
  **corrupt Fraktur scan**, so it is a cross-reference for readings, not a clean base
  (same situation as this repo's *Commentary on the Song of Songs*).
- **P. & M.-T. Nautin, *Origène: Homélies sur Samuel*, Sources Chrétiennes 328** (1986)
  — critical text (Latin Homily I + Greek *De engastrimytho*) with French translation.
  **In copyright**; consult for verification only, do not import.
- **Migne PG 12 also prints the *De engastrimytho* itself** (Migne's "Homilia II in
  librum Regnorum", from a Vatican Greek MS), as **Greek + a parallel Latin translation**.
  A second Greek witness (Vaticanus, vs. Klostermann's Monacensis) plus an old Latin
  version. It was **not** extracted here because in the PG 12 scan those columns are badly
  interleaved and the polytonic Greek OCR is unusable; the Klostermann/First1KGreek Greek
  above is the far better base. The PG 12 Latin translation of the engastrimytho could be
  de-columnized later if a Latin witness is wanted.

## English translation

**FOTC 97** (John Clark Smith, *Origen: Homilies on Jeremiah and 1 Kings 28*, CUA Press,
1998) translates **only the *De engastrimytho*** (Homily II). There is no widely available
English translation of the Latin Homily I (*De Helcana*) — hence the plan to translate it
here from the Latin base.

## Licensing

Klostermann (d. 1954 — GCS 6 text 1901), Migne (d. 1875), Delarue (d. 1763), and Baehrens
(d. 1929) editions, and the Internet Archive / First1KGreek digital sources, are all public
domain. A fresh English translation from these bases is clean to publish.
