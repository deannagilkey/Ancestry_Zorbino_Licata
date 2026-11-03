[README.md](https://github.com/user-attachments/files/34340906/README.md)
# The Zorbino-Licata Line

An interactive pedigree chart tracing the maternal ancestry of Deanna Gilkey — six generations
back to 1742, split between the Zorbino / Bernabei line of Abruzzo & Marche, Italy, and the
Licata / Rizzo / Bonafede line of Agrigento & Palermo, Sicily. Includes siblings for every
person in the tree where the source data records them.

## View it

Open `index.html` directly in a browser, or enable **GitHub Pages** for this repo
(Settings → Pages → Deploy from branch → `main` / root) and it will be live at:

```
https://<your-username>.github.io/<repo-name>/
```

## Photos & documents

Many people in the tree now have a photo and/or linked source documents (baptism records,
immigration cards, marriage records, news clippings, obituaries). These live in `images/`
and `docs/`:

```
images/
  licata/
    antonio-licata.jpg
    carmela-licata-zorbino.jpg
    carmela-licata-zorbino-2.jpg
    philip-m-licata-tampa.jpg
    philip-m-licata-tampa-2.jpg
docs/
  vital-records/
    alfio-zorbino-baptism-1909.jpg
    alfio-zorbino-immigration-card-1930.jpg
    antonio-licata-declaration-of-intention-1923.jpg
    antonio-licata-death-certificate-1934.jpg
    calogero-licata-baptism-1834.jpg
    guiseppe-rosalia-licata-gravestone.jpg
    infantino-rizzo-marriage-1837.jpg
    philip-licata-antonina-monte-marriage-license.jpg
    philip-licata-obituary.jpg
  newspaper-clippings/
    philip-licata-attempted-holdup-tampa.jpg
    philip-licata-payroll-holdup-case.jpg
    philip-licata-trial-concluded.jpg
    philip-licata-acquittal.jpg
    philip-licata-court-page.jpg
    philip-licata-liquor-violation.jpg
    philip-licata-petty-larceny.jpg
```

To add more for someone who already has an ahnentafel number (shown in the `DATA` object in
`index.html`): drop the file into the matching folder and add/extend an entry in the `MEDIA`
object, keyed by that number.

To add more for someone who **only appears as a sibling** (no ahnentafel number — shown in
`SIBLING_GROUPS` instead): add/extend an entry in the `SIBLING_MEDIA` object, keyed by their
exact name as written there.

## Unsorted — not yet linked to the chart

`docs/unsorted/` and `images/unsorted/` hold items that haven't been confidently matched to
anyone in the tree yet. Nothing in these two folders is wired into `index.html`.

**From the 1700s Grotte/Sciacca church records (new surnames not yet in the tree):**
- `rosario-fucale-record-1737.jpg` — Rosario Fucale, 1737
- `antonio-vacanti-record-1701.jpg` — Antonio/Antonino Vacanti, 1701
- `martino-tavormina-record-1751.jpg` — Martino Tavormina, 1751
- `pellegrino-zito-record-1701.jpg` — Pellegrino Zito, 1701
- `michele-firetto-marriage-promise.jpg` — Michele Firetto, marriage promise record

None of these surnames (Fucale, Vacanti, Tavormina, Zito, Firetto) appear elsewhere in the
tree yet — still open whether they're earlier ancestors, in-laws, or something else.

**Antonino Licata contradiction — needs research:**
- `filippo-licate-antonino-licate-ancestry-screenshot.jpg` — an Ancestry record showing
  **Filippo Licate (b. 1816)** as the *father* of an **Antonino Licate**. The tree's existing
  Antonino Licata is recorded as born **~1795** — 21 years *before* this supposed father,
  which can't be right as the same two people. Either the ~1795 birth year is wrong, or this
  is a different Antonino Licata (a relative sharing the name). Unresolved.
- `antonino-licata-portrait.jpg` — a studio portrait, photographic style suggests early
  1900s rather than someone who'd have died in 1851, so likely depicts a *different*
  Antonino than the one currently in the tree (possibly the one from the screenshot above).
- `filippo-licata-record.jpg` — a civil marriage record from Sambuca; the visible text
  doesn't actually show "Filippo Licata" (it shows a groom named Giovanni Vaudajo) — may be
  mislabeled, or Filippo appears elsewhere on the page not clearly legible.
- `maria-licata-death-cert-tampa-daughter-of-filippo-licata.jpg` — a Florida death
  certificate for a Maria Licata (d. ~1918, Hillsborough County/Tampa area), daughter of
  Filippo Licata and Francesca Merla — same parents as the Ancestry screenshot above. This
  points toward the Filippo Licata branch connecting to the **Tampa** Licata family (Philip
  M. Licata) rather than the WV line — still unconfirmed.
- `tampa-tribune-1899-12-29-antonio-licata-court-case.pdf` — an 1899 Tampa Morning Tribune
  front page covering a bribery/shooting case involving an "Antonio Licata" — another data
  point for the Tampa Licata family, predating Philip M. Licata's own 1920s court troubles.
  Possibly a father or uncle of Philip's.

**Bonafede cousin line — not yet modeled in the chart:**
- `natale-bonafede-1854-son-of-gaetano-birth-1854.jpg` and
  `natale-bonafede-1854-son-of-gaetano-death-1859.jpg` — birth (1854) and death (1859,
  age ~5) records for a Natale Bonafede, son of **Gaetano Bonafede** (b. 1829), who is
  already in the tree as a sibling of Salvatore Bonafede (node 14). This Natale would be a
  cousin of Giuseppa Bonefede's, one generation removed — a "second cousin" relationship the
  current chart structure (ancestors + their immediate siblings only) doesn't have a slot
  for. Kept here for the record rather than forced into the chart.

**Kept out of the chart by request:**
- `paul-gilkey-obituary.jpg` and `paul-gilkey-memorial-card.jpg` — Paul Anthony Gilkey's
  (Rosemary's husband) obituary and memorial card. Kept here for the record, but not linked
  anywhere in `index.html`, since that branch was intentionally removed from the chart
  earlier.

**Rizzo photos — need identification:**
- `great-grandparents-rizzo-group-photo.jpg` — an old group photo with handwritten names
  "Diego, Rosario, Della, Frank Dimino" and an arrow labeled "Grampa." Unclear which name
  matches which person in the photo, or how "Dimino" fits in.
- `rizzo-grandparents-photo.jpg` — a photo of three people (young man, older woman, older
  man) labeled only "Rizzo grandparents." Several Rizzo couples exist in the tree across
  generations — unclear which one this depicts.
- `rosario-maria-rizzo-record.jpg` — an Italian birth/baptism register page; handwriting too
  faint to confirm whether this matches an existing Rizzo in the tree or introduces someone
  new.

**Other unresolved:**
- `moon-saloon-ad-licata-varde.jpg` — newspaper ad for a saloon, "Licata & Varde,
  Proprietors" — no first name given, unclear which Licata.
- `rosalia-two-children-photo.jpg` — photo of two young children, filename just says
  "Rosalia" with no surname. Could be Rosalia Licata (d. age 3, already in the tree) or
  Rosalia Infantino, or someone else entirely.

Previous unsorted newspaper pages (full-page scans with no visible family-name match):

- `il-corriere-italiano-1907-08-24-p6.pdf` — mentions a **Salvatore Rizzo** as a festival
  committee president (Rochester, NY)
- `brooklyn-eagle-1917-09-21-p17.pdf` — a WWI unit photo caption lists a **Salvatore
  Bonefede**, corporal, Machine Gun Company at Sheepshead Bay
- `herald-statesman-1969-12-17-p21.pdf` — headline "Buonefede Released On Bail," a
  **Salvatore Buonefede** arrested for breaking/entering and larceny
- `daily-republican-1930-11-21-p1.pdf`, `pittsburgh-press-1931-03-02-p21.pdf`,
  `pittsburgh-post-gazette-1922-11-21-p1.pdf`, `pittsburgh-post-1918-06-29-p5.pdf`,
  `pittsburgh-post-gazette-1918-06-29-p9.pdf` — full pages with no family name found in
  them yet; could be the wrong page, or the relevant item just wasn't legible at this
  resolution

The repeated "Salvatore Bonefede / Buonefede" name (1917 and 1969) is worth a second look —
possibly the same man 52 years apart, or father and son — but it hasn't been confirmed as
connecting to Salvatore Bonafede (b. 1842) already in the tree.

## Open items from the last round of photos

- **Antonio Licata's death certificate** lists his mother as "Josephine Bonefede" — but the
  Ancestry tree has Giuseppa Bonefede as his *wife*, not his mother. Worth double-checking
  which is correct.
- **Philip M. Licata** (Tampa, FL) was added as a 6th sibling of Antonio Licata based on
  family photos/documents rather than the original GEDCOM — his birth order among the
  siblings is a guess (no birth date found yet).
- Three photos from the same batch are still unidentified: a porch photo of three people,
  a young man's yearbook-style portrait, and a young woman's portrait. Not yet added anywhere.

## Source

Built from a GEDCOM export from Ancestry.com. Dates and places are shown as recorded in that
export. A few entries appear to be duplicates in the original source data (e.g., a person
listed twice with identical dates) — these are preserved as-is rather than edited out.
