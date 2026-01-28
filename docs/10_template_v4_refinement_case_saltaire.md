# Template v4 Regeneration Refinement Case (Saltaire — SS-09)

This case documents a Phase 3 refinement loop using the Saltaire Sunday School historical reference image (SS-09).

The reference image was reverse-prompted into the Template v4 façade format.  
The filled template prompt was then iteratively refined to test and improve architectural coherence against the reference Sunday School image.

**Template version used:**
- Façade template: `../templates/template_v4_exterior.md`

---

## 1) Historical Reference Image (Ground Truth — SS-09)

Reference image from the historical dataset (SS-09).

![SS-09 Reference](../images/references/ss_09.png)

---

## 2) Filled Template Prompt — Iteration 1 (Symmetrical / Neoclassical Revival)

A highly detailed sepia engraving showing the three-quarter front-left elevation of a late 19th-century civic/institutional building designed in the Victorian Classical / Neoclassical Revival architectural style. The image shows the building alone against a neutral, context-free background so that the focus is entirely on the architecture.  
The building has a rectangular, symmetrical massing with a strong horizontal emphasis, expressed through evenly spaced bays and continuous string courses, and is depicted with full accuracy to its real proportions, materials, and form.

**Visible architectural details include:**

- **Roof form:**  
  Low-pitched hipped roof with a pronounced overhanging cornice, classical dentil detailing beneath the eaves, and a small central roof ridge element; no dormers or chimneys visible.

- **Wall materials:**  
  Smooth ashlar stone masonry in a light grey tone, with clearly defined coursing; rusticated stonework at ground-floor level; prominent stone quoins articulating the building corners.

- **Windows:**  
  Tall round-arched windows at ground floor level with pronounced stone voussoirs and keystones; upper floors feature rectangular sash windows with flat stone lintels and projecting sills; windows arranged in strict vertical alignment across floors, forming a regular bay rhythm.

- **Doors:**  
  A centrally placed round-arched main entrance door with heavy stone surround, recessed opening, and paneled timber double doors.

- **Ornamentation:**  
  Strong horizontal string courses separating floors; classical cornice with dentils; shallow pilaster-like vertical divisions between window bays; keystone detailing to arched openings.

- **Façade rhythm:**  
  Evenly spaced multi-bay composition across both visible elevations, maintaining strict symmetry and proportional consistency.

- **Distinctive features:**  
  Pronounced classical cornice line, rusticated base level, arched fenestration at ground floor contrasting with rectangular upper windows, corner emphasis through stone quoins.

Render all materials (stone masonry and carved stone detailing) with accurate texture and detail. The building should appear complete and undistorted, with no perspective exaggeration unless intentionally specified.

**Negative instructions:**  
Exclude all surrounding context (trees, sky, pavement, ground, foliage, shadows, people, cars, signs), and exclude any invented or modern elements not present in the described architecture.

---

## 3) Filled Template Prompt — Iteration 2 (Tightened Roof + Two-Storey + Arches Both Levels)

A highly detailed sepia engraving showing the three-quarter front-left elevation of a late 19th-century civic/institutional building designed in the Victorian Classical / Italianate Neoclassical Revival architectural style. The image shows the building alone against a neutral, context-free background so that the focus is entirely on the architecture.  
The building has a rectangular, two-storey symmetrical massing with a pronounced horizontal emphasis, clearly divided by string courses, and is depicted with full accuracy to its real proportions, materials, and form.

**Visible architectural details include:**

- **Roof form:**  
  Complex low-pitched hipped roof system with multiple stepped roof tiers; a dominant central raised roof block with shallow pitch; wide projecting eaves with strong classical cornices; continuous dentil detailing beneath all eaves; small finial-like ridge elements at roof peaks; no chimneys or dormers.

- **Wall materials:**  
  Light-toned brick or ashlar masonry with smooth, uniform coursing; subtle rustication at ground floor level; clean corner returns without projections; minimal color variation consistent with late 19th-century civic construction.

- **Windows:**  
  - *Ground floor:*  
    Tall, evenly spaced round-arched windows, arranged in paired vertical rhythm; pronounced stone voussoirs and keystones; recessed openings; identical arch height across the façade.  
  - *Upper floor:*  
    Round-arched windows mirroring the ground floor alignment, maintaining exact vertical correspondence; slimmer arch proportions; consistent sill and arch heights across all bays.  
  - Windows are strictly aligned vertically and horizontally, forming a disciplined classical grid.

