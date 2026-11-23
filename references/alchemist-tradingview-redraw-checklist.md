# TradingView redraw — PDF-vs-chart verification sheet

Prepared 2026-11-22 ~12:30 IST, for the redraw Nivedh asked for at 12:20 IST
(06:50 UTC): clear every drawing, redo from scratch exactly like the
Alchemist MSNR PDF, fix the Fib Circle colours/settings, compare with the
current drawing, then apply the same method to the current market.
Source PDF: `workspace/user/files/______666__________________1_0_22af.pdf`
(34 pages, image-only). Analysis: `workspace/research_notes/alchemist-pdf-merged/report.md`.

## First drawing (12:19 IST, 06:49 UTC) — what it had, for comparison

- Chart: https://www.tradingview.com/chart/qAYlZwlc/?symbol=OANDA%3AXAUUSD
  — XAUUSD 1H, 17–20 Aug 2026, saved in account nivedhbhat15. No trade placed.
- CRT high / ERL 4,395 · CRT low 4,311.25 · CE 4,353.16
  (midpoint of 4,311.31 and 4,395 — note the low is quoted both ways)
- APEX CE 4,333.79 · BUY 4,336.16 · SL 4,337.65 · TP1 4,445.29 · TP2 4,449.74
- FVG + IRL rectangle 4,333.79–4,353.16, plus trendline and
  liquidity / BOS / shift / premium-discount labels.
- Fib Circle + STDV were approximations, not the PDF's rules:
  Fib Circles on TradingView defaults, anchored 4,318.96 to 4,431.65,
  centred at the midpoint of the anchors (not the swing low), outer arcs
  very large. STDV was a Regression Trend at ±2.5.
- M5 view for 19 Aug could not be shown: Basic plan only goes back
  5,000 five-minute bars (~17 days); 19 Aug is ~95 days back.
- The saved layout already carried LuxAlgo SMC, EMAs, VWAP and other
  indicators — not part of the PDF.

## What the PDF actually shows — the check values

| Item | PDF value | First drawing | Check on redraw |
|---|---|---|---|
| APEX CE centre | ~4,333.78 (pp.3–8); zone edges priced 4,335.25 / 4,333.71 on pp.19–22 — the only priced zone in the book | 4,333.79 | centre within ~0.05; edges 4,333.71–4,335.25 if drawn as a zone |
| BUY (M5, p.9) | 4,336.09 | 4,336.16 (+0.07) | should read 4,336.09 |
| SL (M5, p.9) | 4,337.55 — sits ABOVE the buy line, inverted for a long, unexplained in the PDF | 4,337.65 (+0.10, same inversion) | flag, don't silently "fix": the PDF itself is inverted here; ask Nivedh whether to copy it faithfully or place SL below the buy |
| TP1 | 4,445.19, touched | 4,445.29 (+0.10) | should read 4,445.19 |
| TP2 | 4,449.71, untouched | 4,449.74 (+0.03) | should read 4,449.71 |
| CRT high / low, CE | high ~4,395, low ~4,311, CE = 50% ≈ 4,353 | 4,395 / 4,311.25 / 4,353.16 | CE must be the exact midpoint of the chosen high/low |
| Fib Circle | thin grey fan radiating from a single low point (the swing low), two large blue/purple arcs sweeping up to the top right; label "END FIB CIRCLE" (pp.10–11). Centre = swing low. No ratios, anchors or arc meanings given anywhere | defaults, midpoint-centred, arcs very large | fan must originate at the swing low, thin grey lines + blue/purple arcs — but exact ratios CANNOT be verified from the PDF; any setting is an assumption |
| STDV | scale −2.5 / −2 / −1 / 0 (−4 on p.7); "STDV2-2.5" cited, no formula, anchor or lookback | Regression Trend ±2.5 | ±2.5 matches the cited scale, but the formula/anchor is unverified — label it as assumed |
| Second gold hold (p.27) | M30 buy 4,335.23 on 19 Aug 08:30, +361.63 pts / +8.34% over 174 bars to 25 Aug, no stop/exit/lot/P&L | not drawn | only if Nivedh wants the second example too; it is a separate chart |

## Three things that cannot be made "exact" — don't chase them

1. Fib Circle construction: no centre price, radius, ratios or arc
   meanings in the PDF. Colour/style can match (thin grey fan from the
   swing low, blue/purple arcs); geometry cannot be proven exact.
2. STDV formula: no formula, anchor or lookback. ±2.5 matches the
   cited scale only.
3. HTF → LTF drop: no shown sequence anywhere in the 34 pages. The
   M5/M1 pages are hard cuts with no mapping from HTF levels, and no
   LTF confirmation is drawn on p.9. The redraw can show both
   timeframes side by side, but the link between them is inferred,
   not copied.

## Two catches for the redraw

- "Clear all drawings" clears drawings, not indicators. LuxAlgo SMC,
  EMAs and VWAP are indicators on the saved layout — they stay unless
  hidden/removed separately. If Nivedh wants a PDF-clean chart, those
  need hiding too.
- Line-chart fallback: Nivedh said (12:19 IST) that if the MSNR
  keywords/key lines get confusing, use a line chart instead. The
  PDF itself uses a line chart for the US30 Quarterly pages
  (pp.10–16), so a line chart is in-style for the HTF view — but the
  gold worked example is candles, and CE/CRT need candle high/low,
  so a line chart can't carry the CRT range on the gold chart.

## Current-market application (second half of his ask)

Not yet checkable from the PDF alone: it needs today's XAUUSD range
(live price, current swing high/low) and the same assumed rules
(CRT candle choice, rejection threshold, Fib Circle ratios). The
redraw should state which candle it picked as the CRT candle and
which Fib/STDV settings it assumed, so the current-market version
is reproducible rather than a one-off picture.

## Status at preparation time (12:30 IST, 2026-11-22)

- Redraw task was started in the video side chat at 12:20 IST with
  "it's working on that now". No result message had arrived in the
  conversation by 12:28 IST.
- `browser.windows` in this research run lists NO open windows, so
  the redraw's live state could not be confirmed here — it may be
  running in the main agent's browser context. Do NOT tell Nivedh
  the redraw failed or finished on this evidence alone; check the
  side chat / live task first at delivery.
- This sheet is a verification aid for when the redraw lands, not a
  new request to Nivedh. No reply is needed from him unless the SL
  inversion question (copy faithfully vs place below the buy) needs
  his call.
