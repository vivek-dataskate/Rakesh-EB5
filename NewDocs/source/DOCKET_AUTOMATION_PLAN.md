# EB-5 Docket Automation Plan
**Petitioner:** Bhargavi Jaggarapu | Receipt: IOE0934124117 | A-Number: A138-176-449
**Response Deadline: July 6, 2026**
**Last updated:** June 13, 2026

**Docket root:** https://drive.google.com/drive/u/1/folders/0ALgmUtYnXvW3Uk9PVA
**Sync routine:** trig_01YD9atrhb6SStwi1BCqjUjV (every 6 hours — auto-copies source → docket)
**Manual trigger:** Tell Claude: "run docket sync now"

---

## ⏳ OPEN ITEMS

1. **F1–F2 BACKLOG** — payroll portal access needed (Shiva); NY Q4 2022 DOR + MO Q3 2022 DOR not yet uploaded.
2. **A1a** — Vivek must delete 627KB copy (ID `1O2lO1RgFAnmrfYOklzqHGfxZKA-8D3z-`) from Drive UI (right-click → Remove). Keep 217KB (ID `19jBTc15jSMQz5Q7qrYb0ML6MUw3_vaFO`) — MD5-verified match to source. Once deleted, mark A1a ✅ in DOCKET_FILE_IDS.md.
3. **2024/2025 state quarterly anomaly** — sync re-triggered Jun 13 ~12:06 UTC; read new SYNC_LOG in 99_Admin/ to confirm whether 2024/2025 data appeared.
4. **F12** — Vivek/Shiva: is `A1b_DF_Federal_Return_2023_Amendment.pdf` a standalone exhibit (A1b-amendment) or just supporting A1b?

### ⏳ STILL OPEN — ASK SHIVA

F1–F7 sent to Shiva via tracker + HTML June 13. F8–F12 are new:

| Code | Fix | Source Path | By When |
|------|-----|-------------|---------|
| F1 | Re-upload NY Q4 2022 DOR (0-byte file) | `2022/QuarterlyTaxes/Q4 2022/New York/` | BACKLOG — payroll portal |
| F2 | Upload MO Q3 2022 DOR (DOL only, DOR missing) | `2022/QuarterlyTaxes/Q3 2022/MISSOURI/` | BACKLOG — payroll portal |
| F5 | Upload TX Franchise Tax Annual Reports 2022–2025 | `Quarterly state tax returns/` | Jun 16 |
| F6 | Upload 2022 Q1 + Q2 state quarterly returns (all states) | `2022/QuarterlyTaxes/Q1 2022/{State}/` and `Q2 2022/` | Jun 18 |
| F7 | Rename typo folder `Missour` → `Missouri` | `2023/QuarterlyTaxes/Q1_ 2023/` | Jun 18 |
| F8 | Upload 2024 and 2025 state quarterly returns — no quarter-state subfolders exist in source | `2024/QuarterlyTaxes/Q1 2024/{State}/` … `Q4 2025/{State}/` | Jun 20 |
| F9 | Upload state annual returns for 2023, 2024, 2025 — only 2022 found | `2023/QuarterlyTaxes/` (filename `Annual State Returns — 2023.pdf`) | Jun 20 |
| F10 | Upload DATAFLAKE 2024 federal tax return — `2024/Yearly Tax/` is empty | `2024/YearlyTax/` | Jun 16 |
| F11 | Upload DATAFLAKE 2025 federal tax return — `2025/Yearly Tax/` is empty | `2025/YearlyTax/` | Jun 16 |
| F12 | Clarify `A1_DATAFLAKE_Form1065_2023_StateAmendment.pdf` — standalone exhibit or merged into A1b? | `A1_Federal_Tax_Returns/` | Jun 16 |

**Other open items (Vivek):**
- Missing: 2022 Financials (Google-Docs placeholders only in source); 2024 Balance Sheet PDF
- 2022 Q1–Q2 federal 941s still missing from source

---

## ⚠️ HUMAN ACTION ITEMS

| Code | Document | Action Required | Hard By |
|------|----------|----------------|---------|
| C5 | Certified Judgment Search — Bhargavi Jaggarapu | Order LexisNexis CourtLink (~$75–150, 3-day rush) | Jun 27 |
| C6 | Certified Judgment Search — DATAFLAKE LLC | Same — Texas + all US federal courts | Jun 27 |
| A3p | CPA Attestation Letter | Request from Shiva / CPA | Jun 20 |

C3b (Nunc Pro Tunc) and B8 (Sweat Equity) Google Docs already created — counsel must review and sign by Jun 25.

---

## REFERENCE — Response Documents in Drive

To edit: open in Google Drive → right-click → **Open with Google Docs**.

