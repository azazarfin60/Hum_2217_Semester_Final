# HUM 2217: Subtopic-wise List (Weightage + Flow)

> **Source:** [Question_Analysis_Report.md](PreviousYearQuestions/Question_Analysis_Report.md). It covers **4 semester finals** (2020, 2021, 2023, 2024) and **4 Class Tests** ([CT_questions.md](PreviousYearQuestions/CT_questions.md), 2025 / 23 Series), plus Shoaib Sir's voice-note suggestion and Raidah's class notes. Only active syllabus parts are counted: all of 2023 and 2024, Section A of 2020 and 2021 (**69 final sub-questions, 256 printed marks**), and all 4 Class Tests (**15 main questions / 20 parts, 80 printed marks**). Every topic total below is the exact sum of its subtopics. The [Appendix](#appendix-every-past-sub-question-and-ct-mapped-to-an-id) shows where every mark came from.
>
> **Use:**
> - **Question sorting:** tag each question with one primary subtopic ID (for example `L04.4`). Each past final sub-question and CT question is counted once under its primary ID. Nine combined final sub-questions are split across two IDs as listed in [Sorting Rules](#sorting-rules).
> - **Answers and boss notes:** write one file per topic in the order below. Inside a topic, subtopics are arranged in teaching order: definitions first, then rules, then applied or numerical work.

## Legend

| Symbol | Meaning |
| :-- | :-- |
| **Final Marks** | Printed marks across the 4 finals (256 total) |
| **Share** | Final Marks ÷ 256 |
| **'23–'24** | Printed marks in the two current OBE finals only (160 total) |
| **CT Marks** | Printed marks across the 4 Class Tests in `CT_questions.md` (80 total) |
| **Papers** | How many finals included the topic (out of 2 for CO1; out of 4 for CO2 and CO3) |
| 🔴 / 🟠 / 🟡 / 🟢 / ⚫ | Near-certain / Very likely / Likely / Wildcard / Skip for final (report §9) |
| ♻️ | Recycled question (same or nearly the same wording/template across papers) |
| ⭐ | Never asked in a final, but tested in a CT, suggested by the instructor, or taught in class |
| 📌 | Named in Shoaib Sir's 2026 final exam suggestion |
| **Cov.** | Where the content lives: **N** SI Sir notes/slides · **R** Raidah class notes · **M** MRI Sir lectures · **G** Griffin · **B** BLC statute · **C** `CT_questions.md` |

### Source Key

| Code | File |
| :-- | :-- |
| SI-1 to SI-4 | [Chapter-1.md](Legal_Issues/Notes/Chapter-1.md) · [Chapter-2.md](Legal_Issues/Notes/Chapter-2.md) · [Chapter-3.md](Legal_Issues/Notes/Chapter-3.md) · [Chapter-4.md](Legal_Issues/Notes/Chapter-4.md) |
| SL-1 to SL-4 | [Chapter-1slide.md](Legal_Issues/Slides/Chapter-1slide.md) · [Chapter-2slide.md](Legal_Issues/Slides/Chapter-2slide.md) · [Chapter-3 slide.md](Legal_Issues/Slides/Chapter-3%20slide.md) · [Chapter-4 slide.md](Legal_Issues/Slides/Chapter-4%20slide.md) |
| BLC-xx | [BangladeshLabourCode2006/](Books/BangladeshLabourCode2006/README.md) chapter files (for example BLC-04 = `Chapter_04_Maternity_Benefit.md`) |
| LEC-1 to LEC-5 | [Lecture 1](Industrial_and_Operations_Management/Lecture%201.md) · [Lecture 2](Industrial_and_Operations_Management/Lecture%202.md) · [Lecture 3](Industrial_and_Operations_Management/Lecture%203.md) · [Lecture 4](Industrial_and_Operations_Management/Lecture%204.md) · [Lecture 5](Industrial_and_Operations_Management/Lecture%205.md) |
| INV · PROD | [Inventory Control.md](Industrial_and_Operations_Management/Inventory%20Control.md) · [Productivity.md](Industrial_and_Operations_Management/Productivity.md) |
| RAI | [Classnotes_Hum2217_Raidah.md](Classnote_by_Raidah/Classnotes_Hum2217_Raidah.md) (class number given, for example RAI C-08) |
| CT | [CT_questions.md](PreviousYearQuestions/CT_questions.md) (`IM-CT1`, `Law-CT1`, `Law-CT2`, `OM-CT2`) |
| VN | [Shoaib_Sir_Suggestion_VoiceNote.md](Shoaib_Sir_Suggestion_VoiceNote.md) |
| GR-xx | [Griffin chapters](Books/Fundamentals_of_Management_Griffin/README.md) (for example GR-10 = Ch. 10 Parts 1 and 2) |

---

## Master Flow (topic order for notes)

```mermaid
flowchart TD
    subgraph CO1["CO1 Legal Issues (68 Final + 40 CT marks)"]
        L01["L01 Intro to Law"] --> L02["L02 Contract Basics"]
        L02 --> L03["L03 Consideration"]
        L03 --> L04["L04 Discharge + Case Study"]
        L04 --> L05["L05 BLC Definitions + Hours"]
        L05 --> L06["L06 Maternity"]
        L06 --> L07["L07 Fire & Machine Safety"]
        L07 --> L08["L08 Welfare"]
        L08 --> L09["L09 Termination of Employment"]
        L09 --> L10["L10 Trade Union"]
        L10 --> L11["L11 CBA + Disputes"]
        L11 --> L12["L12 Unfair Labour Practice"]
    end
    subgraph CO2["CO2 Industrial Management (138 Final + 20 CT marks)"]
        M01["M01 Foundations"] --> M02["M02 Levels + Skills"]
        M02 --> M03["M03 Fayol + Taylor"]
        M03 --> M04["M04 Planning, Decisions, Organizing, Control"]
        M04 --> M05["M05 Motivation"]
        M05 --> M06["M06 HRM + Appraisal"]
    end
    subgraph CO3["CO3 Operational Management (50 Final + 20 CT marks)"]
        O01["O01 Inventory Concepts"] --> O02["O02 EOQ + Q-System"]
        O02 --> O03["O03 Productivity"]
    end
```

| ID | Topic | Final Marks | Share | '23–'24 | CT Marks | Papers | Tier | Boss note file |
| :-- | :-- | :-: | :-: | :-: | :-: | :-: | :-: | :-- |
| L01 | Introduction to Law | 2 | 0.8% | 2 | 0 | 1/2 | 🟠 | `L01_Introduction_to_Law.md` |
| L02 | Contract Basics, Formation, Offer & Acceptance | 18 | 7.0% | 18 | 20 | 2/2 | 🔴 | `L02_Contract_Basics_and_Formation.md` |
| L03 | Consideration ⭐📌 | 0 | 0% | 0 | 0 | 0/2 | 🔴 | `L03_Consideration.md` |
| L04 | Discharge of Contract & Case Study 📌 | 4 | 1.6% | 4 | 0 | 1/2 | 🔴 | `L04_Discharge_of_Contract.md` |
| L05 | BLC Definitions, Working Hours & Multi-Issue Compliance 📌 | 10 | 3.9% | 10 | 10 | 1/2 | 🔴 | `L05_BLC_Definitions_and_Adolescents.md` |
| L06 | Maternity Benefit ⭐📌 | 0 | 0% | 0 | 0 | 0/2 | 🔴 | `L06_Maternity_Benefit.md` |
| L07 | Workplace Safety: Fire Precautions & Machinery 📌 | 8 | 3.1% | 8 | 10 | 1/2 | 🟠 | `L07_Fire_Safety.md` |
| L08 | Welfare Measures ⭐📌 | 0 | 0% | 0 | 0 | 0/2 | 🟠 | `L08_Welfare_Measures.md` |
| L09 | Termination of Employment (BLC Ch. II) ⭐ | 0 | 0% | 0 | 0 | 0/2 | 🟡 | `L09_Termination_of_Employment.md` |
| L10 | Trade Union: Basics, Registration, Status, Rights 📌 | 10 | 3.9% | 10 | 0 | 1/2 | 🔴 | `L10_Trade_Union.md` |
| L11 | Collective Bargaining, CBA & Industrial Disputes 📌 | 8 | 3.1% | 8 | 0 | 2/2 | 🔴 | `L11_CBA_and_Industrial_Disputes.md` |
| L12 | Unfair Labour Practices | 8 | 3.1% | 8 | 0 | 1/2 | 🟡 | `L12_Unfair_Labour_Practices.md` |
| M01 | Management Foundations (definition, resources, efficiency, functions, leadership) | 30 | 11.7% | 17 | 12 | 4/4 | 🔴 | `M01_Management_Foundations.md` |
| M02 | Levels, Areas & Managerial Skills | 12 | 4.7% | 8 | 6 | 3/4 | 🟠 | `M02_Levels_Areas_Skills.md` |
| M03 | Classical Theory: Fayol & Taylor | 15 | 5.9% | 5 | 0 | 3/4 | 🟠 | `M03_Fayol_and_Taylor.md` |
| M04 | Planning, Decision Making, Organizing & Controlling | 19 | 7.4% | 10 | 2 | 2/4 | 🟡 | `M04_Planning_Decisions_Organizing_Control.md` |
| M05 | Employee Motivation | 33 | 12.9% | 15 | 0 | 4/4 | 🔴 | `M05_Motivation.md` |
| M06 | HRM & Performance Appraisal | 29 | 11.3% | 7 | 0 | 4/4 | 🔴 (appraisal) / 🟢 (HRM) | `M06_HRM_and_Appraisal.md` |
| O01 | Inventory Concepts | 16 | 6.3% | 4 | 0 | 4/4 | 🔴 | `O01_Inventory_Concepts.md` |
| O02 | EOQ & Continuous Review (Q) System | 34 | 13.3% | 26 | 20 | 4/4 | 🔴 | `O02_EOQ_and_Q_System.md` |
| O03 | Productivity ⭐ | 0 | 0% | 0 | 0 | 0/4 | 🟠 | `O03_Productivity.md` |
| | **Total** | **256** | 100% | **160** | **80** | | | |

**Grouped by CO:**
- **CO1 Legal:** 68 Final Marks (42.5% of 2023–2024 finals) + 40 CT Marks = **108 combined marks**.
- **CO2 Management:** 138 Final Marks (38.8% of 2023–2024 finals) + 20 CT Marks = **158 combined marks**.
- **CO3 Operations:** 50 Final Marks (18.8% of 2023–2024 finals, rising) + 20 CT Marks = **70 combined marks**.

---

## Sorting Rules

1. **One primary ID per question.** If a part asks two things ("Define X and Y"), it goes under the ID of the first or main item. The second item gets a secondary tag in brackets.
2. **Applied parts get their own ID.** "Propose", "assess", "apply", "develop a scenario" and "give your opinion" parts are tagged with the topic's applied subtopic (for example `L02.8`, `L05.7`, `L11.5`).
3. **The inventory numerical is one block.** The whole problem (`2023 Q7c`, `2024 Q4c`, `2024 Q7b`, and `OM-CT2 Q1a–f`) goes under `O02.3`. Sub-steps (`O02.4` to `O02.8`) are tracked by occurrence below it.
4. **Explicit splits in Finals** (the only nine):

| Question | Split |
| :-- | :-- |
| 2020 Q2a (6) | 2 → `M05.1` meaning · 4 → `M05.2` Maslow |
| 2020 Q2b (6) | 2 → `M06.4` what is appraisal · 4 → `M06.5` rating problems |
| 2020 Q4a (5) | 2 → `O01.1` inventory control · 3 → `O01.2` holding costs |
| 2021 Q2a (6) | 3 → `M04.2` decision making · 3 → `M01.3` effective but not efficient example |
| 2021 Q4a (4) | 2 → `O01.1` · 2 → `O01.2` |
| 2021 Q4c (4) | 2 → `M06.4` performance management · 2 → `M06.5` rating problems |
| 2023 Q4a (2) | 1 → `L11.1` collective bargaining · 1 → `L11.2` CBA |
| 2023 Q7a (2) | 1 → `O01.1` · 1 → `O01.3` types |
| 2024 Q8a (2) | 1 → `L11.3` industrial dispute · 1 → `L11.1` collective bargaining |

---

# PART A: CO1 LEGAL ISSUES (SI Sir: Shoaib Islam)

> [!CAUTION]
> Every section number below comes from the verified list in `AGENTS.md` §3. Check each one against the [BLC README](Books/BangladeshLabourCode2006/README.md) or the chapter file before you write it into an answer. A wrong section number costs marks with this examiner.

## L01. Introduction to Law (2 Final + 0 CT marks · 1/2 · 🟠 · Ch. 1 "study all")

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L01.1 | Definitions of law: Holland, Salmond, Woodrow Wilson ⭐ | 0 | 0 | never asked | N | SI-1 · Definition of Law; SL-1 |
| L01.2 | **Definitions of Industrial Law and Labour Law** | 2 | 0 | 2023 Q2a | N | SI-1 · Industrial Law, Labor Law |
| L01.3 | Industrial law vs. labour law (difference table) ⭐ | 0 | 0 | never asked | N | SI-1 · Difference Between… |
| L01.4 | Why ECE students should learn law: 9 reasons (IPR, compliance, contracts, liability, ethics, startups, regulatory change, communication, risk management) ⭐ | 0 | 0 | never asked; feeds the ECE applied parts L02.7, L02.8 | N R | SI-1 · Why Students of ECE…; RAI SI C-01 |
| L01.5 | Law, government and society; statutory scope of labour law | 0 | 0 | background | R | RAI SI C-01 |

## L02. Contract Basics, Formation, Offer & Acceptance (18 Final + 20 CT marks · 2/2 · 🔴)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L02.1 | **Contract** (`Sec 2(h)`) and **agreement** (`Sec 2(e)`); maxim *"All contracts are agreements, but all agreements are not contracts"* 📌 | 2 | 0 | 2024 Q2a *(also inside Law-CT1 Q1)* | N R C | SI-2 · Contract; RAI SI C-02; CT §3 |
| L02.2 | **Void agreement** (`Sec 2(g)`; void agreements `Sec 26–30`) vs. **voidable contract** (`Sec 2(i)`) 📌 | 2 | 0 | 2023 Q3a | N R | SI-2 · Void and Voidable Agreement; RAI SI C-02 |
| L02.3 | **Essential elements of a valid contract** (`Sec 10`): offer + acceptance, intention, lawful consideration, capacity (`Sec 11–12`), free consent (`Sec 13–22`), lawful object (`Sec 23`), not expressly void (`Sec 26–30`), certainty (`Sec 29`), possibility (`Sec 56`) 📌 | 4 | 10 | 2023 Q3b; **Law-CT1 Q1 (10)** | N R C | SI-2 · Essential Elements; RAI SI C-02; CT §3 |
| L02.4 | Proposal/offer (`Sec 2(a)`), acceptance/promise (`Sec 2(b)`), promisor/promisee (`Sec 2(c)`) | 2 | 0 | 2024 Q6a | N | SI-2 · Proposal, Offer, Promise and Acceptance |
| L02.5 | **Rules & legal significance of offer and acceptance:** express/implied (`Sec 9`), specific/general (*Carlill v. Carbolic Smoke Ball*), invitation to offer vs. offer, communication (`Sec 4`), revocation (`Sec 5`) | 0 | 10 | **Law-CT1 Q2 (10)**; also inside 2024 Q6b | N C | SI-2 · Rules Regarding Offer; CT §3 |
| L02.6 | Rules regarding acceptance: absolute and unqualified (`Sec 7(1)`), usual manner (`Sec 7(2)`), acceptance by performing conditions (`Sec 8`) | 0 | 0 | inside Law-CT1 Q2 and 2024 Q6b | N C | SI-2 · Rules Regarding Acceptance; CT §3 |
| L02.7 | **Applied:** offer and acceptance when an ECE firm bids for a government tender (tender notice = invitation to offer, bid = offer, award letter = acceptance) | 4 | 0 | 2024 Q6b | N C | Build from L02.5 + L02.6; CT §3 Q2 |
| L02.8 | **Applied:** strategies to reduce contract risk in ECE R&D agreements (clear scope, IPR clause, milestones, force majeure, dispute clause, confidentiality) | 4 | 0 | 2023 Q3c | N | Build from L02.3 + L04 + L01.4 |

## L03. Consideration (0 Final + 0 CT marks · 0/2 · 🔴 · ⭐📌 "study all")

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L03.1 | Definition (`Sec 2(d)`); *quid pro quo* | 0 | 0 | never asked | N | SI-2 · Consideration |
| L03.2 | Types: past, present, future | 0 | 0 | never asked | N | SI-2 · Types of Consideration |
| L03.3 | **Rules:** at the desire of the promisor; from promisee or any other person; real, not illusory; need not be adequate (`Sec 25 Expl. 2`); lawful; stranger to consideration vs. stranger to contract | 0 | 0 | never asked | N R | SI-2 · Rules Regarding Consideration; RAI SI C-03 |
| L03.4 | **Exceptions to "No consideration, no contract":** natural love and affection (`Sec 25(1)`), voluntary past service (`Sec 25(2)`), time-barred debt (`Sec 25(3)`), agency (`Sec 185`), completed gift (`Sec 25 Expl. 1`), guarantee, charity with detriment | 0 | 0 | never asked | N | SI-2 · Exceptions to the Rule |

## L04. Discharge of Contract & Case Study (4 Final + 0 CT marks · 1/2 · 🔴 · 📌 10-mark case target)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L04.1 | **Methods of termination / discharge** (overview of all 7) | 4 | 0 | 2024 Q6c | N | SI-2 · Methods of Termination or Discharge |
| L04.2 | Discharge by performance (actual performance, tender) | 0 | 0 | inside L04.1 | N | SI-2 item 1 |
| L04.3 | Discharge by mutual agreement (`Sec 62`): novation, rescission, alteration; also remission, waiver, merger | 0 | 0 | inside L04.1 | N | SI-2 item 2 |
| L04.4 | **Supervening impossibility / frustration (`Sec 56`):** valid grounds (destruction of subject matter, change of law, failure of preconditions, death or incapacity in personal service, war) vs. non-grounds (commercial hardship, strikes, third-party default) 📌 | 0 | 0 | never asked alone | N | SI-2 item 3; VN §2 |
| L04.5 | Operation of law (death, insolvency, merger); lapse of time (Limitation Act); material alteration | 0 | 0 | inside L04.1 | N | SI-2 items 4 to 6 |
| L04.6 | Breach of contract: actual vs. anticipatory | 0 | 0 | inside L04.1 | N | SI-2 item 7 |
| L04.7 | **Case study method:** Facts → Law & Section → Analysis → Conclusion; 3 sub-questions = 10 marks ⭐📌 | 0 | 0 | new format for 2026 | N | VN §2 and §3 |

## L05. BLC 2006 Definitions, Working Hours & Multi-Issue Compliance (10 Final + 10 CT marks · 1/2 · 🔴)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L05.1 | What the Labour Code is: Act XLII of 2006, scope and objective ⭐📌 | 0 | 0 | never asked | N | SI-3 top; BLC-00 |
| L05.2 | **Factory** (`Sec 2(7)`: 5 or more workers + manufacturing process) and **worker** (`Sec 2(65)`: incl. apprentice, direct or via contractor; excludes managerial, administrative, supervisory) 📌 | 2 | 0 | 2023 Q1a | N B | SI-3 top; BLC-01 |
| L05.3 | **Manufacturing process** (`Sec 2(2)`; the voice note's "2(lxi)" is a misprint) ⭐📌 | 0 | 0 | never asked | N B | SI-3 top; BLC-01 |
| L05.4 | Age groups: child < 14 (`Sec 2(63)`), adolescent 14 to < 18 (`Sec 2(8)`), adult ≥ 18 (`Sec 2(36)`), minor < 18 | 0 | 0 | inside 2023 Q1b | N | SI-3 top |
| L05.5 | **Working hours for adolescents (`Sec 41`):** 5 h/day and 30 h/week in factory/mine (36 with overtime); 7 h/day and 42 h/week elsewhere (48 with overtime); no work 7 PM to 7 AM; max 2 shifts, spread-over ≤ 7.5 h; relay change once in 30 days; weekly holiday; one establishment per day 📌 | 4 | 0 | 2023 Q1b (asked wider: "children and adolescents") | N B | SI-3 · Sec 41; BLC-03 |
| L05.6 | Other young-person sections (`Sec 34–40, 42–44`) ⚫ | 0 | 0 | part of 2023 Q1b; `Sec 40 & 39(3)` tested in Law-CT2 Q2 (counted in L07.2) | N C | SI-3 · Sec 34 to 44; CT §4 Q2. **Excluded by Sir for final** |
| L05.7 | **Applied: BLC effectiveness & multi-issue factory compliance** (excessive hours `Sec 100–108`, unsafe machines `Sec 61–67`, fire protection `Sec 62`, welfare `Sec 89–94`) | 4 | 10 | 2023 Q1c (4); **Law-CT2 Q1 (10)** | N C | Build from L05.8 + L06 to L08; CT §4 Q1 |
| L05.8 | Adult working hours, rest intervals, weekly holiday, spread-over, overtime (`Sec 100–108`) ⚫ | 0 | 0 | tested inside Law-CT2 Q1 (in L05.7) | N B C | SI-3 · Sec 100–113; CT §4 Q1. **Excluded by Sir for final** |

## L06. Maternity Benefit (0 Final + 0 CT marks · 0/2 · 🔴 · ⭐📌)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L06.1 | `Sec 45`: no employment for 8 weeks after delivery; no arduous or long-standing work before delivery | 0 | 0 | never asked | N B | SI-3 · Sec 45; BLC-04 |
| L06.2 | `Sec 46`: right to 16 weeks paid (8 before + 8 after); needs ≥ 6 months service; no benefit if ≥ 2 surviving children (unpaid leave only) | 0 | 0 | never asked | N B | SI-3 · Sec 46 |
| L06.3 | `Sec 47`: notice (before delivery, or within 7 days after); 3 payment options; pay within 3 working days of proof | 0 | 0 | never asked | N B | SI-3 · Sec 47 |
| L06.4 | `Sec 48`: amount = wages of last 3 months ÷ days actually worked, paid in cash | 0 | 0 | never asked | N B | SI-3 · Sec 48 |
| L06.5 | `Sec 49`: payment if the woman or child dies | 0 | 0 | never asked | N B | SI-3 · Sec 49 |
| L06.6 | `Sec 50`: no termination without sufficient cause 6 months before to 8 weeks after delivery | 0 | 0 | never asked | N B | SI-3 · Sec 50 |

## L07. Workplace Safety: Fire Precautions & Machinery (8 Final + 10 CT marks · 1/2 · 🟠)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L07.1 | **Precaution in case of fire (`Sec 62`):** alternative stairway + firefighting appliances (62(1)); Inspector order (62(2)); unlocked doors opening outward (62(3)); exits marked in red Bangla (62(4)); audible alarm (62(5)); clear passages (62(6)); escape training if > 10 above ground floor or flammables (62(7)); mock drill in ≥ 50-worker factories (62(8): once a year in 2006 text, once every 6 months + 18% trained staff after 2013) 📌 | 4 | 0 | 2023 Q2b (asked as general "safety of workers"); also part of Law-CT2 Q1 | N B C | SI-3 · Sec 62; BLC-06; CT §4 Q1 |
| L07.2 | Other safety sections (`Sec 61, 63–78A`), incl. **work on machinery in motion (`Sec 64`) vs. adolescents on dangerous machines (`Sec 40` & `Sec 39(3)`)** ⚫ | 0 | 10 | **Law-CT2 Q2 (10)**; also part of 2023 Q2b and Law-CT2 Q1 | N B C | SI-3 · Sec 61, 63+; CT §4 Q2. **Excluded by Sir for final** |
| L07.3 | **Applied:** employer vs. employee duties under safety rules (your opinion) | 4 | 0 | 2023 Q2c | N | Build from L07.1 + L08.2 |

## L08. Welfare Measures (0 Final + 0 CT marks · 0/2 · 🟠 · ⭐📌 "full topic important")

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L08.1 | `Sec 89` first aid: 1 box per 150 workers, trained person with badge; sick room + dispensary at ≥ 300 workers | 0 | 0 | tested inside Law-CT2 Q1 (in L05.7) | N B C | SI-3 · Sec 89; BLC-08; CT §4 Q1 |
| L08.2 | `Sec 90` safety record book and board (> 25 workers) | 0 | 0 | tested inside Law-CT2 Q1 | N B C | SI-3 · Sec 90 |
| L08.3 | `Sec 91` washing facilities: adequate, clean, separate and screened for men and women | 0 | 0 | tested inside Law-CT2 Q1 | N B C | SI-3 · Sec 91 |
| L08.4 | `Sec 92` canteen: > 100 workers; committee with worker reps sets food and prices | 0 | 0 | tested inside Law-CT2 Q1 | N B C | SI-3 · Sec 92 |
| L08.5 | `Sec 93` shelters, rest rooms, lunch rooms with drinking water: > 50 workers; separate room if > 25 women | 0 | 0 | tested inside Law-CT2 Q1 | N B C | SI-3 · Sec 93 |
| L08.6 | `Sec 94` rooms for children (crèche): ≥ 40 women; children under 6; trained woman in charge; size, cots, playground | 0 | 0 | tested inside Law-CT2 Q1 | N B C | SI-3 · Sec 94 |
| L08.7 | `Sec 99` compulsory group insurance 🟢 | 0 | 0 | never asked | N | SI-3 · Sec 99 |

## L09. Termination of Employment, BLC Chapter II (0 Final + 0 CT marks · 0/2 · 🟡 · ⭐ backup case topic)

> [!NOTE]
> Only Raidah's note links "methods of termination" to BLC. The voice note puts the case study on the Contract Act (L04). Write L04 first. Keep L09 as a one-page backup.

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L09.1 | `Sec 20` retrenchment: redundancy, 1 month notice, 30 days wage per year of service | 0 | 0 | never asked | B R | BLC-02; RAI §15 |
| L09.2 | `Sec 22` discharge for physical or mental incapacity | 0 | 0 | never asked | B | BLC-02 |
| L09.3 | `Sec 23–24` dismissal for misconduct: charge sheet, 7-day explanation, inquiry | 0 | 0 | never asked | B | BLC-02 |
| L09.4 | `Sec 26` termination by employer by notice: 120 days (monthly-rated), 60 days (others) | 0 | 0 | never asked | B | BLC-02 |
| L09.5 | `Sec 27` resignation by worker | 0 | 0 | never asked | B | BLC-02 |

## L10. Trade Union: Basics, Registration, Status & Rights (10 Final + 0 CT marks · 1/2 · 🔴)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L10.1 | Definition and nature of a trade union; right to form one (`Sec 176`) 📌 | 0 | 0 | never asked | N B | SI-4 · Trade Union; BLC-13 |
| L10.2 | **Objectives of a trade union** | 2 | 0 | 2024 Q3a | N | SI-4 · Objectives |
| L10.3 | Functions of a trade union ⭐📌 | 0 | 0 | never asked | N | SI-4 · Functions |
| L10.4 | **Registration process:** application to Director of Labour (`Sec 177–178`); 30% membership (`Sec 179(2)`); decision within 60 days (`Sec 182`); certificate (`Sec 189`) | 4 | 0 | 2024 Q3b | N B | SI-4 · Methods and Process for Registration |
| L10.5 | Cancellation of registration (`Sec 190`: 7 grounds; needs Labour Court permission) 🟢 | 0 | 0 | never asked | N B | SI-4 · Reasons for Cancellation |
| L10.6 | **Legal status of a registered union** (`Sec 194`: body corporate, perpetual succession, common seal, hold property, contract, sue and be sued) ⭐📌 | 0 | 0 | never asked | N B | SI-4 · Legal Status |
| L10.7 | **Rights and privileges** (`Sec 197` criminal immunity, `Sec 198` civil immunity, `Sec 199` enforceability) + the 8 general rights in the notes ⭐📌 | 0 | 0 | never asked | N B | SI-4 · Rights and Privileges |
| L10.8 | **Applied:** role of trade unions in stopping discrimination or bias against technical staff | 4 | 0 | 2024 Q8c | N | Build from L10.3 + L12.1 |

## L11. Collective Bargaining, CBA & Industrial Disputes (8 Final + 0 CT marks · 2/2 · 🔴)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L11.1 | **Collective bargaining:** definition and features 📌 | 2 | 0 | 2023 Q4a (½), 2024 Q8a (½) | N | SI-4 · Collective Bargaining |
| L11.2 | **CBA:** who it is and how chosen (`Sec 202`: sole union, or secret ballot for 2 years); powers (`Sec 202(24)`) 📌 | 1 | 0 | 2023 Q4a (½) | N B | SI-4 · CBA; Power and Rights of CBA |
| L11.3 | **Industrial dispute:** definition; disputes raised by employers vs. by workers 📌 | 1 | 0 | 2024 Q8a (½) | N | SI-4 · Industrial Dispute |
| L11.4 | **Settlement ladder (`Sec 210`):** written notice → bipartite talks (within 15 days, 1 month) → conciliator (starts in 10 days, 30 days to settle) → arbitration (award in 30 days, valid 2 years) or strike/lock-out → Labour Court; strike notice (`Sec 211`) | 0 | 0 | inside 2024 Q3c | N B | SI-4 · Settlement (Sec-210); BLC-14 |
| L11.5 | **Applied:** build a hypothetical industrial dispute and show the resolution steps | 4 | 0 | 2024 Q3c | N | Build from L11.4 |

## L12. Unfair Labour Practices (8 Final + 0 CT marks · 1/2 · 🟡)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| L12.1 | By employers (`Sec 195`, 12 items: yellow-dog terms, discrimination, retaliation, coercing CBA, hiring during lawful strike, transferring officers, illegal lock-out) | 0 | 0 | inside 2023 Q4b, Q4c | N B | SI-4 · Sec-195 |
| L12.2 | By workers (`Sec 196`, 6 items: intimidation, coercion, gherao, illegal strike or go-slow) | 0 | 0 | inside 2023 Q4b | N B | SI-4 · Sec-196 |
| L12.3 | Penalties for unfair labour practices | 0 | 0 | never asked | N | SI-4 · Penalties |
| L12.4 | **Applied:** consequences of unfair labour practices for employers and employees | 4 | 0 | 2023 Q4b | N | Build from L12.1 + L12.2 |
| L12.5 | **Applied:** strategies unions can use against unfair labour practices | 4 | 0 | 2023 Q4c | N | Build from L10.7 + L11.4 + L12.3 |

---

# PART B: CO2 INDUSTRIAL MANAGEMENT (MRI Sir)

## M01. Management Foundations (30 Final + 12 CT marks · 4/4 · 🔴)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| M01.1 | **Define management / industrial management** (Taylor 1911 "best and cheapest way"; Griffin) ♻️ | 12 | 0 | 2020 Q1a; 2021 Q1a (+M01.3) = 2024 Q5a (+M01.3); 2023 Q5a; 2024 Q1a | M R G | LEC-1 · Define Management; RAI C-01; GR-01 |
| M01.2 | **Stakeholders, 4 organizational resources** (human, financial, physical, information; Telecom firm & University VC examples), and **8 features of nature of management** (universal, social process, goal-oriented, etc.) ⭐ | 0 | 8 | **IM-CT1 Q3 (2), Q7 (2), Q8 (2), Q9 (2)** | M R C | LEC-2; RAI C-01 to C-04; CT §2 |
| M01.3 | **Efficiency vs. effectiveness:** 2 × 2 matrix; examples that are efficient but not effective, effective but not efficient, and both efficient and effective | 7 | 2 | 2021 Q2a (½); 2023 Q5b; **IM-CT1 Q2 (2)** | M R G C | LEC-1; RAI C-03; GR-01; CT §2 |
| M01.4 | **Functions / process of management:** planning and decision making, organizing, leading, controlling | 11 | 0 | 2020 Q1b; 2024 Q1b; 2024 Q5b | M R G | LEC-1 · Key Aspects/Functions; RAI C-02, C-03; GR-01 |
| M01.5 | **Leadership vs. management:** *"All leaders are managers, but all managers are not leaders"* (formal authority vs. personal influence; Kotter's distinction) ⭐ | 0 | 2 | **IM-CT1 Q4 (2)** | R G C | RAI C-03; GR-11; CT §2 |

## M02. Levels, Areas & Managerial Skills (12 Final + 6 CT marks · 3/4 · 🟠)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| M02.1 | **Levels of management:** top, middle, first-line (roles and typical position titles) ⭐ | 0 | 2 | **IM-CT1 Q6 (2)** | M R G C | LEC-3 · Levels; RAI C-05; CT §2 |
| M02.2 | Functional areas of management | 0 | 0 | never asked | M G | LEC-3 · Areas; GR-01 |
| M02.3 | **Managerial skills, critically evaluated** (technical, interpersonal, conceptual, diagnostic, communication, decision-making, time-management) + skill mix across levels (first-line skills, claiming conceptual skills) ♻️ | 8 | 4 | 2021 Q1c ≈ 2024 Q1c; **IM-CT1 Q1 (2), Q5 (2)** | M R G C | LEC-3 · Managerial skills; RAI C-06; GR-01; CT §2 |
| M02.4 | **Skills a top-level manager needs + strategies to improve them** | 4 | 0 | 2023 Q5c | M R G | LEC-3; RAI C-06 |

## M03. Classical Theory: Fayol & Taylor (15 Final + 0 CT marks · 3/4 · 🟠)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| M03.1 | **Fayol's 14 principles of administrative management** (critically evaluate; or selected: unity of command, unity of direction, centralization, authority and responsibility) | 10 | 0 | 2021 Q1b; 2024 Q5c | M R G | LEC-4; RAI C-07; GR-01 |
| M03.2 | Scalar chain and gangplank (diagram) | 0 | 0 | inside M03.1 | M R | LEC-4 · Scalar Chain; RAI C-07 |
| M03.3 | **Taylor's principles of scientific management** | 5 | 0 | 2020 Q1c | M G | LEC-5; GR-01 |

## M04. Planning, Decision Making, Organizing & Controlling (19 Final + 2 CT marks · 2/4 · 🟡)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| M04.1 | Meaning of planning and decision making | 2 | 0 | 2023 Q6a | G | GR-03, GR-04 |
| M04.2 | **Rational decision-making process with example** | 6 | 0 | 2021 Q2a (½); 2023 Q6b | G | GR-04 |
| M04.3 | **Organizing elements, tasks & purposes:** departmentalization, delegation of authority, span of control | 5 | 2 | 2023 Q6c; **IM-CT1 Q10 (2)** | G C | GR-06; CT §2 |
| M04.4 | **Controlling:** meaning and steps of the control process | 6 | 0 | 2021 Q2b | G | GR-14 |

## M05. Employee Motivation (33 Final + 0 CT marks · 4/4 · 🔴)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| M05.1 | **What motivation is and why it matters** ♻️ | 11 | 0 | 2020 Q2a (½); 2021 Q3a = 2023 Q8a; 2024 Q2b | R G | RAI C-08; GR-10 |
| M05.2 | **Maslow's need hierarchy:** levels, criticism, application | 10 | 0 | 2020 Q2a (½); 2021 Q3b | R G | RAI C-08; GR-10 |
| M05.3 | **Herzberg's two-factor theory:** hygiene vs. motivators, criticism, application | 5 | 0 | 2024 Q2c | G | GR-10 |
| M05.4 | **Vroom's expectancy theory:** Motivation = Expectancy × Instrumentality × Valence, application | 4 | 0 | 2023 Q8b | R G | RAI C-08; GR-10 |
| M05.5 | Financial vs. non-financial motivators | 3 | 0 | 2021 Q3c | G | GR-10 |
| M05.6 | Other theories (McGregor X/Y, Alderfer ERG) 🟢 | 0 | 0 | never asked; syllabus only | G | GR-10 |

> [!TIP]
> One motivation theory is asked in every final and they rotate: Maslow → Maslow → Vroom → Herzberg. Motivation was not in IM CT-1, making it a 100% lock for the final. Write M05.2 to M05.4 to the same depth.

## M06. HRM & Performance Appraisal (29 Final + 0 CT marks · 4/4 · 🔴 appraisal · 🟢 HRM)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| M06.1 | What HRM is 🟢 | 3 | 0 | 2020 Q3a | G | GR-08 |
| M06.2 | Recruitment vs. selection 🟢 | 4 | 0 | 2020 Q3b | G | GR-08 |
| M06.3 | Employee training: meaning and need 🟢 | 5 | 0 | 2020 Q3c | G | GR-08 |
| M06.4 | **Performance appraisal / management:** meaning; who appraises (supervisor, peers, self, subordinates, 360°); methods ♻️ | 7 | 0 | 2020 Q2b (½); 2021 Q4c (½) ≈ 2023 Q8c | G | GR-08 |
| M06.5 | **Rating-scale problems and how to avoid them:** halo, leniency/strictness, central tendency, recency, contrast ♻️ | 10 | 0 | 2020 Q2b (½); 2021 Q4c (½); 2024 Q8b | G | GR-08 |

---

# PART C: CO3 OPERATIONAL MANAGEMENT (MRI Sir)

## O01. Inventory Concepts (16 Final + 0 CT marks · 4/4 · 🔴)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| O01.1 | Meaning of inventory, inventory control and inventory management | 5 | 0 | 2020 Q4a (½); 2021 Q4a (½); 2023 Q7a (½) | M R | INV; RAI C-09 |
| O01.2 | **Costs of holding inventory** (high-level vs. low-level costs) | 7 | 0 | 2020 Q4a (½); 2021 Q4a (½); 2024 Q4a | M R | INV · costs for holding inventory; RAI C-09 |
| O01.3 | **Types of inventory:** cycle, safety stock, anticipation, pipeline | 4 | 0 | 2020 Q4c; 2023 Q7a (½) | M | INV · Types of Inventory |
| O01.4 | ABC analysis (A 20%/80%, B 30%/15%, C 50%/5%) ⭐ | 0 | 0 | never asked | M | INV · What is ABC Analysis? |

## O02. EOQ & Continuous Review (Q) System (34 Final + 20 CT marks · 4/4 · 🔴)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| O02.1 | **Define EOQ, reorder point, lead time, safety stock** ♻️ (in all 4 finals, twice in 2024) | 17 | 0 | 2020 Q4b; 2021 Q4b ≈ 2024 Q7a; 2023 Q7b; 2024 Q4b | M R | INV · What is EOQ?; RAI C-09 |
| O02.2 | EOQ assumptions and the cost curve (holding vs. ordering vs. total) ⭐ | 0 | 0 | never asked | M R | INV · Assumptions of EOQ; RAI C-09 |
| O02.3 | **Full continuous review ($Q$) system numerical** (one block; steps below) ♻️ 2024 Q7b = Class Exercise 1.2; OM-CT2 = MCU variant | 17 | 20 | 2023 Q7c (6); 2024 Q4c (5); 2024 Q7b (6); **OM-CT2 Q1a–f (20)** | M R C | INV · Solved Problem, Exercises; RAI C-10, C-11; CT §5 |
| O02.4 | ↳ Step: annual demand D (weekly × 52 or daily × 260) and EOQ | (block) | (block) | 4/4 numericals (incl. OM-CT2 a) | M R C | RAI C-10 Part (a); CT §5 |
| O02.5 | ↳ Step: safety stock $z\sigma_d\sqrt{L}$, z from service level (z not given in 2024 Q4c or OM-CT2), reorder point | (block) | (block) | 4/4 (incl. OM-CT2 a) | M R C | RAI C-10 Part (b); CT §5 |
| O02.6 | ↳ Step: inventory position $IP = OH + SR - BO$; order only if $IP \le R$ | (block) | (block) | 3/4 (2023, 2024 Q7b, OM-CT2 b) | R C | RAI C-10 Inventory Position; CT §5 |
| O02.7 | ↳ Step: total cost comparison (EOQ vs. given Q; current Q and R vs. new) | (block) | (block) | 4/4 (incl. OM-CT2 c) | R C | RAI C-10 Part (c); CT §5 |
| O02.8 | ↳ Step: orders per year ($N$), $TBO$, Q-system sawtooth graph | (block) | (block) | 2023 Q7c(v) + OM-CT2 d, e, f + Class 11 | R C | RAI C-11 Parts (d) to (f); CT §5 |

## O03. Productivity (0 Final + 0 CT marks · 0/4 · 🟠 · ⭐ taught in Class 11 after CT-2)

| ID | Subtopic | Final Marks | CT Marks | Occurrences | Cov. | Source |
| :-- | :-- | :-: | :-: | :-- | :-: | :-- |
| O03.1 | Definition of productivity (output ÷ input); key points | 0 | 0 | never asked | M R | PROD · Definition; RAI C-11 |
| O03.2 | Types: single-factor vs. multifactor | 0 | 0 | never asked | M | PROD · Types of productivity |
| O03.3 | **Single-factor numerical + % change month over month** | 0 | 0 | never asked | M R | PROD · Problems 1 to 7; RAI C-11 A |
| O03.4 | **Multifactor numerical** (labour + material + overhead in one currency) | 0 | 0 | never asked | M R | PROD · Problems; RAI C-11 B |
| O03.5 | Why productivity falls: challenges (human factors, technology, quality trade-off, resources, process, external, measurement) | 0 | 0 | never asked | M | PROD · Challenges faced… |
| O03.6 | Fixes: human factors (training, motivation, ergonomics) and technology (automation, Industry 4.0) | 0 | 0 | never asked | M R | PROD; RAI C-11 C |
| O03.7 | Productivity case studies (Bright Packaging, GreenLeaf Agro) | 0 | 0 | never asked | M | PROD · Case Studies |

---

## Skip List (⚫ Do Not Prioritize for the Semester Final)

| Item | Why |
| :-- | :-- |
| All accounting: journal, ledger, debit/credit rules, accounting cycle, transactions, double entry, trial balance, final accounts, cost sheet, cost classification, BEP, CVP, margin of safety (2020 and 2021 Section B) | Removed from the syllabus |
| BLC young-person sections other than Sec 41 (`L05.6`), adult working hours (`L05.8`), and safety sections other than Sec 62 (`L07.2`) | Already tested in Legal CT-2 and explicitly excluded from the final by Shoaib Sir's voice note |
| Syllabus-only topics with no notes and no past question: sale of goods, hire purchase, negotiable instruments, plant layout, linear programming, forecasting, MRP/MPS, scheduling, work study, Module 7 safety engineering | Not taught by either instructor and never asked |

---

## Appendix: Every Past Sub-Question and CT Mapped to an ID

Format: `Q (marks) → ID`. Split parts show both IDs.

### 2025 Class Tests (4 CTs · 15 Questions / 20 Parts · 80 Marks)

| IM CT-1 (MRI Sir · CO2 · 20m) | Legal CT-1 & CT-2 (SI Sir · CO1 · 40m) | OM CT-2 (MRI Sir · CO3 · 20m) |
| :-- | :-- | :-- |
| Q1 (2) → M02.3 | **Law-CT1 Q1 (10)** → L02.3 [+L02.1] | **OM-CT2 Q1(a–f) (20)** → O02.3 |
| Q2 (2) → M01.3 | **Law-CT1 Q2 (10)** → L02.5 [+L02.6] | ↳ (a) EOQ & ROP → O02.4, O02.5 |
| Q3 (2) → M01.2 | **Law-CT2 Q1 (10)** → L05.7 [+L05.8, L07.1, L07.2, L08.1–L08.6] | ↳ (b) IP decision → O02.6 |
| Q4 (2) → M01.5 | **Law-CT2 Q2 (10)** → L07.2 [+L05.6] | ↳ (c) Cost comparison → O02.7 |
| Q5 (2) → M02.3 | | ↳ (d) Orders/year $N$ → O02.8 |
| Q6 (2) → M02.1 | | ↳ (e) $TBO$ → O02.8 |
| Q7 (2) → M01.2 | | ↳ (f) Q-system graph → O02.8 |
| Q8 (2) → M01.2 | | |
| Q9 (2) → M01.2 | | |
| Q10 (2) → M04.3 | | |

### 2024 Final (60 marks answered, 80 on offer)

| Section A | Section B |
| :-- | :-- |
| Q1a (2) → M01.1 | Q5a (2) → M01.1 [+M01.3] |
| Q1b (4) → M01.4 | Q5b (3) → M01.4 |
| Q1c (4) → M02.3 | Q5c (5) → M03.1 |
| Q2a (2) → L02.1 | Q6a (2) → L02.4 |
| Q2b (3) → M05.1 | Q6b (4) → L02.7 |
| Q2c (5) → M05.3 | Q6c (4) → L04.1 |
| Q3a (2) → L10.2 | Q7a (4) → O02.1 |
| Q3b (4) → L10.4 | Q7b (6) → O02.3 |
| Q3c (4) → L11.5 | Q8a (2) → L11.3 (1) + L11.1 (1) |
| Q4a (2) → O01.2 | Q8b (4) → M06.5 |
| Q4b (3) → O02.1 | Q8c (4) → L10.8 |
| Q4c (5) → O02.3 | |

### 2023 Final (60 marks answered, 80 on offer)

| Section A | Section B |
| :-- | :-- |
| Q1a (2) → L05.2 | Q5a (2) → M01.1 |
| Q1b (4) → L05.5 [+L05.6] | Q5b (4) → M01.3 |
| Q1c (4) → L05.7 | Q5c (4) → M02.4 |
| Q2a (2) → L01.2 | Q6a (2) → M04.1 |
| Q2b (4) → L07.1 [+L07.2] | Q6b (3) → M04.2 |
| Q2c (4) → L07.3 | Q6c (5) → M04.3 |
| Q3a (2) → L02.2 | Q7a (2) → O01.1 (1) + O01.3 (1) |
| Q3b (4) → L02.3 | Q7b (2) → O02.1 |
| Q3c (4) → L02.8 | Q7c (6) → O02.3 |
| Q4a (2) → L11.1 (1) + L11.2 (1) | Q8a (3) → M05.1 |
| Q4b (4) → L12.4 | Q8b (4) → M05.4 |
| Q4c (4) → L12.5 | Q8c (3) → M06.4 |

### 2021 Final (Section A only, 48 marks)

| Q | → ID | Q | → ID |
| :-- | :-- | :-- | :-- |
| Q1a (3) | M01.1 [+M01.3] | Q3a (3) | M05.1 |
| Q1b (5) | M03.1 | Q3b (6) | M05.2 |
| Q1c (4) | M02.3 | Q3c (3) | M05.5 |
| Q2a (6) | M04.2 (3) + M01.3 (3) | Q4a (4) | O01.1 (2) + O01.2 (2) |
| Q2b (6) | M04.4 | Q4b (4) | O02.1 |
| | | Q4c (4) | M06.4 (2) + M06.5 (2) |

### 2020 Final (Section A only, 48 marks)

| Q | → ID | Q | → ID |
| :-- | :-- | :-- | :-- |
| Q1a (3) | M01.1 | Q3a (3) | M06.1 |
| Q1b (4) | M01.4 | Q3b (4) | M06.2 |
| Q1c (5) | M03.3 | Q3c (5) | M06.3 |
| Q2a (6) | M05.1 (2) + M05.2 (4) | Q4a (5) | O01.1 (2) + O01.2 (3) |
| Q2b (6) | M06.4 (2) + M06.5 (4) | Q4b (4) | O02.1 |
| | | Q4c (3) | O01.3 |

### Check Totals

| Paper / Source | Counted Marks | CO1 | CO2 | CO3 |
| :-- | :-: | :-: | :-: | :-: |
| 2024 Final | 80 | 28 | 32 | 20 |
| 2023 Final | 80 | 40 | 30 | 10 |
| 2021 Final (Sec A) | 48 | 0 | 40 | 8 |
| 2020 Final (Sec A) | 48 | 0 | 36 | 12 |
| **Finals Subtotal (69 sub-Qs)** | **256** | **68** | **138** | **50** |
| **2025 Class Tests (4 CTs, 15 Qs)** | **80** | **40** | **20** | **20** |
| **Grand Total** | **336** | **108** | **158** | **70** |
