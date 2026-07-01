# AI² Index — Data Correction Changelog (Pass 7 candidate)

Formula verified against model workbook: **AI² = min(100, 25 × (Raw − 1))**, Raw = 0.5·Auto + 0.45·Econ + 0.1·AII − 0.15·LLL − 0.15·Ethics + 0.25·Prec. Rescored rows use the exact formula with per-occupation AII from the workbook; untouched rows keep published values bit-for-bit.

**Headline stats:** mean 60.0 → **59.4** | High 37.7% → **34.7%** | Medium 53.8% → **56.8%** | Low 8.5% → **8.5%**

## 1. Precedence = 0 repairs (defect present in workbook too)

- **Insurance Underwriters** — prec 0→4 (automated underwriting widely deployed). AI² 33.0 → **57.9** [Low (5+ yrs) → Medium (2–5 yrs)]
- **Graders and Sorters of Agricultural Products** — prec 0→4 (AI/optical sorting ubiquitous). AI² 42.2 → **67.3** [Medium (2–5 yrs) → High (<2 yrs)]
- **Aircraft Cargo Handling Supervisors** — prec 0→2 (limited supervisory automation precedent). AI² 35.3 → **47.8** [Medium (2–5 yrs) → Medium (2–5 yrs)]
- **Floor Sanders and Finishers** — prec 0→1; auto 4.78→3.0 (physical trade cap). AI² 60.5 → **44.5** [Medium (2–5 yrs) → Medium (2–5 yrs)]
- **Dredge Operators** — prec 0→2 (autonomous dredging pilots exist, rare). AI² 33.3 → **45.8** [Medium (2–5 yrs) → Medium (2–5 yrs)]
- **Pile-Driver Operators** — prec 0→1 (no automation precedent). AI² 17.0 → **23.2** [Low (5+ yrs) → Low (5+ yrs)]

## 2. Installation & Repair adjustments (item 3)

Rule: hands-on SOC 49-xxxx trades (plus Carpet Installers and Solar PV Installers) with Automability > 3.0 capped at 3.0 — agents automate diagnostics, scheduling, and documentation, not the physical core. Millwrights, Fabric Menders, Installation/Maintenance & Repair Workers, and Maintenance & Repair Workers additionally EconViability 4→3 (physical delivery required; rubric reserves 4–5 for near-pure software). Result: zero I&R occupations remain in the High tier; sector mean falls 60.8 → 51.1.

