To ensure consistent alignment citations for EPS Learning programs, please follow the instructional guidelines provided below.

### AI Instruction: Generating EPS Alignment Citations

**Objective:** Draft consistent, accurate, and properly formatted citation strings for EPS Learning programs based on specific structural requirements.

---

#### 1. General Formatting Rules

* **Delimiter:** Use a semicolon and a space (`; `) to join all fields.

* **Order of Fields:**
1. **Program** 
2. **Material Type** 
3. **Unit/Level** 
4. **Lesson/Step** 
5. **Page/Click Path** 
6. **Standards Code** 
7. **URL** 
8. **Audience** 
9. **Evidence Type** 
10. **Directions** 

* **String Assembly:** Ensure the final string adheres to the pattern: `Program; Material; Unit/Level; Lesson/Step; Page; Standards; URL; Audience; Evidence; [cite_start] Directions`.
Material``
---

#### 2. Program-Specific Structural Requirements

When identifying the Unit, Lesson, and Task, follow these program-specific hierarchies:

| Program | Hierarchy Structure |
| --- | --- |
| **SPIRE Up** | Skill → Lesson → Activity |
| **SPIRE 4E** | Level → Lesson → Step |
| **SPIRE Foundations** | Lesson → Step |
| **Megawords** | Book → Word List → Exercise |
| **Reading Accelerator** | Skill → Lesson → Activity |
| **SPIRE Next** | Level → Lesson → Read |
| **Wordly Wise** | Book → Lesson → Activity |
| **SPIRE Decodable Readers** | Level → Set → Reader |
| **Readfetti** | Skill Group → Book → Focus |
| **Vocabulary from Classical Roots** | Book → Lesson → Activity/Exercise |

---

#### 3. Material Type Registry

Use the following keys for the **Material Type** field. You may use the shorthand key (e.g., `TE`) if the material type is abbreviated:

* **Print**: `TE` (Teacher Edition), `SE` (Student Edition), `SWB` (Student Workbook), `BLM` (Blackline Master), `TR` (Teacher Resource), `SR` (Student Resource), `DR` (Decodable Reader), `RAC` (Read-Aloud Cards), `WL` (Word List), `EX` (Exercise), `GC` (Game Cards), `LC` (Letter Cards), `WC` (Word Cards), `HWC` (Heart Word Cards), `PFC` (Phonogram Cards), `KWS` (Key Word Sheet), `MC` (Manipulative Cards), `SMK` (Student Kit), `PT` (Placement Test), `ASMT` (Assessment), `FP` (Fluency Practice), `RP` (Reading Passage), `UR` (Unit Resource).
* **Digital**: `DTE`, `DSE`, `DSWB`, `DTR`, `DSR`, `DA`, `DASMT`, `DASH` (Dashboard), `DG` (Digital Game), `DMR`, `DFP`.

---

#### 4. Examples for Reference

Use these examples as a template for style and field ordering:

* **SPIRE Up:** `SPIRE; Skill 12; Lesson 12B; Activity: Heart Words sentence reading`
* **SPIRE 4E:** `SPIRE 4E; Level 3; Reinforcing Lesson 3; Step 6 (Reading & Comprehension)`
* **Megawords:** `Megawords; Book 3; List 12; Exercise: Words in Context practice`
* **Wordly Wise:** `Wordly Wise; Book 5; Lesson 8; Activity: Word study and application`
* **SPIRE Decodable Readers:** `SPIRE Decodable Readers; Level 2; Set A; Reader: “The Lost Dog”`

---

# About This Tool

The EPS Citation Generator builds standardized curriculum-alignment citations for proposals, RFP evidence tables, and compliance documentation. Assemble each citation field by field, save it to your library, then tag, search, copy, or export to CSV.

1.  **Select an EPS Program.** The Unit / Lesson / Task fields automatically relabel to match that program's structure.
2.  **Choose a Material Type.** Toggle *Abbreviate* to use the short key (e.g., `TE`) instead of the full name.
3.  **Add the details** --- standards code, page number(s), format, delivery method, audience, evidence type, and location notes.
4.  **Review the Live Preview,** add optional tags, and **Save Citation.**
5.  **Manage your library** on the Builder tab --- search, filter, tag, copy, or export to CSV.

## Citation Structure
--------------------------------

```
'[Standards Code], [EPS Program Name], [Material Type], [Format], [Unit], [Lesson], [Task], [Page / Click Path], [Delivery Method], [Audience], [Evidence Type], [Location Notes & Cross-References]. See: ([Evidence Web Link (URL)])'
```

## Core Fields
--------------------------------
-   **Standards Code:** The educational standards code this citation supports. *Recommended but optional* --- useful for organizing citations across multiple standards.
-   **EPS Program Name:** Supports quick-fill from the program registry (see Program Hierarchy below) or free-text entry. Selecting a known program automatically relabels the Unit / Lesson / Task fields to match that program's structure.
-   **Material Type:** Select from 31 defined types (see Material Types table below). Toggle *Abbreviate* to use the short key (e.g., `TE`) instead of the full material name.
-   **Format:** Appears directly after Material Type in the citation. Options are `Print`, `Digital`, or `Hybrid`. Selecting **Digital** changes the Page field to **Click Path** and formats the citation accordingly (see below).

```
Program Structure --- Unit → Lesson → Task
```

To remove ambiguity between program structures, a standardized three-level hierarchy is used. Each field relabels automatically when a known program is selected.

