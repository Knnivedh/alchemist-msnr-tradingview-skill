# Alchemist MSNR TradingView Drawing

## What this skill is and what it cannot do

- This skill teaches you to reproduce the Alchemist MSNR chart drawing in TradingView, from the 34 page image only playbook by Satya Alchemist (@SATYA666.SS, Telegram @MSNRPDF1) and from the worked gold example that was drawn through passes P0 to P9 in November 2026.

- This skill transfers the method only, which means the rules, the exact values, the procedures, and the verification steps.

- This skill does not transfer a logged in TradingView session, and it does not transfer access to the user's TradingView account.

- To draw in the user's account you still need your own TradingView access and the user's login, and you still need the user's own copy of the PDF.

- Without those three things you can study the method and you can plan a drawing, but you cannot place a single line on the user's chart.

- Never present an assumption as the PDF's rule, and never present a guessed number as a measured one.

- No trade is ever placed as part of this skill, and nothing in this skill is trading advice or a promise of profit.

- The honest ceiling for the gold chart is about 9 out of 10, not 10, because the PDF leaves several constructions undefined and one view is blocked by the TradingView Basic plan.

## Learning rule — skill first, never text-grabbing

This rule governs every pass, and it comes from Nivedh (23 Nov 2026):

- **Extract the skill, not the text.** From any PDF or video, take how the author *draws* — where the line starts, which candle it anchors to, how thick, what colour, what shape — not what the words say. Copying labels and definitions without watching the drawing is how past passes went wrong (e.g. "TP1"/"TP2" labels that do not exist in the PDF; red circle-cross markers copied onto the gold chart where the PDF has none; Fib radius changed by number while the arcs still looked wrong).
- **Learn from each pass's mistakes.** Before every fix pass, list what the previous pass got wrong (from the measured comparison report, not from memory) and fix those first. A mistake repeated across passes is a method failure, not a drawing slip.
- **Judge only side by side, by looking.** Every improvement is proven by a fresh screenshot of our chart placed next to the PDF render and read visually — same crop, same zoom. Settings read-backs, text counts and claimed fixes are not evidence. If the two pictures do not look the same, the fix is not done, whatever the settings say.

## The method in brief

- Candle Range Theory defines the range from one reference candle, so the candle high is CRT/.HIGH and the candle low is CRT/.LOW.

- CE, Consequent Encroachment, is the 50 percent line of that range.

- Premium and discount split at the 50 percent line, so buy below 50 percent and sell above 50 percent.

- APEX CE is the key CE level the trade keys off, and in the gold example it is the level where the trendline meets the CE in discount after a sell side sweep.

- A zone is a filled rectangle or band captured by confluence, which means the CE 50 percent line plus prior structure plus a trendline or STDV meeting price in discount or premium.

- A zone is validated only by price reaction and by a later BOS or SHIFT, and the PDF gives no tap count, no wick versus body rule, no zone width rule, and no invalidation rule.

- ERL is external range liquidity at the extremes, and IRL is internal range liquidity inside the range.

- FVG is a fair value gap, and the FVG plus IRL zone is drawn as a grey rectangle inside the range.

- BOS is break of structure, SHIFT or MSS is market structure shift, CISD is change in state of delivery, QML is Quasimodo, SBR is support become resistance, and RBS is resistance become support.

- Inducement, IDM, is price pushed to take liquidity before the real move, and a turtle soup is a sweep below a low or above a high that fails and reverses.

- Quarterly Theory divides a range into four quarters, so Q1 is 0 to 25 percent, Q2 is 25 to 50 percent, Q3 is 50 to 75 percent, and Q4 is 75 to 100 percent, with 50 percent as equilibrium.

- The PDF glosses Q1 as accumulation, Q2 as manipulation or transition, Q3 as distribution, and Q4 as reversal or continue, but it also contradicts itself, because Q4 is glossed as both discount and premium in different places and Q3 is glossed as starting in discount even though Q3 is 50 to 75 percent.

- The Zone Equilibrium rule says price inside the 50 percent area moving toward buy side liquidity is a place to look for a SELL setup.

- High Risk Confirmation means entering early before a full sweep, on a wick reaction or inducement, with high reward and low confirmation.

