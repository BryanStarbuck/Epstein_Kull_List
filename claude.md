# Epstein Kull List — Project Instructions

## Scope

This project tracks **two interconnected areas** of suppression:

### 1. Elite Crimes & Cover-Ups (Epstein Network and Beyond)
People who died suspiciously, were likely murdered, or were silenced in connection with elite-level crimes — primarily Jeffrey Epstein's blackmail and trafficking operation, but also other Compromat operations, pedophile rings, and intelligence service cover-ups.

### 2. Advanced Energy Suppression
People involved in **advanced energy breakthroughs and non-traditional energy** — including but not limited to zero-point energy, cold fusion, over-unity devices, advanced propulsion, unconventional fuel systems, electromagnetic energy harvesting, and any energy technology that goes beyond what is currently available on the market.

**We track ALL forms of interference against these people and their work**, not only murders. This includes:
* **Killed** — Murdered, died under suspicious circumstances, suspicious suicides
* **Threatened** — Death threats, intimidation, harassment campaigns
* **Physically attacked** — Beaten, assaulted, poisoned, injured
* **Work blocked** — Patents denied, funding cut off, projects shut down, labs raided
* **Work confiscated** — Devices seized, prototypes taken, research confiscated by government or unknown parties
* **Work classified** — Research classified by government agencies, placed under secrecy orders, national security letters
* **Legal suppression** — Lawsuits, injunctions, regulatory actions used to stop research
* **Discredited** — Smear campaigns, professional blacklisting, forced retractions
* **Disappeared** — Went missing, dropped off the radar under suspicious circumstances
* **Imprisoned** — Jailed on questionable charges related to their energy work

**We care about anyone where some level of power is involved or possibly involved** in the suppression — governments, military, intelligence services, universities, corporations, patent offices, regulatory bodies, or unknown actors willing to use threats or force.

### What Ties These Together

Both areas involve powerful interests suppressing inconvenient people. The same patterns appear: suspicious deaths, seized evidence, classified records, compliant media, and institutions that look the other way. A person can fall into one or both areas.

**Inclusion rule:** If someone falls within either scope area, they belong in this project. Existing entries that predate this expanded scope remain — they are still within scope.

## Shared Work Directories

Agents working on this project have access to these shared directories:
* **Read-only:** `~/BGit/work/into_Work/` — Incoming work and management files
* **Read-only:** `~/BGit/act3/Our_Movies/` — Movie project files
* **Read-write:** `~/BGit/work/inout_work/` — Shared working directory for collaboration

## Web Search

Use web search when running prompts to find up-to-date information about individuals, events, court filings, and news articles. This is a research-heavy project where current sources matter. Search for both Epstein-related and advanced energy suppression topics.

## Links Between Markdown Files

All markdown files should be interconnected:
- Every Details page should link back to the main [README.md](README.md).
- Details pages should cross-link to related individuals (e.g., co-conspirators, same cluster of deaths, shared connections, same field of energy research).
- The main README.md table must link to each person's Details page.
- Pattern sections in README.md should use inline links to the relevant Details pages.
- If a person is mentioned in another person's Details page, that mention should be a link to their Details page (e.g., `[Ghislaine Maxwell](Ghislaine_Maxwell.md)`).

## Overview

A comprehensive list of people who were killed, threatened, attacked, suppressed, or had their work blocked or confiscated — in connection with either (1) elite-level crimes such as Jeffrey Epstein's blackmail and trafficking operation, Compromat operations, pedophile rings, and intelligence service cover-ups, or (2) advanced energy breakthroughs and non-traditional energy technologies that challenge established energy markets.

## Focus Areas

* Jeffrey Epstein-related deaths and suppression (highest priority)
* Intelligence service-level murders, blackmail, and cover-ups
* Elite pedophile rings
* Deep state cover-ups
* Advanced energy inventors who were killed, threatened, or had their work suppressed
* Non-traditional energy breakthroughs blocked by governments, corporations, or unknown actors
* Zero-point energy, cold fusion, over-unity, advanced propulsion, and related technologies
* Patent suppression, secrecy orders, and classified energy research

## Suspicion Ratings

