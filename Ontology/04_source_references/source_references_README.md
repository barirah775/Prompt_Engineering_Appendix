# Source References

This folder contains the source material used to support the development
of the architectural ontology and its use within the prompt-engineering
workflow.

## Source files

-   `UK School Architectural Composition (1).docm` --- architectural and
    historical research describing characteristics of UK school
    architecture.
-   `UK_School_Architecture_Composition (2).xlsx` --- structured
    architectural data covering spatial layout, structure, materials,
    daylight/ventilation, historical drivers, and exemplar buildings.

These documents provided the architectural research basis for
identifying and organising the **classes and relationships** used to
construct the ontology across the exterior/façade and interior/spatial
domains.

## Use in the prompt-engineering workflow

The ontology classes and relationships informed the structure of the initial prompt template, translating the architectural
knowledge into a structured linguistic framework for image generation.

The initial template was subsequently refined for each case study using:

-   the case-study reference images provided in this GitHub
    repository
-   the architectural language generated through reverse prompting of those reference images.
-   negative-prompt constraints developed to reduce persistent visual hallucinations and unwanted architectural features.

The initial constraints were identified from recurring hallucinations observed during the structured chain-of-thought prompting stage described in the paper, prior to development of the ontology-based prompt template. At this stage, the constraints were general rather than tied to a fixed form or case-specific criterion.

Following development of the initial prompt template, these constraints were formally incorporated at the end of the template as negative-prompt instructions. They were then refined for each case study according to the particular recurring hallucinations or unwanted features that needed to be suppressed.