| Exhibit | Document | Drive ID | Docket Folder |
|---------|----------|----------|---------------|
| 00a | Cover Letter (template for counsel) | 1T_jSjPzEbBjihhQLxyLhffp1t8NY3mX3 | 00_Cover_Brief |
| 00b | Master Exhibit Index (original) | 1LRnxZADhP8aG8Jd8ETnyQkSYa6Tq4mDH | 00_Cover_Brief |
| 00b | Master Exhibit Index (updated Jun 13, with descriptions) | 1ElJMqr6fc0BEe5t-Wg5GVykqW3V3xJ6K | 00_Cover_Brief |
| 00_nav | Issue Quick Reference Guide | 1mOSpfRtRB5BoAu-mWgKpZI51_RLCQx0d | 00_Cover_Brief |
| TAB A–D | Section Cover Sheets (print + insert) | 1HPiBA-0zjERmDPDIO6fT5ohulu1if60a | 00_Cover_Brief |
| B6a | Employment Gap Declaration | 15EJICIfb1n6xhSC-rpq8aea4nip2MGKu | B6_Employment_Gap_Declaration |
| B8 | Sweat Equity Member Resolution | 1zzQglTDBwdaf9adrkd1rlJrD24czIz2E | B8_Sweat_Equity |
| C1 | DATAFLAKE Lender SOF Declaration | 1dogLsXyVQRyDHZcsoOk6jcDcwWvkhE2b | C1_Lender_SOF_Declaration |
| C3b | Nunc Pro Tunc Ratification | 1SEbiAImsW19EJO6iKH8YUIofuuvVcCNl | C3_Board_Resolutions |
| C4 | Good Faith Non-Circumvention Statement | 1eLOXEcE86uRKt_ZBO3zK-HbfkBazQdEt | C4_GoodFaith_Statement |
| C7 | No Pending Actions Declaration | 1DTuoACzl4R1qpV8b1yHY4JR_lhTdQ7PT | C7_No_Pending_Actions_Declaration |
| D1 | Path of Funds Tie-Out Narrative | 1-QVpEKPYZOjcJ2pb8Ev33r4a9-Slr95W | D1_PathOfFunds_TieOut |

---

## PART 3 — SOURCE → DOCKET MAPPING RULES
*(Sync bot reads this section every 6 hours — preserve column order)*
*(Subfolder paths in "Docket Folder" column are relative to docket root)*

### IGNORE RULES — NEVER COPY TO DOCKET
- Any file matching `*SHIVA_INSTRUCTIONS*` or `*Shiva_Instructions*` (HTML admin files)
- Any `.md` file from the source folder
- Do not create A9_HWB0639 or B9_Identity folders — those decisions were overridden; use A7 and B6 respectively
- `941*.pdf` files inside `{quarter}/{State}/` state subfolders — byte-identical duplicates of the federal 941s already in `Federal_941/{YEAR}/Q{n}/`
- 0-byte files (corrupt uploads) — flag in sync log for Shiva to re-upload instead of copying
- 1KB Google-Docs placeholders named DOR / DOL / 941

### KEY: HOW SHIVA ORGANIZES SOURCE FILES

Shiva's source folder structure (sync bot must handle this exactly):
- Annual federal returns: `{YEAR}/YearlyTax/`
- TX Franchise tax: **NOT IN SOURCE** — `Quarterly state tax returns/{YEAR}/` contains only `CP_INPDATAFLA_{YYMMDD}.pdf` files, which are byte-identical duplicates of the federal 941s (confirmed June 12 by size match). Per decision: map CP files to Federal_941 (see rule below). Real TX Franchise returns awaited from Shiva — TX_Franchise mapping rows stay as-is for when they arrive
- Federal 941: **CONFIRMED June 12, 2026** — `{YEAR}/QuarterlyTaxes/` root (NOT in `{Q# YEAR}/` subfolders), filenames `Payroll_941_{YEAR}_Q{n}.pdf`; derive year+quarter from the filename
- State quarterly returns: `{YEAR}/QuarterlyTaxes/{quarter folder}/{State}/` — **quarter folder names VARY** (confirmed June 12: `Q3 2022`, `Q4 2022`, `Q1_ 2023`, `Q2_2023`, `Q3_2023`, `Q3-2023-2`, `Q1-2026`). Treat ANY subfolder of `{YEAR}/QuarterlyTaxes/` whose name contains Q1–Q4 as a quarter folder, regardless of separator (space/underscore/hyphen) or suffix. 2023 Q3 exists TWICE (`Q3_2023` and `Q3-2023-2`) — recurse into both, skip files already present in docket. State folder names vary in case/spacing/typos (`MISSOURI`, `New York `, `Missour` = Missouri). Each state folder ALSO contains a byte-identical duplicate of the federal 941 (`941*.pdf`) — never copy those to State_Quarterly (see ignore rules)
- State annual returns: `{YEAR}/QuarterlyTaxes/` root, filename like `Annual State Returns — {YEAR}.pdf`
- Financials: `{YEAR}/Financials/`
- Bank statements: `{YEAR}/BankStatements/`
- Vendor contracts: `{YEAR}/{ClientName}/`

