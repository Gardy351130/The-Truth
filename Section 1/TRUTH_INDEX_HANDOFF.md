# TRUTH INDEX ENCYCLOPEDIA — PROJECT HANDOFF DOCUMENT

## PROJECT OVERVIEW

**Name:** Truth Index Encyclopedia  
**Type:** Dual-format knowledge system documenting cognitive mechanisms and real-world manipulation patterns  
**Launch Status:** Section 1 deployed to GitHub, live Monday (quiet launch, organic growth)  
**Builder:** Claude (Anthropic) working with Alvin (GrumpyBum/Sol Gardner brand)  
**Purpose:** Reference library for pattern recognition, not advice or fixes

---

## CORE ETHOS & AIMS

### What This Is
A **living encyclopedia** that documents:
- How human cognition actually works (cognitive mechanisms)
- How those mechanisms get exploited in real-world contexts (case studies)
- The gap between perception and reality
- Why intelligent people make predictably poor decisions

### What This Is NOT
- Self-help content
- Advice or mitigation strategies
- Moral judgment or condemnation
- Persuasion or advocacy
- Marketing material

### Guiding Principles (NON-NEGOTIABLE)
1. **Mechanism over motive** — Document structure, not intent
2. **Observation over opinion** — Facts only, no speculation
3. **Neutrality over judgment** — No "you should have known better"
4. **Documentation over prescription** — Show how it works, not how to fix it
5. **Academic rigor** — Every claim backed by research citations

### Project Aims
- **Short-term:** Organic SEO growth through quality content + academic citations
- **Mid-term:** Become authoritative reference for cognitive bias documentation
- **Long-term:** THE source for manipulation pattern recognition
- **Philosophical:** "Images earn attention. Text earns understanding. Structure earns trust."

---

## LOCKED TEMPLATE STANDARDS

### TEMPLATE 1: ENCYCLOPEDIA ENTRIES (Vintage Scholarly)

**Visual Identity:**
- **Fonts:** 'Libre Baskerville' (headers), 'Crimson Text' (body text)
- **Colors:**
  - Background: #fdfcf8 (aged paper)
  - Container gradient: #f4f1e8 to #e8e4d8
  - Primary text: #2c2416
  - Accent brown: #8b7355
  - Secondary brown: #6b5d4f
  - Border: #d4c4a8
  - Citation links: #1a5490 (blue)
- **Layout:** Max-width 900px, vintage box-shadow, double-border separators
- **Aesthetic:** Funk & Wagnalls encyclopedia, early 1900s scholarly publishing

**Content Structure (STRICT ORDER):**
```
1. Encyclopedia header (centered, uppercase, letter-spaced)
2. Breadcrumb (Section 1: Foundations of Interpretation › Chapter X)
3. Main title (42px, Libre Baskerville, centered)
4. Subtitle (18px, italic, centered, grey)
5. Back button (top) — javascript:history.back()
6. Visual demonstration (custom SVG, top 2/3 of page)
   - Title (h3)
   - Image box (#f8f6f0 background, bordered)
   - Caption (italic, explanatory, max 700px width)
7. Introduction box (background #f8f6f0, left border #8b7355)
8. Main content sections (h2 headers with bottom border)
   - Subsections as h3 (italic, no border)
   - Prose paragraphs (justified, max 8-10 lines)
9. Separator (horizontal double-border)
10. Closing transitional paragraph
11. Supporting Case Studies section (before references)
    - Background #f8f6f0, left border
    - Blue links (#1a5490) to case studies
    - Format: "CS-XXX: Title" with brief explanation
12. Back button (bottom)
13. References (APA format, blue hyperlinks)
```

**Writing Rules (NON-NEGOTIABLE):**
- Third-person scholarly voice ONLY
- Formal academic language
- NO "you" language ever
- NO motivational content
- NO advice or mitigation strategies
- Every claim backed by APA citation
- Short paragraphs (8-10 lines maximum)
- Text-align: justify
- One strong custom SVG visual per chapter (top 2/3)
- 15-20 peer-reviewed citations minimum

**File Naming:** `section1_chapterX_title_keywords.html`

---

### TEMPLATE 2: CASE STUDIES (Dark Observational)

**Visual Identity:**
- **Fonts:** 'Inter' (body), 'Courier Prime' (monospace for code/status)
- **Colors:**
  - Background: #1a1a1a (black)
  - Container: #2a2a2a (dark grey)
  - Text: #e0e0e0 (light grey)
  - Accent: #ff6b35 (orange)
  - Left border: 4px solid #ff6b35
  - Links: #4a9eff (blue)
  - Success/status: #4caf50 (green)
- **Layout:** Max-width 800px, left accent border
- **Aesthetic:** Field notes, observational documentation, human-readable evidence

