# Ontological Mapping

This folder documents how the architectural ontology was translated into
the **initial prompt templates (Template V1)**.

-   **Figure 2 --- Interior/Spatial Ontology** informed
    `template_v1_interior.md`.
-   **Figure 3 --- Exterior/Façade Ontology** informed
    `template_v1_exterior.md`.
-   **Figure 1 --- Merged Exterior--Interior Ontology** established the
    wider connections between the two architectural domains.

The ontology classes identified the architectural information to be
included in the prompts, while the relationships between these classes
informed how this information was connected and ordered.

------------------------------------------------------------------------

## Figure 2 --- Interior/Spatial Ontology → Template V1 Interior

Figure 2 identifies the main interior/spatial concepts used to structure
the initial floorplan prompt:

-   `Structure`
-   `Spatial Organisation`
-   `Room Type`
-   `Circulation`
-   `Lighting`

### Template V1 --- Interior mapping

  -------------------------------------------------------------------------
  Template component      Template content        Ontology mapping
  ----------------------- ----------------------- -------------------------
  **Key Opening**         Orthographic            Establishes the
                          architectural floorplan `Interior` domain and
                                                  floorplan representation.

  **Storey                e.g. single storey      `Structure` and
  Specification**                                 `Spatial Organisation`

  **Elevation /           e.g. front elevation,   Representation of the
  Perspective             top-down                interior and its
  Specification**                                 `Spatial Organisation`

  **Scale**               1:100                   Supports consistent
                                                  representation of
                                                  structural and spatial
                                                  information.

  **Time Period**         Medieval--Georgian      Provides the historical
                          (pre-1830s)             context for the
                                                  architectural
                                                  characteristics specified
                                                  through the ontology.

  **Representation        Short school +          `Room Type` and
  Scope**                 classroom description   `Spatial Organisation`

  **Structure**           Internal/external wall  `Structure` and its
                          dimensions, placement   relationship with
                          logic, brick or stone   `Spatial Organisation`
                          construction            

  **Further Detail**      Classrooms, corridors,  `Spatial Organisation`,
                          central halls,          `Room Type`, and
                          vestibules and stair    `Circulation`
                          positioning             

  **Additional            Staircases, porches,    Additional spatial,
  Architectural           vestibules, apses and   structural and
  Elements**              galleries               circulation elements

  **Conditions /          Accurate doors/windows, Controls the
  Controls**              symmetry, spacing,      representation of the
                          drawing style, scale    architectural and spatial
                          and no text/labels      information specified
                                                  above.
  -------------------------------------------------------------------------

### Relationship mapping

The ontology relationships determine how these classes are connected
within the prompt rather than treating them as independent architectural
features. For example:

-   `Structure` constrains `Spatial Organisation`;
-   `Spatial Organisation` arranges `Room Type`;
-   `Circulation` connects room types and follows the spatial
    organisation; and
-   `Lighting` relates to the organisation and use of interior spaces.

These dependencies are reflected in the template order, where structural
information is established before the more detailed description of
spatial organisation, room arrangement, circulation, and additional
elements.

------------------------------------------------------------------------

## Figure 3 --- Exterior/Façade Ontology → Template V1 Exterior

Figure 3 identifies the main exterior/façade concepts used to structure
the initial elevation prompt:

-   `Massing`
-   `Structure`
-   `Materials`
-   `Walls`
-   `Openings`
-   `Roof`
-   `Ornamentation`

### Template V1 --- Exterior mapping

  -----------------------------------------------------------------------
  Template component      Template content        Ontology mapping
  ----------------------- ----------------------- -----------------------
  **Key Opening Phrase**  Realistic orthographic  Establishes the
                          elevation               `Exterior` domain and
                                                  elevation
                                                  representation.

  **Elevation             e.g. front elevation    Establishes the façade
  Specification**                                 view through which the
                                                  exterior classes are
                                                  represented.

  **Time Period**         Corresponding to the    Provides the historical
                          previously generated    context and maintains
                          floorplan               consistency with the
                                                  interior
                                                  representation.

  **Central Façade        Façade composition,     `Massing`, `Openings`,
  Description**           window style, door      `Walls`,
                          style and architectural `Ornamentation`, and
                          period                  `Roof` where relevant

  **Structure**           Structural features     `Structure`, `Walls`,
                          such as brickwork and   and associated
                          stone dressings         construction
                                                  characteristics

  **Composition**         Material palette used   `Materials` and its
                          for construction        relationships with the
                                                  exterior elements

  **Conditions / Negative Symmetry, window        Controls the
  Prompting**             rhythm, daylight,       representation of
                          orthographic            façade composition,
                          projection, realistic   openings and materials.
                          materials and no        
                          people/text             

  **Optional Example      Example building with   Provides additional
  Reference**             the required            architectural reference
                          architectural           where required.
                          characteristics         
  -----------------------------------------------------------------------

### Relationship mapping

The exterior ontology relationships similarly determine how the façade
information is combined within the prompt. For example:

-   `Massing` organises `Openings`;
-   `Walls` contain `Openings`;
-   `Walls` are constructed or finished with `Materials`;
-   `Structure` influences exterior form;
-   `Ornamentation` applies to façade elements; and
-   `Roof` contributes to `Massing`.

These dependencies are reflected in the template order, where the
overall façade composition is established before its structural,
material, and detailed architectural characteristics are specified.
