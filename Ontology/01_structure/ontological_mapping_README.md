# Ontological Mapping

This folder documents how the architectural ontology was translated into the **initial prompt templates (Template V1)**.

- **Figure 2 — Interior/Spatial Ontology** informed `template_v1_interior.md`.
- **Figure 3 — Exterior/Façade Ontology** informed `template_v1_exterior.md`.
- **Figure 1 — Merged Exterior–Interior Ontology** established the wider connections between the two architectural domains.

The ontology classes identified the architectural information to be included in the prompts, while the relationships between these classes informed how this information was connected and ordered.

---

## Figure 2 — Interior/Spatial Ontology → Template V1 Interior

Figure 2 identifies the main interior/spatial concepts used to structure the initial floorplan prompt:

- `Structure`
- `Spatial Organisation`
- `Room Type`
- `Circulation`
- `Lighting`

### Template V1 — Interior mapping

**Key Opening**

Orthographic architectural floorplan.

**Ontology mapping:** Establishes the `Interior` domain and floorplan representation.

**Storey Specification**

e.g. single storey.

**Ontology mapping:** `Structure` and `Spatial Organisation`.

**Elevation / Perspective Specification**

e.g. front elevation, top-down.

**Ontology mapping:** Representation of the interior and its `Spatial Organisation`.

**Scale**

1:100.

**Ontology mapping:** Supports consistent representation of structural and spatial information.

**Time Period**

Medieval–Georgian (pre-1830s).

**Ontology mapping:** Provides the historical context for the architectural characteristics specified through the ontology.

**Representation Scope**

Short school + classroom description.

**Ontology mapping:** `Room Type` and `Spatial Organisation`.

**Structure**

Internal/external wall dimensions, placement logic, brick or stone construction.

**Ontology mapping:** `Structure` and its relationship with `Spatial Organisation`.

**Further Detail**

Classrooms, corridors, central halls, vestibules and stair positioning.

**Ontology mapping:** `Spatial Organisation`, `Room Type`, and `Circulation`.

**Additional Architectural Elements**

Staircases, porches, vestibules, apses and galleries.

**Ontology mapping:** Additional spatial, structural and circulation elements.

**Conditions / Controls**

Accurate doors/windows, symmetry, spacing, drawing style, scale and no text/labels.

**Ontology mapping:** Controls the representation of the architectural and spatial information specified above.

### Relationship mapping

The ontology relationships determine how these classes are connected within the prompt rather than treating them as independent architectural features. For example:

- `Structure` constrains `Spatial Organisation`;
- `Spatial Organisation` arranges `Room Type`;
- `Circulation` connects room types and follows the spatial organisation; and
- `Lighting` relates to the organisation and use of interior spaces.

These dependencies are reflected in the template order, where structural information is established before the more detailed description of spatial organisation, room arrangement, circulation, and additional elements.

---

## Figure 3 — Exterior/Façade Ontology → Template V1 Exterior

Figure 3 identifies the main exterior/façade concepts used to structure the initial elevation prompt:

- `Massing`
- `Structure`
- `Materials`
- `Walls`
- `Openings`
- `Roof`
- `Ornamentation`

### Template V1 — Exterior mapping

**Key Opening Phrase**

Realistic orthographic elevation.

**Ontology mapping:** Establishes the `Exterior` domain and elevation representation.

**Elevation Specification**

e.g. front elevation.

**Ontology mapping:** Establishes the façade view through which the exterior classes are represented.

**Time Period**

Corresponding to the previously generated floorplan.

**Ontology mapping:** Provides the historical context and maintains consistency with the interior representation.

**Central Façade Description**

Façade composition, window style, door style and architectural period.

**Ontology mapping:** `Massing`, `Openings`, `Walls`, `Ornamentation`, and `Roof` where relevant.

**Structure**

Structural features such as brickwork and stone dressings.

**Ontology mapping:** `Structure`, `Walls`, and associated construction characteristics.

**Composition**

Material palette used for construction.

**Ontology mapping:** `Materials` and its relationships with the exterior elements.

**Conditions / Negative Prompting**

Symmetry, window rhythm, daylight, orthographic projection, realistic materials and no people/text.

**Ontology mapping:** Controls the representation of façade composition, openings and materials.

**Optional Example Reference**

Example building with the required architectural characteristics.

**Ontology mapping:** Provides additional architectural reference where required.

### Relationship mapping

The exterior ontology relationships similarly determine how the façade information is combined within the prompt. For example:

- `Massing` organises `Openings`;
- `Walls` contain `Openings`;
- `Walls` are constructed or finished with `Materials`;
- `Structure` influences exterior form;
- `Ornamentation` applies to façade elements; and
- `Roof` contributes to `Massing`.

These dependencies are reflected in the template order, where the overall façade composition is established before its structural, material, and detailed architectural characteristics are specified.
