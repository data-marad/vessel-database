# vessel-database
An open source guide to creating a database of vessels. 

┌──────────────────────────────────────────────────────────────┐
│  LOGO        Vessel Data Workbook                            │
│  [About] [Data Sources] [Methodology] [Build Your List] [Git]│
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│  HERO / TAGLINE                                              │
│  “Open, reproducible tools to identify the U.S. merchant and │
│   support fleet — and vessels trading in U.S. waters.”        │
│  [Get Started]  [Download Starter Pack]  [View on GitHub]     │
└──────────────────────────────────────────────────────────────┘

┌───────────────┬───────────────────────────────────────────────┐
│ QUICK START   │  HOW IT WORKS (3 STEPS w/ icons)              │
│ 1. Clone repo │  1. Collect raw data                          │
│ 2. Load ETL   │  2. Normalize & join                          │
│ 3. Filter     │  3. Export your fleet list                    │
│ [Read Guide]  │  [View Methodology]                           │
└───────────────┴───────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│  DATA SOURCE CATALOG (search + filters)                      │
│  [Search box...................................] [Filters▼]  │
│  ┌─────────────────────────────────────────────────────────┐ │
│  │ USCG “Merchant Vessels of the US”   Updated: Dec 2024   │ │
│  │ Fields: Name, Official #, IMO, GT, …                    │ │
│  │ License: Public domain | [Schema] [ETL Script] [Download]│ │
│  ├─────────────────────────────────────────────────────────┤ │
│  │ MARAD U.S.-Flag Fleet List        Updated: Jan 2025     │ │
│  │ …                                                     … │ │
│  └─────────────────────────────────────────────────────────┘ │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│  INTERACTIVE SCHEMA / DATA MODEL DIAGRAM                     │
│  (small thumbnail → expand modal)                            │
│  Core_Vessel  ←→  USCG_MVU  ←→  MARAD_Fleet  ←→  AIS_Calls   │
│                 ↓                ↓                           │
│              Owners          Vessel_Types                    │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│  BUILD YOUR LIST (wizard-style or notebook preview)          │
│  Step 1: Pick universe  [U.S.-flag] [Foreign-in-U.S.] [Both] │
│  Step 2: Filter fields  [Type][Size][Year][Operator]…        │
│  Step 3: Output format  [CSV][SQL dump][GeoJSON]             │
│  [Generate Sample]  [Copy Query]  [Download]                 │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│  EXAMPLES & TUTORIALS                                        │
│  • “Recreate the U.S.-flag tanker fleet (10k+ DWT)”          │
│  • “Tag foreign vessels calling U.S. ports (2022–2024)”      │
│  • “Join AIS tracks to vessel master table”                  │
│  [View Notebooks]                                            │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│  COMMUNITY & GOVERNANCE                                      │
│  Contribute | Issues | Data refresh schedule | Code of Conduct│
│  Contact: MARAD | CMTS                                        │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│  FOOTER                                                      │
│  © MARAD / CMTS 2025 | MIT License | Accessibility | Privacy │
└──────────────────────────────────────────────────────────────┘
