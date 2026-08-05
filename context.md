# Domain background — La Salette

Read together with `AGENTS.md` (working rules) and `KEYWORDS.md` (name
variants). This file is orientation, not data: everything citable lives in
`data/chronology.json`.

## Scope

The chronology runs 1826–2016. It is not only the apparition and the judgments:

- **Before (context, never corroboration).** Philibert de Bruillard's
  consecration as Bishop of Grenoble (1826) and what he had built by 1846 — 107
  new parishes, an eighty-year-old bishop twenty years into rebuilding a
  post-Revolutionary diocese. And the subsistence crisis of the Hungry Forties,
  worst in 1846: potato blight from 1845, failed cereal harvests, food prices
  peaking in the first half of 1847, roughly ten thousand famine-related deaths
  in France, bread doubling in price in the Isère. The reported message speaks
  of spoilt wheat and rotting potatoes. **Readers draw conclusions from that in
  both directions and the dataset draws none** — the entry says so in its own
  text, and any future edit must keep it saying so.
- **After.** The spring and the cures as *reported*; the inquiry of 1847 and the
  commission's vote; Rousselot's printed report; the first vows of the
  Missionaries (1858), Rome's canonical approval of the Institute (1879), the
  consecration and crowning of the basilica (1879), the congregation's spread
  from 1879/1892 onwards, the expulsion under the separation laws and the
  return in 1943, the Pilgrims' Association (1962), and the attendance figures
  as published.

## How reported miracles are handled (core#71)

**A miracle is a claim, not an event.** Only the ACCOUNT is datable here, and
there is no recognition act to date:

- The datable thing is the **reporting** — who claimed a cure, when the claim
  began to circulate, when the commission took it up, and when Rousselot put it
  in print. Titles name the reporter or the reporting, **never** a beneficiary:
  "The first cure is reported and circulated as a 'declared miracle'", never
  "N was cured". No cure is recorded as having happened.
- **There is no recognition act at La Salette.** Unlike Lourdes there is no
  medical bureau and no bishop's declaration that a named cure is miraculous;
  the French Wikipedia article states that the Church subjected these
  "declarations of miracles" to no scientific inquiry. The cures were part of
  the evidence the 1851 diocesan judgment weighed; they are not themselves
  approved miracles, and the 1851 judgment is about the apparition.
- **Cures get no approval-ladder rungs.** The five rungs are judgments on the
  apparition and on the secrets, and stay exactly as they are.
- Attendance figures are attributed to whoever publishes them, and where they
  disagree the gap stays: Villes Sanctuaires gives ~200,000 a year, the French
  Wikipedia ~300,000, neither states a method, and the dataset reconciles
  nothing.
- **Left out on purpose, because omission editorialises.** The individual cures
  Rousselot gathered are not broken out as events: the Gallica digitization of
  his book returned 403 to this session and Google Books shows only a preview,
  so no source read here says who was cured and when. Named-beneficiary cures
  that circulate in the devotional literature are not in the dataset for the
  same reason — a cure that cannot carry a source naming who reported it and
  when stays out.

## The event, as reported

On 19 September 1846, on a mountain pasture at about 1,800 m above the commune
of La Salette-Fallavaux (Isère, French Alps, then diocese of Grenoble), two
shepherd children from nearby Corps — Mélanie Calvat, 14 (the 1910 Catholic
Encyclopedia says 15), and Maximin Giraud, 11 — reported meeting a weeping
woman surrounded by light. Per their accounts she spoke first in French, then
in the local Occitan dialect, delivering a public message centred on blasphemy,
Sunday observance and conversion, and gave each child a personal secret. There
were no other witnesses; every statement about the event's content is a
statement about the children's accounts.

## The Church's judgments — two objects, two tracks

**Track 1 — the apparition.** Bishop Philibert de Bruillard of Grenoble
ordered a canonical investigation (commissions of clergy and theologians; the
French Wikipedia gives 19 July 1847 for the opening and 13 December 1847 for
the commission's favourable vote, both carried and both still flagged, the
diocesan acts themselves not being reachable). On
19 September 1851 — five years to the day — his doctrinal pronouncement
declared that the apparition "bears within itself all the characteristics of
truth" and that the faithful are justified in believing it. (The 1910
Catholic Encyclopedia dates the declaration 16 November 1851, likely its
publication in the diocese; recorded as a dateNote, not resolved.) His
pastoral of 1 May 1852 decreed a sanctuary on the mountain and founded the
Missionaries of Our Lady of La Salette; the cornerstone was laid 25 May 1852;
his successor Ginoulhiac confirmed the judgment in 1855; the church became a
minor basilica in 1879; in 2016 the Congregation for Divine Worship entered
the celebration in France's proper calendar (19 September, optional memorial).
This track has never been revoked.

