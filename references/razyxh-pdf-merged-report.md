# Razyxh MSNR PDF — Merged Deep Analysis (Drawing / Neatness / Skill Focus)

- **Source file:** `~/workspace/user/files/razyxh_pdf_12_pcma.pdf` — 46 pages, 10,792,334 bytes, PDF 1.4, A4 (595.276 × 841.89 pts), image-only (no extractable text), produced with pypdf, not encrypted.
- **Identity (from the pages):** author `TraFx_Trade`, distributed via Telegram `@Msnrpdf1` (watermark diagonal across every page). Screenshots stamped "TraFx_Trade dibuat dengan TradingView.com" (Indonesian: "made with TradingView.com"), Oct 2026, UTC+7. Chart language is Indonesian with standard SMC English vocabulary (MSS, BOS, IDM, SBR, ERL, LIQUIDITY, QML).
- **Method:** each page rendered with `pdftoppm -png -r 120` and read visually by four agents — pp.1–12 (Agent A), pp.13–23 (Agent B), pp.24–35 (Agent C), pp.36–46 (Agent D). Small labels re-checked at 200 dpi where noted. Uncertain readings are marked `[?]` / UNVERIFIED.
- **Per-chunk reports:** `razyxh-pdf-agentA-pages1-12.md`, `razyxh-pdf-agentB-pages13-23.md`, `razyxh-pdf-agentC-pages24-35.md`, `razyxh-pdf-agentD-pages36-46.md`.
- **This is a strategy / drawing test, not financial advice. Do not trade real money on the basis of these pages.**

## Headline verdict

This is a **different, far neater PDF than the 34-page Alchemist one** (same `@Msnrpdf1` distribution channel, same MSNR vocabulary, cleaner layout). Where Alchemist used ~26 labels per chart, coloured boxes, Fib circles with 11 levels, STDV channels and definition essays, this author uses **0–8 labels per page on the ladder pages, thin black 1 px lines, black/white candles, white space, and at most one coloured zone per page**. The neatness is a discipline, not a decoration: one idea per page, labels in empty space, never on candles.

Three sections, three instruments, three stories:

| Section | Pages | Instrument | Story |
|---|---|---|---|
| 1 | 1–3 | **NZDCAD** | One low at **0.79559** (240M → H1 → 60M), no trade, no entry |
| 2 | 4–23 | **XAGUSD** (silver) | One worked short: sell **71.143** → ~54.6, **+20,462.50 USD on 0.25 lot** (p.9 banner); Trade 16 journal card (p.20): sell, D1 > H1 > H4 > (M15), confluences CRT / CLEAR LIQUDITAS / NY AM, narrative IMB TO LIQ, result Win, opened and closed 29 Oct 2026 |
| 3 | 24–46 | **XAUUSD** (gold) | One worked short on the D/4H/1H ladder (target ERL ~3,976.17, p.27), the dense 240M master chart re-framed ~9 times (pp.29, 31–38, 40), and the phone-measured moves: **+737.484 points (+18.70%, 56 bars, 4w)** and **−687.471 points (−14.85%, 78 bars, 5w 4d)** |

**Replication verdict (same shape as the Alchemist verdict, for a different reason):** an agent can replicate the *style* exactly — thin black lines, black/white candles, ≤8 labels, one translucent zone, right-angle leaders, dotted references, the dashed diagonal with red ▼ / blue ◆, the measurement box + stats label — and the *confirmation events* (one wick touch, MSS take, green ✓, X for a failed level). It **cannot replicate the exact drawing end to end** from this PDF alone, because the decisions that make it specific — which candle is the PROFILE candle, which swings qualify, what counts as a "hit"/"validation", what IOFED / +TS / BOSa / BOSm / C.A / SSS mean, what the Fib-circle construction is, and what the entry trigger is on M15 — are never defined. The neatness is copyable; the *judgement* is not written down.

**Contrast with the Alchemist PDF** (`alchemist-pdf-merged/report.md`): the Alchemist book's core primitive is CRT + CE (one reference candle, 50% midpoint, APEX CE 4,333.78, TP1 4,445.19 touched / TP2 4,449.71 untouched). This book has **no CE, no APEX, no 50% line anywhere** — its core primitive is the **PROFILE candle + the confirmation stack** (MSS → minor validation → HIT MAJOR IMB → LIQ TO LIQ → ERL). The Alchemist book never states an HTF→LTF rule; this book states **two** of them in words (see §4). The Alchemist book has no trade record; this book has a journal card and a P&L banner. Both books share the same flaws: no backtest, no win rate, no risk %, no stop/target formula, no disclaimer, and documents that end abruptly (p.46 is a bare chart, no conclusion).

## 1. What the 46 pages are

