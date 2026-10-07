# Source manifest

Planning status: 7 October 2026.

This is the public inventory of supplied source files. It records what exists, whether it is current, and whether it may be published. It does not reproduce confidential figures, clinical drafts, or unverified marketing claims.

The earlier note of 21 attachments is corrected here. **20 originals** are indexed with SHA-256 hashes in the local manifest. **One expected floor-plan screenshot was not found** on the Desktop archive, in Downloads, or in Pictures, and it is not in the hash list.

Current planning authority is the internal review set kept locally under `docs/current/`. Those files, the finance workbooks, and the chat transcript are **not** part of the public repository. Original PDFs, HTML, and Markdown are preserved as historical representations. They are not independent evidence and do not override the current review.

## Count

| Item | Result |
|---|---|
| Hashed originals | 20 |
| Floor-plan screenshot | Missing; not hashed |
| Chat transcript | Held locally only; not one of the 20 |
| Files published from this list | None of the originals |

## Hashed originals

| # | File | Type | Publication tier | Handling |
|---|---|---|---|---|
| 01 | `01-Part1_Landlord_Negotiation_Strategy.md` | Negotiation plan | Confidential | Superseded for scope and budget. Local only. |
| 02 | `02-Part1_Landlord_Negotiation_Strategy.pdf` | Negotiation plan | Confidential | Same content as 01. Local only. |
| 03 | `03-Kakkanad_Sports_Rehab_Longevity_SUPER_MASTER_BLUEPRINT.pdf` | Historical blueprint | Confidential historical | Older layout and cost picture. Not current authority. |
| 04 | `04-Kakkanad_Sports_Rehab_Longevity_SUPER_MASTER_BLUEPRINT.html` | Historical blueprint | Confidential historical | Same family as 03. |
| 05 | `05-Kakkanad_Sports_Rehab_Longevity_SUPER_MASTER_BLUEPRINT.md` | Historical blueprint | Confidential historical | Contains unverified keyword material. Do not republish as fact. |
| 06 | `06-Kakkanad_Financial_and_Demand_Model.xlsx` | Finance workbook | Confidential | Preserved unchanged. Not the current opening model. |
| 07 | `07-Kakkanad_Sports_Rehab_Longevity_Master_Blueprint_REVISED.html` | Revised feasibility draft | Confidential historical | Competitor and feasibility notes. Not current authority. |
| 08 | `08-Kakkanad_Sports_Rehab_Longevity_Master_Blueprint_REVISED.md` | Revised feasibility draft | Confidential historical | Same family as 07. |
| 09 | `09-Master-Strategic-Blueprint-Kakkanad-Sports-Rehab-Longevity.pdf` | Strategic blueprint | Confidential historical | Superseded representation. |
| 10 | `10-Kakkanad_Sports_Rehab_Longevity_Master_Blueprint.html` | Early blueprint | Confidential historical | Superseded representation. |
| 11 | `11-Kakkanad_Sports_Rehab_Longevity_Master_Blueprint.md` | Early blueprint | Confidential historical | Superseded representation. |
| 12 | `12-Part3_Global_Kerala_Website_SEO_Manual.pdf` | Website and search draft | Do not publish claims | Local search volumes and competitor comments are unverified. |
| 13 | `13-Part3_Global_Kerala_Website_SEO_Manual.md` | Website and search draft | Do not publish claims | Same family as 12. |
| 14 | `14-Part2_Master_Operational_Plan.md` | Operations draft | Confidential | Includes unapproved clinical drafts. Not a live protocol. |
| 15 | `15-Part2_Master_Operational_Plan.pdf` | Operations draft | Confidential | Same family as 14. |
| 16 | `16-Calibre_Clinic_Website.html` | Website draft | Superseded | Placeholder contact details. Replaced by `website/index.html`. |
| 17 | `17-Part3_Website_Keyword_Plan.pdf` | Keyword draft | Do not publish claims | Unverified historical search material. |
| 18 | `18-Part2_Super_Master_Blueprint.pdf` | Historical blueprint | Confidential historical | Superseded representation. |
| 19 | `19-Part1_Owner_Discussion_Plan.pdf` | Owner discussion | Confidential | Commercial discussion paper. Local only. |
| 20 | `20-CALIBRE_KAKKANAD_FULL_PROJECT.zip` | Nested project package | Confidential | Includes a planning app and agent-tool exports. Do not publish. |

Hashes for items 01–20 are stored in the local `archive/source-manifest.json`. They are integrity checks, not a reason to publish the files.

## Known conflicts the current review already settled

These points are recorded so older files are not read as the live plan.

| Topic | Older sources | Current handling |
|---|---|---|
| Treatment rooms | Four cubicles in early masters; ten bays in the nested app | Six cubicles: three male and three female |
| Cold plunge | Two-tub or two-pool suites in some blueprints | One compact commercial plunge |
| Sauna | Larger hybrid or multi-person suites in some blueprints | One compact sauna; type still unselected |
| Red light | Full-body pod in some zone drawings | One starter station |
| Hyperbaric chamber | Shown as future or income-bearing in some drafts | Deferred. Not funded as an opening service |
| Public website | Draft pages with placeholder phone and WhatsApp | Pre-opening page only. No booking and no contact number |
| Search volumes | Some manuals label local figures as verified | Treat as unverified. The workbook itself says local metrics were unavailable |

## Missing item

| Expected item | Status |
|---|---|
| Floor-plan screenshot | Not found in the hashed set or in the searched local folders. Do not invent a drawing. Reconcile the shell only from a measured survey. |

## Local-only material (not published)

| Location | Role |
|---|---|
| `docs/current/` | Revised plan, source review, launch gates, and verification note. Current internal authority. |
| `finance/` | Opening budget tables and model checks. |
| `archive/` | Originals, hashes, and the chat transcript. |
| `archive/00_FULL_CHAT_TRANSCRIPT_AND_DISCUSSIONS.md` | Full discussion export. Not one of the 20 hashed originals. |

Patient data, credentials, and agent-tool exports stay out of Git history.
