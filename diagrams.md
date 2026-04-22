# Sui Guild Europe — Diagrams

## 1. Developer Acquisition Funnel

```mermaid
graph TD
    subgraph FUNNEL["🔷 SUI GUILD EUROPE — Developer Acquisition Funnel"]
        direction TB

        A["🌍 OUTREACH\n─────────────────────────────\nUniversity clubs · Conferences · Online communities\nDeVinci (FR/BE/UK) · KryptoSphère · BSA · W3N\n─────────────────────────────\nBroad reach across 9 countries"]

        B["📜 CERTIFICATION WORKSHOPS\n─────────────────────────────\n14 × 2-day in-person workshops\n─────────────────────────────\nUK (2) · Italy (2) · Germany (2) · Spain (2)\nPoland (2) · Estonia (1) · Belgium (1)\nFrance (1) · Portugal (1)\n─────────────────────────────\nFirst quality filter · Move fundamentals"]

        C["⚡ HACKATHONS\n─────────────────────────────\n4 hackathons · Real technical output\n─────────────────────────────\nUK · Italy · Estonia · Spain\n─────────────────────────────\nCuration by execution ability\nTeam formation · Project ideation"]

        D["🎓 BOOTCAMPS\n─────────────────────────────\n5 advanced bootcamps · Mysten engineers\n─────────────────────────────\nUK · France (Paris) · Poland (Warsaw)\nItaly · Spain\n─────────────────────────────\nSecurity · Indexing · Infra\nProduction-ready skills"]

        E["🚀 INCUBATOR\n─────────────────────────────\nLong-term ecosystem engagement\n─────────────────────────────\nBounties · Ecosystem contributions\nEmployment · Project founding\n─────────────────────────────\nSustained builders in Sui"]

        A -->|"University & community partnerships"| B
        B -->|"Top performers advance"| C
        C -->|"Curated developers"| D
        D -->|"Industry-ready builders"| E
    end

    style A fill:#1a1a2e,stroke:#4a9eff,color:#fff
    style B fill:#16213e,stroke:#4a9eff,color:#fff
    style C fill:#0f3460,stroke:#e94560,color:#fff
    style D fill:#533483,stroke:#e94560,color:#fff
    style E fill:#e94560,stroke:#fff,color:#fff
```

## 2. European Network — Events & Partners by Country

```mermaid
graph TB
    subgraph EUROPE["🇪🇺 SUI GUILD EUROPE — Network Map"]
        direction TB

        HQ["🏛️ COUNCIL OF 4\nAlex Mourot · Roel Theuniszen\nPhilip Kourousis · Taz (Legal)"]

        subgraph UK["🇬🇧 UNITED KINGDOM"]
            UK_E["2 Certifications · 1 Hackathon · 1 Bootcamp"]
            UK_P["Imperial College · Cambridge\nOxford · King's College\nDeVinci Blockchain"]
        end

        subgraph FR["🇫🇷 FRANCE"]
            FR_E["1 Certification · 1 Bootcamp (Paris)"]
            FR_P["KryptoSphère\nDeVinci Blockchain (HQ, 12+ antennas)"]
        end

        subgraph DE["🇩🇪 GERMANY"]
            DE_E["2 Certifications"]
            DE_P["TUM Blockchain Club (Munich)\nBerlin Conference Organizer"]
        end

        subgraph ES["🇪🇸 SPAIN"]
            ES_E["2 Certifications · 1 Hackathon · 1 Bootcamp"]
            ES_P["The Bridge"]
        end

        subgraph IT["🇮🇹 ITALY"]
            IT_E["2 Certifications · 1 Hackathon · 1 Bootcamp"]
            IT_P["Urbe ETH (Rome) — Bootcamp partner\nBSA Italy / Olga Arzhaeva\nBSBA (Milan)"]
        end

        subgraph PL["🇵🇱 POLAND"]
            PL_E["2 Certifications · 1 Bootcamp (Warsaw)"]
            PL_P["Local dev community"]
        end

        subgraph EE["🇪🇪 ESTONIA"]
            EE_E["1 Certification · 1 Hackathon"]
            EE_P["W3N Conference"]
        end

        subgraph BE["🇧🇪 BELGIUM"]
            BE_E["1 Certification"]
            BE_P["KryptoSphère\nDeVinci Blockchain"]
        end

        subgraph PT["🇵🇹 PORTUGAL"]
            PT_E["1 Certification"]
            PT_P["Decentralized Student Network (Técnico Lisbon)\nJose (via Roel) · Pedro (BSA)"]
        end

        HQ --> UK
        HQ --> FR
        HQ --> DE
        HQ --> ES
        HQ --> IT
        HQ --> PL
        HQ --> EE
        HQ --> BE
        HQ --> PT
    end

    style HQ fill:#e94560,stroke:#fff,color:#fff
    style UK fill:#1a1a2e,stroke:#4a9eff,color:#fff
    style FR fill:#1a1a2e,stroke:#4a9eff,color:#fff
    style DE fill:#1a1a2e,stroke:#4a9eff,color:#fff
    style ES fill:#1a1a2e,stroke:#4a9eff,color:#fff
    style IT fill:#1a1a2e,stroke:#4a9eff,color:#fff
    style PL fill:#1a1a2e,stroke:#4a9eff,color:#fff
    style EE fill:#1a1a2e,stroke:#4a9eff,color:#fff
    style BE fill:#1a1a2e,stroke:#4a9eff,color:#fff
    style PT fill:#1a1a2e,stroke:#4a9eff,color:#fff
```