- **Bicycle Repairers** — auto 4.56→3.0. AI² 65.0 → **45.6**
- **Bus and Truck Mechanics and Diesel Engine Specialists** — auto 4.11→3.0. AI² 60.1 → **46.2**
- **Camera and Photographic Equipment Repairers** — auto 3.89→3.0. AI² 67.2 → **56.1** [High (<2 yrs) → Medium (2–5 yrs)]
- **Carpet Installers** — auto 4.22→3.0. AI² 73.2 → **58.0** [High (<2 yrs) → Medium (2–5 yrs)]
- **Coin, Vending, and Amusement Machine Servicers and Repairers** — auto 4.44→3.0. AI² 71.2 → **53.1** [High (<2 yrs) → Medium (2–5 yrs)]
- **Computer, Automated Teller, and Office Machine Repairers** — auto 4.0→3.0. AI² 71.0 → **58.5** [High (<2 yrs) → Medium (2–5 yrs)]
- **Control and Valve Installers and Repairers** — auto 4.44→3.0. AI² 72.0 → **54.0** [High (<2 yrs) → Medium (2–5 yrs)]
- **Electric Motor, Power Tool, and Related Repairers** — auto 4.11→3.0. AI² 66.4 → **52.6** [High (<2 yrs) → Medium (2–5 yrs)]
- **Electrical Power-Line Installers and Repairers** — auto 4.17→3.0. AI² 72.8 → **58.2** [High (<2 yrs) → Medium (2–5 yrs)]
- **Electrical and Electronics Installers and Repairers, Transportation Equipment** — auto 3.67→3.0. AI² 56.9 → **48.6**
- **Electrical and Electronics Repairers, Commercial and Industrial Equipment** — auto 3.89→3.0. AI² 64.5 → **53.4**
- **Electrical and Electronics Repairers, Powerhouse, Substation, and Relay** — auto 3.89→3.0. AI² 62.0 → **50.9**
- **Electronic Equipment Installers and Repairers** — auto 4.0→3.0. AI² 72.3 → **59.8** [High (<2 yrs) → Medium (2–5 yrs)]
- **Electronic Home Entertainment Equipment Installers and Repairers** — auto 3.67→3.0. AI² 65.4 → **57.1**
- **Fabric Menders** — econ 4→3. AI² 71.8 → **60.6** [High (<2 yrs) → Medium (2–5 yrs)]
- **Farm Equipment Mechanics** — auto 4.11→3.0. AI² 65.2 → **51.4**
- **Heating, Air Conditioning, and Refrigeration Mechanics and Installers** — auto 4.11→3.0. AI² 60.3 → **46.4**
- **Home Appliance Repairers** — auto 3.89→3.0. AI² 71.6 → **60.5** [High (<2 yrs) → Medium (2–5 yrs)]
- **Industrial Machinery Mechanics** — auto 3.67→3.0. AI² 63.4 → **55.1**
- **Installation, Maintenance, and Repair Workers** — auto 3.89→3.0, econ 4→3. AI² 81.5 → **59.2** [High (<2 yrs) → Medium (2–5 yrs)]
- **Locksmiths and Safe Repairers** — auto 4.56→3.0. AI² 66.3 → **46.9** [High (<2 yrs) → Medium (2–5 yrs)]
- **Maintenance Workers, Machinery** — auto 3.78→3.0. AI² 52.3 → **42.6**
- **Maintenance and Repair Workers** — econ 4→3. AI² 70.7 → **59.5** [High (<2 yrs) → Medium (2–5 yrs)]
- **Managers of Mechanics, Installers, and Repairers** — auto 3.56→3.0. AI² 52.5 → **45.6**
- **Manufactured Building and Mobile Home Installers** — auto 3.67→3.0. AI² 59.6 → **51.3**
- **Mechanical Door Repairers** — auto 4.22→3.0. AI² 69.8 → **54.6** [High (<2 yrs) → Medium (2–5 yrs)]
- **Medical Equipment Repairers** — auto 4.11→3.0. AI² 57.1 → **43.3**
- **Millwrights** — econ 4→3. AI² 69.4 → **58.2** [High (<2 yrs) → Medium (2–5 yrs)]
- **Mobile Heavy Equipment Mechanics** — auto 3.89→3.0. AI² 65.4 → **54.3**
- **Motorboat Mechanics** — auto 4.11→3.0. AI² 61.2 → **47.3**
- **Musical Instrument Repairers and Tuners** — auto 3.89→3.0. AI² 65.0 → **53.9**
- **Outdoor Power Equipment and Other Small Engine Mechanics** — auto 4.22→3.0. AI² 66.5 → **51.2** [High (<2 yrs) → Medium (2–5 yrs)]
- **Radio Mechanics** — auto 4.11→3.0. AI² 66.1 → **52.2** [High (<2 yrs) → Medium (2–5 yrs)]
- **Rail Car Repairers** — auto 4.44→3.0. AI² 76.8 → **58.8** [High (<2 yrs) → Medium (2–5 yrs)]
- **Recreational Vehicle Service Technicians** — auto 3.33→3.0. AI² 48.0 → **43.8**
- **Refractory Materials Repairers** — auto 3.89→3.0. AI² 55.1 → **44.0**
- **Security and Fire Alarm Systems Installers** — auto 4.0→3.0. AI² 40.0 → **27.5** [Medium (2–5 yrs) → Low (5+ yrs)]
- **Signal and Track Switch Repairers** — auto 4.67→3.0. AI² 73.8 → **52.9** [High (<2 yrs) → Medium (2–5 yrs)]
- **Solar Photovoltaic Installers** — auto 3.89→3.0. AI² 67.7 → **56.6** [High (<2 yrs) → Medium (2–5 yrs)]
- **Telecommunications Line Installers and Repairers** — auto 4.44→3.0. AI² 73.2 → **55.1** [High (<2 yrs) → Medium (2–5 yrs)]
- **Tire Repairers and Changers** — auto 3.89→3.0. AI² 70.8 → **59.7** [High (<2 yrs) → Medium (2–5 yrs)]
- **Watch Repairers** — auto 4.11→3.0. AI² 71.7 → **57.9** [High (<2 yrs) → Medium (2–5 yrs)]
- **Wind Turbine Service Technicians** — auto 3.56→3.0. AI² 58.9 → **52.0**

