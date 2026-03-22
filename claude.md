# Epstein Kull List — Project Instructions

## DEFAMATION PREVENTION — MANDATORY RULES

**These rules override all other instructions. Every profile, README entry, and group file MUST comply.**

### The Core Rule

**Never state as fact that any living person committed, ordered, facilitated, or covered up any crime or harmful act — unless proven in court or officially acknowledged by them.**

Everything else about a living person must be attributed:
- "According to [source]..." / "[Source] alleges that..." / "reportedly" / "allegedly"

### Who Counts as a Living Person

- Anyone not confirmed dead
- Anyone whose death status is uncertain (missing, disappeared)
- Currently existing organizations (agencies, corporations, law firms)
- Estates and families of deceased persons

### Prohibited Patterns (about living persons unless court-proven)

| Prohibited | Safe Alternative |
|---|---|
| "[Person] destroyed evidence" | "According to [source], [Person] allegedly [action]" |
| "[Person] covered up the murder" | "According to [source], [Person] is alleged to have been involved in what [source] describes as a cover-up" |
| "[Person] ordered the killing" | "According to [source], [Person] allegedly ordered..." |
| "[Person] is a suspect" | "According to [investigator], [Person] is among those whose actions [investigator] has questioned" |
| "[Person] lied about..." | "According to [source], [Person]'s account is contradicted by..." |
| "[Person] is corrupt" | "[Source] has described [Person]'s actions as [specific description]" |
| "[Person] trafficked / abused / assaulted" | "According to [source/testimony/court filing], [Person] allegedly..." |

### Attribution by Evidence Tier

| Evidence Tier | How to Frame |
|---|---|
| **Court conviction** | State as fact: "[Person] was convicted of [crime] in [year]" |
| **Civil settlement** | "[Person] settled a lawsuit alleging [claim]" — do NOT state allegation as fact |
| **Official inquiry finding** | "The [inquiry] found that..." |
| **Sworn testimony** | "[Witness] testified under oath that..." |
| **Investigator's conclusions** | "According to [investigator]..." |
| **Journalist's reporting** | "As reported by [outlet/journalist]..." |
| **Book or documentary** | "According to [title] by [author]..." |
| **Another person's statement** | "[Speaker] stated that..." |
| **Unverified claims** | "Unverified claims suggest..." |

### Category-Specific Rules

- **Public figures:** Higher threshold but "actual malice" standard applies. Never state crimes as fact unless convicted. Add "has not publicly commented" when applicable.
- **Military/law enforcement:** Never call them suspects or accomplices as fact. Describe documented actions; attribute interpretations.
- **Intel agencies & corporations:** Frame involvement as "alleged" unless confirmed by declassified documents.
- **Convicted persons (e.g., Maxwell):** Convictions = fact. Anything beyond the conviction needs attribution.
- **Witnesses/victims:** Quote with "testified that..." — don't present their accounts as proven fact about the accused.

### Quality Check Before Publishing

1. Every accusation against a living person attributed to a named source
2. No living person called "suspect," "killer," or "accomplice" as fact
3. No living person said to have "destroyed evidence," "covered up," "lied" as fact (unless court-proven)
4. Every accused living person has denial included or "has not publicly responded" noted
5. Counterargument section includes alternative explanations
6. Third-party quotes marked "according to [source who reported the quote]"

**When in doubt, default to attribution. The cost of over-attributing is zero.**

---

## Scope

This project tracks **two interconnected areas** of suppression:

### 1. Elite Crimes & Cover-Ups (Epstein Network and Beyond)
People who died suspiciously or were silenced in connection with elite crimes — primarily Epstein's blackmail/trafficking operation, but also other Compromat operations, pedophile rings, and intelligence cover-ups.

### 2. Advanced Energy Suppression
People involved in **advanced energy breakthroughs** — zero-point energy, cold fusion, over-unity devices, advanced propulsion, unconventional fuel systems, electromagnetic energy harvesting, and any beyond-market energy technology.

