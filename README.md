# Prompt Engineering Appendix

This repository contains the full appendix for our paper "Ontology-Guided Prompt Engineering for contextually accurate Generative AI in Heritage Building Information Modelling". It documents different prompting methods, templates, and experimental results using structured markdown files and supporting image outputs.

---
## Folder Descriptions

### `docs/`

Contains the main written documentation for each prompt engineering strategy and experiment.  
Each file corresponds to a specific prompting method or case study:

- `01_structured_chain_of_thought.md`  
- `02_direct_prompting.md`  
- `03_reverse_prompting.md`  
- `04_historical_reference_images.md`  
- `05_historical_reference_images_reverse_prompting.md`  
- `06_template_v1_baseline_outputs.md`  
- `07_boolean_logic_prompting.md`  
- `08_template_refinement_case_brunswick.md`  
- `09_template_refinement_case_mill_hill.md`  
- `10_template_refinement_case_saltaire.md`  
- `11_template_v5_regulation_based_interiors.md`  

These documents describe:
- The prompt strategy used 
- Iterative refinements  
- References to historical building images and their corresponding generated generated image outputs  

---

### `images/`

Contains all generated image outputs referenced in the documentation.  
Images are grouped into subfolders according to experiment type or prompt strategy:

- `01_structured_chain/`  
- `02_direct_prompting/`  
- `03_boolean_logic_prompting/`  
- `04_natural_language_weighting/`  
- `05_references/`  
- `06_template_v1_outputs/` 
- `07_template_refinement_outputs/`  
- `08_template_v4_outputs/`  
- `09_isometrics/`   
- `10_template_v5_outputs/` 
  
These folders contain generated:
- Facades  
- Floorplans  
- Isometric views  
- Iterative refinement outputs  

They are used for visual comparison and evaluation of prompt performance.

---

### `results/`

Contains summary and comparison documents derived from the experiments:

- `results_facade.md`  
- `results_floorplan.md`  

These files provide:
- Collated visual comparisons  
- Qualitative scoring of architectural accuracy according to key attributes 

This folder represents analysed outcomes rather than raw generation.

---

### `templates/`

Contains the prompt templates used throughout experimentation:

- `template_v1_exterior.md`  
- `template_v1_interior.md`  
- `template_v2_exterior.md`  
- `template_v3_exterior.md`  
- `template_v4_exterior.md`  
- `template_v5_interior.md`  

These templates represent the evolution of prompt structure from early baseline prompts to more constrained and regulation-aware formats. They were used to ensure consistency and repeatability across image generation experiments.

---

## Purpose of the Repository

This repository serves as:

- A structured appendix to the main project report  
- A record of prompt engineering experiments  
- A visual archive of generated architectural outputs  
- A reproducible reference for future work  

---