- **Doors:**  
  A single centrally positioned round-arched main entrance on the front façade; deep recessed arch with heavy masonry surround; tall paneled timber double doors; entrance arch larger and more prominent than window arches.

- **Ornamentation:**  
  Continuous horizontal string courses separating storeys; strong classical cornice with dentils; shallow pilaster-like wall articulation implied through window spacing rather than applied columns; restrained keystone detailing; no excessive carving.

- **Façade rhythm:**  
  Strict multi-bay composition across both visible elevations; equal bay widths; consistent spacing between all openings; symmetry reinforced through repetition of arched fenestration.

- **Distinctive features:**  
  Unified arched window language across both storeys; prominent stepped roof massing rising toward the center; absence of porticos, balconies, or projecting wings; corner expressed purely through masonry return and roof continuity.

Render all materials (brick or stone masonry, carved stone detailing, timber doors, slate or metal roofing) with accurate texture and period-authentic engraving linework. The building should appear complete and undistorted, with no perspective exaggeration unless intentionally specified.

**Negative instructions:**  
Exclude all surrounding context (trees, sky, pavement, ground, foliage, shadows, people, cars, signs), and exclude any invented, modern, or simplified elements not present in the described architecture.

---

## 4) Filled Template Prompt — Iteration 3 (Corner Condition + Explicit Counts (1 Door Assumption))

A highly detailed sepia engraving showing the three-quarter front-left elevation of a late 19th-century civic/institutional building designed in the Victorian Classical / Italianate Neoclassical Revival architectural style. The image shows the building alone against a neutral, context-free background so that the focus is entirely on the architecture.

The building has a rectangular two-storey massing with a disciplined classical hierarchy, not a cubic block, and is depicted with full accuracy to its real proportions, materials, and form. The building occupies a corner condition, with a principal front façade and a longer side elevation, both fully visible.

**Visible architectural details include:**

- **Roof form:**  
  A tiered pavilion-style hipped roof composed of multiple stepped horizontal roof planes; a raised central roof tier sits above the main roof volume; all roof edges terminate in deep overhanging classical cornices with continuous dentil detailing; subtle ridge finials mark roof peaks; no chimneys, dormers, or skylights.

- **Wall materials:**  
  Light-toned brick masonry laid in uniform horizontal courses; smooth wall finish; subtle rusticated brickwork at ground floor level; brick corner returns without quoins; consistent late-19th-century civic construction texture.

- **Windows:**  
  - *Front façade, ground floor:*  
    - Exactly **five** arched openings  
    - A single round-arched **main entrance** positioned slightly left of center  
    - Two paired round-arched windows to the **left** of the entrance  
    - Two paired round-arched windows to the **right** of the entrance  
  - *Front façade, upper floor:*  
    - Exactly **six** round-arched windows  
    - Arranged as **three** evenly spaced paired arches  
    - Arches directly aligned above the ground-floor openings  
  - *Side elevation (both floors):*  
    - A longer rhythmic sequence of tall rectangular sash windows  
    - Windows evenly spaced in a linear grid  
    - **No arched windows** on the side elevation  

  All window openings are vertically aligned floor-to-floor with consistent sill and head heights.

- **Doors:**  
  A single tall round-arched timber entrance door, recessed within a heavy masonry surround; vertically paneled timber double doors; entrance arch taller and wider than window arches.

- **Ornamentation:**  
  Strong horizontal brick string courses separating storeys; pronounced classical cornice beneath the roofline; restrained keystone detailing to arched openings; no columns, porticos, balconies, or applied decoration.

- **Façade rhythm:**  
  The front façade expresses a paired-arch rhythm, while the side elevation expresses a repetitive rectangular sash rhythm, clearly differentiating primary and secondary elevations.

- **Distinctive features:**  
  Corner-sited institutional building; offset entrance; paired arched fenestration on principal façade only; tiered pavilion roof massing; absence of any projecting wings or modern alterations.

Render all materials (brick masonry, carved brick detailing, timber doors, slate or metal roofing) with accurate texture and period-authentic engraving linework. The building should appear complete, proportionally exact, and undistorted, with no perspective exaggeration.

