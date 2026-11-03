# The Lightless Beacon — Adventure Trace V2.0

**Version:** 2.0  
**Status:** PILOT — structural baseline  
**System:** Call of Cthulhu 7th Edition (Quick-Start Rules)  
**Adventure source:** *The Lightless Beacon*, Leigh Carr with Lynne Hardy, Chaosium, 2019  
**Scenario date:** 12 April 1926  
**Location:** Beacon Island, near Rockport, Massachusetts  
**Player Investigator:** Bureau Agent  
**Design model:** Fishbone Adventure Trace  
**Source authority:** Original adventure PDF. This Trace is an operational index and does not replace the source adventure.

---

## 1. Source and classification conventions

Every content element is classified as:

- **CANON** — directly supported by the original adventure.
- **DERIVED** — an operational objective, dependency, grouping, or interpretation constructed from source material.
- **UNSPECIFIED** — the source does not define the detail sufficiently. Runtime must not silently treat an assumption as canon.

The original PDF remains authoritative for scene descriptions, NPCs, clues, events, creature information, and source-defined mechanics. The Call of Cthulhu 7th Edition Quick-Start Rules remain the rules authority. Do not silently import rules from the full Keeper Rulebook where the Quick-Start source does not provide them.

### Runtime adjudication boundary

The Skill Check Register records checks and information gates described by the adventure. It does not require simulated dice, random numbers, probability calculations, or deterministic conversion tables. Runtime adjudicates consequential actions using character capability, current challenge, and the player's approach, under the project's GM Operating Protocol.

No check is required for a routine action or an obvious discovery. A failed attempt does not by itself make a clue impossible. Alternative approaches remain available where plausible.

---

## 2. Adventure overview

### 2.1 Premise — CANON

At approximately 8:15 PM on 12 April 1926, the SS Essex County, carrying passengers and cargo toward Rockport, wrecks after the Beacon Island lighthouse ceases to shine. The investigators reach Beacon Island by rowboat shortly before a storm.

The island's lighthouse and cottage show signs of recent violence. The investigators can explore the grounds and buildings, discover evidence of a previous confrontation, encounter amphibious creatures, survive an assault, and seek rescue or escape.

### 2.2 Keeper-only background — CANON

**GM ONLY. Do not reveal until supported by in-world discovery.**

The SS Essex County was carrying gold associated with the cultists of Dagon and bound for Innsmouth. A lighthouse malfunction caused the beacon to fail during a storm, contributing directly to the ship's wreck.

George Cassidy, a lighthouse keeper, found coins washed ashore and collected them. His inquiries into their value attracted the attention of the cultists, who arranged an operation to recover the missing coins.

Two Deep One hybrids were involved. One remained at Folly Point; the other led Younglings onto Beacon Island. Samuel Smith was captured, interrogated, and murdered. Michael Turner, secretly Bureau of Investigation agent Warren Thomas, was killed by Younglings. Cassidy fought the attackers in the lantern room, killing two Younglings and one hybrid before dying. A stray bullet damaged the lighthouse lens and bulb. The remaining Younglings searched the island for the coins.

### 2.3 Player Investigator — CANON / CONFIGURATION

The solo option recommends the Bureau Agent, with Appraise and Pilot (Boat) increased to 50%. The selected Investigator is the Bureau Agent.

Do not confuse:
- **Player Investigator:** the Bureau Agent.
- **NPC:** Warren Thomas, undercover as lighthouse keeper Michael Turner.

The Bureau Agent is travelling to receive a briefing from colleague Warren Thomas. Thomas's notebook is hidden in Turner's mattress.

### 2.4 Tone and pacing — CANON / DERIVED

Investigative horror, isolation, marine horror, and survival. The adventure is designed as a short scenario, approximately one hour, but exploration, split parties, or extended confrontation may lengthen it.

---

## 3. Backbone — CORE objectives

### Status model

CORE status values are exactly:

- `HIDDEN`
- `AVAILABLE`
- `COMPLETED`
- `IMPOSSIBLE`

A CORE is initially `AVAILABLE` when it has no required predecessor CORE. A CORE with required predecessor COREs remains `HIDDEN` until all required predecessors are `COMPLETED`.

A CORE becomes `COMPLETED` when all its required Branches are `COMPLETED`, all its direct required Clues are `DISCOVERED`, and all its direct operational requirements are satisfied.

A CORE becomes `IMPOSSIBLE` when it is not already `COMPLETED` and at least one mandatory dependency or requirement has become permanently unreachable. A failed check alone does not establish impossibility.

**Historical precedence:** `COMPLETED` is permanent. Never change a completed CORE to `IMPOSSIBLE`.

All four COREs below are initial and independent. No CORE is a prerequisite of another.

### CORE-001 — Ricostruire il destino di Warren Thomas

- **Classification:** DERIVED objective based on CANON characters and evidence.
- **Initial status:** AVAILABLE.
- **Required predecessor COREs:** none.
- **Required Branches:** BR-001A.
- **Direct required Clues:** none.
- **Direct operational requirements:** none.
- **Completion condition:** BR-001A is COMPLETED: the corpse is identified as Warren Thomas and the essential circumstances of his death are established from the available evidence.
- **Optional content:** BR-001B, recovery and examination of Thomas's notebook, is not required for CORE completion.
- **Source:** PDF pp. 8, 11–12, 18.