- The entry models on pages 29 to 34 are schematic only, with no instrument, no prices, and no timeframe, and they are Classic V support buy, Classic A resistance sell, CE entry at 25 percent or 50 percent or 75 percent with no rule for which percent, RBS and SBR flips, Quasimodo QML, and Open Close Level OCL. A third teacher, MSNR BIKASH (video https://youtu.be/JRPDsWhql9A, 22 Nov 2026), gives them as a three-model taxonomy with a ranking — see the Entry models section below — but his rules are his own interpretation, not Satya's.

- The drawing workflow the PDF implies is to open the higher timeframe chart and mark the reference candle high and low, draw the CE at 50 percent and shade the FVG plus IRL zone, extend the range to ERL at the extremes and mark the buy side and sell side liquidity pools, mark structure with BOS, SHIFT, and CISD, mark the APEX CE where the trendline meets the CE in discount after a sell side sweep, add the STDV projection and the circle bars, then drop to M5 or M1 and draw the entry line, the SL line, and the TP lines.

- The PDF never shows the higher timeframe to lower timeframe drop, and the M5 and M1 pages are hard cuts with no mapping, no intermediate timeframes, and no lower timeframe confirmation drawn.

## The worked gold example

- The primary example is XAUUSD gold on 17 to 20 Aug 2026, drawn on OANDA:XAUUSD 1H in TradingView layout qAYlZwlc.

- The PDF gives no higher timeframe label for this chart, and the only hint is "SBR 1H", so 1H is a best guess, not a PDF fact.

- The CRT high comes from the upper wick of the tall Monday 17 Aug candle at about 12:00 to 14:00, and the CRT low comes from the lower wick of the Tuesday 18 Aug candle at about 05:00.

- The APEX band left edge comes from the turtle sweep low candle on Wednesday 19 Aug at about 05:00.

## OCL (Open Close Level) — from the TradeW Mafia Part 4 video

- OCL is the Open Close Level, from the video "MSNR OCL LEVEL Explained! | PART 4" by TradeW Mafia, 23 Nov 2026, 15:31. OCL is a single thin horizontal line at a candle's close, where the next candle opens — the gap between one candle's close and the next candle's open. The video also calls it a "gap level". Bullish: candle closes, next candle opens above the close, and the line through that close/open boundary is support. Bearish is the mirror image, resistance.
- The level is valid whether or not a turtle sweep (TS) of the previous candle happened — a body close alone makes it valid, and no TS is required. If a TS did happen, you take the V level instead; OCL is the fallback when there is no TS.
- "Every level has an OCL level" — the A level (Classic A resistance) is also an OCL by this rule. OCL is a property of every level, not a separate parallel level type, which corrects the PDF's taxonomy where OCL was only named in the pages 29 to 34 entry-model list with no definition.
- The video's only concrete HTF to LTF procedure: mark the HTF OCL (5 minute), drop to 3 minute and 1 minute, and mark the A, V, OCL and CE levels inside it. The PDF never shows this drop.
- Confluence: OCL plus SBR or RBS is the video's "sniper entry" setup, and OCL plus FVG plus LTF CE is the triple confluence. A broken OCL that retests and continues is an OCL flip, playing as RBS.
- The video names no instrument prices for the August chart: its worked examples are all XAUUSD on Friday 20 Nov 2026 (OCLs around 3,545.5, 3,590.6, 3,582.4, 3,554.07, 3,553.02, 3,547.5, 3,580.12, 3,579.9, and one failed support OCL around 3,561.5). Those prices must not be carried onto the August chart.
- Blocker: no OCL price can be computed for the August chart from this skill's values, because the skill records wick-based numbers only (CRT high/low, CE), while OCL needs candle closes and opens. The workspace has no Aug 2026 OHLC data. To draw an OCL on the August chart, read the closes and opens from the TradingView Data Window for 17 to 20 Aug 2026 first. On 24 hour gold the next open usually equals the prior close, so the video's "gap" usually reads as a close-price line, not a visible gap.
- The video gives no entry, stop, target, risk to reward, position size, backtest, or win rate, and its "100 pips or around 150 pips" claim is unverifiable. Its "I guarantee you will be profitable" claim is unproven — do not repeat it.
- Terms the video speaks but never defines, so do not use them: "PUI", "FP / FP LP", "FEG" (probably FVG, unconfirmed), "C" level, and the OCL validity condition mentioned at about 13:10 but truncated in the transcript.
- Full reports: workspace/research_notes/msnr-ocl-agent1-transcript-ocl-definition.md, msnr-ocl-agent2-chart-drawing.md, msnr-ocl-agent3-new-concepts-implementation.md, and the deep research at workspace/research_notes/msnr-ocl-level-part4-20261123-0636/.

## Entry models — three-model taxonomy (MSNR BIKASH video)

- Source: "MSNR Entry Models Explained | Best Sniper Entry Strategy | MSNR & SNR", MSNR BIKASH, https://youtu.be/JRPDsWhql9A, 24:07, uploaded 22 Nov 2026. Bikash presents these as "my own personal entry model" — a third creator, distinct from Satya Alchemist (PDF) and TradeW Mafia (OCL Part 4). His rules are his interpretation, not Satya's, and must be attributed to him wherever they are used. Full reports: workspace/research_notes/msnr-entry-models-video/agent1-transcript-entry-models.md, agent2-chart-drawing.md, agent3-comparison-implementation.md.
- Three models with his ranking. Model 1 shift-entry (best — ranked above direct entry by his own words): HTF key tapped, price closes below the swing low (MSS), drop to the lower timeframe and enter from one of three zones — (a) Double FVG, two FVGs = a valid zone; (b) the key above the pullback; (c) the QML zone. Model 2 direct entry: refine a 4H key down 15m to 5m, enter on a rejection candle at the tap, SL 20 pips stated twice (a data point only — see below). Model 3 Classic A alignment (his favourite): wait for the same key on the same timeframe, Classic A forms at the key, market taps it, enter from it; fallback is the most recent Classic A.
- QML definition (new): QML is the level where BOS was repeatedly created; it is confirmed when price breaks that low and closes below. The validity rules for which QML or key is valid are paywalled in his VIP mentorship — do not guess them. Audit task E5: check the existing [QML] 4,380.382 on the P9 screenshots against this definition (two or more BOS creations at that level = pass; otherwise the label is a placement choice, not a QML by this definition — do not move the label to make it pass).
- Double FVG validity test: two FVGs in one zone = a valid zone. No spacing, overlap, or timeframe rule is given — test-first (E3), stating our own spacing (both FVGs inside one swing leg) and labelling it as ours.
- Refinement ladder 4H to 15m to 5m: a fourth HTF to LTF ladder, kept separate from the OCL video's 5m to 3m to 1m, the ISC ladder, and WHITE's H1 POI to M1–M5/M3. The two-step refinement pattern is corroborated across authors; the rung sets are author-specific — do not merge them into one ladder.
- Rejection candle: the named trigger for Model 2, never defined by him. Test definition (ours, not his): a candle whose wick is at least 2 times its body and which closes back inside the refined zone.
- Multi-timeframe OCL alignment: the same OCL present on 1H, 30m, 15m and 5m = a valid zone. This is a confirmation signal on top of Part 4's OCL definition (close to open gap rule) — it does not redefine OCL.
- Validation language: re-tap = manipulation (a key tapped once will be tapped again, and the second tap manipulates — wait it out); "touch and fly" (a valid key tapped once, price leaves immediately). Pair with the OCL plan's MISS audit.
- Range-quality test: the range's first pullback sweeping liquidity on both sides is the cleanest MSNR structure (test E9). This is a range-quality test, not a CRT test.
- How he draws (from agent 2's 23 inspected frames): keys are thin solid pink/magenta horizontal lines, full chart width, sometimes a wide translucent pink band anchored on a wick; FVGs are pale teal/cyan fill-only rectangles, no border, no label — except IFVG (Double FVG), the only labelled zone in the video; a magenta line-chart (closes) overlay over the candles to see A and V shapes and structure breaks; no text labels for BOS, MSS, QML or POI anywhere — levels are spoken, not labelled. No Fib Circle, no STDV, no CRT, CE or APEX in this video.
- Conflicts (do not merge): Model 2 direct entry (no shift required) is a genuine method fork against the skill's validation-by-BOS rule — keep the skill's stricter rule preferred, Model 2 as the lower-confirmation alternative. His "above liquidity no key is valid" clashes with our KEY SELL MISS ENTRY at 4,401.170 above ERL 4,395.00 — flagged for an explicit decision by Nivedh, not auto-deleted. His 20-pip SL is a data point only: 20 pips on gold at 0.01 lot = $20 risk, 4 times the $5 budget; no placement rule is given; his own position tools show $0.41 to $2.93 stops, contradicting the spoken 20 pips — do not adopt. His "first liquidity / hurdles" TP logic differs from the PDF's drawn TP lines — keep both, replace neither.
- Do not adopt from this video: the around 450-pip and 300-pip claims (unmeasured, no entry or stop shown), the "best sniper" title framing ("sniper" is never spoken in the video), the 20-pip SL as a rule, hurdles as TP, any win rate (none stated), VIP mentorship content, direct entry promoted above shift entry, and "MSNR as SNR" as a licence to drop CRT/CE — the entry models are portable across keys, but the CRT/CE core stays for the Satya gold chart.
- Undefined terms from this video — do not use on a chart until defined: "valid key" (the central term, about 21 hits, never defined), rejection candle, Double FVG spacing, "C key" (the same undefined letter as the OCL video's "C level" — do not merge), LSAR (announced as the next series, do not guess the expansion), sniper zone, hurdles, accumulation zones (Bikash sense is not the PDF Q1 sense), advanced/basic levels.
- Gap update (23 Nov 2026): still 0 of 10 gaps fully answered. A4 (HTF to LTF), A5 (key-level selection) and A8 (entry models) are now stronger partials; A8 is the best-answered gap. A1 is decoupled from entry-model work — the models work on any key, so they can be tested without solving CRT selection. A7 (OCL validity) still unanswered.
- Test-first proposals E1 to E10 are in the agent 3 report section 6. All tests run on a fresh test layout first, never on the saved August layout qAYlZwlc, judged by a fresh screenshot placed side by side with the video frame or PDF page, pass/fail stated before drawing. No trade in any test.

## Wick anchoring — pinpoint, not a full line

- Rule: every line starts at the exact wick where the change happened. The line's left end IS the wick tip of its defining candle. Never start a line at an arbitrary bar, and never draw a full-width line and call it anchored.
- The defining wick for each key line (gold example):
  - CRT high / ERL 4,395.00 — upper wick of the tall Monday 17 Aug candle, about 12:00 to 14:00.
  - CRT low 4,311.31 — lower wick of the Tuesday 18 Aug candle, about 05:00. The PDF's dotted line literally starts at that wick.
  - CE 50 percent 4,353.16 — computed from the range, so it starts at the left edge of the CRT range (the CRT high candle), not mid-chart.
  - APEX CE 4,333.78 — starts at the turtle sweep low candle, Wednesday 19 Aug at about 05:00, the same candle as the APEX band left edge.
  - BUY 4,336.09, SL 4,337.55, TP 4,445.19, TP 4,449.71 — execution lines on the M5 page; their left ends sit on the M5 candles where the trade was placed and where the wicks touched, not on the 1H candles.
- TradingView procedure: type the exact price in Settings first, then drag the on-chart handle so the line's left end sits exactly on the wick tip. Horizontal lines expose no bar or date field in Settings, so the handle position is the only anchor — there is no numeric way to set it.
- Label rule: the text on a line must say exactly what the line is, as "<name> <price>", for example "CRT high 4395.00", "CRT low 4311.31", "CE 4353.16", "APEX CE 4333.78", "BUY 4336.09", "SL 4337.55", "TP 4449.71". No abbreviations, no extra words, and the price in the label must match Settings exactly.
- Verification: add a fourth check to the three-way check — a fresh screenshot must show the line starting at the named wick candle, zoomed in on that candle. A line whose left end floats in empty space fails, even if its price is exact.
- Honest status: as of the P9 check on 23 Nov 2026, the ERL and CRT low wick anchors are still unverified — the handles were never dragged to those wicks. The prices are exact; the pinpoint anchors are not. This procedure is the fix for that gap, not a claim that it is already done.

- The eight key lines below are exact in TradingView Settings, and they were re-measured from Settings with the drawn tags agreeing in the P5 pass.

| Line | PDF value | Drawn value | Status |
|---|---|---|---|
| CRT high / ERL | 4,395.00 | 4,395.00 | Exact |
| CRT low | 4,311.31 | 4,311.31 | Exact |
| CE 50 percent | 4,353.16 | 4,353.16 | Exact |
| APEX CE | 4,333.78 | 4,333.78 | Exact |
| BUY | 4,336.09 | 4,336.09 | Exact |
| SL | 4,337.55 | 4,337.55 | Exact |
| TP 4,445.19 | 4,445.19 | 4,445.19 | Touched |
| TP 4,449.71 | 4,449.71 | 4,449.71 | Untouched on M5 |

- The SL sits 1.46 above the BUY, which is inverted for a long, and the PDF never explains it, so copy it faithfully and never silently fix it.

- The PDF labels only the 4,449.71 line as "TP", in red dashed style on page 9, and the 4,445.19 line carries no label at all, in red dotted style, so "TP1" and "TP2" appear nowhere in the PDF and are our numbering only.

- The 4,445.19 line was touched exactly on page 9 at the highest M5 wick at about 15:00 on 19 Aug, with a red arrow at the top, and the 4,449.71 line was untouched at the M5 screenshot at 20:12, though it was effectively reached later on the 30 minute view at 4,449.27 and 4,450.71 on page 19.

- The TP distances from the BUY are plus 109.10 and plus 113.62, and the PDF gives no risk to reward ratio and no "book 50 percent at TP1" rule anywhere, so do not invent one.

- Both TP lines exist only on page 9, the M5 phone screenshot, and the higher timeframe pages 3 to 8 have no TP lines, because their target is ERL.

- The FVG plus IRL zone is a grey rectangle from 4,353.16 down to 4,333.78, and the blue APEX band is exactly 4,333.78 to 4,335.59.

- The first APEX band drawn in P0 was wrong at 4,335.28 to 4,332.28, with the bottom 1.50 too low, and it was fixed to 4,333.78 to 4,335.59 in P4, so check the band edges, not just the centre price.

- The only other APEX zone edges the PDF prices are 4,335.25 and 4,333.71 on pages 19 to 22, and no other zone edge is priced anywhere in the PDF.

- The Q2 Manipulation band is 4,332.23 to 4,353.16, drawn pink translucent and labelled "Q2 / MANIPULATION", and the APEX CE, the BUY, and the SL all sit inside it.

- The quartile split of the CRT range 4,311.31 to 4,395.00 is Q1 4,311.31 to 4,332.23, Q2 4,332.23 to 4,353.16, Q3 4,353.16 to 4,374.08, and Q4 4,374.08 to 4,395.00, with CE 4,353.16 as the Q2 and Q3 boundary and APEX 4,333.78 just inside Q2.

- The quartile system in the PDF is not shaded price bands, and it is text boxes plus a 4 segment bar with a dot, which is covered in the circle bars section below.

- The swing liquidity targets on pages 25 to 26 are N1 4,665.22 and N2 about 4,718.37, with LIQUIDITY TARGET/.SS- at about 4,621.74, and they belong on a separate 30 minute layout for the later hold, not merged into a TP ladder on the M5 trade.

- The second hold on page 27 is a separate trade, an XAUUSD M30 buy at 4,335.23 on 19 Aug at 08:30, up 361.63 points or 8.34 percent over 174 bars to 25 Aug, with no stop, no exit, no lot size, and no profit and loss given.

- The PDF is internally inconsistent by 0.07 to 0.44 across pages, for example APEX 4,333.78 on the 1H view against 4,333.71 on the 30 minute view, so use the 1H value 4,333.78 as canonical and do not chase the other pages into agreement.

- The US30 Quarterly chart on pages 10 to 16 is a second chart in the same playbook, and it was never drawn, so do not claim this skill covers it.

## Fib Circle procedure as actually done

- TradingView always centres a Fib Circle on the midpoint of its two anchors, and there is no centre control in Settings, so you centre it by mirroring the second anchor around the price you want as centre.

- The mirror rule is that the second anchor bar equals two times the bar of the centre point minus the first anchor bar, and the second anchor price equals two times the centre price minus the first anchor price.

- The P0 pass centred the circle on the APEX CE 4,333.78 with anchors 4,395.00 and 4,272.56, which satisfies the mirror rule exactly, because two times 4,333.78 minus 4,395.00 is 4,272.56.

- A later audit corrected the centre, because the circle should sit on the swing low, not on the APEX CE, and the swing low centre is 4,324.29.

- The P5 rebuild used centre 4,324.29 with radius about 250 and only levels 1, 2.35, and 2.55 enabled, thin light grey, background off, and labels off.

- The P7 pass flattened the circle to radius 600 with anchors 4,924.29 and 3,724.29 and centre still 4,324.29, and the P8 pass reduced it to radius 400 with anchors 4,724.29 and 3,924.29 and centre 4,324.29.

- The P8 radius 400 arcs are still near vertical in the narrow Aug 17 to 20 frame, and the PDF arcs are shallow and large radius, so this is still an open problem.

- The TradingView Fib Circle defaults are 0.236, 0.382, 0.5, 0.618, 0.786, 1, 1.618, 2.618, 3.618, 4.236, and 4.618, and showing all eleven is wrong for this drawing.

- The MSNR settings from the zayanfx video "How To Use FIB CIRCLE IN MSNR STRATEGY" (https://www.youtube.com/watch?v=Ln-xQJgHjLg, 4:12) check five levels, which are 1, 2.35, 2.55, 4.236, and 4.618, and the video says the fifth circle gives the key level.

- Only two or three of those levels show in frame at the PDF zoom, which is why the PDF looks like it has two or three lines, and the gold chart uses only levels 1, 2.35, and 2.55.

- The honest limit is that the PDF gives no centre price, no radius, no ratios, and no arc meanings, so every Fib Circle geometry in this skill is an assumption, and you must label it as one.

- The audit also corrected an earlier error, because at 150 dpi the gold charts do show three large faint grey arcs on pages 3, 5, 23, and 24, with no fan, no colour, and no label, while the fan and the blue and purple arcs are on the US30 Quarterly chart only, on pages 10 to 16.

- Placing a Fib Circle with a fan on gold was therefore a transplant from the US30 chart, and the gold version should be thin grey arcs only, with no fan lines.

- The Fib Circle tool has no fan lines at all, and radiating lines would need the separate Fib Fan tool, because the US30 circle is actually a fan of 10 to 12 thin grey rays plus two or three arcs.

- The drag angle is an unresolved contradiction, because zayanfx insists the low to high drag must be at 90 degrees, while Instagram carousels and TradingView documentation say 45 degrees, and no source settles it, and no source defines centring a circle on APEX CE.

## STDV procedure as actually done

- The PDF cites a scale written as "STDV2-2.5" and shows a thin dashed scale from minus 2.5 to 0 on the right edge, and it gives no formula, no anchor, and no lookback.

- The P1 pass used the Regression Trend tool at plus and minus 2.5, source Close, as a descending channel from about 4,395 to 4,333.78, labelled "STDV ±2.5", and that was an approximation, not a PDF rule.

- The P3 pass exposed a tool limit, because the Regression Trend tool has no fill off switch, so at 30 percent black it became a big grey filled triangle in the middle of the chart, while the PDF has no wedge at all.

- The P4 pass deleted the triangle and replaced it with one thin grey dashed diagonal plus minus 2.5, minus 2, minus 1, and 0 ticks on the right, with no fill and no channel.

- The P6 pass verified the STDV in Settings as a thin grey dashed Trend Line, not a Regression Trend, with no fill and no channel, anchors 4,425.72 and 4,333.264, and ticks 2.5, minus 2, minus 1, and 0 visible.

- The P7 pass moved the STDV top anchor to the 19 Aug rally top wick at 4,449.71, but the low end regressed to about 4,352.5 at 19 Aug 12:00 instead of 4,333.264 at 18 Aug 20:00, and Settings edits to it would not stick.

- The P8 pass restored the low end to 4,333.264 at bar minus 1260, with the top at the rally wick 4,449.71 at bar minus 1252.

- One discrepancy from P8 is still unresolved, because bar minus 1260 shows in the tooltip as Wednesday 19 Aug 00:00 in UTC minus 5, not 18 Aug 20:00 as instructed, so do not claim the STDV date anchor is verified.

- The page 7 scale also shows minus 4 and minus 3.5 marks at the top of the rally, and those are still absent from the chart.

## Circle bars

- The DAILY CIRCLE bar is a 4 segment bar below the price action, and the 90M CIRCLE bar sits above it, with a MACRO marker above that.

- The Daily bar runs from 4,332 at the top to 4,328 at the bottom, on bars minus 1308 to minus 1296 on 17 Aug, with four segments at 50 percent opacity.

- The four segments are grey on bars minus 1308 to minus 1305 from 00:00 to 03:00, pink on bars minus 1305 to minus 1302 from 03:00 to 06:00, green on bars minus 1302 to minus 1299 from 06:00 to 09:00, and blue on bars minus 1299 to minus 1296 from 09:00 to 12:00.

- The 90M bar is a blue bar from 4,339 to 4,335 above the Daily bar, and the label "DAILY CIRCLE / 90M CIRCLE / MACRO" sits at 4,340.254 on Monday 17 Aug at 06:00.

- Q2/.M is a black dot on the DAILY CIRCLE bar at the Q2 to Q3 boundary, with a dotted line down to 4,311.31, and it is a time marker, not a price line.

- The P8 dot was drawn at 4,326.153 on Monday 17 Aug at 01:00, labelled "● Q2/.M", but it sits under the grey and pink boundary, not centred under segment 2, so its position is still wrong.

- Do not merge Q2/.M into the CRT low line, because the chart once carried a dotted line labelled "CRT low 4311.31 / Q2/.M" that merged two different objects, and the fix is to label the line "CRT low 4311.31" and put Q2/.M under the bar dot.

- The PDF never maps the circle bars to clock times or sessions, so the segment times above are the P8 placement choice, not a PDF rule.

- The circle bar label readability is still open after P8, because the label overlaps the 90M bar border.

## Definition boxes

- Copy the wording below verbatim, including the PDF typos, and do not silently correct them, because the typos are part of the match.

- Where a word is cut off by the page edge it is marked [cropped] and the missing word is not invented.

- The five boxes drawn in P5 and re-spaced in P8 are Premium/Discount, Draw on Liquidity, High Risk Confirmation, Q2 Transition, and Discount Zone, with the P8 position given with each box.

- The Quarterly Theory intro, the Quarterly Theory legend, and the ERL box are also in the PDF and are still not drawn, so they are listed here for the next pass.

- Box 1, Premium/Discount, black text in a grey bordered box, on pages 3 and 5, at 4,436.762 on Tuesday 18 Aug at 16:00.

> PREMIUM DISCOUNT IS A CONCEPT IN (SMC / ICT) USED TO DETERMINE WHETHE (DISCOUNT) OR EXPENSIVE (PREMIUM).
> STDV2-2.5
> HOW TO DETERMINE SE A RANGE (HIGH - LOW)
> 50% = EQUILIBRIUM
> • 100% = HIGH SIMPLE VERSION
> BUY BELOW 50%
> - SELL ABOVE 50%
> SUMMARY
> PREMIUM DISCOUNT = A SIMPLE WAY TO KNOW:
> THEN TO
> • WHEN TO SELL

- "WHETHE" and "SE" are as printed, and the last line is truncated in the PDF, so "WHEN TO BUY" is presumably cut off and is not visible, and you must not add it.

- Box 2, High Risk Confirmation, gold text in a grey bordered box, on pages 3 and 5, at 4,407.581 on Tuesday 18 Aug at 22:00.

> HIGH RISK CONFIRMATION
> HIGH RISK CONFIRMATION IS A EARLY ENTRY SIGNAL TAKEN SEPORE FULL A SWEEPS. WICK REACTION, OR INDUCE EARLY ENTRY.
> HIGH REKARD, LOW CONFIRMATION.

- "SEPORE" means BEFORE and "REKARD" means REWARD, as printed.

- Box 3, Discount Zone, gold text in a grey bordered box with a red triangle, on page 5 at the bottom left, at 4,417.708 on Wednesday 19 Aug at 10:00.

> ▲ DISCOUNT ZONE
> - PRICE BELOW
> - FOCUS BUY
> - LOOK FOR • FVG •
> - DEMAND • LIQUIDITY LOW
> SWEEP LEVEL • LOOKING FOR CE
> PRICE REACT LOW AND TRY TO
> DRAW ON TSS TO LEVEL LOW

- "TSS" is partially legible in the PDF and its meaning is unclear, so keep it as printed.

- Box 4, Q2 Transition, black text with a red triangle in a grey bordered box, on page 5 at the bottom right, at about 4,436 on 19 Aug at 09:00.

> ▲ Q2• TRANSITION AREA • NOT YET STRONG DIRECTION • MARKET SELL AREA -
> * IN PREMIUM ZONE FUCUS ON BUY AREA •
> Q3 MARKET RUNNING XAMD BIAS •MARKET
> KILL LEVEL IN Q3 WE CSN FUCUS ON BUY
> LEVEL WHEN THE MARKET MANIPULATION
> ON THE DISCOUNT ZONE AREA

- "FUCUS" means FOCUS, "CSN" means CAN, and "XAMD" is illegible, and the box contradicts itself by saying "MARKET SELL AREA" and "IN PREMIUM ZONE FOCUS ON BUY AREA" in the same box, so copy it as printed and do not resolve it.

- Draw on Liquidity, black text, on page 3 in the footer truncated and on page 5 in full, at 4,324.855 on Tuesday 18 Aug at 12:00.

> DRAW ON LIQUIDITY, IS A CONDITION WHERE PRICES IS *PULLED* TOWARD A SPECIFIC LIQUIDITY ZONE BECAUSE A LARGE NUMBER OF ORDER [ STOP-LOSE AND PENDING ORDER ]

- "STOP-LOSE" is as printed and means STOP-LOSS.

- Box 5, Quarterly Theory intro, black text on page 7 at the right side, cropped at the right edge, still not drawn.

> QUATERLY THEORY IS A CONCEPT IN TRADIN[ G ]
> THAT DIVIDES PRICE MOVEMENT INTO FOUR [ QUARTERS ]
> BASIC CONCEPT
> PRICE WILL MOVE WITHIN A RANGE, AND THA[ T ]
> • Q2
> • Q3
> • Q4 HIGH

- "QUATERLY" and "TRADIN" are as printed and cropped, and Q4 is one word, "HIGH", on page 7.

- Box 6, Quarterly Theory legend, black text with coloured dots on page 7 at the right side, cropped, still not drawn.

> ● Q1 • ACCUMULATION MARKET
> CONSOLIDATE
> NOT CLEAR STRUCTURE
> ● Q2 • MANIPULATION
> TRANSITION AREA
> MARKET CAM M • IN THE QT KZ NOT
> YET STRONG ERECTION [DIRECTION]
> ● Q3 • DITRUSUTION [DISTRIBUTION]
> • FIND KEY LYL [LVL] ENTRY
> TRY IN FIRST ENTRY W/.MSNR
> START IN DISCOUNT

- "DITRUSUTION" means DISTRIBUTION, "LYL" means LVL, and "ERECTION" means DIRECTION, and "MARKET CAM M" and "QT KZ" are not expanded anywhere in the PDF.

- The Q4 legend line is cut off on page 7, and page 15 gives "Q4 - REVERSAL •CONTINUE / (DISCOURT ZONE) / EXPENSIVE PRICE / • SITABLE FOR SELL", which contradicts the Premium/Discount box where Q4 is the Premium Zone.

- Box 7, ERL box, black text in a grey bordered box, on pages 3 and 7, still not drawn.

> PRICES WILL MOVE FROM AN IMBALANCE TO TAKE EXTERNAL RANGES LIQUIDITY [ ERL ].

- The quartile percent box reads "SATYA • LOW TO HIGH/.PD" with Q1 0 to 25 percent [DISCOUNT DEEP] through Q4 75 to 100 percent [PREMUIM ZONE], and "PREMUIM" is as printed.

- The Quarterly Theory legend colours are Q1 black Accumulation, Q2 red Manipulation, Q3 green Distribution, and Q4 blue Reversal or Continue.

- The P8 positions above were verified non overlapping in the narrow Aug 17 to 20 view, but the boxes still pile and clip at the left edge in the wide Aug 12 to 20 view, so check both views before calling the spacing done.

## Structure labels and markers

- The PDF colour code on pages 3, 5, and 7 is strict and small, so black is the default for every structure and level label, gold is for key levels and entry thesis labels and two definition boxes, red is for a missed entry and warning triangles, orange-red is for the APEX label only, blue is for the APEX price tag and the APEX band fill only, and grey is for other price tags, zones, and box borders.

- Any blue text on the chart that is not "4,333.78" or the APEX band is wrong against the PDF.

- The eight black bracket labels are BOS+ with [ BREAK OF STRUCTURE ] for both breaks, SHIFT/.S- with [ MARKET STRUCTURE SHIFT ], CISD/.LVL^, [ INDUCEMENT ]+, TURTLE/.S, [ APEX CE/.LVL+ ]- 1, [ SELL SIDE LIQUIDITY ], and [ TRANDLINE ], with "TRANDLINE" spelled as printed.

- The [ APEX CE/.LVL+ ]- 1 label is orange-red in the PDF, not black, and it sits on the right side above the blue APEX band, with the red step-line above it.

- The P6 structure labels, all in black bracket text at size 12 bold unless stated, are [LAST LIQUIDITY] at 4,422.562 and at 4,316.208, [SINGLE L/Q] at 4,430.395, [QML] at 4,380.382, [FS+] at 4,358.990, [RBS/.LVL+] at about 4,364, a second [SHIFT] at 4,337.900, [KEY SELL MISS ENTRY] in red at 4,401.170, and [KEY/.HTF KEY REJECTION FIRST ENTRY+] in gold at 4,391.529.

- INDUCEMENT was assessed as already on the correct swing at 4,324.644 and was not moved in P6.

- TURTLE/.S sits at 4,316.322, and the PDF gives no price for it, so that is a placement choice, not a price error.

- BOS+ was placed at 19 Aug 06:00 at 4,448.285 in P1, and KEY/.LEVEL+ was placed at 18 Aug 03:00 at 4,398.650 in P1, then moved to gold at 4,394.988 in P5, which is 0.012 off 4,395.00 at the drag limit.

- FS+ was moved in P8 to Wednesday 19 Aug at 05:00 at 4,353.160, and that is the browser best interpretation, not verified against the PDF, so do not present it as a PDF fact.

- RESIS/.T DAILY was moved in P8 to 4,420.391 on Tuesday 18 Aug at 21:00, and KEY/.HTF was moved in P8 to 4,389.551 on Wednesday 19 Aug at 13:00.

- RESIS/.T DAILY is a grey rectangle from 4,399.965 to 4,412.318 with the label inside, drawn in P6.

- The pink 17 Aug session bar was drawn in P6 from 4,310.182 to 4,372.092, and redrawn in P8 from 4,405 at the top to 4,380 at the bottom, on bars minus 1296 to minus 1294, on 17 Aug from 12:00 to 14:00.

- The red APEX step-line is three short red solid segments with no diagonal, at 4,336.000 on bars minus 1257 to minus 1255 on Wednesday 19 Aug from 03:00 to 05:00, at 4,337.000 on bars minus 1255 to minus 1253 from 05:00 to 07:00, and at 4,338.000 on bars minus 1253 to minus 1251 from 07:00 to 09:00, stepping above the APEX band 4,333.78 to 4,335.59.

- The P6 Polyline attempt at the step-line drew a wrong teal diagonal and was deleted, and the P7 pass had only one of three segments and in grey not red, so build the step-line as three separate short horizontal lines and check the colour on each one.

- There is no literal X mark anywhere in the PDF, and what looks like cross boxes are red circle-cross markers, which are a red ring with a crosshair sitting exactly where a horizontal level crosses a vertical line dropped from a turtle sweep candle wick.

- The PDF carries 39 circle-cross markers, but only two transfer to the gold chart, at the TURTLE/.S foot at 4,311.31 and at the APEX band top at 4,335.59, and both were added in P7, while the other 20 belong on a separate entry model layout.

- The two yellow accumulation parallelograms are still not done correctly, and they are pale yellow, tilted minus 30 degrees over the 16 to 17 Aug down leg and plus 30 degrees over the 17 Aug evening leg.

- TradingView has no native Parallelogram tool, so the substitute is a Rotated Rectangle, and the P8 attempt came out as a thin green diagonal on the wrong leg, from Thursday 13 Aug 06:00 at about 4,400 to Monday 17 Aug 06:00 at 4,328.732, with no second parallelogram drawn.

- The light curved cross zone is not a separate curved object, and at 200 dpi it is two very faint light grey Fib Circle arcs crossing in an X over the 18 to 19 Aug manipulation leg, just left of the APEX band, which is why the Fib rebuild needs flatter arcs.

- The ERL 4,395.00 and CRT low wick anchors are still unverified, because TradingView horizontal lines expose no bar or date field in Settings, so the anchor is drag only and the handle was never dragged to those wicks.

- About nine small black dots and eight red and blue arrows on the M5 page are also still missing from the chart.

## Layout hygiene

- Hide LuxAlgo SMC, EMAs, VWAP, KZP, and EMA 9, because none of them are part of the PDF.

- "Clear all drawings" does not remove indicators, so hiding them is a separate step from clearing the drawings.

- Candles are black and white, because the user could not tell up from down when both were black: up candles are a white body with a black border, down candles are a solid black body, and wicks are black for both. This was changed and saved on the Aug layout on 23 Nov 2026. The PDF itself uses black and white candles, so this matches it. The labels are size 12 bold, which is visibly larger than the PDF labels at about size 10 to 11, so do not go larger, and consider size 11 for the three centre labels, because SL, BUY, and APEX sit only 1.46 to 2.31 apart and crowd each other.

- The line chart fallback works for the higher timeframe view, because the PDF uses line charts on pages 10 to 16, but it cannot carry the CRT range on gold, because that needs candle high and low.

- The M5 view for 19 Aug is blocked by the TradingView Basic 5,000 bar limit, which reaches about 17 days back, while 19 Aug is about 95 days back, so the M5 execution lines can only be drawn on the 1H layout for now.

- Rectangle and polyline anchors drift while selected in this layout, so re-read the stored price after every placement instead of trusting the price shown while dragging.

## Current market application

- To apply the method to the live market, pick a reference candle and state which candle it is, then compute its high, its low, and its 50 percent CE, then check whether price is in discount below the CE or premium above it, then look for the APEX style level where the trendline meets the CE in discount after a sell side sweep.

- State the CRT candle choice and the assumed Fib and STDV settings in the same message as the drawing, so another person can reproduce it from your words alone.

- The 22 Nov 2026 example is price 3,538.185, CRT 3,590 to 3,520, CE 3,555.00, APEX style CE 3,537.50, with price in discount, and its Fib Circle is hidden and needs unhiding through the Object Tree.

- The live example is a demonstration of the method, not a trade call, and no entry, stop, or target follows from it without a full setup the PDF never defines.

## Verification

- Verify every line three ways, because typing a price in Settings is necessary but not sufficient, and the pre-P4 comparison found the Settings value and the measured drawn line disagreeing by up to 0.92, with TP1 drawn at 4,444.27 while Settings said 4,445.29.

- Check the Settings value against the PDF value, then check the label text against the Settings value, then read the right axis tag off a fresh screenshot, and only call a line exact when all three agree.

- The tolerance for a key line is exact in Settings, which means 0.00 against the PDF value, and the drawn tag on the screenshot must read the same price, so any visible drift is a fail and the line must be re-placed by dragging.

| Check | PDF value | Drawn value | Result |
|---|---|---|---|
| CRT high / ERL | 4,395.00 | 4,395.00 | Exact |
| CRT low | 4,311.31 | 4,311.31 | Exact |
| CE 50 percent | 4,353.16 | 4,353.16 | Exact |
| APEX CE | 4,333.78 | 4,333.78 | Exact |
| BUY | 4,336.09 | 4,336.09 | Exact |
| SL | 4,337.55 | 4,337.55 | Exact |
| TP 4,445.19 | 4,445.19 | 4,445.19 | Exact, touched |
| TP 4,449.71 | 4,449.71 | 4,449.71 | Exact, untouched on M5 |
| FVG plus IRL top | 4,353.16 | 4,353.16 | Exact |
| FVG plus IRL bottom | 4,333.78 | 4,333.78 | Exact |
| APEX band top | 4,335.59 | 4,335.59 | Exact |
| APEX band bottom | 4,333.78 | 4,333.78 | Exact |
| Q2 band top | 4,353.16 | 4,353.16 | Exact |
| Q2 band bottom | 4,332.23 | 4,332.23 | Exact |
| STDV low end | 4,333.264 | 4,333.264 | Exact price, date unverified |
| KEY/.LEVEL+ | 4,395.00 | 4,394.988 | 0.012 off, drag limit |

- Score a comparison only from fresh screenshots, and never guess a rating, because the P7 score of about 6.5 given from memory was an unmeasured guess and was replaced by a measured 5.8.

- The comparison method is six side by side images, which are the full overview, the centre cluster, the TP area, the Fib Circle, the definition boxes, and the STDV and quarterly area, each scored out of 10, then averaged.

- The measured scores were P6 at 5.5 out of 10, with overview 6, centre 5, TP 8, Fib 5, boxes 5, and STDV and quarterly 4, and P7 at 5.8 out of 10, with overview 6, centre 6, TP 8, Fib 6, boxes 5, and STDV and quarterly 4, and P8 at 6.5 out of 10, with overview 6.5, centre 7, TP 8, Fib 6, boxes 5.5, and STDV and quarterly 6, and P9 at 6.8 out of 10, with overview 7, centre 7, TP 8, Fib 7, boxes 6, and STDV and quarterly 6.

- The TP area scores best at 8 out of 10 in every pass, and the definition boxes score worst at 5.5 out of 10 in P8, after the STDV and quarterly area scored worst at 4 out of 10 in P6 and P7.

- A four agent audit of the early redraw against the PDF found text at 133 items with 0 exact, 12 partial, and 121 missing, and geometry at 204 items with 0 exact, 11 wrong, and 193 missing, which shows how far a first attempt can be even when the prices feel right.

- The known leftovers after P8, ranked by visual impact for the next pass, are: the definition boxes still overlap, with [SINGLE L/Q] on the Premium box, RESIS/.T DAILY on the Premium box, the Q2 Transition and Discount Zone boxes overlapping at the corner, and [KEY SELL MISS ENTRY] on the High Risk Confirmation box edge, and the P8 claim that the boxes were "verified non-overlapping in the narrow view" is contradicted by the P8 comparison images, which show the overlaps in both views, so re-verify with a fresh screenshot before calling the spacing done; the yellow accumulation parallelograms still not done correctly, with the one Rotated Rectangle as a thin green diagonal on the wrong leg and no second parallelogram; the Fib arcs still near vertical in the narrow frame, and radii 400 and 600 both fail there, so fix the geometry, not the radius, by trying the wide Aug 12 to 20 view for the comparison or the Arc tool instead of the Fib Circle tool; the circle bars finished in P8 but with no DAILY CIRCLE, 90M CIRCLE, or MACRO labels and the Q2/.M dot not centred under segment 2; the red step-line too small to read, with the PDF version a long red line with a spike at the right end; FS+ still partly hidden behind a 19 Aug candle; the minus 4 and minus 3.5 STDV marks still absent; the quarter boxes still clipped at the right edge in the narrow view; and the M5 view for 19 Aug still blocked by the Basic plan.
- P9 verification check on 23 Nov 2026 (browser read of the chart, no P9 completion report ever arrived): the two yellow parallelograms ARE now present as pale yellow Rotated Rectangles, the boxes do NOT overlap each other in the narrow view centred on 18 Aug, [SINGLE L/Q] and RESIS/.T DAILY are clear of the Premium box, FS+ is clear, and the black/white candle fix is saved. Still failing: candles run through the Premium box and the Discount Zone's left edge, KEY SELL and HTF KEY REJECTION labels overlap the High Risk Confirmation box text, the grey Fib arcs still read as near-vertical (anchors 4,724.29 / 3,924.29, only 24 bars apart), the red step-line could not be confirmed as three segments at 4,336 / 4,337 / 4,338, and the 90M CIRCLE / MACRO labels and the black "● Q2/.M" dot under segment 2 were not seen. The P9 comparison then measured 6.8 out of 10 overall (overview 7, centre 7, TP 8, Fib 7, boxes 6, STDV and quarterly 6), up from P8's 6.5, and it corrected two of the verification claims: the 3 Arc-tool shallow arcs ARE in the Object Tree, and DAILY CIRCLE / 90M CIRCLE / MACRO labels are all three visible. It also found both the arcs AND the Fib Circle present at once, which the P9 brief said never to leave, and the "● Q2/.M" dot lost entirely — not visible in any screenshot or in the Object Tree. The Object Tree text count came back as 39, which shows the earlier 21 and 23 counts were never reliable, because the tree only loads part of itself at a time. The ranked P10 fix list is: pick ONE Fib geometry and remove the other (keep the shallow arcs, delete or hide the Fib Circle); restore the Q2/.M dot centred under segment 2; finish the boxes so no candle or label crosses any box text and nothing clips at the right edge, verified in narrow AND wide views; step-line as the PDF's long red line with the spike at the right end; verify STDV ticks −2.5 / −2 / −1 / 0; draw the TRANDLINE diagonal; wick anchors via handle-drag plus screenshot.

## Hard limits

- Exact drawing is not replicable from the PDF alone, and the undefined items are the CRT candle selection rule, the rejection definition, the key level selection rule, the zone edge rule, the Fib Circle construction, the STDV formula, the circle bar mapping, and the higher timeframe to lower timeframe drop.

- The PDF gives no entry formula, no stop distance, no lot size, no risk percent, no risk to reward ratio, no session times, no backtest, no win rate, and no profit and loss in its 34 pages.

- The only complete trades shown are page 9, the M5 buy at 4,336.09 to TP1 at 4,445.19 touched, and page 27, the plus 361.63 points hold with no stop, exit, lot, or profit and loss.

- The PDF is internally inconsistent by 0.07 to 0.44 across pages, and it carries garbled blocks in Thai, Khmer, and romanised Khmer that are untranslated, plus stray prices 3,257.96 on page 32 and 3,543.47 on page 33 that do not match gold here, which suggests pages compiled from different charts and dates.

- The Fib Circle appears on the US30 Quarterly chart only in the original reading, and the gold arcs were found only later at 150 dpi, so any claim about which chart carries the circle must say which reading it comes from.

- The Quarterly Theory text is cropped at the right edge on pages 7 and 15, and the Q4 legend line is cut off, so do not complete cropped text from a guess.

- Never present an assumption as the PDF rule, and label every assumed value, every placement choice, and every mirror anchor as an assumption in the same sentence where you use it.

- The honest ceiling for this chart is about 9 out of 10, because the Fib values, the STDV mapping, and the M5 touch arrows are unstated in the PDF or blocked by the Basic plan.

## Second worked example

- The second MSNR PDF, by TraFx_Trade in Oct 2026, is a second worked example in the same method family, and it is not the primary example for this skill.

- Its silver trade is a sell from 71.143 to 54.604, plus 20,462.50 USD at 0.25 lot, Trade 16, on 29 Oct 2026, with SL 71.556 to 71.557 and TP 54.776.

- Its gold trade is a ladder short to ERL 3,976.17, with measured moves plus 737.484, or plus 18.70 percent, and minus 687.471, or minus 14.85 percent.

- Its two higher timeframe to lower timeframe ladders in words are silver monthly PROFILE, weekly MAJORITY, daily MINORITY, and gold daily PROFILE, H1 MINORITY plus MSS, H4 MAJORITY plus CONFIRM.

- Its neatness system is 0 to 8 labels per page, thin 1 pixel black lines, one zone per page, dotted for reference, solid for structure, dashed for trendline, yellow zone, red dot touch, X invalidation, and green tick validation.

- Its style is replicable and its exact drawing is not, because it gives no PROFILE rule, no thresholds, and no Fib or STDV construction, and its XAGUSD lows are unreconciled at 54.776, 54.604, 52.707, 52.758, and 52.085.

## How to use this skill in another Muse

- Install this file at ~/workspace/custom-skills/alchemist-msnr-tradingview-drawing/SKILL.md, or clone the repository that carries it, and read it before you start drawing.

- You need three prerequisites before you draw, which are TradingView access in the browser, the user's login for the account that holds the chart, and the user's own copy of the 34 page PDF.

- Without the login you can still read the PDF, plan the drawing, and write the exact values and steps, but you cannot place anything on the user's chart.

- Without the PDF you can still reproduce the worked gold example from the values in this skill, but you cannot verify the drawing against the source, and you must say that the verification step was skipped.

- Start every drawing session by reading the verification section and the hard limits section, then draw the eight key lines first, then the zones and bands, then the Fib Circle, then the STDV, then the circle bars, then the definition boxes, then the structure labels, and score the result only from fresh screenshots.

- Report the score honestly, list what is still missing, and never call the drawing 10 out of 10.

- If the user asks for a trade, a live entry, or a position size, stop, because this skill covers drawing only and no trade was ever placed with it.

## Sources

- The merged analysis of the 34 page PDF is at workspace/research_notes/alchemist-pdf-merged/report.md, with per chunk reports for pages 1 to 9, 10 to 17, 18 to 25, and 26 to 34 in the same folder.

- The redraw verification sheet is at workspace/research_notes/alchemist-tradingview-redraw-checklist.md.

- The P7 comparison report is at workspace/research_notes/alchemist-comparison/final/p7-comparison-report.md, with the P6 comparison at workspace/research_notes/alchemist-comparison/final/p6-comparison-report.md, and the P8 comparison report at workspace/research_notes/alchemist-comparison/final/p8-comparison-report.md, which measured 6.5 out of 10 overall, up from 5.8 at P7, with the biggest single-pass gain since P5, driven by the circle bars, the red step-line, and the restored STDV low end. The P9 comparison report at workspace/research_notes/alchemist-comparison/final/p9-comparison-report.md measured 6.8 out of 10 overall, up from P8's 6.5, driven by the black and white candles, the re-spaced boxes, both yellow parallelograms, and the shallow Arc-tool arcs.

- The TP audit is at workspace/research_notes/alchemist-tp-audit.md, the text and colour audit is at workspace/research_notes/alchemist-text-colour-audit-p4.md, the missing items audit is at workspace/research_notes/alchemist-missing-audit-p4.md, and the Fib, STDV, and quarterly re-check is at workspace/research_notes/alchemist-fib-stdv-quarterly-p4.md.

- The second PDF merged report is at workspace/research_notes/razyxh-pdf-merged/report.md, and the neat drawing skill sheet is at workspace/research_notes/razyxh-pdf-merged/neat-drawing-skill.md, and both are also in this repository under references/.

- The source PDF itself is not included in this skill or in the repository, because it is the creator playbook at 22 MB, and the user supplies their own copy.
