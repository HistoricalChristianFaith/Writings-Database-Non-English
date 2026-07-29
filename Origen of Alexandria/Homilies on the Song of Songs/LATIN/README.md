# Origen, *Homilies on the Song of Songs* — Latin source (Jerome's version)

Two homilies of Origen on the Song of Songs, surviving not in the lost Greek but in
the Latin translation made by **Jerome** (c. 383), prefaced by Jerome's dedication to
**Pope Damasus**. This folder holds the Latin base text used for the English translation
in the main repository.

## Base text
- **Edition:** J.-P. Migne (ed.), *Patrologia Latina* vol. 23 (Paris, 1845), reprinting
  Vallarsi's text — *Interpretatio homiliarum Origenis in Canticum canticorum*, cols. 1117–1144.
- **Digital source:** *Corpus Corporum* (University of Zurich, https://mlat.uzh.ch), TEI
  encoding by Ph. Roelli (2019), normalized to classical-Latin orthography.
- **Public domain.** Migne (d. 1875) and Vallarsi (d. 1771) are long out of copyright; a
  fresh English translation from this text is clean to publish.

> **Note on the edition.** The project brief named Baehrens, *GCS* 33 (1925) as the
> preferred base. That is the right choice for the *Commentary* (Rufinus). For these two
> *Homilies*, no clean digital Baehrens text was available, whereas Corpus Corporum offers
> a fully clean digital transcription of Migne/Vallarsi — the same Jerome translation. The
> PL 23 text is therefore used here and documented as such rather than mislabeled Baehrens.
> Differences between Vallarsi and Baehrens are matters of a few variant readings, not of
> substance.

## Files
- `praefatio_latin.txt` — Jerome's preface to Pope Damasus.
- `homily1_latin.txt` — Homily 1 (on Song 1:1–1:11 — the bride's opening).
- `homily2_latin.txt` — Homily 2 (from *Nardus mea dedit odorem suum* to *vox tua suavis, et forma tua speciosa*).

## What was stripped
This is **clean digital Latin, not OCR** — no OCR-correction pass was needed. Removed from
the running text:
- Migne column numbers (`<emph>501</emph>` etc.);
- scripture-reference notes (`<note>(Cant. I, 3)</note>` etc.);
- page-break milestones (`<pb/>`);
- editorial **`[Al. ...]`** variant readings — Migne's main-text reading is kept, the
  bracketed alternate dropped (both the `[Al. …]` and the occasional `( Al. …]` forms);
- two editorial Greek glosses on *principale* (`[ ἡγεμονικῷ]`, `( ἡγεμονικὸν)`).

**Kept:** all of Jerome's running Latin, and every Greek word that is part of his own
argument — e.g. the contrast of *ἐπιστηριζομένη* vs *ἐπιστηθιζομένη* (Homily 1), *ὄρμισκος*
(glossed *parvum monile*), and the note that Aquila rendered a word *ἄγροικον* (Homily 2).

## Structure markers
- `== HOMILIA PRIMA ==` / `== HOMILIA SECUNDA ==` headings.
- `[§N]` markers follow **this edition's natural paragraph divisions**. PL 23 prints no
  section numbers for these homilies, so the numbering is editorial-to-this-file (for
  reader navigation and translation alignment), not Baehrens's or Migne's own.

## Scope
This is one of the two works in the Song-of-Songs project. The companion work — Origen's
much longer **Commentary on the Song of Songs** (Rufinus's Latin, running to Song 2:15) —
is a separate folder and is **not** sourced here; it still needs its own Latin base (Baehrens
*GCS* 33 / Corpus Corporum).
