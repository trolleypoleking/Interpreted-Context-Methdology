# Clear-Out Inventory

Running catalog of hardware for a clear-out. Specs only — valuation deferred to the end.

Status legend: 🔲 not yet priced · 💲 priced · ❓ needs reshoot/clarification

---

## RAM Valuation (AUD, rough used-market ballparks — June 2026)

Non-waste items only. Ranges assume working, decent condition; postage + fees eat into singles.

| Item | Ballpark (AUD) | Call |
|------|----------------|------|
| R10 — Samsung 8GB DDR4-2400 SODIMM | $22–34 | ⭐ Sell solo — best item |
| R12+R13 — G.Skill RipjawsX 8GB DDR3-1333 kit | $19–29 | Sell as kit |
| R14 — Crucial 8GB DDR3L-1600 SODIMM | $15–27 | Sell solo |
| R3+R4 — GeIL 8GB DDR3-1866 kit | $15–23 | Sell as kit |
| R7+R8 — GeIL 8GB DDR3-1333 kit | $11–19 | Sell as kit |
| R9 — Kingston 4GB DDR4-2666 SODIMM | $9–17 | Sell or bundle |
| R5+R6 — Unifosa 2×2GB DDR3-1333 | $4–8 | Bundle (marginal) |
| **Estimated total (worthwhile lot)** | **~$95–155** | |

**Waste / bin (not worth listing):** R1 (512MB DDR2-533), R2 (1GB DDR2-667), R11 (1GB DDR2-800 SODIMM).

---

## RAM

| # | Type / Speed | Capacity | Rank | Brand | Part Number | Notes | Status |
|---|--------------|----------|------|-------|-------------|-------|--------|
| R1 | DDR2-533 (PC2-4200U) | 512 MB | 1Rx8 | Nanya | NT512T64U88A0BY-37B | Desktop DIMM | 💲 |
| R2 | DDR2-667 (PC2-5300) | 1 GB | — | Apogee | AU1G082-667P000 | CL5, desktop DIMM | 💲 |
| R3 | DDR3-1866 (PC3-14900) | 4 GB | — | GeIL | GOC38GB1866C9DC | CL9, 1.5V, desktop DIMM. **Matched pair w/ R4** (8GB kit) | 💲 |
| R4 | DDR3-1866 (PC3-14900) | 4 GB | — | GeIL | GOC38GB1866C9DC | CL9, 1.5V, desktop DIMM. **Matched pair w/ R3** (8GB kit) | 💲 |
| R5 | DDR3-1333 | 2 GB | 128Mx8 | Unifosa | GU512303EP0202 | 1.5V, desktop DIMM (single) | 💲 |
| R6 | DDR3-1333 | 2 GB | 128Mx8 | Unifosa | GU512303EP0202 | 1.5V, desktop DIMM (single) | 💲 |
| R7 | DDR3-1333 (PC3-10600) | 4 GB | — | GeIL | GD38GB1333C9DC | CL9, 1.5V, desktop DIMM. **Matched pair w/ R8** (8GB kit) | 💲 |
| R8 | DDR3-1333 (PC3-10600) | 4 GB | — | GeIL | GD38GB1333C9DC | CL9, 1.5V, desktop DIMM. **Matched pair w/ R7** (8GB kit) | 💲 |
| R9 | DDR4-2666 (PC4-21300) | 4 GB | 1Rx16 | Kingston (HP OEM) | HP26D4S9S1MEF-4 | SODIMM (laptop) | 💲 |
| R10 | DDR4-2400 (PC4-19200) | 8 GB | 1Rx8 | Samsung | M471A1K43BB1-CRC | SODIMM (laptop) | 💲 |
| R11 | DDR2-800 (PC2-6400S) | 1 GB | 2Rx16 | Samsung | M470T2864EH3-CF7 | SODIMM (laptop) | 💲 |
| R12 | DDR3-1333 (PC3-10666) | 4 GB | — | G.Skill RipjawsX | F3-10666CL9D-8GBXL | CL9, 1.5V, desktop DIMM. **Matched pair w/ R13** (8GB kit) | 💲 |
| R13 | DDR3-1333 (PC3-10666) | 4 GB | — | G.Skill RipjawsX | F3-10666CL9D-8GBXL | CL9, 1.5V, desktop DIMM. **Matched pair w/ R12** (8GB kit) | 💲 |
| R14 | DDR3L-1600 (PC3L-12800) | 8 GB | — | Crucial (Micron) | CT102464BF160B.M16FN | CL11, 1.35V. **Installed in NUC (S1) — not sold separately; value absorbed into unit** | 💲 |

---

## Systems

| # | Item | Specs | Status | Ballpark (AUD) | Notes |
|---|------|-------|--------|----------------|-------|
| S1 | Intel NUC5i5RYH ("Rock Canyon", mfg 05/2017) | i5-5250U (2c/4t, Broadwell), Intel HD 6000, 8GB DDR3L (R14), 240GB M.2 SSD, 2.5" bay free | Working / tested | **KEEP** | 🚫 NOT FOR SALE — repurposed as Tailscale exit node (AU residential IP). Find 19V/3.43A PSU in cable pile; set BIOS auto-power-on-after-AC-loss; enable Tailscale SSH + disable key expiry |

---

## Single-Board Computers

| # | Item | SoC / RAM | Status | Ballpark (AUD) | Notes |
|---|------|-----------|--------|----------------|-------|
| B1 | Rock64 V2.0 (2017) | RK3328 / **4GB** | Untested | **$50–75** | Top RAM variant — most desirable. Board only; barrel-jack power |
| B2 | Raspberry Pi 1 Model B+ V1.2 (2014) | BCM2835 single-core / 512MB | Untested | $10–18 | Low demand; light/collector use |
| B3 | Raspberry Pi 3 Model B V1.2 (2015) | BCM2837 quad-core / 1GB | Untested | $30–45 | microUSB power |
| B4 | Raspberry Pi 3 Model B V1.2 (2015) | BCM2837 quad-core / 1GB | Untested | $30–45 | microUSB power |
| B5 | Orange Pi One V1.1 | Allwinner H3 quad-core / 512MB | Untested | $10–20 | Niche; weaker software support |

*SBC subtotal: ~A$130–203 (if selling all). Consider keeping one Pi 3 as a travel tinker board.*

---

## Audio / DJ Gear

| # | Item | Condition | Ballpark (AUD) | Notes |
|---|------|-----------|----------------|-------|
| A1 | Numark M101 USB — 2-ch USB DJ mixer | Boxed, complete | **$50–90** | Box + unit. New ~$120 |
| A2 | Allen & Heath ZED-12FX mixing console (AU model) | Boxed, complete | **$250–400** | ⭐ Star item — holds value well, new ~$700+. Test channels/FX before sale |
| A3 | Numark TTX1 direct-drive turntable | "Beat up", no box | **TBD — rough $200–400 ea** | ⏳ Awaiting photos. Pair of them. Condition-dependent; pitch/platter/tonearm function drives price |

---

## PC Components (cases / PSUs)

| # | Item | Condition | Ballpark (AUD) | Notes |
|---|------|-----------|----------------|-------|
| C1 | Fractal Design Arc Midi R2 (FD-CA-ARC-R2-BL-W, black + window) | Used | **$60–110** | Confirmed "the big Fractal". Discontinued classic, good builder demand |
| C2 | Thermaltake 500W PSU (TT-500NL1NH-1) | Used | **$15–35** | ⚠️ Aging PSU — many buyers avoid used PSUs; bundle or sell cheap/as-is |

---
