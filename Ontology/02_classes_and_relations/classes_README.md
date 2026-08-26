# Classes

This folder documents the architectural classes and principal concepts
represented in the figure-level ontology graphs used in the study.

The class documentation is based on the latest ontology structures
represented in:

-   `figure_1_merged_exterior_interior_ontology.csv` --- merged
    exterior--interior ontology.
-   `figure_2_interior_spatial_ontology.csv` --- interior/spatial
    ontology.
-   `figure_3_exterior_facade_ontology.csv` --- exterior/façade
    ontology.

## Architectural classes

Classes represent the principal architectural concepts organised within
the ontology. They include broad architectural domains, such as
`Exterior` and `Interior`, as well as more specific concepts describing
building elements, spatial organisation, and architectural
characteristics.

The table below defines the principal classes used across the three
figure-level ontology graphs. One representative relationship is
included to show how each class is used. The complete set of
relationships is provided in the corresponding figure-level CSV files.

- **`Exterior`**
  - Top-level class grouping concepts associated with the exterior and façade of the building.
  - **Representative example:** `Exterior → INCLUDES → Materials`
- **`Interior`**
  - Top-level class grouping concepts associated with the interior and spatial organisation of the building.
  - **Representative example:** `Interior → INCLUDES → Room Type`
- **`Structure`**
  - Represents structural characteristics and their relationship to the organisation and form of the building.
  - **Representative example:** `Structure → CONSTRAINS → Spatial Organisation`
- **`Materials`**
  - Represents the principal materials and finishes associated with architectural elements.
  - **Representative example:** `Materials → HAS_FEATURE → primary_material`
- **`Massing`**
  - Represents the overall external form, volume, height, and composition of the building.
  - **Representative example:** `Massing → ORGANISES → Openings`
- **`Roof`**
  - Represents roof form and associated architectural characteristics.
  - **Representative example:** `Roof → HAS_FEATURE → pitch`
- **`Walls`**
  - Represents wall elements and their relationships to materials, openings, and other façade characteristics.
  - **Representative example:** `Walls → CONTAINS → Openings`
- **`Openings`**
  - Represents openings within the building envelope, including windows and doors and their positioning.
  - **Representative example:** `Openings → HAS_FEATURE → window_shape`
- **`Ornamentation`**
  - Represents decorative architectural elements and façade detailing.
  - **Representative example:** `Ornamentation → HAS_FEATURE → decorative_elements`
- **`Room Type`**
  - Represents categories of interior rooms and their functional or spatial characteristics.
  - **Representative example:** `Spatial Organisation → ARRANGES → Room Type`
- **`Spatial Organisation`**
  - Represents the organisation, zoning, and arrangement of interior spaces.
  - **Representative example:** `Spatial Organisation → ARRANGES → Room Type`
- **`Circulation`**
  - Represents movement and connectivity between interior spaces.
  - **Representative example:** `Circulation → CONNECTS → Room Type`
- **`Lighting`**
  - Represents lighting characteristics associated with interior spaces.
  - **Representative example:** `Lighting → ILLUMINATES → Room Type`
- **`Primary`**
  - Represents the primary spatial grouping within the interior ontology.
  - **Representative example:** `Primary → INCLUDES → Classrooms`
- **`Secondary`**
  - Represents the secondary spatial grouping within the interior ontology.
  - **Representative example:** `Secondary → INCLUDES → WelfareSpaces`
- **`Classrooms`**
  - Represents classroom spaces within the interior spatial structure.
  - **Representative example:** `Classrooms → ADJACENT_TO → Halls`
- **`Halls`**
  - Represents hall spaces and their relationship to other interior spaces.
  - **Representative example:** `Classrooms → ADJACENT_TO → Halls`
- **`WelfareSpaces`**
  - Represents welfare-related spaces within the interior spatial structure.
  - **Representative example:** `WelfareSpaces → ADJACENT_TO → StorageRooms`
- **`StorageRooms`**
  - Represents storage spaces within the interior spatial structure.
  - **Representative example:** `WelfareSpaces → ADJACENT_TO → StorageRooms`
- **`Doors`**
  - Represents door openings and their role in providing access between spaces.
  - **Representative example:** `Doors → PROVIDE_ACCESS_TO → Primary`
- **`Windows`**
  - Represents window openings and their relationship to natural lighting of spaces.
  - **Representative example:** `Windows → PROVIDE_LIGHT_TO → Primary`
- **`Brickwork`**
  - Represents brickwork as an architectural material or construction characteristic.
  - **Representative example:** `Walls → CONSTRUCTED_WITH → Brickwork`


## Coverage across the ontology figures

**Figure 1 --- merged exterior--interior ontology** combines selected
classes from both domains to show the overall architectural ontology and
relationships between exterior/façade and interior/spatial
characteristics.

**Figure 2 --- interior/spatial ontology** focuses on classes associated
with internal spatial characteristics, including concepts such as
`Room Type`, `Spatial Organisation`, `Circulation`, `Lighting`, and
`Structure`.

**Figure 3 --- exterior/façade ontology** focuses on classes associated
with external architectural characteristics, including concepts such as
`Massing`, `Materials`, `Roof`, `Walls`, `Openings`, `Ornamentation`,
and `Structure`.

The representative examples in this README illustrate how individual
classes occur within the ontology; they do not reproduce every
connection involving each class. The corresponding figure-level CSV
files provide the complete set of source--relation--target relationships
represented in each graph.