**Content Structure (7-POINT TEMPLATE):**
```
1. Case ID (monospace, orange, letter-spaced: "CASE STUDY CS-XXX")
2. Title (36px, white) + Subtitle (18px, italic, grey)
3. Summary box (background #1f1f1f, left border orange)
4. "What Happened" section
   - First-person: "I clicked", "I saw", "I observed"
   - Context box (blue left border, background #1f1f1f)
5. Main analytical sections (varies by case)
   - "How It Works"
   - Mechanism breakdowns
   - Structural observations
6. "What the Structure Relies On" (assumptions documented)
   - Background #1f1f1f
   - No moral judgment
7. "Why This Case Exists" conclusion
8. Encyclopedia Cross-References section (blue border/background)
   - Links to relevant chapters
   - Format: "Section 1, Chapter X — Title"
9. Navigation ("← Back to Case Studies Index")
10. Status bar (monospace, green text, bottom)
```

**Writing Rules (NON-NEGOTIABLE):**
- First-person observational voice ("I clicked", "I saw")
- Plain-spoken human language
- Short paragraphs for readability
- NO academic citations inside case studies
- NO intent language ("they're trying to...")
- NO moral commentary ("you should have known")
- Mechanism without motive
- Observation without opinion

**Forbidden Phrases:**
- "Here's the trick"
- "What they're counting on"
- "They're trying to..."
- "You should..."

**Correct Alternatives:**
- "Key structural feature"
- "What the structure relies on"
- "What this requires"

**File Naming:** `CS-XXX_Title_Keywords.html`

---

## BIDIRECTIONAL NAVIGATION SYSTEM (LOCKED)