**Keeper interpretation:** The badge reveals Thomas's real name. First Aid or Medicine can reveal details about injuries and timing. Do not require the notebook to identify Thomas or establish that he is dead.

### CORE-002 — Ricostruire la verità sul naufragio e sull'oro

- **Classification:** DERIVED objective based on CANON investigative material.
- **Initial status:** AVAILABLE.
- **Required predecessor COREs:** none.
- **Required Branches:** BR-002A AND BR-002B AND BR-002C.
- **Direct required Clues:** none.
- **Direct operational requirements:** none.
- **Completion condition:** all three required Branches are COMPLETED. The Investigator has established the essential relationship between the gold coins and Innsmouth/the cult of Dagon, Cassidy's involvement and the recovery operation, and the lighthouse failure's causal role in the shipwreck.
- **Optional content:** BR-002D, recovering Cassidy's purse of gold, is not required.
- **Source:** PDF pp. 8–10, 13–15, 18–20.

**Evidence standard:** Finding the maintenance log is not by itself equivalent to understanding its significance. The causal connection between the lighthouse going dark and the wreck must be reasonably established through cumulative evidence. The player need not recite a prescribed sentence if the evidence supports the conclusion.

### CORE-003 — Sopravvivere alla minaccia anfibia

- **Classification:** DERIVED objective based on CANON assault and survival outcomes.
- **Initial status:** AVAILABLE.
- **Required predecessor COREs:** none.
- **Required Branches:** BR-003A.
- **Direct required Clues:** none.
- **Direct operational requirements:** none.
- **Completion condition:** BR-003A is COMPLETED when at least one of its alternative survival paths is achieved.
- **Source:** PDF pp. 20–22.

**Important:** Combat is not mandatory. A successful early evacuation can satisfy the survival objective. Surviving until the Younglings withdraw, neutralizing the attacking force sufficiently to end the immediate assault, or escaping the island safely are alternative ways to establish survival.

### CORE-004 — Ottenere la salvezza e lasciare Beacon Island

- **Classification:** DERIVED objective based on CANON possible conclusions.
- **Initial status:** AVAILABLE.
- **Required predecessor COREs:** none.
- **Required Branches:** BR-004A.
- **Direct required Clues:** none.
- **Direct operational requirements:** none.
- **Completion condition:** BR-004A is COMPLETED when the Investigator is actually rescued or reaches a safe location off the island.
- **Source:** PDF pp. 12, 18–22.

**Important:** Repairing the radio or transmitting an SOS does not by itself complete this CORE. The rescue must occur. A boat departure does not count as safe evacuation until the Investigator has reached a safe destination.

---

## 4. Branches

### Branch status model

Branch status values are exactly:

- `HIDDEN`
- `AVAILABLE`
- `COMPLETED`
- `IMPOSSIBLE`