**We track ALL forms of interference**, not only murders:
* **Killed** — murdered, suspicious deaths/suicides
* **Threatened** — death threats, intimidation, harassment
* **Physically attacked** — beaten, poisoned, injured
* **Work blocked** — patents denied, funding cut, projects shut down, labs raided
* **Work confiscated** — devices/prototypes/research seized
* **Work classified** — placed under secrecy orders, national security letters
* **Legal suppression** — lawsuits, injunctions, regulatory actions
* **Discredited** — smear campaigns, blacklisting, forced retractions
* **Disappeared** — went missing suspiciously
* **Imprisoned** — jailed on questionable charges

**Inclusion rule:** If someone falls within either scope area, they belong. Both areas involve powerful interests suppressing inconvenient people via the same patterns: suspicious deaths, seized evidence, classified records, compliant media, institutions looking away.

### Priority Order

1. **Murdered** — deaths disguised as suicides, accidents, or natural causes
2. **Disappeared** — vanished suspiciously
3. **Physically harmed** — poisoned, irradiated, assaulted
4. **Institutionalized** — committed to psychiatric facilities to silence
5. **Career destroyed** — professional retaliation
6. **Threatened** — explicit threats, surveillance, intimidation
7. **Living and at risk** — current whistleblowers in danger

---

## The Audience

Investigators, researchers, journalists, and public who take these cases seriously. Open to the possibility that official narratives may be incomplete or false.

This is **serious investigative documentation**, not speculation. We approach cases like investigative journalists: we don't require courtroom-level proof but do require meaningful facts deviating from normal. Suspicious timing, forensic anomalies, missing evidence, contradicted rulings, cross-case patterns — all legitimate indicators.

**We measure a thesis by meaningful facts that deviate from something normal.** We document those deviations and let readers assess.

---

## Shared Work Directories

* **Read-only:** `~/BGit/work/into_Work/`, `~/BGit/act3/Our_Movies/`
* **Read-write:** `~/BGit/work/inout_work/`

Use web search for up-to-date information on individuals, events, court filings, and news.

---

## Site Structure

```
Epstein_Kull_List/
├── README.md          # Master table of all people with one-line summaries
├── locations.md       # Geographic data and death clusters
├── CLAUDE.md          # This file
├── Details/           # One profile per person (nothing else)
│   ├── Jeffrey_Epstein.md
│   └── ...
└── other/             # Everything else
    ├── groups/        # One file per organization/operation
    │   ├── README.md  # Groups index
    │   └── ...
    ├── *.yaml         # YAML databases
    ├── *.csv          # CSV data files
    ├── laptop.md      # Weiner laptop overview
    └── ...
```

**Rules:**
- **One person per file** in `Details/`. Never combine people.
- **No non-person files** in `Details/`. Research notes go in `other/`.
- **File naming**: `Details/FirstName_LastName.md` — underscores, no spaces.

---

## How It Works

* Visitors start at README.md, click through to profiles in Details/
* Web search encouraged for additional information
* Each new person needs both a README row and a full Details/ profile

---

## README.md Structure

### Header
```markdown
[Locations](locations.md) | [Groups](other/groups/README.md)
```

### Content
1. **Title and Introduction** — 2-4 paragraphs of context
2. **Categorized Tables** — Epstein Network Deaths, Intelligence Service Murders, Banking/Finance Deaths, Witnesses and Accusers, Journalists and Investigators, Advanced Energy Inventors, Living Persons at Risk
3. **Patterns Worth Noting** — bold-titled paragraphs with inline links
4. **Cross-References** — links to subdirectories
5. **Sources** — bulleted references with URLs
6. **Footer** — `*Last Updated: [Date] — [what was added]*`

### Table Formats

**Deceased:** `| Name | Cause of Death | Suspicion Level | Details |`
**Living/at-risk:** `| Name | Status | Risk Level | Details |`
**Disappeared:** `| Name | Year | Circumstances | Details |`

