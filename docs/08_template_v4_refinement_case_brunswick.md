# Template v4 Regeneration Refinement Case (Brunswick — SS-05)

This case documents a Phase 3 refinement loop using the Brunswick Methodist Sunday School historical reference image (SS-05).

The reference image was reverse-prompted into the Template v4 façade format.  
The filled template prompt was then iteratively refined to test and improve architectural coherence against the reference Sunday School image.

**Template version used:**
- Façade template: `../templates/template_v4_exterior.md`

---

## 1) Historical Reference Image (Ground Truth — SS-05)

Reference image from the historical dataset (SS-05).

![MH-02 Reference — SS-05](../images/references/ss_05.png)

---

## 2) Filled Template Prompt — Iteration 0 (Baseline / Under-Specified)

A highly detailed photorealistic architectural elevation rendering showing the front elevation of a late-19th-century institutional building (Victorian civic / educational building) designed in the Victorian Gothic Revival style. The image shows the building alone against a neutral, context-free background so that the focus is entirely on the architecture.

The building has a strongly symmetrical façade with a central projecting bay and is depicted with full accuracy to its real proportions, materials, and form.

**Visible architectural details include:**

- **Roof form:**  
  Steeply pitched gabled roof with slate covering, a dominant central gable, decorative stone coping, small ornamental finials at gable peaks, and modest ridge detailing; no chimneys visible on the primary façade.

- **Wall materials:**  
  Deep red brick masonry laid in regular courses, contrasted with pale stone dressings and lintels, stone string courses dividing storeys, and stone detailing around openings.

- **Windows:**  
  Vertically aligned arched windows arranged symmetrically across the façade; ground-floor windows are tall with rounded arches and stone voussoirs; upper-floor windows are smaller but similarly arched; a prominent circular oculus window is set within the central gable.

- **Doors:**  
  Central arched entrance door set within a stone surround, featuring a rounded arch head and dark timber double doors.

- **Ornamentation:**  
  Stone string courses, arched stone hood moulds, decorative brickwork around arches.

- **Façade rhythm:**  
  Five-bay symmetrical composition with a dominant central bay.

- **Distinctive features:**  
  Central gabled projection with circular oculus window.

Render all materials (brick, stone, slate, timber, metal) with accurate texture and detail.

**Negative instructions:**  
Exclude all surrounding context and exclude any invented or modern elements.

---

## 3) Filled Template Prompt — Iteration 1 (Quantified Openings)

A highly detailed photorealistic architectural elevation rendering showing the front elevation of a late-19th-century institutional building designed in the Victorian Gothic Revival / Victorian Romanesque-influenced brick civic style. The image shows the building alone against a neutral, context-free background so that the focus is entirely on the architecture.

The building has a mostly symmetrical two-storey façade with a dominant central gabled composition and is depicted with full accuracy to its real proportions, materials, and form. A lower, plainer brick side wing is attached on the far left, set slightly back from the main façade.

**Visible architectural details include:**

- **Roof form:**  
  Broad front-facing gable with steep pitch; dark slate roof; deep bracketed eaves; finials at gable corners and apex.

- **Wall materials:**  
  Dark red brick with pale stone banding and trim; brick arches over openings; raised plinth.

- **Windows:**  
  - *Upper floor:* Four tall arched windows arranged **1–2–1**  
  - *Ground floor (centre):* Two smaller arched windows arranged as a pair  
  - *Gable:* One circular oculus window above the paired upper windows

- **Doors:**  
  Two arched entrance doors, one left and one right, each with dark timber double doors.

- **Ornamentation:**  
  Concentric brick arches framing the central gable; stone string courses.

- **Façade rhythm:**  
  Three-part composition (left bay, central gabled bay, right bay).

- **Distinctive features:**  
  Dominant central gable with oculus; paired central windows; two arched entrances.

Render all materials (brick, stone, slate, timber, metal) with accurate texture and detail.

**Negative instructions:**  
Exclude all surrounding context and exclude any invented or modern elements.

---

## 4) Filled Template Prompt — Iteration 2 (Structurally Locked)

A highly detailed photorealistic architectural elevation rendering showing the front elevation of a late-19th-century institutional building designed in the Victorian Gothic Revival / Victorian Romanesque-influenced brick civic style. The image shows the building alone against a neutral, context-free background so that the focus is entirely on the architecture.

The building has a mostly symmetrical two-storey façade with a dominant central gabled composition and is depicted with full accuracy to its real proportions, materials, and form. A lower, plainer brick side wing is attached on the far left, set slightly back from the main façade.

**Visible architectural details include:**

- **Roof form:**  
  Steep front-facing gable with slate roof; deep bracketed eaves; finials at gable corners and apex.

- **Wall materials:**  
  Dark red brick with pale stone banding; brick arches; raised plinth.

- **Windows (exact arrangement):**  
  - *Upper floor:* **Four** arched windows arranged **1–2–1**  
  - *Ground floor (centre):* **Two** smaller arched windows as a paired set  
  - *Gable:* **One** circular oculus window centred above the paired upper windows  

  The paired upper windows must align directly above the paired lower windows.

- **Doors:**  
  **Two** arched entrance doors (left and right), each with dark timber double doors.

- **Ornamentation:**  
  Concentric brick arches framing the central gable; stone string courses.

- **Façade rhythm:**  
  Left bay, central gabled bay, right bay.

- **Distinctive features:**  
  Central gable with oculus; paired windows; two entrances; side wing on far left.

Render all materials (brick, stone, slate, timber, metal) with accurate texture and detail.

**Negative instructions:**  
Exclude all surrounding context and exclude any invented or modern elements.  
Specifically exclude any third window beneath the oculus.

---

## 5) Regenerated Outputs

### Iteration 0
![Brunswick Iteration 0](../images/template_refinement_outputs/ss_05_iter01.png)

### Iteration 1
![Brunswick Iteration 1](../images/template_refinement_outputs/ss_05_iter02.png)

### Iteration 2
![Brunswick Iteration 2](../images/template_refinement_outputs/ss_05_iter03.png)