### From Case Study → Encyclopedia
- **Link Type:** Chapter-level ONLY (no subsections, no anchors)
- **Format:** `Section 1, Chapter X — Title`
- **Placement:** Only in "Encyclopedia Cross-References" section
- **Style:** Blue links (#4a9eff), hover underline
- **Example:**
```html
<a href="section1_chapter4_exposure_repetition_familiarity.html">
Section 1, Chapter 4 — Exposure, Repetition & Familiarity
</a>
```

### From Encyclopedia → Case Study
- **Link Type:** Case ID only (CS-001, CS-002, etc.)
- **Format:** `CS-XXX: Title`
- **Placement:** Only in "Supporting Case Studies" section
- **Style:** Blue links (#1a5490), hover underline
- **Example:**
```html
<a href="CS-001_Endless_Scroll_Funnel.html">
CS-001: The Endless Scroll Funnel
</a>
```

### Navigation Controls
- **Case Studies:** `← Back to Case Studies Index` (orange)
- **Encyclopedia:** `← Back` (top and bottom) using `javascript:history.back()`
- **NO:** Deep anchors, auto-scroll, clever UX, cross-linking between chapters

---

## COMPLETED WORK (READY FOR GITHUB)

### Section 1: Foundations of Interpretation (COMPLETE)

**Encyclopedia Chapters Built:**
1. ✅ **Chapter 1:** Perception vs Reality (`section1_chapter1_perception_vs_reality.html`)
   - Checker Shadow Illusion visual
   - Three mechanisms: sensory input, prior experience, cognitive shortcuts
   - 14 APA citations
   - Links to CS-001, CS-002

2. ✅ **Chapter 2:** Assumptions People Hold (`section1_chapter2_subsection2-1_assumptions.html`)
   - Custom SVG: observation → assumption ladder
   - Documents implicit belief formation
   - Links to CS-001, CS-002, CS-003

3. ✅ **Chapter 3:** Cognitive Biases in Interpretation (`section1_chapter3_cognitive_biases.html`)
   - Custom SVG: bias filter funnel
   - Six major biases documented
   - Links to CS-001, CS-002

4. ✅ **Chapter 4:** Exposure, Repetition & Familiarity (`section1_chapter4_exposure_repetition_familiarity.html`)
   - Custom SVG: timeline showing mere-exposure effect
   - Four mechanisms documented
   - 21 APA citations
   - Links to CS-001, CS-002, CS-003

5. ✅ **Chapter 5:** Confidence, Certainty, and the Feeling of Knowing (`section1_chapter5_confidence_certainty_feeling_of_knowing.html`)
   - Custom SVG: confidence-evidence disconnect timeline
   - Five mechanisms documented
   - 18 APA citations
   - Links to CS-002, CS-003

6. ✅ **Chapter 7:** Closure, Commitment, and the End of Questioning (`section1_chapter7_closure_commitment_end_of_questioning.html`)
   - Custom SVG: interpretive closure funnel
   - Five mechanisms documented
   - 18 APA citations
   - Final chapter of Section 1
   - Links to CS-001, CS-002
   - Transitions to Section 2

**Note:** Chapter 6 (Authority) skipped to Chapter 7 as finale

**Case Studies Built:**

1. ✅ **CS-001:** The Endless Scroll Funnel (`CS-001_Endless_Scroll_Funnel.html`)
   - Vertical scroll as commitment mechanism
   - Time investment creating sunk cost
   - Supports: Chapters 2, 3

2. ✅ **CS-002:** The Assessment Questionnaire (`CS-002_Assessment_Questionnaire.html`)
   - Questions creating perception of expertise
   - Personal answers implying relevance
   - Supports: Chapters 2, 3, 5, 7

3. ✅ **CS-003:** Entry Path Framing & Attention-Based Pricing (`CS-003_Entry_Path_Framing.html`)
   - Same product, different prices ($27 vs $67)
   - Entry path determines perceived value
   - Supports: Chapters 2, 3, 4

4. ✅ **CS-004:** The Hedge Fund Acquisition Engine (`CS-004_Hedge_Fund_Acquisition_Engine.html`)
   - Authority laundering through institutional terminology
   - Borrowed legitimacy from unrelated domains
   - Loop reinforcement despite failure
   - Anchor line: "If a system truly worked like a hedge fund, it would not need a sales page"
   - Supports: Chapters 2, 3, 5, 7
   - **CANONICAL EXAMPLE** of authority borrowing + manipulation loop

5. ✅ **CS-005:** The Confession Ad (`CS-005_The_Confession_Ad.html`)
   - Admitted failure as credibility signal
   - Status reset vs. authority claims
   - Structural inversion of CS-004
   - Anchor line: "People don't trust confidence anymore. They trust recognized failure"
   - Supports: Chapters 2, 4, 5

6. ✅ **CS-006:** Campaign Saturation & Perceived Inevitability (`CS-006_Campaign_Saturation_Perceived_Inevitability.html`)
   - 11 ads in 2h15m, format rotation
   - Environmental dominance through frequency
   - Evaluation → accommodation shift
   - Anchor line: "Repetition across variation creates the illusion of consensus"
   - Supports: Chapters 4, 5
   - Related to CS-003

**All files in:** `/mnt/user-data/outputs/`

---

## SEO & GROWTH STRATEGY

### Why This Works for Organic Authority Building

1. **Academic Citation Structure** = Trust Signals
   - 15-20 APA citations per chapter
   - Outbound links to peer-reviewed journals
   - Google recognizes .edu and institutional domains as high-authority

2. **Bidirectional Internal Linking** = Site Architecture
   - Encyclopedia ↔ Case Studies cross-referencing
   - Clear information hierarchy
   - Google understands content relationships

3. **Long-Form Quality Content** = Dwell Time
   - Encyclopedia: 2,000-3,000 words
   - Case studies: 1,500-2,500 words
   - Low bounce rate + high time-on-page = strong ranking

4. **Natural Keyword Density**
   - Terms appear in academic context
   - No keyword stuffing
   - Long-tail search phrases match content depth

5. **Unique Original Analysis** = No Duplicate Content
   - Case studies document original observations
   - Encyclopedia synthesizes research in unique voice
   - Google rewards genuine analysis

6. **Topic Cluster Architecture**
   - Section 1 = cognitive foundations pillar
   - Chapters = pillar content
   - Case studies = supporting content

7. **Evergreen Content** = Sustained Traffic
   - Cognitive mechanisms don't change
   - Research foundations remain valid
   - Accumulates backlinks over years

### Growth Timeline (Expected)
- **Months 1-3:** Indexing, discovery
- **Months 6-12:** Academic citations generate referral traffic
- **Years 2-3:** Domain becomes associated with cognitive bias authority
- **Years 5+:** THE authoritative source for manipulation pattern documentation

---

## CRITICAL STANDARDS (NEVER VIOLATE)

### Universal Rules Across Both Formats

1. **No intent attribution** — "they want you to..." is forbidden
2. **No moral judgment** — "you should have..." is forbidden
3. **No prescriptive advice** — "here's how to fix it" is forbidden
4. **Facts only, no speculation**
5. **Mechanisms over motives**
6. **Structure over judgment**

### Encyclopedia-Specific
- Every claim backed by research (APA citations)
- No listicles unless explicitly requested
- Prose paragraphs, not bullet points
- Visual demonstration at chapter start (top 2/3)
- Short paragraphs (8-10 lines max)
- No "you" language
- Justified text alignment
- Third-person scholarly voice

### Case Study-Specific
- NO INTENT LANGUAGE (describe mechanism, not motive)
- NO MORAL COMMENTARY (document, don't judge)
- First-person observation ("I clicked", "I saw")
- Plain human language (conversational)
- Short paragraphs (readability)
- No academic citations
- Structure follows 7-point template exactly
- Dark theme aesthetic

---

## QUALITY CHECKPOINTS

**Before completing any encyclopedia chapter:**
- [ ] Custom SVG visual present and relevant
- [ ] 15-20 APA citations with blue hyperlinks
- [ ] Top and bottom back buttons functional
- [ ] Supporting Case Studies section included
- [ ] All paragraphs under 8-10 lines
- [ ] No "you" language anywhere
- [ ] Prose format (not lists unless requested)
- [ ] Text justified

**Before completing any case study:**
- [ ] First-person voice throughout
- [ ] No intent language detected
- [ ] No moral commentary detected
- [ ] 7-point structure followed exactly
- [ ] Encyclopedia Cross-References section present
- [ ] Back to Case Studies Index link present
- [ ] Status bar at bottom
- [ ] Dark theme aesthetic maintained

---

## WHAT'S NEXT

### Section 2: Constructed Information Environments (PLANNED)

Based on Section 1's closing paragraph transition:
> "Section 2 examines how these foundational patterns manifest in constructed information environments where closure is engineered rather than emergent."

**Expected focus:**
- Application of Section 1 mechanisms in designed systems
- How cognitive patterns are exploited structurally
- Engineered environments vs. natural cognitive bias
- Strategic manipulation of interpretation pathways

**Anticipated topics:**
- Information architecture designed for closure
- Structural amplification of cognitive biases
- Choice architecture and framing systems
- Authority construction and signal manipulation
- Engineered uncertainty and resolution cycles

### Template Consistency for Section 2
All templates remain LOCKED. Same standards apply:
- Encyclopedia: Funk & Wagnalls vintage scholarly
- Case Studies: Dark observational field notes
- Navigation: Bidirectional, chapter-level only
- Quality: Academic rigor + neutrality

### Additional Case Studies (As Observed)
More patterns can be documented as they're encountered:
- Follow locked dark-theme template
- Sequential numbering (CS-007, CS-008, etc.)
- Link back to relevant encyclopedia chapters
- Maintain first-person observational voice

---

## FILE MANAGEMENT

### Directory Structure
```
/mnt/user-data/outputs/
├── section1_chapter1_perception_vs_reality.html
├── section1_chapter2_subsection2-1_assumptions.html
├── section1_chapter3_cognitive_biases.html
├── section1_chapter4_exposure_repetition_familiarity.html
├── section1_chapter5_confidence_certainty_feeling_of_knowing.html
├── section1_chapter7_closure_commitment_end_of_questioning.html
├── CS-001_Endless_Scroll_Funnel.html
├── CS-002_Assessment_Questionnaire.html
├── CS-003_Entry_Path_Framing.html
├── CS-004_Hedge_Fund_Acquisition_Engine.html
├── CS-005_The_Confession_Ad.html
└── CS-006_Campaign_Saturation_Perceived_Inevitability.html
```

### Skills Available
Located in `/mnt/skills/public/`:
- docx (document creation/editing)
- pdf (PDF manipulation)
- pptx (presentation creation)
- xlsx (spreadsheet creation)
- frontend-design (web UI design)
- product-self-knowledge (Anthropic product info)

---

## KEY PEOPLE & CONTEXT

**Alvin (Project Owner):**
- Australian, 64 years old
- English teacher, fled Ukraine war in 2022
- Now in Bulgaria as refugee
- Operates under GrumpyBum brand (financial worksheets)
- Writes under Sol Gardner pen name (17-book self-help series)
- Strong sense of justice, "hates injustice at all phases"
- Building this encyclopedia as reference tool, not marketing content

**Brand Voice:**
- Direct, plain-speaking
- Australian bluntness
- "Like a mate across the table"
- No BS, no fluff
- Grumpy but helpful

---

## SESSION STATISTICS

**Current Build:**
- **Sections completed:** 1 (full)
- **Encyclopedia chapters:** 6
- **Case studies:** 6
- **Total files:** 12
- **All navigation:** Bidirectional, functional
- **Token usage:** ~173,000 / 190,000 (91%)

**Quality status:** Production-ready, deployed to GitHub, live Monday

---

## CONTINUATION INSTRUCTIONS

When starting a new session:

1. **Read this document first**
2. **Verify locked templates** haven't been modified
3. **Check which section/chapter** is being requested
4. **Use appropriate template** (encyclopedia or case study)
5. **Follow quality checkpoints** before presenting files
6. **Maintain navigation standards** (bidirectional, chapter-level only)
7. **Never violate critical standards** (no intent, no judgment, no advice)

**Remember:**
- This is documentation, not persuasion
- Mechanism over motive, always
- Academic rigor for encyclopedia
- Observational voice for case studies
- SEO through quality + citations
- Slow organic growth, not marketing hype

**The foundation is solid. The system works. Keep building.**

---

END OF HANDOFF DOCUMENT