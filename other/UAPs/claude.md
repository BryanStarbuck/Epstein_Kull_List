# UAP Deaths & Silenced Witnesses — Project Instructions

## Charter

This directory tracks **people who were killed, died suspiciously, disappeared, or were retaliated against** because of their connection to UAP/UFO information. **Murders are the highest priority.**

We document:

* **People murdered for exposing UAP information** — whistleblowers, researchers, journalists, and insiders who went public (or were about to) with classified or sensitive UAP-related knowledge
* **People murdered for possessing UAP information** — military, intelligence, and civilian personnel who held classified knowledge about recovered craft, reverse-engineering programs, non-human intelligence, or related black projects
* **People who disappeared or were silenced** under circumstances suggesting their UAP knowledge made them a target
* **People retaliated against** — fired, threatened, blacklisted, discredited, surveilled, institutionalized, or otherwise punished for their UAP-related knowledge or disclosure efforts
* **Living persons at credible risk** — current whistleblowers, witnesses, or insiders whose public statements or classified access put them in danger

### Priority Order

1. **Murdered** — highest priority. People killed and deaths made to look like suicides, accidents, or natural causes
2. **Disappeared** — vanished under suspicious circumstances
3. **Physically harmed** — poisoned, irradiated, assaulted, injured in suspicious "accidents"
4. **Institutionalized** — committed to psychiatric facilities to discredit and silence
5. **Career destroyed / fired / blacklisted** — professional retaliation for UAP knowledge or disclosure
6. **Threatened** — explicit threats, surveillance, intimidation, break-ins
7. **Living and at risk** — current whistleblowers and witnesses in danger

### The Audience

The audience is **investigators, researchers, journalists, and members of the public** who take these cases seriously. They are open to the possibility that the official government narrative — that UAPs are not real, that there are no recovery programs, that this is all conspiracy theory — may be false.

This is **serious investigative documentation**, not speculation or entertainment. We approach these cases the way an investigative journalist would: we don't require courtroom-level proof to document a case, but we do require meaningful facts that deviate from what would be normal. Suspicious timing, forensic anomalies, missing evidence, contradicted official rulings, patterns across multiple cases — these are all legitimate indicators worth documenting.

**We measure a thesis not because there's 100% solid proof on everything, but because there are meaningful facts that deviate from something normal.** We document those deviations thoroughly and let the reader assess the weight of the evidence.

### What Belongs Here

A person qualifies for this list if there is a credible argument that their death, disappearance, or retaliation is connected to:

- Recovered non-human craft or materials
- Reverse-engineering or exploitation programs (e.g., AATIP, AAWSAP, legacy SAPs)
- Classified aerospace and defense technology with UAP overlap (SDI/Star Wars, black projects)
- Zero-point energy, antigravity, or exotic propulsion linked to UAP reverse-engineering
- Government knowledge of non-human intelligence
- UAP-related testimony, disclosure efforts, or congressional investigations
- UAP encounters that resulted in physical harm (radiation, burns, physiological effects)

The connection can range from **strong** (e.g., Phil Schneider lecturing about DUMBs before being found dead) to **speculative** (e.g., scientists killed with no direct UAP evidence but whose work overlaps UAP-adjacent fields). Both belong here — the suspicion level rating captures the strength of the link.

### What Does NOT Belong Here

- Energy suppression cases with **no UAP connection** — those go in `../Zero_Point_Energy/`
- Epstein network deaths — those go in the main `../../Details/` directory
- Intelligence service political assassinations with **no UAP angle** — those go in `../Intel_Murders/`
- General conspiracy deaths with no plausible UAP connection

---

## Shared Work Directories

Agents working on this project have access to these shared directories:
* **Read-only:** `~/BGit/work/into_Work/` — Incoming work and management files
* **Read-only:** `~/BGit/act3/Our_Movies/` — Movie project files
* **Read-write:** `~/BGit/work/inout_work/` — Shared working directory for collaboration

## Web Search

Use web search when running prompts to find up-to-date information about individuals, events, court filings, congressional testimony, and news articles. This is a research-heavy project where current sources matter. Search for UAP/UFO-related deaths, suppression, whistleblower retaliation, and disclosure efforts.