## 3. Sector realignment

396 occupations reassigned to their SOC major-group sector. Fixes the flagrant errors (Heavy Truck Drivers, Chiropractors, Court Reporters, Credit Authorizers, Nuclear Power Reactor Operators in 'Arts & Media'; Airline Pilots, Locomotive Engineers, Ship Engineers in 'Architecture & Engineering') and empties the 46% 'Other' bucket. First-line supervisors already labeled Management preserved as a design choice; 27 SOC-less manager rows unchanged.

## 4. Employment repairs (box size = workers)

Order-of-magnitude outliers replaced with BLS OEWS values. Fish & Game Wardens verified directly against BLS (~1,480); others from OEWS figures, rounded — treat as approximate. Systematic placeholder repetition (64,000 ×25, 73,000 ×21, 80,000 ×19…) remains elsewhere in the column; the durable fix is a scripted SOC-crosswalk rejoin to the OEWS national file.

- **Aircraft Structure, Surfaces, Rigging, and Systems Assemblers** — 1,487,000 → **30,000**
- **Fiberglass Laminators and Fabricators** — 1,487,000 → **17,000**
- **Child Care Workers** — 1,430,000 → **500,000**
- **Special Education Teachers in Preschools** — 1,217,000 → **22,000**
- **Telephone Operators** — 1,135,000 → **4,600**
- **Reservation and Transportation Ticket Agents and Travel Clerks** — 1,014,000 → **125,000**
- **Managers of Farming, Fishing, and Forestry Workers** — 942,000 → **50,000**
- **Fish and Game Wardens** — 822,000 → **1,500**
- **Farm and Home Management Advisors** — 742,000 → **12,000**
- **Drywall and Ceiling Tile Installers** — 722,000 → **96,000**
- **Dredge Operators** — 479,000 → **1,500**
- **Mechanical Door Repairers** — 440,000 → **27,000**
- **Private Household Cooks** — 438,000 → **1,000**
- **Tool and Die Makers** — 399,000 → **60,000**
- **Correspondence Clerks** — 333,000 → **3,500**
- **Nurse Midwives** — 232,000 → **7,000**
- **Medical Transcriptionists** — 217,000 → **49,000**
- **Pile-Driver Operators** — 80,000 → **3,900**
- **Nurse Practitioners** — 39,000 → **280,000**
- **Dental Hygienists** — 12,000 → **226,000**

## Verdict on the workbook (item 1)

The uploaded spreadsheet is stale relative to the published heat map: 388 of 738 rows differ, Precedence disagrees on 279 rows (workbook mostly pre-review 5s), and 20 workbook rows have Raw Index hardcoded to 5.0, forcing AI²=100 (Shampooers, Barbers, Commercial Divers all read 100 there). The published heat map (Pass 6) was treated as authoritative for all dimension values except the fixes above. The six prec=0 defects exist in both artifacts — they originated in the workbook and were carried through every pass.

Tier thresholds unchanged: Low ≤33 · Medium 34–66 · High >66.