-   **Unit** --- relabels to: `Level`, `Skill`, `Skill Group`, or `Book` depending on program.
-   **Lesson** --- relabels to: `Lesson`, `Word List`, `Book`, or `Set` depending on program.
-   **Task** --- relabels to: `Step`, `Activity`, `Exercise`, `Read`, `Reader`, or `Focus` depending on program. Programs with only two levels (e.g., SPIRE Foundations) hide the unused field.

### Page Number(s) vs. Click Path
--------------------------------
-   **Print / Hybrid:** Enter a page number or range. Single pages are prefixed with `p.`; ranges are prefixed with `pp.` automatically (e.g., `p. 42` or `pp. 64--68`).
-   **Digital:** The field relabels to **Click Path**. Enter the navigation path to locate the evidence (e.g., `Home > Programs > SPIRE Up > Level 5`). The citation renders as: *Once logged into [Program] follow the following click path [value]*.

### Supporting Fields
--------------------------------
-   **Delivery Method:** *Optional.* How the material is delivered --- Whole Group, Small Group, Direct Instruction, or Independent Practice.
-   **Audience:** *Optional.* Teacher or Student. Related to Evidence Type --- see Field Definitions below.
-   **Evidence Type:** *Optional.* Narrative or Activity. Related to Audience --- see Field Definitions below.
-   **Location Notes & Cross-References:** Short directions to locate cited evidence, a cross-reference to another artifact type, and/or a brief narrative if necessary. Limited to 300 characters.
-   **Evidence Web Link (URL):** A direct link to evidence of the citation's alignment to the standards code being cited. Renders as `See: (URL)` at the end of the citation.

## Field Definitions
--------------------------------------
### Audience
#### Teacher
-   Artifacts designed for the educator to facilitate or guide instruction --- e.g., explicit scripts, instructional rationales, modeling guides, lesson overviews, and progress-monitoring forms.

#### Student
-   Artifacts designed for student interaction where the student is the primary actor --- e.g., workbooks, student text, digital activities, and worksheets.

**Evidence Type**
----------------------------

#### Narrative 'Input'
-   Represents the **"Input"** phase of learning --- the opportunity for the teacher to teach the concept, or for the student to initially learn or read about it.

#### ActivityOutput / Application
-   Represents the **"Output" / "Application"** phase --- the student actively practices, demonstrates, or applies the skill.

## Program Hierarchy

Selecting a program in the Builder relabels the three alignment fields to match this structure. Programs with only two levels (e.g., SPIRE Foundations) hide the unused field.
-   SPIRE Up: Skill→Lesson→Activity
-   SPIRE 4E: Level→Lesson→Step
-   SPIRE Foundations: Sounds Sensible: Lesson→Step
-   Megawords: Book→Word List→Exercise
-   Reading Accelerator: Skill→Lesson→Activity
-   SPIRE Next: Level→Lesson→Read
-   Wordly Wise: Book→Lesson→Activity
-   SPIRE Decodable Readers: Level→Set→Reader
-   Readfetti: Skill Group→Book→Focus
-   Vocabulary from Classical Roots: Book→Lesson→Activity/Exercise

## Material Types (*32 types*)

| Key | Material | Description | Format |
| --- | --- | --- | --- |
| TE | Teacher Edition / Guide | Lesson plans, routines, scripting | Print |
| SE | Student Edition / Book | Core student-facing instructional content | Print |
| SWB | Student Workbook | Practice, encoding, written responses | Print |
| BLM | Blackline Master | Reproducible teacher/student materials | Print |
| PTR | Print Teacher Resource | Supplemental teacher materials | Print |
| PSR | Print Student Resource | Handouts, worksheets, reference sheets | Print |
| DR | Decodable Reader(s) | Controlled text aligned to phonics skills | Print |
| RAC | Read-Aloud Cards | Teacher-led comprehension and vocabulary resource | Print |
| WL | Word List | Megawords structured word list content | Print |
| EX | Exercise / Practice Sheet(s) | Megawords / VCR student practice tasks | Print |
| IGC | Instructional Game Cards | Phonics / vocabulary games | Print |
| L/WC | Letter / Word Cards | Alphabet and phoneme aids; word recognition and decoding practice | Print |
| HWC | High-Frequency / Heart Word Cards | Evidence-based high-frequency word practice | Print |
| PFC | Phonogram Flash Cards | Sound-symbol correspondence | Print |
| KWS | Key Word / Concept Sheet | Introduces phonics concept | Print |
| MB/T | Manipulative Boards / Tiles | Segmentation boards, tiles | Print |
| SMK | Student Manipulatives Kit | Hands-on materials set | Print |
| SPT | Student Placement Test | Initial student placement | Print |
| ASMT | Student Assessment(s) | Formative or summative evaluation tools | Print |
| FPDS | Fluency Practice / Drill Sheet(s) | Fluency development resources | Print |
| SRP | Student Reading Passage(s) | Decodable or comprehension-aligned reading text | Print |
| DTE | Digital Teacher Edition | Interactive Teacher Edition | Digital |
| DSE | Digital Student Edition | Digital teacher guides; lesson plans, routines, scripting | Digital |
| DSWB | Digital Student Workbook | Core student-facing digital instructional content | Digital |
| DTR | Digital Teacher Resource | Lesson guides, reports | Digital |
| DSR | Digital Student Resource | Practice activities | Digital |
| DSA | Digital Student Activity | Interactive practice tasks | Digital |
| DASMT | Digital Assessment | Placement test, benchmarking, oral reading fluency | Digital |
| DASH | Dashboard / Analytics | Progress monitoring, reporting | Digital |
| DGT | Digital Game / Interactive Tool | --- | Digital |
| DMR | Digital Manipulative Resource | Virtual cards / tiles | Digital |
| DFP | Digital Fluency Practice | Oral reading tracking | Digital |