* Each entry should show a level of suspicion — it doesn't have to be provable in court
* Include anyone with credible reports of foul play or suppression, then assess the likelihood
* Levels used (from highest to lowest):
  * **HIGHLY SUSPICIOUS** — Strong evidence of foul play (missing evidence, impossible logistics, key witness silenced, work seized)
  * **SUSPICIOUS** — Multiple red flags, timing coincidences, or contested official rulings
  * **MODERATE SUSPICION** — Some concerning details but partial explanations exist
  * **UNCERTAIN** — Possible connection but largely speculative or weak link
  * **Likely natural / Likely old age** — Person was connected but death appears natural
  * **Not suspicious** — Named in context but death clearly unrelated
* For living persons: **AT RISK**, **Missing**, **Under investigation**, **Arrested**, etc.
* For suppression (especially energy cases): **CONFIRMED SUPPRESSION**, **WORK SEIZED**, **THREATENED**, **BLOCKED**, **DISCREDITED**, **CLASSIFIED**

## Site Structure

* `README.md` — Main entry point; the master table of all people with one-line summaries
* `locations.md` — Geographic data
* `CLAUDE.md` — This file (project guidance)
* `Details/` — One profile per person (no other files in this directory)
* `other/` — Everything else (research notes, YAML databases, CSV files, laptop overview, etc.)
* `other/groups/` — One file per organization, intelligence service, or operation (see Groups section below)

## How It Works

* Visitors start at README.md and click through to individual profiles in Details/
* Web search is encouraged to gather additional information on each person
* Each new person needs both a row in README.md and a full profile in Details/

## Adding a New Person

### Step 1: Create the Detail Profile

* Filename: `Details/FirstName_LastName.md` (underscores, no spaces)
* Use web search to gather thorough information before writing

### Step 2: Profile Structure (Deceased Persons)

Every profile follows this template:

```
[< Back to Main List](../README.md) | [Locations](../locations.md)

# Full Name
One-line summary: who they were and how they died.

| Field | Details |
|-------|---------|
| **Full Name** | Legal name |
| **Born** | Date or year |
| **Died** | Full date |
| **Age at Death** | Number |
| **Location of Death** | City, State/Country |
| **Cause of Death** | How they died |
| **Official Ruling** | Suicide / Accidental / etc. |
| **Category** | See categories below |

## Assessment: SUSPICION LEVEL

2-3 sentence summary of why this death is or isn't suspicious. State the strongest evidence.

## Circumstances of Death

Narrative of what happened. Where found, when, by whom. What was unusual.

## Background

Who this person was. Their connection to Epstein or the broader network. Career, role, relationships.

## Why This Death Possibly Raises Questions

- Bullet points of each suspicious element
- Timing coincidences
- Missing evidence
- Contradictions in official story
- Warnings the person gave before dying

## Key Quotes from Media Coverage

> Blockquoted quotes with attribution and source links

## See Also

- Links to related profiles in this project (use relative paths like [Name](Name.md))

## Sources

- Sourced links, one per line
- Prefer: BBC, NPR, CNN, NBC, court documents, Wikipedia, specialty outlets
- Include at least 3-5 sources per profile

*This information was built by Grok and Claude AI research.*
```

### Step 3: Profile Structure (Living / Missing / At-Risk / Suppressed Persons)

* Same structure but replace death fields with:
  * `**Status**` — ALIVE, Missing, Under investigation, Arrested, Threatened, Work Seized, Suppressed, etc.
  * `**Current Location**` — Where they are now
* Replace "Circumstances of Death" with "Current Situation" or "Suppression Timeline"
* Replace "Why This Death Raises Questions" with "Why This Person Matters" or "Safety Concerns" or "Evidence of Suppression"
* For energy inventors/researchers, include:
  * What technology they were working on
  * What stage it was at (concept, prototype, demonstrated, commercializing)
  * Who allegedly suppressed them (government agency, corporation, unknown actors)
  * What happened to their work/devices after suppression

### Step 4: Add a Row to README.md

* Deceased go in the main deaths table, sorted roughly by suspicion level (highest first)
* Living/missing/at-risk go in the "Living Persons at Risk" table
* Row format: `| [Name](Details/Filename.md) | Cause of Death | **SUSPICION LEVEL** | One-line summary. |`

### Step 5: Update Patterns if Applicable

* Check if the person fits any existing pattern in the "Patterns Worth Noting" section of README.md
* Add them to relevant pattern lists (e.g., hangings, banking deaths, balcony falls)
* If they reveal a new pattern, add a new pattern section

## Person Categories

