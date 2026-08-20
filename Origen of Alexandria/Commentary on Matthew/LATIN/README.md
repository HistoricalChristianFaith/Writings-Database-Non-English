# Origen, *Commentariorum Series in Matthaeum* — Latin source

The Latin **Series** on Matthew: an anonymous late-antique (5th/6th c.) Latin rendering of Origen's
now-lost Greek commentary, covering **Matthew 22:34–27:66** and transmitted not in books but as
**145 numbered sections** (*Comm. ser.* 1–145). It picks up where the surviving Greek books of the
commentary stop (Matt 22:33) and runs to the end of Matthew (omitting ch. 28). This folder holds the
Latin base text used for the English translation in the main repository.

## Base text
- **Edition:** E. Klostermann & E. Benz (edd.), *Origenes Werke* XI — *Matthäuserklärung* II:
  *Die lateinische Übersetzung der Commentariorum Series*, **GCS 38** (Leipzig, 1933).
- **Digital source:** the public-domain page scans of GCS 38 (1933) on archive.org; the running text
  was reconstructed from the images (not from Migne/PG 13, which the scans supersede).
- **Public domain.** The 1933 edition is out of copyright; a fresh English translation from this text
  is clean to publish.

## Collation & accuracy
Transcribed and then verified **page by page against the printed scans** of GCS 38 (the critical
edition's main reading text — not the apparatus variants). Multiple cleaning passes rejoined words
broken across page breaks, removed OCR/apparatus residue, and resolved flagged uncertain readings.

## What was stripped
Removed from the running text: the critical apparatus, running heads, and marginal line-numbers.
Also removed: the **parallel Greek catena fragments** Klostermann prints alongside the Latin — this
file is the **Latin reading text only**. 

## Editorial marks
- `» … «` wrap the **Scripture that Origen quotes** in his exposition (guillemets kept in the
  edition's German orientation).
- `* … *` marks the **Matthew lemma under comment** (the Gospel verse a section expounds), kept
  distinct from the scripture Origen cites while commenting.
- `⟨ … ⟩` are the editor's **supplements** (text he inserts; e.g. `humilia⟨veri⟩t`, `⟨de potibus⟩`) —
  part of the constituted reading.
- `[ … ]` are the editor's **seclusions** (text he brackets for deletion; e.g. `sic[ut]`, `[et]`).
- `…` marks a **printed lacuna** — text lost in the tradition; **do not fill it**.
- Greek letters occasionally appear inside a Latin quotation (e.g. `A et Ω`, Rev 1:8) and are kept.
- `[GCS p.N]` = GCS 38 printed page; `[PG n]` = Migne *PG* 13 column. **Kept for traceability**
  (unlike some sibling Latin sources here, which strip page numbers) — they mark where each page/
  column begins and explain the page-boundary paragraph breaks. Easily removed if undesired.

## Structure markers
- `== Comm. ser. N ==` headings follow **Klostermann's section numbering** (N = 1–145).
- Each section begins with its `*Matthew lemma*`; many sections continue the exposition of a
  preceding lemma and so open directly with commentary.

## Files (grouped by Matthew chapter, mirroring the English translation)
| file | Matthew | sections |
|------|---------|----------|
| `matthew22_latin.txt` | 22:34–46 | Comm. ser. 1–8 |
| `matthew23_latin.txt` | 23:1–39  | Comm. ser. 9–28 |
| `matthew24_latin.txt` | 24:1–51  | Comm. ser. 29–62 |
| `matthew25_latin.txt` | 25:1–46  | Comm. ser. 63–73 |
| `matthew26_latin.txt` | 26:1–75  | Comm. ser. 74–114 |
| `matthew27_latin.txt` | 27:1–66  | Comm. ser. 115–145 |