---

## Directory Structure

```
UAPs/
├── README.md          # Master table: all UAP deaths, disappearances, and at-risk persons
├── claude.md          # This file — project instructions and templates
└── Details/           # One markdown file per person (nothing else goes here)
    ├── Phil_Schneider.md
    ├── Mark_McCandlish.md
    ├── James_Forrestal.md
    └── ...
```

### What Goes Where

| File | Purpose |
|------|---------|
| **README.md** | The master index. Contains all persons in categorized tables with one-line summaries. Contains pattern analysis sections, key reference points, cross-references to sibling directories, and a sources list. This is the entry point — visitors start here. |
| **Details/FirstName_LastName.md** | One file per person. Full investigative profile with metadata table, assessment, narrative, evidence, quotes, cross-links, and sources. File names use underscores, no spaces. |
| **claude.md** | This file. Project instructions, templates, writing guidelines. Not for public reading — it guides AI and human contributors. |

### Rules

- **One person per file** in `Details/`. Never combine multiple people into one file.
- **No non-person files** in `Details/`. Research notes, essays, and other content go elsewhere.
- **File naming**: `Details/FirstName_LastName.md` — underscores for spaces, no special characters. For people known by titles or call signs, use the name they're most commonly identified by (e.g., `William_Cooper.md` not `Bill_Cooper.md`).

---

## How It Works

* Visitors start at README.md and click through to individual profiles in Details/
* Web search is encouraged to gather additional information on each person
* Each new person needs both a row in README.md and a full profile in Details/

---

## README.md Structure

The README is the master document. It follows this structure (modeled on the parent project and sibling directories):

### 1. Header Navigation
```markdown
[< Back to Epstein Kill List](../../README.md) | [Intel Murders](../Intel_Murders/README.md) | [Energy Suppression](../Zero_Point_Energy/README.md) | [Groups](../groups/README.md)
```

### 2. Title and Introduction
- Project title
- 2-4 paragraphs of context: What this project documents, why it matters, key testimony (e.g., Grusch's congressional testimony), historical precedent (Binder's 137 researchers)
- Scope clarifiers: links to sibling directories for cases that don't belong here

### 3. Categorized Tables
People are organized into **category tables**, not one giant list. Each table covers a logical grouping. Current categories include:

- **Government Officials and Military Insiders**
- **Political Figures and Scientists Killed (Speculative UAP Connection)**
- **Disappeared (Recent)**
- **UFO/UAP Researchers and Investigators**
- **Aerospace Whistleblowers and Disclosure Witnesses**
- **Scientists and Energy Researchers (Suppressed Technology)**
- **GEC-Marconi / SDI "Star Wars" Scientists (1982–1990)**
- **Targeted Individuals and Institutionalized**
- **Military Pilot Deaths and Disappearances (UAP-Related)**
- **Disappeared**
- **Unexplained Deaths Attributed to UAP Encounters**

Each table uses this column format:

**For deceased persons:**
```markdown
| Name | Year | Cause of Death | Suspicion Level | Details |
|------|------|----------------|-----------------|---------|
| [Full Name](Details/Filename.md) | YYYY | How they died | **LEVEL** | One-line summary with key facts. |
```

**For living/at-risk persons:**
```markdown
| Name | Year | Cause of Death | Suspicion Level | Details |
|------|------|----------------|-----------------|---------|
| [Full Name](Details/Filename.md) | — | **ALIVE** | **AT RISK** | One-line summary of threat/situation. |
```

**For disappeared persons:**
```markdown
| Name | Year | Circumstances | Details |
|------|------|---------------|---------|
| [Full Name](Details/Filename.md) | YYYY | Missing since [date] | Summary of disappearance. |
```

### 4. Patterns Worth Noting
After all tables, a `## Patterns Worth Noting` section documents recurring patterns across cases. Each pattern is a bold-titled paragraph with inline links to relevant detail profiles. Patterns include things like:
- "Suicide" before testimony or disclosure
- Staged suicides with forensic anomalies
- The Marconi cluster (1982–1990)
- Career destruction preceding death
- Cancer cluster among UFO researchers
- Pilot deaths and disappearances
- Deathbed confessions from insiders