## 3. Organization Structure

```mermaid
graph TD
    subgraph ORG["🏛️ SUI GUILD EUROPE — Organization"]
        direction TB

        C["COUNCIL OF 4\n━━━━━━━━━━━━━━━\nStrategic Governance"]

        C1["Alex Mourot\nDevRel Lead (CH)\n$6K/mo"]
        C2["Roel Theuniszen\nCouncil Member"]
        C3["Philip Kourousis\nCouncil Member"]
        C4["Taz\nLegal"]

        CT["CORE TEAM\n━━━━━━━━━━━━━━━\nOperations"]

        M1["Marketing Lead\nBased in Spain\n$2K/mo"]
        M2["Social / Discord Manager\n$2K/mo"]

        WF["MOBILE WORKFORCE\n━━━━━━━━━━━━━━━\nPolyvalent DevRel"]

        W1["Jules"]
        W2["Alex"]
        W3["Antoine"]

        LP["LOCAL PARTNERS\n━━━━━━━━━━━━━━━\nPer-country execution"]

        P1["DeVinci Blockchain\nFR · BE · UK"]
        P2["KryptoSphère\nFR · BE"]
        P3["The Bridge\nES"]
        P4["Urbe ETH\nIT (Rome)"]
        P5["BSA Italy / Olga\nIT"]
        P6["TUM Blockchain\nDE (Munich)"]
        P7["W3N Conference\nEE"]
        P8["DSN Técnico\nPT (Lisbon)"]

        MENTORS["EVENT MENTORS\n━━━━━━━━━━━━━━━\n$500/certif · $700/hackathon"]

        C --> C1 & C2 & C3 & C4
        C --> CT
        CT --> M1 & M2
        CT --> WF
        WF --> W1 & W2 & W3
        CT --> LP
        LP --> P1 & P2 & P3 & P4 & P5 & P6 & P7 & P8
        CT --> MENTORS
    end

    style C fill:#e94560,stroke:#fff,color:#fff
    style CT fill:#533483,stroke:#e94560,color:#fff
    style WF fill:#0f3460,stroke:#4a9eff,color:#fff
    style LP fill:#16213e,stroke:#4a9eff,color:#fff
    style MENTORS fill:#1a1a2e,stroke:#4a9eff,color:#fff
    style C1 fill:#e94560,stroke:#fff,color:#fff
    style C2 fill:#e94560,stroke:#fff,color:#fff
    style C3 fill:#e94560,stroke:#fff,color:#fff
    style C4 fill:#e94560,stroke:#fff,color:#fff
```