A Branch becomes `AVAILABLE` when its Anchor CORE becomes `AVAILABLE`. Once `AVAILABLE`, it remains `AVAILABLE` until it becomes `COMPLETED` or `IMPOSSIBLE), even if its Anchor CORE later becomes `COMPLETED`.

Concrete in-world access conditions still apply. Availability does not mean the Investigator has found the location or can bypass physical obstacles.

A Branch becomes `COMPLETED` only when all its required Clues are discovered and all its operational requirements are satisfied. If a Branch contains an Operational Requirement with alternative paths, any one viable path can satisfy that requirement. Different declared requirements remain AND.

A Branch becomes `IMPOSSIBLE` only when at least one mandatory requirement is permanently unreachable, or all alternative paths for a mandatory requirement are impossible. A failed attempt alone does not make a Branch impossible.

### CORE-001 Branches

#### BR-001A — Identificare Thomas e ricostruirne la morte

- **Anchor CORE:** CORE-001.
- **Classification:** DERIVED.
- **Required Clues:** CL-001 AND CL-002.
- **Operational requirements:** none.
- **Completion:** the body is located and identified as Warren Thomas; available evidence about the fatal injuries is examined sufficiently to establish his fate.
- **Acquisition:** follow the boot prints toward the thicket; examine the corpse and badge. First Aid or Medicine can provide additional injury and timing information.
- **Source:** PDF pp. 11–12.

#### BR-001B — Recuperare gli appunti di Thomas

- **Anchor CORE:** CORE-001.
- **Classification:** CANON opportunity; optional Branch.
- **Required Clues:** CL-003.
- **Operational requirements:** none.
- **Completion:** locate and recover Thomas's pocket notebook from the mattress.
- **Acquisition:** search Turner's bunkroom mattress; Spot Hidden is specified. The Bureau Agent receives a bonus die in the source rules.
- **Optional:** not required for CORE-001.
- **Source:** PDF p. 18.

### CORE-002 Branches

#### BR-002A — Ricostruire la provenienza delle monete

- **Anchor CORE:** CORE-002.
- **Classification:** DERIVED from CANON coin evidence.
- **Required Clues:** CL-004 AND CL-005 AND CL-006.
- **Operational requirements:** none.
- **Completion:** establish that the coins are gold, recognize their unusual religious symbolism, and identify the aquatic theme.
- **Acquisition:** inspect the three gold coins in the hallway. Appraise identifies solid gold; Occult identifies the sigils as meaningful and similar to those used by remote religious tribes; relevant Art/Craft or Natural World identifies the aquatic theme.
- **Check relationship:** the PDF explicitly allows the Appraise, Occult, Art/Craft, and Natural World checks to be combined. Each successful skill yields its associated information. A different Investigator with the relevant skill may try an information component another Investigator failed.
- **Source:** PDF p. 13.

#### BR-002B — Ricostruire il coinvolgimento di Cassidy e l'operazione di recupero

- **Anchor CORE:** CORE-002.
- **Classification:** DERIVED from CANON documents.
- **Required Clues:** CL-007 AND CL-008.
- **Operational requirements:** none.
- **Completion:** establish Cassidy's inquiries into the coins and the attempt to identify/value them, and connect his collection to the operation to recover the missing coins.
- **Acquisition:** examine the appraisals, letters and Cassidy's journal in the locked desk drawer. Library Use reveals the letters' chronology. The journal is opened with Locksmith, or STR using a kitchen knife, screwdriver or chisel as described by the source.
- **Source:** PDF pp. 14–15.

#### BR-002C — Ricostruire il guasto del faro e il suo legame con il naufragio

- **Anchor CORE:** CORE-002.
- **Classification:** DERIVED from CANON maintenance and lantern evidence.
- **Required Clues:** CL-009 AND CL-010.
- **Operational requirements:** none.
- **Completion:** establish the February 12 lighthouse lamp failure and connect the loss of the beacon to the SS Essex County wreck.
- **Acquisition:** examine the service log; Mechanical Repair or Electrical Repair identifies the exceptional entry. In the lantern room, Spot Hidden can reveal the bullet hole in the lens and the damage to the bulb. Cumulative evidence supports the causal conclusion.
- **Source:** PDF pp. 18–20.

#### BR-002D — Recuperare il tesoro di Cassidy

- **Anchor CORE:** CORE-002.
- **Classification:** CANON optional opportunity.
- **Required Clues:** none.
- **Operational requirements:** OR-002D-A: gain access to Cassidy's body and physically recover the purse of gold coins.
- **Completion:** Cassidy's purse is recovered.
- **Optional:** not required for CORE-002.
- **Source:** PDF pp. 20, 22.

### CORE-003 Branch

#### BR-003A — Superare la minaccia anfibia

- **Anchor CORE:** CORE-003.
- **Classification:** DERIVED from CANON assault and conclusion.
- **Required Clues:** none. Clues CL-011 through CL-015 are optional tactical/investigative information and are not completion prerequisites.
- **Operational requirements:** OR-003A — achieve at least one of the following alternative paths:
  - **Path A — Survive the assault:** remain alive until the Younglings' assault ends, the attackers withdraw, or the immediate attacking force is neutralized sufficiently that the Investigator is no longer under immediate attack.
  - **Path B — Escape the immediate attack:** successfully evade or break away from the attacking Younglings and reach a position where the immediate assault no longer threatens the Investigator.
  - **Path C — Evacuate safely before the assault:** leave Beacon Island and reach safety before the attack can reach the Investigator.
- **Completion:** any one path is achieved.
- **Source:** PDF pp. 20–22.

**Trigger:** The Keeper may trigger the attack after the investigators have explored the lighthouse/cottage or after they have explored the island and found Turner's body. Timing is intentionally flexible. Do not trigger the attack mechanically merely because the Branch is AVAILABLE.

### CORE-004 Branch

#### BR-004A — Raggiungere una condizione di salvezza

- **Anchor CORE:** CORE-004.
- **Classification:** DERIVED from CANON rescue and escape possibilities.
- **Required Clues:** none.
- **Operational requirements:** OR-004A — achieve at least one of the following alternative paths:
  - **Path A — Coastguard rescue:** repair the radio, transmit a distress call, and subsequently be physically rescued by the Coastguard.
  - **Path B — Escape by boat:** obtain access to a usable boat, successfully depart Beacon Island, and reach a safe location off the island.
- **Completion:** actual rescue or safe arrival off the island. An SOS transmission, a prepared boat, or departure without established safety is insufficient.
- **Source:** PDF pp. 12, 18–22.

---

## 5. Clue Register

### Clue status model

Clue status values are exactly:

- `UNDISCOVERED`
- `DISCOVERED`
- `IMPOSSIBLE`

Clues become available when their owning CORE becomes `AVAILABLE`. This is a gating rule only; it does not reveal the clue or guarantee in-world access.

A Clue becomes `DISCOVERED` when its acquisition condition is satisfied through one or more valid Skill Checks or another source-supported approach. A failed attempt alone does not make a Clue impossible. If multiple acquisition methods exist, all must become permanently unreachable before the Clue can become `IMPOSSIBLE`.

There is no `UNDERSTOOD` clue status. Understanding is evaluated by the Keeper from the cumulative evidence when evaluating CORE completion.

### CORE-001 Clues

| ID | Clue | Information | Acquisition | Related Branch | Source |
|---|---|---|---|---|---|
| CL-001 | Il corpo nel bosco | The body is Michael Turner, recently killed and badly mauled. | Follow boot prints from the cottage into the thicket; examine the corpse. | BR-001A | p. 11 |
| CL-002 | Distintivo del Bureau | The dead man's real name is Warren Thomas; he was a Bureau of Investigation agent. | Search the corpse and find the badge. The Bureau Agent can confirm the identity. | BR-001A | pp. 11–12 |
| CL-003 | Quaderno nel materasso | Thomas left a pocket-sized notebook hidden in the mattress. | Spot Hidden while searching the bunkroom mattress; Bureau Agent receives source-defined bonus die. | BR-001B | p. 18 |

### CORE-002 Clues

| ID | Clue | Information | Acquisition | Related Branch | Source |
|---|---|---|---|---|---|
| CL-004 | Monete d'oro | The coins are made of solid gold. | Appraise the three coins in the hallway. | BR-002A | p. 13 |
| CL-005 | Simboli sulle monete | The sigils have a deeper meaning and resemble symbols used by remote religious tribes. | Occult examination of the coins. | BR-002A | p. 13 |
| CL-006 | Tema acquatico | The coin designs have an underlying aquatic theme. | Relevant Art/Craft or Natural World examination. | BR-002A | p. 13 |
| CL-007 | Corrispondenza e valutazioni | Cassidy sought appraisals and contacted antique stores, librarians and universities; the letters are dated from March 8 to April 2, 1926. | Examine the desk documents; Library Use establishes the chronological order. | BR-002B | pp. 14–15 |
| CL-008 | Diario di Cassidy | Cassidy's journal contains his own account and ends abruptly, suggesting interruption. The journal's cover bears the obelisk symbol. | Open the locked desk drawer and read the journal. | BR-002B | p. 15; Handout 2 |
| CL-009 | Registro del faro | On February 12, 1926, wiring problems caused the lamp bulb to burn out; the storm and electrical short delayed repairs, leaving the lighthouse dark for hours. | Mechanical Repair or Electrical Repair examination of the service log. | BR-002C | p. 18 |
| CL-010 | Danno alla lente e alla lampadina | A bullet hole in the lens and damage to the bulb explain why the beacon stopped working at approximately 8 PM on April 12. | Spot Hidden in the lantern room; inspect the lens and broken panes. | BR-002C | p. 20 |

### Optional/supporting clues

These Clues may help the Investigator understand the threat or the island but are not mandatory for CORE completion unless a Branch explicitly lists them.

| ID | Clue | Information | Acquisition | Related Branch | Source |
|---|---|---|---|---|---|
| CL-011 | Impronte anomale | Small footprints resemble duck-like tracks; a Hard success suggests an unidentified species. | Spot Hidden to notice; Natural World or Science (Biology/Zoology) to interpret. | BR-003A support | p. 11 |
| CL-012 | Aghi nel corpo di Turner | Small needles are embedded in Turner's skin and may be animal spines, probably poisonous. | First Aid or Medicine reveals needles at Extreme success; Hard Natural World or Science interprets them. | BR-003A support | p. 11 |
| CL-013 | Dipinto della figura alla finestra | The shadow has bulbous, laterally placed eyes resembling fish or frog anatomy. | Examine painting; Natural World or Science interprets anatomy. | BR-003A support | p. 13 |
| CL-014 | Creature nella lanterna | The creatures are amphibious, fishlike, mobile on land and in water, and not a known recorded species. | Examine corpses; Natural World or Science (Biology/Zoology). Marine Biologist recognizes them without a roll per source. | BR-003A support | p. 19 |
| CL-015 | Aghi e armatura dei younglings | Their exterior provides natural armor; dorsal needles are projectile weapons; Extreme success suggests self-produced poison. | Natural World or Science (Biology/Zoology) examination, with Regular/Hard/Extreme information levels. | BR-003A support | pp. 19–20 |
| CL-016 | Proiettili nel corridoio | Two bullets were fired from a position a few steps up the stairwell. | Spot Hidden notices bullets; Firearms (Handgun) or INT interprets direction. | Context support | p. 13 |
| CL-017 | Sangue e scontro in cucina | Blood is recent; higher successes may suggest it is not human. | First Aid or Medicine; INT can suggest the chair was used as a weapon. | Context support | p. 18 |
| CL-018 | Lanterna e barca a Folly Point | A light is visible; a yellow rowboat is at the mainland pier; at Extreme success the boats appear identical. | Spot Hidden using the study binoculars, with Regular/Hard/Extreme information levels. | BR-004A support | pp. 12–13 |

**Important:** The source's Handout 3 is associated with the bunkroom notebook. Its full text must be consulted in the original PDF when interpreting the notebook. Do not invent notebook contents beyond the handout.

---

## 6. Skill Check Register

The entries below preserve checks explicitly described in the adventure. They are not all Clue acquisition checks. Some are operational, environmental, combat, Sanity, or conditional checks.

| ID | Context | Skill / check | Result / information | Source |
|---|---|---|---|---|
| CHECK-001 | Free rowboat from wreck | Pilot (Boat) | Free the rowboat without crashing into rocks; source describes consequences of fumble or failed pushed roll. | p. 10 |
| CHECK-002 | Inspect submerged wreckage | Combined Know + Spot Hidden | Know: metal may be part of a ship; Spot Hidden: no identifying marks and little deterioration; both yield both pieces. | p. 10 |
| CHECK-003 | Find footprints by cottage | Spot Hidden | Notice small animal-like and boot prints. | p. 11 |
| CHECK-004 | Interpret footprints | Natural World or Science (Biology/Zoology) | Duck-like; Hard success suggests an unidentified species. | p. 11 |
| CHECK-005 | Follow tracks | Track | Determine direction and relationship between boot and animal-like tracks. | p. 11 |
| CHECK-006 | Repair generator shed roof | Relevant Art/Craft (e.g. Carpentry) OR Hard Mechanical Repair | Repair leak using materials in workshop. | p. 11 |
| CHECK-007 | Examine Turner's corpse | First Aid or Medicine | Regular: animal-like teeth/claw wounds; Hard: died within last hour; Extreme: needles embedded in skin. | p. 11 |
| CHECK-008 | Interpret needles in Turner | Hard Natural World or Science (Biology/Zoology) | Needles appear to be animal spines and probably poisonous. | p. 11 |
| CHECK-009 | Notice Folly Point light | Spot Hidden with binoculars | Regular: notice small light; Hard: identify second yellow rowboat; Extreme: boats appear identical. | p. 12 |
| CHECK-010 | Appraise coins | Appraise | Identify solid gold. | p. 13 |
| CHECK-011 | Interpret coin sigils | Occult | Recognize meaningful symbols similar to those used by remote religious tribes. | p. 13 |
| CHECK-012 | Identify coin theme | Relevant Art/Craft OR Natural World | Identify aquatic theme. | p. 13 |
| CHECK-013 | Combine coin analysis | Combined use of Appraise, Occult, Art/Craft, Natural World | Each successful skill yields its associated information; different Investigators may try failed components if qualified. | p. 14 |
| CHECK-014 | Infer chair disturbance | INT | Suggests the occupant stood quickly and knocked the chair over. | p. 13 |
| CHECK-015 | Notice bullets in hallway | Spot Hidden | Regular if hallway is lit; Extreme if not lit. | p. 13 |
| CHECK-016 | Interpret hallway bullets | Firearms (Handgun) or INT | Determine shots came from a position a few steps up the stairwell. | p. 13 |
| CHECK-017 | Identify coin appraisal context | Appraise | Recognize some antique stores overvalued/undervalued Cassidy's coins relative to fair price. | p. 14 |
| CHECK-018 | Reconstruct letter chronology | Library Use | Establish letters are largely chronological, March 8 through April 2, 1926. | p. 14 |
| CHECK-019 | Open locked desk drawer | Locksmith OR STR with kitchen knife, screwdriver or chisel | Gain access to Cassidy's journal. | p. 15 |
| CHECK-020 | Interpret painting figure | Natural World or Science (Biology/Zoology) | Recognize fish/frog-like eye placement. | p. 13 |
| CHECK-021 | Assess painting execution | Relevant Art/Craft (e.g. Painting/Sketching) | Identify that painting was executed in a hurry. | p. 13 |
| CHECK-022 | Assess kitchen chair/blood | INT; First Aid or Medicine | Chair may have been used as weapon; blood is recent; higher success may suggest non-human origin. | p. 18 |
| CHECK-023 | Find Thomas's notebook | Spot Hidden | Locate notebook in mattress; Bureau Agent receives bonus die under source rules. | p. 18 |
| CHECK-024 | Examine service log | Mechanical Repair or Electrical Repair | Identify exceptional February 12, 1926 entry and lighthouse blackout. | p. 18 |
| CHECK-025 | Repair radio | Electrical Repair | Restore radio and transmit a distress call. Source: fumble or failed pushed roll renders radio permanently inoperable. | pp. 18–19 |
| CHECK-026 | Examine strange human corpse in lantern room | First Aid or Medicine | Confirm two gunshot wounds caused death. | p. 19 |
| CHECK-027 | Identify amphibious creatures | Natural World or Science (Biology/Zoology) | Recognize unknown fishlike amphibious species; Marine Biologist needs no roll per source. | p. 19 |
| CHECK-028 | Examine creature armor and wounds | Natural World or Science (Biology/Zoology), Regular | Bullets killed creatures only when entering soft vulnerable areas; rest of exterior is tough natural armor. | p. 20 |
| CHECK-029 | Examine dorsal fins | Natural World or Science (Biology/Zoology), Hard | Identify slimy needles and likely projectile use. | p. 20 |
| CHECK-030 | Identify poison | Natural World or Science (Biology/Zoology), Extreme | Suggest self-produced poison; exact nature requires laboratory testing. | p. 20 |
| CHECK-031 | Find bullet hole in lens | Spot Hidden | Identify bullet hole and reconstruct damage to bulb and panes. | p. 20 |
| CHECK-032 | Assess temporary bulb repair | Mechanical Repair | At least 20% to know lens prevents full restoration; temporary bulb replacement takes at least 40 minutes and a successful Mechanical Repair roll. | p. 20 |
| CHECK-033 | Detect Younglings in woods | Combined Listen + Spot Hidden | Alert investigators to movement and approaching creatures. | p. 20 |
| CHECK-034 | Witness Younglings | Sanity | Sanity loss 1/1D4. | p. 20 |
| CHECK-035 | Reach cottage during pursuit | Opposed DEX or chase procedure | Success reaches relative safety; failure may result in being caught. Full chase rules are referenced externally. | pp. 20–21 |
| CHECK-036 | Break free after being caught | Fighting (Brawl) maneuver | Attempt to break away from a Youngling. | p. 21 |
| CHECK-037 | Hear Younglings inside cottage | Listen | Needed if the front door was closed and investigators were not otherwise alerted. | p. 21 |
| CHECK-038 | Generator short-circuit risk | Group Luck roll, Keeper option | If roof not repaired, intensified rain may short out generator. | p. 21 |
| CHECK-039 | Avoid projectile needle | Dodge opposed by Youngling attack | Unexpected projectile imposes penalty die per source. | p. 22 |
| CHECK-040 | Resist needle poison | Extreme CON | Avoid poison effects after being hit. | p. 22 |
| CHECK-041 | Remove latched Youngling | Hard STR | Remove creature from victim. | p. 22 |

### Skill Check interpretation

- Preserve source-defined Regular, Hard, and Extreme distinctions as information tiers where the adventure specifies them.
- Where the source explicitly offers alternatives, record them as OR.
- Where the source explicitly combines checks, record combined outcomes as described.
- Do not invent a skill check for reading or interpreting the contents of Cassidy's journal or Thomas's notebook.
- Do not convert checks into probability formulas or simulated dice in Runtime.
- The source references full chase rules from the Keeper Rulebook. Those rules are outside the Quick-Start source set and must not be silently imported.

---

## 7. Operational requirements

Operational requirements describe verifiable outcomes, not knowledge. They belong to Branches or COREs, not to the Clue Register.

### OR-002D-A — Recover Cassidy's purse

- **Owner:** BR-002D.
- **Paths:** access Cassidy's body in the lantern room and physically retrieve the purse.
- **Completion:** purse recovered.
- **Source:** PDF p. 20.

### OR-003A — Survive or escape the immediate assault

- **Owner:** BR-003A.
- **Logic:** OR across Path A, Path B, Path C defined in BR-003A.
- **Completion:** any one path achieves a safe outcome from the amphibious threat.
- **Impossibility:** this requirement is IMPOSSIBLE only when every path has become permanently unreachable. If the Investigator has safely evacuated, the requirement is COMPLETED, not IMPOSSIBLE.
- **Source:** PDF pp. 20–22; the early-evacuation path is a DERIVED operational formulation of the source's escape option.

### OR-004A — Reach safety off Beacon Island

- **Owner:** BR-004A.
- **Logic:** OR across Coastguard rescue and safe boat escape.
- **Completion:** actual rescue or safe arrival at a location off the island.
- **Impossibility:** only when all rescue/escape paths are permanently unreachable. Radio failure alone does not make the requirement impossible if a boat escape remains viable.
- **Source:** PDF pp. 12, 18–22.

---

## 8. Outcomes

Outcomes record significant end states. They are not additional CORE objectives and do not replace the CORE/Branch/Clue state model.

| ID | Outcome | Description | Source |
|---|---|---|---|
| OUT-001 | Investigator death | One or all Investigators die during the assault. | pp. 20–22 |
| OUT-002 | Survive until assault ends | Younglings withdraw, are sufficiently neutralized, or stop attacking. | p. 21 |
| OUT-003 | Coastguard rescue | Coastguard arrives following a distress call and rescues the Investigator. | pp. 18–19, 21 |
| OUT-004 | Escape by boat | Investigator leaves Beacon Island by the south pier boat, if conditions permit. | pp. 12, 20 |
| OUT-005 | Unconscious; Younglings recover coins | All Investigators are unconscious; Younglings search for and recover Cassidy's coins, then leave. Investigators may later wake. | p. 22 |
| OUT-006 | Bureau questioning and secrecy | Following Coastguard rescue, investigators may be questioned, have possessions confiscated, and be sworn to secrecy. | p. 22 |

Do not conflate survival with evacuation. OUT-002 can occur while the Investigator remains on Beacon Island; OUT-003 and OUT-004 represent actual routes to safety.

---

## 9. NPC and character reference

| ID | Name | Role / information | Source |
|---|---|---|---|
| NPC-001 | Warren Thomas / Michael Turner | Bureau Agent undercover as lighthouse keeper; deceased. Player's colleague. | pp. 8–12, 18 |
| NPC-002 | George Cassidy | Lighthouse keeper; collected gold coins; died defending himself. | pp. 8–10, 14–15, 20 |
| NPC-003 | Samuel Smith | Lighthouse keeper; captured, interrogated and murdered. | pp. 8–10 |
| NPC-004 | Deep One hybrid at Folly Point | Surviving hybrid waiting on mainland shore; potential extension threat. | pp. 9, 12, 21–23 |
| NPC-005 | Deep One hybrid killed in lantern room | Killed by Cassidy. | pp. 9, 19–20 |
| NPC-006 | Younglings | Amphibious creatures searching for Cassidy's missing coins. | pp. 9, 20–23 |
| NPC-007 | Anna Tilton | Correspondent in Cassidy's letters; Newburyport Society. | p. 14 |
| NPC-008 | Coastguard | Potential rescuers after radio distress call. | pp. 18–19, 21–22 |

**Identity safeguard:** Warren Thomas is the Bureau Agent's colleague and an NPC. The player character is the Bureau Agent. Michael Turner is Thomas's undercover identity, not a separate person.

---

## 10. Location reference

| ID | Location | Function / evidence | Source |
|---|---|---|---|
| LOC-001 | SS Essex County wreck | Opening shipwreck and submerged metal debris. | pp. 9–10 |
| LOC-002 | Beacon Island | Main adventure setting. | pp. 9–12 |
| LOC-003 | North Pier / Dock | Likely landing point; island access. | p. 10 |
| LOC-004 | Lighthouse Cottage | Main exploration hub. | pp. 13–19 |
| LOC-005 | Hallway | Bullets, blood, three gold coins. | p. 13 |
| LOC-006 | Study | Paintings, binoculars, appraisals, letters, locked desk drawer. | pp. 13–15 |
| LOC-007 | Bunkroom | Thomas's notebook hidden in mattress. | p. 18 |
| LOC-008 | Kitchen | Blood, broken chair, knife. | p. 18 |
| LOC-009 | Larder | Food supplies. | p. 18 |
| LOC-010 | Service Room | Maintenance log, replacement bulbs, radio. | pp. 18–19 |
| LOC-011 | Lantern Room | Cassidy, bodies, creatures, gold purse, damaged lens. | pp. 19–20 |
| LOC-012 | Thicket | Turner's body and tracks. | pp. 11–12 |
| LOC-013 | Generator Shed | Running generator and leaking roof. | p. 11 |
| LOC-014 | Workshop | Tools and materials for roof repair and opening drawer. | p. 11 |
| LOC-015 | South Pier | Yellow rowboat and possible escape. | pp. 12, 20 |
| LOC-016 | Folly Point | Mainland shore; light and hybrid presence. | pp. 12–13, 21–23 |

---

## 11. Events and timeline

| ID | Time / sequence | Event | Classification / source |
|---|---|---|---|
| EVT-001 | 12 Feb 1926 | Lighthouse bulb failure during severe storm contributes to SS Essex County wreck. | CANON, pp. 8–9, 18 |
| EVT-002 | Following days/weeks | Gold coins wash ashore; Cassidy collects them and seeks appraisal. | CANON, pp. 8–10, 14–15 |
| EVT-003 | Before 12 Apr 1926 | Cultists arrange recovery operation; hybrids and Younglings assigned. | CANON, pp. 8–10 |
| EVT-004 | 12 Apr 1926, approx. 8 PM | Cassidy fights attackers; kills two Younglings and one hybrid; dies; stray bullet damages beacon lens/bulb. | CANON, pp. 9, 19–20 |
| EVT-005 | 12 Apr 1926, 8:15 PM | SS Essex County wrecks; investigators head to Beacon Island. | CANON, pp. 9–10 |
| EVT-006 | After landing | Investigator explores island, cottage, grounds and lighthouse. | CANON, pp. 10–20 |
| EVT-007 | Keeper-selected trigger | Remaining Younglings assault investigators after exploration or discovery of Turner's body. | CANON with flexible Keeper timing, pp. 20–21 |
| EVT-008 | Conclusion | Younglings withdraw/are neutralized, investigators die, or rescue may arrive. | CANON, pp. 21–22 |
| EVT-009 | After rescue | Bureau questioning, confiscation and secrecy may follow. | CANON, p. 22 |

The PDF does not prescribe a single mandatory exploration order. Do not impose one.

---

## 12. Equipment and resources

| ID | Resource | Source-supported use | Source |
|---|---|---|---|
| RES-001 | Yellow rowboat at south pier | Possible escape from island. | p. 12 |
| RES-002 | Radio in service room | Request Coastguard rescue after repair. | pp. 18–19 |
| RES-003 | Generator | Electrical supply; vulnerable to roof leak and rain. | pp. 11, 21 |
| RES-004 | Replacement bulbs | Temporary lighthouse repair; lens remains damaged. | pp. 18, 20 |
| RES-005 | Workshop tools/materials | Repair generator shed roof; open locked desk drawer. | p. 11 |
| RES-006 | Kitchen knife | Weapon or tool to force desk drawer. | p. 18 |
| RES-007 | Smith & Wesson .38 Special | Turner's revolver; five live bullets and one spent casing when found. | pp. 11–12 |
| RES-008 | Colt M1877 | Cassidy's revolver; all chamber bullets spent, may be reloaded. | p. 20 |
| RES-009 | Cassidy's gold purse | Target of Younglings' search; optional recovery/reward. | pp. 20, 22 |
| RES-010 | Binoculars | Observe Folly Point from the study. | pp. 12–13 |

Do not invent quantities, condition, or availability beyond source descriptions and the current character sheet.

---

## 13. Threats and hazards

### Younglings — CANON

- Amphibious fishlike creatures.
- Pursue prey aggressively and use projectile needles before melee attacks.
- Needles are poison-tipped; the source describes Dodge and Extreme CON checks.
- Possess natural armor; eyes and belly are vulnerable areas.
- They are not particularly intelligent and do not recognize humans as superiors.
- Their number and exact encounter pressure may be adjusted by the Keeper as described in the adventure.

### Deep One hybrids — CANON

- Amphibious humanoid creatures associated with the Innsmouth cultists.
- One hybrid was killed by Cassidy.
- Another remains at Folly Point and may withdraw if the island assault goes badly.
- The adventure suggests a longer-game extension in which the Folly Point hybrid travels to the island with additional Younglings.

### Environmental hazards — CANON

- Storm and heavy rain.
- Rough sea and dangerous rocks.
- Rain may erase tracks.
- Leaking generator shed roof may cause generator failure.
- Darkness and damaged lighthouse lens.
- Slippery, confined lantern room.
- Potentially dangerous boat escape and the hybrid at Folly Point.

---

## 14. Runtime guidance

1. **Preserve player agency.** The COREs describe outcomes, not a required sequence of actions.
2. **Keep secrets concealed.** Do not reveal the GM-only background, hidden identities, creature details, or future events before the Investigator has a legitimate opportunity to discover them.
3. **Use evidence cumulatively.** Evaluate whether the acquired evidence reasonably supports the CORE outcome. The player need not repeat the exact wording of a completion condition.
4. **Separate finding from understanding.** A discovered clue does not automatically establish that its significance is understood.
5. **Separate investigation from operation.** Clues represent information; Operational Requirements represent achieved outcomes.
6. **Do not force every clue.** Supporting clues and optional Branches are not mandatory unless explicitly listed as required.
7. **No unnecessary checks.** Use source-defined checks where they matter; otherwise adjudicate using character capability, challenge, and approach.
8. **No automatic retries.** A new attempt requires a materially different approach, new condition, or different resource, under the GM Operating Protocol.
9. **Failure does not equal impossibility.** Mark a Clue or Branch IMPOSSIBLE only when every valid acquisition/completion path is permanently unreachable.
10. **Preserve completed history.** COMPLETED COREs and Branches, and DISCOVERED Clues, remain completed/discovered.
11. **Handle early escape correctly.** A safe early evacuation completes BR-003A and BR-004A through their respective alternative paths. Do not require the Investigator to experience the assault.
12. **Do not confuse radio repair with rescue.** The Coastguard must actually arrive and rescue the Investigator.
13. **Do not import full Keeper rules silently.** The source references chase rules outside the Quick-Start Rules; flag this limitation rather than importing them without authorization.
14. **Maintain character continuity.** Character Sheet and Adventure State in GitHub remain authoritative for dynamic character and gameplay state. This Trace is static adventure structure.
15. **Do not record a playthrough in this static Trace.** Session events, discovered clues, objective statuses, and outcomes belong in Adventure State.

---

## 15. Validation report

### 15.1 Structural validation

| Criterion | Result | Notes |
|---|---|---|
| CORE IDs unique | PASS | CORE-001 through CORE-004 |
| Every CORE has concrete completion requirements | PASS | Each has required Branch(es) |
| All COREs initially reachable | PASS | No predecessor dependencies |
| No CORE dependency cycles | PASS | No inter-CORE dependencies |
| Branch has one Anchor CORE | PASS | All Branches anchored |
| Required Branch Clues belong to owning CORE | PASS | No cross-CORE clue dependencies |
| Branch has at least one concrete requirement | PASS | Clues or operational requirements |
| Branch completion uses AND across declared requirements | PASS | OR only within declared alternative operational requirement |
| CORE completion uses AND across required Branches | PASS | CORE-004 has one Branch with OR paths |
| Alternative paths represented as OR | PASS | BR-003A and BR-004A |
| Historical completion precedence preserved | PASS | COMPLETED is permanent |
| Clue state model preserved | PASS | UNDISCOVERED / DISCOVERED / IMPOSSIBLE |
| Branch and CORE state model preserved | PASS | HIDDEN / AVAILABLE / COMPLETED / IMPOSSIBLE |

### 15.2 Source coverage and limitations

| Area | Result | Notes |
|---|---|---|
| Main narrative and background | COVERED | Source pp. 8–10 |
| Thomas identity and notebook | COVERED | Source pp. 11–12, 18 |
| Coins and Cassidy documents | COVERED | Source pp. 13–15 |
| Lighthouse failure | COVERED | Source pp. 18–20 |
| Assault and survival | COVERED | Source pp. 20–22 |
| Rescue and escape | COVERED | Source pp. 12, 18–22 |
| Optional Folly Point extension | COVERED | Source pp. 12, 21–23 |
| Skill Check inventory | PROVISIONAL | Explicit source checks listed; not a claim that every possible adjudication is exhausted |
| External chase procedure | NOT INCLUDED | Full Keeper Rulebook rule referenced by source, outside Quick-Start material |
| Exact Coastguard timing | UNSPECIFIED | Runtime must not invent a guaranteed arrival time |
| Exact rain deadline for tracks | UNSPECIFIED | Runtime must not invent a fixed duration |
| Guaranteed boat escape | UNSPECIFIED | Boat and sea conditions may make escape unsafe |
| Complete contents of handouts | SOURCE-DEPENDENT | Consult original handout pages; do not invent missing text |

### 15.3 Known design derivations

- Four independent CORE objectives are a DERIVED operational structure, not a formal Backbone supplied by the author.
- CORE-001's required completion is limited to identifying Thomas and establishing his fate. Recovering his notebook is an optional Branch.
- CORE-002 requires the combined reconstruction of coin provenance, Cassidy's recovery operation, and the lighthouse failure's connection to the wreck.
- CORE-003 and CORE-004 are distinct outcomes but may be completed by the same successful evacuation.
- The safe-early-evacuation path under CORE-003 is DERIVED to ensure that avoiding an attack can count as successful survival.
- Branch groupings and Clue identifiers are operational organization, not labels from the original adventure.

---

## 16. Artifact status

| Field | Value |
|---|---|
| Artifact | The Lightless Beacon — Adventure Trace V2.0 |
| Status | PILOT — STRUCTURAL BASELINE |
| Source | Original adventure PDF |
| Rules source | Call of Cthulhu 7th Edition Quick-Start Rules |
| Design model | Fishbone |
| CORE objectives | 4 |
| Branches | 7 |
| Clues | 18 |
| Skill Check entries | 41 |
| Structural validation | PASS |
| Source coverage | DOCUMENTED |
| Mechanical completeness | NOT CERTIFIED |
| Runtime production approval | NOT GRANTED |

**Operational statement:** This Trace is the static adventure reference for Runtime. It does not replace the original PDF, does not contain dynamic session state, and does not certify mechanical completeness beyond the documented source inventory.

**END OF ADVENTURE TRACE**