### 5. Key Reference Points
Major events that provide context: Grusch testimony, Disclosure Project, GEC-Marconi parliamentary inquiry, Otto Binder's research, UAP Disclosure Act.

### 6. Cross-References
Links to sibling directories and specific overlapping profiles:
- Epstein Kill List (main project)
- Intelligence Service Murders
- Zero Point Energy
- Groups directory

### 7. Sources
Bulleted list of primary references with URLs. Include:
- Congressional testimony transcripts and hearing pages
- Major news outlets (NPR, BBC, Fox News, Washington Post, Newsweek)
- Wikipedia articles for well-documented cases
- Books (author, title, year)
- Specialized sources (The Black Vault, Paranormal Insight, CrimeReads, etc.)
- Academic papers and declassified documents where available

### 8. Footer
```markdown
*Last Updated: [Date] — [Brief note on what was added]*
```

---

## Detail Profile Templates

Every person gets a full profile in `Details/`. The template varies slightly based on whether the person is deceased, living/at-risk, disappeared, or institutionalized.

### Template A: Deceased Person

```markdown
[< Back to UAP Deaths List](../README.md) | [Main Epstein List](../../../README.md)

# Full Name
One-line summary: who they were and how they died. Include their connection to UAP/UFO topics.

| Field | Details |
|-------|---------|
| **Full Name** | Legal name |
| **Born** | Date or year |
| **Died** | Full date |
| **Age at Death** | Number |
| **Location of Death** | City, State/Country |
| **Cause of Death** | How they died |
| **Official Ruling** | Suicide / Accidental / Homicide / Natural causes / etc. |
| **Category** | See person categories below |

## Assessment: [SUSPICION LEVEL]

2-3 sentence summary of why this death is or isn't suspicious. State the strongest
evidence. This is the most important section — it tells the reader immediately whether
this case has strong indicators or is speculative.

## Circumstances of Death

Narrative of what happened. Where found, when, by whom. What was unusual about the
scene, the timing, or the official ruling. Include specific forensic details when
available (e.g., "no fingerprints on the catheter," "suicide note written left-handed
but person was right-handed").

## Background

Who this person was. Their career, credentials, and qualifications. Their specific
connection to UAP/UFO research, classified programs, or disclosure efforts. What they
knew or claimed to know. What they were working on.

For researchers/inventors: describe their specific work, technology, or findings.
For military/intel insiders: describe their clearance level, programs, and access.
For witnesses: describe what they saw and when they went public.

## Why This Death Possibly Raises Questions

- Bullet points of each suspicious element
- Timing coincidences (e.g., died before scheduled testimony)
- Forensic anomalies (e.g., no fingerprints on weapon)
- Missing or destroyed evidence
- Contradictions between official story and physical evidence
- Warnings the person gave before dying ("if I die, it wasn't suicide")
- Parallel deaths of associates or collaborators
- Pattern connections to other cases in this project

## The Counterargument

- Official explanation and its supporting evidence
- Alternative plausible scenarios
- Known issues with the person's credibility (if any)
- Health conditions, personal problems, or other factors
- Why some skeptics find the official ruling adequate

This section is important for credibility. Including counterarguments shows
intellectual honesty and helps the reader weigh the evidence.

## Key Quotes from Media Coverage

> Blockquoted quotes with attribution and source links.
> — **Speaker Name**, Source, Date

Include quotes from: family members disputing rulings, colleagues, investigators,
the person themselves (especially pre-death warnings), official statements.

## See Also

- [Related Person](Related_Person.md) — Brief description of connection
- [Person in Sibling Directory](../Intel_Murders/Details/Person.md) — Cross-project link
- [Person in Parent Project](../../../Details/Person.md) — Parent project link

## Other Shocking Stories

- [Person Name](Person_Name.md): 18 words or less — the most shocking, suspicious, or unjust hook about this person. Maximum impact to make the reader click.
- [Person Name](Person_Name.md): 18 words or less — different person, different hook.
- [Person Name](Person_Name.md): 18 words or less — different person, different hook.
- [Person Name](Person_Name.md): 18 words or less — different person, different hook.

Pick 4 other people from the Details/ directory (not the current person). Choose a diverse mix — different categories, different eras. Write the hook to maximize reader engagement: focus on injustice, suspicious indicators, powerful motives for murder, or the most disturbing facts. Keep each hook to 18 words or fewer. Link each name to their profile using relative paths (e.g., `[Name](Name.md)`).

## Sources

- [Source Title](URL) — one per line
- Prefer: major news outlets, court documents, Wikipedia, congressional records
- Include: specialized UAP sources (The Black Vault, MUFON, etc.)
- Include: books (Author, *Title*, Year)
- Minimum 3-5 sources per profile; more for major cases

*This information was built by Grok and Claude AI research.*
```

