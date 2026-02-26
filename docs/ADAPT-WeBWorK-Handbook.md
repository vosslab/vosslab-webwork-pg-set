# Table of Contents

- [01_Introduction/1.0-Index](#01-introduction10-index)
- [01_Introduction/1.1-What_is_WeBWorK](#01-introduction11-what-is-webwork)
- [01_Introduction/1.2-Why_use_WeBWorK](#01-introduction12-why-use-webwork)
- [01_Introduction/1.3-Key_Features_of_WeBWorK](#01-introduction13-key-features-of-webwork)
- [01_Introduction/1.4-Comparing_WeBWorK_to_other_formats](#01-introduction14-comparing-webwork-to-other-formats)
- [01_Introduction/1.5-Common_terms_and_names](#01-introduction15-common-terms-and-names)
- [01_Introduction/1.6-Quickstart_copy_edit_first_problem](#01-introduction16-quickstart-copy-edit-first-problem)
- [02_Problem_Generation_PG/2.0-Index](#02-problem-generation-pg20-index)
- [02_Problem_Generation_PG/2.1-Introduction_to_PG_Language](#02-problem-generation-pg21-introduction-to-pg-language)
- [02_Problem_Generation_PG/2.2-OPL_header_and_metadata](#02-problem-generation-pg22-opl-header-and-metadata)
- [02_Problem_Generation_PG/2.3-PG_Problem_Files_with_a_pg_file_extension](#02-problem-generation-pg23-pg-problem-files-with-a-pg-file-extension)
- [02_Problem_Generation_PG/2.4-Sections_within_a_PG_question](#02-problem-generation-pg24-sections-within-a-pg-question)
- [02_Problem_Generation_PG/2.5-Common_PG_Macros](#02-problem-generation-pg25-common-pg-macros)
- [02_Problem_Generation_PG/2.6-Legacy_PG_and_deprecated_patterns](#02-problem-generation-pg26-legacy-pg-and-deprecated-patterns)
- [02_Problem_Generation_PG/2.7-Future_PG_Version_Features](#02-problem-generation-pg27-future-pg-version-features)
- [03_PGML_PG_Markup_Language/3.0-Index](#03-pgml-pg-markup-language30-index)
- [03_PGML_PG_Markup_Language/3.1-Introduction_to_PGML](#03-pgml-pg-markup-language31-introduction-to-pgml)
- [03_PGML_PG_Markup_Language/3.2-Answer_blanks_and_answers](#03-pgml-pg-markup-language32-answer-blanks-and-answers)
- [03_PGML_PG_Markup_Language/3.3-Lists_and_workflows](#03-pgml-pg-markup-language33-lists-and-workflows)
- [03_PGML_PG_Markup_Language/3.4-Tables_and_structured_data](#03-pgml-pg-markup-language34-tables-and-structured-data)
- [03_PGML_PG_Markup_Language/3.5-Layout_controls](#03-pgml-pg-markup-language35-layout-controls)
- [03_PGML_PG_Markup_Language/3.6-Command_substitution_and_inserts](#03-pgml-pg-markup-language36-command-substitution-and-inserts)
- [04_Breaking_Down_the_Components/4.0-Index](#04-breaking-down-the-components40-index)
- [04_Breaking_Down_the_Components/4.1-Full_file](#04-breaking-down-the-components41-full-file)
- [04_Breaking_Down_the_Components/4.2-OPL_Header](#04-breaking-down-the-components42-opl-header)
- [04_Breaking_Down_the_Components/4.3-Preamble](#04-breaking-down-the-components43-preamble)
- [04_Breaking_Down_the_Components/4.4-Setup](#04-breaking-down-the-components44-setup)
- [04_Breaking_Down_the_Components/4.5-Statement](#04-breaking-down-the-components45-statement)
- [04_Breaking_Down_the_Components/4.6-Solution](#04-breaking-down-the-components46-solution)
- [04_Breaking_Down_the_Components/4.7-Putting_it_together](#04-breaking-down-the-components47-putting-it-together)
- [05_Different_Question_Types/5.0-Index](#05-different-question-types50-index)
- [05_Different_Question_Types/5.1-Question_types_overview](#05-different-question-types51-question-types-overview)
- [05_Different_Question_Types/5.2-Multiple_choice](#05-different-question-types52-multiple-choice)
- [05_Different_Question_Types/5.3-Multiple_answer](#05-different-question-types53-multiple-answer)
- [05_Different_Question_Types/5.4-Matching](#05-different-question-types54-matching)
- [05_Different_Question_Types/5.5-Numerical_entry](#05-different-question-types55-numerical-entry)
- [05_Different_Question_Types/5.6-Fill_in_the_blank](#05-different-question-types56-fill-in-the-blank)
- [05_Different_Question_Types/5.7-Multi_part_fill_in_the_blank](#05-different-question-types57-multi-part-fill-in-the-blank)
- [05_Different_Question_Types/5.8-Ordered_list](#05-different-question-types58-ordered-list)
- [05_Different_Question_Types/5.9-Workflow_and_QA_in_ADAPT](#05-different-question-types59-workflow-and-qa-in-adapt)
- [06_Advanced_PGML_Techniques/6.0-Index](#06-advanced-pgml-techniques60-index)
- [06_Advanced_PGML_Techniques/6.1-Text_Coloring_and_Emphasis](#06-advanced-pgml-techniques61-text-coloring-and-emphasis)
- [06_Advanced_PGML_Techniques/6.2-Making_Tables_with_niceTables](#06-advanced-pgml-techniques62-making-tables-with-nicetables)
- [06_Advanced_PGML_Techniques/6.3-Making_Graphs](#06-advanced-pgml-techniques63-making-graphs)
- [06_Advanced_PGML_Techniques/6.4-Advanced_Randomization_Techinques](#06-advanced-pgml-techniques64-advanced-randomization-techinques)
- [06_Advanced_PGML_Techniques/6.5-Randomized_Matching_Problems](#06-advanced-pgml-techniques65-randomized-matching-problems)
- [06_Advanced_PGML_Techniques/6.6-Randomized_MC_True_False_Statements](#06-advanced-pgml-techniques66-randomized-mc-true-false-statements)
- [06_Advanced_PGML_Techniques/6.7-Rendering_Chemical_Structures_with_RDKit](#06-advanced-pgml-techniques67-rendering-chemical-structures-with-rdkit)
- [06_Advanced_PGML_Techniques/6.8-Displaying_Chemical_Formulas_with_mhchem](#06-advanced-pgml-techniques68-displaying-chemical-formulas-with-mhchem)
- [07_Testing_and_Debugging/7.0-Index](#07-testing-and-debugging70-index)
- [07_Testing_and_Debugging/7.1-Simple_Syntax_Checking_Linting_in_WeBWork](#07-testing-and-debugging71-simple-syntax-checking-linting-in-webwork)
- [07_Testing_and_Debugging/7.2-Setting_Up_the_PG_Renderer](#07-testing-and-debugging72-setting-up-the-pg-renderer)
- [07_Testing_and_Debugging/7.3-Scripting_and_Automation_of_the_PG_Renderer](#07-testing-and-debugging73-scripting-and-automation-of-the-pg-renderer)
- [07_Testing_and_Debugging/7.4-Common_Mistakes_and_How_to_Fix_Them](#07-testing-and-debugging74-common-mistakes-and-how-to-fix-them)
- [07_Testing_and_Debugging/7.5-Testing_Randomization_and_Edge_Cases](#07-testing-and-debugging75-testing-randomization-and-edge-cases)
- [07_Testing_and_Debugging/7.6-QA_Checklist_Before_Publishing](#07-testing-and-debugging76-qa-checklist-before-publishing)
- [08_Using_AI_Agents_to_Write_WeBWorK/8.0-Index](#08-using-ai-agents-to-write-webwork80-index)
- [08_Using_AI_Agents_to_Write_WeBWorK/8.1-What_are_AI_Agents](#08-using-ai-agents-to-write-webwork81-what-are-ai-agents)
- [08_Using_AI_Agents_to_Write_WeBWorK/8.2-Knowledge_Documents_for_AI_Agents](#08-using-ai-agents-to-write-webwork82-knowledge-documents-for-ai-agents)
- [08_Using_AI_Agents_to_Write_WeBWorK/8.3-Connecting_AI_Agents_to_the_PG_Renderer](#08-using-ai-agents-to-write-webwork83-connecting-ai-agents-to-the-pg-renderer)
- [08_Using_AI_Agents_to_Write_WeBWorK/8.4-Advance_AI_Agents_Advice](#08-using-ai-agents-to-write-webwork84-advance-ai-agents-advice)
- [90_Appendices/90.0-Index](#90-appendices900-index)
- [90_Appendices/90.1-Minimal_templates](#90-appendices901-minimal-templates)
- [90_Appendices/90.2-Glossary](#90-appendices902-glossary)
- [90_Appendices/90.3-Troubleshooting_checklist](#90-appendices903-troubleshooting-checklist)
- [90_Appendices/90.4-Macro_Demonstrations](#90-appendices904-macro-demonstrations)

---

# 01_Introduction/1.0-Index

There are plenty of guides for writing mathematics assessment questions
in WeBWorK. This guide takes a different approach and is written for
people in the sciences and other descriptive fields, especially in the
life sciences.

This book assumes you want questions that read like real lab and lecture
tasks, grade reliably, and are easy to reuse across semesters.

This book assumes you are a domain expert, not a software developer. The
patterns shown here are designed so that you can reason about biology
first and let the templates handle the mechanics.

This guide is based on the PG 2.17 subset used in ADAPT and
webwork-pg-renderer, so some macros from full WeBWorK installs are not
available. Use the macro allowlist reference in Chapter 2.4 before you
try to load new interaction macros.

## On this page

  -----------------------------------------------------------------------
  Section               What it covers
  --------------------- -------------------------------------------------
  What this guide       The PGML-first mindset, science-first tone, and
  emphasizes            subset constraints.

  PG vs PGML (a         A concrete rule of thumb for what goes where.
  practical split)      

  Where to start today  A task-to-chapter map for quick entry.

  Apply it today        Two actions you can take immediately.
  -----------------------------------------------------------------------

## What this guide emphasizes

- PGML-first authoring: write the student-facing prompt in PGML and keep
  regular PG as short setup code for values and answer checking.
- Life-science style prompts: short narratives, concentrations and
  dilution workflows, structured data, and interpretation questions that
  match how biology is taught and practiced.
- Practical reuse: stable patterns you can clone and copy-edit to build
  question banks quickly without breaking grading.
- Subset-aware authoring: the ADAPT and webwork-pg-renderer PG 2.17
  subset lacks some macros, so check the allowlist in Chapter 2.4 before
  adding new interaction types.

## PG vs PGML (a practical split)

  ------------------------------------------------------------------------
  Layer        Use it for                    Avoid using it for
  ------------ ----------------------------- -----------------------------
  PG (setup)   Macros, context, variables,   Long prompt text, hand-built
               answer checkers.              formatting.

  PGML         Student-facing sentences,     Hidden logic and heavy
  (prompt)     math, tables, blanks.         computation.
  ------------------------------------------------------------------------

## Where to start today

This guide is organized as short pages you can read out of order. Pick
the path that matches what you are doing today.

  -------------------------------------------------------------------------
  If you are doing this    Start here               What you get
  today                                             
  ------------------------ ------------------------ -----------------------
  Make one working problem [Chapter                 A safe copy-edit loop
  fast                     1.6](/@go/page/555187)   and a minimal working
                                                    skeleton.

  Set up a new file        [Chapter                 Minimal scaffolding
  correctly                2](/@go/page/488655)     that stays readable.

  Write or edit the prompt [Chapter                 PGML patterns for
  text                     3](/@go/page/488660)     blanks, lists, tables.

  Understand the anatomy   [Chapter                 OPL header plus four
  of a full problem        4](/@go/page/488661)     sections in one worked
                                                    example.

  Pick an interaction type [Chapter                 A catalog of common
                           5](/@go/page/488662)     question types.

  Build biology-first      [Chapter                 Advanced PGML
  patterns                 6](/@go/page/488663)     techniques for HTML,
                                                    tables, and matching.

  Fix a generic ADAPT      [Chapter                 Local rendering with
  error                    7](/@go/page/555731)     line-level error
                                                    messages.
  -------------------------------------------------------------------------

If you want a quick vocabulary reset before you start, use [Chapter
1.5](/@go/page/555734) for the common terms used throughout the book.

## Apply it today

- Pick one page that matches what you are building today and copy-edit
  the example rather than starting from scratch.
- Keep regular PG minimal and write student-facing sentences in PGML.

{{template.ShowOrg()}}

---

# 01_Introduction/1.1-What_is_WeBWorK

WeBWorK delivers automatically graded questions to students through a
web interface. As an author, you write a text-based problem file
(usually a `.pg` file) that defines values, a prompt, answer blanks, and
grading rules.

A single problem can randomize values, present structured data, collect
student answers, and grade them immediately. In this guide, regular PG
is treated as the setup layer and PGML is treated as the student-facing
prompt (see [Chapter 2](/@go/page/488655) for more on PG).

This book targets the PG 2.17 subset used in ADAPT and
webwork-pg-renderer, which means some macros found in full WeBWorK
installs are not available. Keep that constraint in mind when you see
online examples that load macros you do not recognize (see [Section
1.5](/@go/page/555734) for common terms).

## PGML-first rule of thumb

WeBWorK problems are written in a language called PG, but most authors
should treat \"regular PG\" as the plumbing that sets up variables and
answer checkers. The student-facing prompt should be written in PGML (PG
Markup Language), which is designed to replace older `BEGIN_TEXT`
authoring.

Rule of thumb: if it is a sentence the student reads, it belongs in
PGML.

- PG (minimal): load macros, choose contexts, define random values, and
  build MathObjects.
- PGML (primary): write the prompt, math, tables, and answer blanks
  using readable markup.

You should be able to edit most biology questions in this book without
fully understanding the PG setup code, as long as you keep changes
inside the PGML block.

## Why it works well for life sciences

- Short prompts with structured data (tables, concentrations, rates, and
  units).
- Algorithmic variants for repeated practice without reusing the same
  numbers.
- Clear answer checking via MathObjects (numeric, formulas, lists, and
  recognition checks).
- Clean prompts for common biology patterns (dilutions, fold change, and
  small data tables).

## Apply it today

- Write one prompt sentence in PGML and move any student-facing text out
  of regular PG.
- Pick one biology-native pattern (a dilution, a rate, or a fold change)
  and randomize only the numbers.

Next step: read [Section 1.2](/@go/page/488653) to decide when a prompt
belongs in WeBWorK and when a simpler tool is a better fit.

---

# 01_Introduction/1.2-Why_use_WeBWorK

WeBWorK is useful when you want repeated, low-friction practice with
immediate feedback and consistent grading. In science courses, the
strength is not \"more math\", but rather repeatable workflows for
concentrations, dilutions, rates, fold change, and small data tables
inside realistic prompts.

## Choose WeBWorK when

- You want repeated practice with immediate feedback and consistent
  grading.
- You want algorithmic variants where only the numbers change, not the
  story.
- You want explicit answer checking (tolerances, formats, and controlled
  text variants).
- You want prompts that mix text, values, and structured data without
  fragile formatting.

## Choose something else when

- The task depends on rich interaction that is better served by a
  dedicated widget or simulation.
- The assessment is primarily writing or multi-step reasoning that is
  not a good fit for auto-grading.
- You need a standardized export/import workflow and accept the
  constraints of an LMS package format.

WeBWorK is a good fit when you want students to calculate, interpret, or
compare values, but a poor fit for long written explanations or diagram
drawing.

## Why PGML matters

While a WeBWorK problem is \"a PG file\", this guide discourages writing
long blocks of text in regular PG. PGML is designed so that the prompt
reads like the rendered output, and answer blanks can be tied directly
to answers in the same place you write the question.

- Readable prompts with inline and display math.
- Answer blanks like `[_____]{...}` that stay close to the text they
  grade.
- Variable substitution that formats MathObjects correctly in TeX or
  calculator notation.

## Science-friendly patterns

- Use a short narrative plus a table of measurements.
- Ask for one computed quantity with clear units and controlled
  rounding.
- Include one or two recognition checks (multiple choice or matching)
  when appropriate (see [Chapter 5](/@go/page/488662) for question
  types).
- Prefer small, constrained randomizations over complicated logic.
- Reuse a stable template so future edits stay small and predictable.

## Tradeoffs to be honest about

- There is setup cost (macros, contexts, and answer checkers),
  especially for new authors.
- Randomization needs constraints and previewing, or you will generate
  broken variants.
- Format decisions (units, rounding, accepted text variants) must be
  stated to avoid grading disputes.

## Apply it today

- Pick one life-science workflow (a dilution, a rate, or a fold change)
  and write the prompt in PGML.
- Write down the reporting rule (units and rounding) next to the answer
  blank.

## How WeBWorK compares (briefly)

Other systems can also deliver automated questions (for example H5P
interactive content, standardized LMS-import item packages, and
LMS-native quiz questions). The main reason to choose WeBWorK in a
science course is when you want robust answer parsing and checking
(MathObjects), repeatable algorithmic variants, and clear, readable
prompt authoring via PGML.

For a more detailed comparison and \"choose this when\" guidance, see
[Section 1.4](/@go/page/555107).

---

# 01_Introduction/1.3-Key_Features_of_WeBWorK

WeBWorK\'s power is not a single feature, but a stable combination:
algorithmic question setup, structured answer checking, and readable
authoring of the student prompt.

## What matters for authors

- PGML for prompt authoring (recommended): readable markup, math
  delimiters, and answer blanks (see [Chapter 3](/@go/page/488660)).
- MathObjects for robust parsing and checking of student answers
  (numeric, formulas, lists).
- Randomization primitives (e.g., `random()`) to generate variants while
  keeping the scoring rules identical (see [Section
  6.5](/@go/page/555727)).
- Multiple answer interaction types via macros (numeric answers,
  formulas, radio buttons, etc.).

If you are new, focus first on PGML, numeric answer checking, and
fixed-seed previewing (see [Chapter 7](/@go/page/555731) for testing and
debugging); everything else can wait.

Use this page as a checklist when you plan a new problem so you do not
overbuild the setup.

## What matters for life-science prompts

- Prompts that mix words, values, and math without fragile escaping.
- Tables for small datasets (measurements, lanes, conditions) in a
  readable format.
- Common biology workflows such as concentrations, dilutions, rates, and
  fold change.
- Clear expectations about units, rounding, and accepted formats to
  reduce grading disputes.

## Tradeoffs and constraints

- There is setup cost (macros, contexts, and answer checkers), so
  templates matter.
- Randomization needs constraints and previewing to avoid broken
  variants.
- Auto-grading is only as clear as your reporting rules (units,
  rounding, accepted text variants).

## Apply it today

- Pick the interaction first, then keep setup minimal and write the
  student-facing prompt in PGML.
- Write one biology-native task (a dilution, a rate, or a fold change)
  and decide the reporting rule up front.

Next step: use [Section 1.4](/@go/page/555107) to choose WeBWorK versus
another format for a specific activity.

---

# 01_Introduction/1.4-Comparing_WeBWorK_to_other_formats

Many platforms support automated or semi-automated assessment. The goal
of this section is not to rank tools, but to help you choose the right
tool for the learning outcome and the workflow you want for students and
instructors.

Most life-science courses use more than one assessment tool; this book
assumes WeBWorK is one piece of that ecosystem, not the entire solution.

## Quick comparison

  -----------------------------------------------------------------------
  Format          Best for                    Tradeoffs
  --------------- --------------------------- ---------------------------
  WeBWorK         Robust answer checking,     Requires some author setup
  (PGML-first)    algorithmic variants, and   (macros, contexts,
                  science prompts that mix    MathObjects); best results
                  text, values, math, and     come from using templates
                  tables.                     and keeping setup small.

  WeBWorK author  Fast debugging when ADAPT   Requires local renderer
  workflow        is opaque, using local      setup ([Chapter
                  rendering for line-level    7](/@go/page/555731)) while
                  errors.                     still using ADAPT preview
                                              as the final check.

  H5P interactive Highly interactive          Answer checking is often
  content         activities, quick           pattern-based or limited to
                  engagement checks, and      the widget type;
                  media-rich prompts with a   algorithmic variants and
                  low barrier to entry.       strict parsing can be
                                              harder.

  Standardized    Portability across LMS      Question types and scoring
  item packages   systems and standardized    can be constrained by the
                  quiz import/export          LMS; complex parsing or
                  workflows.                  custom checks are often
                                              limited.

  LMS-native      Simple quizzes tightly      Authoring is
  question banks  integrated with grades, due platform-specific;
                  dates, and course           algorithmic and
                  logistics.                  formula-based grading can
                                              be limited or inconsistent
                                              across platforms.

  IMathAS /       Algorithmic questions with  Authoring conventions
  similar systems established patterns and    differ; migrating content
                  large existing libraries.   between systems may require
                                              rewrites.
  -----------------------------------------------------------------------

## Why WeBWorK is a good fit for sciences

- **Science-style prompts**: short narrative plus explicit numbers,
  units, and often a small table of data.
- **Robust answer checking**: MathObjects parse student input and can
  enforce format, tolerances, and domain restrictions.
- **PGML for readability**: the prompt is written in a markup style that
  stays close to what students see, which helps maintainability.
- **Safe randomization**: randomize values while keeping the story and
  scoring rules stable.

## Choose WeBWorK when

- You want multiple algorithmic versions of the same question.
- You want students to enter values or formulas in a structured way.
- You want to grade based on meaning, not only string matching.
- You want to reuse and version-control questions as text files.

## Choose something else when

- The learning outcome depends on rich interaction that is better served
  by a dedicated widget (platform-specific drag-and-drop, hotspots,
  complex UI interactions).
- You need a standardized export/import workflow and are comfortable
  with the constraints of the target LMS.
- The assessment is primarily writing or multi-step reasoning where
  auto-grading is not the main goal.

## A practical hybrid approach

Many courses mix tools:

- Use WeBWorK for numeric and formula-based practice with clear
  feedback.
- Use interactive activities for concept exploration or lab technique
  simulations.
- Use writing tools or projects for synthesis and communication skills.

This book focuses on WeBWorK with a PGML-first workflow. Treat regular
PG as minimal setup code needed to support a clear PGML prompt.

## Apply it today

- Pick one activity and decide whether you need robust parsing and
  grading, or whether a simpler format is enough.
- If you choose WeBWorK, start from a template and keep setup small.

Next step: use [Chapter 5](/@go/page/488662) to pick an interaction
pattern (multiple choice, matching, numerical entry, or
fill-in-the-blank).

---

# 01_Introduction/1.5-Common_terms_and_names

This page defines the short list of terms you will see repeatedly in
this book. The goal is to make the later chapters easier to read without
stopping to decode vocabulary.

The terms are grouped into authoring terms and platform terms. Do not
memorize these; return here when a term blocks your progress.

## Common terms used in this book

  ---------------------------------------------------------------------------------------
  Term                         Meaning (in plain language)   Why you care while authoring
  ---------------------------- ----------------------------- ----------------------------
  **WeBWorK authoring**        Terms you will see inside     These are the knobs you
                               problem files.                touch most often.

  [PG](/@go/page/488655)       The problem-file language     In this book, PG stays
                               that WeBWorK runs.            minimal and supports the
                                                             PGML prompt.

  [PGML](/@go/page/488660)     A markup layer inside PG for  Most text, structure, and
                               writing the student prompt.   blanks should live here.

  [Macros](/@go/page/488659)   Reusable code libraries       Macros enable question
                               loaded by a problem file.     types, answer checkers, and
                                                             PGML features.

  MathObjects                  Typed answer objects          They make checking reliable
                               (numbers, formulas, lists)    and reduce string-matching
                               used for grading.             errors.

  Context                      Rules that control what       Wrong Context is a common
                               student input is allowed.     cause of unexpected grading.

  Answer checker               The rule used to decide       Tolerances and formats
                               whether an answer is correct. usually live here.

  Seed                         A number that reproduces one  Seeds let you debug the
                               randomized variant.           exact failing version.

  **ADAPT and LibreTexts       Platform terms used in ADAPT  Useful when you navigate,
  platform**                   and LibreTexts.               share, or troubleshoot.

  ADAPT                        LibreTexts\' assessment and   This is where you assign
                               adaptive learning system.     questions to students and
                                                             manage delivery.

  WeBWorK                      An open-source homework       This book focuses on WeBWorK
                               system used heavily in math   problems that run inside
                               and science.                  ADAPT.

  OPL (Open Problem Library)   A large, shared library of    Great for patterns and macro
                               WeBWorK problems maintained   references, but it has
                               by the community.             little life-science content.

  H5P                          A framework for interactive   Useful for some prompts, but
                               questions used in ADAPT.      less suited to algorithmic
                                                             parsing.

  Commons                      LibreTexts\' library of       Where course content and
                               shared pages and resources.   shared assets are often
                                                             stored.

  Insight                      LibreTexts\' knowledge base   Where platform help and
                               and documentation hub.        policies usually live.

  Studio                       LibreTexts\' repository for   Often where non-WeBWorK
                               H5P questions and media.      items are stored and shared.
  ---------------------------------------------------------------------------------------

For platform-wide definitions beyond this quick list, consult the
LibreTexts glossary used by your campus.

## Open Problem Library (OPL): value and gaps

The Open Problem Library (OPL) is a large public set of WeBWorK problems
that is invaluable for learning common patterns, macro combinations, and
interaction styles. It is also a reality check for what question types
exist in the wild and how authors structure PG and PGML.

Our 2026-01-17 corpus audit of the full OPL found that the subject mix
is dominated by math and that there are no life_sciences DBsubject tags,
with bio-ish term hits showing up in only about 0.3% of files. That
means the OPL is not a strong source of life-science problem content,
even though it is a rich source of structure.

In this book, we use the OPL to:

- Spot reliable PGML patterns and macro combinations.
- Set realistic expectations for interaction types and widget choices.
- Build safer authoring checklists that avoid legacy patterns.

## Apply it today

- When a term is unfamiliar, return here before you change macros or
  grading rules.
- Use a fixed seed to reproduce any issue you need to debug.

---

# 01_Introduction/1.6-Quickstart_copy_edit_first_problem

This quickstart is designed to give you a complete win early: take a
working PGML-first problem, copy it, and make a small edit that still
grades correctly.

## Quickstart steps

1.  Copy a working template problem (start from [Chapter
    4](/@go/page/488661) if you have one available).
2.  Change only the story text first, keeping the variable names and
    math intact.
3.  Preview multiple variants to confirm the prompt still makes sense.
4.  Then change the numbers or the formula, one small change at a time.

Do not start by changing variable names or answer objects; change text
first.

## A minimal PGML-first skeleton (for copy-editing)

The file below is intentionally complete and minimal: it includes
macros, setup, a PGML prompt, and an answer blank tied directly to its
answer object.


    DOCUMENT();

    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    Context("Numeric");

    $a = random(2, 8, 1);
    $b = random(3, 9, 1);
    $ans = Real($a + $b);

    BEGIN_PGML
    In a lab notebook, two counts were recorded: [$a] and [$b].

    What is the total count?

    [`Total = `] [________]{$ans}
    END_PGML

    ENDDOCUMENT();

After you can copy-edit a problem like this without breaking grading,
you are ready to expand into tables, multi-part prompts, and tighter
answer checking.

## Apply it today

- Copy a working file, change one small thing, and preview multiple
  variants before changing anything else.
- Keep student-facing sentences in PGML and keep regular PG focused on
  values and answer checking.
- After copy-editing, preview in ADAPT, and if ADAPT reports only a
  generic error, use [Chapter 7](/@go/page/555731) (webwork-pg-renderer)
  to get a line-level error and fix it fast.

Next step: use [Chapter 2](/@go/page/488655) to adopt a consistent file
structure, then use [Chapter 4](/@go/page/488661) as your first reusable
template.

---

# 02_Problem_Generation_PG/2.0-Index

This page only covers the PG you need to support a PGML prompt.

## Start here (task first)

- I need to add metadata headers (OPL) -\> [Section
  2.2](/@go/page/557378).
- I need a clean starter .pg skeleton -\> [Section
  2.3](/@go/page/488657).
- I need to know where setup ends and PGML begins -\> [Section
  2.4](/@go/page/488658).
- My problem does not render, missing macro or context? -\> [Section
  2.5](/@go/page/488659).
- I copied code from the internet and it looks weird -\> [Section
  2.6](/@go/page/555742).
- I see a feature online that does not work in ADAPT -\> Section 2.7.

If you are copy-editing a working problem, you can skip this chapter and
come back only when you need to change setup behavior.

WeBWorK problems are written in PG (see [Section 2.1](/@go/page/488656)
for an introduction), but this guide is not trying to turn instructors
into Perl developers. Regular PG is treated as the minimum setup needed
to support a clean PGML prompt: define a few variables, define answer
checkers, and let PGML carry the student-facing text.

Library-quality problems also need an OPL header section that comes
before `DOCUMENT()`, so the five-section reality is: OPL header,
Preamble, Setup, Statement, and Solution.

## What PG is used for in this guide

- Load the macros needed for PGML and answer checking.
- Choose a MathObjects context that matches the expected input.
- Generate a small number of randomized values with sensible ranges.
- Compute the target answer(s) and attach the right answer checkers.

## What regular PG is not used for in this guide

- Writing the prompt as long blocks of `BEGIN_TEXT/END_TEXT`.
- Building complex formatting by hand (PGML is preferred).
- Turning a single problem into a large Perl script.

If a problem feels like it needs complexity, prefer clearer prompts,
tighter ranges, or a different interaction pattern before adding more PG
logic.

## How this chapter fits the book

Chapter 2 exists because every PGML problem still needs some PG
scaffolding ([macros](/@go/page/488659), variables, answers). The goal
is to keep that scaffolding short, readable, and reusable.

{{template.ShowOrg()}}

---

# 02_Problem_Generation_PG/2.1-Introduction_to_PG_Language

PG is the programming language behind every WeBWorK problem. It is
implemented in Perl and provides macros for answer checking,
randomization, and formatting. Think of PG as the scaffolding that
supports the student-facing prompt: it loads the tools you need, sets up
variables, and wires the grading, but the text the student actually
reads belongs in PGML.

This page covers only the PG you need to support a PGML prompt. If you
can read this page, you already know enough PG to write most science and
math problems. Set up a local renderer to test your work ([Section
7.1](/@go/page/555732)).

**Use this page when:** you need to change setup behavior without
touching the student-facing prompt.

## The five-component problem structure

Every PG problem file follows the same five components, in order.
Keeping this structure consistent makes problems easier to read, debug,
and share.

1.  **OPL header**: metadata comments for searchability and attribution
    (covered in Section 2.2; see also [Chapter 4](/@go/page/488661) for
    a detailed component breakdown).
2.  **Preamble**: `DOCUMENT();` and `loadMacros(...)`.
3.  **Setup**: context selection, random values, computed answers, and
    answer checkers.
4.  **Statement**: the PGML text block that the student reads and
    interacts with (see [Chapter 3](/@go/page/488660) for PGML details).
5.  **Solution**: a solution block (and optional hints) for student
    review.

## Canonical problem skeleton

Copy this skeleton and fill in the pieces you need.


    ## (Tagging header block goes here -- see Section 2.2)

    DOCUMENT();

    # ----------------------------
    # 1) Preamble
    # ----------------------------
    loadMacros(
      "PGstandard.pl",
      "MathObjects.pl",
      "PGML.pl",
      "PGcourse.pl",
    );

    $showPartialCorrectAnswers = 1;

    # ----------------------------
    # 2) Setup
    # ----------------------------
    Context("Numeric");
    $a = random(2, 9, 1);
    $b = random(3, 9, 1);
    $ans = Compute("$a + $b");

    # ----------------------------
    # 3) Statement (PGML)
    # ----------------------------
    BEGIN_PGML
    Compute [`[$a] + [$b]`].

    Answer: [__________]{$ans}
    END_PGML

    # ----------------------------
    # 4) Solution
    # ----------------------------
    BEGIN_PGML_SOLUTION
    The answer is [`[$a] + [$b] = [$ans]`].
    END_PGML_SOLUTION

    ENDDOCUMENT();

## Key rules

- Every file must start with `DOCUMENT();` and end with
  `ENDDOCUMENT();`.
- Put all macro loads in a single `loadMacros(...)` block in the
  preamble.
- All student-facing text goes inside `BEGIN_PGML` / `END_PGML` blocks.
  Do not write long prompts in raw PG.
- Always include a `BEGIN_PGML_SOLUTION ... END_PGML_SOLUTION` block,
  even if it is only a single sentence.
- Keep the five sections in order and visually separated with comment
  headings.

## Minimum recommended macros

Start every problem with these four macros. Add others only when you
need them.

  -----------------------------------------------------------------------
  Macro                 Purpose
  --------------------- -------------------------------------------------
  `PGstandard.pl`       Core PG functions; required in practice for every
                        problem.

  `MathObjects.pl`      Modern answer types such as `Real()`,
                        `Compute()`, and `Formula()`.

  `PGML.pl`             Enables `BEGIN_PGML` / `END_PGML` blocks for
                        writing prompts.

  `PGcourse.pl`         Commonly expected by WeBWorK installations;
                        include unless you have a reason to drop it.
  -----------------------------------------------------------------------

If you add a specialized macro (for example `parserPopUp.pl` for
dropdowns), add a short comment explaining why.

## PGML-first authoring

In PGML-first problems, the student-facing text and answer blanks live
entirely inside PGML blocks. PG handles everything that happens before
and after the prompt: loading macros, choosing a context, generating
random values, and defining correct answers.

**Inline grading principle:** attach answer evaluators directly to
blanks in the PGML block. Do not create a blank in PGML and then wire
the grader separately with `ANS(...)` calls.


    # Preferred: evaluator attached at the blank
    BEGIN_PGML
    Answer: [__________]{$ans}
    END_PGML

    # Avoid: blank in PGML with separate ANS() wiring
    BEGIN_PGML
    Answer: [__________]
    END_PGML
    ANS($ans->cmp());

When the evaluator lives next to the blank, the connection between the
prompt and the grading stays obvious. This is especially helpful for
problems with multiple answer blanks.

## File extensions: .pgml vs .pg

Use the `.pgml` extension for full PGML-first problems where the
statement and graders are entirely inside PGML blocks. If a problem uses
legacy `ANS(...)` wiring or mixed PG/PGML structure, keep the extension
as `.pg`. The extension signals whether tooling should expect pure PGML
structure.

## Context selection

A context controls what kind of input WeBWorK accepts from the student.
Always set an explicit context in the Setup section before defining
answers.

  -----------------------------------------------------------------------
  Context           When to use
  ----------------- -----------------------------------------------------
  `Numeric`         General numeric answers (the most common default).

  `Real`            Answers that must be real numbers (no complex
                    values).

  `Vector`          Answers that are vectors.

  `Matrix`          Answers that are matrices.

  `Complex`         Answers that involve complex numbers.
  -----------------------------------------------------------------------

## Question order recommendation

Inside the PGML block, present information in this order so that
questions are consistent and scannable for students.

1.  **Background**: context or scenario the student needs to understand.
2.  **Statement**: what is being asked.
3.  **Data**: any tables or given values.
4.  **Directions**: how to respond, constraints, formatting
    expectations.

Keep directions concise and place them after the data or statement
rather than before the prompt.

## PG concepts you actually need

  -----------------------------------------------------------------------
  PG concept          Why you care                 What you type
  ------------------- ---------------------------- ----------------------
  Macro loading       Enables PGML and answer      `loadMacros(...)`
                      checking.                    

  Context             Controls what student input  `Context("Numeric")`
                      is allowed.                  

  Random values       Creates variants without     `random(2, 8, 1)`
                      changing the story.          

  MathObjects         Builds answers the grader    `Real(...)` or
                      can check.                   `Compute(...)`

  Answer checker      Defines how grading works.   `$ans->cmp()`
  -----------------------------------------------------------------------

## Common failure and fix


    Broken: $ans = Real($a + $b);
    What you will see: Undefined subroutine &main::Real called
    Fix: load "MathObjects.pl" before using Real(...)

## A mindset for science problems

- Randomize the values, not the story.
- Keep units explicit and consistent (and prevent unit drift: μM vs mM,
  μL vs mL).
- Use realistic ranges (no negative concentrations, no 10,000 μL
  pipettes).
- For text answers, state naming expectations (gene/protein symbols,
  case, and hyphens).
- Prefer one or two answer blanks with clear interpretation.
- When you need a table or structured layout, reach for PGML helpers
  rather than ad-hoc HTML.

## Safe defaults (micro-pattern)

- Choose a context early.
- Define a small set of values with constrained ranges.
- Define answers as MathObjects.
- Attach answers directly to blanks in PGML.

You can stop here if you are only editing prompts or adding one numeric
value. This page is enough to keep your PG setup stable.

**Next, depending on what you are doing:**

- Need the OPL header? Go to [Section 2.2](/@go/page/557378).
- Need a clean starter .pg skeleton? Go to [Section
  2.3](/@go/page/488657).
- Not sure where setup ends and PGML begins? Go to [Section
  2.4](/@go/page/488658).
- Need macro help? Go to [Section 2.5](/@go/page/488659).

---

# 02_Problem_Generation_PG/2.2-OPL_header_and_metadata

The OPL header is the metadata block that comes before `DOCUMENT()` and
makes a problem searchable, classifiable, and reusable. In this guide,
the header is treated as a real section (\"section zero\") even though
traditional PG documentation only lists four sections.

**Use this page when:** you are creating a new problem or adapting an
existing one and need correct metadata for long-term reuse.

Use the templates in Appendix 90.1 as your starting point so you do not
forget required fields.

## Required and recommended fields

  -----------------------------------------------------------------------------------
  Field                             Status                   Why it matters
  --------------------------------- ------------------------ ------------------------
  `TITLE('...')`                    Required                 Short, student-facing
                                                             title used in search and
                                                             listings.

  `DESCRIPTION` block               Required                 Two to three sentences
                                                             describing the task and
                                                             constraints.

  `KEYWORDS(...)`                   Strongly recommended     Improves search and
                                                             grouping across a bank.

  `DBsubject/DBchapter/DBsection`   Strongly recommended     Primary classification
                                                             tags for the Open
                                                             Problem Library.

  `Level(...)`                      Required                 Bloom\'s taxonomy level
                                                             (1-6) for difficulty
                                                             classification.

  Attribution fields                Recommended              Credits authors and
                                                             institutions for
                                                             long-term reuse.

  `Language(en)`                    Required                 ISO 639-1 code
                                                             specifying the problem
                                                             language.
  -----------------------------------------------------------------------------------

## Copy and edit (OPL header template)


    ## TITLE('Short descriptive title')
    ## DESCRIPTION
    ## One to three sentences describing the task and constraints.
    ## ENDDESCRIPTION
    ## KEYWORDS('keyword1','keyword2','keyword3')
    ## DBsubject('Biochemistry')
    ## DBchapter('Enzymes')
    ## DBsection('Kinetics basics')
    ## Level(2)
    ## Date('2026-01-28')
    ## Author('Author name')
    ## Institution('Institution name')
    ## Language(en)

## TITLE field guidance

The TITLE is the student-facing name that appears in problem listings
and search results. Keep it short (under 80 characters), descriptive,
and focused on the task rather than the story wrapper.

### Good vs bad titles

  -----------------------------------------------------------------------------------------------------------------------------------------------------------
  Good title                                                     Bad title                                                                     Why
  -------------------------------------------------------------- ----------------------------------------------------------------------------- --------------
  `Compute dilution factor from stock and final concentration`   `This is a problem about dilutions in the lab`                                Bad: filler
                                                                                                                                               words, says
                                                                                                                                               \"problem\",
                                                                                                                                               not
                                                                                                                                               task-focused

  `X-linked inheritance from fly offspring counts`               `Genetics practice`                                                           Bad: vague, no
                                                                                                                                               detail,
                                                                                                                                               \"practice\"
                                                                                                                                               is filler

  `Enzyme kinetics: calculate Km from Lineweaver-Burk`           `Calculate Michaelis constant using the reciprocal transformation approach`   Bad: too long
                                                                                                                                               (\> 80 chars)

  `Determine qPCR fold change from Ct values`                    `qPCR`                                                                        Bad: too
                                                                                                                                               terse,
                                                                                                                                               doesn\'t
                                                                                                                                               describe the
                                                                                                                                               task
  -----------------------------------------------------------------------------------------------------------------------------------------------------------

## DESCRIPTION block guidance

The DESCRIPTION block is a 2-3 sentence instructor-facing summary that
explains the task, any constraints that affect adoption (unit
requirements, rounding, domain restrictions), and provenance if adapted
from another source.

### Template with placeholders


    ## DESCRIPTION
    ## [Task in one sentence]. [Constraints or special requirements]. [Optional: Adapted from ...]
    ## ENDDESCRIPTION

### Biology examples of complete DESCRIPTION blocks

**Enzyme kinetics problem:**


    ## DESCRIPTION
    ## Students calculate the Michaelis constant (Km) from enzyme kinetics data using a
    ## Lineweaver-Burk plot. Answers require two significant figures and appropriate units (mM).
    ## ENDDESCRIPTION

**Genetics cross problem:**


    ## DESCRIPTION
    ## Students determine the probability of offspring genotypes from a dihybrid cross using
    ## Punnett square logic. Answers are fractions in lowest terms (e.g., 9/16).
    ## ENDDESCRIPTION

**Dilution series problem:**


    ## DESCRIPTION
    ## Students calculate final concentrations in a serial dilution series given a stock
    ## concentration and dilution factors. Answers must include units (µM or mM) and use
    ## scientific notation for very small values.
    ## ENDDESCRIPTION

### What NOT to include in DESCRIPTION

- Do not paste full solutions or step-by-step instructions.
- Do not include long pedagogical essays or teaching philosophy.
- Do not include code or implementation details.
- Do not describe the story wrapper (e.g., \"students imagine they are
  in a lab\").

## KEYWORDS guidance

Use 3 to 5 keywords (prefer 3-4 when possible) that describe techniques,
concepts, or methods. Avoid character names, story nouns, or terms
already implied by DBsubject.

### Keyword selection process for biology problems

**Example 1: Dilution problem**

- Good keywords: `'serial dilution', 'concentration', 'stock solution'`
- Bad keywords: `'biology', 'lab', 'science', 'tube'`
- Why: Good keywords are searchable techniques. Bad keywords are too
  generic or story nouns.

**Example 2: Enzyme kinetics problem**

- Good keywords:
  `'Michaelis-Menten', 'Lineweaver-Burk', 'enzyme kinetics', 'Km'`
- Bad keywords: `'biochemistry', 'enzyme', 'calculation'`
- Why: Good keywords name specific methods. Bad keywords duplicate
  DBsubject or are too broad.

**Example 3: qPCR problem**

- Good keywords: `'qPCR', 'fold change', 'Ct value', 'delta-delta Ct'`
- Bad keywords: `'gene expression', 'RNA', 'technique'`
- Why: Good keywords are technique-specific. Bad keywords are outcome
  terms, not methods.

### How to avoid duplicating DBsubject terms

If DBsubject is `Biochemistry`, do not use `'biochemistry'` as a
keyword. Instead, use technique names like `'enzyme kinetics'`,
`'Henderson-Hasselbalch'`, or `'buffer capacity'`. Keywords should
narrow the search within the subject area.

## DBsubject, DBchapter, and DBsection guidance

These three fields form the primary classification taxonomy for the Open
Problem Library. Choose values that fit life science courses and match
existing usage in your repository for consistency.

### Biology-appropriate DBsubject values

  -----------------------------------------------------------------------
  DBsubject value              When to use
  ---------------------------- ------------------------------------------
  `Biology - molecular`        DNA, RNA, transcription, translation,
                               replication

  `Biology - introductory`     General biology concepts, cell structure,
                               basic processes

  `Biochemistry`               Enzyme kinetics, metabolism, protein
                               structure, buffers

  `Genetics`                   Inheritance patterns, Punnett squares,
                               linkage, pedigrees

  `Laboratory Techniques`      Dilutions, spectrophotometry, gel
                               electrophoresis, qPCR

  `Cell Biology`               Organelles, transport, signaling, cell
                               cycle

  `Biostatistics`              Statistical tests, experimental design,
                               data analysis
  -----------------------------------------------------------------------

### Decision tree: choosing the right DBsubject

1.  **What is the primary discipline?** Start with the course context
    (Biochemistry, Genetics, etc.)
2.  **Is it a technique or concept?** If purely technique-focused
    (dilutions, PCR), use Laboratory Techniques.
3.  **Is it broad or specific?** If the problem spans multiple
    sub-disciplines, use the most specific subject that still fits
    typical course organization.
4.  **Does it match existing usage?** Search your repository for similar
    problems and copy the exact DBsubject string to maintain
    consistency.

### Full list of biology-appropriate DBsubject values

Use these DBsubject values for life science content. If a new subject is
needed, add it to the list so tags remain consistent across the
repository.

  ---------------------------------------------------------------------------------------
  DBsubject value                              When to use
  -------------------------------------------- ------------------------------------------
  `Anatomy and Physiology`                     Organ systems, body structures,
                                               physiological processes

  `Biochemistry`                               Enzyme kinetics, metabolism, protein
                                               structure, buffers

  `Bioinformatics and Computational Biology`   Sequence analysis, phylogenetics,
                                               computational methods

  `Biomedical Sciences`                        Disease mechanisms, pharmacology, clinical
                                               applications

  `Biostatistics`                              Statistical tests, experimental design,
                                               data analysis

  `Cell Biology`                               Organelles, transport, signaling, cell
                                               cycle

  `DNA Profiling`                              Forensic DNA analysis, STR markers,
                                               electrophoresis patterns

  `Ecology`                                    Population dynamics, ecosystems,
                                               biodiversity

  `Evolution`                                  Natural selection, phylogenetics,
                                               population genetics

  `Immunology`                                 Immune responses, antibodies, vaccines,
                                               immunoassays

  `Inheritance Genetics`                       Inheritance patterns, Punnett squares,
                                               linkage, pedigrees

  `Laboratory Techniques`                      Dilutions, spectrophotometry, gel
                                               electrophoresis, qPCR

  `Microbiology`                               Bacteria, viruses, microbial growth,
                                               antimicrobials

  `Molecular Biology`                          DNA replication, transcription,
                                               translation, gene regulation

  `Neuroscience`                               Neural signaling, brain structure,
                                               synaptic transmission

  `Organismic Biology`                         Whole-organism biology, plant biology,
                                               animal biology
  ---------------------------------------------------------------------------------------

### Complete classification examples

**Example 1: Dilution problem**


    ## DBsubject('Laboratory Techniques')
    ## DBchapter('Solution preparation')
    ## DBsection('Serial dilutions')

**Example 2: Enzyme kinetics problem**


    ## DBsubject('Biochemistry')
    ## DBchapter('Enzymes')
    ## DBsection('Kinetics basics')

**Example 3: Genetics cross problem**


    ## DBsubject('Genetics')
    ## DBchapter('Mendelian inheritance')
    ## DBsection('Dihybrid crosses')

## Problem level: Bloom\'s taxonomy scale

The `Level(...)` field uses a 1-6 scale aligned to Bloom\'s revised
taxonomy: Remember, Understand, Apply, Analyze, Evaluate, Create. This
field is required for problems in the biology-problems repository.

  ------------------------------------------------------------------------
  Level   Bloom\'s     Verbs                 Biology example
          category                           
  ------- ------------ --------------------- -----------------------------
  1       Remember     recall, define,       \"Which amino acid has a
                       label, list, match,   sulfur atom in its side
                       identify              chain?\"

  2       Understand   explain, summarize,   \"Classify this molecule as a
                       interpret, classify,  carbohydrate, lipid, protein,
                       compare               or nucleic acid.\"

  3       Apply        apply, use,           \"Using the genetic code
                       determine, solve,     table, translate this mRNA
                       choose                sequence.\"

  4       Analyze      analyze, compare,     \"Analyze this gel
                       contrast, categorize, electrophoresis result to
                       infer                 determine which protein is
                                             largest.\"

  5       Evaluate     evaluate, justify,    \"Justify why an Arg-Glu-Asp
                       critique, defend      peptide would be more soluble
                                             than Leu-Val-Ile at pH 7.0.\"

  6       Create       design, propose,      \"Design a peptide sequence
                       formulate, develop,   that would be maximally
                       create                soluble at pH 7.0.\"
  ------------------------------------------------------------------------

### Level assessment tips

- **Level 1 (Remember):** Direct recall, no inference or multi-step
  reasoning needed. Asking for definitions, names, or lists.
- **Level 2 (Understand):** Requires understanding and classification,
  but necessary reference values are given.
- **Level 3 (Apply):** Direct application of rules or formulas with
  clear instructions and provided data.
- **Level 4 (Analyze):** Student must infer relationships, analyze
  multiple factors, or synthesize information from different knowledge
  domains.
- **Level 5 (Evaluate):** Requires defending a conclusion, evaluating
  competing explanations, or justifying choices based on multiple
  criteria.
- **Level 6 (Create):** Requires synthesizing knowledge to create novel
  solutions, designs, or models.

### Level format


    ## Level(3)

## Language field

Use ISO 639-1 language codes to specify the problem language. This field
is required. For English, use:


    ## Language(en)

## Attribution and provenance fields

These fields credit authors, track provenance, and clarify licensing.
They are recommended for all problems and required for adapted content.

### Minimal recommended set


    ## Date('2026-01-28')
    ## Author('Dr. Neil R. Voss')
    ## Institution('Roosevelt University')

### Rules for attribution

- If the problem is adapted, also state that in DESCRIPTION (e.g.,
  \"Adapted from \...\").
- Use a real date when known. Prefer ISO format: YYYY-MM-DD.
- Empty strings are acceptable when you do not know the details, but do
  not invent information.

### Textbook provenance fields

Use these when the problem is adapted from a textbook, worksheet, or
other source. Number the tags (TitleText1, TitleText2, etc.) to map to
multiple texts when appropriate.


    ## TitleText1('Title of source')
    ## EditionText1('Edition')
    ## AuthorText1('Author(s)')
    ## Section1('Section identifier')
    ## Problem1('Problem identifier')

## License comments

OPL does not define a standard license tag. Use plain comment lines
(single `#`, not `##`) to state licensing for the problem text and any
included images or code.


    # This work is licensed under CC BY 4.0 (Creative Commons Attribution 4.0
    # International License).
    # https://creativecommons.org/licenses/by/4.0/
    # Source code portions are licensed under LGPLv3.

## Tagging quality rules

1.  DBsubject reflects the discipline and course area, not the scenario.
2.  KEYWORDS reflect methods and concepts, not superficial nouns.
3.  Use consistent capitalization and spelling across the corpus.
4.  Prefer stable, existing label strings over \"better\" new strings.
5.  Avoid \"meta noise\" labels like `WeBWorK` or `ZZZ-Inserted Text` in
    new content.

## Header review checklist

Before publishing a problem, verify the following:

- DESCRIPTION exists and is short, accurate, and code-free.
- KEYWORDS exist and are concept-focused (3-5 terms).
- DBsubject uses an existing repo string from the local list.
- DBchapter and DBsection are present (no empty strings).
- Level is set using the 1-6 Bloom\'s taxonomy scale.
- Author and Date are present when known.
- Language(en) is present.
- No smart quotes or non-ASCII characters in header lines.

## Complete worked examples

These examples show full OPL headers for different problem types. Copy
and adapt for your own problems. For more templates, see Appendix 90.1.

### Full header for a dilution problem


    ## TITLE('Serial dilution: calculate final concentrations')
    ## DESCRIPTION
    ## Students calculate final concentrations in a serial dilution series given a stock
    ## concentration and dilution factors. Answers must include units (µM or mM) and use
    ## scientific notation for very small values.
    ## ENDDESCRIPTION
    ## KEYWORDS('serial dilution','concentration','stock solution')
    ## DBsubject('Laboratory Techniques')
    ## DBchapter('Solution preparation')
    ## DBsection('Serial dilutions')
    ## Level(3)
    ## Date('2026-01-28')
    ## Author('Dr. Neil R. Voss')
    ## Institution('Roosevelt University')
    ## Language(en)

### Full header for a genetics problem


    ## TITLE('Dihybrid cross: predict offspring ratios')
    ## DESCRIPTION
    ## Students determine the probability of offspring genotypes from a dihybrid cross using
    ## Punnett square logic. Answers are fractions in lowest terms (e.g., 9/16).
    ## ENDDESCRIPTION
    ## KEYWORDS('dihybrid cross','Punnett square','Mendelian inheritance','independent assortment')
    ## DBsubject('Genetics')
    ## DBchapter('Mendelian inheritance')
    ## DBsection('Dihybrid crosses')
    ## Level(3)
    ## Date('2026-01-28')
    ## Author('Dr. Neil R. Voss')
    ## Institution('Roosevelt University')
    ## Language(en)

### Full header for a pathway problem


    ## TITLE('Glycolysis: identify rate-limiting enzymes')
    ## DESCRIPTION
    ## Students identify which enzymes in the glycolytic pathway are subject to allosteric
    ## regulation and explain their physiological significance. Free-response answers are
    ## graded for keyword matches.
    ## ENDDESCRIPTION
    ## KEYWORDS('glycolysis','allosteric regulation','rate-limiting enzyme','metabolism')
    ## DBsubject('Biochemistry')
    ## DBchapter('Metabolism')
    ## DBsection('Glycolysis')
    ## Level(4)
    ## Date('2026-01-28')
    ## Author('Dr. Neil R. Voss')
    ## Institution('Roosevelt University')
    ## Language(en)

## Common mistakes and how to avoid them

- **Empty DBsubject string:** Never leave DBsubject, DBchapter, or
  DBsection empty. Choose the closest existing label and revise later if
  needed.
- **Smart quotes in header:** Use plain ASCII quotes (`'`), not curly
  quotes (`'` or `'`). Smart quotes break OPL parsing tools.
- **Missing ENDDESCRIPTION tag:** Always close the DESCRIPTION block
  with `## ENDDESCRIPTION`. Without it, parsers may read subsequent code
  as part of the description.
- **Too many keywords:** More than 5 keywords dilutes search
  effectiveness. Stick to 3-5, preferring the most distinctive terms.
- **Using \"practice\" or \"problem\" in title:** Titles should describe
  the task, not announce that it\'s a practice problem. Replace
  \"Practice computing dilutions\" with \"Compute dilution factor from
  concentrations\".
- **Pasting code into DESCRIPTION:** The description is for humans, not
  parsers. Keep it plain English and code-free.

## Apply it today

- Before editing a problem, confirm it has a TITLE and DESCRIPTION
  block.
- Copy the template from Appendix 90.1 and fill in metadata before
  writing PGML.

---

# 02_Problem_Generation_PG/2.3-PG_Problem_Files_with_a_pg_file_extension

This page only covers the PG you need to support a PGML prompt.

Use this page when starting a new file or diagnosing a broken one.

**Use this page when:** you need a clean, reliable .pg skeleton you can
reuse.

## Copy and edit (PGML-first skeleton)


    # ===== OPL HEADER =====
    ## TITLE('Short descriptive title')
    ## DESCRIPTION
    ## One to three sentences describing the task and constraints.
    ## ENDDESCRIPTION
    ## KEYWORDS('keyword1','keyword2','keyword3')
    ## DBsubject('Biochemistry')
    ## DBchapter('Enzymes')
    ## DBsection('Kinetics basics')
    ## Date('2026-01-28')
    ## Author('Author name')
    ## Institution('Institution name')

    # ===== PREAMBLE =====
    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    # ===== SETUP =====
    Context("Numeric");
    $a = random(2, 8, 1);
    $b = random(3, 9, 1);
    $ans = Real($a + $b);

    # ===== STATEMENT =====
    BEGIN_PGML
    [`Total = `] [____]{$ans}
    END_PGML

    # ===== SOLUTION =====
    # BEGIN_PGML_SOLUTION
    # END_PGML_SOLUTION

    ENDDOCUMENT();

+-----------------------------------+-----------------------------------+
| Change this first                 | Do not touch yet                  |
+===================================+===================================+
| - Prompt text in PGML             | - Macro list and order            |
| - Random ranges and values        | - DOCUMENT()/ENDDOCUMENT()        |
+-----------------------------------+-----------------------------------+

**Common failure and fix**


    Broken: BEGIN_PGML before DOCUMENT();
    What you will see: PGML block not recognized or raw text output
    Fix: Keep DOCUMENT() and loadMacros() above PGML

After any macro change, render locally to catch missing macros early
([Chapter 7](/@go/page/555731)).

A WeBWorK problem is typically stored in a file with a `.pg` extension.
The file is a mix of:

- Comments (for authors)
- PG code (setup and answer checking)
- PGML text blocks (the student-facing prompt)

## Common structure (five sections)

Most `.pg` files follow a predictable structure. When you know the
structure, you can read problems faster and keep your own authoring
consistent.

1.  **OPL header**: metadata comments for searchability and attribution.
2.  **Preamble**: `DOCUMENT();` and `loadMacros(...);` (see [Section
    4.3](/@go/page/555710)).
3.  **Setup**: contexts, variables, randomization, answer objects.
4.  **Statement**: the student-facing prompt, typically in `BEGIN_PGML`.
5.  **Solution (optional)**: hints/solutions and any remaining answer
    setup. With PGML-first authoring, answers are usually attached
    directly to blanks, so a separate answer section is often
    unnecessary.

File structure errors are the most common cause of total failure. Most
bugs at this level are mechanical, not conceptual.

## Most common failure modes

- Missing `DOCUMENT();` or `ENDDOCUMENT();`.
- A macro is loaded after it is needed.
- A PGML block appears outside the document lifecycle.

## Annotated skeleton (recommended)

When you are learning, it helps to keep a short commented skeleton and
copy-edit it rather than starting from a blank file.


    # 1) OPL header (recommended)
    ## TITLE('Short descriptive title')
    ## DESCRIPTION
    ## ... summary for future authors ...
    ## ENDDESCRIPTION
    ## KEYWORDS('keyword1','keyword2','keyword3')
    ## DBsubject('Biochemistry')
    ## DBchapter('Enzymes')
    ## DBsection('Kinetics basics')
    ## Date('2026-01-28')
    ## Author('Author name')
    ## Institution('Institution name')

    # 2) Initialization (required)
    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    # 3) Setup (keep small)
    Context("Numeric");
    # ... choose random values ...
    # ... define answer objects and graders ...

    # 4) Text (student-facing prompt)
    BEGIN_PGML
    ... prompt text ...
    ... answer blanks tied to answers ...
    END_PGML

    # 5) Optional hint/solution blocks
    # BEGIN_PGML_HINT ... END_PGML_HINT
    # BEGIN_PGML_SOLUTION ... END_PGML_SOLUTION

    ENDDOCUMENT();

## What to keep stable

- Always include `DOCUMENT();` and `ENDDOCUMENT();`.
- Always load `PGML.pl` when you use `BEGIN_PGML`.
- Keep setup code short and readable; your future self will thank you.

## Test immediately (recommended)

- After any macro or setup change, render locally with
  webwork-pg-renderer ([Chapter 7](/@go/page/555731)) to catch missing
  macros and syntax errors early.
- If local setup feels like too much, preview in ADAPT instead, but
  expect slower debugging when something breaks.

**Next, depending on what you are doing:**

- Need macro help? Go to [Section 2.5](/@go/page/488659).
- Copied legacy code? Go to [Section 2.6](/@go/page/555742).
- Not sure where setup ends and PGML begins? Go to [Section
  2.4](/@go/page/488658).

---

# 02_Problem_Generation_PG/2.4-Sections_within_a_PG_question

This page only covers the PG you need to support a PGML prompt.

**Use this page when:** you need to decide where a change belongs in the
file.

## Copy and edit (section map)

The block below is a complete PG file skeleton with all five sections
labeled so you can see the overall structure at a glance.


    # ===== OPL HEADER =====
    ## TITLE('Short descriptive title')
    ## DESCRIPTION
    ## One to three sentences describing the task and constraints.
    ## ENDDESCRIPTION
    ## KEYWORDS('keyword1','keyword2','keyword3')
    ## DBsubject('Biochemistry')
    ## DBchapter('Enzymes')
    ## DBsection('Kinetics basics')
    ## Date('2026-01-28')
    ## Author('Author name')
    ## Institution('Institution name')

    # ===== PREAMBLE =====
    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    # ===== SETUP =====
    Context("Numeric");
    $a = random(2, 8, 1);
    $ans = Real($a + 1);

    # ===== STATEMENT =====
    BEGIN_PGML
    [`Result = `] [____]{$ans}
    END_PGML

    # ===== SOLUTION =====
    # BEGIN_PGML_SOLUTION
    # END_PGML_SOLUTION

    ENDDOCUMENT();

To adapt this skeleton, replace the OPL header fields with your own
metadata, change the Context to match your answer type, set up your
random values, and build your answer expression.

PG executes sections top-to-bottom, and the PGML block captures variable
references at parse time. If you place `Context()` or answer object
definitions after `BEGIN_PGML`, PGML will not see them because they do
not exist yet when the block is parsed.

**Common failure and fix**


    Broken: Context("Numeric") after BEGIN_PGML
    What you will see: parsing errors or wrong answer checking
    Fix: keep Context and answer objects in Setup above PGML

## Where does this go?

Use the following table as a quick lookup for deciding which section a
new line of code belongs in.

  ------------------------------------------------------------------------
  Task                      Section           Example
  ------------------------- ----------------- ----------------------------
  Tag the problem           OPL header        `## TITLE('...')`

  Load macros               Preamble          `loadMacros(...)`

  Choose a context          Setup             `Context("Numeric")`

  Random values             Setup             `$a = random(2, 8, 1);`

  Attach an answer checker  Setup             `$ans = Real(...);`

  Show the prompt text      Statement         `BEGIN_PGML ... END_PGML`

  Show a hint or solution   Solution          `BEGIN_PGML_SOLUTION`
  ------------------------------------------------------------------------

Most WeBWorK examples describe a PG file as having several sections
(description, initialization, setup, text, answers/solutions). That
model is still useful, but when you write PGML-first (see [Chapter
4](/@go/page/488661) for a detailed breakdown), the roles shift:

## Recommended sections (PGML-first)

1.  **OPL header**: metadata comments for searchability and attribution.
2.  **Preamble**: `DOCUMENT();` and `loadMacros(...)`.
3.  **Setup**: define variables and answers, pick a context, set
    tolerances.
4.  **Statement (PGML)**: the prompt between `BEGIN_PGML` and `END_PGML`
    (see [Section 3.1](/@go/page/555703) for PGML syntax).
5.  **Solution (optional)**: use `BEGIN_PGML_SOLUTION` or
    `BEGIN_PGML_HINT` when you want a structured solution.
6.  **End**: `ENDDOCUMENT();`.

## Why answers often live inside the PGML text

When you attach the correct answer directly to an answer blank (for
example `[______]{Real(12)}`), the connection between prompt and grading
stays obvious. This is especially helpful for science prompts with
multiple values and multiple parts.

When answers live next to the text they grade, it is much easier to see
why a student got something wrong.

Rule of thumb: if it is a sentence the student reads, it belongs in
PGML.

**Next, depending on what you are doing:**

- Need the OPL header? Go to [Section 2.2](/@go/page/557378).
- Need a clean starter .pg skeleton? Go to [Section
  2.3](/@go/page/488657).
- Need macro help? Go to [Section 2.5](/@go/page/488659).
- Copied legacy code? Go to [Section 2.6](/@go/page/555742).

---

# 02_Problem_Generation_PG/2.5-Common_PG_Macros

This page is not a catalog of everything PG can do. It is a short list
of macros you will actually see and use when writing PGML-first science
problems.

**Use this page when:** a problem will not render, a widget is missing,
or you are adding a new interaction type.

This guide reflects the PG 2.17 subset used in ADAPT and
webwork-pg-renderer. Some macros used in online examples are missing in
this subset, so check the allowlist before you add a new file to
`loadMacros()`.

For the full comparison table, see
`docs/PG_MACRO_VERSION_COMPARISON.md`.

If you are writing your first problem, start with the four core macros
(PGstandard.pl, MathObjects.pl, PGML.pl, PGcourse.pl). Add interaction
macros only when you need a specific widget like radio buttons or
dropdowns.

## Copy and edit (minimal macro set)


    DOCUMENT();

    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

This is the most common macro error: calling a function that requires a
macro you forgot to load. PG reports the function name as \"Undefined
subroutine\" because the macro file that defines it was never loaded.

**Common failure and fix**


    Broken: RadioButtons(...) without parserRadioButtons.pl
    What you will see: Undefined subroutine &main::RadioButtons called
    Fix: add "parserRadioButtons.pl" to loadMacros()

## Core macros for PGML-first problems

These four macros form the foundation of every PGML problem. Load all
four unless you have a specific reason to omit one. The table below
shows what each macro enables and what breaks if you leave it out.

  ------------------------------------------------------------------------
  Macro            What it enables            What breaks if it is missing
  ---------------- -------------------------- ----------------------------
  PGstandard.pl    Core PG helpers and        Basic PG functions are
                   defaults.                  undefined.

  PGML.pl          PGML blocks, formatting,   PGML blocks fail or render
                   and answer blanks.         as raw text.

  PGcourse.pl      Course-level helpers and   Course-specific helpers are
                   defaults.                  undefined.

  MathObjects.pl   MathObjects: Real,         Needed when using Real(),
                   Formula, Compute, Context. Compute(), Formula(), or
                                              Context(). Not required for
                                              RadioButtons or
                                              CheckboxList.
  ------------------------------------------------------------------------

**Note:** MathObjects.pl is included in most science problems because
they use numeric answers with Real() or Compute(). For pure
multiple-choice or matching problems that do not compute numeric values,
it can be omitted.

## Add-ons by interaction type

Beyond the core four, you add macros based on the interaction type your
problem needs. Each row below corresponds to a student-facing widget.
Load the macro only when you use that widget \-- extra macros add no
value and slow down debugging.

  -----------------------------------------------------------------------------
  What students see        Macro to load             Notes
  ------------------------ ------------------------- --------------------------
  Single-choice questions  parserRadioButtons.pl     Visible options, one
  (radio buttons)                                    correct choice (see
                                                     [Section
                                                     5.2](/@go/page/555715)).

  Matching or shuffled     PGchoicemacros.pl         Matching and choice
  lists                                              helpers (see [Section
                                                     5.4](/@go/page/555717) and
                                                     [Section
                                                     6.3](/@go/page/555725)).

  Targeted feedback for    answerHints.pl            Instructor-style feedback
  common errors                                      without extra widgets.

  Dropdown menus (select   parserPopUp.pl            Use PopUp() for inline
  one from a list)                                   dropdown selection.
                                                     Available in ADAPT (see
                                                     [Section
                                                     6.3](/@go/page/555725)).

  Drag-and-drop proof      draggableProof.pl         Students arrange steps
  ordering                                           into the correct order.

  Drag-and-drop grouping   draggableSubsets.pl       Students sort items into
  into subsets                                       labeled bins.

  Free-response essay box  PGessaymacros.pl          Open-ended text entry;
                                                     requires manual grading.

  Fill-in-the-blank word   parserWordCompletion.pl   Accepts specific string
  completion                                         answers from a word bank.
  -----------------------------------------------------------------------------

## Macro availability (subset vs full PG)

Not every PG macro is available in the ADAPT/renderer subset. The table
below shows which macros work in your environment. If a macro shows
\"No\" in the ADAPT column, you need a workaround.

  -------------------------------------------------------------------------
  Macro file                ADAPT/renderer   Full PG 2.17+  PG 2.20
                            subset                          
  ------------------------- ---------------- -------------- ---------------
  PGML.pl                   Yes              Yes            Yes

  MathObjects.pl            Yes              Yes            Yes

  parserRadioButtons.pl     Yes              Yes            Yes

  parserCheckboxList.pl     No               Yes            Yes

  VectorListCheckers.pl     No               Yes            Yes
  -------------------------------------------------------------------------

## What macro availability means for you

The ADAPT/renderer subset is based on PG 2.17 but uses a flattened macro
tree with some files removed. This affects what widgets and helpers you
can use in problems.

### Parser widgets: Key differences

  ---------------------------------------------------------------------------
  Widget              ADAPT/renderer   Full PG      Notes
                                       2.17+        
  ------------------- ---------------- ------------ -------------------------
  PopUp               Yes              Yes          Use for matching
                                                    dropdowns (see [Section
                                                    6.3](/@go/page/555725))

  RadioButtons        Yes              Yes          Use for single-choice
                                                    questions and
                                                    per-statement True/False

  CheckboxList        No               Yes          Not available. Use
                                                    RadioButtons per
                                                    statement instead
                                                    ([Section
                                                    6.4](/@go/page/555726))

  DropDown            No               No           PG 2.18+ only. Use PopUp
                                                    in ADAPT/renderer
  ---------------------------------------------------------------------------

### Core macros: All available

  ---------------------------------------------------------------------------
  Macro               ADAPT/renderer   Full PG      Notes
                                       2.17+        
  ------------------- ---------------- ------------ -------------------------
  PGML.pl             Yes              Yes          Always load this for PGML
                                                    blocks

  PGstandard.pl       Yes              Yes          Core PG functions

  MathObjects.pl      Yes              Yes          Required for Real(),
                                                    Compute(), Formula()

  niceTables.pl       Yes              Yes          The only supported way to
                                                    create tables (see
                                                    [Section
                                                    6.2](/@go/page/555724))
  ---------------------------------------------------------------------------

### Context macros: Most available, some missing

  -------------------------------------------------------------------------------
  Macro                   ADAPT/renderer   Full PG      Notes
                                           2.17+        
  ----------------------- ---------------- ------------ -------------------------
  contextUnits.pl         Yes              Yes          Unit-aware parsing for
                                                        science problems

  contextReaction.pl      Yes              Yes          Chemical reaction input
                                                        validation

  VectorListCheckers.pl   No               Yes          Vector list validation
                                                        not available in subset
  -------------------------------------------------------------------------------

### What this means for problem authors

- **Use PopUp and RadioButtons:** These work reliably across all PG
  versions and are available in the ADAPT/renderer subset.
- **Avoid CheckboxList:** It\'s not in the PG 2.17 subset. Use
  RadioButtons per statement instead (see [Section
  6.4](/@go/page/555726) for the pattern).
- **Check the allowlist before copying:** Online examples may use macros
  that aren\'t in the subset. Always verify against the allowlist in
  `docs/PG_2_17_RENDERER_MACROS.md`.
- **Use niceTables.pl for all tables:** HTML table tags (`<table>`,
  `<tr>`, `<td>`) are blocked. niceTables.pl is the only supported way
  to create tables.
- **Test locally:** Use the local renderer ([Chapter
  7](/@go/page/555731)) to catch missing macros before deploying to
  ADAPT.

## When a macro is missing

If you try to load a macro that\'s not in the ADAPT/renderer subset,
you\'ll see an error. Here\'s how to diagnose and fix it.

### Symptoms of a missing macro

- **\"Can\'t locate \[MacroFile\].pl\" error:** The macro file doesn\'t
  exist in the renderer\'s macro search path.
- **\"Undefined subroutine\" error:** A function from a missing macro
  was called (e.g., `CheckboxList()` without `parserCheckboxList.pl`).
- **Widget doesn\'t appear:** The problem renders but the expected
  checkbox list, dropdown, or other widget is missing.

### How to diagnose

1.  **Check the allowlist:** Open `docs/PG_2_17_RENDERER_MACROS.md` and
    search for the macro file name. If it\'s not listed, it\'s not
    available.
2.  **Test locally with renderer:** Run the problem through the local
    renderer ([Section 7.1](/@go/page/555732)). The error message will
    tell you which macro failed to load and where it was called.
3.  **Search for alternatives:** Look for similar functionality in
    macros that ARE in the allowlist. For example, use `PopUp` instead
    of `DropDown`.

### Common workarounds

  -------------------------------------------------------------------------
  Missing macro           What it provided         Workaround
  ----------------------- ------------------------ ------------------------
  parserCheckboxList.pl   Checkbox lists for       Use RadioButtons per
                          multiple correct answers statement (True/False),
                                                   see [Section
                                                   6.4](/@go/page/555726)

  DropDown (PG 2.18+)     Modern dropdown widget   Use PopUp from
                                                   parserPopUp.pl (same
                                                   functionality)

  VectorListCheckers.pl   Vector list validation   Use MathObjects Vector
                          helpers                  context directly or
                                                   simplify to scalar
                                                   answers
  -------------------------------------------------------------------------

### Prevention

- Before copying code from online examples, check the macro list against
  the allowlist.
- Use templates from Appendix 90.1, which are verified to work with the
  PG 2.17 subset.
- Test problems locally ([Section 7.1](/@go/page/555732)) before
  deploying to ADAPT.

## Science-native contexts and grading helpers

These macros extend PG\'s answer checking to handle science-specific
input formats like units, chemical reactions, and scientific notation.
Use them when the standard Numeric or String contexts are too
restrictive for what you want students to enter.

  ------------------------------------------------------------------------------------
  Use it when              Macro to load                  Why it matters
  ------------------------ ------------------------------ ----------------------------
  Units are part of        contextUnits.pl                Supports unit-aware parsing
  correctness                                             and validation.

  You need chemical        contextReaction.pl             Validates reactants/products
  reaction input                                          and reaction structure.

  Multiple blanks depend   parserMultiAnswer.pl           Ties related blanks to one
  on each other                                           checker.

  Parts should contribute  weightedGrader.pl              Supports weighted scoring
  different weights                                       across parts.

  Order should not matter  unorderedAnswer.pl             Grades set-style answers
  in a list                                               without order.

  Answer must include      parserNumberWithUnits.pl       Parses and validates a
  physical units (e.g.,                                   number paired with a unit
  \"9.8 m/s\^2\")                                         string.

  Answer is a formula with parserFormulaWithUnits.pl      Extends FormulaWithUnits to
  units (e.g., \"2\*pi\*r                                 accept symbolic expressions
  m\")                                                    with units.

  Answer should be in      contextScientificNotation.pl   Requires answers like
  scientific notation                                     6.02E23 or 6.02 x 10\^23.
                                                          Useful for biology
                                                          measurements.

  Answer must be a         contextFraction.pl             Requires fractional form;
  fraction, not a decimal                                 rejects decimal equivalents.

  Answer is a percentage   contextPercent.pl              Parses answers like \"45%\"
                                                          and validates the percent
                                                          sign.

  You need a custom answer answerCustom.pl                Build a fully custom grading
  checker                                                 subroutine when standard
                                                          checkers are insufficient.

  Partial credit for       PGgraders.pl                   Provides full_partial_grader
  multi-part problems                                     and other grading
                                                          strategies.
  ------------------------------------------------------------------------------------

## Tables, layouts, and visual tools

These macros control how content is displayed, from data tables to
scaffolded multi-part prompts to generated graphs. Most biology problems
need at most niceTables.pl for data presentation.

  --------------------------------------------------------------------------
  Use it when              Macro to load        Why it matters
  ------------------------ -------------------- ----------------------------
  You need structured      niceTables.pl /      Keeps data displays clean
  tables or aligned blanks unionTables.pl       and readable.

  You want scaffolded,     scaffold.pl          Supports structured sections
  multi-part prompts                            without custom logic.

  An interactive graph     parserGraphTool.pl   Provides interactive graph
  tool is required                              widgets.

  You need a               PGtikz.pl            Renders TikZ code to an
  TikZ-generated image in                       image at display time.
  the problem                                   

  You need a               PGlateximage.pl      Renders arbitrary LaTeX
  LaTeX-generated diagram                       snippets to images.
  or figure                                     
  --------------------------------------------------------------------------

## Symptoms when missing

  --------------------------------------------------------------------------
  Symptom                    Likely missing          Fix
  -------------------------- ----------------------- -----------------------
  PGML renders as raw text   PGML.pl                 Load PGML.pl before
                                                     BEGIN_PGML.

  Radio buttons do not       parserRadioButtons.pl   Add
  appear                                             parserRadioButtons.pl
                                                     to loadMacros().

  Checkbox list does not     parserCheckboxList.pl   Use per-statement
  appear                     (not available)         RadioButtons or
                                                     matching instead.

  MathObjects are undefined  MathObjects.pl          Load MathObjects.pl
                                                     before using
                                                     Real/Compute.
  --------------------------------------------------------------------------

Local render shows the line and missing macro when ADAPT only reports a
generic error ([Chapter 7](/@go/page/555731)).

## Graph, plotting, and image macros

The renderer includes several macros for generating figures and plots.
Most biology problems do not need dynamic graphs, but these are
available when a problem requires a visual.

  -------------------------------------------------------------------------------
  Macro                        What it does             When to use it
  ---------------------------- ------------------------ -------------------------
  PGgraphmacros.pl             Creates 2D function      Simple function graphs
                               plots using the          (growth curves,
                               WWPlot/Fun system.       dose-response). See
                                                        [Section
                                                        6.6](/@go/page/555728).

  PGtikz.pl                    Renders TikZ code to an  Custom diagrams,
                               image.                   flowcharts, or annotated
                                                        figures.

  PGlateximage.pl              Renders arbitrary LaTeX  Complex LaTeX-only
                               to an image.             figures or chemical
                                                        structures.

  parserGraphTool.pl           Interactive graph widget Problems that ask
                               where students plot      students to construct a
                               points or draw lines.    graph.

  LiveGraphics3D.pl            Embeds interactive 3D    Rarely needed for
                               graphics.                life-science problems.
                                                        Available but niche.

  PGstatisticsGraphMacros.pl   Pre-built statistical    Statistics-oriented
                               graph types (histograms, problems with data
                               scatter plots).          visualization.
  -------------------------------------------------------------------------------

## Statistics and numerical macros

These macros are available in the renderer and are useful for
quantitative biology, biostatistics, or ecology problems that involve
data analysis.

  -------------------------------------------------------------------------
  Macro                   What it provides         Notes
  ----------------------- ------------------------ ------------------------
  PGstatisticsmacros.pl   Statistical functions:   Useful for biostatistics
                          mean, standard           problems involving
                          deviation, normal and    hypothesis testing or
                          t-distribution values.   confidence intervals.

  PGnumericalmacros.pl    Numerical methods:       Rarely needed for
                          interpolation, numerical biology. More common in
                          integration, Newton\'s   engineering or physics.
                          method.                  

  RserveClient.pl         Connects to an R         Requires a running
                          statistical computing    Rserve instance. Not
                          server from within PG.   available in most ADAPT
                                                   deployments.
  -------------------------------------------------------------------------

## Matrix and linear algebra macros

Matrix macros are available in the renderer but are rarely needed for
biology or life-science problems. They appear frequently in math and
engineering problem libraries.

  --------------------------------------------------------------------------
  Macro                    What it provides         Notes
  ------------------------ ------------------------ ------------------------
  PGmatrixmacros.pl        Basic matrix display and Use for problems
                           input helpers.           involving transition
                                                    matrices (population
                                                    genetics, Markov
                                                    chains).

  MatrixCheckers.pl        Answer checkers for      Validates student matrix
                           matrix-valued answers.   input against correct
                                                    answer.

  MatrixReduce.pl          Row reduction and RREF   Rarely needed for
                           utilities.               biology.

  contextMatrixExtras.pl   Extra MathObject         Extends the Matrix
                           operations for matrices. context with additional
                                                    operations.
  --------------------------------------------------------------------------

## Complex number and specialized math macros

These macros exist in the renderer for completeness but are almost never
needed in biology or life-science problems. They are listed here so you
recognize them if encountered in borrowed code.

  ---------------------------------------------------------------------------
  Macro                     What it provides         Relevance to biology
  ------------------------- ------------------------ ------------------------
  PGcomplexmacros.pl        Complex number           None. Remove if found in
                            arithmetic and display.  copied code.

  contextComplexExtras.pl / Extended complex number  None.
  contextComplexJ.pl        contexts (j instead of   Engineering-oriented.
                            i).                      

  PGdiffeqmacros.pl         Differential equation    Rare. Could appear in
                            display and solution     population dynamics or
                            helpers.                 pharmacokinetics
                                                     problems.

  PGpolynomialmacros.pl     Polynomial manipulation  None for typical biology
                            utilities.               problems.

  LinearProgramming.pl      Simplex method and LP    None. Operations
                            helpers.                 research only.
  ---------------------------------------------------------------------------

## Quick reference: which macro for which task

Use this table when you know what you want the problem to do but are not
sure which macro provides it.

  -----------------------------------------------------------------------
  I want to\...                   Load this macro
  ------------------------------- ---------------------------------------
  Ask a multiple-choice question  parserRadioButtons.pl

  Ask a dropdown selection        parserPopUp.pl
  question                        

  Ask for a numeric answer with   parserNumberWithUnits.pl
  units                           

  Require scientific notation in  contextScientificNotation.pl
  the answer                      

  Accept a chemical reaction as   contextReaction.pl
  input                           

  Require a fraction (no          contextFraction.pl
  decimals)                       

  Accept a percentage answer like contextPercent.pl
  \"45%\"                         

  Display a data table in the     niceTables.pl
  problem                         

  Create a multi-part scaffolded  scaffold.pl
  problem                         

  Show a dynamically generated    PGgraphmacros.pl (or PGtikz.pl for
  graph or plot                   custom diagrams)

  Let students arrange steps in   draggableProof.pl
  order                           

  Give partial credit by part     PGgraders.pl (or weightedGrader.pl for
                                  weighted scoring)

  Grade related answer blanks     parserMultiAnswer.pl
  together                        

  Write a custom answer checker   answerCustom.pl
  from scratch                    

  Provide targeted feedback for   answerHints.pl
  common mistakes                 

  Ask for a free-response essay   PGessaymacros.pl
  -----------------------------------------------------------------------

## Do not cargo-cult

- Remove macros you do not use and re-render.
- Load macros only once per file.
- Let dependencies load themselves; do not list everything \"just in
  case.\"

**Next, depending on what you are doing:**

- Not sure where the macro block belongs? Go to [Section
  2.4](/@go/page/488658).
- Need a clean starter .pg skeleton? Go to [Section
  2.3](/@go/page/488657).
- Copied legacy code? Go to [Section 2.6](/@go/page/555742).

---

# 02_Problem_Generation_PG/2.6-Legacy_PG_and_deprecated_patterns

This page helps you recognize legacy PG patterns that show up in older
problem libraries and online examples. The goal is to translate the
useful idea into a PGML-first structure (see [Section
3.1](/@go/page/555703) for modern PGML) without carrying forward fragile
formatting or scattered grading logic.

If you pasted code from an old problem and it uses BEGIN_TEXT, &ANS, or
raw Perl formatting, start here.

If you see a PopUp example online, treat it as a historical artifact,
not a recommendation.

**Use this page when:** a copied problem looks strange or grades
unpredictably.

## Copy and edit (PGML-first rewrite)


    # Legacy text block (do not use)
    # BEGIN_TEXT
    # The stock concentration is $c_stock uM.$PAR
    # Find the final concentration: \{ans_rule(10)\} uM
    # END_TEXT

    # PGML-first rewrite
    BEGIN_PGML
    The stock concentration is [c_stock] μM.

    Find the final concentration: [________]{$c_final} μM
    END_PGML

**Common failure and fix**


    Broken: $PAR and BEGIN_TEXT blocks mixed with PGML
    What you will see: raw $PAR output or missing blanks
    Fix: move all prompt text into BEGIN_PGML/END_PGML

## Rewrite recipe (fast path)

1.  Identify the story text and move it into a PGML block.
2.  Move all numbers, ranges, and answer objects into Setup.
3.  Attach each answer object directly to the blank in PGML.
4.  Remove unused macros and leftover text-formatting codes.
5.  Render a few seeds to confirm the prompt, units, and grading.

## Legacy patterns to recognize (and replace)

+---------------------+------------------------+------------------------+
| Legacy pattern      | Why you see it         | PGML-first replacement |
+=====================+========================+========================+
| `beginproblem()`    | Found in 78% of OPL    | Delete the line.       |
| call in DOCUMENT    | files. Was once        | `DOCUMENT()` alone is  |
| section             | required for           | sufficient.            |
|                     | initialization but is  |                        |
|                     | now handled by         |                        |
|                     | `DOCUMENT()`.          |                        |
+---------------------+------------------------+------------------------+
| BEGIN_TEXT /        | Pre-PGML format for    | Use BEGIN_PGML /       |
| END_TEXT blocks     | the prompt text.       | END_PGML for readable  |
|                     |                        | prompt text.           |
+---------------------+------------------------+------------------------+
| \$PAR, \$BR, and    | Older formatting       | Use normal paragraphs, |
| manual line breaks  | controls inside text   | lists, or tables in    |
|                     | blocks.                | PGML.                  |
+---------------------+------------------------+------------------------+
| String-built HTML   | Manual HTML assembly   | Use PGML with variable |
| (\"                 | in PG strings.         | inserts for clean      |
|                     |                        | text.                  |
| \" . \$x . \"       |                        |                        |
|                     |                        |                        |
| \")                 |                        |                        |
+---------------------+------------------------+------------------------+
| `ANS(num_cmp(...))` | `num_cmp` appears in   | Use MathObjects and    |
| or                  | 46% and `str_cmp` in   | PGML inline blanks:    |
| `ANS(str_cmp(...))` | 7% of OPL files.       | `[_]{$answer}`. See    |
|                     | Legacy evaluators from | the table below for    |
|                     | the pre-MathObjects    | specific replacements. |
|                     | era.                   |                        |
+---------------------+------------------------+------------------------+
| ans_rule() without  | Older blank creation   | Attach answer objects  |
| nearby answer       | with separate answer   | directly to PGML       |
| object              | logic.                 | blanks.                |
+---------------------+------------------------+------------------------+
| Manual rounding     | Legacy formatting for  | Use MathObjects and    |
| inside strings      | display-only answers.  | explicit tolerance     |
|                     |                        | rules.                 |
+---------------------+------------------------+------------------------+

## Deprecated or fragile behaviors

  --------------------------------------------------------------------------------
  Pattern                  Why it is fragile        Preferred approach
  ------------------------ ------------------------ ------------------------------
  `NchooseK($N, $K)`       Deprecated in            Use
                           PGchoicemacros.pl. Very  `random_subset($K, 0..$N-1)`
                           common in OPL (1,000+    from PGstandard.pl, or build
                           files). Returns K        an index array and
                           indices chosen from      `@list[@indices]`.
                           0..N-1.                  

  `shuffle($N)`            Deprecated in            Use
                           PGchoicemacros.pl.       `random_subset($N, 0..$N-1)`
                           Returns a random         for a full permutation, or
                           permutation of indices   Perl\'s built-in list
                           0..N-1.                  operations.

  `new_match_list` with    PGchoicemacros.pl legacy Use PopUp widgets
  `print_q`/`print_a`      match list generates its (`parserPopUp.pl`) with PGML
                           own form fields,         inline blanks. See Appendix
                           requiring                90.4 for both patterns.
                           `ANS(str_cmp(...))`.     

  PopUp menus for choices  Legacy UI pattern and    Use DropDown or radio/checkbox
                           inconsistent rendering.  patterns.

  Hidden grading logic in  Hard to debug and easy   Compute answers in Setup and
  text assembly            to mismatch with the     attach to blanks.
                           prompt.                  

  Multiple unrelated       Inconsistent parsing     Set Context once and override
  Context() changes        rules across blanks.     only if necessary.

  `num_cmp()`,             Legacy evaluators from   Use MathObjects (`Compute()`,
  `str_cmp()`, `fun_cmp()` pre-MathObjects era.     `String()`, `Formula()`) with
                           `num_cmp` alone appears  `->cmp()` or PGML blanks. See
                           in 46% of OPL files.     table below.

  `TEXT(beginproblem())`   No longer needed.        Delete the line entirely. Use
                           Appears in 78% of OPL    `DOCUMENT();` alone.
                           files but `DOCUMENT()`   
                           handles initialization.  

  `AnswerFormatHelp.pl`    Entire macro file        Use `helpLink()` from
                           deprecated in PG 2.17.   PGbasicmacros.pl (loaded via
                                                    PGstandard.pl).

  `compoundProblem.pl` /   Deprecated in PG 2.19.   Use `scaffold.pl` with
  `compoundProblem5.pl`    Legacy multi-section     `Scaffold::Begin()` and
                           problem macros.          `Section::Begin()`.

  Old macro families       Adds noise and can mask  Load only the macros needed
  loaded \"just in case\"  missing dependencies.    for the prompt.
  --------------------------------------------------------------------------------

## Legacy answer evaluators (very common in copied code)

Before MathObjects existed, every problem used standalone evaluator
functions like `num_cmp()` and `str_cmp()`. These still work but are
discouraged because MathObjects provide richer error messages, tolerance
handling, and direct attachment to PGML blanks. If you copy a problem
from the OPL, there is roughly a 50% chance it uses at least one of
these legacy evaluators.

### Copy and edit (answer evaluator rewrite)


    # Legacy pattern (do not use in new problems)
    # $answer = 42;
    # ANS(num_cmp($answer));
    # ANS(num_cmp($answer, tol => 0.01));

    # MathObjects + PGML rewrite
    $answer = Compute("42");
    BEGIN_PGML
    Enter the answer: [_________]{$answer}
    END_PGML
    # Tolerance is set via: $answer->cmp(tolerance => 0.01)

  ---------------------------------------------------------------------------------------------------
  Legacy evaluator                   OPL          What it does          MathObjects replacement
                                     prevalence                         
  ---------------------------------- ------------ --------------------- -----------------------------
  `num_cmp($x)`                      46% (33,804  Compares student      `$x = Compute("42");` then
                                     files)       answer to a number.   PGML `[_]{$x}` or
                                                  Supports tolerance,   `ANS($x->cmp())`
                                                  strings like \"DNE\". 

  `str_cmp("text")`                  7% (4,958    Compares student      `$x = String("text");` then
                                     files)       answer to a string.   PGML `[_]{$x}` or
                                                  Used for word         `ANS($x->cmp())`
                                                  answers, matching.    

  `fun_cmp("x^2")`                   Common in    Compares student      `$f = Formula("x^2");` then
                                     math OPL     formula by sampling   PGML `[_]{$f}` or
                                                  points.               `ANS($f->cmp())`

  `std_num_str_cmp()`                Low          Hybrid number/string  Use `Compute()` with
                                                  comparator. Formally  appropriate Context.
                                                  deprecated in PG      
                                                  2.17.                 

  `numerical_compare_with_units()`   Low          Number comparison     Use `NumberWithUnits()` from
                                                  with unit checking.   `parserNumberWithUnits.pl`.
                                                  Formally deprecated   
                                                  in PG 2.17.           
  ---------------------------------------------------------------------------------------------------

**Key point:** `num_cmp()` and `str_cmp()` are not formally marked
deprecated in the PG source (they have been rewritten to use MathObjects
internally), but the PG documentation recommends using MathObjects
`->cmp()` methods directly. New problems should always use MathObjects.

## beginproblem(): safe to delete

`beginproblem()` appears in 78% of OPL files (56,953 of 72,734). It was
once required to initialize problem output, but `DOCUMENT()` now handles
all initialization. If you copy a problem that includes
`TEXT(beginproblem())`, simply delete that line.


    # Legacy (found in most OPL files)
    # DOCUMENT();
    # TEXT(beginproblem());

    # Modern (just DOCUMENT is enough)
    DOCUMENT();

## PGchoicemacros.pl: widely used, mostly deprecated

PGchoicemacros.pl appears in over 1,000 OPL files, but most of its
utility functions are now deprecated. If you copy a problem that loads
PGchoicemacros.pl, check which functions it actually uses and consider
whether a modern replacement exists.

  -------------------------------------------------------------------------------
  Deprecated function     Replacement         Example rewrite
  ----------------------- ------------------- -----------------------------------
  `NchooseK(5, 3)`        `random_subset()`   `@pick = random_subset(3, 0..4);`

  `shuffle(5)`            `random_subset()`   `@perm = random_subset(5, 0..4);`

  `new_match_list`        PopUp widgets       Build PopUp objects and use PGML
                                              inline blanks (see [Section
                                              5.4](/@go/page/555717)).

  `new_select_list`       RadioButtons        Use `parserRadioButtons.pl` with
                                              PGML (see [Section
                                              5.2](/@go/page/555715)).

  `new_multiple_choice`   RadioButtons        Use `parserRadioButtons.pl` with
                                              PGML (see [Section
                                              5.2](/@go/page/555715)).
  -------------------------------------------------------------------------------

**Not deprecated:** `PGsort` is sometimes confused with
PGchoicemacros.pl but is actually a core function from PGbasicmacros.pl
(loaded via PGstandard.pl). It does not require loading
PGchoicemacros.pl and is not deprecated.

## Apply it today

- When you copy an older example, rewrite the text block into PGML
  first.
- Keep the macro list short and focused on what the prompt actually
  uses.
- Use seeds to reproduce any unexpected grading or formatting behavior
  (see [Section 7.2](/@go/page/555733) for common mistakes).

**Next, depending on what you are doing:**

- Once it is PGML-first, go back to [Section 2.3](/@go/page/488657) and
  rebuild from the minimal skeleton.
- Need macro help? Go to [Section 2.5](/@go/page/488659).
- Not sure where setup ends and PGML begins? Go to [Section
  2.4](/@go/page/488658).

---

# 02_Problem_Generation_PG/2.7-Future_PG_Version_Features

This guide targets the PG 2.17 subset available in ADAPT and the
standalone `webwork-pg-renderer`. Newer PG releases add features that
are not yet available in this environment, but understanding what is
coming helps you plan problems that will benefit from future upgrades
and avoid reinventing patterns that already exist upstream.

**Use this page when:** you see a feature in online examples or the
OpenWeBWorK wiki that does not work in ADAPT and want to know which PG
version introduced it.

## How to read this page

- Features listed under each version are *cumulative*: PG 2.19 includes
  everything from 2.18 and earlier.
- Items marked **(PG only)** are changes to the problem-authoring
  language. Items marked **(WW only)** are server or UI changes that do
  not affect .pg files.
- The textbook currently targets **PG 2.17**. Everything below that line
  already works in ADAPT.

## PG 2.17 (current ADAPT baseline)

This is what ADAPT and the standalone renderer support today. Key
features already documented in this textbook:

- Java and Flash applet support removed (problems using them will show a
  warning).
- GraphTool additions: point tool, three-point quadratic tool,
  four-point cubic tool, and keyboard controls for accessibility.
- DraggableProof updated to work in Gateway quizzes when written
  correctly.
- MathQuill input improvements for expressions and units.

## PG 2.18 features (not yet in ADAPT)

PG 2.18 is the first version with significant new authoring capabilities
beyond what ADAPT currently supports.

### New PGML syntax

PG 2.18 is the first version that reduces the need for many of the
workarounds you see in this textbook, especially for inserting images
into PGML and creating checkbox (select-all-that-apply) questions.

  -----------------------------------------------------------------------
  Feature                  What it does
  ------------------------ ----------------------------------------------
  PGML images              Insert images with
                           `[!alt text!]{image source}{width}{height}`
                           directly in PGML instead of using command
                           substitution or HTML.

  -----------------------------------------------------------------------

### New macros

  -------------------------------------------------------------------------------
  Macro                         Description
  ----------------------------- -------------------------------------------------
  `plotly3D.pl`                 Plot 3D curves and surfaces using the plotly.js
                                library. Useful for visualizing molecular
                                structures, reaction coordinate diagrams, or any
                                data that needs a third axis.

  `randomPerson.pl`             Generate a random person name with correct
                                pronoun methods (he/she/they). Produces
                                inclusive, readable story problems.

  `parserCheckboxList.pl`       Native checkbox answer type for
                                select-all-that-apply questions. Replaces the
                                RadioButtons-per-statement workaround documented
                                in [Section 5.3](/@go/page/555716).

  `parserRadioMultiAnswer.pl`   Tie a radio answer together with dependent answer
                                blanks that change based on the radio choice.
                                Useful for branching questions.

  `parserLinearRelation.pl`     Context for lines and linear inequalities as
                                MathObjects.

  `specialTrigValues.pl`        Standard trig values on the unit circle as a
                                helper macro.
  -------------------------------------------------------------------------------

### Updated macros

- **niceTables.pl**: Completely overhauled. If you are writing
  table-heavy problems, the 2.18 version has better options and cleaner
  syntax than what is documented in [Section 6.2](/@go/page/555724).
- **parserCheckboxList.pl / parserRadioButtons.pl**: Past-answer display
  now shows meaningful labels instead of B0, B1, etc.
- **parserGraphTool.pl**: Number line mode for intervals, default answer
  checkers, a `generateAnswerGraph` method for solutions, and a dynamic
  help system.
- **parserPopUp.pl**: New `DropDown` method as a modern replacement for
  `PopUp`.

### Other PG 2.18 changes

- MathQuill: typing `deg` produces a degree symbol; trig and log
  functions auto-wrap arguments in parentheses.
- Units: students can enter °C and °F directly; many new units added
  (angstroms, microseconds, picometers, etc.); plural forms accepted (30
  ft, 30 feet, 1 foot).
- Hardcopy generation revamped with a theme system (eleven themes
  included).
- LTI 1.3 authentication module added.

## PG 2.19 features (not yet in ADAPT)

PG 2.19 adds several quality-of-life improvements for PGML authoring.

### New PGML syntax

PG 2.19\'s biggest authoring win is native PGML tables, which means you
can build tables directly inside a PGML block without the explicit
`loadMacros("niceTables.pl")` call you currently need.

  -----------------------------------------------------------------------
  Feature                  What it does
  ------------------------ ----------------------------------------------
  PGML tables              Create tables directly in PGML blocks using
                           niceTables.pl syntax. The macro is
                           automatically loaded when using PGML, so no
                           explicit `loadMacros` call is needed.

  HTML div/span tags in    Add HTML `<div>` or `<span>` tags within PGML
  PGML                     using `[< ... >]` syntax. This replaces the
                           MODES workaround for wrapper divs documented
                           in [Section 6.3](/@go/page/555725).

  Horizontal rules fixed   PGML horizontal rules updated and made
                           reliable.
  -----------------------------------------------------------------------

### New macros and MathObjects

  -----------------------------------------------------------------------------
  Macro                       Description
  --------------------------- -------------------------------------------------
  `contextBoolean.pl`         Boolean MathObject context with parsing of
                              boolean expressions, reduction rules with AND/OR,
                              and customizable true/false symbols including
                              unicode. Relevant for logic gates in genetics or
                              Boolean search problems.

  `parserMultipleChoice.pl`   Umbrella macro that loads all multiple choice
                              parsers at once: PopUp, CheckboxList,
                              RadioButtons, RadioMultiAnswer. Simplifies the
                              `loadMacros` block.
  -----------------------------------------------------------------------------

### Other PG 2.19 changes

- **Matrix MathObjects**: New methods for creating zero, permutation,
  and elementary matrices; tests for triangular, orthogonal, diagonal,
  symmetric, row echelon, and reduced row echelon forms.
- **Fraction MathObjects**: New `num` and `den` methods for extracting
  numerator and denominator.
- **Compute behavior**: Calling `Compute` on a number now creates a Real
  directly instead of stringifying and passing to Formula.
- **Knowls**: Reworked to open in modal dialogs instead of inline
  expansion.
- The attempts table has been removed; feedback is now associated
  directly with each answer blank. **(WW only)**
- The PG editor now has an option to convert problems to PGML (use with
  care, conversion is not complete). **(WW only)**

### Breaking changes in PG 2.19

- **parserPopUp.pl default change**: When the correct answer is a
  non-negative integer, it is now treated as an index into the answer
  array (consistent with other macros) rather than the literal answer
  string. Problems using integer values as PopUp answers may need
  updating.

### Deprecated in PG 2.19

- **compoundProblem.pl** (all versions: compoundProblem.pl,
  compoundProblem2.pl, compoundProblem5.pl): Migrate to `scaffold.pl`
  instead.

## PG 2.20 features (current release)

PG 2.20 focuses on graphing tool improvements, modern plotting, units as
MathObjects, and cleanup of deprecated patterns.

### New macros and features

PG 2.20 brings unit-aware MathObjects through `contextUnits.pl`, so you
can grade answers that include units as part of the MathObject system
instead of relying on external workarounds. It also introduces a modern
plotting macro and a new context extension mechanism.

  --------------------------------------------------------------------------
  Macro / Feature          Description
  ------------------------ -------------------------------------------------
  `plots.pl`               Modern, efficient plotting macro for a wide
                           variety of graph types. Intended as a more
                           capable replacement for older graphing
                           approaches.

  `contextUnits.pl`        Units implemented as MathObject classes. Students
                           can enter answers with units and have them graded
                           as part of the MathObject framework.

  `contextExtensions.pl`   New context extension mechanism. Fraction
                           contexts are now extensions of the parent context
                           rather than standalone replacements.
  --------------------------------------------------------------------------

### Updated macros

- **parserGraphTool.pl**: Four new tools added: polygon tool, sine wave
  tool, vector tool, and improved fill tool.
- **contextReaction.pl**: Improvements to chemical reaction context.
  Relevant for chemistry and biochemistry problems.
- **parserPopUp.pl**: Full HTML now supported in drop-down menu items
  (bold, subscripts, etc.).
- **Degree n matrices**: Improvements to matrices/tensors with more than
  two dimensions.
- **Rserve interface**: Rewritten within PG; the
  `Statistics::R::IO::Rserve` package is no longer required.

### Breaking changes in PG 2.20

- **`custom_problem_grader_0_60_100` removed**: Problems must be
  converted to use `custom_problem_grader_fluid` instead. This is
  relevant if you copy older problems that use the 0/60/100 grading
  scale.
- **Degree 1 vs degree 2 matrix comparison**: Changed behavior when
  comparing a degree 1 matrix and a degree 2 matrix.

### WeBWorK 2.20 server changes **(WW only)**

- Problem editor upgraded to CodeMirror 6 with accordioning,
  autocompletion, and improved syntax highlighting.
- Security vulnerability fixes and database efficiency improvements.
- Problems can now be loaded directly from the Problem Editor or from
  sample problems.

## What this means for ADAPT authors today

Until ADAPT upgrades its PG version, the workarounds documented in this
textbook remain necessary. Here is a summary of what changes when ADAPT
eventually updates:

The following table maps each workaround documented in this textbook to
the PG version that eliminates it, so you can plan which problems to
update first when ADAPT upgrades.

  ----------------------------------------------------------------------------------------
  Current workaround                 Available in          What replaces it
  ---------------------------------- --------------------- -------------------------------
  RadioButtons per statement for     PG 2.18               Native `parserCheckboxList.pl`
  select-all-that-apply ([Section                          with proper checkbox UI
  5.3](/@go/page/555716))                                  

  PopUp for dropdown menus           PG 2.18               `DropDown` method in
                                                           `parserPopUp.pl`

  MODES wrapper for flexbox divs in  PG 2.19               `[< ... >]` div/span syntax in
  matching layouts ([Section                               PGML
  6.3](/@go/page/555725))                                  

  Explicit                           PG 2.19               niceTables.pl auto-loaded with
  `loadMacros("niceTables.pl")` for                        PGML
  tables                                                   

  Command substitution or HTML for   PG 2.18               Native `[!alt!]{src}{w}{h}`
  images in PGML                                           PGML image syntax

  No 3D visualization available      PG 2.18               `plotly3D.pl` for 3D curves and
                                                           surfaces

  TikZ images not available          PG 2.16+              `PGtikz.pl` for LaTeX-quality
                                                           vector graphics (requires
                                                           server-side LaTeX; not
                                                           available in ADAPT\'s renderer
                                                           subset)

  Plain text in PopUp/DropDown menu  PG 2.20               Full HTML in drop-down items
  items                                                    (bold, subscripts, special
                                                           characters)

  `custom_problem_grader_0_60_100`   PG 2.20               Removed. Use
                                                           `custom_problem_grader_fluid`
                                                           instead

  PGgraphmacros.pl for static plots  PG 2.20               `plots.pl` for modern,
                                                           efficient graph generation

  No native unit-aware answer        PG 2.20               `contextUnits.pl` for units as
  checking                                                 MathObject classes
  ----------------------------------------------------------------------------------------

## Apply it today

- Write problems using the PG 2.17 patterns in this textbook. They will
  continue to work in newer versions.
- When ADAPT upgrades, revisit select-all-that-apply problems (switch
  from RadioButtons fallback to CheckboxList) and matching layouts
  (replace MODES wrappers with PGML div syntax).
- Do not use TikZ, plotly3D, plots.pl, contextUnits.pl, CheckboxList,
  RadioMultiAnswer, or DropDown in problems intended for the current
  ADAPT environment.
- If you copy a problem that uses `custom_problem_grader_0_60_100`,
  replace it with `custom_problem_grader_fluid` (required in PG 2.20,
  works in all versions).

**Next, depending on what you are doing:**

- Need the current macro allowlist? Go to [Section
  2.5](/@go/page/488659).
- Copied legacy code and it looks strange? Go to [Section
  2.6](/@go/page/555742).
- Ready to write your first problem? Go to [Section
  2.3](/@go/page/488657).

{{template.ShowOrg()}}

---

# 03_PGML_PG_Markup_Language/3.0-Index

PGML (PG Markup Language) is the recommended way to write the
student-facing text of a WeBWorK problem. It is designed to replace
older authoring patterns that required long blocks of text and manual
escaping.

## Start here (task first)

- I need one blank that grades correctly -\> [Section
  3.2](/@go/page/555704) (Core).
- I need a multi-step lab workflow prompt -\> [Section
  3.3](/@go/page/555705) (Core).
- I need a small dataset table students read from -\> [Section
  3.4](/@go/page/555706) (Core).
- My prompt is too long and hard to scan -\> [Section
  3.5](/@go/page/555707) (Optional).
- I need to insert computed or helper-generated output -\> [Section
  3.6](/@go/page/555708) (Optional).

This chapter is the core of the book: most science-friendly question
writing can be done by combining a small PG setup with a clear PGML
prompt.

## What PGML gives you

- Readable prompts that look similar to the rendered output.
- Math in TeX or calculator notation, with consistent delimiters.
- Answer blanks that can be tied directly to answers.
- Simple structure tools (headings, lists, tables) that fit science
  prompts.

## PGML quick patterns

  --------------------------------------------------------------------------------
  Task                         Use                       Page
  ---------------------------- ------------------------- -------------------------
  One blank that grades        Answer blanks attached to [3.2](/@go/page/555704)
  correctly                    answers                   

  Multi-step lab workflow      Numbered lists            [3.3](/@go/page/555705)

  Small dataset table          DataTable                 [3.4](/@go/page/555706)

  Long prompt cleanup          Headings and light        [3.5](/@go/page/555707)
                               emphasis                  

  Computed or helper output    Command substitution      [3.6](/@go/page/555708)

  PGML basics and notation     Minimal PGML patterns     [3.1](/@go/page/555703)
                                                         (Optional)
  --------------------------------------------------------------------------------

The subsections in this chapter cover the small set of PGML features you
will use constantly: math notation, answer blanks, lists for workflows,
tables for data, and a small \"escape hatch\" for advanced insertion
when PGML alone is not enough.

Core pages: [3.2](/@go/page/555704) (Answer blanks) and
[3.3](/@go/page/555705) (Lists). Optional pages: [3.5](/@go/page/555707)
(Layout) and [3.6](/@go/page/555708) (Command substitution). Use
[3.1](/@go/page/555703) as a quick primer if you want notation examples.

If you are unsure which PGML pattern to use, start with the simplest
option that clearly communicates the task. Most grading issues in life
science questions come from misaligned structure rather than missing
features. When in doubt, clarity beats cleverness.

{{template.ShowOrg()}}

---

# 03_PGML_PG_Markup_Language/3.1-Introduction_to_PGML

PGML is a markup language for writing the student-facing text of a
WeBWorK problem. It is designed to replace older authoring styles that
required long blocks of text and careful escaping.

In this book, [PG](/@go/page/488656) is treated as minimal setup code,
and PGML is where you spend most of your authoring time.

**Use this when:** you want the prompt to read like a worksheet while
keeping the grading logic close to the text students see.

## Copy and edit (minimum viable PGML)

This template shows a minimal PGML block with inline math, variable
substitution, and one answer blank.


    $km = Real(2.5);
    $substrate = Real(12);
    $rate = Real(0.48);

    BEGIN_PGML
    For this enzyme, [`K_m = [$km]`] μM and [`[S] = [$substrate]`] μM.
    Report the rate [`v`] in μM/s:

    [`v = `] [____]{$rate}
    END_PGML

Customize the variable names, the prompt text, and the answer expression
in braces.

**Common failure and fix**

Without backtick delimiters, subscripts and Greek letters render as
plain text instead of formatted math.


    Broken: Km = 2.5 μM
    Fix: [`K_m`] = 2.5 μM

## What PGML is good at

- Readable prompts that look similar to the rendered output.
- Math written in TeX or calculator notation with consistent delimiters.
- Answer blanks tied directly to answer checkers.
- Structured formatting for science prompts (lists, tables, and short
  sections).

Most instructors do not need to learn PGML exhaustively. In practice, a
small set of patterns covers the majority of biology and life science
questions: inline math, answer blanks, short lists, and simple tables.
This chapter focuses on those patterns so you can write readable prompts
without treating PGML as another programming language.

## Math notation (TeX and calculator notation)

PGML supports two styles for writing mathematics: TeX and calculator
notation. Both styles support inline math and displayed math, and you
should pick the one that matches the situation.

Use TeX when you care about typesetting (for example, `` [`K_m`] `` or
`` [`V_{max}`] ``). Use calculator notation when you care about
readability and copy-paste (for example, `[: Ct :]` or `[: C1*V1/V2 :]`
for a dilution).

### TeX math delimiters

- Inline: `` [` ... `] ``
- Display-style inline: ``` [`` ... ``] ```
- Display (own line): ```` [``` ... ```] ````

### Calculator notation delimiters

- Inline: `[: ... :]`
- Display-style inline: `[:: ... ::]`
- Display (own line): `[::: ... :::]`

  ---------------------------------------------------------------------------------------
  Task                  Delimiter         Example
  --------------------- ----------------- -----------------------------------------------
  Variable name         TeX inline        `` [`K_m`] ``

  Short equation        Calculator inline `[: C1*V1/V2 :]`

  Long equation         TeX display       ```` [``` V = V_{max} * S/(K_m + S) ```] ````
  ---------------------------------------------------------------------------------------

### Science-friendly practice

- Use inline math for variable names and short expressions.
- Use display math for longer equations or multi-step expressions.
- Keep units outside the math expression unless you are explicitly
  typesetting them.

## Math formatting vs variable substitution

PGML uses square brackets for two different purposes. Confusing them is
a common mistake.

  ----------------------------------------------------------------------------------
  Purpose         Syntax                  Example                 Result
  --------------- ----------------------- ----------------------- ------------------
  Math formatting `` [` ... `] ``         `` [`K_m`] ``           Renders K with
                                                                  subscript m

  Variable        `[$variable]`           `[$km]`                 Displays value:
  substitution                                                    2.5

  Combined        `` [`K_m = [$km]`] ``   `` [`K_m = [$km]`] ``   Math with value
                                                                  inserted
  ----------------------------------------------------------------------------------

**Key rule:** Use backticks when you want LaTeX math rendering. Use
plain brackets (no backticks) when you want to display a variable\'s
value as text.

**Common mistake**


    Wrong: The answer is [`$radio->correct_ans`]
    Right: The answer is [$radio->correct_ans]

The wrong version tries to render \"Blue\" as LaTeX math. The right
version displays the text value.

## PGML is single-pass

PGML parses your text exactly once. This means that if you build PGML
tag-wrapper syntax inside a Perl variable, PGML will not re-parse it.
The variable\'s contents are inserted as literal text, so patterns like
`[<...>]{[...]}` stored in a string will not produce the expected
formatting.

A related pitfall involves the `[<` character sequence. If a Perl string
assigned earlier in your code contains `[<`, it can collide with PGML\'s
own bracket-angle syntax and produce parser errors or garbled output.
Watch for this when building HTML snippets or conditional text in Perl
and then inserting them with `[$var]`.

The single-pass rule also means that `[$...]` PGML interpolation inside
a `[@ ... @]` eval block will not work. The eval block runs Perl; it
does not re-enter the PGML parser. If you need formatted output from an
eval block, return a string and let PGML display it.

If you are writing your first problem, go to [Section
3.2](/@go/page/555704) now.

**Next, depending on what you are doing:**

- Need a blank that grades correctly? See [Section
  3.2](/@go/page/555704).
- Building a multi-step workflow prompt? See [Section
  3.3](/@go/page/555705).
- Need a data table students read from? See [Section
  3.4](/@go/page/555706).

---

# 03_PGML_PG_Markup_Language/3.2-Answer_blanks_and_answers

Answer blanks are the center of most WeBWorK problems. In PGML, blanks
are written as `[_____]` and the correct answer can be attached
immediately after the blank using braces. For the full catalog of
question types that use answer blanks, see [Chapter
5](/@go/page/488662).

**Use this when:** you want the grading rule to be obvious and close to
the prompt text students read.

## Copy and edit

The following template shows a numeric answer blank with the correct
value attached inline, so the grading rule lives right next to the
prompt text.


    $value = Real(12);
    $answer = Real(24);

    BEGIN_PGML
    You measure a stock with [`c = [$value]`] mM.
    What is twice the concentration?

    Report your answer in mM:
    [`2c = `] [____]{$answer} mM
    END_PGML

To adapt this for your own problem, change the variable names, the PGML
prompt text, and the answer expression inside the braces.

This error happens when you pass a numeric MathObject (like a Real)
where PG expects a string answer. PG requires the type inside the braces
to match the active Context, so passing `$ans2` (a Real) in a spot that
needs a string produces a type mismatch.

**Common failure and fix**


    Broken: [`ATP = `] [_____]{$ans2}
    Fix: [`ATP = `] [_____]{"ATP"}

Many examples online define answers far away from the text that students
see. That pattern works for short math problems but becomes fragile in
biology-style prompts with multiple parts and narrative flow. Attaching
each answer directly to its blank keeps the grading logic aligned with
the story and makes later edits much safer.

## Text answers in biology

Text answers are common in biology (gene/protein names, labels, or
categories). Keep the accepted strings narrow and document what counts
as correct to avoid over-accepting.

Free-text answers are appropriate when the response is a specific
term---a gene name, molecule, or category label---rather than a number
or formula. Use free-text instead of multiple choice when you want
students to recall the term rather than recognize it from a list. Keep
the accepted string set narrow to avoid grading ambiguity.


    Context("String");
    Context()->strings->add(
        ATP => {},
        atp => { alias => "ATP" },
        adenosine_triphosphate => { alias => "ATP" }
    );

    BEGIN_PGML
    The molecule is [_____]{"ATP"}.
    END_PGML

## Expression and formula blanks

If the correct answer is a formula, use a quoted string or a Formula
MathObject. Use `Compute()` or `Formula()` when the correct answer is an
expression students type, not just a number.


    $f = Compute("x^2-1");

    BEGIN_PGML
    [`y = `] [________________]{$f}
    END_PGML

## Why attach answers to blanks

When you attach an answer directly to a blank with `{$ans}`, PG
registers the answer checker at parse time and binds it to that specific
blank, so there is no separate answer-matching step that could go wrong.
This matters most in multi-part problems where answer order can drift if
answers and blanks are defined separately.

- The grading rule stays next to the text that asks for it.
- Multi-part science prompts are easier to maintain.
- It reduces the chance of mismatching answer order and prompt order.
  For common answer blank mistakes and how to fix them, see [Section
  7.2](/@go/page/555733).

**Next, depending on what you are doing:**

- Writing a multi-step lab workflow? Go to [Section
  3.3](/@go/page/555705).
- Need a data table students read from? Go to [Section
  3.4](/@go/page/555706).
- If formatting is the only issue, try [Section 3.5](/@go/page/555707).

---

# 03_PGML_PG_Markup_Language/3.3-Lists_and_workflows

Lists are one of the most useful PGML features for life science prompts
because many tasks are multi-step workflows. Use lists to make
expectations scannable and to reduce \"I missed that part\" errors. For
a complete ordered-list question type, see [Section
5.8](/@go/page/555721).

**Use this when:** you want a lab-style sequence that doubles as a
grading rubric.

## Copy and edit


    BEGIN_PGML
    You are preparing a PCR reaction. Follow these steps:

    1. Compute the final primer concentration in μM: [____]{$c_final}
    2. Report the MgCl2 concentration in mM: [____]{$mg_final}
    3. State whether the buffer is 1x or not: [____]{$buffer_ok}

    Use the units shown in each step.
    Round to two decimals.
    END_PGML

**Common failure and fix**


    Broken:
    1. First step
    Second paragraph without indent.
    Fix:
        Second paragraph with four-space indent.

In lab-style questions, lists are not just formatting. They communicate
order, expectations, and reporting structure to students. When you later
revise a problem, changing list order often requires checking that the
associated answer blanks still match the intended step.

## Numbered lists


    BEGIN_PGML
    1. Compute the concentration.
    2. Report the value with units.
    END_PGML

Start a numbered list item with a number, a period, and a space. PGML
will renumber items in the rendered output, so the specific numbers you
type are not the important part.

To include a second paragraph within the same list item, indent the
paragraph with four spaces.


    BEGIN_PGML
    1. First step with a paragraph.

        This stays inside the first item.
    2. Second step
    END_PGML

## Bullet lists


    BEGIN_PGML
    * Use the values from the table.
    * Keep units consistent.
    END_PGML

Bulleted list items typically begin with an asterisk (`*`) or a dash
(`-`).

## Biology workflow example


    BEGIN_PGML
    You are preparing a PCR reaction mix. Follow these steps:

    1. Compute the final primer concentration in μM.
    2. Compute the final MgCl2 concentration in mM.
    3. Decide whether the final buffer is 1x or not.
    END_PGML

## Watch out for auto-parsed list labels

PGML\'s list parser is aggressive. Any line that starts with a letter
followed by a period (for example, `A.` or `B.`) can be interpreted as
an ordered list item, even when you intended it as a plain label. This
is especially common when writing matching-style questions where you use
letters as answer choices.

Two easy fixes:

- Make the label bold: `*A.*` --- the bold wrapper prevents list
  parsing.
- Escape the period: `A\.` --- the backslash tells PGML that the period
  is literal text.

<!-- -->


    BEGIN_PGML
    Match each description to the correct answer.

    *A.* Mitochondria
    *B.* Chloroplast
    *C.* Ribosome
    END_PGML

## Authoring notes

- Keep each list item to one task.
- When a task requires a unit or a format, state it inside the list
  item.
- Use lists to make constraints visible (for example, \"round to two
  decimals\").

**Next, depending on what you are doing:**

- Need a single blank that grades correctly? Go to [Section
  3.2](/@go/page/555704).
- Need a data table students read from? Go to [Section
  3.4](/@go/page/555706).
- If grading is failing, go back to [Section 3.2](/@go/page/555704).

---

# 03_PGML_PG_Markup_Language/3.4-Tables_and_structured_data

Science prompts often require structured data. Prefer table helpers that
produce accessible tables in HTML output, and avoid using tables purely
for layout.

**Use this when:** students need to read values from a dataset before
answering.

## Copy and edit

**Required macro:** `niceTables.pl` must be loaded in the preamble to
use `DataTable` or `LayoutTable`. For advanced table formatting with
niceTables, see [Section 6.2](/@go/page/555724).


    # In preamble:
    loadMacros("PGstandard.pl", "PGML.pl", "niceTables.pl", "PGcourse.pl");

    # In setup:
    $ct_treat = Real(21.2);

    BEGIN_PGML
    [@ DataTable([
        [ "Sample", "Ct (cycles)" ],
        [ "Control", 18.2 ],
        [ "Treatment", 21.2 ],
    ], caption => "qPCR results") @]*

    The Ct for Treatment is [____]{$ct_treat}.
    END_PGML

**Common failure and fix**


    Broken: DataTable(...) without niceTables.pl loaded
    Fix: add "niceTables.pl" to loadMacros()

    Broken: LayoutTable([["Sample","Ct"],["Control",18.2]]) for real data
    Fix: DataTable([["Sample","Ct"],["Control",18.2]])

## Two table roles

- Data tables: real measurements or observations.
- Layout tables: spacing-only, when there is no meaningful row/column
  relationship.

## Recommended helpers

- `DataTable(...)`: use when the table communicates data (measurements,
  observations, counts).
- `LayoutTable(...)`: use when the table is only for arranging content
  and there is no meaningful row/column relationship.

Whenever a table represents measurements, observations, or experimental
results, treat it as data rather than layout. Using a data-oriented
table makes the prompt clearer to students and reduces the chance that
later formatting changes will alter meaning or grading behavior.

Tables should carry units in the header row, not scattered in every cell
(for example \"Ct (cycles)\" or \"Concentration (μM)\").

## Basic calling pattern


    DataTable(
        [
            [ "Sample", "Ct" ],
            [ "Control", 18.2 ],
            [ "Treatment", 21.2 ],
        ],
        caption => "qPCR results",
    );

## Authoring notes

- Use a data table whenever you want students to read values and compute
  from them.
- Keep tables small and label columns clearly; avoid wide tables with
  many decimals.
- Do not use a data table to position unrelated content; use
  `LayoutTable` for layout.

**Next, depending on what you are doing:**

- Need a multi-step workflow prompt? Go to [Section
  3.3](/@go/page/555705).
- Need computed inserts or helper output? Go to [Section
  3.6](/@go/page/555708).
- Need a single blank that grades correctly? Go to [Section
  3.2](/@go/page/555704).

---

# 03_PGML_PG_Markup_Language/3.5-Layout_controls

Layout controls can improve readability for longer prompts, but fragile
formatting is one of the fastest ways to create problems that render
differently across systems. Prefer simple structure (headings, lists,
and tables) and treat layout controls as an optional finishing touch.

**Use this when:** a prompt needs clearer scanning after the grading is
already stable.

## Copy and edit (minimal structure recipe)


    BEGIN_PGML
    # Data
    Measured values are shown above.

    ## Tasks
    1. Compute the rate in s^-1.
    2. Report the final value with units.

    ### Report
    [`Rate = `] [____]{$rate} s^-1
    END_PGML

**Common failure and fix**


    Broken: *Measure* *_everything_* *carefully* and *report* *everything*.
    Fix: Report the value in *mM* to *two decimals*.

## Headings (structure)

Headings help students scan a multi-part prompt. In PGML, headings are
written with `#` characters at the start of a line.


    BEGIN_PGML
    # Data
    ## Tasks
    ### Report
    END_PGML

## Emphasis (bold and italic)

- Bold: `*bold*`
- Italic: `_italic_`
- Bold italic: `*_bold italic_*`

Use emphasis to highlight the task being asked and the reporting
expectations (units, rounding), not to decorate the story. For coloring
and advanced emphasis options, see [Section 6.1](/@go/page/555723).

## Horizontal rules (sparingly)

Horizontal rules can separate major blocks, but headings are usually
clearer.


    ----

## Justification and centering (rare)

PGML supports simple right-justification and centering syntax. These are
occasionally useful for a short \"report\" block, but they can be
fragile and are easy to overuse.


    BEGIN_PGML
    >> Right-justified line

    >> centered <<
    END_PGML

Layout controls are best used sparingly. If a formatting change affects
how answers are entered, checked, or interpreted, it is usually a sign
that the structure should be simplified rather than refined. Clear
structure matters more than visual polish.

## Raw HTML and variable output

When a Perl variable contains HTML tags (such as `<span>` or `<div>`),
PGML escapes them by default. To preserve the HTML, use the raw
pass-through marker: `[$var]*`. Without the trailing asterisk, the
student sees literal angle brackets instead of styled output. This is
the same asterisk used after `[@ ... @]*` eval blocks.

**Next, depending on what you are doing:**

- If grading is failing, go back to [Section 3.2](/@go/page/555704).
- Need a data table students read from? Go to [Section
  3.4](/@go/page/555706).
- Need computed inserts? Go to [Section 3.6](/@go/page/555708).

---

# 03_PGML_PG_Markup_Language/3.6-Command_substitution_and_inserts

Command substitution lets you run a small Perl expression and insert its
output into the PGML prompt. This is useful for inserting images,
computed strings, or helper-generated markup. Variables used in
substitution are typically defined in the [Setup
block](/@go/page/555711) (Section 4.4).

Command substitution is powerful, but it should not be the first
solution to a formatting or clarity problem. In most cases, PGML lists,
tables, or explicit text are easier to read and easier to maintain. Use
substitution only when the content genuinely depends on computed or
conditional output.

**Use this when:** you need to insert computed output or
helper-generated markup that PGML cannot express directly.

## Copy and edit


    $ct = Real(21.2);
    $rows = [
        [ "Sample", "Ct (cycles)" ],
        [ "Control", 18.2 ],
        [ "Treatment", 21.2 ],
    ];

    BEGIN_PGML
    [@ DataTable($rows, caption => "qPCR results") @]*
    The Ct for Treatment is [____]{$ct}.
    END_PGML

**Common failure and fix**


    Broken: [@ DataTable($rows) @]
    Fix: [@ DataTable($rows) @]*

## Syntax


    [@ some_perl_expression() @]

If the substitution produces output that is already formatted as
PG/HTML, follow it with a star:


    [@ some_perl_expression() @]*

  -----------------------------------------------------------------------
  Use it for                          Avoid it for
  ----------------------------------- -----------------------------------
  Computed intermediate values or     Basic formatting that PGML already
  helper-generated tables.            supports.

  Reusable PG helpers that return     Simple text that can be typed
  formatted output.                   directly.
  -----------------------------------------------------------------------

## Common uses

- Insert a computed intermediate value into a worked solution line.
- Insert a table or figure generated by helper functions.
- Use a specialized PG helper when PGML does not provide a direct
  syntax.

## Example: computed text inside math mode


    BEGIN_PGML
    To solve [: x + [$a] = [$b] x :], subtract [:x:] from both sides to get
    [: [$a] = ([$b]-1) x = [@ $b - 1 @] x :].
    END_PGML

## HTML in variables is escaped by default

If you store HTML markup in a Perl variable (for example,
`$label = "<span style='color:red'>Warning</span>"`) and insert it with
`[$label]`, PGML will escape the angle brackets and the student will see
the raw tags instead of styled text.

To pass HTML through unescaped, append an asterisk:


    [$label]*

This tells PGML to treat the variable\'s output as pre-formatted HTML,
the same trailing `*` used after `[@ ... @]*` eval blocks. Use it
whenever a variable contains `<span>`, `<div>`, `<sup>`, `<sub>`, or any
other HTML tags that should render as markup.

## Avoid MODES() inside eval blocks

A common mistake is to use `MODES(HTML => '...')` inside a `[@ ... @]`
eval block, expecting it to emit raw HTML. In practice, `MODES(...)`
returns `1` in eval context, so the student sees the number 1 instead of
the intended content.

If you need mode-dependent output, build it in the Perl setup section
and insert the result with `[$var]*`, or use PGML tag wrappers and raw
HTML outside eval blocks.

## MathJax color commands

TeX color macros such as `\color{}` and `\textcolor{}` do not reliably
render in PGML because MathJax may wrap them in `tex2jax_ignore` spans.
If you need colored text in a prompt, use HTML
`<span style="color:...">` instead. For a fuller discussion of MathJax
rendering constraints, see [Section 6.1](/@go/page/555723).

## Blocked HTML tags

PGML\'s HTML whitelist does not allow raw `<table>`, `<tr>`, `<td>`, or
`<th>` tags. If you write them in PGML output they will be stripped or
trigger warnings. Use `niceTables.pl` for any tabular layout. For more
on the tag whitelist and workarounds, see [Section
6.2](/@go/page/555724).

## Images and links (LibreTexts constraint)

Images can be inserted via helper functions and command substitution,
but the textbook content in this repository avoids HTML links because
LibreTexts provides its own table of contents and in-platform
navigation. Keep prompts self-contained and do not rely on linking out
to other pages.

Treat this as an advanced escape hatch: keep substitutions small,
readable, and easy to test.

**Next, depending on what you are doing:**

- If you only need a data table, go to [Section 3.4](/@go/page/555706).
- If you need a blank that grades correctly, go to [Section
  3.2](/@go/page/555704).
- If you are writing a workflow prompt, go to [Section
  3.3](/@go/page/555705).

---

# 04_Breaking_Down_the_Components/4.0-Index

------------------------------------------------------------------------
  Section        What it controls             What to check when debugging
  -------------- ---------------------------- ----------------------------
  OPL header     Metadata, searchability, and Missing TITLE/DESCRIPTION or
                 attribution.                 empty tags.

  Preamble       Macros, rendering switches,  Missing macro files, wrong
                 and global knobs.            load order, or disabled
                                              features.

  Setup          Values, constraints,         Choice list mismatches,
                 answers, and graders.        wrong correct answer, or
                                              grading mistakes.

  Statement      PGML prompt text, structure, Blank binding, missing
                 and blanks.                  inserts, or formatting
                                              breaks.

  Solution       Explanations, trust, and     Mismatch between solution
                 grading alignment.           conventions and the checker.
  ------------------------------------------------------------------------

Chapter 4 is a single worked problem sliced into OPL Header, Preamble,
Setup, Statement, Solution, and a Put it together workflow page. It
mirrors the OpenWeBWorK PG sample-problem structure while acknowledging
the five-section reality so you can scan each layer quickly and edit the
right section first.

This chapter is not teaching new syntax. It is teaching how to read a
working WeBWorK problem so you know where to edit safely.

The five parts of a problem are visually distinguished throughout this
chapter so you can spot where an edit belongs at a glance.

Running example: a short multiple-choice prompt with two radio-button
blanks, one vertical and one horizontal.

Instead of treating a problem as a block of code, this chapter treats it
as five parts that each have a job and each fail in predictable ways.
The goal is not to memorize syntax, but to build a reliable editing
habit: change one part, test it quickly, and keep the file readable for
the next person.

## One-screen anatomy (table version)

  -----------------------------------------------------------------------
  Section name    What readers usually change What usually breaks
  --------------- --------------------------- ---------------------------
  OPL header      TITLE, keywords, DBsubject  Missing DESCRIPTION or
                  tags.                       empty tags.

  Preamble        Macro list, display         Missing macro file, wrong
                  options, parser features.   load order, or missing
                                              feature.

  Setup           Answer objects, choice      Choice list mismatches or a
                  lists, and correctness      wrong correct answer.
                  rules.                      

  Statement       Story wording, tables,      Unbound blanks, missing
                  blanks, formatting.         variables, malformed PGML.

  Solution        Explanation steps, rounding Solution shows a different
                  notes, units.               convention than the
                                              checker.
  -----------------------------------------------------------------------

If ADAPT reports only a generic error, do a fast local render from
[Chapter 7](/@go/page/555731) to get a line number before you
troubleshoot the section tables below.

## Section pages

- [Section 4.1](/@go/page/555709) -- Full file (reference copy)
- [Section 4.2](/@go/page/557383) -- OPL Header
- [Section 4.3](/@go/page/555710) -- Preamble
- [Section 4.4](/@go/page/555711) -- Setup
- [Section 4.5](/@go/page/555712) -- Statement
- [Section 4.6](/@go/page/555713) -- Solution
- [Section 4.7](/@go/page/555741) -- Putting it together

## Practical edit map

  -----------------------------------------------------------------------
  Task                  Where to edit            Fast check
  --------------------- ------------------------ ------------------------
  Change options        Setup (choice lists)     Render and confirm the
                                                 correct label still
                                                 matches.

  Change prompt wording Statement (PGML)         Confirm each blank still
                                                 has an answer attached.

  Add another blank     Setup then Statement     Verify the new blank
                                                 label maps to the right
                                                 answer.

  Change the correct    Setup (answer object)    Confirm the Solution
  answer                                         shows the same label.
  -----------------------------------------------------------------------

## Section snapshots

**OPL header**

Why this exists: it makes the problem searchable and credits the author.

+-----------------------------------+-----------------------------------+
| Common edits                      | Common failures                   |
+===================================+===================================+
| - Update TITLE or DESCRIPTION.    | - Missing DESCRIPTION block.      |
| - Adjust DBsubject tags.          | - Empty or mismatched tags.       |
+-----------------------------------+-----------------------------------+

**Preamble**

Why this exists: it declares the macros and global options that make the
rest of the file possible.

+-----------------------------------+-----------------------------------+
| Common edits                      | Common failures                   |
+===================================+===================================+
| - Add or remove macro files.      | - Macro file not loaded.          |
| - Enable a parser or display      | - Macro load order hides a        |
|   option.                         |   feature.                        |
+-----------------------------------+-----------------------------------+

**Setup**

Why this exists: it defines the values, constraints, and answer objects
that the PGML uses.

+-----------------------------------+-----------------------------------+
| Common edits                      | Common failures                   |
+===================================+===================================+
| - Edit choice lists or correct    | - Correct answer no longer        |
|   answers.                        |   matches the list.               |
| - Adjust layout or ordering       | - Statement points to the wrong   |
|   options.                        |   answer object.                  |
+-----------------------------------+-----------------------------------+

**Statement**

Why this exists: it is the PGML prompt students read, including data,
structure, and blanks.

+-----------------------------------+-----------------------------------+
| Common edits                      | Common failures                   |
+===================================+===================================+
| - Rewrite the story or add a data | - Blank missing its attached      |
|   table.                          |   answer.                         |
| - Insert or remove answer blanks. | - Variable used before it is      |
|                                   |   defined.                        |
+-----------------------------------+-----------------------------------+

**Solution**

Why this exists: it shows the grading target and builds trust without
becoming a second lecture.

+-----------------------------------+-----------------------------------+
| Common edits                      | Common failures                   |
+===================================+===================================+
| - Clarify the correct option or   | - Solution names a different      |
|   rationale.                      |   option.                         |
| - Explain how the choice is       | - Solution label does not match   |
|   determined.                     |   grading.                        |
+-----------------------------------+-----------------------------------+

{{template.ShowOrg()}}

---

# 04_Breaking_Down_the_Components/4.1-Full_file

------------------------------------------------------------------------
  Section        What it controls             What to check when debugging
  -------------- ---------------------------- ----------------------------
  OPL header     Metadata, searchability, and Missing TITLE/DESCRIPTION or
                 attribution.                 wrong DBsubject tags.

  Preamble       Macros, rendering switches,  Missing macro files, wrong
                 and global knobs.            load order, or disabled
                                              features.

  Setup          Values, constraints,         Bad ranges, unit mismatches,
                 answers, and graders.        or tolerance mistakes.

  Statement      PGML prompt text, structure, Blank binding, missing
                 and blanks.                  inserts, or formatting
                                              breaks.

  Solution       Explanations, trust, and     Mismatch between solution
                 grading alignment.           conventions and the checker.
  ------------------------------------------------------------------------

This page shows the full problem file as a reference copy so you can see
the entire flow from top to bottom. For an overview of the five
sections, see [Section 2.4](/@go/page/488658). The prompt text uses
[PGML](/@go/page/488660) (Chapter 3). Read the file once as a story:
macros are loaded, values are chosen, the prompt is written, answers are
graded, and a solution explains the work.

When you start editing, avoid making changes on this page directly. Use
the section pages to make one targeted change at a time, then come back
here to confirm that the full file still reads cleanly and that values
and answers are consistent throughout.

As you read, notice which lines are structural and which lines are
content. Structural lines are macro loading and section delimiters;
content lines are the prompt text, choice lists, and the explanation in
the solution.

## Section anchors (reference map)

Use this table to find the line where each section starts and ends. When
debugging, start by identifying which section contains the error, then
jump to the section-specific page for detailed guidance.

  ---------------------------------------------------------------------------
  Section      Starts at       Ends at             One-line description
  ------------ --------------- ------------------- --------------------------
  OPL header   \## TITLE(\...) \##                 Metadata that makes the
                               Institution(\...)   problem searchable.

  Preamble     \# =====        \# ===== SETUP      Loads macros and switches
               PREAMBLE =====  =====               that unlock features.

  Setup        \# ===== SETUP  \# ===== STATEMENT  Defines values,
               =====           =====               constraints, and answer
                                                   objects.

  Statement    \# =====        \# ===== SOLUTION   Contains the PGML prompt
               STATEMENT ===== =====               students read.

  Solution     \# =====        ENDDOCUMENT();      Explains the target and
               SOLUTION =====                      matches the grading rules.
  ---------------------------------------------------------------------------

Each section page (4.2 through 4.6) walks through the purpose, common
edits, and failure patterns for that part of the file. Start with the
section closest to your error. This page is a reference copy so you can
see the whole file in one place after you make changes in the
section-specific pages.

The tables below give you a one-line summary of what each section does,
what you typically edit there, and what fails most often.

## Section quick reference

**OPL header**

Why this exists: it documents metadata for search and attribution before
any code runs.

  -----------------------------------------------------------------------
  Common edits                        Common failures
  ----------------------------------- -----------------------------------
  Update TITLE, KEYWORDS, and         Missing DESCRIPTION or empty tags.
  DBsubject tags.                     

  -----------------------------------------------------------------------

**Preamble**

Why this exists: it declares the macros and global options that make the
file render.

  -----------------------------------------------------------------------
  Common edits                        Common failures
  ----------------------------------- -----------------------------------
  Add or remove a macro file.         Missing macro that defines a
                                      feature.

  -----------------------------------------------------------------------

**Setup**

Why this exists: it defines the answer objects and correct choices.

  -----------------------------------------------------------------------
  Common edits                        Common failures
  ----------------------------------- -----------------------------------
  Edit choice lists or correct        Correct answer no longer matches
  answers.                            the list.

  -----------------------------------------------------------------------

**Statement**

Why this exists: it is the PGML prompt with readable structure and
blanks.

  -----------------------------------------------------------------------
  Common edits                        Common failures
  ----------------------------------- -----------------------------------
  Rewrite the story or add a table.   Blank not bound to an answer.

  -----------------------------------------------------------------------

**Solution**

Why this exists: it explains the grading target and the method.

  -----------------------------------------------------------------------
  Common edits                        Common failures
  ----------------------------------- -----------------------------------
  Clarify the correct option or       Solution label does not match
  rationale.                          grading.

  -----------------------------------------------------------------------

## Complete file (reference copy)

This is the complete worked example assembled from sections 4.2 through
4.6. Read it once as a story \-- macros load, values are chosen, the
prompt appears, answers are graded, and the solution explains the work.


    # ===== OPL HEADER =====
    ## TITLE('Color choice using radio buttons')
    ## DESCRIPTION
    ## Select the correct color label from two radio button formats and confirm the choice labels.
    ## ENDDESCRIPTION
    ## KEYWORDS('radio buttons','choice list','PGML prompt')
    ## DBsubject('Biochemistry')
    ## DBchapter('Lab techniques')
    ## DBsection('Reporting conventions')
    ## Date('2026-01-28')
    ## Author('Example author')
    ## Institution('Example institution')

    # ===== PREAMBLE =====
    DOCUMENT();

    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    # ===== SETUP =====
    $radio1 = RadioButtons(
        [ 'Red', 'Blue', 'Green', 'None of these' ],
        'Blue',
    );

    $radio2 = RadioButtons(
        [ 'Red', 'Blue', 'Green', 'None of these' ],
        2,
        separator => $SPACE x 5
    );

    # ===== STATEMENT =====
    BEGIN_PGML
    My favorite color is

    [_]{$radio1}

    The same question with horizontal options:

    My favorite color is [_]{$radio2}
    END_PGML

    # ===== SOLUTION =====
    BEGIN_PGML_SOLUTION
    The correct answer to the first is [$radio1->correct_ans].

    The correct answer to the second is [$radio2->correct_ans].
    END_PGML_SOLUTION

    ENDDOCUMENT();

---

# 04_Breaking_Down_the_Components/4.2-OPL_Header

This section explains the OPL header for the worked example and shows
how to pick biology-appropriate classification tags. The header comes
before `DOCUMENT()` and acts as the metadata \"section zero\" for the
problem.

**Use this page when:** you are writing metadata for a new problem or
reviewing a problem before publishing.

## Worked example header

This is the complete OPL header for the worked example in Chapter 4.


    ## TITLE('Color choice using radio buttons')
    ## DESCRIPTION
    ## Select the correct color label from two radio button formats and confirm the choice labels.
    ## ENDDESCRIPTION
    ## KEYWORDS('radio buttons','choice list','PGML prompt')
    ## DBsubject('Biochemistry')
    ## DBchapter('Lab techniques')
    ## DBsection('Reporting conventions')
    ## Level(2)
    ## Date('2026-01-28')
    ## Author('Example author')
    ## Institution('Example institution')
    ## Language(en)

Customize the TITLE, DESCRIPTION, KEYWORDS, and classification fields to
match your problem\'s content and subject area.

## Field checklist

  ---------------------------------------------------------------------------------
  Field                           What it should contain   Common mistakes
  ------------------------------- ------------------------ ------------------------
  TITLE                           Short, student-facing    Too long or story-like
                                  task title.              titles.

  DESCRIPTION                     2 to 3 sentences         No constraints or overly
                                  describing the task and  long explanations.
                                  constraints.             

  KEYWORDS                        3 to 5 concept or        Story nouns instead of
                                  technique keywords.      concepts.

  DBsubject/DBchapter/DBsection   Life science             Leaving these blank or
                                  classification strings.  too generic.

  Level                           Bloom\'s taxonomy level  Omitted or set to wrong
                                  (1-6).                   cognitive level.

  Date/Author/Institution         Attribution fields for   Omitted attribution.
                                  reuse.                   

  Language                        ISO 639-1 code (e.g.,    Omitted entirely.
                                  `en`).                   
  ---------------------------------------------------------------------------------

## How this header fits into the problem structure

The OPL header is \"section zero\" - it comes before `DOCUMENT()` and
exists outside the traditional four-section structure (Preamble, Setup,
Statement, Solution). Think of it as the problem\'s passport: it makes
the problem searchable, classifiable, and reusable in problem banks.

### Five-section reality

1.  **Section 0: OPL Header** (metadata comments, before DOCUMENT)
2.  **Section 1: Preamble** (DOCUMENT through loadMacros)
3.  **Section 2: Setup** (Perl code before PGML)
4.  **Section 3: Statement** (BEGIN_PGML / END_PGML)
5.  **Section 4: Solution** (optional BEGIN_PGML_SOLUTION /
    END_PGML_SOLUTION)

Traditional PG documentation only lists four sections because it omits
the OPL header. However, for long-term reuse and problem bank
classification, the header is essential.

## Choosing biology classifications

The worked example uses `DBsubject('Biochemistry')` because the problem
context is lab-focused. Here\'s how to choose classifications for other
biology problems.

### Classification decision guide

  -----------------------------------------------------------------------
  Problem type             DBsubject             DBchapter suggestion
  ------------------------ --------------------- ------------------------
  Dilution calculations,   Laboratory Techniques Solution preparation,
  spectrophotometry, gel                         Protein analysis, DNA
  analysis                                       analysis

  Enzyme kinetics, buffer  Biochemistry          Enzymes, Acids and
  pH, protein structure                          bases, Proteins

  Punnett squares,         Genetics              Mendelian inheritance,
  pedigrees, linkage                             Pedigree analysis,
                                                 Linkage

  Cell signaling, membrane Cell Biology          Signal transduction,
  transport, organelles                          Membranes, Organelles

  DNA replication,         Biology - molecular   DNA replication, Gene
  transcription,                                 expression, Translation
  translation                                    
  -----------------------------------------------------------------------

### Classification guidelines

- **Start with course context:** If the problem is for a Biochemistry
  course, use `DBsubject('Biochemistry')` even if it involves lab
  techniques.
- **Use existing tags:** Search your repository for similar problems and
  copy the exact classification strings to maintain consistency.
- **Be specific in DBsection:** Instead of \"General concepts\", use
  \"Michaelis-Menten kinetics\" or \"Serial dilutions\".
- **Avoid empty strings:** Never leave DBsubject, DBchapter, or
  DBsection blank. Choose the closest existing label and revise later if
  needed.

## Quick reference: Header fields explained

### TITLE field

Student-facing title that appears in problem listings. Keep it under 80
characters and focus on the task, not the story wrapper. For detailed
guidance and good/bad examples, see [Section 2.2](/@go/page/557378).

**Example for worked problem:**
`TITLE('Color choice using radio buttons')`

### DESCRIPTION block

Instructor-facing summary (2-3 sentences) that describes the task,
constraints (units, rounding), and provenance if adapted from another
source. For templates and biology examples, see [Section
2.2](/@go/page/557378).

**Example for worked problem:** The description mentions \"radio button
formats\" and \"choice labels\" to clarify what students will interact
with.

### KEYWORDS field

3-5 technique or concept keywords that make the problem searchable.
Avoid story nouns and generic terms. For keyword selection process and
biology examples, see [Section 2.2](/@go/page/557378).

**Example for worked problem:**
`KEYWORDS('radio buttons','choice list','PGML prompt')` focuses on
interaction type and PGML features, not biology content (since this is a
demonstration problem).

### Attribution fields

Date, Author, and Institution provide credit and help track provenance
for long-term reuse. Always include these fields, even for internal
problems.

### Textbook provenance fields

When a problem is adapted from a textbook or other source, use these
fields to track the original. Number the tags (TitleText1, TitleText2,
etc.) to map to multiple texts when appropriate.


    ## TitleText1('Title of source')
    ## EditionText1('Edition')
    ## AuthorText1('Author(s)')
    ## Section1('Section identifier')
    ## Problem1('Problem identifier')

If adapted, also state that in the DESCRIPTION block (e.g., \"Adapted
from \...\").

## Level field: Bloom\'s taxonomy

The `Level(...)` field uses a 1-6 scale aligned to Bloom\'s revised
taxonomy. This field classifies the cognitive demand of the problem and
is required.

  ------------------------------------------------------------------------
  Level    Category       Description
  -------- -------------- ------------------------------------------------
  1        Remember       Recall a term, definition, or basic fact. Verbs:
                          recall, define, label, list, identify.

  2        Understand     Describe, explain, or classify a concept. Verbs:
                          explain, summarize, interpret, classify.

  3        Apply          Use rules or methods in a direct way. Verbs:
                          apply, use, determine, solve.

  4        Analyze        Interpret data and connect to conclusions.
                          Verbs: analyze, compare, contrast, infer.

  5        Evaluate       Justify choices or critique evidence. Verbs:
                          evaluate, justify, critique, defend.

  6        Create         Design or propose something new. Verbs: design,
                          propose, formulate, develop.
  ------------------------------------------------------------------------

The worked example is Level 2 (Understand) because students classify
color labels from given options. For the full Bloom\'s taxonomy scale
with biology-specific examples, see [Section 2.2](/@go/page/557378).

## Language field

Use ISO 639-1 language codes. This field is required. For English:


    ## Language(en)

## License comments

Include a license comment block at the top of every problem file for
proper attribution and reuse. OPL does not define a standard license
tag. Use plain comment lines (single `#`) to state licensing. This is
not an OPL tag but is required for the repository.


    # This work is licensed under CC BY 4.0 (Creative Commons Attribution 4.0
    # International License).
    # https://creativecommons.org/licenses/by/4.0/
    # Source code portions are licensed under LGPLv3.

## Cross-references for detailed guidance

- **[Section 2.2](/@go/page/557378):** Comprehensive OPL header guidance
  with biology examples, decision trees, and good/bad comparisons.
- **Appendix 90.1:** Complete problem templates with pre-filled OPL
  headers you can copy and adapt.
- **Next sections in Chapter 4:** After the header, see [4.3
  Preamble](/@go/page/555710), [4.4 Setup](/@go/page/555711), [4.5
  Statement](/@go/page/555712) for how each section builds on the
  metadata.

## Common mistakes in problem context

- **Forgetting to update the header after modifying the problem:** If
  you change a dilution problem to a genetics problem, update DBsubject,
  DBchapter, KEYWORDS, and DESCRIPTION.
- **Copying header from unrelated problem:** Always customize TITLE,
  DESCRIPTION, and classification tags to match the new problem\'s
  actual content.
- **Smart quotes in header:** Use plain ASCII quotes (`'`), not curly
  quotes (`'` or `'`). Smart quotes break OPL parsing tools.
- **Empty classification fields:** Never leave DBsubject, DBchapter, or
  DBsection empty. Pick the closest existing tag and revise later if
  needed.

## Apply it today

- Check that every problem has TITLE and DESCRIPTION before you edit the
  prompt.
- Update the DBsubject tags whenever the scientific context changes.
- Use existing classification strings from your repository to maintain
  consistency.
- Cross-reference [Section 2.2](/@go/page/557378) for detailed field
  guidance and biology examples.
- Use templates from Appendix 90.1 for pre-filled OPL headers.

---

# 04_Breaking_Down_the_Components/4.3-Preamble

**Preamble**

The Preamble is the environment setup for the problem. It loads the
macro files that make PGML work and unlocks specific interaction
patterns the rest of the file assumes exist. For a reference list of
commonly used macros, see [Section 2.5](/@go/page/488659). For
background on PG files, see [Section 2.3](/@go/page/488657).

When a problem fails to load with a generic error, the cause is almost
always a missing or mismatched macro in the preamble. This section is
boring when it works and unforgiving when it does not, so most authors
touch it last, not first.

## How to read this code

When reading the preamble, ignore the story of the problem entirely.
This section exists to answer one question only: what tools does this
problem need in order to render and grade correctly. If something fails
to load, displays as plain text, or shows missing widgets, the cause is
almost always here.

The excerpt below is the exact preamble used in the worked example. It
shows the macro files that are loaded before any values or text are
defined.


    DOCUMENT();

    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl"
    );

**Line notes**

  -------------------------------------------------------------------------------
  Line or snippet           What it does                    What you would change
                                                            first
  ------------------------- ------------------------------- ---------------------
  `DOCUMENT();`             Initializes the problem file so Almost never changed.
                            WeBWorK knows where it begins.  

  `PGstandard.pl`           Provides core PG functionality  Always required.
                            used by nearly all problems.    

  `PGML.pl`                 Enables PGML formatting and     Remove only if
                            answer blanks.                  converting away from
                                                            PGML.

  `parserRadioButtons.pl`   Enables radio button answer     Add or remove when
                            widgets.                        changing interaction
                                                            type.

  `PGcourse.pl`             Loads course-level helpers and  Usually left alone.
                            defaults.                       
  -------------------------------------------------------------------------------

A common mistake is copying an example from elsewhere and missing a
macro that enables a widget. When that happens, the problem often
renders with no useful error message unless you test locally.

Why this exists: it declares which macro files and features the problem
can use.

+-----------------------------------+-----------------------------------+
| Common edits                      | Common failures                   |
+===================================+===================================+
| - Add a macro to enable a new     | - A feature is missing because    |
|   interaction.                    |   the macro is not loaded.        |
| - Remove a macro that is not      | - Load order masks a macro or     |
|   used.                           |   parser option.                  |
+-----------------------------------+-----------------------------------+

## Macro selection (what to load)

  -------------------------------------------------------------------------------------
  Macro                   What it enables When you need it Common failure Canonical
                                                                          example
  ----------------------- --------------- ---------------- -------------- -------------
  PGstandard.pl           Core PG         Always (baseline Undefined      OpenWeBWorK
                          functions and   PG utilities).   basic          PG samples:
                          helpers.                         functions.     most core
                                                                          examples.

  PGML.pl                 PGML prompt     Any PGML-first   BEGIN_PGML     OpenWeBWorK
                          blocks and      prompt.          fails or       PG samples:
                          inserts.                         renders raw    PGML intro
                                                           text.          pages.

  parserRadioButtons.pl   Radio-button    Single-correct   Radio buttons  OpenWeBWorK
                          answer widgets. multiple choice  do not render. PG samples:
                                          prompts.                        radio button
                                                                          techniques.

  PGcourse.pl             Course macros   You rely on      Custom helper  OpenWeBWorK
                          and shared      course-wide      not found.     PG samples:
                          helpers.        helpers.                        course macro
                                                                          usage.
  -------------------------------------------------------------------------------------

For radio-button interactions, load `parserRadioButtons.pl` and mirror
the official radio button technique pages in the OpenWeBWorK PG samples
so the UI matches the pattern you want.

Useful reference samples include parserMultiAnswer and
NumericalTolerance in the OpenWeBWorK PG samples, which show canonical
patterns for coordinated blanks and tolerance handling when you move
beyond single-choice prompts.

Some older examples use legacy macros or interaction widgets that still
appear online; prefer the patterns shown in the official PG sample
problems when choosing an interaction style.

## When it breaks

  -----------------------------------------------------------------------
  Symptom             Likely cause              Fix
  ------------------- ------------------------- -------------------------
  Macro not found     Missing macro file in     Add the macro and keep
  error               `loadMacros()`.           load order consistent.

  Choice widget       Radio button macro file   Load
  renders as plain    not loaded.               `parserRadioButtons.pl`
  text                                          in the Preamble.

  PGML block not      Missing `PGML.pl`.        Load `PGML.pl` before the
  recognized                                    PGML block.
  -----------------------------------------------------------------------

## Broken example: missing macro for the interaction

This problem fails before the statement even renders. The author copied
a radio button example but did not load the macro that provides the
widget. In ADAPT, this often appears as a generic error with no line
number.


    DOCUMENT();

    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "PGcourse.pl"
    );

Later in the file, the setup uses `RadioButtons`.

**What went wrong**

- The interaction widget exists in setup, but the macro that defines it
  was never loaded.
- The PG file parses, but rendering fails when the widget is
  encountered.
- ADAPT typically reports a generic error loading the problem.

**How to recognize it**

- The file worked in another problem you copied from.
- The error appears before any text renders.
- Local rendering reports an undefined subroutine or missing macro.

**How to fix it**

Add the missing macro to `loadMacros()` and re-render immediately. This
is why preamble problems should always be tested locally before import.

---

# 04_Breaking_Down_the_Components/4.4-Setup

**Setup**

Setup is where a general prompt becomes a specific, randomized instance.
This is where you define values, choose realistic options, and create
answer objects for the blanks in the Statement. For randomization
patterns and best practices, see [Section 6.5](/@go/page/555727).
Variables defined here are inserted into the prompt using [command
substitution](/@go/page/555708) (Section 3.6). For a catalog of question
types and the widgets they use, see [Chapter 5](/@go/page/488662).

Setup is the section most life science instructors edit. Think of it as
the lab notebook for the problem: if the values, units, or tolerances
are wrong here, no amount of prompt editing will fix grading.

## How to read this code

The setup section is where the abstract idea of the problem becomes
concrete. This is where values are chosen, constrained, and combined
into the exact targets the grader will check. If a problem behaves
differently across seeds or produces surprising answers, this is the
first place to look.

The excerpt below defines the answer objects used later in the
statement. Nothing here is visible to students, but everything here
controls grading behavior.


    $radio1 = RadioButtons(
        [ 'Red', 'Blue', 'Green', 'None of these' ],
        'Blue',
    );

    $radio2 = RadioButtons(
        [ 'Red', 'Blue', 'Green', 'None of these' ],
        2,
        separator => $SPACE x 5
    );

**Line notes**

  --------------------------------------------------------------------------------------------------
  Line or snippet                                 What it does                 What you would change
                                                                               first
  ----------------------------------------------- ---------------------------- ---------------------
  `RadioButtons(...)`                             Creates a radio-button       Change this if you
                                                  answer object.               switch interaction
                                                                               types.

  `[ 'Red', 'Blue', 'Green', 'None of these' ]`   Defines what students can    Edit when changing
                                                  select.                      the story or options.

  `'Blue'`                                        Sets the correct answer by   Use this when clarity
                                                  value.                       matters more than
                                                                               indexing.

  `2`                                             Sets the correct answer by   Use when randomizing
                                                  index (starting at 0).       or reordering
                                                                               choices.

  `separator => $SPACE x 5`                       Controls layout spacing.     Adjust for
                                                                               readability only.
  --------------------------------------------------------------------------------------------------

A frequent source of confusion is changing the prompt text without
updating the corresponding answer object. Keeping all answer definitions
together in setup makes these mismatches easier to spot.

Why this exists: it turns a story into answer objects and grading rules
that the PGML can use.

+-----------------------------------+-----------------------------------+
| Common edits                      | Common failures                   |
+===================================+===================================+
| - Edit choice lists or correct    | - Correct answer no longer        |
|   answers.                        |   matches the choice list.        |
| - Adjust layout spacing or        | - Statement references the wrong  |
|   ordering.                       |   answer object.                  |
+-----------------------------------+-----------------------------------+

Try it now: change one choice, render a variant, and confirm the correct
answer still matches the intended option and the layout is readable.

## Answer objects and choices

  ---------------------------------------------------------------------------
  Answer object     Choice list                  Correct      Why it exists
                                                 answer       
  ----------------- ---------------------------- ------------ ---------------
  radio1            Red, Blue, Green, None of    Blue (by     Single-choice
                    these                        value)       prompt with a
                                                              clear correct
                                                              label.

  radio2            Red, Blue, Green, None of    Index 2      Same options
                    these                                     with a
                                                              horizontal
                                                              layout.
  ---------------------------------------------------------------------------

Answer targets are the glue between Setup and Statement: these are the
answer objects attached to blanks in the prompt.

## Answer targets

  -----------------------------------------------------------------------
  Answer object   Correct answer      How it is set       Used by which
                                                          blank
  --------------- ------------------- ------------------- ---------------
  radio1          Blue                Value string        radio1 blank

  radio2          Index 2             Index in list       radio2 blank
                                      (0-based)           
  -----------------------------------------------------------------------

## Answer object options

  -----------------------------------------------------------------------
  Option              What it controls          When to use it
  ------------------- ------------------------- -------------------------
  Correct answer by   Chooses the correct       When clarity matters more
  value               option by its label.      than index tracking.

  Correct answer by   Chooses the correct       When you randomize or
  index               option by position.       reorder choices.

  separator =\>       Spacing between choices.  When horizontal layout
  \$SPACE x 5                                   needs breathing room.
  -----------------------------------------------------------------------

## Broken example: correct answer does not match the story

This problem renders and accepts input, but grading behaves
unexpectedly. Students select the correct option according to the
prompt, but the system marks it wrong.


    $radio = RadioButtons(
        [ 'ATP', 'ADP', 'AMP' ],
        'AMP',
    );

The statement later asks which molecule has the highest energy.

**What went wrong**

- The story implies ATP is correct.
- The setup defines AMP as the correct answer.
- The grader is doing exactly what it was told.

**How to recognize it**

- Multiple students report being marked wrong for the same choice.
- Previewing the problem shows consistent wrong grading.
- The solution displays a different answer than the prompt implies.

**How to fix it**

Always read the setup and the statement back to back. When changing the
story, update the setup first, then confirm the statement still matches.

Keep the choice lists and correct answers aligned with the statement
text so the grading intent stays obvious.

---

# 04_Breaking_Down_the_Components/4.5-Statement

**Statement**

The Statement is the student-facing prompt written in
[PGML](/@go/page/488660) (Chapter 3). It is where the story, data, and
tasks become visible, and where each blank must be tied to one answer
object from Setup.

The Statement never grades anything. Blanks are just hooks into Setup,
and PGML reads top to bottom like a worksheet, not like code. If
something grades incorrectly, the cause is almost never here, even if
the formatting looks scary.

## How to read this code

The statement is the only part of the file that students actually read.
Your goal here is to keep the text readable while making sure every
blank is unambiguous and attached to the correct answer checker. PGML
allows you to do this without mixing formatting logic into setup code.

The excerpt below shows the full statement used in the example,
including how answer objects are inserted into the text.


    BEGIN_PGML
    My favorite color is

    [_]{$radio1}

    The same question with horizontal options:

    My favorite color is [_]{$radio2}
    END_PGML

**Line notes**

  ------------------------------------------------------------------------
  Line or snippet       What it does                 What you would change
                                                     first
  --------------------- ---------------------------- ---------------------
  `BEGIN_PGML`          Starts PGML rendering.       Required for PGML
                                                     formatting.

  Plain text            Displays directly to         Edit freely for
                        students.                    clarity.

  `[_]{$radio1}`        Inserts a blank bound to an  Reorder or duplicate
                        answer checker.              blanks here.

  `{$radio2}`           References a second answer   Update if setup
                        object.                      changes.

  `END_PGML`            Ends the PGML block.         Always required.
  ------------------------------------------------------------------------

If grading works but students are confused, the problem is usually here
rather than in setup. Read the statement out loud and check whether each
blank clearly signals what kind of answer is expected.

Think of the Statement as a contract. The text you show here must match
what the checker accepts, or students will feel the grading is arbitrary
even when their reasoning is right. Example: the prompt asks for one
choice, but the blank is tied to a different answer object.

Choose the structure that reduces reading load: use short paragraphs for
a single task, lists for steps, and tables for multi-value data. For
emphasis and color options, see [Section 6.1](/@go/page/555723). If a
prompt feels hard to scan, structure is usually the fix, not more words.

Why this exists: it is the student-facing prompt that ties the story to
the answer blanks.

+-----------------------------------+-----------------------------------+
| Common edits                      | Common failures                   |
+===================================+===================================+
| - Rewrite the story in plain      | - Blank not attached to the       |
|   language.                       |   intended answer object.         |
| - Reorder blanks or add a second  | - Answer object name does not     |
|   prompt variant.                 |   match setup.                    |
+-----------------------------------+-----------------------------------+

Fast test: render one seed, enter the expected answer, confirm grading,
then change the seed and repeat.

## Blanks map

  ------------------------------------------------------------------------
  Blank label    What it asks for      Answer object     Student format
                                                         expectations
  -------------- --------------------- ----------------- -----------------
  radio1         Single-choice         \$radio1          Select one
                 selection                               option.

  radio2         Single-choice         \$radio2          Select one
                 selection                               option.
                 (horizontal)                            
  ------------------------------------------------------------------------

Blank binding smell test: if a blank is visible but always marks wrong,
confirm it is attached to an answer object defined in Setup.

## Broken example: blank attached to the wrong answer object

This is one of the most common PGML mistakes. The problem renders
cleanly, but answers are silently mismatched.


    BEGIN_PGML
    The enzyme with the highest activity is [_]{$radio2}.
    END_PGML

In setup, `$radio1` and `$radio2` are both defined, but `$radio2`
corresponds to a different question.

**What went wrong**

- The blank is bound to the wrong answer object.
- The prompt text and grading logic no longer refer to the same concept.
- There is no syntax error, so nothing warns the author.

**How to recognize it**

- The blank accepts input, but grading feels random.
- Swapping answers between blanks changes which one grades correctly.
- Reviewing setup reveals multiple answer objects with similar names.

**How to fix it**

Use consistent naming and keep the statement immediately adjacent to the
setup during editing. When in doubt, temporarily print `->correct_ans`
in the solution to confirm alignment.

Use tables only when there is real data to scan or compare, not to
simulate layout. Lists and short paragraphs are usually better for
narrative prompts.

## Structure patterns

  ------------------------------------------------------------------------
  Pattern        When to use                  Avoid when
  -------------- ---------------------------- ----------------------------
  Short          One clear story with 1 to 2  Steps are procedural or
  paragraphs     tasks.                       multi-part.

  Lists          Protocols or multi-step      The prompt is a single
                 directions.                  sentence.

  Tables         Real data or comparisons     Two values can be in plain
                 need scanning.               text.

  Inline math    Small substitutions and unit Equations are long or
                 checks.                      multi-line.
  ------------------------------------------------------------------------

For radio buttons and other choice-based inserts, load
`parserRadioButtons.pl` and follow the OpenWeBWorK technique samples for
multiple choice patterns, using those pages as the pattern directory.

MultiAnswer is an optional advanced variant for interdependent blanks;
use the `parserMultiAnswer.pl` documentation and its sample problem when
you need shared logic.

---

# 04_Breaking_Down_the_Components/4.6-Solution

**Solution**

The Solution is for trust and alignment, not grading. It shows students
what the system expected and helps instructors confirm that the checker
matches the stated method.

The solution does not affect grading, but students trust it more than
the grader. A correct grader with a confusing solution still feels
broken, and any mismatch creates disputes.

## How to read this code

The solution is not a second version of the prompt. It is a short
explanation that mirrors the grading logic so students can reconcile
their work with what the system checked. Solutions use the same [PGML
syntax](/@go/page/555703) (Section 3.1) as the statement block. A good
solution is compact, accurate, and consistent with the setup section.

The excerpt below shows the solution block used in the example.


    BEGIN_PGML_SOLUTION
    The correct answer to the first is [$radio1->correct_ans].

    The correct answer to the second is [$radio2->correct_ans].
    END_PGML_SOLUTION

**Line notes**

  --------------------------------------------------------------------------
  Line or snippet         What it does                 What you would change
                                                       first
  ----------------------- ---------------------------- ---------------------
  `BEGIN_PGML_SOLUTION`   Starts the solution block.   Required for PGML
                                                       solutions.

  Explanatory text        Describes the correct        Keep aligned with
                          reasoning.                   grading.

  `->correct_ans`         Retrieves the expected       Useful for debugging.
                          answer.                      

  Inline PGML             Formats output cleanly.      Match statement
                                                       style.

  `END_PGML_SOLUTION`     Ends the solution block.     Always required.
  --------------------------------------------------------------------------

If the solution disagrees with grading, students will trust the grader
and distrust the explanation. Keep the solution minimal and mechanically
consistent with the setup logic.

The solution must use the same conventions the checker uses. If the
checker expects the label \"Blue,\" the solution should show \"Blue,\"
not a shorthand label or a different ordering.

Why this exists: it clarifies the target, the method, and the reporting
format that the grader expects.

+-----------------------------------+-----------------------------------+
| Common edits                      | Common failures                   |
+===================================+===================================+
| - State the correct option in     | - Solution shows a different      |
|   plain language.                 |   label than the checker.         |
| - Add a short rationale for the   | - Solution implies a different    |
|   choice.                         |   set of choices.                 |
+-----------------------------------+-----------------------------------+

## Solution checklist

  ------------------------------------------------------------------------
  Include           Why                       One-sentence example
  ----------------- ------------------------- ----------------------------
  Restate the       Confirms the student is   \"The choices are Red, Blue,
  prompt            using the same choices.   Green, or None of these.\"

  State the correct Makes the target          \"The correct answer is
  choice            explicit.                 Blue.\"

  Short rationale   Connects the answer to    \"Blue matches the prompt\'s
                    the intent.               condition.\"

  Exact label       Prevents grading          \"Use the same label shown
                    mismatches.               in the options list.\"

  Format reminder   Keeps expectations clear. \"Select a single option.\"
  ------------------------------------------------------------------------

## Debugging alignment

Use this table as a quick alignment check: the solution should echo the
same conventions the checker uses so students see the expected format.

  -----------------------------------------------------------------------
  Grading expectation                 Solution alignment
  ----------------------------------- -----------------------------------
  Correct answer by value             Use the exact label from the choice
                                      list.

  Correct answer by index             Show the label, not the index.

  Reordered choice list               Mirror the displayed order or name
                                      the label.
  -----------------------------------------------------------------------

## Helpful feedback hooks (optional)

  -----------------------------------------------------------------------
  Hook                   Why it helps
  ---------------------- ------------------------------------------------
  Short rationale line   Reinforces why the correct option is correct.

  Distractor reminder    Helps students distinguish near-miss options.

  Format reminder        Signals that exactly one choice is expected.
  -----------------------------------------------------------------------

## Broken example: solution contradicts grading logic

This problem grades correctly, but the solution confuses students. The
explanation no longer matches what the system actually checked.


    BEGIN_PGML_SOLUTION
    The correct answer is ATP because it has the highest energy.
    END_PGML_SOLUTION

In setup, the answer checker expects ADP.

**What went wrong**

- The solution was written before the setup was finalized.
- The grading logic changed, but the explanation did not.
- Students see a contradiction between feedback and results.

**How to recognize it**

- Students say, \"The solution says X but I was marked wrong for X.\"
- Preview mode shows correct grading with an incorrect explanation.
- Instructors trust the solution text instead of the grader.

**How to fix it**

Treat the solution as a mirror of the grading logic, not an independent
explanation. When debugging, temporarily echo the computed answer in the
solution to verify consistency.

---

# 04_Breaking_Down_the_Components/4.7-Putting_it_together

Pick the change, edit the right section, render one seed to confirm
grading, then sweep a few seeds to catch edge cases. For the full
catalog of question types, see [Chapter 5](/@go/page/488662). For macro
reference details, see [Section 2.5](/@go/page/488659). Most failures
trace to missing macros, bad ranges, unbound blanks, or a mismatch
between prompt and checker.

When something goes wrong, the goal is not to fix the whole problem at
once. The goal is to identify which section owns the failure, edit only
that section, and render early and often before you return to ADAPT.

  ------------------------------------------------------------------------
  Section        What it controls             What to check when debugging
  -------------- ---------------------------- ----------------------------
  OPL header     Metadata, searchability, and Missing TITLE/DESCRIPTION or
                 attribution.                 empty tags.

  Preamble       Macros, rendering switches,  Missing macro files, wrong
                 and global knobs.            load order, or disabled
                                              features.

  Setup          Values, constraints,         Choice list mismatches,
                 answers, and graders.        wrong correct answer, or
                                              grading mistakes.

  Statement      PGML prompt text, structure, Blank binding, missing
                 and blanks.                  inserts, or formatting
                                              breaks.

  Solution       Explanations, trust, and     Mismatch between solution
                 grading alignment.           conventions and the checker.
  ------------------------------------------------------------------------

## Common edits (workflow map)

  ------------------------------------------------------------------------
  What you want to       Edit here first  Then verify here Fast test
  change                                                   
  ---------------------- ---------------- ---------------- ---------------
  Update metadata or     OPL header       Full file        Confirm tags
  subject tags                                             and description
                                                           are filled.

  Swap interaction type  Preamble         Statement        Check that the
                                                           widget renders.

  Change options or the  Setup            Solution         Confirm the
  correct answer                                           correct label
                                                           still matches.

  Add a new blank        Setup            Statement        Confirm the
                                                           blank shows the
                                                           right answer.

  Explain why the choice Solution         Statement        Check wording
  is correct                                               against the
                                                           choice list.
  ------------------------------------------------------------------------

## Preflight before ADAPT import

ADAPT errors are often generic, so local rendering is the first
diagnostic step when something fails to preview.

  -----------------------------------------------------------------------
  Check                                      Why it matters
  ------------------------------------------ ----------------------------
  Render locally ([Chapter                   Line numbers save time when
  7](/@go/page/555731)) if ADAPT gives only  a macro or PGML issue
  a generic error.                           appears.

  Preview 3 to 5 seeds.                      Catches impossible variants
                                             early.

  Scan option labels in prompt, blanks, and  Prevents silent grading
  solution.                                  mismatches.
  -----------------------------------------------------------------------

When you want to swap interaction types, use the techniques list in the
OpenWeBWorK PG samples as your menu of proven patterns.

## Complete example: biology RadioButtons problem

This complete problem demonstrates all five sections (OPL header,
preamble, setup, statement, and PGML prompt) working together. Copy this
template and modify the content for your own biology questions.


    ## TITLE('Identify an amino acid property')
    ## DESCRIPTION
    ## Select the amino acid that is nonpolar from a short list.
    ## Demonstrates RadioButtons with biology content.
    ## ENDDESCRIPTION
    ## KEYWORDS('amino acids','nonpolar','RadioButtons')
    ## DBsubject('Biochemistry')
    ## DBchapter('Amino Acids')
    ## DBsection('Classification')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    $rb = RadioButtons(
        [ 'Leucine', 'Glutamate', 'Lysine', 'Serine' ],
        'Leucine',
        labels        => 'ABC',
        displayLabels => 1,
    );

    BEGIN_PGML
    Which of the following amino acids has a nonpolar
    (hydrophobic) side chain?

    [_]{$rb}
    END_PGML

    ENDDOCUMENT();

---

# 05_Different_Question_Types/5.0-Index

This chapter is the bridge between WeBWorK authoring and using WeBWorK
inside ADAPT. It collects common question interaction patterns (question
types) and pairs them with a practical workflow and a short QA checklist
so you can ship reliable assignments without surprises.

Most biology and biochemistry prompts start as a story with a single
decision, a short label, or a short workflow. If the grading needs
robust math parsing, multiple equivalent forms, or algorithmic variants,
use PGML-first WeBWorK. If the task is recognition, labeling, or a short
protocol step check, these interaction types are usually faster to build
and easier to maintain.

Instructors usually lose time in two places: blank binding mistakes and
generic error testing loops. Use the [workflow and QA
page](/@go/page/555722) as the default finishing step, even when a
question looks correct in author view.

WeBWorK problems are authored using PG (a Perl-based setup layer) and
PGML (a markup layer for the student-facing prompt). In this guide, PG
is treated as minimal scaffolding and PGML is the default authoring
style.

Life-science-first emphasis: examples and checklists are written to
answer \"what breaks when the content is biology?\" and to prioritize
patterns that grade reliably for biology-style prompts. For advanced
techniques such as colored emphasis, table layouts, and matching with
two-column displays, see [Chapter 6](/@go/page/488663).

{{template.ShowOrg()}}

---

# 05_Different_Question_Types/5.1-Question_types_overview

This section introduces core question types used across many assessment
systems. These are often useful for concept checks, terminology, and
simple workflows that do not require WeBWorK-style answer parsing or
algorithmic randomization.

In this textbook, question types are treated as a practical authoring
skill: you learn the patterns in Chapter 5, and then [Chapter
6](/@go/page/488663) shows how to apply those patterns in specific
scientific subjects.

Use Multiple Choice when there is one best scientific claim and you can
write distractors that represent real misconceptions. Use Multiple
Answer when the concept is a set and you can define the set boundaries
clearly. Use Matching for term-to-meaning mapping, Fill in the Blank for
short labels with controlled variants, and Ordered List only when the
sequence is truly standard in your context.

Life science questions fail in predictable ways: naming conventions
drift, unit prefixes drift, and prompts quietly allow more than one
interpretation. When that risk is high, prefer recognition-style items
with explicit wording, or switch to WeBWorK answer checking where you
can enforce structure.

## How this fits a PGML-first course

- Use WeBWorK (PGML-first) for numeric and formula-based practice where
  robust parsing and answer checking matters.
- Use these question types for portable, simple interaction patterns
  (multiple choice, matching, ordering, fill-in-the-blank).

## Supported question types

- [Multiple Choice (MC)](/@go/page/555715)
- [Multiple Answer (MA)](/@go/page/555716)
- [Matching (MATCH)](/@go/page/555717)
- [Numerical Entry (NUM)](/@go/page/555718)
- [Fill-in-the-Blank (FIB)](/@go/page/555719)
- [Multi-Part Fill-in-the-Blank (MULTI_FIB)](/@go/page/555720)
- [Ordered List (ORDER)](/@go/page/555721)

## Science prompt style (recommended)

- Keep the story stable and short.
- Use explicit numbers and units in the prompt when relevant.
- Prefer tables for data instead of long prose when the problem is
  data-driven.
- For concept checks, write distractors that reflect common
  misconceptions.

## Input conventions

Each type is defined by a small set of inputs. The next sections show a
science example for each type using those inputs.

---

# 05_Different_Question_Types/5.2-Multiple_choice

Multiple Choice (MC) is best for a single conceptual decision where one
answer is clearly correct and the distractors represent plausible
misconceptions.

A good biology multiple choice item is really a single claim test. Write
the stem so the correct choice is correct for one reason, and each
distractor is wrong for one specific reason you would actually see on an
exam. If two choices are defensible under different assumptions, the
problem is the stem, not the students.

The most common break is mixed formats inside the choice list, like
fractions mixed with decimals or words mixed with symbols. Keep choices
parallel and decide your conventions first, then write distractors to
match that convention.

## Inputs

- `question_text` (str): the question prompt
- `choices_list` (list): answer choices
- `answer_text` (str): the correct answer

## Science example (genetics)

Use this type for a single decision, like recognizing a pattern in an
inheritance scenario.


    question_text:
      In a diploid organism, allele A is dominant to allele a.
      Two heterozygous parents (Aa x Aa) produce offspring.
      What fraction of offspring are expected to be homozygous recessive (aa)?

    choices_list:
      - 1/4
      - 1/2
      - 3/4
      - 1

    answer_text: 1/4

Official example (OpenWeBWorK PG samples):
[MultipleChoiceRadio](https://openwebwork.github.io/pg-docs/sample-problems/Misc/MultipleChoiceRadio.html).

## Preferred PGML pattern

Use `RadioButtons` with `parserRadioButtons.pl` (see [Section
2.5](/@go/page/488659) for macro loading) and attach the evaluator
inline in the PGML blank. This is the standard pattern for all multiple
choice questions. For statement-by-statement evaluation patterns, see
[Section 6.4](/@go/page/555726).


    loadMacros(
      "PGstandard.pl",
      "PGML.pl",
      "parserRadioButtons.pl",
      "PGcourse.pl",
    );

    $rb = RadioButtons(
      [ [ 'Red', 'Blue', 'Green' ], 'None of these' ],
      'Blue',
      labels        => 'ABC',
      displayLabels => 1,
      randomize     => 0,
    );

    BEGIN_PGML
    My favorite color is

    [_]{$rb}
    END_PGML

Key options:

- `labels => 'ABC'` gives each choice a consistent letter label.
- `displayLabels => 1` shows the letter labels to students.
- `randomize => 0` is the default and keeps the order you defined. Only
  enable randomization if you are safely mapping the correct answer.
- For horizontal layout, use `separator => $SPACE x 5` or an HTML
  spacing string.

## Complete working examples

**Genetics multiple choice** \-- Identify the expected fraction of
homozygous recessive offspring from a monohybrid cross.


    ## TITLE('Monohybrid cross outcome')
    ## DESCRIPTION
    ## Determine the expected fraction of homozygous recessive
    ## offspring from a cross between two heterozygous parents.
    ## ENDDESCRIPTION
    ## KEYWORDS('genetics','monohybrid cross','RadioButtons')
    ## DBsubject('Genetics')
    ## DBchapter('Mendelian Genetics')
    ## DBsection('Monohybrid Cross')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    $rb = RadioButtons(
        [ '1/4', '1/2', '3/4', '1' ],
        '1/4',
        labels        => 'ABC',
        displayLabels => 1,
    );

    BEGIN_PGML
    In a diploid organism, allele A is dominant to allele a.
    Two heterozygous parents (Aa x Aa) produce offspring.
    What fraction of offspring are expected to be homozygous
    recessive (aa)?

    [_]{$rb}
    END_PGML

    ENDDOCUMENT();

**Organelle identification** \-- Identify the organelle responsible for
protein synthesis.


    ## TITLE('Identify the protein synthesis organelle')
    ## DESCRIPTION
    ## Select the organelle that is the primary site of
    ## protein synthesis in eukaryotic cells.
    ## ENDDESCRIPTION
    ## KEYWORDS('cell biology','organelles','RadioButtons')
    ## DBsubject('Cell Biology')
    ## DBchapter('Organelles')
    ## DBsection('Function')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    $rb = RadioButtons(
        [ 'Ribosome', 'Golgi apparatus', 'Lysosome', 'Smooth ER' ],
        'Ribosome',
        labels        => 'ABC',
        displayLabels => 1,
    );

    BEGIN_PGML
    Which organelle is the primary site of protein synthesis
    in eukaryotic cells?

    [_]{$rb}
    END_PGML

    ENDDOCUMENT();

## Authoring notes

- Keep choices parallel in format (all fractions, all numbers, etc.).
- Use distractors that match common mistakes (for example confusing
  genotype vs phenotype).

---

# 05_Different_Question_Types/5.3-Multiple_answer

Multiple Answer (MA) is best when more than one choice is correct and
the learning objective includes recognizing a set of correct statements.
Unlike [Multiple Choice](/@go/page/555715), which expects a single best
answer, Multiple Answer requires students to identify all correct items.

Multiple answer works best when you can define membership in the set
using a rule students can apply. State \"Select all that apply\"
explicitly, keep the set small, and avoid choices that depend on
exceptions you did not teach. This type is excellent for wet lab
requirements and \"which statements are supported\" checks, but it
punishes ambiguity.

## Inputs

- `question_text` (str)
- `choices_list` (list)
- `answers_list` (list): list of correct answers

## Science example (molecular biology)


    question_text:
      Which of the following are typically required for a standard PCR reaction?
      Select all that apply.

    choices_list:
      - Template DNA
      - Primers
      - DNA polymerase
      - Restriction enzyme
      - dNTPs

    answers_list:
      - Template DNA
      - Primers
      - DNA polymerase
      - dNTPs

Official example (OpenWeBWorK PG samples):
[MultipleChoiceCheckbox](https://openwebwork.github.io/pg-docs/sample-problems/Misc/MultipleChoiceCheckbox.html).

## Checkbox macro availability

Checkbox macros are unreliable in the PG 2.17 renderer snapshot used by
this project (see [Section 2.5](/@go/page/488659) for available macros).
Do not use checkbox-style macros unless you have verified the macro
exists in the renderer and tested that it renders correctly.

## Preferred fallback pattern

Instead of checkboxes, use one `RadioButtons` or `PopUp` widget per
statement. Each statement becomes its own True/False or Yes/No decision,
and students answer all of them.


    loadMacros(
      "PGstandard.pl",
      "PGML.pl",
      "parserRadioButtons.pl",
      "PGcourse.pl",
    );

    $rb1 = RadioButtons([ 'Yes', 'No' ], 'Yes',
      labels => 'ABC', displayLabels => 1);
    $rb2 = RadioButtons([ 'Yes', 'No' ], 'Yes',
      labels => 'ABC', displayLabels => 1);
    $rb3 = RadioButtons([ 'Yes', 'No' ], 'No',
      labels => 'ABC', displayLabels => 1);

    BEGIN_PGML
    For each statement, select Yes if it is required for PCR.

    Template DNA: [_]{$rb1}

    Primers: [_]{$rb2}

    Restriction enzyme: [_]{$rb3}
    END_PGML

## Complete working examples

**PCR requirements** \-- Evaluate whether each component is required for
a standard PCR reaction using per-statement RadioButtons.


    ## TITLE('Identify PCR requirements')
    ## DESCRIPTION
    ## For each component, indicate whether it is required for
    ## a standard PCR reaction.
    ## ENDDESCRIPTION
    ## KEYWORDS('PCR','molecular biology','true false','RadioButtons')
    ## DBsubject('Molecular Biology')
    ## DBchapter('Techniques')
    ## DBsection('PCR')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    $rb1 = RadioButtons([ 'Yes', 'No' ], 'Yes');
    $rb2 = RadioButtons([ 'Yes', 'No' ], 'Yes');
    $rb3 = RadioButtons([ 'Yes', 'No' ], 'Yes');
    $rb4 = RadioButtons([ 'Yes', 'No' ], 'No');

    BEGIN_PGML
    For each component, select Yes if it is required for a
    standard PCR reaction.

    Template DNA: [_]{$rb1}

    Primers: [_]{$rb2}

    DNA polymerase: [_]{$rb3}

    Restriction enzyme: [_]{$rb4}
    END_PGML

    ENDDOCUMENT();

**Enzyme properties** \-- Evaluate true/false statements about general
enzyme characteristics.


    ## TITLE('Enzyme characteristics true or false')
    ## DESCRIPTION
    ## Evaluate whether each statement about enzyme properties
    ## is true or false.
    ## ENDDESCRIPTION
    ## KEYWORDS('enzymes','biochemistry','true false','RadioButtons')
    ## DBsubject('Biochemistry')
    ## DBchapter('Enzymes')
    ## DBsection('Properties')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    $tf = [ 'True', 'False' ];
    $rb1 = RadioButtons($tf, 'True');
    $rb2 = RadioButtons($tf, 'False');
    $rb3 = RadioButtons($tf, 'True');

    BEGIN_PGML
    For each statement, select True or False.

    1. Enzymes lower the activation energy of a reaction. [_]{$rb1}

    2. Enzymes are consumed during the reaction they catalyze. [_]{$rb2}

    3. Enzyme activity is affected by temperature and pH. [_]{$rb3}
    END_PGML

    ENDDOCUMENT();

## Authoring notes

- Say \"Select all that apply\" explicitly.
- Avoid trick items; keep the set small and clearly defined.

---

# 05_Different_Question_Types/5.4-Matching

Matching (MATCH) is best for vocabulary, functional associations, and
paired relationships. In science courses, it works well for mapping
terms to definitions or steps to outcomes.

Matching is strongest when the task is association, not recall of a
sentence from a glossary. Prompts should be short and choices should be
short, but the pairing should reflect a functional relationship students
use in biology. If the correct pairing is obvious from word shape alone,
add one distractor choice only when it forces actual thinking.

## Inputs

- `question_text` (str)
- `prompts_list` (list): items to be matched
- `choices_list` (list): possible matching answers

## Science example (biochemistry)


    question_text:
      Match each macromolecule class with the most typical monomer unit.

    prompts_list:
      - Proteins
      - Nucleic acids
      - Polysaccharides

    choices_list:
      - Amino acids
      - Nucleotides
      - Monosaccharides

Official example (OpenWeBWorK PG samples):
[Matching](https://openwebwork.github.io/pg-docs/sample-problems/Misc/Matching.html).
Macro reference:
[PGchoicemacros](https://openwebwork.github.io/pg-docs/pod/pg/macros/ui/PGchoicemacros.html).

## Preferred PGML pattern

Use `PopUp` from `parserPopUp.pl` and place each dropdown inline in PGML
next to its prompt. This gives a clean matching layout without legacy PG
macros.


    loadMacros(
      "PGstandard.pl",
      "PGML.pl",
      "parserPopUp.pl",
      "PGcourse.pl",
    );

    $popup1 = PopUp([ '?', 'Amino acids', 'Nucleotides', 'Monosaccharides' ],
      'Amino acids');
    $popup2 = PopUp([ '?', 'Amino acids', 'Nucleotides', 'Monosaccharides' ],
      'Nucleotides');
    $popup3 = PopUp([ '?', 'Amino acids', 'Nucleotides', 'Monosaccharides' ],
      'Monosaccharides');

    BEGIN_PGML
    Match each macromolecule class with its monomer.

    1. Proteins [_]{$popup1}
    2. Nucleic acids [_]{$popup2}
    3. Polysaccharides [_]{$popup3}
    END_PGML

For advanced matching layouts with tables or formatted columns, see
[Section 6.3](/@go/page/555725) (Matching Problems).

## Complete working examples

**Macromolecule matching** \-- Match each macromolecule class with its
monomer unit using PopUp dropdowns.


    ## TITLE('Match macromolecule classes to monomers')
    ## DESCRIPTION
    ## Match each macromolecule class with its monomer unit
    ## using PopUp dropdown widgets.
    ## ENDDESCRIPTION
    ## KEYWORDS('macromolecules','monomers','PopUp','matching')
    ## DBsubject('Biochemistry')
    ## DBchapter('Macromolecules')
    ## DBsection('Structure')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserPopUp.pl",
        "PGcourse.pl",
    );

    $popup1 = PopUp(
        ['?', 'Amino acids', 'Nucleotides', 'Monosaccharides'],
        'Amino acids');
    $popup2 = PopUp(
        ['?', 'Amino acids', 'Nucleotides', 'Monosaccharides'],
        'Nucleotides');
    $popup3 = PopUp(
        ['?', 'Amino acids', 'Nucleotides', 'Monosaccharides'],
        'Monosaccharides');

    BEGIN_PGML
    Match each macromolecule class with its monomer.

    1. Proteins [_]{$popup1}

    2. Nucleic acids [_]{$popup2}

    3. Polysaccharides [_]{$popup3}
    END_PGML

    ENDDOCUMENT();

**Bond type matching** \-- Match each molecular scenario with the type
of bond or interaction involved.


    ## TITLE('Match molecular interactions to bond types')
    ## DESCRIPTION
    ## Match each molecular scenario to the correct bond type
    ## using PopUp dropdown widgets.
    ## ENDDESCRIPTION
    ## KEYWORDS('chemical bonds','matching','PopUp')
    ## DBsubject('Chemistry')
    ## DBchapter('Chemical Bonding')
    ## DBsection('Bond Types')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserPopUp.pl",
        "PGcourse.pl",
    );

    $popup1 = PopUp(
        ['?', 'Ionic', 'Covalent', 'Hydrogen'],
        'Covalent');
    $popup2 = PopUp(
        ['?', 'Ionic', 'Covalent', 'Hydrogen'],
        'Ionic');
    $popup3 = PopUp(
        ['?', 'Ionic', 'Covalent', 'Hydrogen'],
        'Hydrogen');

    BEGIN_PGML
    Match each molecular scenario to the type of bond
    or interaction involved.

    1. Two atoms share a pair of electrons [_]{$popup1}

    2. An electron is transferred from one atom to another [_]{$popup2}

    3. A partially positive H is attracted to a nearby electronegative atom [_]{$popup3}
    END_PGML

    ENDDOCUMENT();

## Authoring notes

- Keep the prompts and choices short and parallel.
- If there are obvious one-to-one pairs, add 1-2 extra distractor
  choices only if it helps learning.

---

# 05_Different_Question_Types/5.5-Numerical_entry

Numerical Entry (NUM) is best for a single computed value with a defined
tolerance. Use this when you want a straightforward numeric result
without the full expression parsing features of WeBWorK.

In biology, tolerance is usually about reporting, not instrument
precision. Decide what you are grading: the computation, the unit
conversion, or the reported number format. Put the unit next to the
blank, and pick a tolerance that matches the rounding rule you stated,
so the grader is enforcing your instruction, not guessing your intent.

## Inputs

- `question_text` (str)
- `answer_float` (float)
- `tolerance_float` (float)
- `tolerance_message` (bool, default=True)

## Science example (dilution)

This example uses a simple dilution where students compute a final
concentration.


    question_text:
      You dilute 2.0 mL of a 50.0 mg/mL stock solution to a final volume of 10.0 mL.
      What is the final concentration (mg/mL)?

    answer_float: 10.0
    tolerance_float: 0.1
    tolerance_message: true

Official example (OpenWeBWorK PG samples):
[NumericalTolerance](https://openwebwork.github.io/pg-docs/sample-problems/ProblemTechniques/NumericalTolerance.html).

## Preferred PGML pattern

Use `Compute` with explicit tolerance settings and attach the evaluator
inline in the PGML blank.


    Context("Numeric");
    $ans = Compute("10.0")->with(tolType => "absolute", tolerance => 0.1);

    BEGIN_PGML
    You dilute 2.0 mL of a 50.0 mg/mL stock to 10.0 mL.
    What is the final concentration (mg/mL)?

    [__________]{$ans}
    END_PGML

Set up `Context("Numeric")` before defining numerical answers. State the
tolerance policy in the question prompt when it matters for grading. For
more on answer blanks in PGML, see [Section 3.2](/@go/page/555704). For
common tolerance mistakes, see [Section 7.2](/@go/page/555733).

## Complete working examples

**Dilution calculation** \-- Calculate the final concentration after
diluting a stock solution, with randomized values and absolute
tolerance.


    ## TITLE('Dilution calculation')
    ## DESCRIPTION
    ## Calculate the final concentration after diluting a stock
    ## solution to a larger final volume.
    ## ENDDESCRIPTION
    ## KEYWORDS('dilution','concentration','numeric','tolerance')
    ## DBsubject('Biochemistry')
    ## DBchapter('Concentrations')
    ## DBsection('Dilution')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $stock = random(20, 80, 10);
    $vol_stock = random(1, 4, 1);
    $vol_final = random(10, 20, 5);
    $final_conc = Real($stock * $vol_stock / $vol_final);

    BEGIN_PGML
    You dilute [$vol_stock] mL of a [$stock] mg/mL stock solution
    to a final volume of [$vol_final] mL.

    What is the final concentration (mg/mL)? [________]{$final_conc}
    END_PGML

    ENDDOCUMENT();

**Surface area to volume ratio** \-- Calculate a ratio using relative
tolerance, demonstrating the `tolType` and `tolerance` options.


    ## TITLE('Surface area to volume ratio')
    ## DESCRIPTION
    ## Calculate the surface area to volume ratio of a spherical
    ## cell and report it with relative tolerance.
    ## ENDDESCRIPTION
    ## KEYWORDS('ratio','relative tolerance','numeric')
    ## DBsubject('Cell Biology')
    ## DBchapter('Cell Size')
    ## DBsection('Surface Area')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $radius = random(2, 8, 1);
    $ratio = Real(3 / $radius)->with(
        tolType => "relative",
        tolerance => 0.02,
    );

    BEGIN_PGML
    A spherical cell has a radius of [$radius] micrometers.

    The surface area to volume ratio of a sphere is 3/r.

    What is the surface area to volume ratio for this cell?
    [________]{$ratio}
    END_PGML

    ENDDOCUMENT();

## Authoring notes

- State units in the prompt and use the same units in the expected
  answer.
- Choose tolerances that reflect rounding expectations (do not guess
  after the fact).

---

# 05_Different_Question_Types/5.6-Fill_in_the_blank

Fill-in-the-Blank (FIB) is best for short textual answers (terms,
labels, short phrases) where you can list a small number of acceptable
answers.

Text answers are a biology reality: names, labels, and short phrases
show up everywhere. Decide in advance what you will accept for
pluralization, hyphens, and capitalization, and list those variants
explicitly. If spelling or naming is not the point, switch to
recognition style (MC, matching) so the item grades the concept, not
typing accuracy.

## Inputs

- `question_text` (str)
- `answers_list` (list): acceptable answers

## Science example (cell biology)


    question_text:
      The organelle primarily responsible for ATP production in eukaryotic cells is the ________.

    answers_list:
      - mitochondrion
      - mitochondria

Official example (OpenWeBWorK PG samples):
[StringsInContext](https://openwebwork.github.io/pg-docs/sample-problems/problem-techniques/StringsInContext.html).

## Preferred PGML pattern

Use a string `Context` and `Compute` to define the expected answer, then
attach it inline in the PGML blank.


    Context("String");
    $ans = Compute("mitochondrion");

    BEGIN_PGML
    The organelle primarily responsible for ATP production
    in eukaryotic cells is the [__________]{$ans}.
    END_PGML

If the string context is not available in your renderer snapshot,
convert the question to multiple choice (`RadioButtons`) or a dropdown
(`PopUp`) instead. This avoids grading failures from unsupported
evaluator types. For answer blank syntax details, see [Section
3.2](/@go/page/555704). When a prompt requires multiple blanks, see
[Section 5.7](/@go/page/555720) (Multi-Part Fill-in-the-Blank).

## Complete working examples

**Organelle naming** \-- Name the organelle responsible for ATP
production using a String context answer.


    ## TITLE('Name the ATP-producing organelle')
    ## DESCRIPTION
    ## Name the organelle primarily responsible for ATP production
    ## in eukaryotic cells using a fill-in-the-blank format.
    ## ENDDESCRIPTION
    ## KEYWORDS('organelles','fill in the blank','String')
    ## DBsubject('Cell Biology')
    ## DBchapter('Organelles')
    ## DBsection('Energy')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "contextArbitraryString.pl",
        "PGcourse.pl",
    );

    Context("ArbitraryString");
    $ans = Compute("mitochondrion");

    BEGIN_PGML
    The organelle primarily responsible for ATP production
    in eukaryotic cells is the [__________]{$ans}.
    END_PGML

    ENDDOCUMENT();

**Nucleic acid abbreviation** \-- Name the molecule that carries genetic
information, demonstrating a simple string answer.


    ## TITLE('Name the genetic information molecule')
    ## DESCRIPTION
    ## Name the molecule that carries genetic information
    ## in most organisms.
    ## ENDDESCRIPTION
    ## KEYWORDS('genetics','DNA','fill in the blank','String')
    ## DBsubject('Molecular Biology')
    ## DBchapter('Nucleic Acids')
    ## DBsection('DNA')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "contextArbitraryString.pl",
        "PGcourse.pl",
    );

    Context("ArbitraryString");
    $ans = Compute("DNA");

    BEGIN_PGML
    The molecule that stores hereditary information in most
    living organisms is [__________]{$ans}.
    END_PGML

    ENDDOCUMENT();

## Authoring notes

- Decide whether you will accept plural vs singular forms, and list them
  explicitly.
- Keep capitalization rules explicit (either normalize answers or list
  variants).

---

# 05_Different_Question_Types/5.7-Multi_part_fill_in_the_blank

Multi-Part Fill-in-the-Blank (MULTI_FIB) is best when students must
supply several short answers within a single prompt. This matches many
science workflows (labeling, short computed parts, or multi-step
interpretation). For single-blank questions, see [Section
5.6](/@go/page/555719) instead.

Multi-blank prompts are great for short workflows, but they fail when
blanks are not clearly tied to a specific request. Keep each blank\'s
request local to the blank, keep formatting consistent across blanks,
and prefer two to three blanks unless the prompt is very structured.
When students miss one part, they should still understand what each
other blank was asking.

## Inputs

- `question_text` (str)
- `answer_map` (dict): map from blank position to correct answer

## Science example (genotype to phenotype)


    question_text:
      For a monohybrid cross Aa x Aa:
      - The expected fraction of aa offspring is [blank_1].
      - The expected fraction of offspring showing the dominant phenotype is [blank_2].

    answer_map:
      blank_1: 1/4
      blank_2: 3/4

Official example (OpenWeBWorK PG samples):
[Multianswer](https://openwebwork.github.io/pg-docs/sample-problems/ProblemTechniques/Multianswer.html).

## Preferred PGML pattern

Define each answer as a separate named variable and attach each one
inline in the PGML blank closest to its prompt (see [Section
3.2](/@go/page/555704) for answer blank syntax). Do not use anonymous
evaluator arrays or rely on implicit `ANS(...)` ordering.


    Context("Numeric");
    $ans_a = Compute("1/4");
    $ans_b = Compute("3/4");

    BEGIN_PGML
    For a monohybrid cross Aa x Aa:

    Part A: The expected fraction of aa offspring is [__________]{$ans_a}.

    Part B: The expected fraction showing the dominant
    phenotype is [__________]{$ans_b}.
    END_PGML

For mixed formats (for example a RadioButtons part and a numeric part),
define each answer object separately and place its blank next to the
corresponding text. Keep variable naming consistent (`$ans_a`, `$ans_b`,
or `$ans1`, `$ans2`).

## Complete working examples

**Genetics cross fractions** \-- Calculate two expected fractions from a
monohybrid cross between heterozygous parents.


    ## TITLE('Monohybrid cross fractions')
    ## DESCRIPTION
    ## Calculate the expected fraction of homozygous recessive
    ## and dominant phenotype offspring from Aa x Aa.
    ## ENDDESCRIPTION
    ## KEYWORDS('genetics','monohybrid','multi-part','numeric')
    ## DBsubject('Genetics')
    ## DBchapter('Mendelian Genetics')
    ## DBsection('Monohybrid Cross')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $ans_a = Compute("1/4");
    $ans_b = Compute("3/4");

    BEGIN_PGML
    For a monohybrid cross Aa x Aa:

    Part A: The expected fraction of aa offspring is
    [__________]{$ans_a}.

    Part B: The expected fraction showing the dominant
    phenotype is [__________]{$ans_b}.
    END_PGML

    ENDDOCUMENT();

**Three-part dilution** \-- Calculate stock concentration, dilution
factor, and final concentration across three answer blanks.


    ## TITLE('Three-part dilution problem')
    ## DESCRIPTION
    ## Given a dilution scenario, calculate the stock concentration
    ## in different units, the dilution factor, and the final
    ## concentration.
    ## ENDDESCRIPTION
    ## KEYWORDS('dilution','multi-part','numeric','concentration')
    ## DBsubject('Biochemistry')
    ## DBchapter('Concentrations')
    ## DBsection('Dilution')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $stock_mM = random(10, 50, 10);
    $stock_uM = Real($stock_mM * 1000);
    $dilution_factor = list_random(5, 10, 20);
    $final_uM = Real($stock_uM / $dilution_factor);

    BEGIN_PGML
    A stock solution has a concentration of [$stock_mM] mM.

    Part A: What is the stock concentration in uM?
    [__________]{$stock_uM}

    Part B: If you dilute it 1:[$dilution_factor], what is the
    dilution factor? [__________]{$dilution_factor}

    Part C: What is the final concentration in uM?
    [__________]{$final_uM}
    END_PGML

    ENDDOCUMENT();

## Authoring notes

- Keep blanks unambiguous and label them consistently.
- Use consistent formatting for answers (fractions vs decimals).

---

# 05_Different_Question_Types/5.8-Ordered_list

Ordered List (ORDER) is best for sequencing steps in a process. In
science courses it is useful for protocols and workflows (PCR, gel
electrophoresis, sample prep), as long as the sequence is well-defined.

Ordered list questions work best for canonical cycles and short
protocols, not for long procedures. If your course has multiple
acceptable orders depending on reagent choice or instrument, this type
will create disputes. Keep lists short and pick sequences students
should be able to justify, not merely recite.

## Inputs

- `question_text` (str)
- `ordered_answers_list` (list): correct sequence

## Science example (PCR workflow)


    question_text:
      Put the following PCR steps in the correct order.

    ordered_answers_list:
      - Denaturation
      - Primer annealing
      - Extension

Official examples (OpenWeBWorK PG samples): [Problem techniques
list](https://openwebwork.github.io/pg-docs/sample-problems/techniques.html).

## Preferred PGML pattern (DraggableProof)

Use `draggableProof.pl` to create a drag-and-drop ordering widget (for
general list formatting in PGML, see [Section 3.3](/@go/page/555705)).
The inline `[_]{$ordering}` pattern is not supported in PG 2.17 (it
produces an unrecognized evaluator error), so use the legacy `->Print`
plus `ANS(...)` form instead.


    loadMacros(
      "PGstandard.pl",
      "MathObjects.pl",
      "PGML.pl",
      "draggableProof.pl",
      "PGcourse.pl",
    );

    $ordering = DraggableProof(
      [ "Denaturation", "Primer annealing", "Extension" ],
      [],
      SourceLabel => "Steps",
      TargetLabel => "Put in correct order",
    );
    $ordering_html = $ordering->Print;

    BEGIN_PGML
    Put the PCR steps in the correct order.

    [$ordering_html]*
    END_PGML

    ANS($ordering->cmp);

Key points:

- The first array holds items in the correct order; the second array
  (usually empty) holds items that start in the target zone.
- Include `MathObjects.pl`; it is required by the macro.
- Use `[$ordering_html]*` to inject the widget HTML without PGML
  escaping (the `*` flag is critical).
- Use `ANS($ordering->cmp)` for grading because inline attachment is not
  supported.

## Complete working examples

**PCR steps** \-- Order the three main steps of a PCR cycle using the
DraggableProof drag-and-drop widget.


    ## TITLE('Order the PCR cycle steps')
    ## DESCRIPTION
    ## Put the three main steps of a PCR cycle in the correct
    ## order using a drag-and-drop interface.
    ## ENDDESCRIPTION
    ## KEYWORDS('PCR','ordering','DraggableProof')
    ## DBsubject('Molecular Biology')
    ## DBchapter('Techniques')
    ## DBsection('PCR')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "draggableProof.pl",
        "PGcourse.pl",
    );

    $ordering = DraggableProof(
        [ "Denaturation", "Primer annealing", "Extension" ],
        [],
        SourceLabel => "Steps",
        TargetLabel => "Put in correct order",
    );
    $ordering_html = $ordering->Print;

    BEGIN_PGML
    Put the three main steps of a PCR cycle in the correct order.

    [$ordering_html]*
    END_PGML

    ANS($ordering->cmp);

    ENDDOCUMENT();

**Mitosis phases** \-- Order the four phases of mitosis in the correct
sequence.


    ## TITLE('Order the phases of mitosis')
    ## DESCRIPTION
    ## Put the four phases of mitosis in the correct order
    ## using a drag-and-drop interface.
    ## ENDDESCRIPTION
    ## KEYWORDS('mitosis','cell division','ordering','DraggableProof')
    ## DBsubject('Cell Biology')
    ## DBchapter('Cell Division')
    ## DBsection('Mitosis')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "draggableProof.pl",
        "PGcourse.pl",
    );

    $ordering = DraggableProof(
        [ "Prophase", "Metaphase", "Anaphase", "Telophase" ],
        [],
        SourceLabel => "Phases",
        TargetLabel => "Put in correct order",
    );
    $ordering_html = $ordering->Print;

    BEGIN_PGML
    Put the four phases of mitosis in the correct order.

    [$ordering_html]*
    END_PGML

    ANS($ordering->cmp);

    ENDDOCUMENT();

## Authoring notes

- Only use ORDER when there is a single standard sequence for the
  context you are testing.
- Keep the list short (3-6 items) to avoid turning it into a memory
  game.

---

# 05_Different_Question_Types/5.9-Workflow_and_QA_in_ADAPT

This page combines a practical ADAPT workflow checklist with a compact
QA pass for biology-style WeBWorK items. The goal is to give you a
repeatable routine that turns \"generic error\" screens into specific
fixes before you publish to students.

Treat previewing as a scientific replication step: same inputs should
give the same result, and failures should be reproducible. For a
systematic approach to testing and common pitfalls, see [Chapter
7](/@go/page/555731). First pass should be fast and local to get
line-level errors and sweep variants, then final pass should be in ADAPT
to confirm student view and assignment behavior. If a platform only
reports \"error,\" that is a signal to change the testing tool, not to
guess.

## Workflow: clone, edit, preview, assign

1.  Start from a working question (clone or copy a trusted template from
    the OPL, see [Section 2.2](/@go/page/557378) for OPL metadata).
2.  Edit one small thing at a time: story text, values, answer checker,
    or prompt structure.
3.  Preview and revise until the student view and grading are stable.
4.  Add the question to an assignment and confirm ordering and point
    values.
5.  Publish, then spot-check student view for the assignment context.

## QA: variants, blanks, text variants, units, plausibility

- **Variants**: preview multiple variants and watch for impossible
  biology and awkward rounding.
- **Blanks**: confirm each blank is bound to the intended answer checker
  and that blank order matches prompt order.
- **Text variants**: decide what you accept for plural/singular,
  hyphens, spacing, and case (gene and protein naming is a common trap).
- **Units**: prevent unit drift (μM vs mM, μL vs mL) and restate
  expected units next to the blank.
- **Plausibility**: constrain random ranges (no negative concentrations,
  no unrealistic pipette volumes).
- **Log-scale traps**: state the model and reporting format for pH, Ct,
  and fold change.

## Recommended testing loop

- First pass: use local rendering to get line-level errors and to sweep
  variants quickly.
- Final pass: use ADAPT preview to confirm permissions, assignment
  behavior, and student view.

---

# 06_Advanced_PGML_Techniques/6.0-Index

This chapter introduces advanced PGML authoring patterns for richer
layouts and interaction patterns. It covers CSS-based emphasis, tables
with `niceTables.pl`, modern matching layouts, statement-by-statement
evaluation, safer randomization habits, display graphs with
`PGgraphmacros.pl`, and chemical structure rendering with RDKit.js.

Matching layouts include the one place where `MODES(HTML => ...)` is
required: wrapper HTML built inside eval blocks for dynamic content.

These techniques assume the PG 2.17 subset used in ADAPT and
webwork-pg-renderer, so some macros from full WeBWorK installs are not
available. Use the patterns here when the basic PGML tools in Chapter 3
are not enough.

## Start here (task first)

- I need visual emphasis or color in the prompt -\> [Section
  6.1](/@go/page/555723).
- I need a data or layout table -\> [Section 6.2](/@go/page/555724).
- I need a two-column matching layout -\> [Section
  6.3](/@go/page/555725).
- I need true/false per statement -\> [Section 6.4](/@go/page/555726).
- I need safer randomization -\> [Section 6.5](/@go/page/555727).
- I need a display graph (titration curve, data plot) -\> [Section
  6.6](/@go/page/555728).
- I need to render chemical structures from SMILES -\> [Section
  6.7](/@go/page/555729).
- I need to display chemical formulas or reaction equations -\> Section
  6.8.

## Quick patterns

  --------------------------------------------------------------------------------
  Need                      Use                          Page
  ------------------------- ---------------------------- -------------------------
  Emphasize key words       HTML spans and PGML wrappers [6.1](/@go/page/555723)

  Structured data display   DataTable or LayoutTable     [6.2](/@go/page/555724)

  Two-column matching       PopUp widgets + flexbox      [6.3](/@go/page/555725)

  Evaluate multiple         RadioButtons per statement   [6.4](/@go/page/555726)
  statements                                             

  Stable random variants    problemSeed + guard checks   [6.5](/@go/page/555727)

  Display graph (curve,     PGgraphmacros.pl +           [6.6](/@go/page/555728)
  data plot)                init_graph                   

  Chemical structure        RDKit.js + SMILES strings    [6.7](/@go/page/555729)
  rendering                                              

  Chemical formula /        mhchem via MathJax \\ce{}    6.8
  reaction display                                       
  --------------------------------------------------------------------------------

{{template.ShowOrg()}}

---

# 06_Advanced_PGML_Techniques/6.1-Text_Coloring_and_Emphasis

This page shows how to add visual emphasis using CSS-based styling that
works in the PG 2.17 subset. Use this for terms like ABOVE/BELOW or NOT
where color or bold weight prevents misreads.

**Use this page when:** you need to highlight key words, numeric values,
or label classes in matching or statement-based prompts. For general
PGML layout controls, see [Section 3.5](/@go/page/555707). For common
CSS mistakes, see [Section 7.2](/@go/page/555733).

## Why emphasize key information?

Students often miss critical details in question statements, leading to
common errors:

- Reading the wrong value (pH 7.4 instead of pH 8.0)
- Missing important qualifiers like NOT, LEAST, or MOST
- Overlooking units or experimental conditions

Visual emphasis helps students quickly locate critical values and focus
on what matters. Even a small amount of color or size change can
dramatically reduce misreading errors.

## Emphasis styles by use case

  -------------------------------------------------------------------------------
  Use case        Style             CSS properties              Example content
  --------------- ----------------- --------------------------- -----------------
  Numeric values  Blue badge        color:#0066cc;              pH 7.4
  (pH,                              font-size:1.35em;           
  temperatures)                     font-weight:700;            
                                    background-color:#e6f2ff;   
                                    padding:0.1em 0.4em;        
                                    border-radius:4px           

  Key terms       Gold emphasis     color:#997300;              hydrophobic
  (hydrophobic,                     font-size:1.25em;           
  polar)                            font-weight:700             

  Negation (NOT,  Red warning       color:#cc0000;              NOT
  EXCEPT)                           font-size:1.3em;            
                                    font-weight:700             

  Multiple values Monospace with    font-family:monospace;      1.82, 6.00, 9.17
  (pKa lists)     background        background-color:#f5f5f5;   
                                    padding:0.2em 0.5em;        
                                    border-radius:3px;          
                                    font-size:1.1em             
  -------------------------------------------------------------------------------

## CSS class approach (preferred)

Define CSS classes once in `HEADER_TEXT` at the top of the problem, then
reference them with PGML tag wrappers. This keeps styles in one place
and reusable throughout the problem.


    HEADER_TEXT(MODES(TeX => '', HTML => <<'END_STYLE'));
    <style>
    .emph-data    { color:#0066cc; font-size:1.35em; font-weight:700;
                    background-color:#e6f2ff; padding:0.1em 0.4em; border-radius:4px; }
    .emph-term    { color:#997300; font-size:1.25em; font-weight:700; }
    .emph-warning { color:#cc0000; font-size:1.3em;  font-weight:700; }
    </style>
    END_STYLE

    BEGIN_PGML
    Which amino acid is predominantly charged at
    [<pH 7.4>]{['span', class => 'emph-data']}{['','']}?

    Which of the following is
    [<NOT>]{['span', class => 'emph-warning']}{['','']}
    a nucleotide?
    END_PGML

The tag wrapper syntax is
`[<text>]{['span', class => 'class-name']}{['','']}`. The first brace
pair sets the HTML element and attributes; the second `{['','']}` closes
the tag.

## Inline style approach

If you only need emphasis in one place, you can use inline styles
directly in the tag wrapper. This works but is harder to maintain when
the same style appears in multiple places.


    BEGIN_PGML
    [<Important>]{['span', style => 'color:#b91c1c; font-weight:700;']}{['','']}
    END_PGML

## What does NOT work: TeX and MathJax color commands

Do not use `\color`, `\textcolor`, or other TeX/MathJax color commands
for text coloring in PGML. In this install, PGML escapes backslashes
into `tex2jax_ignore` spans before MathJax processes them, so the TeX
color commands never reach the math renderer.


    ## These all FAIL - do not use them ##
    [\color{#cc00cc}{\text{colored text}}]
    \(\color{#cc00cc}{\text{colored text}}\)
    $colored = "\color{red}{\text{warning}}";
    [$colored]

Backslashes are escaped into `<span class="tex2jax_ignore">\\</span>`
before MathJax runs, so the TeX commands are never processed. Use CSS
styling instead.

## Passing HTML variables through PGML

PGML tag wrappers are parsed at compile time. If you build HTML spans
inside Perl variables, PGML will not re-parse them. Instead, pass them
through using `[$var]*` so the HTML is not escaped.


    # Build the HTML span in the Setup section
    $label = "<span style='color:#0f766e; font-weight:700;'>ABOVE</span>";

    BEGIN_PGML
    Threshold: [$label]*
    END_PGML

The trailing `*` tells PGML to pass the content through as raw HTML.
Without it, the HTML tags are escaped and displayed as literal text.

## Font size guidelines

  -----------------------------------------------------------------------
  Size           Level of emphasis        When to use
  -------------- ------------------------ -------------------------------
  1.1em          Subtle                   Formulas, value lists,
                                          monospace data

  1.25em         Moderate                 Key terms, qualitative
                                          descriptors

  1.35em         Strong                   pH values, critical numeric
                                          data

  1.5em          Maximum                  Rarely needed; only for
                                          prominent warnings
  -----------------------------------------------------------------------

Do not exceed 1.5em. Larger text becomes distracting and looks
unprofessional.

## Color palette recommendations

  -----------------------------------------------------------------------
  Color             Hex value         Use case
  ----------------- ----------------- -----------------------------------
  Blue              #0066cc           pH values, temperatures,
                                      concentrations

  Gold              #997300           Key terms like hydrophobic, polar,
                                      most, least

  Red               #cc0000           NOT, EXCEPT, CANNOT (use sparingly)

  Light blue bg     #e6f2ff           Data badge backgrounds behind blue
                                      text

  Light gray bg     #f5f5f5           Subtle monospace backgrounds for
                                      value lists
  -----------------------------------------------------------------------

Avoid pure black (#000000) for emphasis, bright green or yellow
(accessibility issues), and using more than two or three colors per
question (visual clutter).

## Accessibility considerations

Never rely on color alone to convey meaning. Combine color with at least
one other method such as font size, font weight, or a background
highlight so that colorblind users can still distinguish emphasized
content. Aim for a minimum contrast ratio of 4.5:1 between text and
background. The recommended palette above meets this threshold on white
backgrounds (`#0066cc` = 8.6:1, `#997300` = 5.2:1, `#cc0000` = 5.9:1).

## Complete working examples

**pH question with blue badge** (CSS class approach):


    HEADER_TEXT(MODES(TeX => '', HTML => <<'END_STYLE'));
    <style>
    .emph-ph { color:#0066cc; font-size:1.35em; font-weight:700;
               background-color:#e6f2ff; padding:0.1em 0.4em; border-radius:4px; }
    </style>
    END_STYLE

    $ph_value = list_random(6.0, 7.0, 7.4, 8.0);

    BEGIN_PGML
    Which amino acid is predominantly charged at
    [<pH [$ph_value]>]{['span', class => 'emph-ph']}{['','']}?

    [_]{$answer}
    END_PGML

**Negation question with red warning** (variable approach):


    $not_emph = "<span style='color:#cc0000; font-size:1.3em; font-weight:700;'>NOT</span>";

    BEGIN_PGML
    Which of the following is [$not_emph]* a nucleotide?

    [_]{$answer}
    END_PGML

**Multiple emphasized elements** (mixed data and term emphasis):


    HEADER_TEXT(MODES(TeX => '', HTML => <<'END_STYLE'));
    <style>
    .emph-data { color:#0066cc; font-size:1.25em; font-weight:700;
                 background-color:#e6f2ff; padding:0.1em 0.3em; border-radius:3px; }
    .emph-term { color:#997300; font-size:1.25em; font-weight:700; }
    </style>
    END_STYLE

    $compound = "glucose";
    $temp = "37 degrees C";

    BEGIN_PGML
    At [<[$temp]>]{['span', class => 'emph-data']}{['','']},
    what is the solubility of
    [<[$compound]>]{['span', class => 'emph-term']}{['','']}
    in water?

    [_]{$answer} g/L
    END_PGML

**Complete renderable problem with emphasis** \-- A full problem using
CSS class emphasis to highlight a pH value in the question stem.


    ## TITLE('Amino acid charge at a given pH')
    ## DESCRIPTION
    ## Identify whether an amino acid side chain is charged
    ## at a specified pH, with the pH value visually emphasized.
    ## ENDDESCRIPTION
    ## KEYWORDS('amino acids','pH','emphasis','RadioButtons')
    ## DBsubject('Biochemistry')
    ## DBchapter('Amino Acids')
    ## DBsection('Charge')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    HEADER_TEXT(MODES(TeX => '', HTML => <<'END_STYLE'));
    <style>
    .emph-ph { color:#0066cc; font-size:1.35em; font-weight:700;
               background-color:#e6f2ff; padding:0.1em 0.4em;
               border-radius:4px; }
    </style>
    END_STYLE

    $rb = RadioButtons(
        [ 'Positively charged', 'Negatively charged',
          'Neutral', 'Zwitterionic only' ],
        'Positively charged',
        labels        => 'ABC',
        displayLabels => 1,
    );

    BEGIN_PGML
    The side chain of lysine has a pKa of approximately 10.5.

    At [<pH 7.4>]{['span', class => 'emph-ph']}{['','']},
    is the lysine side chain:

    [_]{$rb}
    END_PGML

    ENDDOCUMENT();

## Matching problem label colors

When labels in matching problems need fixed colors by meaning (not by
randomized position), build an HTML mapping in Perl and emit each label
with `*` so PGML does not escape the spans. This keeps colors tied to
the label text even when the display order is randomized.


    %answer_html = (
      'ionic bond'    => "<span style='color:#009900; font-weight:700;'>ionic bond</span>",
      'hydrogen bond' => "<span style='color:#e60000; font-weight:700;'>hydrogen bond</span>",
    );
    @answers_html = map { $answer_html{$_} || $_ } @answers;

    # In PGML, render each label with * to pass through HTML
    [$answers_html[$shuffle[0]]]*

## Common failure: missing the asterisk


    [$label]     # BROKEN - HTML is escaped, shows raw tags
    [$label]*    # CORRECT - asterisk prevents escaping

If you see literal `<span>` tags in the rendered question, the most
likely cause is a missing `*`. Always use `[$var]*` when the variable
contains HTML.

## Best practices

### Do

- Emphasize one to three key elements per question.
- Use consistent colors for similar element types across your problem
  set.
- Combine color with size or weight for accessibility.
- Create emphasis variables in the Setup section, not inside PGML.
- Use `[$var]*` to render HTML stored in Perl variables.
- Prefer CSS classes defined in HEADER_TEXT over inline styles.

### Do not

- Emphasize everything; it defeats the purpose.
- Use more than three colors in one question.
- Make text larger than 1.5em.
- Use red for non-warning content.
- Use TeX or MathJax color commands; they do not render in this install.
- Forget the `*` in `[$var]*` when the variable contains HTML.

---

# 06_Advanced_PGML_Techniques/6.2-Making_Tables_with_niceTables

This page explains how to build tables with `niceTables.pl` (see
[Section 2.5](/@go/page/488659) for macro loading), which is the only
supported way to create tables in this install. For basic table concepts
in PGML, see [Section 3.4](/@go/page/555706). Standard HTML table tags
(`<table>`, `<tr>`, `<td>`, `<th>`) are blocked by the server and will
not render. Use `DataTable` or `LayoutTable` instead.

**Use this page when:** you need to present measurements, observations,
or structured data in a readable format inside a WeBWorK problem.

## Why niceTables is the only option

The WeBWorK PG rendering engine strips raw HTML table tags for security
reasons. If you write `<table><tr><td>...</td></tr></table>` inside a
problem, the tags are silently removed and the cell contents collapse
into a single line. The `niceTables.pl` macro generates safe, styled
tables that the server allows through. Every table in every problem must
use this macro.

## DataTable vs LayoutTable

  ------------------------------------------------------------------------
  Table type     Use it for                   Notes
  -------------- ---------------------------- ----------------------------
  DataTable      Real data with headers,      Adds header structure and
                 captions, or semantic        improves accessibility.
                 meaning (measurements,       Supports the `caption`
                 conditions, experimental     option.
                 results).                    

  LayoutTable    Visual layout: side-by-side  No header semantics. Use
                 answer blanks, aligned       sparingly; do not fake data
                 labels, widget grids.        tables with LayoutTable.
  ------------------------------------------------------------------------

**Rule of thumb:** if the content has a header row or a caption, use
`DataTable`. If you are arranging blanks or labels spatially, use
`LayoutTable`.

## Copy and edit (DataTable)

This template shows a three-row DataTable with a header row. Customize
the row data, column headers, and options to match your experiment.


    loadMacros(
      "PGstandard.pl",
      "MathObjects.pl",
      "PGML.pl",
      "niceTables.pl",
    );

    $rows = [
      ['Tube', 'Stock (mM)', 'Final (uM)'],
      ['A', 2.0, ''],
      ['B', 4.0, ''],
      ['C', 8.0, ''],
    ];

    $tbl = DataTable($rows, columns => 'left', center => 1, horizontalrules => 1);

    BEGIN_PGML
    [@ $tbl @]*
    END_PGML

## Copy and edit (LayoutTable)

Use LayoutTable when you need to arrange answer blanks or labels side by
side without header semantics. Customize the cell contents and answer
variables.


    $layout = LayoutTable(
      [
        [ 'Lane 1', 'Lane 2', 'Lane 3' ],
        [ '[________]{ $ans1 }', '[________]{ $ans2 }', '[________]{ $ans3 }' ],
      ],
      center => 1,
      horizontalrules => 1,
    );

    BEGIN_PGML
    [@ $layout @]*
    END_PGML

## Cell content formats

Most cells are plain text strings. Use a hashref or arrayref only when
you need per-cell alignment or CSS overrides.

Each cell in the 2-D array you pass to `DataTable` or `LayoutTable` can
be one of three shapes.

- **Plain text** (`'hello'`) \-- most cells. Just pass a string or
  number.
- **Hashref** (`{ data => 'hello', halign => 'c' }`) \-- when you need
  per-cell options like alignment or CSS.
- **Arrayref** (`[ 'hello', halign => 'c' ]`) \-- shorthand for hashref.
  Item 0 is content; the rest are key/value options.

## Table-level options reference

These options are passed as key/value pairs after the row data.

- `center` \-- set to 1 to center the table horizontally.
- `caption` \-- add a caption above the table (DataTable only).
- `horizontalrules` \-- set to 1 to draw horizontal lines between rows.
- `valign` \-- vertical alignment: `top`, `middle`, or `bottom`.
- `padding` \-- array `[vertical, horizontal]` specifying cell padding
  in em.

CSS hooks for fine-grained styling:

- `tablecss` \-- CSS applied to the outer table element.
- `datacss` \-- CSS applied to every data cell.
- `headercss` \-- CSS applied to every header cell.
- `allcellcss` \-- CSS applied to every cell (header and data).
- `columnscss` \-- arrayref of CSS strings, one per column.

## PGML table syntax

PGML\'s inline table syntax is convenient for simple tables that do not
need heavy customization.

PGML also supports an inline table syntax using `[# ... #]`. This is
backed by `niceTables` internally and is acceptable when it improves
readability. Each row uses `[. ... .]` for cells.


    BEGIN_PGML
    [# 'Tube'  , 'Stock (mM)' , 'Final (uM)' #]
    [. 'A'     , 2.0          , [________]{$ans1} .]
    [. 'B'     , 4.0          , [________]{$ans2} .]
    [. 'C'     , 8.0          , [________]{$ans3} .]
    END_PGML

For complex tables with many options, the explicit `DataTable()` or
`LayoutTable()` call gives you more control.

## Translating HTML tables

If you are converting a problem from another platform or an older PG
format, you will likely encounter raw HTML tables that need translation.

If you are converting a problem that originally used raw HTML tables,
follow these rules.

- **Header row or caption present:** use `DataTable()`. Map `<th>` cells
  to the first row of the array.
- **Pure layout (two-column lists, widget grids):** use `LayoutTable()`.
- **Nested tables:** not supported. Flatten the content into a single
  table or use separate tables.
- **rowspan or colspan:** not supported. Restructure the data into a
  simple rectangular grid.
- Never emit raw HTML table tags as a fallback. If the table cannot be
  translated, rewrite it manually.

## Biology examples

### Dilution series

A DataTable showing stock concentrations where students compute the
final concentration.


    $dilution = DataTable(
      [
        ['Tube', 'Stock (mM)', 'Dilution', 'Final (uM)'],
        ['A', 2.0, '1:10', ''],
        ['B', 4.0, '1:10', ''],
        ['C', 8.0, '1:10', ''],
      ],
      caption => 'Serial dilution worksheet',
      center => 1,
      horizontalrules => 1,
    );

### Enzyme kinetics

Substrate concentration vs reaction velocity with one computed blank.


    $kinetics = DataTable(
      [
        ['[S] (mM)', 'Velocity (umol/min)'],
        [0.1, 12],
        [0.5, 45],
        [1.0, '[________]{ $vmax_half }'],
        [5.0, 88],
      ],
      center => 1,
      horizontalrules => 1,
    );

### Gel or blot comparison

A LayoutTable that arranges lane labels above answer blanks so students
identify bands.


    $gel = LayoutTable(
      [
        [ 'Marker', 'Sample 1', 'Sample 2', 'Control' ],
        [ '[________]{ $band1 }', '[________]{ $band2 }',
          '[________]{ $band3 }', '[________]{ $band4 }' ],
      ],
      center => 1,
      allcellcss => 'padding: 4px 8px;',
    );

## Complete working example

**Enzyme kinetics data table** \-- A full problem presenting substrate
concentration vs velocity data in a DataTable, with a RadioButtons
question about the data pattern.


    ## TITLE('Enzyme kinetics data interpretation')
    ## DESCRIPTION
    ## Review an enzyme kinetics data table and identify the
    ## relationship between substrate concentration and velocity.
    ## ENDDESCRIPTION
    ## KEYWORDS('enzyme kinetics','DataTable','niceTables','RadioButtons')
    ## DBsubject('Biochemistry')
    ## DBchapter('Enzymes')
    ## DBsection('Kinetics')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "niceTables.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    $tbl = DataTable(
        [
            ['[S] (mM)', 'Velocity (umol/min)'],
            [0.1, 12],
            [0.5, 45],
            [1.0, 68],
            [5.0, 88],
            [10.0, 95],
        ],
        center => 1,
        horizontalrules => 1,
    );

    $rb = RadioButtons(
        [ 'Velocity increases linearly with [S]',
          'Velocity approaches a maximum as [S] increases',
          'Velocity decreases as [S] increases',
          'Velocity is independent of [S]' ],
        'Velocity approaches a maximum as [S] increases',
        labels        => 'ABC',
        displayLabels => 1,
    );

    BEGIN_PGML
    The following table shows enzyme kinetics data.

    [@ $tbl @]*

    Which statement best describes the relationship between
    substrate concentration and reaction velocity?

    [_]{$rb}
    END_PGML

    ENDDOCUMENT();

## Apply it today

- Use `DataTable` for real measurements and `LayoutTable` only for
  visual arrangement.
- Never use raw HTML table tags; they are blocked and will not render.
- Start with the copy-and-edit examples above, then customize options as
  needed.

---

# 06_Advanced_PGML_Techniques/6.3-Making_Graphs

This page covers how to create graphs in WeBWorK PG/PGML problems. It
focuses on `PGgraphmacros.pl`, which produces static GD bitmap images
suitable for display-only graphs such as titration curves, enzyme
kinetics plots, and dose-response data.

**Use this page when:** you need to show a graph in a problem but
students answer with RadioButtons, PopUp menus, or numeric blanks rather
than by clicking on the graph itself. Load `PGgraphmacros.pl` via the
macro block (see [Section 2.5](/@go/page/488659)), set up graph
variables in the Setup block (see [Section 4.4](/@go/page/555711)), and
always test the rendered output (see [Chapter 7](/@go/page/555731)).

## Which graph macro to use

  ------------------------------------------------------------------------
  Need                     Macro                  Notes
  ------------------------ ---------------------- ------------------------
  Display-only graph       `PGgraphmacros.pl`     GD bitmap image, no
  (titration curve, data                          answer entry
  plot)                                           

  Student clicks or draws  `parserGraphTool.pl`   JS canvas, registers an
  on graph                                        answer entry
  ------------------------------------------------------------------------

**Rule of thumb:** if students answer via RadioButtons or other PGML
widgets (not by clicking the graph), use `PGgraphmacros.pl`. GraphTool
creates a phantom answer entry that can interfere with subsequent PGML
answer evaluators.

## Minimal example with PGgraphmacros

Copy this block into a new problem file, save, and preview. It draws a
single sine curve on a labeled grid.


    loadMacros(
      'PGstandard.pl',
      'MathObjects.pl',
      'PGML.pl',
      'PGgraphmacros.pl',
      'PGcourse.pl',
    );

    # Create graph: init_graph(xmin, ymin, xmax, ymax, ...)
    $gr = init_graph(-1, 0, 10, 14,
      axes  => [0, 0],
      grid  => [11, 14],
      size  => [480, 400],
    );

    # Plot a function (string formula, not a code reference)
    add_functions($gr,
      "2 + 3*sin(x) for x in <0,10> using color:blue and weight:2"
    );

    # Render as an image
    $graph_img = image(insertGraph($gr), width => 480, height => 400, tex_size => 700);

    BEGIN_PGML
    Here is a graph:

    [$graph_img]*
    END_PGML

Key points:

- `init_graph` returns a GD graph object.
- `add_functions` takes a **string** formula with
  `for x in <min,max> using color:COLOR and weight:N`.
- `image(insertGraph($gr), ...)` produces an HTML img tag.
- Use `[$graph_img]*` in PGML. The asterisk prevents HTML escaping.

## init_graph parameters


    $gr = init_graph($xmin, $ymin, $xmax, $ymax,
      axes  => [$x_origin, $y_origin],  # where axes cross
      grid  => [$x_divisions, $y_divisions],  # grid line count
      size  => [$width_px, $height_px],  # image dimensions
    );

- `axes => [0, 0]` places the origin at (0, 0).
- `grid` controls the number of light grid lines (not tick labels).
- `size` sets the GD image dimensions in pixels.

## Adding labels

Labels are positioned in graph coordinates (not pixel coordinates). The
constructor is:


    new Label($x, $y, $text, $color, $h_align, $v_align)

Horizontal alignment: `'left'`, `'center'`, `'right'`. Vertical
alignment: `'top'`, `'middle'`, `'bottom'`.

### Axis labels at edges of the plot area


    $gr->lb(new Label($xmax, $ymin - 0.7, 'x-axis label', 'black', 'right', 'top'));
    $gr->lb(new Label($xmin - 0.1, $ymax, 'y-axis', 'black', 'right', 'top'));

### Tick labels


    # Tick labels on y-axis
    for $yv (0, 2, 4, 6, 8, 10, 12) {
      $gr->lb(new Label($xmin - 0.08, $yv, $yv, 'black', 'right', 'middle'));
    }

    # Tick labels on x-axis
    for $xv (0, 1, 2, 3) {
      $gr->lb(new Label($xv, $ymin - 0.3, $xv, 'black', 'center', 'top'));
    }

## add_functions syntax and computed coefficients

The function string format is:


    "FORMULA for x in <XMIN,XMAX> using color:COLOR and weight:WEIGHT"

- `FORMULA`: a Perl math expression using `x` as the variable (e.g.,
  `2*x**3 + x - 1`).
- `<XMIN,XMAX>`: domain interval (angle brackets).
- `color:COLOR`: `blue`, `red`, `green`, `black`, etc.
- `weight:WEIGHT`: line thickness in pixels (1, 2, 3, \...).

For computed coefficients, interpolate Perl variables into the string:


    $a = 0.5;
    $b = -1.2;
    $c = 3.0;
    $d = 1.5;
    $func_str = "$a*x**3 + $b*x**2 + $c*x + $d";
    add_functions($gr, "$func_str for x in <0,3> using color:blue and weight:2");

## Multiple curves

Pass multiple formula strings to `add_functions`. Each string specifies
its own color and weight.


    add_functions($gr,
      "$curve1 for x in <0,10> using color:blue and weight:2",
      "$curve2 for x in <0,10> using color:red and weight:2",
    );

## Point-by-point curves with moveTo and lineTo

When a formula string cannot express the curve shape (parametric curves,
physical models where x is not the independent variable), draw
point-by-point with `moveTo` and `lineTo`. Use 300 to 400 points for
smooth results.


    $first_pt = 1;
    for $i (0..400) {
      $t = $i / 400.0;
      # compute ($x_val, $y_val) from $t
      if ($first_pt) {
        $gr->moveTo($x_val, $y_val);
        $first_pt = 0;
      } else {
        $gr->lineTo($x_val, $y_val, 'blue', 2);
      }
    }

This approach is essential when the x-axis value is a computed function
of the sweep variable rather than the independent variable itself.

## Dashed lines

PGgraphmacros has no built-in dash style. Draw dashes manually as short
line segments with gaps:


    # Horizontal dashed line at y=$pka from x=0 to x=$xeq
    for $d (0..29) {
      $x1d = $d * 0.10;
      $x2d = $x1d + 0.05;
      if ($x1d < $xeq) {
        if ($x2d > $xeq) { $x2d = $xeq; }
        $gr->moveTo($x1d, $pka);
        $gr->lineTo($x2d, $pka, 'gray', 1);
      }
    }

Tune dash length (0.05) and gap (0.05) relative to graph coordinates.
For vertical dashes, swap x and y in the loop.

## Dots and stamps

Use `stamps` with `closed_circle` or `open_circle` to mark individual
points:


    # Filled circle at a point
    $gr->stamps(closed_circle($x, $y, 'black'));

    # Open circle (hollow)
    $gr->stamps(open_circle($x, $y, 'black'));

## Label sizing: why labels look small

Labels in PGgraphmacros are GD bitmap text. This has important
consequences:

- `tex_size` on `image()` only affects TeX/PDF output, not HTML/GD
  output.
- TeX size commands (`\Large`, `\huge`) in label strings render as
  literal text in GD, not as formatting.
- `GD::Font->Giant` is the largest GD bitmap font (9 by 15 pixels) and
  is still small.
- **Rendering at 2x and displaying at 1x makes labels half-size.** GD
  text is fixed-pixel; there is no display-DPI concept.

### GD font sizes

Available via `$label->font(GD::Font->NAME)`:

  -----------------------------------------------------------------------
  Font              Pixel size            Notes
  ----------------- --------------------- -------------------------------
  `Tiny`            5 x 8                 Too small for most uses

  `Small`           6 x 12                Default in most PG builds

  `MediumBold`      7 x 13                Slightly larger

  `Large`           8 x 16                Good default choice

  `Giant`           9 x 15                Largest available
  -----------------------------------------------------------------------

All are fixed-size bitmap fonts. The size difference between Small and
Giant is modest.

### Pragmatic fixes for readable labels

Keep `size` at the final display dimensions (no 2x trick). Improve
readability through layout:


    # Slightly larger canvas with extra margin for labels
    $gr = init_graph(-0.6, -1.2, 3.4, 12.5,
      axes => [0, 0],
      grid => [8, 5],
      size => [520, 420],
    );

    # Axis labels at edges (right-aligned at plot boundary)
    $gr->lb(new Label(3.4, -0.7, 'OH- (equivalents)', 'black', 'right', 'top'));
    $gr->lb(new Label(-0.1, 12.5, 'pH', 'black', 'right', 'top'));

    # Fewer tick labels to reduce crowding
    for $yv (0, 2, 4, 6, 8, 10, 12) {
      $gr->lb(new Label(-0.08, $yv, $yv, 'black', 'right', 'middle'));
    }

    $graph_img = image(insertGraph($gr), width => 520, height => 420, tex_size => 700);

Key techniques:

- **Widen graph bounds** beyond data range (`-0.6` to `3.4` instead of
  `0` to `3`) to create margin space for labels.
- **Place axis labels at edges** using `$xmax`/`$ymax` coordinates with
  `'right', 'top'` alignment.
- **Reduce tick label count** to avoid crowding (every 2 or 4 units
  instead of every 1).
- **Use high contrast** (black text on white background).

## Worked example: triprotic titration curve

A single cubic polynomial **cannot** produce the correct titration curve
shape for a molecule with three pKa values. A cubic has at most one
inflection point, but a 3-pKa titration needs three sigmoid steps. The
correct approach uses a physical speciation model.

### Why not a cubic?

A cubic `ax^3 + bx^2 + cx + d` through four points:

- Has only **one inflection point** \-- a triprotic titration needs
  three sigmoid transitions.
- Anchors pKa values at integer equivalents (1, 2) instead of the
  correct half-equivalents (0.5, 1.5, 2.5).
- Produces a smooth bend, not the characteristic
  staircase-with-shoulders shape.

### Speciation model (correct shape)

Sweep pH and compute the equivalents of base (n_bar) from the charge
balance:


    n_bar = (Ka1*H^2 + 2*Ka1*Ka2*H + 3*Ka1*Ka2*Ka3)
          / (H^3 + Ka1*H^2 + Ka1*Ka2*H + Ka1*Ka2*Ka3)

This gives three sigmoid steps with buffer flats at half-equivalence
points (0.5, 1.5, 2.5 equivalents) and steep transitions at equivalence
points (1.0, 2.0 equivalents).

### Copy and edit (triprotic titration)


    $Ka1_val = 10**(-$pKa1_num);
    $Ka2_val = 10**(-$pKaR_num);
    $Ka3_val = 10**(-$pKa2_num);

    $num_pts = 400;
    $ph_lo = 0.5;
    $ph_hi = 12.5;
    $first_pt = 1;
    for $i (0..$num_pts) {
      $ph_sweep = $ph_lo + ($ph_hi - $ph_lo) * $i / $num_pts;
      $H_conc = 10**(-$ph_sweep);

      $denom = $H_conc**3
             + $Ka1_val * $H_conc**2
             + $Ka1_val * $Ka2_val * $H_conc
             + $Ka1_val * $Ka2_val * $Ka3_val;
      $nbar = ($Ka1_val * $H_conc**2
             + 2 * $Ka1_val * $Ka2_val * $H_conc
             + 3 * $Ka1_val * $Ka2_val * $Ka3_val) / $denom;

      if ($nbar >= 0 && $nbar <= 3.0) {
        if ($first_pt) {
          $gr->moveTo($nbar, $ph_sweep);
          $first_pt = 0;
        } else {
          $gr->lineTo($nbar, $ph_sweep, 'blue', 2);
        }
      }
    }

This sweeps pH (y-axis) uniformly and computes equivalents (x-axis) as
the dependent variable. The `moveTo`/`lineTo` approach handles this
naturally since x is not the sweep variable.

### Alternative: stacked logistic sigmoids

If you do not need physical accuracy, three logistic functions centered
at half-equivalents approximate the shape. Note that this version does
**not** pass exactly through pKa at each half-equivalence point; the
speciation model is preferred for accuracy.


    $k = 10;  # steepness
    $y0 = 1.0;
    $y_top = 11.5;

    for $i (0..300) {
      $xx = 3.0 * $i / 300.0;
      $s1 = 1 / (1 + exp(-$k * ($xx - 0.5)));
      $s2 = 1 / (1 + exp(-$k * ($xx - 1.5)));
      $s3 = 1 / (1 + exp(-$k * ($xx - 2.5)));

      $ph = $y0
          + ($pKa1_num - $y0) * $s1
          + ($pKaR_num - $pKa1_num) * $s2
          + ($pKa2_num - $pKaR_num) * $s3
          + ($y_top - $pKa2_num) * $s3 * 0.20;

      # draw with moveTo/lineTo as shown above
    }

## GraphTool warning: answer evaluator interference

`parserGraphTool.pl` creates a JS-based interactive canvas where
students can draw or place points. Its `ans_rule()` registers an answer
entry (typically `AnSwEr0001`). This shifts the numbering of subsequent
PGML answer blanks and can cause `"Unrecognized evaluator type ||"`
errors on later RadioButtons or other PGML widgets.

**Workaround** (if you must use GraphTool alongside PGML answers):

- Place GraphTool in a `BEGIN_TEXT` block with `\{$gt->ans_rule()\}`.
- Use `LABELED_ANS($gt_ans_id, $gt_checker)` before the PGML block.
- Keep RadioButtons and other widgets in a separate `BEGIN_PGML` block.

**Better approach:** if the graph is display-only, use
`PGgraphmacros.pl` instead.

## Sizing and margins

The `size` parameter in `init_graph` sets the GD image pixel dimensions.
The `width` and `height` in `image()` control the HTML display size.
**Always keep these matched at 1x** \-- rendering at 2x and displaying
at 1x shrinks bitmap labels.


    # Good: matched sizes, extra margin from wider bounds
    $gr = init_graph(-0.6, -1.2, 3.4, 12.5,
      axes => [0, 0],
      grid => [8, 5],
      size => [520, 420],
    );
    $graph_img = image(insertGraph($gr), width => 520, height => 420, tex_size => 700);

To create margin space for labels without shrinking the data region,
widen the graph bounds beyond the data range (e.g., `-0.6` to `3.4` for
data spanning 0 to 3).

`tex_size` controls the image width in TeX/PDF output only (700 = 70% of
text width). It has no effect on HTML/GD rendering.

## Variable scoping reminder

Do **not** use `my` on any variable that PGML needs to interpolate. PG
runs in a safe compartment where `my` variables are invisible to PGML.


    # WRONG - invisible to PGML
    my $graph_img = image(insertGraph($gr), ...);

    # RIGHT - package-level, visible to PGML
    $graph_img = image(insertGraph($gr), ...);

## Unavailable macros

The following graph-related macros exist in the OPL but are **not**
available in the local PG 2.17 renderer:

- `PGlateximage.pl` (LaTeX-to-image pipeline, requires LaTeX
  installation)
- `PGtikz.pl` (TikZ/pgfplots, requires LaTeX installation)

Stick to `PGgraphmacros.pl` for display graphs and `parserGraphTool.pl`
for interactive graphs.

## Complete working example

**Simple function graph with numeric answer** \-- A full problem that
plots a linear function and asks students to read a value from the
graph.


    ## TITLE('Read a value from a graph')
    ## DESCRIPTION
    ## A linear function is plotted on a graph. Students read
    ## the y-value at a given x-coordinate.
    ## ENDDESCRIPTION
    ## KEYWORDS('graph','PGgraphmacros','numeric','function plot')
    ## DBsubject('Biostatistics')
    ## DBchapter('Data Visualization')
    ## DBsection('Reading Graphs')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGgraphmacros.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $m = random(1, 3, 1);
    $b = random(1, 4, 1);
    $x_ask = random(2, 5, 1);
    $y_ans = Real($m * $x_ask + $b);

    $gr = init_graph(-1, -1, 8, 20,
        axes  => [0, 0],
        grid  => [9, 21],
        size  => [400, 400],
    );
    add_functions($gr,
        "$m*x + $b for x in <0,8> using color:blue and weight:2"
    );

    $graph_img = image(insertGraph($gr),
        width => 400, height => 400, tex_size => 700);

    BEGIN_PGML
    The graph below shows a linear function.

    [$graph_img]*

    What is the y-value when x = [$x_ask]? [________]{$y_ans}
    END_PGML

    ENDDOCUMENT();

## Apply it today

- Use `PGgraphmacros.pl` for any display-only graph. Reserve
  `parserGraphTool.pl` for problems where students answer by drawing.
- Match `init_graph size` to `image() width/height` at 1x so bitmap
  labels stay readable.
- Widen graph bounds to create margin space for axis labels and tick
  marks.
- Use `moveTo`/`lineTo` for curves where x is not the independent
  variable (titration curves, parametric shapes).
- Avoid `my` on any variable referenced inside PGML blocks.

---

# 06_Advanced_PGML_Techniques/6.4-Advanced_Randomization_Techinques

This page summarizes safer randomization patterns in the PG 2.17 subset.
The goal is to avoid impossible values, repeated variants, and
hard-to-reproduce failures.

**Use this page when:** you need multi-step randomization or constraints
between values, or you want to choose the right randomization function
for your situation. Randomization variables are typically defined in the
Setup block (see [Section 4.4](/@go/page/555711)). For testing
randomized variants, see [Section 7.4](/@go/page/557411).

## Built-in random functions are already seeded

The PG environment automatically seeds the random number generator with
`$problemSeed` before your problem code runs. For most problems, you can
use the built-in random functions directly without any manual seeding.
The same `$problemSeed` always produces the same sequence of random
values, so student results are reproducible.


    # These functions are already deterministic based on $problemSeed.
    # No manual seeding required for most problems.
    $value = random(1, 10, 1);
    $item = list_random(@items);
    $nonzero = non_zero_random(-5, 5, 1);

## Core randomization functions (PGbasicmacros.pl)

  -----------------------------------------------------------------------------------------
  Function                              What it does                 When to use it
  ------------------------------------- ---------------------------- ----------------------
  `random(begin, end, incr)`            Returns a random number from Numeric ranges like
                                        begin to end stepping by     concentrations,
                                        incr.                        volumes, or counts.

  `non_zero_random(begin, end, incr)`   Same as random but excludes  Denominators,
                                        zero from the result.        divisors, or any value
                                                                     that must not be zero.

  `list_random(@list)`                  Returns one randomly chosen  Choosing from named
                                        element from the list.       items like enzymes,
                                                                     organisms, or codons.

  `SRAND(seed)`                         Resets the global PG random  Rarely needed. The
                                        generator to a specific      environment already
                                        seed.                        seeds with
                                                                     problemSeed.
  -----------------------------------------------------------------------------------------

## Other randomization helpers

- `random_coprime([arrays...])` and
  `random_pairwise_coprime([arrays...])` from PGauxiliaryFunctions.pl
  return coprime integers.
- `randomOrder(...)` in parserPopUp.pl and parserRadioButtons.pl
  shuffles answer choices.
- `randomPrime(start, end)` from contextInteger.pl returns a random
  prime in the given range.

## Statistics distribution functions

These functions generate random samples from common probability
distributions, useful for statistics and quantitative biology problems.

  -------------------------------------------------------------------------------
  Function                           Distribution
  ---------------------------------- --------------------------------------------
  `urand(mean, sd, N, digits)`       Normal distribution with given mean and
                                     standard deviation.

  `exprand(lambda, N, digits)`       Exponential distribution with rate parameter
                                     lambda.

  `poissonrand(lambda, N)`           Poisson distribution with rate parameter
                                     lambda.

  `binomrand(p, N, num)`             Binomial distribution with probability p and
                                     N trials.

  `bernoullirand(p, num, options)`   Bernoulli distribution (single trial,
                                     probability p).

  `discreterand(n, @table)`          Discrete distribution from a probability
                                     table.
  -------------------------------------------------------------------------------

## Manual PGrandom: when and how

Most problems do not need a manual PGrandom object. Only create one when
you need multiple independent random streams or explicit control over
seeding for complex multi-stage randomization.


    # CORRECT: create an instance, then call srand on the instance.
    $local_random = PGrandom->new();
    $local_random->srand($problemSeed);

    # Use the instance methods for random values.
    $value = $local_random->random(1, 10, 1);
    $item = $local_random->list_random('A', 'B', 'C');

### Common PGrandom mistakes

  ---------------------------------------------------------------------------
  Mistake                           Why it fails
  --------------------------------- -----------------------------------------
  `PGrandom->seed($problemSeed)`    The method is called `srand`, not `seed`.

  `PGrandom->srand($problemSeed)`   Cannot call `srand` as a class method.
                                    Create an instance with `PGrandom->new()`
                                    first.

  `SRAND($problemSeed)`             Resets the global RNG. Usually
                                    unnecessary because it is already seeded.
  ---------------------------------------------------------------------------

## Practical tips

- **Sort hash keys before random selection.** Hash key order is not
  guaranteed in Perl. Always sort keys first so the same seed yields the
  same result across runs.
- **Avoid NchooseK and shuffle.** These are deprecated in the PG 2.17
  subset. Use built-in random selection or manual array manipulation for
  subsets.
- **Record the seed when debugging.** Use `$problemSeed` to reproduce
  failures exactly.

<!-- -->


    # Sort hash keys before selecting randomly.
    @sorted_keys = sort keys %hash;
    $selected = list_random(@sorted_keys);

## Guard patterns

Always add guard checks so randomization never produces impossible
cases.

### Zero denominators


    $den = random(1, 9, 1);
    if ($den == 0) { $den = 1; }
    $ratio = $num / $den;

### Repeated values


    $a = random(1, 10, 1);
    do { $b = random(1, 10, 1); } until ($b != $a);

### Invalid domains


    # Ensure the argument to log is positive.
    $conc = random(1, 100, 1);
    if ($conc <= 0) { $conc = 1; }
    $pH = -log($conc / 1000) / log(10);

### Negative concentrations


    $stock = random(10, 100, 5);
    $dilution = random(2, 20, 1);
    $final = $stock / $dilution;
    if ($final < 0.1) {
        $dilution = 2;
        $final = $stock / $dilution;
    }

## Biology-specific randomization examples

### Randomized dilution series


    $stock_mM = random(10, 50, 5);
    $dilution_factor = list_random(2, 5, 10, 20);
    $final_uM = ($stock_mM * 1000) / $dilution_factor;

### Randomized genetics cross


    # Monohybrid cross with valid Mendelian ratios.
    @dominant_traits = ('Tall', 'Round', 'Purple', 'Axial');
    @recessive_traits = ('Short', 'Wrinkled', 'White', 'Terminal');
    $idx = random(0, scalar(@dominant_traits) - 1, 1);
    $dominant = $dominant_traits[$idx];
    $recessive = $recessive_traits[$idx];
    $total_offspring = random(40, 120, 4);
    $expected_dominant = 3 * $total_offspring / 4;
    $expected_recessive = $total_offspring / 4;

### Randomized qPCR conditions


    # qPCR problem with plausible Ct values and efficiency.
    $efficiency = random(90, 100, 1) / 100;
    $Ct_control = random(18, 25, 1);
    $fold_change = list_random(2, 4, 8, 16);
    $delta_Ct = -log($fold_change) / log(1 + $efficiency);
    $Ct_treated = $Ct_control + $delta_Ct;

## Complete working example

**Randomized genetics problem** \-- A full problem demonstrating
`random()` and `list_random()` with biology content and a guard check to
prevent repeated values.


    ## TITLE('Randomized genetics offspring count')
    ## DESCRIPTION
    ## Calculate the expected number of offspring showing the
    ## dominant phenotype from a randomized monohybrid cross.
    ## ENDDESCRIPTION
    ## KEYWORDS('genetics','randomization','numeric','list_random')
    ## DBsubject('Genetics')
    ## DBchapter('Mendelian Genetics')
    ## DBsection('Expected Ratios')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    @traits = ('Tall', 'Round', 'Purple', 'Axial');
    $trait = list_random(@traits);
    $total = random(40, 120, 4);
    $expected_dom = Real(3 * $total / 4);

    BEGIN_PGML
    In a monohybrid cross between two heterozygous plants,
    [$total] offspring are produced. The dominant trait is
    "[$trait]".

    How many offspring are expected to show the dominant
    phenotype? [________]{$expected_dom}
    END_PGML

    ENDDOCUMENT();

## Apply it today

- Use the built-in `random()` functions for most problems. They are
  already seeded.
- Only create a PGrandom instance when you need independent random
  streams.
- Add guard checks so randomization never produces impossible cases.
- Sort hash keys before random selection for deterministic results.

---

# 06_Advanced_PGML_Techniques/6.5-Randomized_Matching_Problems

This page covers modern matching problems using PopUp widgets and
two-column layouts. It also explains the one case where
`MODES(HTML => ...)` is required: wrapper HTML that must be emitted from
inside Perl eval blocks that build dynamic HTML with `join()`.

**Use this page when:** you need a two-column matching layout with
consistent labels and randomized ordering. For basic matching with PopUp
dropdowns, see [Section 5.4](/@go/page/555717).

## When to use matching vs other question types

Matching problems work best for:

- **Definitions:** Match terms with their meanings (e.g., genotype vs
  phenotype)
- **Associations:** Connect related concepts (e.g., enzyme names with
  their substrates)
- **Component identification:** Link structures to functions (e.g.,
  organelles to their roles)
- **Classification:** Match examples to categories (e.g., bond types to
  molecular scenarios)

**Not ideal for:**

- Pure memorization with no conceptual pairing
- Sequence ordering (use drag-and-drop or ordered list instead)
- True/false evaluation of statements (use RadioButtons per statement,
  see Chapter 6.4)

**Typical problem sizes:** 4-8 pairs work well. Fewer than 4 is too
easy; more than 8 becomes cognitively overwhelming and increases
guessing.

## PopUp widgets for matching

Use `PopUp` widgets from `parserPopUp.pl` to create dropdown menus in
the left column. Note that `DropDown` is a PG 2.18+ macro and is not
available in the PG 2.17 subset used by ADAPT/renderer.

### Widget creation pattern


    loadMacros(
      "PGstandard.pl",
      "PGML.pl",
      "parserPopUp.pl",
      "PGcourse.pl",
    );

    # Define choices (labels A, B, C, D for 4 answers)
    my @choices = ('A', 'B', 'C', 'D');

    # Define correct answers (mapped to choices)
    my @correct_answers = ('B', 'D', 'A', 'C');  # Correct letter for each question

    # Create PopUp widgets
    my @answer_dropdowns = map { PopUp(\@choices, $correct_answers[$_]) } 0 .. $#correct_answers;

### How shuffle arrays work

Use the `shuffle()` function to randomize the order of right-column
answers while maintaining correct left-right mapping:


    my @questions = (
      'Two oxygen atoms share electrons equally',
      'Sodium transfers an electron to chlorine',
      'Partial charges on C-O bond',
      'O-H bond attracted to nearby C=O',
    );

    my @answers = (
      'non-polar covalent bond',
      'ionic bond',
      'polar covalent bond',
      'hydrogen bond',
    );

    # Shuffle the right column
    my @shuffle = shuffle(scalar(@answers));  # Returns a permutation [0..3]

    # Now answers appear in shuffled order, but @shuffle maps them back to originals

### Answer evaluation in PGML

In the left column, use `[_]{$answer_dropdowns[$i]}` to insert each
PopUp widget. The student selects a letter from the dropdown, and
WeBWorK checks it against the correct answer stored in the widget.

## Two layout patterns: When MODES is needed

There are two ways to build matching layouts: with wrapper tags directly
in PGML (preferred), or with `MODES` when wrapper HTML must be emitted
from inside Perl eval blocks.

### Pattern 1: Wrapper tags directly in PGML (preferred)

If you can write the wrapper `<div>` tags directly in PGML, do that.
This avoids `MODES` entirely and is easier to read and maintain.


    BEGIN_PGML
    Match each molecular scenario with its bond type.

    <div class="two-column">
    <div>
    [@ join("\n\n", map {
      '[_]{$answer_dropdowns[' . $_ . ']} '
        . '*' . ($_ + 1) . '.* '
        . $questions[$_]
    } 0 .. $#questions) @]**
    </div>

    <div>
    [@ join("\n\n", map {
      '*' . chr(65 + $_) . '.* '
        . $answers[$shuffle[$_]]
    } 0 .. $#answers) @]**
    </div>
    </div>
    END_PGML

In this pattern, the `<div class="two-column">` wrapper is written
directly in PGML. The `join()` expressions build the content for each
column, and PGML processes everything correctly without needing `MODES`.

### Pattern 2: MODES when wrapper must be in eval block (required in specific cases)

Use `MODES(HTML => ...)` only when the wrapper tags must be built inside
a Perl eval block, such as when the wrapper and content are created
together in a single Perl variable. Without `MODES`, the wrapper HTML
gets escaped by PGML and the layout collapses to a single column.


    # Build left column HTML
    my $left_html = join("\n\n", map {
      '[_]{$answer_dropdowns[' . $_ . ']} '
        . '*' . ($_ + 1) . '.* '
        . $questions[$_]
    } 0 .. $#questions);

    # Build right column HTML
    my $right_html = join("\n\n", map {
      '*' . chr(65 + $_) . '.* '
        . $answers[$shuffle[$_]]
    } 0 .. $#answers);

    # Wrap with MODES because wrapper tags are in eval block
    my $columns = MODES(HTML => "<div class='two-column'><div>\n$left_html\n</div><div>\n$right_html\n</div></div>");

    BEGIN_PGML
    [$columns]*
    END_PGML

In this pattern, the wrapper `<div>` tags are built inside the Perl
variable `$columns`, so `MODES` is required to prevent PGML from
escaping them.

### Pattern 3: Inline MODES for wrapper segments (alternative)

You can also emit wrapper HTML segments using inline `MODES` calls
between `join()` expressions:


    BEGIN_PGML
    Match each molecular scenario with its bond type.

    [@ MODES(HTML => '<div class="two-column"><div>') @]*
    [@ join("\n\n", map { ... } 0 .. $#questions) @]**
    [@ MODES(HTML => '</div><div>') @]*
    [@ join("\n\n", map { ... } 0 .. $#answers) @]**
    [@ MODES(HTML => '</div></div>') @]*
    END_PGML

This is a middle-ground approach. Use it when you want the wrapper
segments close to the content but cannot write them directly as plain
HTML in PGML.

### Why MODES is needed (technical explanation)

PGML parses content once and escapes HTML tags for safety. When wrapper
`<div>` tags are inside Perl variables or eval blocks, PGML sees them as
data to be escaped, not markup. Using `MODES(HTML => ...)` tells PG to
emit the HTML directly without escaping, but only in HTML output mode
(not TeX/PDF mode).

**What happens if you forget MODES:** The wrapper `<div>` tags appear as
literal text in the rendered problem (e.g.,
`&lt;div class="two-column"&gt;`) or are stripped entirely, causing the
layout to collapse to a single column.

## CSS styling for two-column layout

Use `HEADER_TEXT` with flexbox CSS to create a responsive two-column
layout. This style works across devices and wraps to a single column on
narrow screens.

### Recommended flexbox style


    HEADER_TEXT(MODES(HTML => <<'END_STYLE'));
    <style>
    .two-column {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      align-items: flex-start;
      justify-content: space-evenly;
    }
    .two-column > div {
      flex: 1 1 40%;
      min-width: 250px;
    }
    </style>
    END_STYLE

### CSS property explanations

- `display: flex;` - Creates a flexible container for the two columns
- `flex-wrap: wrap;` - Allows columns to wrap on narrow screens
  (mobile-friendly)
- `gap: 2rem;` - Adds spacing between columns
- `align-items: flex-start;` - Aligns columns to the top (not vertically
  centered)
- `justify-content: space-evenly;` - Distributes horizontal space evenly
- `flex: 1 1 40%;` - Each column takes \~40% width, can grow or shrink
- `min-width: 250px;` - Prevents columns from becoming too narrow

### Alternative alignment options

- `align-items: center;` - Vertically center columns (use if heights
  differ significantly)
- `justify-content: space-between;` - Push columns to edges with space
  between
- `gap: 1rem;` - Reduce spacing for compact layouts

## Colored labels for fixed label-to-meaning mapping

When answer labels need fixed colors by meaning (not by position), build
an HTML mapping in Perl and emit the labels with the `[$var]*` pattern
(trailing asterisk required) so PGML does not escape the `<span>` tags.

### Building the color mapping


    # Label -> HTML mapping (fixed colors by meaning)
    my %answer_html = (
      'polar covalent bond' => '<span style="color:#00b3b3; font-weight:700;">polar covalent bond</span>',
      'non-polar covalent bond' => '<span style="color:#b3b300; font-weight:700;">non-polar covalent bond</span>',
      'ionic bond' => '<span style="color:#009900; font-weight:700;">ionic bond</span>',
      'hydrogen bond' => '<span style="color:#e60000; font-weight:700;">hydrogen bond</span>',
    );

    # Build colored HTML labels array
    my @answers_html = map { $answer_html{$_} } @answers;

### Emitting colored labels in PGML

In the right-column `join()` expression, use
`[$answers_html[$shuffle[$_]]]*` with the trailing asterisk to pass
through the HTML without escaping:


    [@ join(
      "\n\n",
      map {
        '*' . chr(65 + $_) . '.* '
          . '[$answers_html[$shuffle[' . $_ . ']]]*'
      } 0 .. $#answers
    ) @]**

### Why the trailing asterisk is required

Without the trailing `*`, PGML escapes HTML tags for safety. Using
`[$var]*` tells PGML to pass through the variable\'s content as raw
HTML. This keeps colors tied to label meaning even when the order is
randomized. For more on this pattern, see Chapter 6.1.

## Biology examples

### Example 1: Chemical bond types

**Scenario:** Match molecular interactions with the correct bond type.
Use colored labels to distinguish bond types visually.


    my @questions = (
      'Two oxygen atoms share electrons equally',
      'Sodium transfers an electron to chlorine',
      'Partial charges on C-O bond',
      'O-H bond attracted to nearby C=O',
    );

    my @answers = (
      'non-polar covalent bond',
      'ionic bond',
      'polar covalent bond',
      'hydrogen bond',
    );

    my @shuffle = shuffle(scalar(@answers));

    my %answer_html = (
      'non-polar covalent bond' => '<span style="color:#b3b300; font-weight:700;">non-polar covalent bond</span>',
      'ionic bond' => '<span style="color:#009900; font-weight:700;">ionic bond</span>',
      'polar covalent bond' => '<span style="color:#00b3b3; font-weight:700;">polar covalent bond</span>',
      'hydrogen bond' => '<span style="color:#e60000; font-weight:700;">hydrogen bond</span>',
    );
    my @answers_html = map { $answer_html{$_} } @answers;

**Note:** Fixed colors ensure that \"hydrogen bond\" is always red,
regardless of randomization, helping students build consistent mental
associations.

### Example 2: Pathway components matched to functions

**Scenario:** Match glycolytic enzymes with their specific reactions in
the pathway.


    my @questions = (
      'Converts glucose-6-phosphate to fructose-6-phosphate',
      'Phosphorylates fructose-6-phosphate (rate-limiting step)',
      'Splits fructose-1,6-bisphosphate into two 3-carbon sugars',
      'Converts phosphoenolpyruvate to pyruvate (ATP-generating step)',
    );

    my @answers = (
      'phosphoglucose isomerase',
      'phosphofructokinase-1',
      'aldolase',
      'pyruvate kinase',
    );

    my @choices = ('A', 'B', 'C', 'D');
    my @shuffle = shuffle(scalar(@answers));

    my @correct_answers = map { $choices[$shuffle[$_]] } 0 .. $#questions;
    my @answer_dropdowns = map { PopUp(\@choices, $correct_answers[$_]) } 0 .. $#questions;

**Note:** This example demonstrates function-to-enzyme matching without
colors, focusing on conceptual pairing for pathway memorization.

### Example 3: Genetics terminology matched to definitions

**Scenario:** Match genetics terms with their formal definitions.


    my @questions = (
      'Observable physical characteristic',
      'Genetic makeup at a locus',
      'Alternative form of a gene',
      'Physical location of a gene on a chromosome',
    );

    my @answers = (
      'phenotype',
      'genotype',
      'allele',
      'locus',
    );

    my @choices = ('A', 'B', 'C', 'D');
    my @shuffle = shuffle(scalar(@answers));

    my @correct_answers = map { $choices[$shuffle[$_]] } 0 .. $#questions;
    my @answer_dropdowns = map { PopUp(\@choices, $correct_answers[$_]) } 0 .. $#questions;

**Note:** This is a pure definition-matching problem, ideal for
introducing formal terminology early in a genetics unit.

## Common failures and fixes

### Failure 1: Forgot trailing asterisk on colored labels

**Symptom:** Raw `<span>` tags appear in the rendered problem instead of
colored text.

**Cause:** Used `[$var]` instead of `[$var]*`, so PGML escaped the HTML
for safety.

**Fix:** Always use `[$answers_html[$shuffle[$_]]]*` with the trailing
asterisk to pass through HTML.

**Prevention:** Check all variable interpolations that contain HTML. The
rule is: `[$var]*` for HTML, `[$var]` for plain text.

### Failure 2: Used MODES for everything

**Symptom:** Code works but is unnecessarily complex and harder to
maintain.

**Cause:** Wrapped every HTML snippet in `MODES`, including cases where
wrapper tags could be written directly in PGML.

**Fix:** Use Pattern 1 (wrapper tags directly in PGML) whenever
possible. Only use `MODES` when the wrapper HTML is inside Perl eval
blocks.

**Prevention:** Ask: \"Can I write these `<div>` tags directly in
PGML?\" If yes, do that.

### Failure 3: Shuffle array index mismatch

**Symptom:** Wrong answers are marked correct. Dropdown selections
don\'t map to the displayed right-column labels.

**Cause:** Used `$shuffle[$_]` incorrectly in left column or right
column, breaking the mapping.

**Fix:** Verify that left column uses `$answer_dropdowns[$_]` (no
shuffle) and right column uses `$answers[$shuffle[$_]]` (with shuffle).

**Prevention:** Test with `problemSeed` values that produce different
shuffle orders. Check that correct answers remain correct.

### Failure 4: PopUp choices don\'t match answer labels

**Symptom:** Dropdown shows letters that don\'t appear in the right
column, or vice versa.

**Cause:** Used different `@choices` arrays for PopUp creation and
right-column labels.

**Fix:** Use the same `@choices` array (e.g., `('A', 'B', 'C', 'D')`)
for both PopUp widget creation and right-column label generation.

**Prevention:** Define `@choices` once at the top of setup and reference
it everywhere.

### Failure 5: Layout collapses to single column

**Symptom:** Both columns stack vertically instead of appearing
side-by-side.

**Cause:** Wrapper `<div>` tags were built in Perl without `MODES`, so
PGML escaped them.

**Fix:** Either move wrapper tags directly into PGML (Pattern 1) or wrap
them with `MODES(HTML => ...)` (Pattern 2).

**Prevention:** If wrapper HTML is inside a Perl variable, use `MODES`.
If it\'s directly in PGML, no `MODES` needed.

## Creating matching banks with YAML

Instead of writing each matching problem by hand, you can define a bank
of matching pairs in a YAML file and use a generator script to produce
PGML files automatically. This workflow separates content authoring from
code, making it easier for instructors to contribute questions without
editing Perl.

### File naming convention

Use filenames that are readable to instructors and map naturally to
course chapters. Follow the pattern: topic prefix + plain-English
descriptor.

- `enzymes_basics.yml` \-- enzyme classes matched to reaction types
- `senses_receptor_types.yml` \-- receptor types matched to sensory
  modalities
- `metabolism_pathway_components.yml` \-- pathway enzymes matched to
  functions

Avoid deep jargon in filenames (keep jargon inside the YAML content).
Future-you should know what the bank covers without opening the file.

### YAML file structure

Every YAML bank requires four top-level keys that describe what students
are matching:

  Key                    Purpose                               Example
  ---------------------- ------------------------------------- ------------------
  `key description`      Singular label for the left column    `enzyme class`
  `keys description`     Plural label for the left column      `enzyme classes`
  `value description`    Singular label for the right column   `reaction type`
  `values description`   Plural label for the right column     `reaction types`

The fifth required key is `matching pairs`, which holds the actual
content (see next section).

### Matching pairs format

Under `matching pairs`, each key maps to a list of one or more values.
Each key is a left-column concept; each value is a right-column
definition or function.


    matching pairs:
      Kinase:
        - Adds a phosphate group to a substrate (phosphorylation)
        - Transfers a phosphate group to a molecule
      Phosphatase:
        - Removes a phosphate group from a substrate (dephosphorylation)
        - Catalyzes phosphate removal from a molecule

Each key must map to a YAML list, even if there is only one value. For
each generated question, the generator picks one value per key at
random.

### Same concept, different phrasing

The most important quality rule: put synonyms and equivalent statements
under one key as multiple values. Do not split a single concept across
multiple keys (that turns synonyms into trick questions).

This makes banks feel fresh without changing what you are assessing.
Students see one wording per key in any single question, but across
different generated questions the bank naturally rotates through
alternate wordings.


    matching pairs:
      Protease:
        - Breaks peptide bonds in proteins
        - Hydrolyzes peptide bonds
      Ligase:
        - Joins two molecules by forming a new bond (often using ATP)
        - Catalyzes bond formation to link molecules

### Excluding confusable pairs

If two keys are too similar (or their values are too easy to mix up),
use `exclude pairs` so they never appear together in the same question:


    exclude pairs:
      - [Coenzyme, Cofactor]
      - [competitive inhibitor, non-competitive inhibitor]

Use `exclude pairs` sparingly, only for classic confusions where
students can reasonably know both terms yet still mix them up under time
pressure. Do not exclude pairs just because two terms are related \--
that can remove the learning objective.

### Replacement rules for formatting and color

The `replacement_rules` key defines simple search-and-replace
substitutions applied after question text is constructed. This is
commonly used for highlighting phrases with color or ensuring consistent
typography.


    replacement_rules:
      releases&nbsp;energy: "<span style='color: #e60000;'>releases&nbsp;energy</span>"

Colors are assigned deterministically: the same prompt set gets the same
colors on every run. If any prompt already contains HTML color markup,
automatic coloring is disabled for the entire question so author-chosen
colors are preserved.

### Optional metadata keys

The generators ignore unknown top-level keys, so you can add
author-facing metadata for long-term maintenance:

- `topic` \-- short label (e.g., `phototransduction`)
- `learning_objective` \-- one sentence (e.g.,
  `Trace the cGMP pathway in rods`)
- `source` \-- textbook or chapter reference
- `items to match per question` \-- how many pairs appear per question
  (default 5)

## Generating PGML files from YAML

The `yaml_match_to_pgml.py` script reads a YAML bank and produces
matching-problem PGML files. The generated files follow the same PopUp
widget and `MODES` wrapper patterns described earlier in this chapter.

**What the generator does:**

- Reads the YAML matching pairs and descriptions
- Selects one value per key at random (rotating through phrasings across
  runs)
- Applies replacement rules for color and formatting
- Unescapes HTML entities (named and numeric) into Unicode for rendering
  without MathJax
- Converts `<sub>`/`<sup>` tags into Unicode subscripts/superscripts
- Outputs PGML files using the two-column flexbox layout with PopUp
  widgets

The default output uses inline HTML spans for replacement-rule colors.
Use `--no-color` to disable styling.

## Quality checks for matching banks

Before shipping a new matching set, run through these checks:

  Check                               What to look for
  ----------------------------------- -------------------------------------------------------------------------------------------
  Single learning objective per key   Each key should test one concept, not a bundle of related facts
  Parallel grammar                    All values should use the same grammatical form (all noun phrases, or all full sentences)
  Similar value length                If one answer is much longer than others, students use length as a hint
  No keyword cues                     If a prompt contains a distinctive word, do not repeat it in the matching value
  Distinct values across keys         If multiple keys could match the same value text, students are guessing
  Accessibility                       Do not rely on color alone to convey meaning; use color as an accent

## Difficulty control

Adjust the difficulty of matching questions by changing the number of
items and the phrasing style:

- **Easier:** Use direct definitions and unique vocabulary. Set
  `items to match per question: 3` or `4` for fewer items per question.
- **Harder:** Use mechanism or consequence phrasing instead of
  definitions. Include more similar terms in the bank, then use
  `exclude pairs` for the worst confusions.

## Copy/paste YAML example: enzyme classes

This is a complete, working YAML file for a matching bank. Copy it as a
starting point for new banks.


    #YAML file for Matching Questions
    topic: enzymes_basics
    learning_objective: Match enzyme classes to what they do.

    items to match per question: 5

    key description: enzyme class
    keys description: enzyme classes

    value description: reaction type
    values description: reaction types

    matching pairs:
      Kinase:
        - Adds a phosphate group to a substrate (phosphorylation)
        - Transfers a phosphate group to a molecule
      Phosphatase:
        - Removes a phosphate group from a substrate (dephosphorylation)
        - Catalyzes phosphate removal from a molecule
      Protease:
        - Breaks peptide bonds in proteins
        - Hydrolyzes peptide bonds
      Ligase:
        - Joins two molecules by forming a new bond (often using ATP)
        - Catalyzes bond formation to link molecules
      Isomerase:
        - Rearranges atoms within a molecule to form an isomer
        - Converts a molecule into its isomer

Each enzyme class key has two phrasing variants. The generator picks one
wording per question, so students see different phrasings across
attempts while always being assessed on the same concept.

## Complete working example

**Organelle function matching** \-- A full problem using PopUp dropdowns
to match organelles with their primary functions.


    ## TITLE('Match organelles to functions')
    ## DESCRIPTION
    ## Match each organelle with its primary function using
    ## PopUp dropdown widgets.
    ## ENDDESCRIPTION
    ## KEYWORDS('organelles','matching','PopUp','cell biology')
    ## DBsubject('Cell Biology')
    ## DBchapter('Organelles')
    ## DBsection('Function')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserPopUp.pl",
        "PGcourse.pl",
    );

    @functions = ('ATP production', 'Protein sorting',
        'Intracellular digestion', 'Lipid synthesis');

    $popup1 = PopUp(['?', @functions], 'ATP production');
    $popup2 = PopUp(['?', @functions], 'Protein sorting');
    $popup3 = PopUp(['?', @functions], 'Intracellular digestion');
    $popup4 = PopUp(['?', @functions], 'Lipid synthesis');

    BEGIN_PGML
    Match each organelle with its primary function.

    1. Mitochondrion [_]{$popup1}

    2. Golgi apparatus [_]{$popup2}

    3. Lysosome [_]{$popup3}

    4. Smooth ER [_]{$popup4}
    END_PGML

    ENDDOCUMENT();

## Apply it today

- Write wrapper `<div>` tags directly in PGML whenever possible (Pattern
  1).
- Use `MODES(HTML => ...)` only for wrapper HTML built inside eval
  blocks (Pattern 2).
- Always use `[$var]*` (trailing asterisk) for HTML variables to prevent
  escaping.
- Define `@choices` once and use it for both PopUp widgets and
  right-column labels.
- Test with multiple `problemSeed` values to verify shuffle mapping
  works correctly.
- Use 4-8 pairs for optimal cognitive load and assessment effectiveness.
- For YAML-based banks, define 8-20 keys with 2-4 phrasing variants
  each.
- Run quality checks for parallel grammar, similar value length, and no
  keyword cues.
- For more on colored emphasis, see [Section 6.1](/@go/page/555723). For
  statement-based questions, see [Section 6.4](/@go/page/555726).

---

# 06_Advanced_PGML_Techniques/6.6-Randomized_MC_True_False_Statements

This page shows how to build statement-by-statement evaluation prompts
using RadioButtons or PopUp widgets for each statement. It also covers
how to create YAML-based statement banks and generate multiple-choice
\"Which statement is TRUE/FALSE?\" questions from them.

**Use this page when:** you want students to mark each statement as
true/false or correct/incorrect rather than choose one best answer, or
when you want to generate multiple-choice questions from curated pools
of true and false statements. For basic single-answer multiple choice,
see [Section 5.2](/@go/page/555715). For checkbox-style multiple answer,
see [Section 5.3](/@go/page/555716).

## When to use MC statements vs matching sets

Statement-based multiple choice is best when you want students to
**evaluate ideas** (truth or falsehood), not just map terms to
definitions.

Good fits for MC statements:

- \"Which statement is TRUE/FALSE?\" conceptual checks
- Misconception diagnostics (wrong molecule, wrong direction, wrong
  location, sign flips)
- \"Why\" and \"what changes\" logic that is hard to make one-to-one

If your goal is to map terms or components to their matching definitions
or functions (especially pathways and part-to-function), consider a
matching set instead (see Chapter 6.3).

## Copy and edit (RadioButtons per statement)


    $tf = [ 'True', 'False' ];
    $rb1 = RadioButtons($tf, 'True');
    $rb2 = RadioButtons($tf, 'False');

    BEGIN_PGML
    1. The enzyme activity increases with temperature. [_]{$rb1}

    2. The inhibitor decreases Vmax in competitive inhibition. [_]{$rb2}
    END_PGML

## Common failure and fix


    Broken: parserCheckboxList.pl used for statement checks
    What you will see: widget missing or render failure
    Fix: use RadioButtons or PopUp per statement

## Styling and emphasis

- Use HTML spans to emphasize key words like NOT or ONLY.
- Keep each statement short so students can scan quickly.

## Creating statement banks with YAML

Instead of hand-coding each PGML problem, you can define pools of true
and false statements in a YAML file and use a generator script to
produce multiple-choice questions automatically. Each generated question
presents one correct answer among several distractors drawn from the
bank.

### YAML file structure

Each YAML file requires three top-level keys:

  Key                  Required   Description
  -------------------- ---------- ----------------------------------------------------------------
  `topic`              Yes        Short phrase used in the question stem (e.g., `DNA structure`)
  `true_statements`    Yes        Mapping of statement IDs to correct statement text
  `false_statements`   Yes        Mapping of statement IDs to incorrect statement text

### Common optional keys

  Key                         Description
  --------------------------- ---------------------------------------------------------------------------------------------------
  `connection_words`          YAML list of stem connectors (defaults to built-in words like `concerning`, `about`, `regarding`)
  `replacement_rules`         Mapping of literal substring replacements for consistent formatting or color
  `override_question_true`    Replace the TRUE stem with custom text, or set to `~` to disable TRUE questions
  `override_question_false`   Replace the FALSE stem with custom text, or set to `~` to disable FALSE questions

In YAML, `~` means null (like Python `None`). For `connection_words`,
null means \"use the built-in defaults.\" For override keys, null means
\"disable that question form entirely.\"

### Statement IDs and conflict groups

Statement IDs follow the pattern `truth<N>a`, `truth<N>b`, `false<N>a`,
`false<N>b`, and so on. Statements that share the same number represent
the **same concept with different phrasing**. The generator
automatically prevents variants of the same concept from appearing
together in one question.


    true_statements:
      truth3a: Enzymes lower activation energy.
      truth3b: Enzymes speed reactions by lowering activation energy.

Because `truth3a` and `truth3b` share the number 3, they will never both
appear as choices in the same generated question. This lets you author
multiple equivalent phrasings for the same idea without creating
confusing near-duplicate answer choices.

### Replacement rules for formatting consistency

The `replacement_rules` key is a simple search-and-replace table applied
to all question text and choices. It is commonly used for:

- Highlighting key terms with HTML color spans
- Consistent symbols and typography (e.g., `&Delta;G`, `&nbsp;`)

<!-- -->


    replacement_rules:
      cAMP: "<strong>cAMP</strong>"
      cGMP: "<strong>cGMP</strong>"

## Generating PGML files from YAML

The `yaml_mc_statements_to_pgml.py` script reads the same YAML schema
described above and generates WeBWorK PGML problem files. This workflow
uses the same statement bank format, so you can maintain one YAML file
and produce both Blackboard export files and PGML problems from it.


    source source_me.sh
    python3 yaml_mc_statements_to_pgml.py -y your_set.yml -x 20

The `-x` flag controls how many question variants to generate. By
default, the generator creates both \"Which statement is TRUE?\" and
\"Which statement is FALSE?\" forms. You can disable either form with
`--no-true` or `--no-false`.

## Second messenger signaling example (complete YAML)


    ---
    topic: second messenger signaling
    learning_objective: Distinguish cAMP vs cGMP roles and enzymes that regulate them.

    replacement_rules:
      cAMP: "<strong>cAMP</strong>"
      cGMP: "<strong>cGMP</strong>"

    true_statements:
      truth1a: cAMP is a second messenger made from ATP
      truth1b: cyclic AMP (cAMP) is produced from ATP by adenylyl cyclase
      truth2: phosphodiesterase breaks down cyclic nucleotides to terminate a signal
      truth3: Protein kinase A (PKA) is activated by cAMP

    false_statements:
      false1a: cAMP is a second messenger made from glucose
      false1b: cyclic AMP (cAMP) is produced from ADP by phosphodiesterase
      false2: phosphodiesterase makes cAMP from ATP
      false3: Protein kinase A (PKA) is activated by cGMP

Note the conflict groups: `truth1a` and `truth1b` both describe how cAMP
is made, so they share number 1 and will not appear together. The same
applies to `false1a` and `false1b`.

## What makes a good false statement

False statements should be \"plausible but wrong\" in a way that
diagnoses a specific misconception. Good patterns include:

- **Wrong substrate or reactant:** ATP vs GTP, NADH vs NADPH
- **Wrong directionality:** influx vs efflux, synthesis vs degradation
- **Wrong cellular location:** nucleus vs cytosol vs mitochondrion
- **Swapped cofactors or ions:** Mg2+ vs Ca2+
- **Wrong sign or relationship:** reversed thermodynamic logic using
  delta-G or equilibrium

Practical trick: write the true statement first, then create the false
version by changing exactly one detail.

## Avoiding accidental cues

Three quick checks that prevent students from using test-taking
strategies instead of content knowledge:

- **Similar length:** Do not let one statement be noticeably longer or
  shorter than the others.
- **Parallel grammar:** Use the same sentence structure across all
  choices (all noun phrases, or all full sentences).
- **No unique keywords:** Avoid terms that appear in only one choice, as
  they can give away the answer.

Additional statement hygiene: one main idea per statement (avoid \"and
also\...\" bundles), use concrete biology verbs (binds, phosphorylates,
opens, inhibits), avoid double negatives, and define abbreviations on
first use.

## Difficulty control

You can adjust question difficulty by varying how the false statements
are constructed:

  Difficulty   Strategy
  ------------ ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Easier       Use direct definitions and unique vocabulary. Keep false statements clearly wrong with one obvious error.
  Harder       Make false statements \"plausible but wrong\" using common misconceptions. Use more similar terms across choices, relying on conflict groups to avoid near-duplicates in the same question.

## Quality checks for statement banks

Before using a bank in an assessment, run through this checklist:

- **Misfiled statements:** Confirm all `truth*` entries are under
  `true_statements` and all `false*` entries are under
  `false_statements`.
- **ID collisions:** Do not reuse the same ID for two unrelated meanings
  (e.g., two different `truth5a` ideas).
- **Duplicate text:** The generator fails if the exact same sentence
  appears twice, even across true and false sections.
- **Replacement rule overlap:** Use specific, non-overlapping phrases to
  avoid nested spans or partial matches.
- **Grammar scan:** Fix typos and subject/verb agreement. Correct
  grammar improves student trust even when the biology is right.

## Biology examples to model

- Experimental design statements (controls, variables, replication).
- Pathway regulation claims (activation vs repression).

## Complete working example

**Enzyme true/false statements** \-- A full problem with per-statement
RadioButtons evaluating claims about enzyme behavior.


    ## TITLE('Enzyme behavior true or false')
    ## DESCRIPTION
    ## Evaluate true/false statements about enzyme regulation
    ## and kinetics using per-statement RadioButtons.
    ## ENDDESCRIPTION
    ## KEYWORDS('enzymes','true false','RadioButtons','kinetics')
    ## DBsubject('Biochemistry')
    ## DBchapter('Enzymes')
    ## DBsection('Regulation')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    $tf = [ 'True', 'False' ];
    $rb1 = RadioButtons($tf, 'True');
    $rb2 = RadioButtons($tf, 'False');
    $rb3 = RadioButtons($tf, 'True');
    $rb4 = RadioButtons($tf, 'False');

    BEGIN_PGML
    For each statement about enzymes, select True or False.

    1. Enzymes increase the rate of a reaction without being consumed. [_]{$rb1}

    2. A competitive inhibitor decreases the Vmax of an enzyme. [_]{$rb2}

    3. Allosteric regulation involves binding at a site other than the active site. [_]{$rb3}

    4. Increasing temperature always increases enzyme activity. [_]{$rb4}
    END_PGML

    ENDDOCUMENT();

## Apply it today

- Use one RadioButtons object per statement and keep answer keys
  aligned.
- Avoid checkbox macros not available in the PG 2.17 subset.
- Create YAML statement banks with 8 to 20 items per truth category for
  good question variety.
- Use conflict group IDs (e.g., `truth4a`, `truth4b`) for equivalent
  phrasings of the same concept.
- Write the true statement first, then create the false version by
  changing one detail.
- Run the quality checklist before deploying a bank to an assessment.

---

# 06_Advanced_PGML_Techniques/6.7-Rendering_Chemical_Structures_with_RDKit

This page explains how to render publication-quality chemical structures
in WeBWorK problems using RDKit.js and SMILES strings. Students see
interactive, consistent molecular drawings without any image files to
manage.

**Use this page when:** you want to display chemical structures such as
amino acids, nucleotides, or peptides in a PGML problem. RDKit.js is
loaded via `HEADER_TEXT` (see [Section 2.5](/@go/page/488659) for macro
loading conventions). For common RDKit rendering errors, see [Section
7.2](/@go/page/555733).

## Why RDKit.js instead of static images

- High-quality, consistent rendering across all molecules and devices.
- No image file management or hosting required.
- SMILES strings are compact and easy to maintain in PG code.
- Customizable rendering options (explicit hydrogens, stereochemistry
  labels, legends).
- Students cannot reverse-image-search for answers.

RDKit.js loads from a public CDN and runs entirely in the browser. It
requires an internet connection and a modern browser with JavaScript
enabled.

## Quick start pattern

Every RDKit problem follows three steps: define a SMILES string, create
an HTML canvas element, and load RDKit.js through `HEADER_TEXT`. Below
is a minimal working example that displays L-alanine.

### Step 1: Define SMILES and create a canvas


    # ----------------------------
    # 2) Setup
    # ----------------------------

    # SMILES for L-alanine (zwitterion at physiological pH)
    $smiles_alanine = 'C[C@@H](C(=O)[O-])[NH3+]';

    # Build the canvas element with a unique id
    $canvas_alanine = '<canvas id="canvas_alanine" width="320" height="240"'
        . ' data-smiles="' . $smiles_alanine . '"></canvas>';

### Step 2: Load RDKit.js in HEADER_TEXT

Place this block after `loadMacros` but before `BEGIN_PGML`. The
JavaScript finds every canvas that has a `data-smiles` attribute and
draws the corresponding molecule.


    HEADER_TEXT(<<'END_HEADER');
    <script src="https://unpkg.com/@rdkit/rdkit/dist/RDKit_minimal.js"></script>
    <script>
    let RDKitReady = null;
    function getRDKit() {
        if (!RDKitReady) {
            RDKitReady = initRDKitModule();
        }
        return RDKitReady;
    }
    function initMoleculeCanvases() {
        getRDKit().then(function(RDKit) {
            const canvases = document.querySelectorAll('canvas[data-smiles]');
            canvases.forEach((canvas) => {
                const smiles = canvas.dataset.smiles;
                if (!smiles) { return; }
                const mol = RDKit.get_mol(smiles);
                const mdetails = {
                    "legend": "",
                    "explicitMethyl": true
                };
                if (canvas && mol) {
                    mol.draw_to_canvas_with_highlights(
                        canvas, JSON.stringify(mdetails)
                    );
                    mol.delete();
                }
            });
        }).catch(error => {
            console.error('Error initializing RDKit:', error);
        });
    }
    if (document.readyState === 'loading') {
        document.addEventListener('DOMContentLoaded', initMoleculeCanvases);
    } else {
        initMoleculeCanvases();
    }
    </script>
    END_HEADER

### Step 3: Display the canvas in PGML


    BEGIN_PGML
    **Identify this amino acid:**

    [$canvas_alanine]*

    [_]{$answer}
    END_PGML

The `*` after the closing bracket tells PGML not to escape the HTML, so
the browser sees a real `<canvas>` element instead of literal tags.

## SMILES basics

SMILES (Simplified Molecular Input Line Entry System) is a compact text
notation for chemical structures. If you have never used SMILES before,
the rules below are all you need for biochemistry problems.

### Atoms and bonds

  -----------------------------------------------------------------------
  Feature         Syntax                     Example
  --------------- -------------------------- ----------------------------
  Standard atoms  Uppercase letters: C, N,   `CCO` (ethanol)
                  O, S, P                    

  Single bond     Implicit (omitted between  `CC` (ethane)
                  atoms)                     

  Double bond     `=`                        `C=O` (formaldehyde core)

  Triple bond     `#`                        `C#N` (cyanide)

  Branches        Parentheses `(...)` for    `CC(=O)O` (acetic acid)
                  side chains                

  Rings           Matching digits to close a `C1CCCCC1` (cyclohexane)
                  ring                       

  Aromatic atoms  Lowercase letters          `c1ccccc1` (benzene)
  -----------------------------------------------------------------------

### Stereochemistry

Many biological molecules are chiral. SMILES encodes chirality at
tetrahedral centers with `[C@@H]` and `[C@H]`, and double-bond geometry
with `/` and `\`. For amino acids, the L-form typically uses `[C@@H]`.


    # L-Alanine breakdown:
    #   C          methyl group (CH3)
    #   [C@@H]     chiral center (L-configuration)
    #   (C(=O)[O-])  carboxylate branch
    #   [NH3+]     protonated amino group

    $ala = 'C[C@@H](C(=O)[O-])[NH3+]';

## Charged species (critical for biochemistry)

Most biological molecules carry formal charges at physiological pH.
SMILES uses square brackets `[...]` for atoms with formal charges,
explicit hydrogens, or non-default valence. Getting charges right is the
single most common source of errors in biochemistry SMILES.

### Common ionizable groups

  -------------------------------------------------------------------------------------------
  Group         Neutral form     Charged form       SMILES (neutral)   SMILES (charged)
  ------------- ---------------- ------------------ ------------------ ----------------------
  Carboxylic    COOH             COO-               `C(=O)O`           `C(=O)[O-]`
  acid                                                                 

  Amino group   NH2              NH3+               `N`                `[NH3+]`

  Imidazole     NH + N           NH + NH+           `C1=CN=C([NH]1)`   `C1=C([NH]C=[NH+]1)`
  (His)                                                                

  Guanidinium   C(=NH)(NH2)NH2   C(=NH2+)(NH2)NH2   `C(=N)(N)N`        `C(=[NH2+])(N)N`
  (Arg)                                                                

  Thiol (Cys)   SH               S-                 `S`                `[S-]`

  Phenol (Tyr)  OH               O-                 `O`                `[O-]`
  -------------------------------------------------------------------------------------------

### Critical note: imidazole protonation

The imidazole ring on histidine is the most common source of SMILES
errors. The protonated form has **one hydrogen on each nitrogen** (NH +
NH+), not two hydrogens on one nitrogen. Using `[NH2+]` is incorrect for
imidazole because that implies two hydrogens on a single nitrogen.


    # CORRECT: protonated histidine (pH below 6)
    # Imidazole ring has NH and NH+ (one H on each nitrogen)
    $his_protonated = 'C1=C([NH]C=[NH+]1)C[C@@H](C(=O)[O-])[NH3+]';

    # CORRECT: neutral histidine (pH above 6)
    # Imidazole ring has NH and N (hydrogen on only one nitrogen)
    $his_neutral = 'C1=CN=C([NH]1)C[C@@H](C(=O)[O-])[NH3+]';

    # WRONG: do not use NH2+ for protonated imidazole
    # $his_wrong = 'C1=C(N=C[NH2+]1)...';

## Validating SMILES strings

Always validate every SMILES string before using it in a problem. An
invalid SMILES will silently produce an empty canvas. Three methods are
available, listed from most to least reliable.

### Method 1: Python RDKit (recommended)


    from rdkit import Chem

    smiles = "C[C@@H](C(=O)[O-])[NH3+]"
    mol = Chem.MolFromSmiles(smiles)

    if mol is None:
        print("ERROR: Invalid SMILES!")
    else:
        print(f"Valid SMILES")
        print(f"Formula: {Chem.rdMolDescriptors.CalcMolFormula(mol)}")
        print(f"Charge: {Chem.GetFormalCharge(mol)}")

### Method 2: Online SMILES viewers

Paste a SMILES string into the PubChem Sketcher
(`https://pubchem.ncbi.nlm.nih.gov/edit3/index.html`) or any other
online SMILES viewer to see the rendered structure immediately.

### Method 3: Test render in WeBWorK

Use the local renderer to preview the problem and confirm that the
canvas draws the expected molecule.

## Canvas sizing guidelines

The canvas dimensions control how large the structure appears. Choose a
size based on molecule complexity.

  -----------------------------------------------------------------------
  Use case          Width x Height    Aspect ratio      Examples
  ----------------- ----------------- ----------------- -----------------
  Standard molecule 320 x 240         4:3               Single amino
                                                        acids,
                                                        monosaccharides

  Large molecule    480 x 320         3:2               Dipeptides,
                                                        nucleotides,
                                                        fatty acids

  Very large        640 x 480         4:3               Tripeptides,
  molecule                                              complex lipids

  Compact (grid     240 x 180         4:3               Side-by-side
  display)                                              comparisons
  -----------------------------------------------------------------------

## Rendering options (mdetails)

The `mdetails` object in the JavaScript controls how RDKit draws each
molecule. Adjust these settings inside the `HEADER_TEXT` block.

### Production settings (for students)


    const mdetails = {
        "legend": "",
        "explicitMethyl": true
    };

### Debug settings (for development)


    const mdetails = {
        "legend": "Debug view",
        "explicitMethyl": true,
        "addAtomIndices": true,
        "addBondIndices": true,
        "addStereoAnnotation": true
    };

  --------------------------------------------------------------------------
  Option                  Effect                              Default
  ----------------------- ----------------------------------- --------------
  `legend`                Text label drawn below the          `""`
                          molecule.                           

  `explicitMethyl`        Shows CH3 groups as text rather     `true`
                          than a bare vertex.                 

  `addAtomIndices`        Numbers each atom (useful for       `false`
                          debugging).                         

  `addBondIndices`        Numbers each bond (useful for       `false`
                          debugging).                         

  `addStereoAnnotation`   Draws R/S and E/Z labels on         `false`
                          stereocenters.                      
  --------------------------------------------------------------------------

## Multiple molecules in one problem

### Pattern 1: Sequential display

Create a separate canvas for each molecule. Each canvas must have a
unique `id`.


    $smiles_ala = 'C[C@@H](C(=O)[O-])[NH3+]';
    $smiles_gly = 'C(C(=O)[O-])[NH3+]';

    $canvas_ala = '<canvas id="canvas_ala" width="320" height="240"'
        . ' data-smiles="' . $smiles_ala . '"></canvas>';
    $canvas_gly = '<canvas id="canvas_gly" width="320" height="240"'
        . ' data-smiles="' . $smiles_gly . '"></canvas>';

    BEGIN_PGML
    **Molecule A:**
    [$canvas_ala]*

    **Molecule B:**
    [$canvas_gly]*

    Which molecule is glycine? [_]{$answer}
    END_PGML

### Pattern 2: Side-by-side with HTML wrapper

Wrap multiple canvases in a flex container to display them in a row.


    $side_by_side = '<div style="display: flex; gap: 1em;">'
        . '<div>' . $canvas_ala . '<p>Molecule A</p></div>'
        . '<div>' . $canvas_gly . '<p>Molecule B</p></div>'
        . '</div>';

    BEGIN_PGML
    Compare these molecules:

    [$side_by_side]*

    Which is glycine? [_]{$answer}
    END_PGML

## Randomization with RDKit

Use a Perl hash to map molecule names to SMILES strings, then randomly
select one. Always sort the hash keys before random selection so the
same problem seed produces the same molecule.


    %amino_acids = (
        'alanine' => 'C[C@@H](C(=O)[O-])[NH3+]',
        'glycine' => 'C(C(=O)[O-])[NH3+]',
        'serine'  => 'C([C@@H](C(=O)[O-])[NH3+])O',
    );

    # Sort keys before random selection for seed stability
    @aa_names = sort keys %amino_acids;
    $selected_name = list_random(@aa_names);
    $selected_smiles = $amino_acids{$selected_name};

    $canvas = '<canvas id="canvas_aa" width="320" height="240"'
        . ' data-smiles="' . $selected_smiles . '"></canvas>';

    BEGIN_PGML
    Identify this amino acid:

    [$canvas]*

    [_]{$selected_name}
    END_PGML

**Why sort the keys?** Perl hashes have no guaranteed ordering. Without
sorting, the same seed could map to different molecules on different
runs or different servers, making grades unreproducible.

## Common pitfalls

### 1. Incorrect formal charges


    # WRONG: missing brackets around charged atom
    $smiles = 'CC(C(=O)O)NH3+';

    # RIGHT: square brackets enclose charged atoms
    $smiles = 'CC(C(=O)O)[NH3+]';

### 2. Imidazole protonation errors


    # WRONG: NH2+ implies two H on one nitrogen
    $his = 'C1=C(N=C[NH2+]1)...';

    # RIGHT: NH and NH+ (one H on each nitrogen)
    $his = 'C1=C([NH]C=[NH+]1)...';

### 3. Quote escaping in canvas attributes


    # WRONG: nested double quotes break the HTML attribute
    $canvas = "<canvas data-smiles=\"$smiles\"></canvas>";

    # RIGHT: use single-quoted string with dot concatenation
    $canvas = '<canvas data-smiles="' . $smiles . '"></canvas>';

### 4. Canvas ID collisions


    # WRONG: duplicate IDs cause only one molecule to render
    $canvas1 = '<canvas id="canvas" ...></canvas>';
    $canvas2 = '<canvas id="canvas" ...></canvas>';

    # RIGHT: every canvas gets a unique ID
    $canvas1 = '<canvas id="canvas_mol1" ...></canvas>';
    $canvas2 = '<canvas id="canvas_mol2" ...></canvas>';

### 5. Missing asterisk in PGML


    # WRONG: PGML escapes the HTML tags
    [$canvas]

    # RIGHT: the * tells PGML to output raw HTML
    [$canvas]*

## Chemistry-specific guidelines

### Amino acids

At physiological pH (around 7.4), amino acids exist as zwitterions with
a protonated amino group (`[NH3+]`) and a deprotonated carboxylate
(`C(=O)[O-]`). Side chains may carry additional charges depending on
their pKa.


    # L-Alanine (simple zwitterion)
    $ala = 'C[C@@H](C(=O)[O-])[NH3+]';

    # L-Lysine (charged side chain: extra NH3+)
    $lys = 'C(CC[NH3+])[C@@H](C(=O)[O-])[NH3+]';

    # L-Aspartate (charged side chain: extra COO-)
    $asp = 'C([C@@H](C(=O)[O-])[NH3+])C(=O)[O-]';

    # L-Histidine (protonated imidazole side chain)
    $his = 'C1=C([NH]C=[NH+]1)C[C@@H](C(=O)[O-])[NH3+]';

### Nucleotides and nucleobases


    # Adenine (neutral nucleobase)
    $adenine = 'C1=NC(=C2C(=N1)N=CN2)N';

    # Cytosine (neutral nucleobase)
    $cytosine = 'C1=CN(C(=O)N=C1N)C';

### Peptides


    # Dipeptide: Gly-Ala (peptide bond connects the two residues)
    $gly_ala = 'C[C@@H](C(=O)O)NC(=O)CN';

Use a larger canvas (480 x 320 or larger) for peptides because the
extended backbone needs more horizontal space.

## Troubleshooting

### Canvas shows an empty box

- RDKit.js may not have loaded. Open the browser console and look for
  network errors.
- Confirm that the WeBWorK server allows loading external scripts from
  the CDN.
- Verify that `HEADER_TEXT` appears after `loadMacros` and before
  `BEGIN_PGML`.

### Console shows \"Error initializing RDKit\"

- The SMILES string is probably invalid. Validate it with Python RDKit
  first.
- Check that the `data-smiles` attribute is properly quoted (no nested
  double quotes).
- Confirm that every canvas has a unique `id`.

### Molecule renders but looks wrong

- Check stereochemistry: `[C@@H]` vs `[C@H]` changes the 3D arrangement.
- Check formal charges: `[NH3+]` vs `N` changes protonation.
- Check explicit hydrogens on charged atoms: `[NH+]` vs `[N+]`.
- Check ring closures: mismatched numbers produce the wrong ring system.

## Best practices checklist

- Validate all SMILES with Python RDKit or an online viewer before
  publishing.
- Use correct formal charges, especially `[NH3+]`, `[O-]`, and `[NH+]`.
- Give every canvas a unique `id`.
- Choose canvas dimensions appropriate for the molecule complexity.
- Sort hash keys before random selection for seed stability.
- Use `[$variable]*` (with the asterisk) in PGML for HTML variables.
- Test the rendered output in a browser before assigning to students.
- Use production `mdetails` settings for student-facing problems.

## Complete working example

**Amino acid identification with RDKit** \-- A full problem that renders
an amino acid structure using RDKit.js and asks students to identify it
with RadioButtons.


    ## TITLE('Identify an amino acid from its structure')
    ## DESCRIPTION
    ## A chemical structure is rendered using RDKit.js. Students
    ## identify the amino acid from its structure.
    ## ENDDESCRIPTION
    ## KEYWORDS('amino acids','RDKit','chemical structure','RadioButtons')
    ## DBsubject('Biochemistry')
    ## DBchapter('Amino Acids')
    ## DBsection('Structure')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    HEADER_TEXT(<<'END_HEADER');
    <script src="https://unpkg.com/@rdkit/rdkit/dist/RDKit_minimal.js"></script>
    <script>
    let RDKitReady = null;
    function getRDKit() {
        if (!RDKitReady) { RDKitReady = initRDKitModule(); }
        return RDKitReady;
    }
    function initMoleculeCanvases() {
        getRDKit().then(function(RDKit) {
            const canvases = document.querySelectorAll('canvas[data-smiles]');
            canvases.forEach((canvas) => {
                const smiles = canvas.dataset.smiles;
                if (!smiles) { return; }
                const mol = RDKit.get_mol(smiles);
                const mdetails = {"legend": "", "explicitMethyl": true};
                if (canvas && mol) {
                    mol.draw_to_canvas_with_highlights(
                        canvas, JSON.stringify(mdetails));
                    mol.delete();
                }
            });
        }).catch(error => {
            console.error('Error initializing RDKit:', error);
        });
    }
    if (document.readyState === 'loading') {
        document.addEventListener('DOMContentLoaded', initMoleculeCanvases);
    } else {
        initMoleculeCanvases();
    }
    </script>
    END_HEADER

    $smiles = 'C[C@@H](C(=O)[O-])[NH3+]';
    $canvas = '<canvas id="canvas_aa" width="320" height="240"'
        . ' data-smiles="' . $smiles . '"></canvas>';

    $rb = RadioButtons(
        [ 'Alanine', 'Glycine', 'Valine', 'Serine' ],
        'Alanine',
        labels        => 'ABC',
        displayLabels => 1,
    );

    BEGIN_PGML
    Identify the amino acid shown below.

    [$canvas]*

    [_]{$rb}
    END_PGML

    ENDDOCUMENT();

## Apply it today

- Copy the quick start pattern above into a new PG file and replace the
  SMILES string with your target molecule.
- Validate the SMILES, set the canvas size, and preview in a browser.
- For problems that compare multiple structures, give each canvas a
  unique ID and consider side-by-side layout.

---

# 06_Advanced_PGML_Techniques/6.8-Displaying_Chemical_Formulas_with_mhchem

This page explains how to display chemical formulas and reaction
equations in WeBWorK problems using the mhchem extension for MathJax.
Students see properly typeset formulas such as \\( \\ce{H2O} \\) and
balanced equations without any image files or external libraries.

**Use this page when:** you need to display chemical formulas, ions, or
reaction equations in a PGML problem. The `\ce{}` command is part of the
mhchem package, which is loaded automatically by MathJax in WeBWorK. For
rendering graphical molecular structures from SMILES strings, see
[Section 6.7](/@go/page/555729) instead.

## Background on displaying chemical formulas

MathJax includes the mhchem extension, which provides the `\ce{}`
command for typesetting chemical formulas and equations. This is the
same syntax used in LaTeX chemistry documents and on LibreTexts pages.
Because MathJax is already loaded in WeBWorK, no additional macros or
JavaScript are required.

Use `\ce{}` whenever you need chemical notation in a problem. It handles
subscripts, superscripts, charges, reaction arrows, and stoichiometric
coefficients automatically, producing cleaner output than manually
formatting with standard math mode.

## Displaying chemical formulas

### Inline formulas

Wrap `\ce{}` inside `\( ... \)` to display a formula inline with the
surrounding text.


    The molecular formula for glucose is \( \ce{C6H12O6} \).

This renders as: The molecular formula for glucose is \\( \\ce{C6H12O6}
\\).

### Display-mode equations

Wrap `\ce{}` inside `\[ ... \]` (or use PGML double-backtick ``` `` ```)
to display an equation on its own centered line.


    [``\ce{C6H12O6 + 6 O2 -> 6 CO2 + 6 H2O}``]

This renders as:

\\\[ \\ce{C6H12O6 + 6 O2 -\> 6 CO2 + 6 H2O} \\nonumber \\\]

### Common mhchem syntax

  --------------------------------------------------------------------------
  Feature               Syntax                      Renders as
  --------------------- --------------------------- ------------------------
  Molecular formula     `\ce{H2SO4}`                \\( \\ce{H2SO4} \\)

  Ionic charge          `\ce{SO4^2-}`               \\( \\ce{SO4\^2-} \\)

  Reaction arrow        `\ce{A -> B}`               \\( \\ce{A -\> B} \\)

  Equilibrium arrow     `\ce{A <=> B}`              \\( \\ce{A \<=\> B} \\)

  State symbols         `\ce{NaCl(aq)}`             \\( \\ce{NaCl(aq)} \\)

  Stoichiometric        `\ce{2 H2 + O2 -> 2 H2O}`   \\( \\ce{2 H2 + O2 -\> 2
  coefficients                                      H2O} \\)
  --------------------------------------------------------------------------

### Using \\ce{} inside RadioButtons choices

When chemical formulas appear as answer choices in a RadioButtons
widget, wrap each formula in inline math delimiters `\( \ce{...} \)`.
The radio button will render the formula using MathJax.


    $rb = RadioButtons(
        [ "\( \ce{C6H12O6} \)", "\( \ce{O2} \)", "\( \ce{CO2} \)", "\( \ce{H2O} \)" ],
        "\( \ce{C6H12O6} \)",
    );

## Complete working example

**Cellular respiration with mhchem** \-- A full problem that displays a
balanced chemical equation using `\ce{}` and asks students to identify
the oxidized reactant with RadioButtons.


    ## TITLE('Identify the oxidized reactant in cellular respiration')
    ## DESCRIPTION
    ## A balanced chemical equation is rendered using mhchem. Students
    ## identify which reactant is being oxidized.
    ## ENDDESCRIPTION
    ## KEYWORDS('mhchem','chemical formula','cellular respiration','RadioButtons')
    ## DBsubject('Chemistry')
    ## DBchapter('Chemical Reactions')
    ## DBsection('Oxidation-Reduction')
    ## Date('2026-02-26')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    $rb = RadioButtons(
        [ "\( \ce{C6H12O6} \)", "\( \ce{O2} \)", "\( \ce{CO2} \)", "\( \ce{H2O} \)" ],
        "\( \ce{C6H12O6} \)",
        labels        => "ABC",
        displayLabels => 1,
        separator     => '<div style="margin-bottom: 0.7em;"></div>',
        uncheckable   => 1,
        randomize     => 1,
    );

    BEGIN_PGML
    In the following chemical reaction for cellular respiration, which reactant is being oxidized?

    [``\ce{C6H12O6 + 6 O2 -> 6 CO2 + 6 H2O}``]

    [_]{$rb}
    END_PGML

    ENDDOCUMENT();

## Apply it today

- Use `\ce{}` for any chemical formula or equation instead of manually
  formatting subscripts and superscripts in math mode.
- For inline formulas, use `\( \ce{...} \)`. For display equations, use
  PGML double-backtick syntax: ``` [``\ce{...}``] ```.
- For graphical molecular structures (ring systems, stereochemistry),
  use RDKit.js instead (see [Section 6.7](/@go/page/555729)).

---

# 07_Testing_and_Debugging/7.0-Index

This chapter helps you find and fix problems in your WeBWorK questions.
Whether you are setting up local rendering for the first time, debugging
a broken problem, or doing a final check before publishing, start here
to find the right section.

Debugging WeBWorK problems is not fundamentally different from
troubleshooting a lab protocol. You isolate the variable that changed,
reproduce the failure under controlled conditions, and fix one thing at
a time. The tools in this chapter give you a fast feedback loop so you
spend less time guessing and more time writing good questions.

## What just went wrong?

Use this table to jump straight to the section that matches your
symptom. If you are not sure what went wrong, start at the top and work
down.

  What you see                                                            Go to                             What you will find
  ----------------------------------------------------------------------- --------------------------------- ------------------------------------------------------------
  Render fails with an error message                                      [Section 7.2](/@go/page/555733)   Common mistakes organized by symptom with copy-paste fixes
  Widget shows as a plain text box instead of radio buttons or dropdown   [Section 7.2](/@go/page/555733)   Variable scoping rules (the `my` keyword trap)
  HTML tags appear as literal text in the output                          [Section 7.2](/@go/page/555733)   The `[$var]*` rule for HTML variables
  Problem works for one seed but breaks on others                         [Section 7.4](/@go/page/557411)   Randomization testing and guard patterns
  Everything looks fine but want a final checklist                        [Section 7.5](/@go/page/557412)   QA checklist before publishing
  Need to lint or test many files at once                                 [Section 7.6](/@go/page/557409)   Scripting and batch automation
  Setting up local rendering for the first time                           [Section 7.1](/@go/page/555732)   Install, start, and first render walkthrough

## Section map

  Section                                                        What it covers
  -------------------------------------------------------------- --------------------------------------------------------------------------------------------------------------
  [7.1 Setting up and first render](/@go/page/555732)            Install the renderer and confirm it works with your first problem file.
  [7.2 Common mistakes and how to fix them](/@go/page/555733)    The big reference. Symptom-based lookup for PGML parsing, variable scoping, HTML escaping, macros, and more.
  [7.3 Linting your problems](/@go/page/557407)                  Static checks you can eyeball and renderer-based lint that catches issues before students see them.
  [7.4 Testing randomization and edge cases](/@go/page/557411)   Sweep seeds to find broken variants, guard against impossible values.
  [7.5 QA checklist before publishing](/@go/page/557412)         A prevention checklist and author checklist to run before you ship.
  [7.6 Scripting and automation](/@go/page/557409)               API endpoints, Python examples, and batch linting for advanced workflows.

## Start here

- If you are new to local rendering, start with [Section
  7.1](/@go/page/555732). It walks you through installing the renderer
  and confirming your first problem file works.
- If something just broke, go to [Section 7.2](/@go/page/555733). It is
  organized by symptom so you can look up what you see and find a fix
  without reading everything else first.
- If you are about to publish, go to [Section 7.5](/@go/page/557412).
  The QA checklist catches the problems that look fine in author view
  but fail when students encounter them.

## Apply it today

- Use the decision table above to jump directly to the section that
  matches your current situation instead of reading the chapter front to
  back.
- Keep the QA checklist from [Section 7.5](/@go/page/557412) open as a
  tab while you finalize problems for a new assignment.

{{template.ShowOrg()}}

---

# 07_Testing_and_Debugging/7.1-Simple_Syntax_Checking_Linting_in_WeBWork

Use this section when you want to catch mistakes before students see
them. Linting means checking your problem file for common errors, either
by reading through it yourself (static checks) or by running it through
the renderer and inspecting the output. Both approaches catch different
kinds of issues, so use them together.

Think of linting like proofreading a lab protocol. Some errors you can
catch by reading the text carefully. Others only show up when you
actually run the protocol and watch what happens. A good QA pass uses
both strategies: read the code for known pitfalls, then render the
problem and inspect the result in a browser.

## What linting catches that reading misses

- Variables that look correct in source but render wrong because of
  escaping or parsing rules (see [Section 3.1](/@go/page/555703) for
  PGML syntax basics)
- HTML that gets escaped when you wanted it to render as formatted
  content
- PGML syntax that parses differently than you expected (list markers,
  bold, eval blocks)
- Missing macros that only fail at render time, not while reading the
  code (see [Section 7.2](/@go/page/555733) for common macro mistakes)
- Layout issues that only appear in a browser (spacing, alignment,
  missing blanks)

## Static checks you can do by eye

These are patterns you can search for in your source file before
rendering. Each one causes a specific failure that is easy to miss in
the code but obvious in the rendered output.

  What to look for                                                                                                         Why it matters                                                           What to do
  ------------------------------------------------------------------------------------------------------------------------ ------------------------------------------------------------------------ --------------------------------------------------------------------------------------------
  PGML tag wrappers inside Perl variables (`"[<"` or `"]{["` in string assignments)                                        PGML parses once. Tags in variables are not re-parsed.                   Move PGML syntax out of variables and into the PGML block directly.
  HTML in variables without `*` (variable contains `<span`, `<div`, etc. but is output as `[$var]` without trailing `*`)   PGML escapes the HTML. You see literal tags instead of formatted text.   Add `*` after the bracket: `[$var]*`
  `MODES(` inside `[@ ... @]` eval blocks                                                                                  MODES returns `1` in eval context, not the HTML string.                  Use `[@ ... @]*` with MODES only for wrapper divs. For simple HTML, use `[$var]*` instead.
  TeX color macros (`\color{` or `\textcolor{`) in PGML                                                                    MathJax does not render these in this install.                           Use HTML `<span>` styles for color instead.
  Blocked HTML tags: `<table`, `<tr`, `<td`, `<th`                                                                         These tags are stripped by the HTML whitelist.                           Use `niceTables.pl` (DataTable or LayoutTable) for any tables.
  Ordered list label patterns: `A.` or `B.` at the start of a line in PGML                                                 PGML may parse these as list markup instead of plain text.               Use `*A.*` (bold) or escape the dot: `A\.`

## Structural checks

These checks confirm that the required scaffolding of a PG file is in
place. Missing any of these causes the renderer to fail or produce
partial output.

  Check                                 What to look for                                               Symptom if missing
  ------------------------------------- -------------------------------------------------------------- -----------------------------------------
  Missing `DOCUMENT();`                 File does not start with `DOCUMENT()` after `loadMacros`       Render fails with a cryptic error
  Missing `ENDDOCUMENT();`              File does not end with `ENDDOCUMENT()`                         Render fails or produces partial output
  Unmatched `BEGIN_PGML` / `END_PGML`   One is present without the other                               Parse error, content not rendered
  Nested `BEGIN_PGML` without closing   Two `BEGIN_PGML` in a row without an `END_PGML` between them   Parse error
  Unbalanced `[@ ... @]` eval blocks    Opening `[@` without closing `@]` or vice versa                PGML parse failure

## Renderer-based lint

Static checks catch many issues, but some problems only surface when the
renderer actually processes the file. Renderer-based lint sends your
file through the same pipeline students will use and reports errors,
warnings, and the final HTML output.

### HTML render is the primary test

WeBWorK questions are designed for browsers, so the rendered HTML is the
most important check. Render your problem, save the output as an HTML
file, and open it in a browser. Check: Does the question text read
clearly? Are all blanks visible? Does the layout look right? Are
interactive widgets (radio buttons, dropdowns) displaying correctly
instead of plain text boxes?

### Using the lint script

The helper script `lint_pg_via_renderer_api.py` wraps the renderer API
for a local file. It sends your PG source to the renderer, collects any
lint messages, and optionally saves the rendered HTML.

To get lint messages only (no HTML output), omit the `-r` flag:


    python3 lint_pg_via_renderer_api.py -i private/myproblem.pg

To generate full HTML output for visual inspection, include the `-r`
flag and redirect the output to a file:


    python3 lint_pg_via_renderer_api.py -i private/myproblem.pg -r > /tmp/pg_render.html

The script prints the seed it uses. You can set a specific seed with
`-s`:


    python3 lint_pg_via_renderer_api.py -i private/myproblem.pg -s 1234 -r > /tmp/pg_render.html

### What to check in the output

- **Render errors:** The renderer reports line numbers and error
  messages. Fix these first, since they usually mean the problem will
  not display at all.
- **Warnings:** Check for PGML parse warnings. These may not prevent
  rendering but can cause unexpected behavior for some students or
  certain seeds.
- **Visual inspection:** Open the HTML in a browser and read it like a
  student. Check that text is formatted correctly, blanks appear where
  expected, and no raw markup is visible.
- **Widget behavior:** Confirm that interactive widgets (radio buttons,
  dropdowns, checkboxes) display as the correct widget type, not as a
  plain text input box.

## A simple lint workflow

Follow these steps in order each time you finish editing a problem. The
whole process takes less than a minute once you are familiar with it.

1.  Save your `.pg` file.
2.  Run the lint script without `-r` to check for errors.
3.  Fix any reported issues.
4.  Run the lint script with `-r` to generate HTML.
5.  Open the HTML file in your browser.
6.  Read the question as a student would.
7.  Check that every answer blank appears and is in the right place.

## Apply it today

Run a lint check on one problem file today. Fix any issues it reports,
then open the HTML in your browser and read the question as if you were
a student seeing it for the first time. If the text is clear, the blanks
are visible, and the layout looks right, your problem is ready for
further testing.

---

# 07_Testing_and_Debugging/7.2-Setting_Up_the_PG_Renderer

Use this section when you are setting up local rendering for the first
time or returning after a break. The goal is to get one problem
rendering in your browser so you have a fast feedback loop for editing
and debugging.

Think of local rendering like setting up a bench assay. Before you run a
full experiment, you confirm that your reagents work, your equipment
reads correctly, and you can reproduce a known result. Here, the reagent
is your `.pg` file, the equipment is the renderer container, and the
known result is a cleanly rendered problem with visible answer blanks.
Once this baseline works, every edit you make is a single-variable
change from a known-good state.

## What you need

- Podman or Docker installed on your machine
- A folder containing your `.pg` files (see [Section
  2.3](/@go/page/488657) for PG file structure)
- A terminal (command prompt) for running commands
- A web browser for viewing rendered problems

## Start the renderer

The renderer runs inside a container. Start it from your terminal with
one of these commands, depending on which container tool you have
installed.

1.  Start the container:

        podman compose up -d

    or

        docker compose up -d

2.  Check that it is running. Open a terminal and run:

        curl http://localhost:3000/health

    You should see `{"status":"ok"}` in the output.

3.  If you see \"connection refused\", the container is not running yet.
    Wait a few seconds and try again. The renderer can take 10 to 30
    seconds to finish starting up.

## What working looks like vs what broken looks like

  What you see                                                                                                                 What it means                                       What to do
  ---------------------------------------------------------------------------------------------------------------------------- --------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------
  The `/health` endpoint returns `{"status":"ok"}`                                                                             The renderer is running and ready.                  Proceed to the browser editor.
  The browser editor at `http://localhost:3000` loads and rendering a simple problem shows formatted text with answer blanks   Everything is working end to end.                   You are ready to start editing problems.
  \"Connection refused\" in the terminal                                                                                       The container is not running.                       Wait a few seconds and try the health check again. If it still fails, check that the container started without errors.
  A blank page or error page in the browser                                                                                    The renderer started but something else is wrong.   Check the container logs for error messages.

## Open the browser editor

1.  Open `http://localhost:3000` in your browser.
2.  Load a `.pg` file from the `private/` folder (see [Section
    4.1](/@go/page/555709) for a full file example).
3.  Set a seed number. Start with something simple like `1234`.
4.  Click Render.

The rendered output should show formatted text, any math expressions,
and answer blanks where students would type or select their answers. If
you see raw PGML markup or error text instead, something needs to be
fixed. [Section 7.2](/@go/page/555733) covers the most common causes.

## Private folder workflow

Place your `.pg` files inside the `private/` folder that is mounted into
the renderer container. The web editor can then load files directly
using the path `private/yourfile.pg`.

Changes you save to files on your computer appear in the container
automatically. There is no separate upload or sync step. Edit the file
in your text editor, save it, then click Render in the browser to see
the updated output.

## The one rule that saves hours

When debugging, write down (1) the file path and (2) the seed. Do not
change either until the failure is fixed. Change one thing at a time.

This is the same principle as a controlled experiment. If you change the
seed and the code at the same time, you cannot tell which change caused
the new behavior. Lock the seed, fix the code, and only move on to
testing other seeds after the current one renders correctly.

## What to record while you work

  Record             Example                                   Why it matters
  ------------------ ----------------------------------------- -----------------------------------------------------------
  File path          `private/enzyme_kinetics.pg`              Keeps your failing case tied to one file.
  Seed               `1234`                                    Locks the random variant for reproducibility.
  What you changed   \"Changed units from mM to micromolar\"   Makes debugging traceable when you need to undo a change.

## Your first render checklist

1.  Start the renderer container.
2.  Check `/health` returns `{"status":"ok"}`.
3.  Open your browser to `http://localhost:3000`.
4.  Load a `.pg` file from `private/`.
5.  Set the seed to `1234`.
6.  Click Render.
7.  Read the output like a student would.
8.  Confirm answer blanks appear where expected.

## HTML render is the primary test

WeBWorK questions are designed for browsers. The rendered HTML page is
the most important test of whether your problem works correctly. Open it
in a browser and check that the question looks right visually: text is
formatted, math displays properly, answer blanks are in the right
places, and interactive widgets (radio buttons, dropdowns) appear as
expected instead of plain text boxes.

Static linting and code review are useful supporting checks, but they
cannot replace the rendered output. A problem that passes every lint
check can still display poorly or confuse students. Always finish by
reading the rendered page as a student would read it.

## Apply it today

- Use local rendering for the tight edit-preview loop: edit your file,
  save, click Render, and check the output. This cycle should take
  seconds, not minutes.
- Once the local render looks right, use ADAPT for the final publish
  workflow. Local rendering confirms the code works; ADAPT confirms the
  assignment context and student view.

---

# 07_Testing_and_Debugging/7.3-Scripting_and_Automation_of_the_PG_Renderer

Use this section when you need to render or lint problems
programmatically rather than through the browser editor. This covers the
renderer API endpoints, scripting examples, and batch linting workflows.
This section is for advanced users who are comfortable with command-line
tools and scripting. The examples below assume the renderer is already
running on `http://localhost:3000` (see [Section 7.1](/@go/page/555732)
for setup).

## API endpoints

The renderer exposes three HTTP endpoints. Use the primary endpoint for
all new scripts.

  Endpoint        Method   Use for
  --------------- -------- ----------------------------------------------------------------------
  `/`             POST     Primary endpoint for rendering problems (preferred for all new work)
  `/render-api`   POST     Legacy compatibility endpoint (same behavior as `/`)
  `/health`       GET      Check if the renderer is running and accepting requests

## Parameter precedence

The renderer accepts three input types for specifying problem source. If
you provide more than one, the renderer uses the highest-precedence
source and ignores the rest.

**Precedence order:** `problemSourceURL` (highest) \> `problemSource`
(middle) \> `sourceFilePath` (lowest)

  Parameter            What it is                                                            Use when
  -------------------- --------------------------------------------------------------------- ----------------------------------------------------------------------------------
  `problemSourceURL`   URL to a JSON endpoint that returns problem source                    Problem source lives on a remote server
  `problemSource`      Raw PG source as a string                                             Source is generated by a script or read from a file (most common for automation)
  `sourceFilePath`     Path relative to the renderer\'s `private/` or `Library/` directory   File exists inside the renderer container

## Curl example

The simplest way to test the renderer from the command line is a
form-encoded POST with `curl`:


    curl -X POST "http://localhost:3000/" \
      -F "sourceFilePath=private/myproblem.pg" \
      -F "problemSeed=1234" \
      -F "_format=json"

- `sourceFilePath` \-- path relative to the renderer\'s directory
  structure.
- `problemSeed` \-- integer seed for randomization. Use a fixed seed so
  failures are reproducible.
- `_format=json` \-- returns structured JSON instead of HTML. Always use
  this for scripted workflows.

If the file is on your host machine but not mounted into the container,
read it in your script and send it as `problemSource` instead.

## Python example

This function reads a local `.pg` file, sends it to the renderer, and
reports problems:


    import requests

    def render_pg_file(filepath, seed=1234):
        with open(filepath, 'r') as f:
            pg_source = f.read()
        response = requests.post(
            'http://localhost:3000/',
            json={
                'problemSource': pg_source,
                'problemSeed': seed,
                '_format': 'json',
            }
        )
        data = response.json()
        error_flag = data.get('flags', {}).get('error_flag', 0)
        warnings = data.get('debug', {}).get('pg_warn', [])
        if error_flag:
            print(f'Error rendering {filepath}')
        elif warnings:
            print(f'Warnings for {filepath}:')
            for w in warnings:
                print(f'  {w}')
        else:
            print(f'{filepath}: OK')
        return data

Call `render_pg_file('problems/my_problem.pg')` to test a single file.
The function returns the full JSON response so you can inspect
`renderedHTML`, `answers`, or other fields as needed.

## Batch linting

To lint all `.pg` files in a directory tree, walk the directory and
render each file:


    import os

    failed = []
    for root, dirs, files in os.walk('problems/'):
        for f in files:
            if f.endswith('.pg'):
                path = os.path.join(root, f)
                data = render_pg_file(path)
                if data.get('flags', {}).get('error_flag'):
                    failed.append(path)

    if failed:
        print(f'{len(failed)} files failed')
    else:
        print('All files passed')

Use a fixed seed so that any failure you find is reproducible.

## Response format

When `_format=json` is set, the renderer returns a structured JSON
object. Key fields:

  Field                Type     Description
  -------------------- -------- --------------------------------------------------------
  `renderedHTML`       string   The rendered problem HTML (student view)
  `flags.error_flag`   int      0 = success, 1 = rendering error
  `debug.pg_warn`      array    Warning messages from the renderer
  `answers`            object   (Instructor mode) Answer structure with correct values

## Checking for success

A clean render has `error_flag == 0` and an empty `pg_warn` array.
Always check both, because a problem can render without a fatal error
but still produce warnings:


    error_flag = data.get('flags', {}).get('error_flag', 0)
    warnings = data.get('debug', {}).get('pg_warn', [])

    if error_flag:
        print('Rendering failed completely')
    elif warnings:
        print('Rendered with warnings:')
        for w in warnings:
            print(f'  - {w}')
    else:
        print('Clean render, no issues')

## Apply it today

- Start with the curl example above to verify your renderer is
  responding.
- Adapt the Python `render_pg_file` function for your own workflow.
- Use the batch linting pattern to check an entire directory of problems
  before publishing.
- Always set `_format=json` and check both `flags.error_flag` and
  `debug.pg_warn` in scripted workflows.

---

# 07_Testing_and_Debugging/7.4-Common_Mistakes_and_How_to_Fix_Them

Use this section when something is wrong with your WeBWorK problem and
you need to find and fix it. The mistakes below are organized by what
you see (the symptom), what caused it, and exactly how to fix it. Every
fix includes code you can copy and paste.

These are the most common mistakes made by problem authors, collected
from real debugging sessions. If your problem is not working, there is a
good chance the answer is on this page.

## PGML parsing errors

PGML uses asterisks and other punctuation as formatting markers (see
[Chapter 3](/@go/page/488660) for full PGML syntax). When these markers
appear near variables, the parser can misinterpret them and produce
confusing errors.

### Asterisks around variables

**Symptom:** `'*' was not closed before paragraph ends`

**Cause:** PGML interprets `*` as the start of italic text. When you
wrap a variable in single asterisks, PGML tries to treat everything
between them as italic content. If the variable expands to something
unexpected, the italic block never closes.

**Wrong:**


    BEGIN_PGML
    The answer is *[$variable]*.
    END_PGML

**Right (option 1 \-- use bold instead of italic):**


    BEGIN_PGML
    The answer is **[$variable]**.
    END_PGML

**Right (option 2 \-- remove the emphasis):**


    BEGIN_PGML
    The answer is [$variable].
    END_PGML

**Right (option 3 \-- build emphasis in a variable):**


    $answer_emph = "<em>$variable</em>";

    BEGIN_PGML
    The answer is [$answer_emph]*.
    END_PGML

Option 3 moves the emphasis into an HTML variable and uses `[$var]*` to
pass the HTML through without escaping.

### Bold markers around variables

**Symptom:** `'**' was not closed before paragraph ends`

**Cause:** Bold markers (`**`) break when the variable content contains
characters that PGML interprets as additional formatting.

**Wrong:**


    BEGIN_PGML
    At pH [$selected_ph], histidine exists in **[$correct_label]**.
    END_PGML

**Right (remove the bold):**


    BEGIN_PGML
    At pH [$selected_ph], histidine exists in [$correct_label].
    END_PGML

**Right (build emphasis in a variable):**


    $label_bold = "<strong>$correct_label</strong>";

    BEGIN_PGML
    At pH [$selected_ph], histidine exists in [$label_bold]*.
    END_PGML

### Using \* for bullets when you also have italic content

**Symptom:** Confusing PGML parse behavior. Lines that begin with `*`
and also contain `*italic*` markers cause the parser to misread which
asterisks are bullets and which are emphasis.

**Wrong:**


    BEGIN_PGML
    * *State 1* (pH < 1.82): Description
    * *State 2* (pH > 1.82): Description
    END_PGML

**Right (use dashes for bullets):**


    BEGIN_PGML
    - **State 1** (pH < 1.82): Description
    - **State 2** (pH > 1.82): Description
    END_PGML

## Variable scoping: the number one surprise

This is the single most confusing issue for new PG authors. It looks
like you did everything right, but the widget does not appear.

### The `my` keyword makes variables invisible to PGML

**Symptom:** RadioButtons renders as a plain text input box instead of
radio buttons. Grading fails with
`Answer evaluator was not executed due to errors`.

**Cause:** Writing `my $radio = RadioButtons(...)` creates a lexical
variable that PGML cannot see. Think of it this way: PGML looks up
variables in a shared directory (the package symbol table). The `my`
keyword puts the variable in a private closet that PGML cannot open.
When PGML encounters `[_]{$radio}`, it checks the shared directory,
finds nothing, and falls back to a generic text input.

**Wrong:**


    my $radio = RadioButtons(['Alpha', 'Beta'], 'Alpha');

    BEGIN_PGML
    [_]{$radio}
    END_PGML

**Right:**


    $radio = RadioButtons(['Alpha', 'Beta'], 'Alpha');

    BEGIN_PGML
    [_]{$radio}
    END_PGML

**The rule:** Any variable referenced inside `BEGIN_PGML` (via `[$var]`,
`[_]{$var}`, or `[$var]*`) must NOT use `my`. Using `my` for loop
counters and temporary helpers is fine, as long as those variables never
appear inside a PGML block.


    # OK -- my for intermediates, bare for PGML-visible results
    my $idx = random(0, 3, 1);
    $rb = RadioButtons([@choices], $choices[$idx]);

  Keyword               PGML visible?   Use for
  --------------------- --------------- ---------------------------------------------------------
  `$var = ...` (bare)   Yes             Variables displayed or graded in PGML
  `local $var = ...`    Yes             Temporary override of a package variable inside a block
  `my $var = ...`       No              Helper variables, loop counters, temporary computation

### Why `local` works but `my` does not

Authors who know that `my` is \"more modern\" than `local` sometimes
avoid `local` entirely. In PG, the two keywords have critically
different PGML visibility. `local` temporarily modifies a package
variable, so it stays in the symbol table and PGML can still find it.
`my` creates a lexical variable on the Perl pad stack, which is
invisible to PGML\'s symbol-table lookup. For PG problems, the simplest
approach is to use bare package variables (no `my`, no `local`) for
anything PGML needs to see.

## HTML escaping: the `[$var]*` rule

**Symptom:** HTML tags show as literal text on screen. Instead of
colored or bold text, the student sees raw markup like
`<span style="color:red;">Important</span>`.

**Cause:** PGML escapes HTML by default for safety. Every `<` becomes
`&lt;` so the browser displays tags as text instead of rendering them.

**Wrong:**


    $html_content = '<span style="color:red;">Important</span>';

    BEGIN_PGML
    This is [$html_content] text.
    END_PGML

**Right:**


    $html_content = '<span style="color:red;">Important</span>';

    BEGIN_PGML
    This is [$html_content]* text.
    END_PGML

**The rule:** If a variable contains any HTML tags (`<span>`, `<div>`,
`<strong>`, `<sub>`, etc.), always add `*` after the closing bracket.
The asterisk tells PGML to pass the content through without escaping.

## Missing or wrong macros

PG widgets like RadioButtons and DropDown live in separate macro files
(see [Section 2.5](/@go/page/488659) for macro basics). If you forget
the macro, the widget function is undefined and the renderer crashes.

### Symptom table: missing macro errors

  Widget or feature         Required macro            What happens without it
  ------------------------- ------------------------- ----------------------------
  DropDown / PopUp          `parserPopUp.pl`          Undefined subroutine error
  RadioButtons              `parserRadioButtons.pl`   Undefined subroutine error
  DataTable / LayoutTable   `niceTables.pl`           Undefined subroutine error
  NchooseK                  `PGchoicemacros.pl`       Undefined subroutine error

### How to fix

Check your `loadMacros()` block near the top of the file and add the
missing macro. A correct block that covers common widgets:


    loadMacros(
      'PGstandard.pl',
      'PGML.pl',
      'parserRadioButtons.pl',
      'parserPopUp.pl',
      'niceTables.pl',
      'PGcourse.pl',
    );

### `use` statements are trapped

**Symptom:** `'require' trapped by operation mask`

**Cause:** Perl\'s `use` statement calls `require` internally, and the
PG sandbox blocks it for security. PG problems run on shared servers and
cannot load arbitrary Perl modules.

**Wrong:**


    use POSIX qw(floor);
    use List::Util qw(shuffle);

**Right:** Use `loadMacros()` for PG macros and built-in alternatives
for standard functions.


    # For truncation (instead of POSIX floor)
    $val = int(3.7);              # returns 3

    # For rounding (instead of POSIX round)
    $val = sprintf("%.0f", 3.7);  # returns 4

Other trapped operations include `eval "string"`, `open()`, `system()`,
and backtick execution.

## Blocked HTML tags

**Symptom:** Table content disappears or renders as broken text.

**Cause:** The tags `<table>`, `<tr>`, `<td>`, and `<th>` are blocked by
the HTML whitelist. The renderer strips them out silently.

**Wrong:**


    BEGIN_PGML
    <table>
      <tr><td>Cell 1</td><td>Cell 2</td></tr>
    </table>
    END_PGML

**Right:** Use `niceTables.pl` with `DataTable` or `LayoutTable`.


    loadMacros('niceTables.pl');

    $table = DataTable(
      [['Header 1', 'Header 2'],
       ['Cell 1',   'Cell 2']],
    );

    BEGIN_PGML
    [$table]*
    END_PGML

Note the `*` after `[$table]` because the variable contains HTML.
`niceTables.pl` is the only supported way to create tables in PG
problems.

## MODES misuse

**Symptom:** The number `1` appears on screen where you expected HTML
content.

**Cause:** `MODES(...)` returns `1` in eval context instead of the HTML
string. This happens when `MODES()` is called inside a `[@ ... @]` eval
block in PGML.

**When MODES is needed:** Only when wrapper HTML must be emitted from
inside Perl eval blocks, typically for layout structures like two-column
matching.

**When MODES is NOT needed:** Inline HTML like `<span>`, `<sub>`, and
`<sup>` renders directly without `MODES()`. Store the HTML in a variable
and use `[$var]*` instead.

**Wrong:**


    BEGIN_PGML
    [@ MODES(HTML => '<div>content</div>') @]*
    END_PGML

**Right:**


    $content = '<div>content</div>';

    BEGIN_PGML
    [$content]*
    END_PGML

**TeX color macros do not work.** Commands like `\color{}` and
`\textcolor{}` do not render in this environment. Use HTML `<span>`
elements with inline CSS for colored text instead.

## Order of operations

PG runs your code from top to bottom. If you reference a variable before
it is assigned, it silently becomes an empty string with no warning.

### Using variables before they are defined

**Symptom:** Empty output, missing content, or blank areas in the
rendered problem.

**Wrong:**


    @all_cards = ($card1, $card2, $card3);
    # ... 50 lines later ...
    $card1 = '<div>content 1</div>';
    $card2 = '<div>content 2</div>';
    $card3 = '<div>content 3</div>';

**Right:**


    $card1 = '<div>content 1</div>';
    $card2 = '<div>content 2</div>';
    $card3 = '<div>content 3</div>';
    # ... then use them ...
    @all_cards = ($card1, $card2, $card3);

### Shuffle timing

The correct pattern: (1) define all items, (2) create the array, (3)
shuffle. Never shuffle before the items exist.


    # 1. Define all items first
    $item1 = "content 1";
    $item2 = "content 2";
    $item3 = "content 3";

    # 2. Create array
    @all_items = ($item1, $item2, $item3);

    # 3. Shuffle
    @shuffled = ();
    @temp = @all_items;
    while (@temp) {
      my $i = random(0, $#temp, 1);
      push @shuffled, splice(@temp, $i, 1);
    }

### Hash key order is not deterministic

**Symptom:** Random order changes between runs even with the same seed.

**Cause:** Perl hash key iteration order is not guaranteed. Each run can
return keys in a different order, making randomization unreproducible.

**Wrong:**


    %items = (a => 'Apple', b => 'Banana', c => 'Cherry');
    @choices = values %items;  # Random order!

**Right:**


    %items = (a => 'Apple', b => 'Banana', c => 'Cherry');
    @sorted_keys = sort keys %items;
    $selected = list_random(@sorted_keys);

## Perl-in-PG gotchas

PG is Perl, but it runs inside a security sandbox (the Safe
compartment). Several standard Perl operations are blocked or behave
differently.

### Backslash references are broken (`\@` and `\%`)

**Symptom:** `Not an ARRAY reference` or `Not a HASH reference`

**Cause:** The PG sandbox blocks the backslash (`\`) operator for
creating references. Writing `\@array` does not produce a usable array
reference.

**Wrong:**


    @choices = ('Alpha', 'Beta', 'Gamma');
    $rb = RadioButtons(\@choices, 'Alpha');

**Right (option 1 \-- anonymous copy, preferred):**


    @choices = ('Alpha', 'Beta', 'Gamma');
    $rb = RadioButtons([@choices], 'Alpha');

**Right (option 2 \-- PG double-tilde operator):**


    @choices = ('Alpha', 'Beta', 'Gamma');
    $rb = RadioButtons(~~@choices, 'Alpha');

The same rule applies to hash references:


    # Wrong:  $href = \%data;
    # Right:  $href = {%data};
    # Right:  $href = ~~%data;

### Loops do not work inside BEGIN_TEXT

**Symptom:** No output, empty section where the loop content should
appear.

**Cause:** `BEGIN_TEXT...END_TEXT` is a string construction block, not
Perl code execution. A `foreach` loop inside it becomes part of the
string rather than running as code.

**Wrong:**


    BEGIN_TEXT
    foreach my $item (@items) {
      \{ $item \}
    }
    END_TEXT

**Right (build the string before BEGIN_TEXT):**


    $all_items_html = '';
    foreach my $item (@items) {
      $all_items_html .= $item;
    }

    BEGIN_TEXT
    \{ $all_items_html \}
    END_TEXT

## Answer field naming

**Symptom:** The answer is always marked wrong, or grading silently
fails (see [Section 3.2](/@go/page/555704) for answer blank syntax).

**Cause:** The `ANS()` function expects an answer field created by
`ans_rule()`. When you create a hidden input with JavaScript or raw
HTML, its `name` attribute does not match the name that `ANS()` is
looking for (e.g., `AnSwEr0001`). The answer evaluator and the input
field never connect.

**Wrong:**


    ANS(str_cmp($answer));  # Looks for AnSwEr0001
    # But JS or HTML creates an input with a different name -- no connection!

**Right:**


    BEGIN_TEXT
    \{ MODES(HTML => '<div style="display:none;">' . ans_rule(20) . '</div>', TeX => '') \}
    END_TEXT
    ANS(str_cmp($answer));

**The rule:** `ans_rule()` creates the input field that `ANS()` checks.
Always create the `ans_rule()` first, then call `ANS()`. When you need a
custom UI with JavaScript, hide the `ans_rule()` input and use
JavaScript to populate its value.

## RDKit and SMILES chemistry errors

If your problems use RDKit to render molecular structures from SMILES
strings, incorrect SMILES notation can cause silent rendering failures
or chemically wrong diagrams.

### Incorrect formal charges in ring systems

**Symptom:** Molecule renders with wrong structure, or RDKit rejects the
SMILES string entirely.

**Cause:** Using incorrect formal charge notation for nitrogen atoms in
ring systems like imidazole. Writing `NH2+` implies two hydrogens on one
nitrogen, which is chemically incorrect for the imidazole ring.

**Wrong:**


    # NH2+ implies TWO hydrogens on one nitrogen -- wrong for imidazole
    $imidazole_protonated = '...N=C[NH2+]1)...';

**Right:**


    # Imidazole has two nitrogens: one NH, one NH+
    $imidazole_protonated = 'C1=C([NH]C=[NH+]1)...';

**Prevention:** Always validate SMILES strings with Python RDKit before
embedding them in PG problems. A SMILES string that parses without
errors can still be chemically wrong, so check the rendered structure
visually.

## Debugging strategies

When the quick reference table below does not solve your problem, use
these strategies to isolate the issue systematically.

### Check line numbers

When variables seem empty or undefined, check where the variable is used
versus where it is defined. Find the usage with a search for the
variable name, then find the definition (the line with
`$var_name = ...`). The definition line number must be lower (earlier in
the file) than the usage line number.

### Isolate PGML errors with binary search

When you get `'*' was not closed` or similar PGML parsing errors:

1.  Comment out the bottom half of your PGML block.
2.  Render the problem. If the error is gone, the problem is in the
    bottom half.
3.  Restore the bottom half and comment out the top half to confirm.
4.  Keep splitting the offending half until you find the exact line.
5.  Check for `*`, `**`, or `_` near variables on that line.

### Test with a minimal example

Create the smallest possible problem file that reproduces the error:


    DOCUMENT();
    loadMacros("PGstandard.pl", "PGML.pl");

    $var = "test";

    BEGIN_PGML
    Test: [$var]
    END_PGML

    ENDDOCUMENT();

Add complexity one piece at a time until the problem reappears. The last
piece you added is the cause.

### Check renderer output

If your local setup supports the `-r` flag on the renderer script, use
it to inspect the actual HTML output. Look for HTML that was escaped
when it should not have been (`&lt;` instead of `<`), missing elements,
or structural problems in the generated markup.

## Prevention checklist

Before committing a new PG problem file, verify each of these items:

- Variables are defined before use (check line numbers).
- No `my` on variables referenced in PGML (`$rb`, `$popup`, display
  variables).
- No `\@` or `\%` references. Use `[@array]` or `~~@array` instead.
- No `use` statements. Use `loadMacros()` for PG macros.
- No `*` or `**` immediately around `[$variables]` in PGML.
- HTML variables use `[$var]*` syntax (with the asterisk).
- No Perl loops inside `BEGIN_TEXT...END_TEXT` blocks.
- Hash keys sorted before random selection (see [Section
  6.5](/@go/page/555727)).
- Shuffling happens after all items are defined (see [Section
  6.5](/@go/page/555727)).
- `ans_rule()` created before `ANS()` call.
- SMILES strings validated with RDKit (if applicable).
- No PGML parsing errors in renderer output.

## Quick reference: error message table

Use this table to look up the error or symptom you are seeing. Find your
row and follow the fix in the right column.

  Error message or symptom                Likely cause                        Fix
  --------------------------------------- ----------------------------------- ---------------------------------------------
  `'*' was not closed`                    Asterisks around variable in PGML   Remove `*` or use `**` (bold)
  `'**' was not closed`                   Bold markers around variable        Remove bold or build emphasis in a variable
  Empty output / no content               Variable used before defined        Move definition before usage
  HTML shown literally                    Missing `*` in `[$var]*`            Add asterisk: `[$var]*`
  Answer always wrong                     Answer field name mismatch          Use `ans_rule()` before `ANS()`
  RadioButtons renders as text input      `my $rb = RadioButtons(...)`        Remove `my`: `$rb = RadioButtons(...)`
  `Not an ARRAY reference`                `\@array` backslash ref             Use `[@array]` or `~~@array`
  `Not a HASH reference`                  `\%hash` backslash ref              Use `{%hash}` or `~~%hash`
  `'require' trapped by operation mask`   `use Module` in PG                  Use `loadMacros()` or built-ins
  `'eval "string"' trapped`               `eval $code` in PG                  Restructure to avoid string eval
  `'open' trapped by operation mask`      File I/O in PG                      Not possible; use PG data macros
  Variable shows empty in PGML            `my $var` instead of `$var`         Remove `my`
  Random order changes between runs       Hash keys not sorted                Sort keys before selection
  Table content disappears                `<table>` tags blocked              Use `niceTables.pl`
  Number `1` appears instead of HTML      MODES in eval context               Check MODES usage; use `[$var]*` instead
  `A.` parsed as a list item              Ordered list auto-parsing           Use `*A.*` or `A\.` to escape

## Apply it today

When something breaks, come back to this page and look up the symptom.
Most issues fall into one of these categories:

- A PGML parsing error caused by asterisks near variables (remove or
  change the markers).
- A variable that PGML cannot see because of `my` (remove `my`).
- HTML showing as literal text (add `*` after the bracket).
- A missing macro (add it to `loadMacros()`).
- A blocked HTML tag (switch to `niceTables.pl`).
- Variables used before they are defined (move the definition earlier).
- A backslash reference that does not work in the sandbox (use
  `[@array]`).
- Answer field name mismatches (create `ans_rule()` before `ANS()`).
- SMILES chemistry errors in RDKit problems (validate with Python
  RDKit).

Start with the quick reference table above. Match your error message to
the row, read the fix, and apply it. If your problem is still not
working, use the debugging strategies earlier on this page to isolate
the issue: check line numbers, use binary search on PGML blocks, test
with a minimal example, and inspect the renderer output.

---

# 07_Testing_and_Debugging/7.5-Testing_Randomization_and_Edge_Cases

Use this section when your problem works for one seed but you need to
make sure it works for many seeds. Randomization is what makes WeBWorK
problems reusable: each student gets different numbers. But different
numbers can produce impossible biology, division by zero, or answers
that do not make sense. Testing multiple seeds catches these problems
before students encounter them.

Think of each seed as a different student sitting down with your
question. You wrote the problem with one set of numbers in your head,
but the randomization engine will generate hundreds of variants. Your
job is to make sure every variant tells a coherent story with plausible
numbers and a correct answer that makes sense.

## Why randomization testing matters

- Same problem, different seed, different failure. A problem that works
  perfectly with seed 1234 might produce a negative concentration with
  seed 5678.
- Students will see many different variants. You only tested a few. The
  variant you did not test is the one that will confuse a student at
  midnight before the deadline.
- Guard patterns (described below) prevent bad values at the source, so
  you do not have to test every possible seed by hand.

## How to sweep variants

In the browser editor, change the seed field and re-render. Try at least
five to ten different seeds for any problem that uses randomization. For
each variant, check the following:

- Does the story still make sense with these numbers?
- Are all numbers plausible for the biology? (No negative
  concentrations, no probabilities above 1, no impossible rates.)
- Does the rounding produce readable numbers? (Watch for long repeating
  decimals like 0.333333 that should be rounded.)
- Is the correct answer reasonable? (If the answer is 0, or negative, or
  astronomically large, something is wrong.)

If you are using the command-line lint script, you can render with a
specific seed using the `-s` flag:


    python3 lint_pg_via_renderer_api.py -i private/myproblem.pg -s 5678 -r > /tmp/pg_render.html

## Guard patterns: preventing bad values

Guard patterns are short code snippets that prevent randomization from
producing values that would break the problem (see [Section
6.5](/@go/page/555727) for additional randomization patterns and
techniques). Add them in the setup section of your PG file, before the
PGML block.

### Avoid zero denominators

If a random variable might be zero and you later divide by it, the
problem will crash for some students. Prevent this with a do/while loop
or the `non_zero_random` function.


    # Option 1: do/while loop
    do { $b = random(-5, 5, 1); } while ($b == 0);

    # Option 2: non_zero_random (simpler)
    $b = non_zero_random(-5, 5, 1);

### Avoid repeated values

When two variables should have different values (for example, two
different enzyme concentrations to compare), use a do/while loop to
ensure they are not equal.


    $a = random(2, 9, 1);
    do { $b = random(2, 9, 1); } while ($b == $a);

### Avoid invalid domains

Some mathematical operations are undefined for certain inputs. If your
problem takes the logarithm or square root of a random value, make sure
that value cannot be zero or negative.


    # Ensure $x is positive before using log($x)
    do { $x = random(-5, 5, 1); } while ($x <= 0);

### Sort hash keys before random selection

Perl hash key order is not deterministic. If you select a random key
from a hash, the same seed can produce different results on different
runs unless you sort the keys first.


    @sorted_keys = sort keys %items;
    $selected = list_random(@sorted_keys);

### Shuffle after all items are defined

A common mistake is to shuffle an array before all of its elements are
assigned. This produces empty or missing items in the shuffled result.
Always follow this three-step pattern:


    # Step 1: Define all items first
    $item1 = "Adenine";
    $item2 = "Thymine";
    $item3 = "Guanine";

    # Step 2: Create the array
    @all_items = ($item1, $item2, $item3);

    # Step 3: Shuffle (only after all items are in the array)
    @temp = @all_items;
    @shuffled = ();
    while (@temp) {
        $index = random(0, $#temp, 1);
        push @shuffled, splice(@temp, $index, 1);
    }

## Boundary value testing

Beyond sweeping random seeds, test specific values near the boundaries
of expected ranges. These are the values most likely to cause problems.

- Test values near zero, one, and other natural breakpoints in your
  problem.
- Test the smallest and largest values in your random range.
- Test values that produce simple fractions or exact answers to confirm
  rounding behaves as expected.

For biology problems, pay special attention to domain-specific
constraints:

- **Concentrations:** Never negative. Usually between 0 and a realistic
  maximum for the context (millimolar, micromolar, etc.).
- **Probabilities:** Always between 0 and 1. Never above 1, never below
  0.
- **pH values:** Between 0 and 14.
- **Rates:** Non-negative and of a reasonable magnitude for the
  biological process.
- **Percentages:** Between 0 and 100.

## What to watch for: a checklist

  Check                          What could go wrong                                   How to test
  ------------------------------ ----------------------------------------------------- ----------------------------------------------------------------------------
  Negative concentrations        Random subtraction goes below zero                    Try seeds that produce small values near the lower end of the range
  Impossible probabilities       Probability exceeds 1 or goes below 0                 Check boundary cases where the computed probability approaches 0 or 1
  Awkward rounding               Values like 0.333333\... displayed without rounding   Set explicit rounding in the problem and verify the display
  Repeated answer choices        Two random choices get the same value                 Use a do/while guard to ensure uniqueness
  Division by zero               Random denominator is zero                            Use `non_zero_random` or a do/while guard
  Story does not match numbers   Random values make the scenario implausible           Read each variant as a student would and ask whether the story makes sense

## Apply it today

Pick one problem with randomization. Render it with five different
seeds. For each variant, ask yourself: \"Would this make sense to a
student?\" If any variant produces impossible numbers or a confusing
story, add a guard pattern to prevent it. A few minutes of seed-sweeping
now saves a confused email from a student later.

---

# 07_Testing_and_Debugging/7.6-QA_Checklist_Before_Publishing

Use this section when your problem is working and you want to make sure
it is ready for students. This is the final check before publishing. The
two checklists below cover code-level issues (things the computer cares
about) and author-level issues (things that affect students). Run both
before you ship.

These checklists are distilled from the most common problems found in
real WeBWorK files (see also [Section 5.9](/@go/page/555722) for the
full authoring workflow). Each item links back to the section where you
can find a full explanation and fix. If you are not sure what an item
means, follow the section reference first.

## Prevention checklist: code-level checks

Walk through this table before you render for the last time. Each row is
one thing that can silently break your problem without producing an
obvious error message. Most of these issues will not show a helpful
error \-- the problem will simply render wrong or grade incorrectly.

  Check                                                      What to verify                                                                                                Section reference
  ---------------------------------------------------------- ------------------------------------------------------------------------------------------------------------- ---------------------------------
  Variables defined before use                               All variables are assigned values before they are referenced in arrays, shuffles, or PGML                     [Section 7.2](/@go/page/555733)
  No `my` on PGML-visible variables                          Variables referenced in PGML (`$rb`, `$popup`, display variables) do not use `my`                             [Section 7.2](/@go/page/555733)
  No `\@` or `\%` backslash references                       Use `[@array]` or `~~@array` instead of `\@array`                                                             [Section 7.2](/@go/page/555733)
  No `use` statements                                        Use `loadMacros()` for PG macros, not Perl `use`                                                              [Section 7.2](/@go/page/555733)
  No `*` or `**` immediately around `[$variables]` in PGML   Asterisks near variables cause parse errors such as \"\* was not closed before paragraph ends\"               [Section 7.2](/@go/page/555733)
  HTML variables use `[$var]*` syntax                        Variables containing HTML tags have the trailing asterisk so tags render instead of showing as literal text   [Section 7.2](/@go/page/555733)
  No Perl loops inside `BEGIN_TEXT...END_TEXT` blocks        Build strings before the block, then insert them with a variable reference                                    [Section 7.2](/@go/page/555733)
  Hash keys sorted before random selection                   Use `sort keys %hash` before `list_random()` so a fixed seed gives stable results                             [Section 7.4](/@go/page/557411)
  Shuffling happens after all items are defined              Define all items first, create the array, then shuffle                                                        [Section 7.4](/@go/page/557411)
  OPL metadata complete                                      TITLE, DESCRIPTION, KEYWORDS, and DBsubject fields are filled in (see [Section 2.2](/@go/page/557378))        [Section 2.2](/@go/page/557378)
  No blocked HTML tags                                       No `<table>`, `<tr>`, `<td>`, `<th>` in PGML output (use `niceTables.pl` instead)                             [Section 7.2](/@go/page/555733)
  Required macros loaded                                     Every widget and feature has its macro in the `loadMacros()` call                                             [Section 7.2](/@go/page/555733)
  `DOCUMENT()` and `ENDDOCUMENT()` present                   File starts with `DOCUMENT()` and ends with `ENDDOCUMENT()`                                                   [Section 7.3](/@go/page/557407)

## Author checklist: student-facing checks

This checklist catches problems that render without errors but still
confuse or frustrate students. These are things only a human can verify
by reading the problem as a student would.

  Check                                 What to verify                                              How to test
  ------------------------------------- ----------------------------------------------------------- ------------------------------------------------------------------------------------------------
  Render multiple variants              The problem works correctly with different seeds            Change seeds in the editor and render at least five variants ([Section 7.4](/@go/page/557411))
  Displayed question matches grader     The story and the expected answer agree                     Read the question and check that the correct answer matches the prompt
  Correct answers accepted              The right answer is marked correct                          Enter the correct answer and submit
  Common wrong answers rejected         Plausible wrong answers are marked incorrect                Enter a few wrong answers (off-by-one, wrong units, sign errors) and check
  Edge cases checked                    Boundary values and extreme random ranges work              Test with seeds that produce small or large values ([Section 7.4](/@go/page/557411))
  No course-local dependencies          The problem runs without files from your specific course    Test in the local renderer, not in ADAPT
  Every blank has an inline evaluator   Each answer blank in PGML has a grader attached             Check that every blank has content in curly braces: `[_]{$ans}` or `[__]{$ans}`
  Solution block included               A `BEGIN_PGML_SOLUTION...END_PGML_SOLUTION` block exists    Search for SOLUTION in the file
  Units and rounding stated             The prompt tells students what units and precision to use   Read the question as a student and check that units and rounding are explicit

## Minimal debugging note template

When you find a problem during your QA pass, fill in this template and
save it. Having these details written down before you start fixing
anything will save you time and prevent you from losing track of the
original failure.


    File:
    Seed:
    Symptom:
    Error message (if any):
    What I changed last:
    Expected behavior:

Copy this block into a text file or comment in your code. When you
report an issue to a colleague or come back to a problem days later,
this note tells you exactly where to start.

## What \"ready to publish\" looks like

A problem is ready to publish when all of the following are true:

- Both checklists above are satisfied with no remaining failures.
- The problem renders cleanly with at least five different seeds.
- The question reads clearly as a student-facing prompt, with no
  ambiguous wording or missing context.
- Every answer blank is visible and in the right location on the page.
- The solution block explains the expected method and shows the correct
  answer.
- No warnings or errors appear from the renderer in either HTML or JSON
  output.

If any of these conditions are not met, fix the issue before importing
the problem to ADAPT. A problem that passes all checks here should work
correctly the first time a student sees it.

### Quick sanity test

If you only have time for one test, do this: render the problem with
five different seeds, enter the correct answer for each, and submit. If
all five accept the correct answer and the question text makes sense for
each variant, the problem is probably ready. If any variant looks wrong,
go back to the checklists.

## Apply it today

- Pick one problem you are about to publish. Run both checklists above,
  row by row.
- If anything fails, fix it before importing to ADAPT. Use the section
  references in the code-level checklist to find the explanation and
  fix.
- Save the debugging note template somewhere you can find it quickly the
  next time something breaks.

---

# 08_Using_AI_Agents_to_Write_WeBWorK/8.0-Index

Placeholder index for Chapter 8: Using AI Agents to Write WeBWorK.

{{template.ShowOrg()}}

---

# 08_Using_AI_Agents_to_Write_WeBWorK/8.1-What_are_AI_Agents

Placeholder page for 8.1: What are AI Agents?

---

# 08_Using_AI_Agents_to_Write_WeBWorK/8.2-Knowledge_Documents_for_AI_Agents

Placeholder page for 8.2: Knowledge Documents for AI Agents.

---

# 08_Using_AI_Agents_to_Write_WeBWorK/8.3-Connecting_AI_Agents_to_the_PG_Renderer

Placeholder page for 8.3: Connecting AI Agents to the PG Renderer.

---

# 08_Using_AI_Agents_to_Write_WeBWorK/8.4-Advance_AI_Agents_Advice

Placeholder page for 8.4: Advance AI Agents Advice.

---

# 90_Appendices/90.0-Index

This appendix collects reusable reference material: minimal templates, a
concise glossary, a troubleshooting checklist, and a macro demonstration
compendium with complete renderable problems for each commonly used PG
macro.

Worked examples live in the main chapters where the techniques are
introduced. See [Chapter 4](/@go/page/488661) for component breakdowns
and [Chapter 7](/@go/page/555731) for testing and debugging. Appendix
90.4 provides one complete, renderable PG problem per macro with
biology-themed demos and version history notes.

{{template.ShowOrg()}}

---

# 90_Appendices/90.1-Minimal_templates

This page provides copy-paste templates for common problem patterns (see
[Section 2.1](/@go/page/488656) for an introduction to PG and [Chapter
4](/@go/page/488661) for detailed component breakdowns). Each template
includes a complete OPL header so you can start with proper metadata.

## Template: single numeric answer


    ## TITLE('Compute a simple sum')
    ## DESCRIPTION
    ## Add two values and report the total with specified units.
    ## ENDDESCRIPTION
    ## KEYWORDS('addition','numeric entry','units')
    ## DBsubject('Biostatistics')
    ## DBchapter('Basic calculations')
    ## DBsection('Unit reporting')
    ## Date('2026-01-28')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $a = random(2, 8, 1);
    $b = random(3, 9, 1);
    $ans = Real($a + $b);

    BEGIN_PGML
    Total: [________]{$ans} units
    END_PGML

    ENDDOCUMENT();

## Template: RadioButtons (single choice)


    ## TITLE('Select the correct label')
    ## DESCRIPTION
    ## Choose the correct label from a short list using radio buttons.
    ## ENDDESCRIPTION
    ## KEYWORDS('radio buttons','single choice','labels')
    ## DBsubject('Cell Biology')
    ## DBchapter('Lab techniques')
    ## DBsection('Labeling conventions')
    ## Date('2026-01-28')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    $radio = RadioButtons(
        [ 'Label A', 'Label B', 'Label C' ],
        'Label B',
    );

    BEGIN_PGML
    Select the correct label: [_]{$radio}
    END_PGML

    ENDDOCUMENT();

## Template: PopUp matching


    ## TITLE('Match terms to definitions')
    ## DESCRIPTION
    ## Match each term to its definition using PopUp widgets.
    ## ENDDESCRIPTION
    ## KEYWORDS('matching','PopUp','definitions')
    ## DBsubject('Molecular Biology')
    ## DBchapter('Vocabulary')
    ## DBsection('Core terms')
    ## Date('2026-01-28')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "parserPopUp.pl",
        "PGcourse.pl",
    );

    $popup1 = PopUp(['?','A','B','C'], 'A');
    $popup2 = PopUp(['?','A','B','C'], 'B');

    BEGIN_PGML
    1. Term one [_]{$popup1}

    2. Term two [_]{$popup2}
    END_PGML

    ENDDOCUMENT();

## Template: multi-part prompt


    ## TITLE('Compute and interpret a value')
    ## DESCRIPTION
    ## Compute a value, then interpret it with a short follow-up statement.
    ## ENDDESCRIPTION
    ## KEYWORDS('multi-part','numeric','interpretation')
    ## DBsubject('Biochemistry')
    ## DBchapter('Concentrations')
    ## DBsection('Dilution')
    ## Date('2026-01-28')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $c1 = random(2, 6, 1);
    $c2 = random(1, 4, 1);
    $ratio = Real($c1 / $c2);
    $double = Real(2 * $ratio);

    BEGIN_PGML
    1. Compute the ratio: [________]{$ratio}

    2. What is twice the ratio? [________]{$double}
    END_PGML

    ENDDOCUMENT();

## Template: DraggableProof (ordered list)


    ## TITLE('Order a sequence of steps')
    ## DESCRIPTION
    ## Put items in the correct order using a drag-and-drop
    ## interface.
    ## ENDDESCRIPTION
    ## KEYWORDS('ordering','DraggableProof','sequence')
    ## DBsubject('Molecular Biology')
    ## DBchapter('Techniques')
    ## DBsection('Protocols')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "draggableProof.pl",
        "PGcourse.pl",
    );

    $ordering = DraggableProof(
        [ "Step one", "Step two", "Step three" ],
        [],
        SourceLabel => "Items",
        TargetLabel => "Correct order",
    );
    $ordering_html = $ordering->Print;

    BEGIN_PGML
    Put the steps in the correct order.

    [$ordering_html]*
    END_PGML

    ANS($ordering->cmp);

    ENDDOCUMENT();

## Template: fill-in-the-blank (String)


    ## TITLE('Name a biological term')
    ## DESCRIPTION
    ## Type the correct term in the blank using a string
    ## context answer.
    ## ENDDESCRIPTION
    ## KEYWORDS('fill in the blank','String','terminology')
    ## DBsubject('Cell Biology')
    ## DBchapter('Vocabulary')
    ## DBsection('Core terms')
    ## Date('2026-02-15')
    ## Author('Author name')
    ## Institution('Institution name')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "contextArbitraryString.pl",
        "PGcourse.pl",
    );

    Context("ArbitraryString");
    $ans = Compute("mitochondrion");

    BEGIN_PGML
    The organelle responsible for producing most of the cell's
    ATP is the [__________]{$ans}.
    END_PGML

    ENDDOCUMENT();

Remember to update TITLE, DESCRIPTION, KEYWORDS, and DBsubject fields
for your specific problem.

---

# 90_Appendices/90.2-Glossary

This glossary defines the key terms used throughout the textbook so you
can look up unfamiliar jargon quickly. For additional context on these
terms, see [Section 1.5](/@go/page/555734).

  -----------------------------------------------------------------------
  Term            Definition
  --------------- -------------------------------------------------------
  PG              The Perl-based language that defines a WeBWorK problem
                  file.

  PGML            A markup layer inside PG for writing student-facing
                  text and blanks (see [Chapter 3](/@go/page/488660)).

  Context         Rules that control what student input is allowed and
                  how it is parsed.

  MathObjects     Typed answer objects (numbers, formulas, lists) used
                  for grading.

  Macro           A reusable code library loaded by a problem to enable
                  features (see [Section 2.5](/@go/page/488659)).

  Seed            A number that reproduces one randomized variant of a
                  problem.

  OPL header      Metadata comment block used for searchability and
                  attribution.

  ADAPT           LibreTexts assessment platform where WeBWorK problems
                  are assigned.

  Renderer        Local webwork-pg-renderer service used for fast
                  previews (see [Section 7.1](/@go/page/555732)).
  -----------------------------------------------------------------------

---

# 90_Appendices/90.3-Troubleshooting_checklist

This checklist maps common failure symptoms to likely causes and the
quickest first fix (see [Section 7.2](/@go/page/555733) for detailed
explanations and [Chapter 7](/@go/page/555731) for the full testing and
debugging guide). Use it when ADAPT reports a generic error or when
grading does not match the prompt.

## Common symptoms

  -----------------------------------------------------------------------
  Symptom                   Likely cause           First fix
  ------------------------- ---------------------- ----------------------
  Generic ADAPT error       Missing macro or       Render locally and
                            syntax error           check the line number.

  Blank missing or out of   PGML formatting or     Confirm the blank
  place                     wrong answer object    token matches the
                            binding                answer object name.

  Grading feels wrong       Tolerance or unit      Restate units next to
                            mismatch               the blank and check
                                                   the checker settings.

  Only some seeds make      Randomization range is Constrain random
  sense                     too wide               values and rerender
                                                   multiple seeds.

  CSS styling missing       HTML was escaped in    Use `[$var]*` for HTML
                            PGML                   variables.
  -----------------------------------------------------------------------

## Quick preflight

- Preview at least two seeds.
- Read the prompt as a student (units, rounding, format cues).
- Confirm each blank has the intended answer object.
- Keep a note of the file path and seed for any failure.

---

# 90_Appendices/90.4-Macro_Demonstrations

This appendix provides one complete, renderable PG problem for each of
the most commonly used macros documented in [Section
2.5](/@go/page/488659). Every demo is a full
`DOCUMENT()`/`ENDDOCUMENT()` problem with a biology-themed prompt that
you can copy, paste, and render immediately.

Some macros already have complete working examples elsewhere in the
textbook. Where that is the case, a cross-reference replaces the demo.
Each entry also includes a brief version history note so you know how
long the macro has been available and what changed in recent PG
releases.

## Interaction widgets

### parserRadioButtons.pl

**History:** Long-running (MathObjects era). Values display added PG
2.18 (2023).

Complete examples appear in [Section 5.2](/@go/page/555715) (multiple
choice) and Appendix 90.1 (minimal template). See those pages for
copy-paste RadioButtons demos.

### parserPopUp.pl

**History:** Long-running (MathObjects era). DropDown method added PG
2.18. Breaking change PG 2.19.

Complete examples appear in [Section 5.4](/@go/page/555717) (matching)
and Appendix 90.1 (minimal template). See those pages for copy-paste
PopUp demos.

### PGchoicemacros.pl

**History:** Long-running legacy macro (WeBWorK 2.0+, 2004). Predates
MathObjects.

**Note:** PGchoicemacros.pl is a legacy macro. Its utility functions
(`NchooseK`, `shuffle`) are deprecated; `PGsort` is a core function from
PGbasicmacros.pl, not from this macro. The non-deprecated core is
`new_match_list` with `print_q`/`print_a`. These methods generate their
own form fields, so `ANS()` is required. For new problems, prefer PopUp
(`parserPopUp.pl`) or RadioButtons (`parserRadioButtons.pl`).


    ## TITLE('Match organelles to functions')
    ## DESCRIPTION
    ## Use PGchoicemacros new_match_list to associate organelles
    ## with their primary cellular functions.
    ## ENDDESCRIPTION
    ## KEYWORDS('matching','organelles','match list')
    ## DBsubject('Cell Biology')
    ## DBchapter('Organelles')
    ## DBsection('Functions')
    ## Date('2026-02-16')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGML.pl",
        "PGchoicemacros.pl",
        "PGcourse.pl",
    );

    $ml = new_match_list();
    $ml->qa(
        "Site of aerobic respiration",    "Mitochondrion",
        "Site of protein synthesis",      "Ribosome",
        "Packages and ships proteins",    "Golgi apparatus",
        "Contains the cell's DNA",        "Nucleus",
    );
    $ml->choose(4);

    BEGIN_PGML
    Match each function with the correct organelle.

    [@ $ml->print_q @]*

    [@ $ml->print_a @]*
    END_PGML

    ANS(str_cmp($ml->ra_correct_ans));

    ENDDOCUMENT();

### draggableProof.pl

**History:** Introduced \~PG 2.14. Updated PG 2.17 (2022) for Gateway
quiz support.

Complete examples appear in [Section 5.8](/@go/page/555721) (ordered
list) and Appendix 90.1 (minimal template). See those pages for
copy-paste DraggableProof demos.

### draggableSubsets.pl

**History:** Introduced \~PG 2.14.


    ## TITLE('Sort molecules into macromolecule categories')
    ## DESCRIPTION
    ## Drag molecules into the correct macromolecule bin using
    ## DraggableSubsets.
    ## ENDDESCRIPTION
    ## KEYWORDS('classification','macromolecules','drag and drop')
    ## DBsubject('Biochemistry')
    ## DBchapter('Macromolecules')
    ## DBsection('Classification')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "draggableSubsets.pl",
        "PGcourse.pl",
    );

    $draggable = DraggableSubsets(
        [ "Glucose", "Starch", "Hemoglobin", "Phospholipid",
          "Cellulose", "Insulin", "Cholesterol", "Glycogen" ],
        [
            [ 0, 1, 4, 7 ],
            [ 2, 5 ],
            [ 3, 6 ],
        ],
        DefaultSubsets => [
            { label => "Carbohydrates", indices => [] },
            { label => "Proteins", indices => [] },
            { label => "Lipids", indices => [] },
        ],
    );

    BEGIN_PGML
    Drag each molecule into the correct macromolecule category.

    [_]{$draggable}
    END_PGML

    ENDDOCUMENT();

### parserWordCompletion.pl

**History:** Long-running (MathObjects era).


    ## TITLE('Fill in homeostasis from a word bank')
    ## DESCRIPTION
    ## Select the correct biological term from a word bank using
    ## WordCompletion.
    ## ENDDESCRIPTION
    ## KEYWORDS('word bank','homeostasis','terminology')
    ## DBsubject('Physiology')
    ## DBchapter('Homeostasis')
    ## DBsection('Core concepts')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "parserWordCompletion.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $wc = WordCompletion(
        [ "homeostasis", "metabolism", "mitosis", "osmosis", "diffusion" ],
        "homeostasis",
    );

    BEGIN_PGML
    The process by which organisms maintain a stable internal environment
    despite changes in external conditions is called
    [_]{$wc}.

    _Word bank: homeostasis, metabolism, mitosis, osmosis, diffusion_
    END_PGML

    ENDDOCUMENT();

### PGessaymacros.pl

**History:** Introduced \~PG 2.9 (2014). Equation editor added PG 2.16.

**Note:** Essay questions cannot be auto-graded. The student sees a text
box and the instructor must grade manually. The `essay_box()` function
creates its own form field, so `ANS(essay_cmp())` is required after
`END_PGML`.


    ## TITLE('Short essay on natural selection')
    ## DESCRIPTION
    ## Prompt students to write a short explanation of natural
    ## selection using an essay box.
    ## ENDDESCRIPTION
    ## KEYWORDS('essay','natural selection','free response')
    ## DBsubject('Evolution')
    ## DBchapter('Natural Selection')
    ## DBsection('Mechanisms')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "PGessaymacros.pl",
        "PGML.pl",
        "PGcourse.pl",
    );

    BEGIN_PGML
    In three to five sentences, explain how natural selection
    leads to adaptation in a population over time. Include at
    least one specific example from a real organism.

    [@ essay_box(8, 60) @]*
    END_PGML

    ANS(essay_cmp());

    ENDDOCUMENT();

## Science-native contexts

### parserNumberWithUnits.pl

**History:** Long-running (MathObjects era). Unit improvements PG 2.18.


    ## TITLE('Enzyme reaction rate with units')
    ## DESCRIPTION
    ## Calculate an enzyme reaction rate and report the answer
    ## with correct units using NumberWithUnits.
    ## ENDDESCRIPTION
    ## KEYWORDS('units','enzyme kinetics','reaction rate')
    ## DBsubject('Biochemistry')
    ## DBchapter('Enzyme Kinetics')
    ## DBsection('Reaction rates')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "parserNumberWithUnits.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $moles = random(2, 8, 1);
    $seconds = random(10, 30, 5);
    $rate_val = $moles / $seconds;
    $ans = NumberWithUnits("$rate_val mol/s");

    BEGIN_PGML
    An enzyme converts [$moles] mol of substrate in [$seconds] seconds.

    What is the reaction rate? Include units in your answer.

    Rate = [__________]{$ans}

    _(Enter your answer as a number followed by units, e.g. "0.5 mol/s")_
    END_PGML

    ENDDOCUMENT();

### parserFormulaWithUnits.pl

**History:** Long-running (MathObjects era).


    ## TITLE('Dilution formula with units')
    ## DESCRIPTION
    ## Express a dilution formula C1*V1/V2 with units using
    ## FormulaWithUnits.
    ## ENDDESCRIPTION
    ## KEYWORDS('formula','dilution','units')
    ## DBsubject('Biochemistry')
    ## DBchapter('Solutions')
    ## DBsection('Dilutions')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "parserFormulaWithUnits.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    Context()->variables->add(c => "Real");
    $ans = FormulaWithUnits("3 c ml");

    BEGIN_PGML
    A formula for the volume of a solution used in a serial
    dilution is [`V = 3c`] mL, where [`c`] is a
    concentration factor.

    Express this formula with units.

    [`V`] = [__________]{$ans}

    _(Enter a formula with units, e.g. "3 c ml")_
    END_PGML

    ENDDOCUMENT();

### contextScientificNotation.pl

**History:** Long-running (MathObjects era).


    ## TITLE('Bacterial count after doublings')
    ## DESCRIPTION
    ## Calculate the number of bacteria after several doublings
    ## and express the answer in scientific notation.
    ## ENDDESCRIPTION
    ## KEYWORDS('scientific notation','bacteria','exponential growth')
    ## DBsubject('Microbiology')
    ## DBchapter('Growth')
    ## DBsection('Exponential growth')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "contextScientificNotation.pl",
        "PGcourse.pl",
    );

    Context("ScientificNotation");
    $doublings = random(10, 20, 1);
    $initial = 1000;
    $final = $initial * 2**$doublings;
    $ans = ScientificNotation($final);

    BEGIN_PGML
    A bacterial culture starts with [$initial] cells and doubles
    every 30 minutes. After [$doublings] doublings, how many
    cells are present?

    Express your answer in scientific notation.

    Number of cells = [______________]{$ans}

    _(Example format: 1.5 x 10^6 or 1.5E6)_
    END_PGML

    ENDDOCUMENT();

### contextReaction.pl

**History:** Long-running (MathObjects era). Improved PG 2.20 (2025).


    ## TITLE('Write a combustion reaction')
    ## DESCRIPTION
    ## Enter a balanced combustion reaction using the
    ## Reaction context.
    ## ENDDESCRIPTION
    ## KEYWORDS('chemical equation','combustion','reaction')
    ## DBsubject('Biochemistry')
    ## DBchapter('Metabolism')
    ## DBsection('Chemical reactions')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "contextReaction.pl",
        "PGcourse.pl",
    );

    Context("Reaction");
    $rxn = Formula("2 H_2 + O_2 --> 2 H_2O");

    BEGIN_PGML
    Hydrogen gas reacts with oxygen gas to produce water.

    Write the balanced equation for this reaction.
    Use --> for the reaction arrow. Use _ for subscripts
    (e.g., H_2 for [`\text{H}_2`]).

    Equation: [__________________________]{$rxn}

    _(Example format: 2 H_2 + O_2 --> 2 H_2O)_
    END_PGML

    ENDDOCUMENT();

### contextFraction.pl

**History:** Long-running (MathObjects era). `num`/`den` methods added
PG 2.19 (2024). Updated PG 2.20.


    ## TITLE('Mendelian cross offspring ratio')
    ## DESCRIPTION
    ## Calculate the fraction of offspring with a recessive
    ## phenotype from a monohybrid cross using Fraction context.
    ## ENDDESCRIPTION
    ## KEYWORDS('fraction','Mendelian genetics','monohybrid')
    ## DBsubject('Genetics')
    ## DBchapter('Mendelian Genetics')
    ## DBsection('Monohybrid cross')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "contextFraction.pl",
        "PGcourse.pl",
    );

    Context("Fraction");
    $ans = Fraction(1, 4);

    BEGIN_PGML
    In a monohybrid cross between two heterozygous parents
    (Aa x Aa), what fraction of the offspring are expected
    to show the recessive phenotype (aa)?

    Express your answer as a fraction.

    Fraction with recessive phenotype = [________]{$ans}
    END_PGML

    ENDDOCUMENT();

### contextPercent.pl

**History:** Long-running (MathObjects era).


    ## TITLE('Hardy-Weinberg allele frequency as percent')
    ## DESCRIPTION
    ## Calculate a heterozygote frequency using Hardy-Weinberg
    ## equilibrium and express it as a percentage.
    ## ENDDESCRIPTION
    ## KEYWORDS('percent','Hardy-Weinberg','allele frequency')
    ## DBsubject('Genetics')
    ## DBchapter('Population Genetics')
    ## DBsection('Hardy-Weinberg')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "contextPercent.pl",
        "PGcourse.pl",
    );

    Context("Percent");
    $q_sq = list_random(0.01, 0.04, 0.09, 0.16);
    $q = sqrt($q_sq);
    $p = 1 - $q;
    $heterozygote_freq = 2 * $p * $q;
    $ans = Percent($heterozygote_freq * 100);

    BEGIN_PGML
    In a population at Hardy-Weinberg equilibrium, the frequency of
    the homozygous recessive genotype (aa) is [$q_sq].

    What is the expected frequency of heterozygotes (Aa)?

    Express your answer as a percentage.

    Heterozygote frequency = [________]{$ans}

    _(Include the % sign in your answer, e.g. "48%")_
    END_PGML

    ENDDOCUMENT();

### contextArbitraryString.pl

**History:** Long-running (MathObjects era).

Complete examples appear in [Section 5.6](/@go/page/555719) (fill in the
blank) and Appendix 90.1 (minimal template). See those pages for
copy-paste ArbitraryString demos.

## Grading and feedback

### answerCustom.pl

**History:** Long-running (MathObjects era).


    ## TITLE('Accept pH values in a custom range')
    ## DESCRIPTION
    ## Use a custom answer checker to accept any pH value
    ## within the physiological range as correct.
    ## ENDDESCRIPTION
    ## KEYWORDS('custom checker','pH','physiology')
    ## DBsubject('Biochemistry')
    ## DBchapter('Buffers')
    ## DBsection('pH')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "answerCustom.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $correct = Real(7.4);
    $checker = custom_cmp(
        $correct,
        sub {
            my ($correct_ans, $student_ans) = @_;
            return ($student_ans >= 7.35 && $student_ans <= 7.45) ? 1 : 0;
        },
    );

    BEGIN_PGML
    Normal blood pH is tightly regulated within a narrow range.

    Enter any pH value within the normal physiological range
    for human blood.

    pH = [________]{$checker}

    _(Hint: normal blood pH is approximately 7.35 to 7.45)_
    END_PGML

    ENDDOCUMENT();

### answerHints.pl

**History:** Long-running. Updated PG 2.16 (2021): no hints in preview
mode.


    ## TITLE('Dilution calculation with targeted error feedback')
    ## DESCRIPTION
    ## Calculate a dilution with AnswerHints providing feedback
    ## for common student errors.
    ## ENDDESCRIPTION
    ## KEYWORDS('answer hints','dilution','feedback')
    ## DBsubject('Biochemistry')
    ## DBchapter('Solutions')
    ## DBsection('Dilutions')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "answerHints.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $c1 = 10;
    $v1 = 5;
    $v2 = 50;
    $c2 = Real($c1 * $v1 / $v2);
    $wrong_multiply = Real($c1 * $v2 / $v1);
    $wrong_ratio = Real($v2 / $v1);

    BEGIN_PGML
    You dilute [$v1] mL of a [$c1] mM solution to a final volume
    of [$v2] mL. What is the final concentration in mM?

    Final concentration = [________]{AnswerHints(
        $wrong_multiply =>
            "Check your formula: C2 = C1*V1/V2, not C1*V2/V1.",
        $wrong_ratio =>
            "You calculated the dilution factor, not the final concentration.",
        $c2 => "Correct!",
    )} mM
    END_PGML

    ENDDOCUMENT();

### parserMultiAnswer.pl

**History:** Long-running (MathObjects era). Bug fix PG 2.16 for
singleResult scoring.


    ## TITLE('Linked dilution blanks graded together')
    ## DESCRIPTION
    ## Enter two related dilution values that are graded
    ## together using MultiAnswer.
    ## ENDDESCRIPTION
    ## KEYWORDS('MultiAnswer','dilution','linked grading')
    ## DBsubject('Biochemistry')
    ## DBchapter('Solutions')
    ## DBsection('Dilutions')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "parserMultiAnswer.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $vol = Real(5);
    $conc = Real(2);

    $ma = MultiAnswer($vol, $conc)->with(
        singleResult => 0,
        checker => sub {
            my ($correct, $student) = @_;
            my ($sv, $sc) = @{$student};
            my @scores = (0, 0);
            $scores[0] = 1 if ($sv * $sc == 10);
            $scores[1] = 1 if ($sv * $sc == 10);
            return [@scores];
        },
    );

    BEGIN_PGML
    You need a total of 10 mM*mL of solute. Choose a volume
    and concentration whose product equals 10.

    Volume (mL): [____]{$ma}

    Concentration (mM): [____]{$ma}
    END_PGML

    ENDDOCUMENT();

### PGgraders.pl

**History:** Long-running (WeBWorK 2.x+).
`custom_problem_grader_0_60_100` removed PG 2.20.

**Note:** The `install_problem_grader` call is setup code that works
with PGML inline blanks. PGML blanks generate `ANS()` calls
automatically, so no explicit `ANS()` is needed.


    ## TITLE('Calculate three enzyme rates with partial credit')
    ## DESCRIPTION
    ## Students calculate three enzyme reaction rates with
    ## partial credit using full_partial_grader from PGgraders.
    ## ENDDESCRIPTION
    ## KEYWORDS('partial credit','enzyme kinetics','grading')
    ## DBsubject('Biochemistry')
    ## DBchapter('Enzyme Kinetics')
    ## DBsection('Reaction rates')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "PGgraders.pl",
        "PGcourse.pl",
    );

    install_problem_grader(~~&full_partial_grader);

    Context("Numeric");
    $r1 = Real(10 / 2);
    $r2 = Real(20 / 4);
    $r3 = Real(30 / 5);

    BEGIN_PGML
    Calculate the reaction rate (substrate/min) for each enzyme.
    You will receive partial credit for each correct answer.

    Enzyme A converts 10 units in 2 min. Rate = [________]{$r1}

    Enzyme B converts 20 units in 4 min. Rate = [________]{$r2}

    Enzyme C converts 30 units in 5 min. Rate = [________]{$r3}
    END_PGML

    ENDDOCUMENT();

### weightedGrader.pl

**History:** Long-running (WeBWorK 2.x+).

**Note:** Use `weight_ans()` to wrap a checker with a weight. The
wrapped checker works with PGML inline blanks.


    ## TITLE('Weighted dilution: volume then concentration')
    ## DESCRIPTION
    ## A two-part dilution problem where the concentration
    ## calculation is worth more, using weightedGrader.
    ## ENDDESCRIPTION
    ## KEYWORDS('weighted grading','dilution','partial credit')
    ## DBsubject('Biochemistry')
    ## DBchapter('Solutions')
    ## DBsection('Dilutions')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "weightedGrader.pl",
        "PGcourse.pl",
    );

    install_weighted_grader();

    Context("Numeric");
    $dilution_factor = Real(10);
    $final_conc = Real(5);

    BEGIN_PGML
    You dilute a 50 mM stock solution by a factor of 10.

    Part 1 (30%): What is the dilution factor?
    [________]{weight_ans($dilution_factor->cmp, 30)}

    Part 2 (70%): What is the final concentration in mM?
    [________]{weight_ans($final_conc->cmp, 70)}
    END_PGML

    ENDDOCUMENT();

## Layout and scaffolding

### niceTables.pl

**History:** Long-running. Overhauled PG 2.18 (2023). Auto-loaded in
PGML PG 2.19.

Complete examples appear in [Section 6.2](/@go/page/555724) (making
tables with niceTables). See that page for copy-paste DataTable and
LayoutTable demos.

### scaffold.pl

**History:** Long-running. Replaces deprecated compoundProblem\*.pl
(deprecated PG 2.19).

**Authoring warning:** Each `Section` block requires its own
`BEGIN_PGML`/`END_PGML` pair. Variables defined in one section are
visible in later sections, but each section\'s PGML block must be
self-contained. Rendering quirks may appear with deeply nested
scaffolds.


    ## TITLE('Two-section genetics: genotype then phenotype ratio')
    ## DESCRIPTION
    ## A scaffolded problem where students first identify a
    ## genotype, then calculate the phenotype ratio in a
    ## separate section.
    ## ENDDESCRIPTION
    ## KEYWORDS('scaffold','genetics','multi-section')
    ## DBsubject('Genetics')
    ## DBchapter('Mendelian Genetics')
    ## DBsection('Monohybrid cross')
    ## Date('2026-02-15')
    ## Author('Textbook demo')
    ## Institution('LibreTexts')

    DOCUMENT();
    loadMacros(
        "PGstandard.pl",
        "MathObjects.pl",
        "PGML.pl",
        "scaffold.pl",
        "parserRadioButtons.pl",
        "PGcourse.pl",
    );

    Context("Numeric");
    $genotype_radio = RadioButtons(
        [ "AA x AA", "Aa x Aa", "AA x aa", "aa x aa" ],
        "Aa x Aa",
    );
    $ratio = Real(3/4);

    Scaffold::Begin();

    Section::Begin("Part 1: Identify the cross");
    BEGIN_PGML
    Both parents are heterozygous for a single gene with
    complete dominance. Which cross represents this mating?

    [_]{$genotype_radio}
    END_PGML
    Section::End();

    Section::Begin("Part 2: Calculate the ratio");
    BEGIN_PGML
    For the cross Aa x Aa, what fraction of offspring will
    show the dominant phenotype?

    Express your answer as a decimal.

    Fraction dominant = [________]{$ratio}
    END_PGML
    Section::End();

    Scaffold::End();

    ENDDOCUMENT();

### PGgraphmacros.pl

**History:** Long-running core macro (WeBWorK 2.x+).

Complete examples appear in [Section 6.3](/@go/page/555728) (making
graphs). See that page for copy-paste graph demos with biology-themed
content.