**Negative instructions:**  
Exclude all surrounding context (trees, sky, pavement, ground, foliage, shadows, people, cars, signs), and exclude any invented, modern, or simplified elements not present in the described architecture.

---

## 5) Filled Template Prompt — Iteration 4 (Stepped Massing + Two Doors (Pediment + Pavilion + Long Wing))

A highly detailed sepia engraving showing the three-quarter front-left elevation of a late 19th-century civic/institutional building designed in the Victorian Classical / Italianate Neoclassical Revival architectural style. The image shows the building alone against a neutral, context-free background so that the focus is entirely on the architecture.  
The building has a stepped, multi-volume massing (a taller principal front block plus a projecting right-front pavilion plus a longer rear/right wing), and is depicted with full accuracy to its real proportions, materials, and form.

**Visible architectural details include:**

- **Roof form:**  
  A complex tiered hipped roof composition: the main front block has a low-pitched hipped roof surmounted by a raised central clerestory/monitor roof tier (standing-seam metal look) with small finials; deep overhanging eaves with dentil cornice; the right-front projecting pavilion has its own lower hipped roof that intersects the main roof; the longer rear/right wing continues under a lower hipped roof plane; no chimneys or dormers.

- **Wall materials:**  
  Light-toned brick masonry in uniform courses; smooth planar walls; subtle horizontal banding/string courses; minimal surface ornament beyond cornices and bands; clean corner returns.

- **Windows:**  
  - *Front façade, upper floor (principal block):*  
    A row of round-arched paired windows (paired arches with a thin mullion between each pair), evenly spaced beneath the cornice, plus a single round-arched window near the right edge of the front block close to the corner transition.  
  - *Front façade, ground floor (principal block):*  
    Round-arched paired windows matching the upper rhythm, plus two separate round-arched door openings (see **Doors**). All arches have pronounced voussoirs/arched brick heads and clear recessed reveals.  
  - *Right-front projecting pavilion:*  
    Rectangular sash windows (one on the front face and one on the side face visible), aligned floor-to-floor with flat heads and simple sills.  
  - *Long right/rear wing (side elevation):*  
    A repetitive grid of tall, narrow rectangular sash windows on both floors, evenly spaced in a strict rhythm; **no round arches** on this long wing.

- **Doors:**  
  Two distinct entrance doors on the principal front block, both set in round-arched openings with deep recessed reveals:  
  - **Door 1:** Positioned toward the far left of the front façade (near the left edge); tall paneled timber door.  
  - **Door 2:** Positioned closer to the center-right of the front façade; tall paneled timber door in a slightly larger round arch.  
  Both doors are darker than the masonry and visually prominent.

- **Ornamentation:**  
  Strong classical cornice with dentils along roof eaves; a large triangular pediment on the left portion of the front block with dentil trim under the pediment eave; continuous horizontal string courses separating storeys; restrained keystone/arch emphasis; no columns, porticos, balconies, or modern signage.

- **Façade rhythm:**  
  The principal block uses a paired-arch rhythm (paired round-arched openings), while the projecting pavilion and long wing use rectangular sash rhythms; storey heights remain consistent across volumes.

- **Distinctive features:**  
  Clearly stepped building layout (principal pedimented block + projecting right-front pavilion + long right/rear wing); two arched entrance doors on the principal front block; raised central monitor/clerestory roof tier; absence of any modern alterations.

Render all materials (brick masonry, carved/formed brick arch heads, timber doors, metal or slate roofing) with accurate texture and period-authentic engraving linework. The building should appear complete and undistorted, with no perspective exaggeration unless intentionally specified.

**Negative instructions:**  
Exclude all surrounding context (trees, sky, pavement, ground, foliage, shadows, people, cars, signs), and exclude any invented or modern elements not present in the described architecture.

---

## 6) Filled Template Prompt — Iteration 4 (“Blueprint-Style” Hard Constraints (Do Not Deviate))

A highly detailed sepia engraving showing the three-quarter front-left elevation of a late 19th-century civic/institutional building designed in the Victorian Classical / Italianate Neoclassical Revival architectural style. The image shows the building alone against a neutral, context-free background so that the focus is entirely on the architecture.  
The building has a stepped, multi-volume massing (a taller principal front block plus a projecting right-front pavilion plus a longer rear/right wing), and is depicted with full accuracy to its real proportions, materials, and form.