### Template B: Living / At-Risk Person

Same structure as Template A with these modifications:

- **Metadata table**: Replace death fields with:
  - `| **Status** | ALIVE / AT RISK / THREATENED / SURVEILLED / etc. |`
  - `| **Current Location** | Where they are now (if public) |`
- **Replace "Circumstances of Death"** with **"Current Situation"** or **"Suppression Timeline"** — describe threats, retaliation, career destruction, surveillance, work seizure
- **Replace "Why This Death Possibly Raises Questions"** with **"Why This Person Is at Risk"** or **"Evidence of Retaliation"** or **"Safety Concerns"**
- Include: **What they disclosed or are disclosing** — specific claims, testimony, evidence
- Include: **Protective measures** — public "dead man's switch" statements, legal protections, whistleblower status
- For UAP whistleblowers/insiders, include:
  - What programs or information they had access to
  - What stage their disclosure is at (pre-testimony, testified, ongoing, under NDA)
  - Who allegedly retaliated against them (agency, contractor, unknown actors)
  - What happened to their career, security clearance, or personal safety after disclosure

### Template C: Disappeared Person

Same as Template A with:
- `| **Status** | MISSING since [date] |`
- `| **Last Known Location** | Where they were last seen |`
- Replace "Circumstances of Death" with **"Circumstances of Disappearance"**
- Include timeline of last known movements
- Include search efforts and their outcomes

### Template D: Institutionalized / Targeted Individual

Same as Template A with:
- `| **Status** | INSTITUTIONALIZED / COMMITTED / TARGETED |`
- Replace "Circumstances of Death" with **"How They Were Neutralized"**
- Document the specific disinformation, legal, or psychiatric tactics used
- Name the agencies or actors involved (with attribution language)

---

## Person Categories

Use one of these categories in the metadata table:

- **Government Official / Military Insider** — Held classified access, military rank, or government position
- **Government Contractor / Whistleblower** — Civilian with classified access who went public
- **Intelligence Officer** — CIA, DIA, NSA, or foreign intelligence with UAP knowledge
- **UFO/UAP Researcher** — Civilian researcher, author, or investigator
- **Aerospace Illustrator / UFO Disclosure Witness** — Provided testimony or visual documentation
- **Scientist / Engineer** — Academic or industrial researcher working on UAP-adjacent technology
- **Military Pilot** — Pilot who encountered UAPs or pursued unidentified craft
- **Journalist / Investigator** — Reported on UAP topics
- **Contactee / Experiencer** — Claimed direct contact or abduction
- **Defense Scientist (GEC-Marconi)** — Specifically for the 1982-1990 cluster
- **Energy Inventor** — Worked on technology with UAP reverse-engineering overlap
- **Targeted Individual** — Subjected to confirmed government harassment/disinformation

---

## Suspicion Ratings

Rate every case. The rating captures the strength of evidence connecting the death/incident to UAP-related silencing, not whether the death itself is suspicious in a general sense.