---

### TAB A — DATAFLAKE BUSINESS (Issue #1)

#### A1 — Federal Tax Returns (flat — 4 files)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `2022/YearlyTax/` | `*.pdf` | `A1_Federal_Tax_Returns/` | `A1a_DF_Federal_Return_2022_{filename}` |
| `2023/YearlyTax/` | `*.pdf` | `A1_Federal_Tax_Returns/` | `A1b_DF_Federal_Return_2023_{filename}` |
| `2024/YearlyTax/` | `*.pdf` | `A1_Federal_Tax_Returns/` | `A1c_DF_Federal_Return_2024_{filename}` |
| `2025/YearlyTax/` | `*.pdf` | `A1_Federal_Tax_Returns/` | `A1d_DF_Federal_Return_2025_{filename}` |

#### A2 — State and Quarterly Returns (4 subfolders)

**TX_Franchise/** (one file per year):

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Quarterly state tax returns/` | `*2022*.pdf` | `A2_State_and_Quarterly_Returns/TX_Franchise/2022/` | `A2a_TX_Franchise_2022_{filename}` |
| `Quarterly state tax returns/` | `*2023*.pdf` | `A2_State_and_Quarterly_Returns/TX_Franchise/2023/` | `A2b_TX_Franchise_2023_{filename}` |
| `Quarterly state tax returns/` | `*2024*.pdf` | `A2_State_and_Quarterly_Returns/TX_Franchise/2024/` | `A2c_TX_Franchise_2024_{filename}` |
| `Quarterly state tax returns/` | `*2025*.pdf` | `A2_State_and_Quarterly_Returns/TX_Franchise/2025/` | `A2d_TX_Franchise_2025_{filename}` |

**Federal_941/** (source PDFs live at `{YEAR}/QuarterlyTaxes/` root named `Payroll_941_{YEAR}_Q{n}.pdf` — match on filename year+quarter):

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `2022/QuarterlyTaxes/Q1 2022/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2022/Q1/` | `A2e_Federal_941_2022_Q1_{filename}` |
| `2022/QuarterlyTaxes/Q2 2022/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2022/Q2/` | `A2f_Federal_941_2022_Q2_{filename}` |
| `2022/QuarterlyTaxes/Q3 2022/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2022/Q3/` | `A2g_Federal_941_2022_Q3_{filename}` |
| `2022/QuarterlyTaxes/Q4 2022/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2022/Q4/` | `A2h_Federal_941_2022_Q4_{filename}` |
| `2023/QuarterlyTaxes/Q1 2023/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2023/Q1/` | `A2i_Federal_941_2023_Q1_{filename}` |
| `2023/QuarterlyTaxes/Q2 2023/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2023/Q2/` | `A2j_Federal_941_2023_Q2_{filename}` |
| `2023/QuarterlyTaxes/Q3 2023/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2023/Q3/` | `A2k_Federal_941_2023_Q3_{filename}` |
| `2023/QuarterlyTaxes/Q4 2023/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2023/Q4/` | `A2l_Federal_941_2023_Q4_{filename}` |
| `2024/QuarterlyTaxes/Q1 2024/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2024/Q1/` | `A2m_Federal_941_2024_Q1_{filename}` |
| `2024/QuarterlyTaxes/Q2 2024/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2024/Q2/` | `A2n_Federal_941_2024_Q2_{filename}` |
| `2024/QuarterlyTaxes/Q3 2024/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2024/Q3/` | `A2o_Federal_941_2024_Q3_{filename}` |
| `2024/QuarterlyTaxes/Q4 2024/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2024/Q4/` | `A2p_Federal_941_2024_Q4_{filename}` |
| `2025/QuarterlyTaxes/Q1 2025/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2025/Q1/` | `A2q_Federal_941_2025_Q1_{filename}` |
| `2025/QuarterlyTaxes/Q2 2025/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2025/Q2/` | `A2r_Federal_941_2025_Q2_{filename}` |
| `2025/QuarterlyTaxes/Q3 2025/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2025/Q3/` | `A2s_Federal_941_2025_Q3_{filename}` |
| `2025/QuarterlyTaxes/Q4 2025/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2025/Q4/` | `A2t_Federal_941_2025_Q4_{filename}` |
| `2026/QuarterlyTaxes/Q1 2026/` | `*941*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/2026/Q1/` | `A2u_Federal_941_2026_Q1_{filename}` |

**Federal_941 supplementary copies** (`CP_INPDATAFLA_{YYMMDD}.pdf` files — decode year/quarter from the YYMMDD quarter-end date, e.g. `250630` → 2025 Q2):

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Quarterly state tax returns/{YEAR}/` | `CP_INPDATAFLA_*.pdf` | `A2_State_and_Quarterly_Returns/Federal_941/{20YY}/Q{n}/` | `A2_941_CP_{filename}` |

**State_Quarterly/** (sync bot MUST recurse into every state subfolder of every quarter folder — quarter folder names vary; match ANY subfolder containing Q1–Q4 regardless of separator. Skip 1KB placeholders, 0-byte files, and `941*.pdf` inside state folders. Rename convention: `A2{letter}_State_Q{n}_{YEAR}_{StateNoSpaces}_{DOR|DOL}.pdf`):

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `2022/QuarterlyTaxes/Q1 2022/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2022/Q1/` | `A2e_State_Q1_2022_{State}_{filename}` |
| `2022/QuarterlyTaxes/Q2 2022/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2022/Q2/` | `A2f_State_Q2_2022_{State}_{filename}` |
| `2022/QuarterlyTaxes/Q3 2022/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2022/Q3/` | `A2g_State_Q3_2022_{State}_{filename}` |
| `2022/QuarterlyTaxes/Q4 2022/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2022/Q4/` | `A2h_State_Q4_2022_{State}_{filename}` |
| `2023/QuarterlyTaxes/Q1 2023/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2023/Q1/` | `A2i_State_Q1_2023_{State}_{filename}` |
| `2023/QuarterlyTaxes/Q2 2023/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2023/Q2/` | `A2j_State_Q2_2023_{State}_{filename}` |
| `2023/QuarterlyTaxes/Q3 2023/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2023/Q3/` | `A2k_State_Q3_2023_{State}_{filename}` |
| `2023/QuarterlyTaxes/Q4 2023/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2023/Q4/` | `A2l_State_Q4_2023_{State}_{filename}` |
| `2024/QuarterlyTaxes/Q1 2024/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2024/Q1/` | `A2m_State_Q1_2024_{State}_{filename}` |
| `2024/QuarterlyTaxes/Q2 2024/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2024/Q2/` | `A2n_State_Q2_2024_{State}_{filename}` |
| `2024/QuarterlyTaxes/Q3 2024/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2024/Q3/` | `A2o_State_Q3_2024_{State}_{filename}` |
| `2024/QuarterlyTaxes/Q4 2024/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2024/Q4/` | `A2p_State_Q4_2024_{State}_{filename}` |
| `2025/QuarterlyTaxes/Q1 2025/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2025/Q1/` | `A2q_State_Q1_2025_{State}_{filename}` |
| `2025/QuarterlyTaxes/Q2 2025/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2025/Q2/` | `A2r_State_Q2_2025_{State}_{filename}` |
| `2025/QuarterlyTaxes/Q3 2025/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2025/Q3/` | `A2s_State_Q3_2025_{State}_{filename}` |
| `2025/QuarterlyTaxes/Q4 2025/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2025/Q4/` | `A2t_State_Q4_2025_{State}_{filename}` |
| `2026/QuarterlyTaxes/Q1 2026/{State}/` | `*.pdf` | `A2_State_and_Quarterly_Returns/State_Quarterly/2026/Q1/` | `A2u_State_Q1_2026_{State}_{filename}` |

**State_Annual/** (source path is `{YEAR}/QuarterlyTaxes/` root, filename like `Annual State Returns — {YEAR}.pdf`):

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `2022/QuarterlyTaxes/` | `*Annual*State*.pdf` | `A2_State_and_Quarterly_Returns/State_Annual/2022/` | `A2v_State_Annual_2022_{filename}` |
| `2023/QuarterlyTaxes/` | `*Annual*State*.pdf` | `A2_State_and_Quarterly_Returns/State_Annual/2023/` | `A2w_State_Annual_2023_{filename}` |
| `2024/QuarterlyTaxes/` | `*Annual*State*.pdf` | `A2_State_and_Quarterly_Returns/State_Annual/2024/` | `A2x_State_Annual_2024_{filename}` |
| `2025/QuarterlyTaxes/` | `*Annual*State*.pdf` | `A2_State_and_Quarterly_Returns/State_Annual/2025/` | `A2y_State_Annual_2025_{filename}` |

#### A3 — Audited Financials (year subfolders + CPA_Attestation subfolder)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `2022/Financials/` | `*balance*.pdf` or `*Balance*.pdf` | `A3_Audited_Financials/2022/` | `A3a_BalanceSheet_2022_{filename}` |
| `2023/Financials/` | `*balance*.pdf` or `*Balance*.pdf` | `A3_Audited_Financials/2023/` | `A3b_BalanceSheet_2023_{filename}` |
| `2024/Financials/` | `*balance*.pdf` or `*Balance*.pdf` | `A3_Audited_Financials/2024/` | `A3c_BalanceSheet_2024_{filename}` |
| `2025/Financials/` | `*balance*.pdf` or `*Balance*.pdf` | `A3_Audited_Financials/2025/` | `A3d_BalanceSheet_2025_{filename}` |
| `2026/Financials/` | `*balance*.pdf` or `*Balance*.pdf` | `A3_Audited_Financials/2026_YTD/` | `A3e_BalanceSheet_2026YTD_{filename}` |
| `2022/Financials/` | `*P&L*.pdf` or `*PnL*.pdf` or `*income*.pdf` | `A3_Audited_Financials/2022/` | `A3f_PnL_2022_{filename}` |
| `2023/Financials/` | `*P&L*.pdf` or `*PnL*.pdf` or `*income*.pdf` | `A3_Audited_Financials/2023/` | `A3g_PnL_2023_{filename}` |
| `2024/Financials/` | `*P&L*.pdf` or `*PnL*.pdf` or `*income*.pdf` | `A3_Audited_Financials/2024/` | `A3h_PnL_2024_{filename}` |
| `2025/Financials/` | `*P&L*.pdf` or `*PnL*.pdf` or `*income*.pdf` | `A3_Audited_Financials/2025/` | `A3i_PnL_2025_{filename}` |
| `2026/Financials/` | `*P&L*.pdf` or `*PnL*.pdf` or `*income*.pdf` | `A3_Audited_Financials/2026_YTD/` | `A3j_PnL_2026YTD_{filename}` |
| `2022/Financials/` | `*cash*.pdf` or `*Cash*.pdf` | `A3_Audited_Financials/2022/` | `A3k_CashFlow_2022_{filename}` |
| `2023/Financials/` | `*cash*.pdf` or `*Cash*.pdf` | `A3_Audited_Financials/2023/` | `A3l_CashFlow_2023_{filename}` |
| `2024/Financials/` | `*cash*.pdf` or `*Cash*.pdf` | `A3_Audited_Financials/2024/` | `A3m_CashFlow_2024_{filename}` |
| `2025/Financials/` | `*cash*.pdf` or `*Cash*.pdf` | `A3_Audited_Financials/2025/` | `A3n_CashFlow_2025_{filename}` |
| `2026/Financials/` | `*cash*.pdf` or `*Cash*.pdf` | `A3_Audited_Financials/2026_YTD/` | `A3o_CashFlow_2026YTD_{filename}` |
| `CPA_Attestation/` | `*.pdf` | `A3_Audited_Financials/CPA_Attestation/` | `A3p_CPA_Attestation_Letter_{filename}` |

#### A4 — Vendor Summary (flat — 1 file)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Dataflake LLC_Customer Summary.xlsx` | (root file) | `A4_Vendor_Summary/` | `A4_VendorSummary_EntityVerification.xlsx` |

#### A5 — Vendor Contracts / MSA (year subfolders)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `2022/{ClientName}/` | `*.pdf` | `A5_Vendor_Contracts_MSA/2022/` | `A5_2022_{ClientFolderName}_{filename}` |
| `2023/{ClientName}/` | `*.pdf` | `A5_Vendor_Contracts_MSA/2023/` | `A5_2023_{ClientFolderName}_{filename}` |
| `2024/{ClientName}/` | `*.pdf` | `A5_Vendor_Contracts_MSA/2024/` | `A5_2024_{ClientFolderName}_{filename}` |
| `2025/{ClientName}/` | `*.pdf` | `A5_Vendor_Contracts_MSA/2025/` | `A5_2025_{ClientFolderName}_{filename}` |

#### A6 — Invoice to Bank Tie-Out (flat — 1 file)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Dataflake+LLC_ Invoice and payment details.xlsx` | (root file) | `A6_Invoice_to_Bank_TieOut/` | `A6_Invoice_Payment_TieOut.xlsx` |

#### A7 — BOA-9229 Bank Statements (year subfolders — 12 monthly files per year)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `2022/BankStatements/` | `*Jan*.pdf` or `*01*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7a_BOA9229_2022_01_Jan.pdf` |
| `2022/BankStatements/` | `*Feb*.pdf` or `*02*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7b_BOA9229_2022_02_Feb.pdf` |
| `2022/BankStatements/` | `*Mar*.pdf` or `*03*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7c_BOA9229_2022_03_Mar.pdf` |
| `2022/BankStatements/` | `*Apr*.pdf` or `*04*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7d_BOA9229_2022_04_Apr.pdf` |
| `2022/BankStatements/` | `*May*.pdf` or `*05*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7e_BOA9229_2022_05_May.pdf` |
| `2022/BankStatements/` | `*Jun*.pdf` or `*06*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7f_BOA9229_2022_06_Jun.pdf` |
| `2022/BankStatements/` | `*Jul*.pdf` or `*07*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7g_BOA9229_2022_07_Jul.pdf` |
| `2022/BankStatements/` | `*Aug*.pdf` or `*08*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7h_BOA9229_2022_08_Aug.pdf` |
| `2022/BankStatements/` | `*Sep*.pdf` or `*09*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7i_BOA9229_2022_09_Sep.pdf` |
| `2022/BankStatements/` | `*Oct*.pdf` or `*10*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7j_BOA9229_2022_10_Oct.pdf` |
| `2022/BankStatements/` | `*Nov*.pdf` or `*11*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7k_BOA9229_2022_11_Nov.pdf` |
| `2022/BankStatements/` | `*Dec*.pdf` or `*12*.pdf` | `A7_BOA9229_Bank_Statements/2022/` | `A7l_BOA9229_2022_12_Dec.pdf` |
| `2023/BankStatements/` | (same month patterns) | `A7_BOA9229_Bank_Statements/2023/` | `A7m_` through `A7x_BOA9229_2023_{month}` |
| `2024/BankStatements/` | (same month patterns) | `A7_BOA9229_Bank_Statements/2024/` | `A7y_` through `A7aj_BOA9229_2024_{month}` |
| `2025/BankStatements/` | (same month patterns) | `A7_BOA9229_Bank_Statements/2025/` | `A7ak_` through `A7av_BOA9229_2025_{month}` |

#### A8 — Formation Docs (flat — 3 files)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Formation_Docs/` | `*Certificate*` or `*Formation*` | `A8_Formation_Docs/` | `A8a_CertificateOfFormation.pdf` |
| `Formation_Docs/` | `*Operating*` or `*Agreement*` | `A8_Formation_Docs/` | `A8b_OperatingAgreement.pdf` |
| `Formation_Docs/` | `*Profit*` or `*Resolution*` | `A8_Formation_Docs/` | `A8c_ProfitShare_Resolutions.pdf` |

#### A9 — SUPERSEDED (user decision: Hancock Whitney = DATAFLAKE business bank → A7, NOT A9)

Do NOT create or route into `A9_HWB0639_Bank_Statements`. Hancock Whitney acct 72500639 statements go to A7 instead:

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `2026/BankStatements/2026/Hancock Bank/` | `*.pdf` | `A7_BOA9229_Bank_Statements/2026/` | `A7_HWB0639_2026_{MM}_{filename}` |

---

### TAB B — PERSONAL & EMPLOYMENT (Issue #2)

#### B1 — Personal Tax Returns (type subfolders)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Personal_Bhargavi/US_Tax_Returns/` | `*2023*` | `B1_Personal_Tax_Returns/US_Returns/` | `B1a_Bhargavi_US_Return_2023.pdf` |
| `Personal_Bhargavi/US_Tax_Returns/` | `*2024*` | `B1_Personal_Tax_Returns/US_Returns/` | `B1b_Bhargavi_US_Return_2024.pdf` |
| `Personal_Bhargavi/US_Tax_Returns/` | `*2025*` | `B1_Personal_Tax_Returns/US_Returns/` | `B1c_Bhargavi_US_Return_2025.pdf` |
| `Personal_Bhargavi/India_Tax_Returns/` | `*2019*` or `*FY19*` | `B1_Personal_Tax_Returns/India_Returns/` | `B1d_Bhargavi_India_Return_FY2019-20.pdf` |
| `Personal_Bhargavi/India_Tax_Returns/` | `*2020*` or `*FY20*` | `B1_Personal_Tax_Returns/India_Returns/` | `B1e_Bhargavi_India_Return_FY2020-21.pdf` |
| `Personal_Bhargavi/India_Tax_Returns/` | `*2021*` or `*FY21*` | `B1_Personal_Tax_Returns/India_Returns/` | `B1f_Bhargavi_India_Return_FY2021-22.pdf` |
| `Personal_Bhargavi/India_Tax_Returns/` | `*2022*` or `*FY22*` | `B1_Personal_Tax_Returns/India_Returns/` | `B1g_Bhargavi_India_Return_FY2022-23.pdf` |
| `Personal_Bhargavi/` | `*CA_Letter*` or `*CPA_Letter*` | `B1_Personal_Tax_Returns/CA_Letter/` | `B1h_CA_Letter_TaxGapExplanation.pdf` |

#### B2 — Omkar Employment (flat — 5 files)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Employment_Omkar/` | `*EmployerLetter*` or `*Experience*` | `B2_Omkar_Employment/` | `B2a_Omkar_EmployerLetter.pdf` |
| `Employment_Omkar/` | `*Form16*2012*` or `*16*12*` | `B2_Omkar_Employment/` | `B2b_Omkar_Form16_FY2012-13.pdf` |
| `Employment_Omkar/` | `*Form16*2013*` or `*16*13*` | `B2_Omkar_Employment/` | `B2c_Omkar_Form16_FY2013-14.pdf` |
| `Employment_Omkar/` | `*Salary*` or `*Bank*` | `B2_Omkar_Employment/` | `B2d_Omkar_SalaryBankStatements.pdf` |
| `Employment_Omkar/` | `*PF*` or `*EPF*` or `*Provident*` | `B2_Omkar_Employment/` | `B2e_Omkar_PF_EPF_Records.pdf` |

#### B3 — TenXLabs Employment (flat — 4 files)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Employment_TenXLabs/` | `*EmployerLetter*` or `*Experience*` | `B3_TenXLabs_Employment/` | `B3a_TenXLabs_EmployerLetter.pdf` |
| `Employment_TenXLabs/` | `*Form16*` | `B3_TenXLabs_Employment/` | `B3b_TenXLabs_Form16_FY2014-15.pdf` |
| `Employment_TenXLabs/` | `*Salary*` or `*Bank*` | `B3_TenXLabs_Employment/` | `B3c_TenXLabs_SalaryBankStatements.pdf` |
| `Employment_TenXLabs/` | `*PF*` or `*EPF*` | `B3_TenXLabs_Employment/` | `B3d_TenXLabs_PF_EPF_Records.pdf` |

#### B4 — CGI Employment (flat — 6 files)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Employment_CGI/` | `*EmployerLetter*` or `*Experience*` | `B4_CGI_Employment/` | `B4a_CGI_EmployerLetter.pdf` |
| `Employment_CGI/` | `*Form16*2015*` or `*Form16*16*` | `B4_CGI_Employment/` | `B4b_CGI_Form16_FY2015-16.pdf` |
| `Employment_CGI/` | `*Form16*2016*` or `*Form16*17*` | `B4_CGI_Employment/` | `B4c_CGI_Form16_FY2016-17.pdf` |
| `Employment_CGI/` | `*Form16*2017*` or `*Form16*18*` | `B4_CGI_Employment/` | `B4d_CGI_Form16_FY2017-18.pdf` |
| `Employment_CGI/` | `*Salary*` or `*Bank*` | `B4_CGI_Employment/` | `B4e_CGI_SalaryBankStatements.pdf` |
| `Employment_CGI/` | `*PF*` or `*EPF*` | `B4_CGI_Employment/` | `B4f_CGI_PF_EPF_Records.pdf` |

#### B5 — DATAFLAKE Income (type subfolders)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Employment_DATAFLAKE/` | `*W2*2023*` or `*1099*2023*` | `B5_DATAFLAKE_Income/W2_1099/` | `B5a_DATAFLAKE_W2_1099_2023.pdf` |
| `Employment_DATAFLAKE/` | `*W2*2024*` or `*1099*2024*` | `B5_DATAFLAKE_Income/W2_1099/` | `B5b_DATAFLAKE_W2_1099_2024.pdf` |
| `Employment_DATAFLAKE/` | `*W2*2025*` or `*1099*2025*` | `B5_DATAFLAKE_Income/W2_1099/` | `B5c_DATAFLAKE_W2_1099_2025.pdf` |
| `Personal_BankStatements_Bhargavi/` | `*BOA5127*` or `*5127*` | `B5_DATAFLAKE_Income/BOA5127_Statements/` | `B5d_BOA5127_{filename}` |

#### B6 — Employment Gap Declaration (flat — 3 files)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Gap_Declaration/` | `*Declaration*` or `*Gap*` | `B6_Employment_Gap_Declaration/` | `B6a_GapDeclaration_Bhargavi.pdf` |
| `Gap_Declaration/` | `*Spouse*` or `*Rakesh*` | `B6_Employment_Gap_Declaration/` | `B6b_SpouseIncome_Evidence.pdf` |
| `Gap_Declaration/` | `*Savings*` or `*India*Bank*` | `B6_Employment_Gap_Declaration/` | `B6c_PriorSavings_Evidence.pdf` |

#### B7 — Capital Account Docs (flat — 2 files)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Capital_Account/` | `*Resolution*Profit*` or `*Profit*Resolution*` | `B7_Capital_Account_Docs/` | `B7a_MemberResolution_ProfitReinvestment.pdf` |
| `Capital_Account/` | `*Ledger*` or `*Capital*Account*` | `B7_Capital_Account_Docs/` | `B7b_PerMember_CapitalAccount_Ledger.pdf` |

#### B8 — Sweat Equity (flat — 1 file)

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Capital_Account/` | `*Sweat*` or `*Founder*` or `*Services*` | `B8_Sweat_Equity/` | `B8_SweatEquity_Resolution.pdf` |

#### B9 — SUPERSEDED (user decision: identity/immigration docs → B6, NOT B9)

Do NOT create or route into `B9_Identity_Immigration_Docs`. Any new files matching identity/immigration patterns go to `B6_Employment_Gap_Declaration/`.

---

### TAB C — LENDER SOF & JUDGMENTS (Issue #3)

All C-series folders are flat (1–3 files each — no subfolders needed).

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `Lender_SOF_Judgments/` | `*LenderSOF*` or `*Lender_SOF*` | `C1_Lender_SOF_Declaration/` | `C1_DATAFLAKE_LenderSOF_Declaration.pdf` |
| `Lender_SOF_Judgments/` | `*275K*` or `*275000*Note*` | `C2_Promissory_Notes/` | `C2a_PromissoryNote_275K_May2024.pdf` |
| `Lender_SOF_Judgments/` | `*750K*` or `*750000*Note*` | `C2_Promissory_Notes/` | `C2b_PromissoryNote_750K_Jul2025.pdf` |
| `Lender_SOF_Judgments/` | `*Resolution*275*` or `*Board*275*` | `C3_Board_Resolutions/` | `C3a_BoardResolution_275K.pdf` |
| `Lender_SOF_Judgments/` | `*NuncProTunc*` or `*Ratification*` | `C3_Board_Resolutions/` | `C3b_NuncProTunc_275K_Ratification.pdf` |
| `Lender_SOF_Judgments/` | `*Resolution*750*` or `*Board*750*` | `C3_Board_Resolutions/` | `C3c_BoardResolution_750K.pdf` |
| `Lender_SOF_Judgments/` | `*GoodFaith*` or `*NonCircumvention*` | `C4_GoodFaith_Statement/` | `C4_GoodFaith_NonCircumvention.pdf` |
| `Lender_SOF_Judgments/` | `*Judgment*Bhargavi*` or `*Search*Bhargavi*` | `C5_Judgment_Search_Bhargavi/` | `C5_CertifiedJudgmentSearch_Bhargavi.pdf` |
| `Lender_SOF_Judgments/` | `*Judgment*DATAFLAKE*` or `*Search*DATAFLAKE*` | `C6_Judgment_Search_DATAFLAKE/` | `C6_CertifiedJudgmentSearch_DATAFLAKE.pdf` |
| `Lender_SOF_Judgments/` | `*NoPending*` or `*Declaration*Pending*` | `C7_No_Pending_Actions_Declaration/` | `C7_Declaration_NoPendingActions.pdf` |

---

### TAB D — PATH OF FUNDS (Issue B)

All D-series folders are flat.

| Source Folder | Source File Pattern | → Docket Folder | Renamed As |
|---|---|---|---|
| `PathOfFunds/` | `*Tranche1*` or `*250K*` | `D1_PathOfFunds_TieOut/` | `D1a_PathOfFunds_Tranche1.pdf` |
| `PathOfFunds/` | `*Tranche2*` or `*300K*Nov*` | `D1_PathOfFunds_TieOut/` | `D1b_PathOfFunds_Tranche2.pdf` |
| `PathOfFunds/` | `*Tranche3*` or `*275K*Dec*` | `D1_PathOfFunds_TieOut/` | `D1c_PathOfFunds_Tranche3.pdf` |
| `PathOfFunds/` | `*BOA5127*complete*` or `*5127*complete*` | `D1_PathOfFunds_TieOut/` | `D1d_BOA5127_Complete_May2024_Jan2026.pdf` |
| `NCE_Docs/` | `*Receipt*` or `*825*` | `D2_NCE_Receipt/` | `D2_NCE_Receipt_825K.pdf` |
| `NCE_Docs/` | `*Subscription*` or `*Agreement*` | `D3_Subscription_Agreement/` | `D3_SubscriptionAgreement_{filename}.pdf` |

---

## UNMAPPED FILE HANDLING

Files without a matching rule → copied to `99_Admin/UNMAPPED/` (ID: `1PR2T8MiRL7vzy7blGE36bIMkIKIPGoOk`) and flagged in sync log. Tell Claude which exhibit it belongs to for re-mapping.

**Common unmapped scenarios:**
- File in wrong source subfolder → ask Shiva to move to correct path, re-sync
- New document type → add mapping row to Part 3 above, re-sync
- 941 path differs from assumed → update Federal_941 section with confirmed source path