**Visible architectural details include:**

- **Roof form:**  
  A complex tiered hipped roof composition: the main front block has a low-pitched hipped roof surmounted by a raised central clerestory/monitor roof tier (standing-seam metal look) with small finials; deep overhanging eaves with dentil cornice; the right-front projecting pavilion has its own lower hipped roof that intersects the main roof; the longer rear/right wing continues under a lower hipped roof plane.  
  **No chimneys, no dormers, no skylights, no towers.**

- **Wall materials:**  
  Light-toned brick masonry in uniform courses; smooth planar walls; subtle horizontal banding/string courses; minimal surface ornament beyond cornices and bands; clean corner returns.

- **Windows (LOCKED COUNTS + ARRANGEMENT, DO NOT DEVIATE):**  
  - *Principal front façade, upper floor (taller front block):*  
    Exactly **six** round-arched windows total, arranged as **three paired arched-window groups** (pair–pair–pair), evenly spaced under the cornice. Each pair contains two narrow arched windows separated by a thin mullion. **No single arched window** on this upper front façade.  
  - *Principal front façade, ground floor (taller front block):*  
    Exactly **four** round-arched windows total, arranged as **two paired arched-window groups** (pair–pair) with the same thin mullion logic. These sit **between the two entrance doors**. **No additional** ground-floor arched windows beyond these four.  
  - *Right-front projecting pavilion:*  
    Exactly **one** rectangular sash window per floor on the pavilion’s **front face** (two total), vertically aligned; and exactly **one** rectangular sash window per floor on the pavilion’s **side face** (two total), vertically aligned. **No arched windows** on the pavilion.  
  - *Long rear/right wing (side elevation):*  
    Exactly **eight** tall, narrow rectangular sash windows on the upper floor and exactly **eight** matching rectangular sash windows on the ground floor, evenly spaced and aligned directly above/below each other. **No arched windows** on the long wing.

- **Doors (LOCKED, ONLY THESE TWO DOORS EXIST):**  
  Exactly **two** entrance doors on the principal front façade, both in round-arched openings with recessed reveals and dark paneled timber doors:  
  - **Door 1:** Positioned at the far left end of the front façade (near the left edge), round-arched doorway, dark timber door.  
  - **Door 2:** Positioned to the right of the two paired window groups (closer to center-right of the front façade), round-arched doorway, dark timber door.  
  **No third door. No side doors. No extra arched entrances.**

- **Ornamentation:**  
  Strong classical cornice with dentils along roof eaves; a large triangular pediment on the left portion of the front block with dentil trim under the pediment eave; continuous horizontal string courses separating storeys; restrained arch emphasis.  
  **No columns, no porticos, no balconies, no balustrades.**

- **Façade rhythm:**  
  The principal front block expresses paired-arch groups only (pairs on both floors), interrupted only by the two doors; the pavilion and long wing express a strict rectangular sash rhythm.

- **Distinctive features:**  
  Clearly stepped building layout (principal pedimented block + projecting right-front pavilion + long right/rear wing); two arched entrance doors on the principal front block; raised central monitor/clerestory roof tier; no modern alterations.

Render all materials (brick masonry, formed brick arch heads, timber doors, metal or slate roofing) with accurate texture and period-authentic engraving linework. The building should appear complete and undistorted, with no perspective exaggeration unless intentionally specified.

**Negative instructions:**  
Exclude all surrounding context (trees, sky, pavement, ground, foliage, shadows, people, cars, signs), and exclude any invented, modern, or simplified elements not present in the described architecture. Also exclude stairs, entry steps, platforms, porches, towers, domes, extra doors, extra arches, and any additional windows beyond the specified counts.

---

## 7) Regenerated Outputs

### Iteration 1
![Saltaire Iteration 1](../images/template_refinement_outputs/ss_09_iter01.png)

### Iteration 2
![Saltaire Iteration 2](../images/template_refinement_outputs/ss_09_iter02.png)

### Iteration 3
![Saltaire Iteration 3](../images/template_refinement_outputs/ss_09_iter03.png)

### Iteration 4
![Saltaire Iteration 4](../images/template_refinement_outputs/ss_09_iter04.png)

### Iteration 5
![Saltaire Iteration 5](../images/template_refinement_outputs/ss_09_iter05.png)