| Rating | Meaning |
|--------|---------|
| **HIGHLY SUSPICIOUS** | Strong evidence of foul play connected to UAP knowledge. Forensic anomalies, missing evidence, died before testimony, multiple corroborating indicators. |
| **SUSPICIOUS** | Multiple red flags, timing coincidences, or contested official rulings. Reasonable to suspect UAP connection but not conclusive. |
| **MODERATE SUSPICION** | Some concerning details but partial explanations exist. UAP connection is plausible but other motives may also explain the death. |
| **UNCERTAIN** | Possible connection but largely speculative. Included because the person's work or knowledge overlaps with UAP topics. |
| **UNCERTAIN (UAP link)** | Death is suspicious on its own merits but the specific connection to UAPs is speculative or debated. |
| **NOT SUSPICIOUS** | Person had UAP connections but death appears genuinely natural or accidental. Included for completeness or as a notable deathbed disclosure. |
| **NOT SUSPICIOUS (UAP link debunked)** | UAP connection was alleged but has been debunked by investigation. |
| **CONFIRMED** | Government harassment or operation is confirmed by official documents, judicial findings, or agency admission (e.g., AFOSI targeting of Bennewitz). |

For living persons:
- **AT RISK** — Active whistleblower/witness in potential danger
- **THREATENED** — Has received explicit threats
- **SURVEILLED** — Under confirmed or suspected surveillance
- **Radiation-injured witness** — Physically harmed by UAP encounter

---

## Writing Style

### Lead with Facts

Every profile leads with verified facts before presenting suspicions. State what is documented and sourced before discussing what is alleged or theorized.

### Evidence-Based Suspicion

We take suspicious indicators seriously — but we document them honestly:

- **State what the suspicious facts actually are** — "no fingerprints on the catheter," "died 10 days before scheduled Senate testimony," "body found in area already searched"
- **Don't editorialize** — let the facts speak. "The rubber catheter had no fingerprints" is more powerful than "obviously someone else wrapped it around his neck"
- **Include counterarguments** — document mental health history, personal problems, alternative explanations. This strengthens credibility, not weakens it
- **Distinguish tiers of evidence** — what is court-proven vs. what is testimony vs. what is claimed in books vs. what circulates online

### Defamation Prevention

This project documents real people, real deaths, and real organizations. Defamation-safe language is mandatory:

| Evidence Tier | How to Frame It |
|--------------|-----------------|
| Court findings, convictions, official inquiries | State as fact |
| Declassified government documents | State as fact with document citation |
| Sworn testimony and depositions | "testified under oath that..." |
| Major outlet journalism (NPR, BBC, etc.) | "reported by [outlet]..." |
| Investigative journalism from major outlets | "reported by [outlet]..." |
| Books and documentaries | "claimed in [title] by [author]..." |
| Whistleblower statements (not under oath) | "stated that..." or "claimed that..." |
| Unverified online accounts | "unverified claims circulated that..." |
| Social media theories (X/Twitter) | "X theorists allege..." or "social media speculation suggests..." |

**Always:**
- Use "allegedly," "reportedly," "according to" for all unconfirmed claims
- Attribute claims to their source — "According to [book/article/testimony]..." not stated as fact
- Include denials when the accused party has denied allegations
- For living persons and active organizations: note legitimate roles before allegations
- For intelligence services: frame as "alleged" unless confirmed by declassified documents or official inquiries
- For currently operating companies: note their current legitimate operations before discussing allegations
- Never present speculation as fact — if the connection is circumstantial, say so explicitly

### Tone

- **Investigative, not conspiratorial** — write like a journalist, not an advocate
- **Specific, not vague** — cite dates, locations, names, document numbers
- **Respectful of the dead** — these are real people; write with gravity
- **No emojis** — professional tone throughout
- **Straightforward** — avoid hedging language when facts are established; avoid certainty language when they're not

### Additional Writing Guidelines

* Include the person's own words when available (quotes from interviews, lectures, podcasts, court filings)
* Include family members' statements when they dispute official rulings
* Note when evidence was destroyed, sealed, or went missing
* Always include the "See Also" section linking to related profiles — this creates the web of connections
* Cross-link to group files in `../groups/` when a person is connected to a documented group

### Footer

Every profile ends with:
```markdown
*This information was built by Grok and Claude AI research.*
```

---

## Cross-Linking

Cross-linking creates the investigative web that makes this project valuable. Every connection between people, events, and organizations should be a clickable link.

### Within This Directory

