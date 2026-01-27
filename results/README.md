# Results Evaluation Framework

---

## Results – Exterior Central Façade

To evaluate how closely each generated façade corresponds to its historical reference, a structured attribute-based validation framework was applied. The assessment is organised into four attribute groups, each capturing a different aspect of architectural correspondence.

### Attribute Groups

**1. Door and Window Arrangement**  
- Number of entrance doors  
- Total number of windows  
- Vertical alignment of openings between storeys  

**2. Historical Period**  
- Overall architectural style  
- Form of window and door openings  

**3. Building Composition**  
- Primary wall material  
- Presence and placement of secondary materials (e.g. stone trim or banding)  

**4. Geometry**  
- Overall façade symmetry or asymmetry  
- Principal roof or gable form  

---

### Accuracy Calculation

Each sub-criterion was assessed using a binary scoring system:  
- **1 = match**  
- **0 = mismatch**  
- **NA = not visible or not assessable**

Accuracy for each building was calculated as:

Accuracy = (Number of matched attributes / Number of applicable attributes) × 100


Attributes marked as NA were excluded from the calculation.

---

### Notes

- The framework prioritises countable and architecturally meaningful features to minimise subjective judgement.  
- Image-generation models do not reliably maintain strict numerical or layout constraints (e.g. window counts), as they generate visually plausible patterns rather than explicitly “counting” elements.  
- Final images selected for evaluation were those most consistent across multiple generations of the same prompt.

---

## Results – Interior Ground Floorplan

Interior ground floorplans were evaluated using a structured attribute-based framework focused on spatial logic, usability, and coherence. Unlike the façade assessment, this evaluation assesses internal plausibility rather than direct visual comparison with historical imagery.

### Attribute Groups

**1. Functional Grouping**  
- Logical grouping of primary spaces (e.g. halls, classrooms)  
- Appropriate placement of service and support spaces (e.g. cloak rooms, kitchens, offices, boiler rooms)  

**2. Size Relationships**  
- Primary spaces proportionally larger than secondary or service spaces  
- Room sizes appropriate for their intended function  

**3. Consistency with Exterior Openings**  
- Alignment between major interior rooms and façade window rhythm  
- Correspondence between plan entrances and exterior entrances  

**4. Overall Usability**  
- Clear and readable circulation routes  
- Inclusion of essential support functions  
- Overall plausibility as a functioning Sunday school interior  

---

### Accuracy Calculation

Each sub-condition was scored using a binary system:  
- **1 = condition met**  
- **0 = condition not met**

Where features were absent or unclear, they were treated as mismatches.

Score = (Number of matched attributes / Total applicable attributes) × 100