---

## Detail Profile Templates

### Template A: Deceased Person

```markdown
[< Back to Main List](../README.md) | [Locations](../locations.md)

# Full Name
One-line summary: who they were, how they died, connection to scope area.

| Field | Details |
|-------|---------|
| **Full Name** | Legal name |
| **Born** | Date or year |
| **Died** | Full date |
| **Age at Death** | Number |
| **Location of Death** | City, State/Country |
| **Cause of Death** | How they died |
| **Official Ruling** | Suicide / Accidental / Homicide / Natural / etc. |
| **Category** | See categories below |

## Assessment: [SUSPICION LEVEL]
2-3 sentences: why suspicious or not. State strongest evidence.

## Circumstances of Death
Narrative: where found, when, by whom. Forensic details. What was unusual.

## Background
Career, credentials, connection to Epstein/elite crimes/energy research.
What they knew or claimed. What they worked on.
- Energy inventors: technology, findings, development stage
- Witnesses: what they saw, when they went public
- Financial figures: role in money flows
- Intel operatives: clearance level and access

## Why This Death Possibly Raises Questions
- Timing coincidences, forensic anomalies, missing evidence
- Contradictions with official story, pre-death warnings
- Parallel deaths, pattern connections

## The Counterargument
- Official explanation, alternative scenarios, credibility issues
- Health conditions, personal problems

## Key Quotes from Media Coverage
> Blockquoted quotes with attribution.

## See Also
- [Related Person](Related_Person.md) — connection description
- [Group Name](../other/groups/group_name.md) — connection to group

## Other Shocking Stories
- 4 entries from Details/, 18 words each max, diverse mix, maximize engagement

## Sources
- [Source Title](URL) — one per line
- 3-5 sources minimum; major cases 5-10+

*This information was built by Grok and Claude AI research.*
```

### Template B: Living / At-Risk / Suppressed Person

Same as A with modifications:
- Replace death fields with `Status` (ALIVE/AT RISK/THREATENED/etc.) and `Current Location`
- Replace "Circumstances of Death" with "Current Situation" or "Suppression Timeline"
- Replace "Why This Death..." with "Why This Person Matters" or "Evidence of Suppression"
- Include: what they disclosed, protective measures
- Energy cases: technology, stage, who suppressed, what happened to work/devices

### Template C: Disappeared Person

Same as A with `MISSING since [date]`, `Last Known Location`. Replace with "Circumstances of Disappearance". Include timeline and search efforts.

### Template D: Institutionalized / Targeted Individual

Same as A with `INSTITUTIONALIZED / COMMITTED / TARGETED`. Replace with "How They Were Neutralized". Document disinformation, legal, or psychiatric tactics.

---

## Adding a New Person

1. **Research** — web search for name + "death," "murder," "suicide," "suspicious," "Epstein," "suppressed." Check news, Wikipedia, court docs, family statements, books, congressional testimony.
2. **Create profile** — `Details/FirstName_LastName.md`, appropriate template, 3-5+ sources, cross-links
3. **Add to README.md** — correct category table, ordered by suspicion level then year
4. **Update patterns** — add to relevant pattern lists; add new patterns if needed
5. **Cross-link** — link from/to related profiles, groups, subdirectories

---

## Person Categories

### Epstein / Elite Crime
* Co-conspirator, Witness / Primary Accuser, Victim
* Journalist / Investigator, Law Enforcement, Banking / Finance
* Legal, Political Figure, Intelligence, Modeling Industry
* Celebrity / Public Figure, Whistleblower, Silenced Witness / Disappeared, Staff / Employee

### Advanced Energy
* Energy Inventor, Energy Researcher, Energy Whistleblower
* Energy Business, Energy Supporter / Funder

---

## Suspicion Ratings

Rates strength of evidence connecting death/incident to suppression or cover-up (not general suspicion).

