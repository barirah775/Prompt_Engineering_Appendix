# Relations

This folder documents the semantic relationship types used in the
figure-level ontology graphs.

The relation documentation is based on the latest ontology structures
represented in:

-   `figure_1_merged_exterior_interior_ontology.csv` --- merged
    exterior--interior ontology.
-   `figure_2_interior_spatial_ontology.csv` --- interior/spatial
    ontology.
-   `figure_3_exterior_facade_ontology.csv` --- exterior/façade
    ontology.

## Relation structure

Relations describe how architectural concepts are connected within the
ontology. In the figure-level CSV files:

-   `Source` identifies the concept from which the relationship begins.
-   `Target` identifies the concept to which the relationship points.
-   `Type` records the relationship as directed.
-   `Label` identifies the semantic relation connecting the two
    concepts.

For example, `Structure → CONSTRAINS → Spatial Organisation` indicates a
directed relationship in which structural characteristics constrain
spatial organisation.

## Relation types

- **`INCLUDES`**
  - Indicates that a broader architectural concept contains or comprises the target concept.
  - **Representative example:** `Exterior → INCLUDES → Materials`
- **`CONSTRAINS`**
  - Indicates that one architectural concept places limits on or influences the organisation of another.
  - **Representative example:** `Structure → CONSTRAINS → Spatial Organisation`
- **`DEFINES`**
  - Indicates that one concept establishes or determines the character or form of another.
  - **Representative example:** `Structure → DEFINES → Walls`
- **`DECORATES`**
  - Indicates that an ornamental element is applied to or visually modifies another architectural element.
  - **Representative example:** `Ornamentation → DECORATES → Walls`
- **`FINISHED_WITH`**
  - Indicates the material or finish applied to an architectural element.
  - **Representative example:** `Walls → FINISHED_WITH → Materials`
- **`CONTRIBUTES_TO`**
  - Indicates that one architectural element contributes to the formation or character of another.
  - **Representative example:** `Roof → CONTRIBUTES_TO → Massing`
- **`CONTAINS`**
  - Indicates that an architectural element physically contains or accommodates another element.
  - **Representative example:** `Walls → CONTAINS → Openings`
- **`CONSTRUCTED_WITH`**
  - Indicates the material or construction element used to form another architectural element.
  - **Representative example:** `Walls → CONSTRUCTED_WITH → Brickwork`
- **`CONNECTS`**
  - Indicates that an element provides a connection between architectural spaces or concepts.
  - **Representative example:** `Circulation → CONNECTS → Room Type`
- **`PROVIDE_ACCESS_TO`**
  - Indicates that an opening or element provides access to a spatial category.
  - **Representative example:** `Doors → PROVIDE_ACCESS_TO → Primary`
- **`PROVIDE_LIGHT_TO`**
  - Indicates that an opening provides natural light to a spatial category.
  - **Representative example:** `Windows → PROVIDE_LIGHT_TO → Primary`
- **`USES`**
  - Indicates that an architectural concept makes use of the target element or material.
  - **Representative example:** `Exterior → USES → Materials`
- **`DETERMINES`**
  - Indicates that one architectural concept determines the organisation or behaviour of another.
  - **Representative example:** `Spatial Organisation → DETERMINES → Circulation`
- **`REQUIRES`**
  - Indicates that a concept depends on or requires the presence of the target element.
  - **Representative example:** `Room Type → REQUIRES → Lighting`
- **`SUPPORTS`**
  - Indicates a supporting structural, spatial, or functional relationship.
  - **Representative example:** `Structure → SUPPORTS → Room Type`
- **`ADJACENT_TO`**
  - Indicates that two spatial elements are positioned next to or in close relation to one another.
  - **Representative example:** `Classrooms → ADJACENT_TO → Halls`
- **`HAS_FEATURE`**
  - Connects an architectural concept to a descriptive feature or attribute used to characterise it.
  - **Representative example:** `Roof → HAS_FEATURE → pitch`
- **`DEFINES_LIMITS_OF`**
  - Indicates that one architectural concept establishes physical or spatial limits for another.
  - **Representative example:** `Structure → DEFINES_LIMITS_OF → Spatial Organisation`
- **`ARRANGES`**
  - Indicates that spatial organisation determines the arrangement of a room type.
  - **Representative example:** `Spatial Organisation → ARRANGES → Room Type`
- **`IS_ARRANGED_BY`**
  - Expresses the inverse of `ARRANGES`, indicating that a room type is arranged by spatial organisation.
  - **Representative example:** `Room Type → IS_ARRANGED_BY → Spatial Organisation`
- **`FOLLOWS`**
  - Indicates that circulation follows or responds to spatial organisation.
  - **Representative example:** `Circulation → FOLLOWS → Spatial Organisation`
- **`IS_CONNECTED_TO`**
  - Indicates that one architectural or spatial concept is connected to another.
  - **Representative example:** `Room Type → IS_CONNECTED_TO → Circulation`
- **`ILLUMINATES`**
  - Indicates that lighting provides illumination to an interior spatial concept.
  - **Representative example:** `Lighting → ILLUMINATES → Room Type`
- **`IS_CONSTRAINED_BY`**
  - Expresses the inverse of `CONSTRAINS`, indicating that a concept is constrained by another.
  - **Representative example:** `Spatial Organisation → IS_CONSTRAINED_BY → Structure`
- **`CONTRIBUTES`**
  - Indicates that one architectural element contributes to the form or character of another.
  - **Representative example:** `Roof → CONTRIBUTES → Massing`
- **`INFLUENCES`**
  - Indicates that one architectural element affects the form or configuration of another.
  - **Representative example:** `Structure → INFLUENCES → Massing`
- **`ARE_PLACED_IN`**
  - Indicates the architectural element within which openings are positioned.
  - **Representative example:** `Openings → ARE_PLACED_IN → Walls`
- **`ORGANISES`**
  - Indicates that one architectural concept structures the arrangement of another.
  - **Representative example:** `Massing → ORGANISES → Openings`
- **`APPLIES_TO`**
  - Indicates the architectural element to which ornamentation is applied.
  - **Representative example:** `Ornamentation → APPLIES_TO → Walls`
- **`MAY_INCLUDE`**
  - Indicates that a broader architectural concept may optionally contain the target concept.
  - **Representative example:** `Ornamentation → MAY_INCLUDE → decorative_elements`


## Coverage across the ontology figures

**Figure 1 --- merged exterior--interior ontology** contains relations
connecting selected exterior/façade and interior/spatial concepts.

**Figure 2 --- interior/spatial ontology** contains relations describing
internal spatial organisation, room types, circulation, lighting,
structural constraints, and related interior concepts.

**Figure 3 --- exterior/façade ontology** contains relations describing
massing, materials, roof, walls, openings, ornamentation, structure, and
related exterior concepts.

The same relation type can occur multiple times across the ontology. The
examples above provide one representative use of each relation to
clarify its meaning; they are not intended to list every occurrence. The
corresponding figure-level CSV files contain the complete set of
directed source--relation--target connections represented in Figures
1--3.