- **README → Details**: Every person in a README table links to their profile: `[Name](Details/Name.md)`
- **Details → README**: Every profile has a back-link header: `[< Back to UAP Deaths List](../README.md)`
- **Details → Details**: When one person's profile mentions another person documented here, link to them: `[Phil Schneider](Phil_Schneider.md)` (relative path within Details/)
- **README patterns → Details**: Pattern analysis sections use inline links to every referenced profile

### To Sibling Directories

- **To Intel Murders**: `[Person Name](../Intel_Murders/Details/Person_Name.md)`
- **To Zero Point Energy**: `[Person Name](../Zero_Point_Energy/Details/Person_Name.md)`
- **To Groups**: `[Group Name](../groups/group_name.md)`
- **To Locations**: `[Location](../locations/location_name.md)`

### To Parent Project

- **To main Epstein Details**: `[Person Name](../../Details/Person_Name.md)`
- **To main README**: `[Epstein Kill List](../../README.md)`

### From Other Projects to Here

Other directories should link back to UAP profiles when relevant. If a person appears in multiple directories (e.g., Frank Olson appears in both Intel Murders and UAPs), both profiles should link to each other.

### When to Create Cross-Links

- When a person is **mentioned by name** in another person's profile
- When two people **died under similar circumstances** (e.g., same method, same time period)
- When people **worked together** or were in the **same program/organization**
- When a person's death is part of a **documented cluster** (e.g., Marconi scientists)
- When a person appears in a **sibling directory** under a different context

---

## Adding a New Person

### Step 1: Research

Use web search to gather thorough information before writing. Look for:
- News articles about the death/incident
- Wikipedia pages
- Court documents or official rulings
- Family member statements
- Books and documentaries that cover the case
- Congressional testimony or declassified documents
- Existing coverage in UAP/UFO research communities

Search for the person's name + "death," "murder," "suicide," "suspicious," "UFO," "UAP," "classified," "whistleblower," or relevant keywords for their area.

### Step 2: Create the Detail Profile

- Filename: `Details/FirstName_LastName.md`
- Use the appropriate template (A, B, C, or D above)
- Include at least 3-5 sources
- Include cross-links to related profiles

### Step 3: Add to README.md

- Add a row to the appropriate category table in README.md
- Place it in the correct table based on the person's category
- Within each table, order by suspicion level (highest first), then by year
- Deceased go in the relevant category deaths table
- Living/missing/at-risk go in the appropriate living/at-risk or disappeared table
- Include the one-line summary in the Details column

### Step 4: Update Patterns

- Check if the person fits any existing pattern in the "Patterns Worth Noting" section
- Add them to relevant pattern lists with inline links
- If they reveal a new pattern, add a new pattern section

### Step 5: Cross-Link

- Link from the new profile to any related existing profiles
- Update existing profiles to link back to the new one
- Add cross-references to sibling directories if applicable

---

## Patterns to Watch For

When adding new entries, check if they fit these documented patterns (and add new patterns when they emerge):

- **"Suicide" before testimony or disclosure** — People scheduled to testify or publish who die first
- **Staged suicides with forensic anomalies** — Missing fingerprints, wrong-hand notes, physically impossible methods
- **Career destruction preceding death** — Discredit → isolate → destroy → death
- **Deaths of Disclosure Project witnesses** — People who testified at the 2001 National Press Club event
- **Cancer cluster among UFO researchers** — Unusually fast-acting cancers in UFO investigators
- **GEC-Marconi cluster (1982-1990)** — 25 defense scientists in 8 years, SDI-connected
- **Pilot deaths and disappearances** — Military/civilian pilots who encounter or pursue UAPs
- **Area 51 / Groom Lake worker harm** — Toxic exposure, state secrets invoked to block lawsuits
- **Deathbed confessions from insiders** — People who wait until dying to speak
- **Disinformation campaigns to discredit** — AFOSI-style operations to drive targets to breakdown
- **Suppressed energy technology deaths** — Overlap with Zero Point Energy directory
- **Congressional testimony on killings** — Officials acknowledging harm under oath

---

## Sources and Research Standards

### Preferred Sources (in order of credibility)