| Rating | Meaning |
|--------|---------|
| **HIGHLY SUSPICIOUS** | Strong foul play evidence: missing evidence, impossible logistics, witness silenced, work seized, forensic anomalies, died before testimony |
| **SUSPICIOUS** | Multiple red flags, timing coincidences, contested rulings. Not conclusive |
| **MODERATE SUSPICION** | Concerning details but partial explanations exist. Other motives possible |
| **UNCERTAIN** | Largely speculative. Person's work/knowledge overlaps project scope |
| **Likely natural / old age** | Connected but death appears natural |
| **Not suspicious** | Named in context but death clearly unrelated |

**Living persons:** AT RISK, Missing, Under investigation, Arrested, THREATENED, SURVEILLED

**Suppression (energy):** CONFIRMED SUPPRESSION, WORK SEIZED, THREATENED, BLOCKED, DISCREDITED, CLASSIFIED

---

## Writing Style

### Lead with Facts
State documented, sourced facts before suspicions or theories.

### Evidence-Based Suspicion
- **State specific suspicious facts** — "no fingerprints on the weapon," "died 10 days before Senate testimony"
- **Don't editorialize** — let facts speak. "The catheter had no fingerprints" beats "obviously someone else did it"
- **Include counterarguments** — mental health history, personal problems, alternative explanations strengthen credibility
- **Distinguish evidence tiers** — court-proven vs. testimony vs. books vs. online claims

### Tone
- **Investigative, not conspiratorial** — write like a journalist
- **Specific** — dates, locations, names, document numbers
- **Respectful** — these are real people
- **No emojis**
- **Straightforward** — don't hedge established facts; don't assert uncertain claims

### Additional Guidelines
* Include the person's own words when available
* Include family statements disputing official rulings
* Note when evidence was destroyed, sealed, or went missing
* Always include "See Also" linking to related profiles
* Cross-link to group files when connected

### Footer
Every profile ends with: `*This information was built by Grok and Claude AI research.*`

---

## Cross-Linking

Every connection should be a clickable link.

### Path Formats
- **README → Details**: `[Name](Details/Name.md)`
- **Details → README**: `[< Back to Main List](../README.md)`
- **Details → Details**: `[Name](Name.md)` (relative within Details/)
- **Details → Groups**: `[Group](../other/groups/group.md)`
- **Groups → Details**: `[Person](../../Details/Person.md)`
- **To UAPs**: `[Name](other/UAPs/Details/Name.md)`

### When to Cross-Link
- Person mentioned by name in another profile
- Similar death circumstances
- Same organization/operation
- Part of a documented cluster
- Appears in a subdirectory under different context

### Overlap Rules
People can appear in multiple directories. Each gets a full profile emphasizing that directory's angle, linking to other versions. "See Also" notes cross-listings.

---

## Key Patterns to Watch For

### Epstein / Elite Crime
* Hangings in custody (Epstein, Brunel, Middleton)
* Deaths before testimony or trial
* Banking executives who handled Epstein's money
* Balcony/building falls
* Investigators/journalists who died while researching trafficking
* "If I die, it wasn't suicide" statements followed by death
* Cluster deaths in same time period
* Geographic clusters (Florida, NYC, Caribbean, Columbus OH, Europe)
* Intelligence connections (Mossad, CIA, PROMIS)
* Modeling industry pipeline victims
* Sealed records or destroyed evidence after death
* Career destruction preceding death — discredit → isolate → destroy → death
* Staged suicides with forensic anomalies

### Advanced Energy Suppression
* Died shortly after demonstrating working device
* Patents under government secrecy orders
* Labs raided or devices confiscated
* Threatened then died in "accidents" or "suicides"
* Prototypes disappeared after inventor's death
* Funding suddenly cut
* Offered buyouts, killed when refused
* Research classified under national security
* Smear campaigns labeling inventors as frauds
* Multiple inventors in same field dying in short period

---

## Sources and Research Standards

