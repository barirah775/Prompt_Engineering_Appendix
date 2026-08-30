# Prompt Engineering Appendix

This repository contains the full appendix for the paper
**"Evaluating Ontology-Guided Prompt Engineering for Contextually Grounding Heritage Visualisation
in HBIM-Oriented Workflows."** It
documents the prompting methods, prompt templates, iterative refinement
processes, experimental results, and supporting visual outputs used in
the study.

## AI-Generated Visual Content and Provenance

Unless explicitly identified as a historical reference image, the
architectural façades, floorplans, isometric representations, and
iterative visual outputs contained in this repository are AI-generated
experimental outputs produced during the prompt-engineering workflow
described in the associated paper.

These AI-generated images are not presented as documentary records or
historically verified reconstructions of the referenced buildings. Their
role in the research is methodological: they constitute experimental
outputs used to examine generative behaviour, support iterative prompt
refinement and reverse-prompt diagnostics, compare prompt
configurations, investigate façade--floorplan coherence, and support
evaluation of prompt performance.

Historical reference images used to inform prompt refinement and
comparison are separately identified and attributed to their original
sources within the relevant documentation. Author-generated diagrams or
visualisations created using non-generative software are not classified
as AI-generated.

------------------------------------------------------------------------

## Folder Descriptions

### `docs/`

Contains the main written documentation for each prompt-engineering
strategy and experiment. Each file corresponds to a specific prompting
method or case study:

-   `01_structured_chain_of_thought.md`
-   `02_direct_prompting.md`
-   `03_reverse_prompting.md`
-   `04_natural_language_weighting.md`
-   `05_boolean_logic_prompting.md`
-   `06_historical_reference_images.md`
-   `07_historical_reference_images_reverse_prompting.md`
-   `08_template_v1_baseline_outputs.md`
-   `09_template_refinement_case_brunswick.md`
-   `10_template_refinement_case_mill_hill.md`
-   `11_template_refinement_case_saltaire.md`
-   `12_template_v5_regulation_based_interiors.md`

These documents describe:

-   The prompt strategy used
-   Iterative refinements
-   Historical reference images, where applicable
-   Corresponding AI-generated experimental image outputs
-   The use of generated outputs in prompt comparison, refinement, and
    evaluation

Historical reference images are distinguished from AI-generated outputs
and are attributed to their original sources in the relevant
documentation.

------------------------------------------------------------------------

### `images/`

Contains the visual material referenced in the documentation. Images are
grouped into subfolders according to experiment type or prompt strategy:

-   `01_structured_chain/`
-   `02_direct_prompting/`
-   `03_boolean_logic_prompting/`
-   `04_natural_language_weighting/`
-   `05_references/`
-   `06_template_v1_outputs/`
-   `07_template_refinement_outputs/`
-   `08_template_v4_outputs/`
-   `09_isometrics/`
-   `10_template_v5_outputs/`

With the exception of historical reference material contained in the
designated reference folder, the experimental image folders contain
**AI-generated outputs**, including:

-   Façades
-   Floorplans
-   Isometric views
-   Iterative refinement outputs

These AI-generated outputs constitute experimental material used for
visual comparison, prompt refinement, analysis of façade--floorplan
relationships, and evaluation of prompt performance. They should not be
interpreted as documentary or historically verified reconstructions of
the referenced buildings.

The `05_references/` folder contains historical reference material used
for comparison and prompt refinement. These reference images are **not
AI-generated** and are attributed to their original sources in the
accompanying documentation.

------------------------------------------------------------------------

### `results/`

Contains summary and comparison documents derived from the experiments:

-   `results_facade.md`
-   `results_floorplan.md`

These files provide:

-   Collated comparisons of AI-generated experimental outputs
-   Qualitative scoring of architectural accuracy according to key
    attributes

This folder represents analysed experimental outcomes rather than raw
image generation.

------------------------------------------------------------------------

### `templates/`

Contains the prompt templates used throughout experimentation:

-   `template_v1_exterior.md`
-   `template_v1_interior.md`
-   `template_v2_exterior.md`
-   `template_v3_exterior.md`
-   `template_v4_exterior.md`
-   `template_v5_interior.md`

These templates represent the evolution of prompt structure from early
baseline prompts to more constrained and regulation-aware formats. They
were used to support consistency and repeatability across the
image-generation experiments.

------------------------------------------------------------------------

## Purpose of the Repository

This repository serves as:

-   A structured appendix to the associated research paper
-   A record of the prompt-engineering experiments and iterative
    refinement process
-   A visual archive of AI-generated experimental architectural outputs
-   A record of the relationship between prompt configurations and
    corresponding generated outputs
-   A supporting resource for the evaluation and comparison reported in
    the paper
-   A reproducible reference for future work

The repository is intended to provide transparency and traceability
between the prompt-engineering methodology, AI-generated experimental
outputs, historical reference material, and the evaluation reported in
the associated paper.