- **pp.1–3 — NZDCAD:** p.1 NZDCAD 240M range (9 Oct 2026, 0.80076 / 0.79559); p.2 NZDCAD H1 mobile, the cleanest page in the book (2 objects, 0 labels, 0 prices — a horizontal line + a dashed diagonal with blue ↑ / red ↓ arrows); p.3 NZDCAD 60M stepped range (5 Oct 2026, 0.79705 / 0.79579 / 0.79559). The 0.79559 low is shared across 240M and 60M — HTF→LTF by price continuity only, no arrow or caption.
- **pp.4–12 — XAGUSD Daily/Monthly (the confirmation stack):** p.4 D, the three Indonesian text blocks teaching MSS → minor validation → HIT MAJOR IMB; p.5 D, the fullest label set (IDM, +TS, IOFED, LIQUIDITY, IDM INDOCEMENT ZONE, CLEAR VALIDASI, MSS, BOSa, ticks 4.5→2); p.6 M, the PROFILE (53.925, dotted line from the monthly low); p.7 D, HIT MAJOR IMB → LIQ TO LIQ → major target ~52.749; p.8 D, the full structure map (SBR, C.A, BOSa, BOSm, MSS / MARKET STRUKTUR SHIFT 💡); p.9 W1 phone, the trade proof (sell 71.143, 0.25 lot, +20,462.50 USD, current 54.604); pp.10–11 D, IDM → SHIFT (21 Aug) → same chart + teal projection box and "erl" line (28 Aug, 69.550) — the same bracket is labelled SHIFT 💡 on p.10 and MSS on p.11; p.12 D, the full fall to ERL (ticks 2→5).
- **pp.13–23 — XAGUSD, the single sell told in sequence:** p.13 D analysis chart (LIQUIDITY, +TS, IOFED, BOSs, CLEAR VALIDASI, 65.727 / 53.952); p.14 D1 phone, the order placed (SELL LIMIT zone 71.145–71.557, SL 71.557, TP 54.776 green dotted); p.15 D1 phone, the measured-move diagonal (high ~71.3 → low 54.604, red ▼ / blue ◆, zero words); p.16 D1 phone, the fill/rejection (wick to 71.143, long red candle to 66.388); p.17 D1, the diagonal again with a second red ▼ (rejection line); p.18 60M, the HTF→LTF rule page (two yellow zones, "validasi", mss, 52.758); p.19 240M, the majority view ("hit imb major", SSS diagonal, mss, "target majority" 52.707); p.20 Trade 16 journal card (Notion-style, Win); p.21 the diagonal again (no axis); p.22 D, the profile candle ("profile" line at the base of a tall white candle, ~52.7x); p.23 the diagonal + SSS + yellow zone, price fallen to 52.085.
- **pp.24–28 — XAUUSD, the ladder + bare downtrends:** p.24 downtrend with IDM + MSS (2 labels, 4 lines — the cleanest annotated page); p.25 XAUUSD D, D1 PROFILE (yellow highlight on the big black daily candle, ERL below); p.26 XAUUSD 60M, VALIDATION AFTER TAKE MSS (small yellow zone, green ✓); p.27 XAUUSD 240M, HIT IMB → TARGET MAJORITY IMB TO LIQ (ERL 3,976.17, confirmed at 200 dpi); p.28 bare downtrend, zero labels, 5 arrow markers, meaning unverified.
- **p.29 — GOLD 240M master chart (31 Oct, 08:51):** Fib-circle arcs + Quarterly Theory, ~25 labels, Premium Zone box, Q1–Q4 legend, STDV scale 2–5.5, BOS+ ×3, IDM, CLASSIC V, RBS, QML, IRL TAKEN, colour bar.
- **p.30 — ALCHEMIST cover (art page, not a chart):** anime swordsman, "ALCHEMIST / Inner Circle Trader", with the definition blocks (High Risk Confirmation, Draw on Liquidity list, Candle Range Theory, Premium Zone, SBR, BSL, SHIFT, BOS, KEY LEVELs, STDV uses, Quarterly Theory) partly covered by the artwork — the worst page for legibility.
- **pp.31–35 — GOLD 240M master, one layer per framing (31 Oct, 08:52–08:55):** p.31 Q1–Q4 legend + ERL definition + STDV box (+2–2.5); p.32 CLASSIC A sell model + DOL list in full + CRT definition + AMDX/XAMD variations + X marks (invalidation); p.33 discount zone / ORDER BLOCK / LAST LIQUIDITY; p.34 buy-side liquidity + QML + the three repeated text blocks; p.35 FAILURE / INVERSION / BUY STOPS / AKUMULASI — the only page that labels a failed move.
- **pp.36–38, 40 — GOLD 240M annotated master (31 Oct, 08:56):** p.36 Quarterly legend (fullest in the book, incl. Q2 "STOP-HUNT PHASE / KILLZONE MANIPULATION / KEY LEVEL SWEEP"); p.37 Premium Zone + High Risk Confirmation + Draw on Liquidity (clearest definitions; variations A-M-D / M-A-D); p.38 turtle sweep (TSS) + QML ×2 + STDV + ERL definition ("the end of Fibonacci circle"); p.40 CLASSIC A ×2 + ERL TAKEN + TRAP + SSS + LAST LIQUIDITY.
- **pp.39, 41, 43 — XAUUSD phone screenshots (the measurement pages):** p.39 H12, +737.484 (+18.70%, 56 bars, 4w), 3,943.876 → 4,681.360, 4 BUY flags; p.41, −687.471 (−14.85%, 78 bars, 5w 4d), 4,627.899 → 3,940.428, trendline fan; p.43, SELL ladder, 7 dashed SELL lines (5,415.461 / 5,375.580 / 4,888.984 / 4,769.709 / 4,695.401 / 4,491.899 / 4,396.553).
- **pp.42, 44–46 — bare trendline charts (no prices):** p.42 trendline fan (~6–8 dashed lines); p.44 two trendlines + one solid level; p.45 densest fan + SELL line with masked text `XXXXXXXX 60 IDR`; p.46 final page — one dashed trendline, nothing else. The document ends abruptly: no conclusion, no checklist, no disclaimer, no link or QR.

**Duplication:** ~46 pages hold roughly 15–18 distinct visuals. The GOLD 240M master is re-framed ~9 times (pp.29, 31–38, 40); the XAGUSD diagonal appears 4 times (pp.15/17/21/23); the XAGUSD D1 structure chart appears ~5 times (pp.4/5/7/8/12/13); the gold range ~3,940–4,680 is shown ~8 times in different framings (pp.36–46). Unlike the Alchemist duplicates (some byte-identical, zero new information), most re-framings here add one element — a new label, a new zone, a new marker — which is the book's teaching method. The padding is real but thinner.

## 2. The three worked trades

### Trade 1 — NZDCAD low 0.79559 (pp.1–3) — no trade

No entry, no stop, no target, no outcome. The section exists to show one level carried across timeframes by price alone: the 240M range low (p.1, 10 Oct) is the 60M low (p.3, 5 Oct) and the H1 level (p.2, undated). CONFIRMED prices: 0.80076 (dotted line, p.1 — what it is is UNVERIFIED), 0.79559 (range low, pp.1/3), 0.79579 (p.3), 0.79705 (p.3). Nothing else is priced.

### Trade 2 — XAGUSD sell 71.143 → 54.604, +20,462.50 USD at 0.25 lot (pp.4–23)