### Preferred Sources (credibility order)
1. Court documents — rulings, depositions, evidence, indictments
2. Congressional testimony and hearing records
3. Declassified government documents — FOIA, official inquiries
4. Major news outlets — NPR, BBC, CNN, NBC, WaPo, Fox News, Newsweek
5. Quality investigative journalism
6. Wikipedia — for well-documented cases
7. Books by credentialed authors — cite author, title, year
8. Documentary films — cite title, director, year
9. Specialized sources — topic-specific archives
10. Social media — lowest tier; only for documenting claims, not as evidence

### Requirements
- **Every profile**: 3-5+ sourced links
- **Major cases**: 5-10+ preferred
- **Living persons**: Extra sourcing for defamation safety
- **Diverse sources** — don't rely solely on niche communities

---

## Key Concepts

### What Makes a Death Suspicious

Core question: **Did this person's knowledge, activities, or connections put them at risk, and does evidence suggest their death was not what it appeared?**

Indicators:
- Death shortly before/after testimony, publication, or disclosure
- Forensic anomalies contradicting official ruling
- Missing/destroyed evidence
- Person publicly predicted being killed
- Associates also died suspiciously
- Death fits documented pattern
- Investigation was unusually brief or incomplete
- Government agencies appeared quickly or removed materials
- Person had access to information powerful people wanted secret

### What We're NOT Doing
- Not claiming every death was murder
- Not claiming every theory is true
- Not ignoring contradicting evidence
- ARE documenting patterns deserving investigation
- ARE noting when official stories don't match physical evidence
- ARE taking sworn testimony seriously

### Standard of Evidence
We don't require courtroom proof. We document cases where **meaningful facts deviate from normal**. The suspicion rating tells readers how strong the evidence is.

---

## Groups Directory (`other/groups/`)

One file per organization, intelligence service, blackmail operation, or trafficking ring. Documents the group's history, scope, methods, and connections. Cross-links to people in `Details/`.

### What Qualifies as a Group

* **Intelligence services** — agencies allegedly involved in blackmail, trafficking, Compromat, cover-ups
* **Epstein's operation** — the core trafficking/blackmail network
* **Prostitution / madam operations** — especially those supplying elites/politicians/intel services, involving minors, with surprisingly light consequences, with alleged intel/blackmail connections. **DC-area operations are highest priority.**
* **Financial institutions** — banks moving Epstein's money or laundering trafficking proceeds
* **Modeling agencies** — used as trafficking pipelines
* **Government entities** — USVI, DOJ units allegedly protecting the network
* **Media / suppression operations** — allegedly buried or destroyed evidence
* **Other Compromat rings** — Franklin scandal, PROMIS/Octopus, Dutroux network

### Group File Template

```markdown
[< Back to Main List](../../README.md) | [Groups Index](README.md)

# Group / Organization Name
One-line summary.

| Field | Details |
|-------|---------|
| **Type** | Intelligence Service / Blackmail Operation / Trafficking Ring / etc. |
| **Active Period** | Years |
| **Location(s)** | Where they operated |
| **Status** | Active / Disbanded / Under investigation / etc. |
| **Alleged Connection** | How connects to Epstein or broader network |

## Overview
## Alleged Activities
## Key Figures
## Connection to Epstein Network
## Notable Books, Documentaries, and Investigations
## Why This Group Matters
## Sources

*This information was built by Grok and Claude AI research.*
```

**Naming:** `other/groups/short_name.md` (lowercase, underscores)
**Index:** `other/groups/README.md` — master list by type
**Cross-linking:** Groups link to people via `../../Details/Person.md`; people link back via `../other/groups/group.md`

---

## Data Files (in other/)

* YAML: `epstein_deaths.yaml`, `epstein_deaths_comprehensive.yaml`
* CSV: `person_types.csv`, `person_categories.csv`, `locations.csv`
* Research: `findings_*.txt`, `detailed_*.txt`
* `laptop.md` — Weiner laptop overview
* `groups/` — organization and operation profiles