### Epstein / Elite Crime Categories
* Co-conspirator — Directly involved in Epstein's operation
* Witness / Primary Accuser — Testified or provided evidence
* Victim — Trafficked or abused person
* Journalist / Investigator — Researched or reported on the network
* Law Enforcement — Police, FBI, prosecutors
* Banking / Finance — Handled Epstein's money
* Legal — Lawyers, judges, attorneys general
* Political Figure — Politicians, diplomats, government officials
* Intelligence — CIA, Mossad, MI6 connections
* Modeling Industry — Models, agents, scouts
* Celebrity / Public Figure — Famous people with tangential connections
* Whistleblower — Provided inside information to authorities or media
* Silenced Witness / Disappeared — Spoke out and vanished
* Staff / Employee — Worked for Epstein directly

### Advanced Energy Categories
* Energy Inventor — Developed a non-traditional energy device or technology
* Energy Researcher — Conducted research into advanced energy (academic or independent)
* Energy Whistleblower — Exposed suppression of energy technology
* Energy Business — Attempted to commercialize or patent advanced energy technology
* Energy Supporter / Funder — Financially backed or publicly supported advanced energy work

## Writing Style and Defamation Prevention

* Lead with facts, not speculation
* State what is verified vs. what is alleged or unverified
* **Use "allegedly," "reportedly," "according to" for all unconfirmed claims** — this is critical for defamation prevention
* **Attribute claims to their source** — "According to [book/article/testimony]..." not stated as fact
* **Tiers of evidence (use appropriate framing for each):**
  * Court findings and convictions — can state as fact
  * Sworn testimony — "testified under oath that..."
  * Major outlet journalism — "reported by [outlet]..."
  * Books and documentaries — "claimed in [title] by [author]..."
  * Unverified online accounts — "unverified claims circulated that..."
* **Include denials** — if a person or organization has denied allegations, include the denial
* **For living persons and active organizations:** Extra caution; note legitimate roles before allegations
* Include the person's own words when available (quotes from interviews, tweets, court filings)
* Include family members' statements when they dispute official rulings
* Note when evidence was destroyed, sealed, or went missing
* Always include the "See Also" section linking to related profiles — this creates the web of connections
* Cross-link to group files in `other/groups/` when a person is connected to a documented group
* End every profile with `*This information was built by Grok and Claude AI research.*`

## Key Patterns to Watch For

### Epstein / Elite Crime Patterns
* Hangings in custody (Epstein, Brunel, Middleton, etc.)
* Deaths before testimony or trial
* Banking executives who handled Epstein's money
* Balcony/building falls
* Investigators or journalists who died while researching trafficking
* People who publicly said "if I die, it wasn't suicide" and then died
* Cluster deaths in the same time period
* Geographic clusters (Florida, NYC, Caribbean, Columbus OH, Europe)
* Intelligence service connections (Mossad, CIA, PROMIS software)
* Modeling industry pipeline victims
* Sealed records or destroyed evidence after death

### Advanced Energy Suppression Patterns
* Inventors who died shortly after demonstrating a working device
* Patents placed under secrecy orders by government agencies
* Labs raided or devices confiscated by government or unknown parties
* Inventors threatened then died in "accidents" or "suicides"
* Working prototypes that disappeared after the inventor's death
* University researchers whose funding was suddenly cut
* Inventors offered buyouts, then killed or suppressed when they refused
* Government classification of energy research under national security
* Smear campaigns labeling inventors as frauds before investigation
* Multiple inventors in the same field dying in a short time period
* Cars or engines achieving extreme efficiency, then inventor dies or device vanishes

## Groups Directory (`other/groups/`)

The `other/groups/` directory contains one markdown file per organization, intelligence service, blackmail operation, or trafficking ring. These files document the **group itself** — its history, scope, methods, and connections — and cross-link to individual people in `Details/`.

### What Qualifies as a Group

* **Intelligence services** — Any agency allegedly involved in blackmail, trafficking, Compromat, or cover-ups (e.g., Mossad, CIA, MI6)
* **Epstein's operation** — The core trafficking/blackmail network itself
* **Prostitution / madam operations** — Especially those that:
  * Allegedly supplied elites, politicians, or intelligence services
  * Involved minors
  * Had madams who received surprisingly light consequences
  * Had books written claiming intel or blackmail connections
  * Operated in or around Washington, DC (highest priority)
* **Financial institutions** — Banks that moved Epstein's money or laundered trafficking proceeds
* **Modeling agencies** — Agencies used as trafficking pipelines
* **Government entities** — USVI government, DOJ units, etc. that allegedly protected the network
* **Media / suppression operations** — Organizations that allegedly buried or destroyed evidence
* **Other blackmail / Compromat rings** — Franklin scandal, PROMIS/Octopus, Dutroux network, etc.