## 4. Q1-Q2 Timeline (Sep 2026 — Feb 2027)

```mermaid
gantt
    title Sui Guild Europe — Q1-Q2 Execution Timeline
    dateFormat YYYY-MM-DD
    axisFormat %b %Y

    section Q1 (Sep-Nov 2026)
    ── CERTIFICATIONS ──          :milestone, 2026-09-01, 0d

    UK Certification 1 (Cambridge/Oxford)     :cert1, 2026-09-08, 5d
    Germany Certification (Munich/TUM)        :cert2, 2026-09-15, 5d
    France Certification (KryptoSphère)       :cert3, 2026-09-22, 5d
    Belgium Certification (KryptoSphère)      :cert4, 2026-10-01, 5d
    Italy Certification 1 (Milan/BSBA)        :cert5, 2026-10-08, 5d
    Spain Certification 1 (The Bridge)        :cert6, 2026-10-15, 5d
    Poland Certification 1                    :cert7, 2026-10-22, 5d
    Estonia Certification (W3N)               :cert8, 2026-10-29, 5d
    Germany Certification 2 (Berlin)          :cert9, 2026-11-05, 5d
    Portugal Certification (Técnico Lisbon)   :cert10, 2026-11-12, 5d

    ── HACKATHONS ──              :milestone, 2026-10-15, 0d

    Estonia Hackathon (W3N)                   :hack1, 2026-11-01, 7d
    UK Hackathon (multi-university)           :hack2, 2026-11-10, 7d

    section Q2 (Dec 2026 - Feb 2027)
    ── REMAINING CERTIFICATIONS ──:milestone, 2026-12-01, 0d

    UK Certification 2 (Imperial/King's)      :cert11, 2026-12-01, 5d
    Italy Certification 2 (Rome/Urbe)         :cert12, 2026-12-08, 5d
    Spain Certification 2                     :cert13, 2026-12-15, 5d
    Poland Certification 2                    :cert14, 2027-01-06, 5d

    ── HACKATHONS ──              :milestone, 2026-12-15, 0d

    Italy Hackathon (Rome + Milan)            :hack3, 2027-01-12, 7d
    Spain Hackathon (The Bridge)              :hack4, 2027-01-26, 7d

    ── BOOTCAMPS ──               :milestone, 2027-01-15, 0d

    UK Bootcamp                               :boot1, 2027-01-19, 10d
    France Bootcamp (Paris)                   :boot2, 2027-01-26, 10d
    Poland Bootcamp (Warsaw)                  :boot3, 2027-02-02, 10d
    Italy Bootcamp (Urbe ETH)                 :boot4, 2027-02-09, 10d
    Spain Bootcamp                            :boot5, 2027-02-16, 10d
```

## Updated Budget (with Portugal + Germany additions)

```mermaid
pie title Q1-Q2 Budget Allocation — $345,000
    "Bootcamps (5)" : 150000
    "Hackathons (4)" : 80000
    "Certifications (14)" : 70000
    "Core Team Salaries (6mo)" : 60000
    "Travel & Logistics" : 25000
    "Content Creation" : 20000
```

| Category | Unit Cost | Qty | Total |
|---|---|---|---|
| Bootcamps (UK, Paris, Poland, Italy, Spain) | $30,000 | 5 | $150,000 |
| Hackathons (ops + prize pool) | $20,000 | 4 | $80,000 |
| 2-Day Certification Workshops | $5,000 | 14 | $70,000 |
| Travel & Logistics | — | — | $25,000 |
| Content Creation | $1,000 | 15–20 | $20,000 |
| Core Team Salaries (6 months) | $10,000/mo | 6 | $60,000 |
| **TOTAL** | | | **$345,000** |

*Note: +2 certifications (Germany Berlin + Portugal) = +$10K certs, +$5K travel vs original budget.*
