Now build a Skill from the approved Style Profile. Output it as a folder
structure with the full contents of each file.

STRUCTURE
my-writing-skill/
├── SKILL.md
└── references/
    ├── style-profile.md        (voice, tone, sentence/paragraph patterns)
    ├── analysis-framework.md   (my step-by-step method for reading and
    │                            evaluating literature)
    ├── structure-templates.md  (templates for each document type I write)
    ├── exemplars.md            (labeled excerpts from my real writing)
    └── negative-profile.md     (things I never do; patterns to avoid)

SKILL.md REQUIREMENTS
- YAML frontmatter with `name` and a `description` that states clearly WHAT
  the skill does and WHEN to trigger it (writing, rewriting, or analyzing
  academic literature in my voice).
- A concise workflow, in this order:
  1. INTAKE: Ask for the task, audience, length, citation style, and the
     source materials. Ask if anything is unclear.
  2. READ: Extract from each source: claim, method, evidence, assumptions,
     limitations. Use only what is actually in the source.
  3. ANALYZE: Apply analysis-framework.md to produce my likely
     interpretation, critique, and synthesis. Show these as brief notes
     before drafting.
  4. OUTLINE: Use the matching template in structure-templates.md.
  5. DRAFT: Write in my voice using style-profile.md and exemplars.md.
  6. SELF-EDIT: Check against negative-profile.md and the quantitative
     targets (sentence-length variation, paragraph rhythm, transition
     habits). Revise.
  7. FLAG: List what I must verify or add myself: claims needing checks,
     page numbers, places where my own opinion or experience is needed.
- Hard rules:
  * NEVER invent citations, quotations, data, or page numbers. If a source
    is not provided, say so and mark a placeholder.
  * Do not add arguments I would not make; mark any extrapolation as
    "[check: does this reflect your view?]"
  * Prioritize specificity (concrete details from the sources) over generic
    statements.
  * Match my imperfections and rhythm, not an idealized polish.
- Keep SKILL.md under ~500 lines; put detail in the reference files and
  tell the model when to read each one.

VALIDATION (do this before finalizing)
1. I will now give you the held-out sample's source material (not the
   sample itself). Write the piece using the Skill.
2. Then compare your output with my held-out sample on: sentence rhythm,
   paragraph structure, transitions, analytical moves, tone, vocabulary.
3. Score each dimension 1–10, list the specific mismatches, and update the
   Skill files to fix them. Repeat until all dimensions are 8+ or I tell
   you to stop.