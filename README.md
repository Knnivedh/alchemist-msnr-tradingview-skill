# Alchemist MSNR TradingView Drawing Skill

A deep, honest skill for reproducing the Alchemist MSNR chart drawing in TradingView, built from a 34-page image-only playbook by Satya Alchemist (@SATYA666.SS) and from the worked gold example that was drawn through eight passes (P0–P8) in November 2026.

## What it is

- `SKILL.md` teaches the method: Candle Range Theory plus CE (one reference candle's high/low is the range, CE is its 50%), premium/discount, APEX CE, zones captured by confluence, and validation by price reaction only.
- It gives the worked gold example (XAUUSD, 17–20 Aug 2026) with every key line at its exact verified price, the Fib Circle and STDV procedures as they were actually done in TradingView, the circle bars, the definition boxes in the PDF's own verbatim wording, the structure labels, and the verification method used to score the drawing.
- It is scored honestly: the drawing measured 5.5/10 after P6 and 5.8/10 after P7, and the honest ceiling is about 9/10, not 10.

## What it cannot do

This skill transfers the **method** — the rules, the exact values, the procedures, and the verification steps. It does **not** transfer a logged-in TradingView session or access to the user's TradingView account. A Muse that receives this skill still needs its own TradingView access and the user's login to draw in the user's account, plus the user's own copy of the PDF to verify against the source.

Exact drawing is **not** replicable from the PDF alone. The CRT candle selection rule, the rejection definition, the zone-edge rule, the Fib Circle construction, the STDV formula, and the higher-timeframe to lower-timeframe drop are all undefined in the PDF. Every assumption in the skill is labelled as an assumption, and the skill must never be used to present one as the PDF's rule.

No trade is ever placed with this skill. Nothing here is trading advice or a promise of profit.

## Install in another Muse

1. Copy `SKILL.md` to `~/workspace/custom-skills/alchemist-msnr-tradingview-drawing/SKILL.md` in the receiving Muse's workspace, or clone this repository and point the Muse at it.
2. Make sure the receiving Muse has TradingView access in its browser, the user's login for the account that holds the chart, and the user's own copy of the 34-page PDF.
3. Read the skill before drawing. Without the login it can plan but not place anything; without the PDF it can reproduce the worked example but cannot verify against the source.

## The worked gold example at a glance

| Line | Price |
|---|---|
| CRT high / ERL | 4,395.00 |
| CRT low | 4,311.31 |
| CE 50% | 4,353.16 |
| APEX CE | 4,333.78 |
| BUY | 4,336.09 |
| SL | 4,337.55 |
| TP 4,445.19 | 4,445.19 (touched) |
| TP 4,449.71 | 4,449.71 (untouched on M5) |

The SL sits 1.46 **above** the buy — inverted for a long, unexplained in the PDF, copied faithfully and never silently "fixed". The PDF labels only the 4,449.71 line as "TP" (red dashed, M5, page 9); the 4,445.19 line carries no label (red dotted). "TP1"/"TP2" appear nowhere in the PDF.

The FVG + IRL zone is a grey rectangle from 4,353.16 down to 4,333.78, the blue APEX band is exactly 4,333.78 to 4,335.59, and the Q2 Manipulation band is 4,332.23 to 4,353.16. The Fib Circle is mirror-centred on the swing low 4,324.29 (P8: radius 400, anchors 4,724.29 / 3,924.29, levels 1 / 2.35 / 2.55 only). The STDV is a thin grey dashed diagonal with −2.5 / −2 / −1 / 0 ticks, low end 4,333.264.

## Repo layout

```
.
├── README.md
├── SKILL.md                  # the skill (same file as in custom-skills)
├── LICENSE                   # MIT, copyright K N Nivedh Bhat, 2026
├── .gitignore
└── references/
    ├── alchemist-pdf-merged-report.md        # merged analysis of the 34-page PDF
    └── alchemist-tradingview-redraw-checklist.md  # redraw verification sheet
```

## The source PDF

The 34-page source PDF is **not** included in this repository. It is the creator's playbook (22 MB, image-only), so the user supplies their own copy. The skill and the references are enough to reproduce the worked example and to verify a drawing, but the PDF itself is needed to verify against the source.

## Sources

- Merged PDF analysis: `references/alchemist-pdf-merged-report.md` (per-chunk reports for pages 1–9, 10–17, 18–25, 26–34 are cited in `SKILL.md`)
- Redraw verification sheet: `references/alchemist-tradingview-redraw-checklist.md`
- P7 comparison report, TP audit, text/colour audit, missing-items audit, and Fib/STDV/quarterly re-check are cited by path in `SKILL.md` under "Sources"
- Second MSNR PDF (TraFx_Trade, Oct 2026) merged report: cited in `SKILL.md`; it is a second worked example only, not the primary example

## License

MIT. See `LICENSE`.