### DC-Area Operations (High Priority)

* Washington, DC madams and escort operations are especially important
* Any operation where politicians or intelligence figures were clients
* Operations where the madam died suspiciously, received minimal sentencing, or evidence was sealed
* Cases where books, documentaries, or investigative journalism alleged intel/blackmail connections

### Group File Template

```
[< Back to Main List](../../README.md) | [Groups Index](README.md)

# Group / Organization Name
One-line summary of what this group is and why it matters.

| Field | Details |
|-------|---------|
| **Type** | Intelligence Service / Blackmail Operation / Trafficking Ring / Financial Institution / etc. |
| **Active Period** | Years of operation |
| **Location(s)** | Where they operated |
| **Status** | Active / Disbanded / Under investigation / etc. |
| **Alleged Connection** | How this group connects to Epstein or the broader network |

## Overview

What this group is. What it allegedly did. How it connects to elite blackmail, trafficking, or intelligence operations.

## Alleged Activities

* Bullet points of what the group allegedly did
* Use "allegedly," "reportedly," "according to [source]" throughout
* Distinguish verified facts from claims made in books, documentaries, or testimony

## Key Figures

* [Person Name](../../Details/Person_Name.md) — Role in the group (link to Details/ profile if one exists)
* Person Name — Role (no link if they don't have a Details/ profile yet)

## Connection to Epstein Network

How this group connects to the broader Epstein/elite blackmail ecosystem. Shared personnel, methods, geography, or financial flows.

## Notable Books, Documentaries, and Investigations

* Book/film title — Author — Year — Key claims made
* Use these as sources but note they are claims, not proven facts

## Why This Group Matters

* What pattern it reveals
* What it tells us about the broader system

## Sources

* Sourced links, one per line
* Court documents, news reports, books, documentaries
* At least 3-5 sources per group file

*This information was built by Grok and Claude AI research.*
```

### Group File Naming

* Filename: `other/groups/short_name.md` (lowercase, underscores, no spaces)
* Examples: `jeffrey_epstein_network.md`, `mossad.md`, `cia.md`, `dc_madam.md`, `franklin_scandal.md`, `elite_model_management.md`, `deutsche_bank.md`

### Groups Index File

* `other/groups/README.md` — A master list of all group files, organized by type
* Each row links to the group file and gives a one-line description

### Cross-Linking Between Groups and People

* **Group files link to people:** In the "Key Figures" section, link to `../../Details/Person_Name.md`
* **Person files link back to groups:** In the person's "Background" or "See Also" section, link to `../../other/groups/group_name.md`
* This creates a two-way web: readers can go from a person to the groups they were part of, or from a group to all the people involved

### Defamation Prevention

* **Use "allegedly" and "reportedly" liberally** — especially for living persons and active organizations
* **Attribute claims to their source** — "According to [book/article/testimony]..." rather than stating as fact
* **Distinguish tiers of evidence:**
  * Court findings and convictions — can state as fact
  * Sworn testimony and depositions — "testified under oath that..."
  * Investigative journalism from major outlets — "reported by [outlet]..."
  * Books and documentaries — "claimed in [title] by [author]..."
  * Unverified online accounts — "unverified claims circulated that..."
* **For currently operating companies:** Note their current legitimate operations before discussing allegations
* **For intelligence services:** Frame as "alleged" unless confirmed by declassified documents or official inquiries
* **Never present speculation as fact** — if the connection is circumstantial, say so explicitly
* **Include denials** — if the group or person has denied allegations, include that denial

### What to Research for Each Group

* Use web search to gather information on:
  * The group's history and leadership
  * Court cases, indictments, convictions
  * Books and documentaries that investigated them
  * Connections to known Epstein-linked individuals
  * Deaths of people connected to the group
  * Evidence of intelligence service involvement
  * Evidence of blackmail or Compromat operations
  * Political protection or surprisingly light consequences

## Data Files (in other/)

* YAML databases: `epstein_deaths.yaml`, `epstein_deaths_comprehensive.yaml`, etc.
* CSV files: `person_types.csv`, `person_categories.csv`, `locations.csv`
* Research notes: `findings_*.txt`, `detailed_*.txt`
* Weiner laptop overview: `other/laptop.md`
* Groups directory: `other/groups/` — organization and operation profiles