1. **Congressional testimony and hearing records** — House Oversight, Senate Intelligence Committee
2. **Declassified government documents** — FOIA releases, official inquiries
3. **Court documents** — rulings, depositions, evidence records
4. **Major news outlets** — NPR, BBC, CNN, NBC, Washington Post, Fox News, Newsweek
5. **Quality investigative journalism** — CyberNews, CrimeReads, specialized investigative reporters
6. **Wikipedia** — for well-documented historical cases
7. **Books by credentialed authors** — Nick Redfern, Nick Cook, Greg Bishop, H.P. Albarelli
8. **UAP-specialized sources** — The Black Vault, MUFON, Paranormal Insight
9. **Documentary films and series** — with title, director, year
10. **Social media and forums** — lowest tier; use only for documenting claims others have made, not as evidence

### Minimum Source Requirements

- **Every profile**: At least 3-5 sourced links
- **Major cases** (HIGHLY SUSPICIOUS): 5-10+ sources preferred
- **Living persons at risk**: Extra sourcing required due to defamation concerns
- **Sources should be diverse** — don't rely solely on UFO community sources; include mainstream coverage when available

### Research Tools

- Use **web search** extensively — this is a research-heavy project where current sources matter
- Search for the person's name + "death," "murder," "suicide," "suspicious," "UFO," "UAP"
- Check Find a Grave for death details and family statements
- Check court record databases for legal proceedings
- Check congressional hearing archives for testimony

---

## Relationship to Sibling Directories

This project is one of several subdirectories under the [Epstein Kill List](../../README.md) umbrella. Each has a distinct focus:

| Directory | Focus | Location |
|-----------|-------|----------|
| **Main Epstein Kill List** | Deaths connected to Epstein's sex-trafficking/blackmail network | `../../README.md` |
| **Intel Murders** | Intelligence service political assassinations and state killings | `../Intel_Murders/` |
| **Zero Point Energy** | Advanced energy inventors/researchers killed or suppressed | `../Zero_Point_Energy/` |
| **UAPs** (this directory) | Deaths/silencing connected to UAP/UFO information | `./` |
| **Groups** | Organizations, intelligence services, and operations | `../groups/` |
| **Locations** | Geographic analysis of death clusters | `../locations/` |

### Overlap Rules

People can appear in multiple directories when they fit multiple scopes:
- **Frank Olson** — appears in both UAPs and Intel Murders (CIA scientist, MKULTRA, possible UAP connection)
- **Danny Casolaro** — appears in Intel Murders and main Epstein list (PROMIS software, intelligence connections)
- **Stanley Meyer** — appears in both UAPs and Zero Point Energy (water fuel cell, suppressed technology)

When a person appears in multiple directories:
- Each directory has its own full profile (not a stub that links elsewhere)
- Each profile emphasizes the angle relevant to that directory
- Each profile links to the version in the other directory
- The "See Also" section explicitly notes the cross-listing

---

## Key Concepts for Contributors

### What Makes a UAP-Related Death Suspicious

The core question is always: **Did this person's UAP-related knowledge or activities put them at risk, and does the evidence suggest their death was not what it appeared?**

Indicators we look for:
- Death occurred **shortly before or after** scheduled testimony, publication, or disclosure
- **Forensic anomalies** that contradict the official ruling
- **Missing or destroyed evidence** — files, recordings, research materials vanished
- The person **publicly predicted** they would be killed ("if I die, it wasn't suicide")
- **Associates or collaborators** also died under suspicious circumstances
- Death fits a **documented pattern** (same method, same time period, same program)
- **Official investigation** was unusually brief, incomplete, or refused to consider alternatives
- **Government agencies** appeared at the scene unusually quickly or removed materials
- The person had **classified access** to programs related to UAP recovery or reverse-engineering

### What We're NOT Doing

- We are not claiming every death here was a murder
- We are not claiming every UAP theory is true
- We are not ignoring evidence that contradicts our thesis
- We ARE documenting patterns that deserve investigation
- We ARE noting when official stories don't match physical evidence
- We ARE taking seriously the sworn testimony of government officials who say people have been killed

### The Standard of Evidence