- **Entry:** sell 0.25 lot at **71.143** (p.9 phone banner: "Jual 0.25 lot pada 71.143"; p.16 shows the wick touching 71.143 and rejecting). The order was a SELL LIMIT zone of three red dashed lines, 71.143 / ~71.527 / 71.557 (p.14); on p.16 only two lines remain visible (71.143 / 71.556) — the middle line's disappearance is UNVERIFIED (removed, or hidden behind the P&L box).
- **Stop:** **71.556–71.557** (top red dashed line). The 0.001 difference between pp.14 and 16 is display rounding, not a different level.
- **Take profit (order):** **54.776**, green dotted line at the D1 swing low (pp.14/16).
- **Outcome shown:** **+20,462.50 USD** (p.9 banner, "XAG/USD TP SL / +20,462.50 USD"). Current price at the screenshot 54.604. Sanity check: 71.143 → 54.604 = 16.539 points; silver 1 standard lot = 5,000 oz, so 16.539 × 5,000 × 0.25 ≈ $20,674 — within ~1% of the stated $20,462.50 (difference consistent with a slightly different exit, e.g. the banner's 54.775). The P&L is roughly consistent, not independently verifiable: no order ticket, no exit price, no exit timestamp, no account.
- **Journal (p.20, Trade 16 ✅):** Open 29 Oct 2026, Close 29 Oct 2026, Pair XAGUSD, Direction "Sel" [Sell], "time frime — D1 > H1 > H4 > (M15)", Confluence "CRT | CLEAR LIQUDITAS | NY AM", "narativ — IMB TO LIQ", result "● Selesai" (finished), "win/lose — Win". No exit price, no lot size, no R:R, no P&L on the card — the SL/TP live only on the phone screenshots.
- **Unreconciled targets — flag, do not merge:** TP 54.776 (D1 order) vs diagonal end 54.604 (pp.15/17) vs "target majority" 52.707 (p.19) vs dotted line 52.758 (p.18) vs late low 52.085 (p.23) vs dotted line 53.952 (p.13). These are different targets on different timeframes/views. The PDF never says which one the trade actually exited at. The 0.051 gap between 52.707 and 52.758 is two different moments/views of the same target, or two different levels — flag it, do not merge them.
- **Unexplained:** "54.775" in the p.9 banner (possibly a TP price or a pip figure — do not use it as a level); "54.604" vs "54.776" as the exit; the lot size and USD P&L on p.16 are greyed out; the "BUY 0.0" / "SELL 0.0" figures on the phone pages are cut off — do not quote them as lot sizes.
- **Caption (p.9):** "jere tonggo editan lek" (Javanese slang, roughly "according to the neighbour, it's an edit") — a self-deprecating caption acknowledging the screenshot is edited/annotated, not a strategy label.

### Trade 3 — XAUUSD gold short + the two measured moves (pp.24–46)

- **The ladder short (pp.25–27):** D1 PROFILE sets the bias (yellow highlight on the big black daily candle, ERL below); H4 confirms (rally wicks into the yellow IMB zone, "HIT IMB", MSS taken, fall); H1 validates ("VALIDATION AFTER TAKE MSS", green ✓); target "TARGET MAJORITY IMB TO LIQ" at the ERL, price tag **3,976.17** (p.27, confirmed at 200 dpi). **No entry price, no stop, no lot size, no P&L, no exit is shown for this short.** It is a framework example, not a trade record.
- **Measured move up (p.39, H12 phone):** **+737.484 points (+18.70%, +737.484), 56 bars, 4w**, 3,943.876 → 4,681.360. Arithmetic verified: 4,681.360 − 3,943.876 = 737.484 ✓; 737.484 / 3,943.876 = 18.70% ✓. Four BUY flags (ladder entries) at 4,452.191, 4,315.232, 3,976.266, 3,961.134. No stop, no lot size, no dollar P&L, no entry timestamps.
- **Measured move down (p.41, phone):** **−687.471 points (−14.85%, −687.471), 78 bars, 5w 4d**, 4,627.899 → 3,940.428. Arithmetic verified: 4,627.899 − 3,940.428 = 687.471 ✓; 687.471 / 4,627.899 = 14.85% ✓. Three dashed red trendlines converge from the top high to the bottom low (fan). The two measurements cross-validate: the low ~3,940–3,944 and the high ~4,627–4,681 agree across both pages — the same gold range viewed from opposite ends.
- **SELL ladder (p.43):** seven dashed SELL lines — 5,415.461 / 5,375.580 / 4,888.984 / 4,769.709 / 4,695.401 / 4,491.899 / 4,396.553. Two are red-dashed (5,415.461, 4,491.899), five brown/black-dashed — the distinction is unexplained. No stop, no target, no outcome; price is shown falling through the ladder, but no fill or exit is marked. The top two levels sit ~500 points above the next level (4,888.984) with no explanation.
- **Price-tag caveat (master pages):** the right-axis tags on pp.29/32/34 are only partly legible even at 200 dpi and inconsistent with a single late-Oct gold price path (gold fell from ~4,400 mid-Oct toward ~3,976 by 30 Oct): p.29 "4,701.9[?]", p.32 "4,049.[?]", p.34 "4,354.7[?]". Treat them as UNVERIFIED — do not build levels off them without a live-chart check. Only p.27's 3,976.17 is confirmed.

## 3. Every key line — the master catalogue

Levels are single horizontal lines; zones are filled translucent rectangles/bands; touches are red dots; failures are X marks. Almost no 240M level carries a dollar price — the right axis on the master pages is the Fib-circle scale (2–5.5), not prices. Only the phone pages (pp.9, 14–16, 39, 41, 43) carry priced levels.

| # | Line / zone | Pages | How drawn | What it marks | Price (if any) |
|---|---|---|---|---|---|
| 1 | Range top / high (NZDCAD) | 1, 3 | Thin black horizontal | Range high / external liquidity | ~0.8007 (unlabelled) |
| 2 | Range bottom 0.79559 | 1, 3 | Thin black horizontal + pink band (p.1) | Range low — NZDCAD anchor | 0.79559 |
| 3 | Dotted level 0.80076 | 1 | Thin dotted horizontal | Unlabelled level above range top | 0.80076 |
| 4 | Dotted / dashed diagonal | 1, 2, 15, 17, 21, 23, 24, 28, 41–46 | Thin dotted/black dashed, low → high or high → low, red ▼ / blue ◆ at ends (phone pages) | Trendline / measured-move projection; on pp.15–23 the high→low leg itself | ~71.3 → 54.604 (XAGUSD); gold range ~3,940–4,681 |
| 5 | Stepped structure lines | 3, 4, 5, 7, 8, 10–12 | Thin black right-angle steps | Swing highs/lows carried right | — |
| 6 | MSS / mss / SHIFT 💡 | 4, 5, 7, 8, 10–13, 18, 19, 24, 26, 27, 31, 35, 38, 40 | Thin black/red horizontal bracket + 💡 (sometimes) | Market Structure Shift — the confirmation event | — |
| 7 | BOSa / BOSm / BOSs / BOS+ | 5, 8, 12, 13, 29, 31–36, 38, 40 | Thin black brackets at swing breaks | Break of Structure (subscripts a/m/s unexplained) | — |
| 8 | IDM / IDM INDOCEMENT ZONE | 5, 8, 10–13, 24, 29, 31–33, 35–38, 40 | Thin black bracket / horizontal | Inducement — trap leg / zone | — |
| 9 | IOFED line / red diagonal | 5, 13 | Thin black horizontal / thin red diagonal | "IOFED" — undefined, never expanded | — |
| 10 | LIQUIDITY line (red) | 5, 13, 32 | Thin red horizontal from a swing high | Liquidity pool above | ~3.5 tick (p.5) |
| 11 | +TS + red dot | 5, 8, 12, 13, 36, 37, 40 | Red dot at the highest wick | "+TS" — undefined (possibly Turtle Soup; do NOT expand) | — |
| 12 | SBR / RBS | 8, 12, 29, 33, 36, 40 | Thin black/red horizontal at a flipped level | Support-Becomes-Resistance / Resistance-Becomes-Support | — |
| 13 | C.A | 8, 12, 13, 32, 36 | Thin black horizontal at a swing high | "C.A" — undefined | — |
| 14 | PROFILE level (Monthly) | 6 | Dotted horizontal from the monthly low | Monthly PROFILE | 53.925 |
| 15 | D1 PROFILE (yellow) | 25 | Yellow translucent rectangle = one daily candle | The HTF profile candle / zone | — |
| 16 | profile (red line, D1) | 22 | Thin red horizontal at the base of a tall white candle | The D1 profile low | ~52.7 (tag illegible) |
| 17 | Yellow IMB zone | 4, 7, 18, 19, 26, 27 | Translucent yellow rectangle | Minor/major imbalance zone | — |
| 18 | Orange IMB / demand band | 5, 10, 11, 13 | Translucent orange rectangle at the lows | IMB / demand zone | — |
| 19 | Pink band (top) | 8, 24 | Thin translucent pink horizontal band | Unlabelled top zone / range high | — |
| 20 | Pink / cyan vertical bar | 5, 29, 31–35 | One vertical bar, pink top / cyan bottom | Session/time bar — construction unlabelled | — |
| 21 | Teal projection box | 11 | Large translucent teal rectangle, top = range high, bottom = ERL | Projected move / range to ERL | top ~69.5, bottom = ERL |
| 22 | "erl" line | 11, 12, 25, 27, 31, 38 | Thin black/red horizontal, full width (+ dotted extension) | External Range Liquidity — terminal target | 3,976.17 (p.27); ~52.749 (p.7) |
| 23 | Numbered tick scale | 5, 8, 12, 13, 29, 31–38, 40 | Small horizontal ticks, centre/right edge | A scale, most plausibly STDV — NOT labelled as such on pp.5/8/12/13 | 2, 2.5, 3, 3.5, 4, 4.5, 5, (5.5, 6 on master pages) |
| 24 | Major target line | 7 | Thin black horizontal, full width | Major LIQ TO LIQ target | ~52.749 |
| 25 | SELL LIMIT zone (red dashed ×3) | 14, 16 | Red dashed horizontals | Sell-limit entry zone | 71.143 / ~71.527 / 71.557 |
| 26 | SL | 14, 16 | Top red dashed line | Stop loss | 71.556–71.557 |
| 27 | TP (green dotted) | 14, 16 | Green dotted horizontal at the swing low | Take profit | 54.776 |
| 28 | Dotted level 53.952 | 13 | Red dotted horizontal | Unlabelled level | 53.952 |
| 29 | Top yellow band (supply / major IMB) | 18, 19 | Yellow filled rectangle, full width | HTF supply / major imbalance zone; "hit imb major" | — |
| 30 | Bottom yellow rectangle ("validasi") | 18 | Yellow filled rectangle at the base of the V | Validation zone | — |
| 31 | SSS diagonal (red) | 19, 23, 37, 40 | Thin red diagonal, top-left high → mid-chart | SSS — expansion unverified | — |
| 32 | target majority (red line) | 19 | Thin red horizontal at the bottom | H4 majority target | 52.707 |
| 33 | Dotted line 52.758 / 52.085 | 18 / 23 | Dotted horizontal | Unlabelled levels | 52.758 / 52.085 |
| 34 | Fib-circle arcs (2–3) | 29, 31–38, 40 | Very thin black arcs, page-spanning, centre far off-page | Fib circle boundary; STDV numbers sit on the arcs | Scale 2–5.5 (not prices) |
| 35 | SINGLE LIQUIDITY (red) | 29 | Thin red horizontal at the top-left high | Single liquidity / sweep high | — |
| 36 | OPEN CLOSE (yellow) | 29 | Yellow rectangle, upper right | Open/close level zone | — |
| 37 | CLASSIC V (red dot) | 29, 34 | Red dot on the V low | Classic V buy touch point | — |
| 38 | QML / QUASIMODO LEVEL (red dots) | 31, 32, 34, 38 | Thin red/gold horizontal + red dots; yellow band on p.38 (×2) | Quasimodo level | — |
| 39 | RANGE LIQUIDITY | 31, 32 | Thin horizontal at a swing high | Range liquidity pool | — |
| 40 | ORDER BLOCK (yellow) | 33 | Yellow rectangle over a basing range | Order block zone | — |
| 41 | LAST LIQUIDITY (red + dot) | 33, 40 | Thin red horizontal + red dot at the low | Last liquidity pool | — |
| 42 | TBS^ / TSS [TURTLE BODY SWEEP] | 32, 35, 38 | Short bracket at the sweep | Body sweep (not wick) of a level | — |
| 43 | X marks (invalidation) | 32 | Small black X at failed levels | Invalidated levels | — |
| 44 | BUY STOPS (yellow) / AKUMULASI | 35, 38 | Yellow translucent rectangle at the high | Buy-stops pool / accumulation | — |
| 45 | INVERSION (orange) | 35, 38 | Orange translucent rectangle | Inversion / reversal zone | — |
| 46 | FAILURE (text) | 35 | Text label at the failed peak | The failed high | — |
| 47 | BSL / BUY SIDE LIQUIDITY (red) | 30, 34, 35, 37 | Thin red horizontal at the high | Buy-side liquidity pool | — |
| 48 | SEL SIDE LIQUIDITY | 36–38, 40 | Horizontal line at equal lows | Sell-side liquidity pool | — |
| 49 | KEY LEVELs / KEY LEVEL (gold/red) | 29, 31–38, 40 | Thin gold/red horizontal, red dot on the wick | The key level — the decision line | — |
| 50 | OCL (Open Close Level) | 30, 36–38, 40 | Short horizontal + red dot at a swing | Open/close level of the key candle | — |
| 51 | TRAP | 40 | Small yellow vertical band at a false low | Trap (false low before the final fall) | — |
| 52 | ERL TAKEN | 40 | Horizontal line, labelled as taken | External liquidity already taken | — |
| 53 | FAKE BOI! | 38 | Red dot + label at the false break | Fake breakout | — |
| 54 | Colour bar (grey/red/green/blue) | 29, 31–35 | Short 4-segment horizontal bar | Quarterly / DAILY CIRCLE bar (unlabelled) | — |
| 55 | BUY dashed lines + red flags | 39 | Brown/orange dashed horizontals, red-flag markers | Buy levels (ladder) | 4,452.191 / 4,315.232 / 3,976.266 / 3,961.134 |
| 56 | Measurement box (blue, filled) | 39 | Light-blue translucent rectangle + black stats label | Measured move (+18.70%) | 3,943.876 → 4,681.360 |
| 57 | Measurement box (outline only) | 41 | Dashed rectangle, no fill + black stats label | Measured move (−14.85%) | 4,627.899 → 3,940.428 |
| 58 | SELL dashed lines + red flags | 43 | Dashed horizontals (2 red, 5 brown/black), red-flag markers | Sell levels (ladder) | 5,415.461 / 5,375.580 / 4,888.984 / 4,769.709 / 4,695.401 / 4,491.899 / 4,396.553 |
| 59 | Trendline fan (dashed) | 41, 42, 44, 45 | 3–8 dashed diagonal lines from successive highs to one low | Trendline fan (confluence of trendlines) | — (no prices pp.42/44–46) |

## 4. HTF → LTF frameworks as written (verbatim)

This PDF states **two different ladders** — one in the silver section, one in the gold section. They are not the same rule. Do not merge them.

### Ladder 1 — silver (pp.4, 6, 7)

> **MN > PROFILE / W1 > MAJORITY / D1 > MINORITY**

- Monthly gives the PROFILE, Weekly gives the MAJORITY (bias), Daily gives the MINORITY (the entry timeframe). "PROFILE" is defined on p.6 by the dotted line from the monthly low (53.925).
- The sequence (reconstructed from the Indonesian text blocks on p.4, repeated on pp.6–7): take MSS → minor validation (IMB to LIQ) → wait for HIT MAJOR IMB → narrative becomes LIQ TO LIQ → target the major line (ERL).
- Verbatim text blocks (p.4, Indonesian as written; translations are the agents'):
  - "VALIDASI MINOR SELESAI / DISINI SELANJUTNYA TUNGGU / HIT MAJOR IMB" — "Minor validation is complete; here, next, wait for a hit of the major IMB."
  - "SETELAH TAKE MSS / BUTUH VALIDASI MINOR / YAITU IMB TO LIQ" — "After taking the MSS, minor validation is needed, namely IMB to LIQ."
  - "HIT MAJOR IMB / DAN TERTS, DISINI / NARATIVNYA LIQ TO LIQ" (p.7) — "Hit major IMB and [terts — likely 'tertest'/retest, clipped], here the narrative is LIQ TO LIQ."
  - "INI TARGET MAJOR / NARATIV LIQ TO LIQ" (p.7) — "This is the major target, narrative LIQ TO LIQ."

### Ladder 2 — gold (pp.25, 27; also pp.18, 19, 22 in the silver section)

> **D1 > PROFILE / H1 > MINORITY + MSS / H4 > MAJORITY + CONFIRM**

- Printed verbatim on pp.25 and 27 (gold), and in the shorter form **D1 > PROFILE / H1 > MINORITY / H4 > MAJORITY (M15)** on pp.18, 19, 22 (silver). The journal (p.20) gives the chain as **D1 > H1 > H4 > (M15)**.
- Meaning as drawn: D1 defines the profile (the D1 candle, p.22 "profile" line at its base; the D1 sell-limit zone / TP, pp.14/16); H1 is the minority context and provides the MSS ("VALIDATION AFTER TAKE MSS", p.26); H4 is the majority — the tradable structure ("hit imb major" → SSS → mss → "target majority" 52.707, p.19); M15 is execution.
- **H1 and M15 are never drawn in the silver section** (no H1 page, no M15 page in pp.13–23) and **no M15 chart appears anywhere in the 46 pages**. The roles are named but never shown — flag it.
- The gold ladder as drawn (pp.25 → 27 → 26): D1 PROFILE (highlight the biggest daily candle yellow, mark ERL below) → H4 MAJORITY + CONFIRM (wait for the wick to touch the yellow IMB zone, "HIT IMB", MSS taken) → H1 MINORITY + MSS (take the MSS, then validation in a small yellow zone, green ✓) → target "TARGET MAJORITY IMB TO LIQ" (the ERL). Note the file order is D (p.25) → H4 (p.27) → H1 (p.26) by timestamp (17:59 → 17:54 → 17:55); the ladder reads D1 → H4 → H1.
- **What changes when you drop timeframes (observable only):** on Monthly there is 1 line and 1 word; on Weekly 1 diagonal and 1 trade banner; on Daily 5–8 labels and 1 zone; on the gold ladder D1 has 1 zone + 1 line, H4 has 1 zone + 2 lines + 2 leader lines, H1 has 1 small zone + 2 lines + a ✓. The lower the timeframe, the more precise the drawing — but the style never changes (thin black lines, white space, one zone max). On 240M the drawing is structural (labels, Quarterly legend, Fib arcs, definition boxes); on H12/phone it is executional (dashed lines + price tags + flags only, no labels, no legend).
- **What is missing in both ladders:** no price links the charts (no shared price tag across MN/W1/D1 or D/H4/H1); no rule for when to drop (what D1 event triggers the H4 check, what H4 event triggers the H1 check); no entry trigger on the lowest timeframe (which candle, wick vs close); no stop/target numbers. The sequences are frameworks with named steps, not procedures with thresholds. The Alchemist PDF never stated any of this — that is this book's main advance over it.

## 5. Every confirmation used (in order)

The confirmation stack as the PDF presents it (silver ladder, pp.4–7, then gold ladder, pp.25–27). No confirmation has a numeric threshold — every one is a label on a chart or a tag in the journal.

| # | Confirmation | Where | What it is | Rule stated? |
|---|---|---|---|---|
| 1 | MN / D1 PROFILE | pp.6, 22, 25 | The monthly/daily profile level — the HTF bias anchor | No — "largest candle" is the visible rule; exact anchor (low vs close vs body) unstated |
| 2 | W1 / H4 MAJORITY | pp.4, 18, 19, 27 | The weekly/4H direction is the majority bias | No |
| 3 | CRT (Candle Range Theory) | p.20 (journal) | The range (one candle's high–low) | No — named only; definition on pp.32/34/37: "A CONCEPT THAT ANALYZES THE PRICE RANGE OF A SINGLE CANDLE [USUALLY THE DAILY OR WEEKLY] TO DETERMINE BALANCE AREAS AND POTENTIAL FUTURE PRICE MOVEMENT" |
| 4 | CLEAR LIQUIDITY / CLEAR LIQUDITAS | pp.13, 20 | Liquidity clearly swept / clear validation | No — "CLEAR VALIDASI" is a label, not a threshold |
| 5 | NY AM | p.20 (journal) | New York AM session | No — session only, no clock times |
| 6 | Take MSS / SHIFT 💡 | pp.4, 8, 10–13, 18, 19, 24, 26, 27 | The market structure shift — first trigger | No — no close rule; SHIFT and MSS are the same event (pp.10–11 relabel the identical bracket) |
| 7 | Minor validation: IMB to LIQ | p.4 | After the MSS, price must validate the minor imbalance-to-liquidity move | No — what counts as a "hit"/"validation" undefined |
| 8 | HIT MAJOR IMB | pp.4, 7, 19, 27 | Price hits the major imbalance zone | As drawn: **one wick touch is enough** (p.27, the rally wick touches the yellow zone and price falls) — no body-close requirement, no second tap |
| 9 | Narrative flips to LIQ TO LIQ | pp.7, 20, 27 | Once major IMB is hit, the trade is liquidity-to-liquidity | No |
| 10 | Target the major line (ERL) | pp.7, 11, 12, 25, 27 | Terminal objective is the external range liquidity line | No — ERL defined on p.31/38 as liquidity outside the main range, "the arc of Fibonacci circle" / "the end of Fibonacci circle" |
| 11 | IDM (inducement) | pp.5, 8, 12, 13, 24, 29 | Trap swing before the move | No |
| 12 | BOS / BOSa / BOSm / BOSs / BOS+ | pp.5, 8, 12, 13, 29 | Break of structure | No — subscripts unexplained |
| 13 | SBR / RBS | pp.8, 12, 29, 33, 36 | Support-becomes-resistance / resistance-becomes-support | No |
| 14 | SSS | pp.19, 23, 37, 40 | Red diagonal (sell-side sweep family) | No — never expanded |
| 15 | validasi / CLEAR VALIDASI (✓) | pp.13, 18, 26 | Zone validation — green ✓ on p.18, green ✓ box on p.26 | No — shown (the ✓, the rejection candle on p.16, the collapse after "hit imb major"), never written as a rule |
| 16 | Tap-and-reject | p.16 | Wick to 71.143 then a long red candle | Shown in sequence, no rule |
| 17 | Diagonal rejection (×2) | p.17 | Price rejected at the diagonal twice | Shown, no rule |
| 18 | Red-dot touch | pp.29, 31–34, 36–38 | The dot records the exact touching candle | No wick-vs-body rule |
| 19 | X mark (invalidation) | p.32 | A level that failed | No invalidation rule given |
| 20 | TBS / TSS (turtle body sweep) | pp.32, 35, 38 | The sweep was by candle *body*, not wick | Partial — the only wick-vs-body distinction in the book |
| 21 | CLASSIC V / CLASSIC A | pp.29, 32, 34, 37, 40 | The V/A shape itself is the entry model | No confirmation candle drawn |
| 22 | FAILURE | p.35 | The peak that did not hold — labelled, not hidden | Labelled outcome, not a measured one |
| 23 | High Risk Confirmation | pp.30, 31, 34, 35, 37, 38 | Early entry before a full sweep, on wick reaction/inducement; high reward, low confirmation | Concept only — no wick-size threshold |
| 24 | Measurement (points / % / bars) | pp.39, 41 | Blue/outlined rectangle + black stats box | Yes — the numbers ARE the confirmation of the move |

**The sequence in one line (silver):** MN PROFILE → W1 MAJORITY → D1 MINORITY → take MSS → minor validation (IMB to LIQ) → wait HIT MAJOR IMB → LIQ TO LIQ → target ERL.
**The sequence in one line (gold):** D1 PROFILE → H4 MAJORITY + CONFIRM (HIT IMB) → H1 MINORITY + MSS (VALIDATION AFTER TAKE MSS) → TARGET MAJORITY IMB TO LIQ.

## 6. How each zone is captured

- **A zone is a single translucent fill, one per page, edges aligned to candle extremes.** Zones: yellow IMB (pp.4, 7, 18, 19, 26, 27), orange IMB/demand band (pp.5, 10, 11, 13), pink band (pp.8, 24), teal projection box (p.11), yellow QML bands (p.38 ×2), ORDER BLOCK (p.33), BUY STOPS (pp.35, 38), INVERSION (pp.35, 38), D1 PROFILE (p.25 — the zone IS the candle). No zone has a written width rule; the edges sit on a swing high/low or a candle body edge, by eye. The teal box (p.11) is the only zone that is also a *time* projection (it spans future bars, not past price action).
- **Identification:** a zone is born from a prior event — an imbalance left by a displacement leg (IMB), an inducement sweep (IDM zone), the range itself (teal box = range high to ERL), or a candle (PROFILE zone = the big daily candle; ORDER BLOCK = the basing candles; QML zone = the Quasimodo candles). The author never writes a zone rule; the zone *is* the event's footprint.
- **Validation:** the only validation shown is **price returning to the zone and the structure that follows** — the minor zone on p.4 is validated when price leaves it and the MSS holds; the major IMB on p.7 is validated by the hit itself ("HIT MAJOR IMB") followed by the fall to the major target; on p.27 one wick touch validates. No tap count, no wick-vs-body rule (except TBS/TSS), no numeric threshold anywhere in the 46 pages.
- **Zone vs level vs touch:** a level is one thin line (a price); a zone is a filled rectangle (a price *area* with visible height); a dot is where a touch is *recorded* (the exact candle). The distinction is purely visual — the PDF never states it in words. The entry/order is placed *inside a band* (the sell-limit zone is three dashed lines, 71.143–71.557 — a band, not a line); a level is where a break or target is *measured* (BOS/MSS/target majority are single lines).
- **Colour varies without a rule:** the bottom IMB zone is yellow on pp.4/7 and orange on pp.5/10/11. Same zone, different colour — colour is presentation, not meaning, in this PDF. The one exception is the *grammar*: yellow = zone/imbalance, red = MSS/liquidity sweep, pink/cyan = session/vertical bars — consistent across the master pages.
- **Measurement boxes are not zones:** the blue rectangle on p.39 and the dashed rectangle on p.41 measure a *completed* move (points / % / bars / duration) — they do not mark an area to trade from. Do not confuse them with trading zones.

## 7. The definition blocks (verbatim, as printed)

These are the book's reference text, repeated across the master pages. Spelling is as printed — do not silently correct it.

**Premium Zone (top-left box, pp.29, 32, 35, 37):**
> • PREMIUM ZONE / • PRICE ABOVE / • FOCUS SELL / • FVG + IDM / • SUPPLY LIQUIDITY HIGH SWEEP / • CLEAN IDM + STRUCTURE BUY
> (p.37 variant: "CLEAR IDM + STRUCTURE BUY" — both readings appear; flag, do not merge.)

**Discount Zone (p.33):**
> • DISCOUNT ZONE / • PRICE BELOW / • FOCUS BUY / • FVG + IDM / • DEMAND LIQUIDITY HIGH SWEEP / • CLEAN IDM + STRUCTURE SELL [sic — as read]

**High Risk Confirmation (pp.30, 31, 34, 35, 37, 38 — repeated verbatim):**
> HIGH RISK CONFIRMATION / HIGH RISK CONFIRMATION IS EARLY ENTRY SIGNAL TAKEN BEFORE FULL MARKET ENTRY SIGNAL TAKEN BEFORE FULL MARKET ST [truncated in the original] / IT IS USUALLY BASED ON LIQUIDITY SWEEPS, WICK REACTION, OR INDUCEMENT WITH A HIGH RISK+ EARLY ENTRY / HIGH REWARD, LOW CONFIRMATION
> (p.37 cleanest reading: "HIGH RISK CONFIRMATION IS EARLY ENTRY SIGNAL TAKEN BEFORE FULL MARKET SWEEP. IT IS USUALLY BASED ON LIQUIDITY SWEEPS, WICK REACTION, OR INDUCEMENT WITH A HIGH RISK-REWARD, LOW CONFIRMATION.")

**Draw on Liquidity (pp.30, 32, 34, 37):**
> • DRAW ON LIQUIDITY / HERE IS THE LIST OF DRAW ON LIQUIDITY [DOL] LEVELS / DRAW ON LIQUIDITY LIST: / PDH: PREVIOUS DAILY HIGH / PDL: PREVIOUS DAILY LOW / PWH: PREVIOUS WEEKLY HIGH / PWL: PREVIOUS WEEKLY LOW / PMH: PREVIOUS MONTHLY HIGH / PML: PREVIOUS MONTHLY LOW
> (p.37's prefixes read "21H / 21L / 21M / 21W" at 120 dpi — likely PDH/PDL/PWH/PWL/PMH/PML misread; do not quote the p.37 prefixes as certain. p.38 confirms PDL = PREVIOUS DAILY LOW and PWL = PREVIOUS WEEKLY LOW.)

**Candle Range Theory (pp.30, 32, 34, 37):**
> CANDLE RANGE THEORY: / A CONCEPT THAT ANALYZES THE PRICE RANGE OF A SINGLE CANDLE [USUALLY THE DAILY OR WEEKLY] TO DETERMINE BALANCE AREAS AND POTENTIAL FUTURE PRICE MOVEMENT

**Quarterly Theory (pp.29, 31–35, 36–38, 40):**
> QUARTERLY THEORY IS A CONCEPT IN TRADING ESPECIALLY IN (SMC/ICT) [THAT] DIVIDES PRICE MOVEMENT INTO FOUR PARTS (QUARTER) [BASIC CONCEPT PRICE] WILL MOVE WITHIN A RANGE AND THAT RANGE IS DIVIDED INTO SECTIONS *Q1 *Q2 *Q3 *Q4 HIGH
> Q1 • ACCUMULATION / • MARKET CONSOLIDATION / • NO CLEAR STRUCTURE / • UNCLEAR STRUCTURE / • DIFFICULT TO READ
> Q2 • MANIPULATION / • TRANSITION AREA / • MARKET CAN BE IN THE QT KZ / • NOT YET STRONG DIRECTION / • KILLZONE MANIPULATION / • STOP-HUNT PHASE (p.36) / • KEY LEVEL SWEEP (p.36)
> Q3 • DISTRIBUTION / • FIND KEY LVL ENTRY / • SECOND ENTRY CONFIRMATION / • FIRST ENTRY W/ MSNR / • DOUBLE CONFIRMATION / • START IN PREMIUM AREA (pp.29/33) — vs "START IN DISCOUNT" (p.31) and "TRY IN FIRST ENTRY W/ MSNR" (p.31)
> Q4 • REVERSAL OR CONTINUATION / • [DISCOUNT ZONE] (pp.29/31) / • STRUCTURAL CONFIRMATION / • ENTRY TYPE / • TARGET EXPANSION / • EXPENSIVE PRICE / • SUITABLE FOR BUY (p.31) — vs "(PREMIUM ZONE)" (p.36)
> Two model variations (p.32/34): **[AMDX]** A - ACCUMULATIONS / M - MANIPULATIONS / D - DISTRIBUTIONS / X - EXPANSIONS; **[XAMD]** X - EXPANSIONS / A - ACCUMULATIONS / M - MANIPULATIONS / D - DISTRIBUTIONS. (p.37 lists the variations as A-M-D and M-A-D, plus R = REVERSALS. No rule for which ordering applies when — BLOCKED.)
> Price-quartile gloss (Alchemist pp.23–24, echoed here only by the legend): Q1 0–25% [Discount Deep], Q2 25–50%, Q3 50–75%, Q4 75–100% [Premium Zone], 50% = equilibrium, buy below 50% / sell above 50%. **This PDF never gives the quartile price formula** — the legend is words only, no High/Low anchors are marked, so quartile prices cannot be computed from this book alone.

**ERL definition (pp.31, 38):**
> EXTERNAL RANGE LIQUIDITY / [LIQUIDITY] THAT IS OUTSIDE THE MAIN RANGE OF THE MARKET / THE ARC OF FIBONACCI CIRCLE
> ERL [EXTERNAL RANGE LIQUIDITY] / IS LIQUIDITY THAT IS OUTSIDE THE MAIN RANGE OF THE MARKET / THE END OF FIBONACCI CIRCLE

**STDV (pp.30, 31, 32, 34, 38):**
> IN TRADING STDV +2-2.5 / STDV IS USED FOR: / • MEASURING VOLATILITY / • SETTING STOP LOSSES / • INDICATORS LIKE / • BOLLINGER BANDS / • VOLATILITY BANDS
> "STDV +2-2.5" is a range (2–2.5), not a single value and not a formula. The scale on the arcs runs 2 / 2.5 / 3 / 3.5 / 4 / 4.5 / 5 / 5.5 / (6). No anchor, no lookback, no price-to-STDV mapping anywhere in the 46 pages.

**MSS (p.8):** "MSS / MARKET STRUKTUR SHIFT 💡" — spelling "STRUKTUR" as printed, everywhere.

## 8. Drawing style end to end — the visual workflow (reconstructed, not numbered in the PDF)

1. Open the HTF chart and find the PROFILE candle (the largest daily/monthly candle); highlight it yellow; mark the ERL below the range (pp.6, 22, 25).
2. Mark structure on Daily: IDM → BOS → MSS (p.13); mark the liquidity pool above (LIQUIDITY line, +TS sweep high) and the inducement zone; note "CLEAR VALIDASI" when price clears the validation level.
3. Place the order on D1: SELL LIMIT zone (three red dashed lines, 71.143–71.557), SL above at 71.556, TP at the swing low 54.776 (green dotted) (pp.14/16).
4. Draw the measured-move diagonal: dashed line from the swing high (red ▼) to the swing low (blue ◆); watch for rejections on it (p.17's second ▼) (pp.15/17/21/23).
5. Drop to H4 (240M): mark the major imbalance zone (yellow band), wait for "hit imb major", draw the SSS diagonal, confirm with mss, target the "target majority" line (52.707) (p.19).
6. Check the 60M view (p.18): the same hierarchy header, the top yellow supply band (✓ = tapped), the bottom "validasi" zone. Identify the D1 profile candle (p.22).
7. Drop to H1/60M (gold ladder): mark the MSS line at the equivalent swing; wait for the take, then for validation — price returning to/holding a small yellow zone after the take; tick it green (✓) when it holds (p.26).
8. Record the trade in the journal (p.20): pair, direction, TF chain D1>H1>H4>(M15), confluences (CRT, CLEAR LIQUIDITY, NY AM), narrative (IMB TO LIQ), result (Win).
9. On the 240M master, add the reference layer only when needed: Fib-circle arcs (2–3 thin black arcs, page-spanning), STDV numbered scale on the arcs (2–6), Q1–Q4 legend, BOS brackets at each break, red dots at each touch, X marks at each failed level, and the three text blocks (Premium Zone, High Risk Confirmation, Draw on Liquidity / Quarterly Theory) placed in empty space, never on candles (pp.29/31–35).
10. Manage by the labels: FAILURE at a peak that did not hold, INVERSION where structure inverted, LAST LIQUIDITY at the final pool, ERL TAKEN once the target is hit (pp.35, 40).
11. Measure a completed move: one rectangle + one black stats box reading `points (% , ±points)` on line 1 and `bars, duration` on line 2 (pp.39, 41).

Steps 1–8 are the order the pages imply (analysis → order → diagonal → H4 → 60M → profile → journal). The PDF itself contains no numbered steps — this sequence is an inference from page order and the journal's TF chain, and the trigger (what exactly counts as a "hit", a "validation", a "shift") is undefined.

## 9. CONFIRMED vs UNVERIFIED vs CONTRADICTED register

### CONFIRMED (read directly off the pages)

- Identity: TraFx_Trade / @Msnrpdf1, Oct 2026, UTC+7, Indonesian annotations, TradingView + mobile broker screenshots.
- Instruments per range: NZDCAD pp.1–3 only; XAGUSD pp.4–23; XAUUSD pp.24–46. (The brief's "NZDCAD Oct 2026" describes only the first 3 pages.)
- Both HTF→LTF ladders verbatim (see §4); the confirmation stack (see §5); the DOL list PDH/PDL/PWH/PWL/PMH/PML; the CRT definition; the High Risk Confirmation, Premium Zone, Discount Zone, ERL and STDV +2–2.5 texts (see §7).
- XAGUSD trade: sell 71.143, 0.25 lot, SL 71.556–71.557, TP 54.776, +20,462.50 USD banner, current 54.604; Trade 16 journal (29 Oct 2026, Win, confluences CRT / CLEAR LIQUDITAS / NY AM, narrative IMB TO LIQ).
- XAUUSD moves: +737.484 (+18.70%, 56 bars, 4w, 3,943.876 → 4,681.360) ✓ and −687.471 (−14.85%, 78 bars, 5w 4d, 4,627.899 → 3,940.428) ✓ — arithmetic verified, and the two ranges cross-validate each other.
- Gold ladder target: ERL 3,976.17 (p.27, 200 dpi). Monthly PROFILE 53.925 (p.6). NZDCAD low 0.79559 (pp.1/3).
- BUY ladder (p.39): 4,452.191 / 4,315.232 / 3,976.266 / 3,961.134. SELL ladder (p.43): 5,415.461 / 5,375.580 / 4,888.984 / 4,769.709 / 4,695.401 / 4,491.899 / 4,396.553.
- Visual grammar: yellow zone, thin black/red level line, red dot = touch, X = failed level, green ✓ = validated, 2–3 thin black Fib arcs, STDV numbers on the arcs, dashed = measured/projection, solid = confirmed level, dotted = reference.
- "INDOCEMENT" is the author's consistent spelling (pp.5, 10, 11, 13) — not a one-off typo. "STRUKTUR" likewise. Quote as written.
- The document ends at p.46 with no conclusion, checklist, disclaimer, link or QR.

### UNVERIFIED (visible but undefined, or unreadable)

- **Undefined abbreviations (never expanded anywhere in 46 pages):** IOFED, +TS, BOSa, BOSm, BOSs, C.A, SSS, FS, IQFBD, EQE, BOI, L.T4/L.T8, CLA, TS^, +7B^, TOFED, C.V, "54.775" (p.9 banner), "60 IDR" (p.45), "XXXXXXXX" (p.45, masked). Do not expand any of them.
- **Zone edges:** no yellow zone or red line on the master pages carries a price tag; edges are by eye on the defining candles' wicks/bodies.
- **PROFILE anchor:** low vs close vs body of the profile candle — unstated (same gap as the Alchemist CRT candle).
- **Validation thresholds:** what counts as a "hit", a "validation", a "shift", a "rejection" — no tap count, no wick/body rule (except TBS/TSS), no time-in-zone rule.
- **Fib circle:** arcs visible, no centre, radius, ratios or anchors; the scale (2–5.5) is not mapped to prices.
- **STDV:** "+2-2.5" is a range citation with a use-list, no formula, anchor or lookback (same blocker as the Alchemist PDF).
- **Tick scale direction:** p.5 runs 4.5 (top) → 2 (bottom); pp.8/12 run 2 (top) → 5 (bottom). Either two different scales or an inconsistency in the collage. Do not treat the ticks as one scale.
- **Pink/cyan vertical bars and the grey/red/green/blue colour bar:** appear on pp.5, 29, 31–35 with no legend anywhere — meaning UNVERIFIED (likely session/quarter bars, but that is inference). Same for the bottom segment bar on p.1.
- **Price tags on master pages:** p.29 "4,701.9[?]", p.32 "4,049.[?]", p.34 "4,354.7[?]" — partly legible, mutually inconsistent, UNVERIFIED.
- **p.22 price tag** (~52.7x) illegible at 120 dpi; p.36 "0,466.2" unreadable as a price; p.25 right-axis tag cropped/illegible; p.26 tag illegible.
- **H1 and M15 never drawn; no M15 chart anywhere.** The TF chains name them; the PDF shows D1, 60M, 240M (silver) and D/240M/60M (gold) only.
- **Which target the XAGUSD trade actually exited at** (54.776 vs 54.604 vs 52.707 vs 52.758 vs 52.085) — unstated; the journal says only "Win".
- **Entry trigger, stop distance, lot size, risk %, R:R, session times** — none anywhere in the 46 pages. The "BUY 0.0" / "SELL 0.0" figures are cut off; do not quote them as sizes.
- **Arrow markers** on pp.28/42/44–46 (red/blue triangles) — no legend; meaning unverified. The 2 red-dashed vs 5 brown-dashed SELL lines on p.43 — distinction unexplained.
- **Dates are not in page order:** p.3 is 5 Oct, p.1 is 10 Oct; p.10 is 21 Aug, p.11 is 28 Aug, pp.4–8/12 are 23 Oct. The PDF is a collage, not a chronological journal — do not read page order as time order.
- **Watermark:** `@Msnrpdf1` is watermarked diagonally across every chart and obscures some candle/label areas. Text under the watermark is UNREADABLE where it crosses.

### CONTRADICTED (flag, do not resolve)

1. **Q3 gloss:** "START IN PREMIUM AREA" (pp.29/33) vs "START IN DISCOUNT" (p.31) vs "TRY IN FIRST ENTRY W/ MSNR" (p.31). A learner copying either gloss will be wrong half the time.
2. **Q4 gloss:** "(DISCOUNT ZONE)" + "EXPENSIVE PRICE / SUITABLE FOR BUY" (p.31) vs "(PREMIUM ZONE)" (p.36) vs "[PREMIUM ZONE]" (p.33). Q4 is glossed both discount and premium in different legend blocks.
3. **Q2 box (Alchemist p.5, echoed in this book's legend structure):** "MARKET SELL AREA" and "IN PREMIUM ZONE FOCUS ON BUY AREA" in the same box.
4. **Two ladders:** MN > PROFILE / W1 > MAJORITY / D1 > MINORITY (silver) vs D1 > PROFILE / H1 > MINORITY + MSS / H4 > MAJORITY + CONFIRM (gold). Different HTF anchors for different sections — do not present one as the book's single rule.
5. **Quarterly variations:** AMDX / XAMD (pp.32/34) vs A-M-D / M-A-D (p.37). No rule for which ordering applies when.
6. **Tick-scale direction flips** (p.5 vs pp.8/12) — see UNVERIFIED above.
7. **Three-plus lows for the same XAGUSD sell-off** (54.776 / 54.604 / 52.707 / 52.758 / 52.085) — never reconciled.
8. **Premium Zone box wording:** "CLEAN IDM + STRUCTURE BUY" (pp.29/32/35) vs "CLEAR IDM + STRUCTURE BUY" (p.37).
9. **SL 71.556 vs 71.557** (pp.16 vs 14) — 0.001 apart; treated as display rounding, not a different level, but flag it.
10. **SELL zone line count:** three dashed lines on p.14 (71.145/71.527/71.557) but only two on p.16 (71.143/71.556) — the middle line disappears.
11. **Zone colour changes without a rule:** yellow on pp.4/7, orange on pp.5/10/11 for the same IMB zone.
12. **SHIFT vs MSS for the same event:** p.10 "SHIFT 💡" vs p.11 "MSS" on the identical bracket. The two terms are interchangeable here — do not treat them as different confirmations.
13. **"Buyside liquidity is a collection of sell order"** (Alchemist p.13) — non-standard vs ICT (buyside = buy-stop orders above highs); flag, do not silently correct. This book does not repeat the claim, but shares the vocabulary.

## 10. Replication capability — can an agent replicate this exact drawing end to end?

**REPLICABLE from this PDF:**
- The visual grammar: black/white candles, 1px thin black lines, dashed = measured/projection level, solid = confirmed key level, dotted = reference, one translucent yellow zone per chart, red dot per swing, X = failed level, green ✓ = validated, margin legends, measurement box + stats label.
- The label vocabulary (BOS, MSS, IDM, OCL, SBR, RBS, QML, TSS/TBS, SSS, ERL, LIQ SWEEP, CLASSIC A/V, TRAP, INVERSION, FAKE BOI, LAST LIQUIDITY, ERL TAKEN).
- The two HTF→LTF ladders verbatim and the confirmation checklist (CRT + clear liquidity + NY AM + IMB→LIQ + IDM/BOS/MSS).
- The order lines (SL/TP prices are given for the XAGUSD trade) and the BUY/SELL ladders and the two measured moves with exact prices.
- The trendline fan construction (successive highs → one low, dashed lines, cap ~5 lines) and the single dashed diagonal (red ▼ / blue ◆).
- The Quarterly Theory legend wording (Q1–Q4 definitions) and the three definition boxes (Premium Zone, High Risk Confirmation, Draw on Liquidity — p.37 text is the most copy-ready in the book).

**BLOCKED / UNVERIFIED:**
- Which candle is the PROFILE candle (no size threshold); which swings qualify (no selection rule); what counts as a "hit"/"validation"/"shift" (no thresholds).
- Zone edges: no zone on the master pages carries a price; edges are by eye.
- Fib-circle construction (no centre, radius, ratios, anchors) and STDV (no formula, anchor, lookback, price mapping).
- HTF→LTF drop rule: steps are named, no trigger for dropping, no shared price links the charts; H1/M15 never drawn.
- Entry/stop/target/sizing: no stop distance, no lot size, no risk %, no R:R, no session times, no backtest, no win rate, no P&L. The only complete trade record is Trade 16 (Win, no exit price) and the p.9 banner (+20,462.50 USD, no order ticket).
- Undefined labels (IOFED, +TS, BOSa/BOSm, C.A, SSS, FS, IQFBD, +7B^, TOFED, C.V, 60 IDR, masked text).
- Q3/Q4 gloss contradictions; AMDX vs XAMD vs A-M-D/M-A-D; tick-scale direction flip.
- Readability blockers: right-edge cropping on several pages (pp.40, 42, 44–46 lose their price axis entirely), p.30 cover hiding its own reference text under artwork, watermark obscuring labels, p.45 masked text.
- No performance evidence anywhere: no backtest, win rate, sample size, losing example with numbers, or dollar P&L beyond the single p.9 banner. The two measured moves are single after-the-fact moves with no order tickets.

**Verdict:** style replicable, exact drawing NOT replicable from this PDF alone. An agent build would need a PROFILE-candle selection rule, a swing-selection rule, a zone-edge rule, a Fib-circle construction rule, a validation threshold, and an HTF→LTF drop rule from outside this PDF — or it would be inventing them. What this book *does* give, which the Alchemist book does not, is a **written HTF→LTF ladder, a journal template, a priced order, and a measurement spec** — the four most codable parts of either MSNR PDF.

## 11. What this PDF gives Nivedh's drawing skill (the "learn this skill" takeaway)

- A **neatness checklist** (see the skill sheet: `neat-drawing-skill.md`) — 12 copyable restraints that make a chart look like this PDF rather than the Alchemist one.
- **Two teachable ladders** that fit on any chart: MN > PROFILE / W1 > MAJORITY / D1 > MINORITY (silver) and D1 > PROFILE / H1 > MINORITY + MSS / H4 > MAJORITY + CONFIRM (gold).
- A **confirmation stack to learn:** PROFILE → MAJORITY → MINORITY → take MSS → minor validation (IMB to LIQ) → wait HIT MAJOR IMB → LIQ TO LIQ → target ERL — with the drawn rule that **one wick touch validates a zone**.
- A **drawing vocabulary** that is small and consistent: stepped black lines, dotted references, one dashed diagonal with red ▼ / blue ◆, one translucent zone, brackets for BOS/IDM/MSS, 💡 for the shift moment, red dot for a touch, X for a failed level, green ✓ for validation.
- A **journal template** (Trade 16, p.20) and a **measurement spec** (pp.39/41) — the two ways the book proves a move instead of asserting it.
- Three **worked price anchors**: NZDCAD low 0.79559; XAGUSD short 71.143 → 54.604, +20,462.50 USD on 0.25 lot; XAUUSD +737.484 (+18.70%) and −687.471 (−14.85%).
- And a clear **blocked list** (§9–10) that any agent build must resolve before it can claim to replicate the drawing — above all the PROFILE anchor definition, the validation thresholds, the five-plus undefined abbreviations, and the missing entry/stop/target.

*This is a strategy/drawing test, not financial advice. Do not trade real money on the basis of these pages.*