**Track 2 — the expanded "secrets".** In July 1851 the children wrote their
secrets (Maximin's letter dated 3 July, Mélanie's 6 July) and the sealed texts
went to Pius IX via two envoys of the bishop — accounts differ on whether the
carriers were canons Gerin and Rousselot or vicars-general Melin and
Rousselot. Neither text was published; Maximin's never appeared at all.
Mélanie's versions grew over the following decades, culminating in the booklet
she published at Lecce on 15 November 1879 with the imprimatur of Bishop
Salvatore Luigi Zola — far longer than anything attested for 1851, including
the much-quoted apocalyptic passages. Rome's reactions were disciplinary and
aimed at this corpus, not at the apparition: an 1880 Holy Office wish (Cardinal
Caterini) that the Lecce booklet be withdrawn; the decree of 21 December 1915
ordering all the faithful not to discuss the "Secret de la Salette", its
diverse forms, or its application to present or future times (AAS 7 (1915)
594–595 — which adds expressly that devotion to Our Lady of La Salette is not
forbidden); and the decree of 9 May 1923 placing the 1922 reprint of the Lecce
booklet on the Index of Forbidden Books (AAS 15 (1923) 287–288).

**The repo's distinguishing requirement:** these two tracks are separate
judgments about separate objects. The most common error in the literature —
sympathetic and critical alike — is collapsing them, either "Rome condemned
La Salette" or "the 1851 approval covers the 1879 secret". This dataset keeps
them apart and carries the secrets controversy attributed and dated, never
resolved.

## The seers, briefly

- **Maximin Giraud** — unsettled later life (seminary studies, odd
  employments), returned to Corps, died there 1 March 1875. His secret was
  never published.
- **Mélanie Calvat** — in and out of convents in France, England and Italy;
  protected in Italy by Bishop Zola of Lecce; author of the expanding secret
  texts; died at Altamura (southern Italy) in December 1904 — sources disagree
  between 14 and 15 December.

## Glossary pointers

Shared terms are cross-linked with `[[term-id]]` markers against the pinned
`data/glossary-terms.json` — this repo currently uses `[[cdf-ddf]]` for the
Holy Office (predecessor of the CDF/DDF). Do not re-explain shared terms
inline.

## Verified primary anchors

Both Holy Office instruments were verified character-by-character against the
vatican.va AAS scans during the bootstrap (August 2026):

- AAS 7 (1915), pp. 594–595: "Decretum circa vulgo dictum «Secret de la
  Salette»", dated Rome, Holy Office, 21 December 1915, signed by the notary
  Aloisius (Luigi) Castellano.
- AAS 15 (1923), pp. 287–288: Holy Office decree of Feria IV, 9 May 1923,
  condemning "L'apparition de la très Sainte Vierge sur la sainte montagne de
  la Salette … Simple réimpression du texte intégral publié par Mélanie"
  (Société Saint-Augustin, 1922), approved by Pius XI the same day; the
  printed decree is dated 10 May 1923. (The AAS scan's OCR misprints the
  booklet title's year as "1845".)

## Sources not reachable from this session (August 2026)

Recorded so the next pass does not rediscover them:

- **Gallica (gallica.bnf.fr) returned 403** to this session's egress, both for
  the page view and for `.texteBrut`. That blocks the digitized full text of
  Rousselot's 1848 report, which is the primary source for the cures the
  episcopal commission examined. The reference cites the Google Books catalogue
  record instead, and says so in its `publisherNote`. Worth retrying via the
  `net-access` ladder.
- **catholic-hierarchy.org returned 300** for de Bruillard; the OMI World
  dictionary was used instead, which is a Catholic institutional source warm
  about him and labelled as such.
- **alpes-isere.com returned 403**, so the second attendance figure is cited to
  the French Wikipedia rather than to the departmental tourism board.
- Four dates rest on the French Wikipedia alone and stay flagged: the opening of
  the inquiry (19 July 1847), the commission's vote (13 December 1847), the
  spring (21 September 1846) and the first reported cure (17 November 1846).
  The diocesan archives of Grenoble would settle all four.
- **The 1879 consecration is a live disagreement, not an unverified date.** The
  French articles give 20 August, the English gives 21 August for the canonical
  coronation, and the congregation's own timeline gives 20–21 April, with
  18 August for the canonical approval of the Institute — a different act,
  recorded here as a separate event. Only the year is treated as verified.