We don't require courtroom-level proof. We document cases where **meaningful facts deviate from what would be normal**. A "suicide" where the gun has no fingerprints is worth documenting. A cluster of 25 defense scientists dying in 8 years is worth documenting. A whistleblower who said "if I die, investigate" and then died is worth documenting.

The suspicion level rating tells the reader how strong the evidence is. A reader can filter for only HIGHLY SUSPICIOUS cases if they want the strongest leads, or include UNCERTAIN cases if they want the full picture.

---

## Groups Directory (`../groups/`)

The `../groups/` directory (shared with the parent project) contains one markdown file per organization, intelligence service, black project, or cover-up operation. These files document the **group itself** — its history, scope, methods, and connections — and cross-link to individual people across all subdirectories including this one.

### What Qualifies as a Group (UAP-Relevant)

* **Intelligence services** — Any agency allegedly involved in UAP recovery, reverse-engineering, cover-ups, or witness intimidation (e.g., CIA, DIA, AFOSI, NSA, NRO)
* **Black programs** — Classified programs allegedly involved in UAP recovery or reverse-engineering (e.g., legacy SAPs, AATIP, AAWSAP)
* **Defense contractors** — Companies allegedly holding recovered materials or running reverse-engineering programs
* **Government entities** — Agencies that allegedly suppressed UAP information or retaliated against whistleblowers
* **Research organizations** — Groups investigating UAP phenomena (e.g., MUFON, Disclosure Project, TTSA)
* **Military units** — Specific units involved in UAP encounters, recoveries, or cover-ups

### Group File Template

```
[< Back to Main List](../../README.md) | [Groups Index](README.md)

# Group / Organization Name
One-line summary of what this group is and why it matters.

| Field | Details |
|-------|---------|
| **Type** | Intelligence Service / Black Program / Defense Contractor / Government Entity / etc. |
| **Active Period** | Years of operation |
| **Location(s)** | Where they operated |
| **Status** | Active / Disbanded / Under investigation / Classified / etc. |
| **Alleged Connection** | How this group connects to UAP suppression or the broader network |

## Overview

What this group is. What it allegedly did. How it connects to UAP recovery, reverse-engineering, cover-ups, or witness intimidation.

## Alleged Activities

* Bullet points of what the group allegedly did
* Use "allegedly," "reportedly," "according to [source]" throughout
* Distinguish verified facts from claims made in testimony, books, documentaries, or whistleblower statements

## Key Figures

* [Person Name](../../Details/Person_Name.md) — Role in the group (link to Details/ profile if one exists)
* Person Name — Role (no link if they don't have a Details/ profile yet)

## Connection to UAP Suppression

How this group connects to the broader UAP cover-up ecosystem. Shared personnel, methods, programs, or institutional relationships.

## Notable Books, Documentaries, and Investigations

* Book/film title — Author — Year — Key claims made
* Use these as sources but note they are claims, not proven facts

## Why This Group Matters

* What pattern it reveals
* What it tells us about the broader system of UAP suppression

## Sources

* Sourced links, one per line
* Congressional testimony, court documents, news reports, books, documentaries
* At least 3-5 sources per group file

*This information was built by Grok and Claude AI research.*
```

### Group File Naming

* Filename: `../groups/short_name.md` (lowercase, underscores, no spaces)
* Examples: `afosi.md`, `aatip.md`, `lockheed_skunkworks.md`, `disclosure_project.md`

### Groups Index File

* `../groups/README.md` — A master list of all group files, organized by type
* Each row links to the group file and gives a one-line description

### Cross-Linking Between Groups and People

* **Group files link to people:** In the "Key Figures" section, link to the person's Details/ profile in whichever directory they appear
* **Person files link back to groups:** In the person's "Background" or "See Also" section, link to `../groups/group_name.md`
* This creates a two-way web: readers can go from a person to the groups they were part of, or from a group to all the people involved

### What to Research for Each Group

* Use web search to gather information on:
  * The group's history and leadership
  * Congressional testimony mentioning the group
  * Declassified documents referencing the group
  * Books and documentaries that investigated them
  * Connections to known UAP whistleblowers or witnesses
  * Deaths of people connected to the group
  * Evidence of witness intimidation or retaliation
  * Evidence of UAP material recovery or reverse-engineering programs
