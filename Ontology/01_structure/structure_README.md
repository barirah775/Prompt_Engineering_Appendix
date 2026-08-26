# 01 Structure

This folder documents the tabular structure of the architectural
ontology, its representation in Neo4j, and the simplified ontology data
corresponding to Figures 1--3.

## Master ontology tables

The master ontology is defined by two complementary CSV files that are
used together:

-   `master_nodes.csv` contains the architectural concepts included in
    the ontology.
-   `master_edges.csv` contains the directed semantic relationships
    connecting those concepts.

### `master_nodes.csv`

Each row defines a concept that can appear as a node in the ontology.
The main columns are:

-   **`Id`** --- the unique name used to identify the concept.
-   **`Label`** --- the displayed name of the concept.
-   **`Type`** --- identifies the role of the entry, such as a broader
    group or architectural feature.

The table includes concepts from both exterior/façade and
interior/spatial architectural domains.

### `master_edges.csv`

Each row defines a relationship between two concepts listed in the
ontology. The columns are:

-   **`Source`** --- the concept from which the relationship begins.
-   **`Target`** --- the concept to which the relationship points.
-   **`Type`** --- identifies the relationship as directed.
-   **`Label`** --- describes the semantic meaning of the relationship.

The two master tables therefore complement one another:
`master_nodes.csv` defines the architectural concepts, while
`master_edges.csv` defines how those concepts relate to one another.

For example, `Spatial Organisation` and `Room Type` are concepts
represented in the node table, while the edge table connects them
through the relationship `Spatial Organisation → ORGANISES → Room Type`.

## Neo4j representation

The master node and edge CSV files were imported into **Neo4j** to
represent the ontology as a knowledge graph.

Cypher queries were used to create and match the architectural concept
nodes and to establish the directed relationships recorded in
`master_edges.csv`. In the graph, each node represents an architectural
concept and each connection represents the corresponding semantic
relationship between concepts.

Further Neo4j queries were used to retrieve and examine particular
groups of concepts and relationships. Node colours and graph
arrangements were also adjusted within the Neo4j visualisation to
distinguish architectural domains and make the structure and
dependencies of the ontology easier to interpret.

The Neo4j representation therefore provides a graph-based view of the
same architectural concepts and relationships defined in the master CSV
tables.

## Figure-level ontology data

The figure-level CSV files are simplified and adapted representations of
the broader master ontology. They were created to make the principal
architectural relationships legible in the manuscript figures without
reproducing the full level of detail contained in the master tables.

Relevant concepts and relationships from the master ontology were
selected for each figure and, where necessary, consolidated or
simplified. The resulting relationships were then recorded as
figure-specific CSV edge lists.

These files use the same general relationship structure:

-   **`Source`** --- starting concept.
-   **`Target`** --- connected concept.
-   **`Type`** --- direction of the relationship.
-   **`Label`** --- semantic relationship between the concepts.

The figure-level CSVs are therefore not separate ontologies or direct
copies of the master edge table. They are simplified representations of
the broader ontology structure developed specifically for the
corresponding visualisations.

### Figure 1 --- merged exterior--interior ontology

`figure_1_merged_exterior_interior_ontology.csv` documents the
simplified graph represented in Figure 1.

It combines selected exterior/façade and interior/spatial concepts to
show the broader organisation of the ontology and the dependencies
connecting the two architectural domains.

### Figure 2 --- interior/spatial ontology

`figure_2_interior_spatial_ontology.csv` documents the simplified
interior/spatial graph represented in Figure 2.

It focuses on concepts and relationships associated with spatial
organisation, room type, structure, circulation, openings, and other
interior architectural characteristics. The broader ontology was reduced
and consolidated to retain the relationships required to communicate the
interior/spatial structure clearly.

### Figure 3 --- exterior/façade ontology

`figure_3_exterior_facade_ontology.csv` documents the simplified
exterior/façade graph represented in Figure 3.

It focuses on concepts and relationships associated with exterior form,
massing, structure, materials, openings, roof characteristics,
ornamentation, and related façade features. As with Figure 2, the
broader ontology was simplified to provide a clearer figure-level
representation.

## Relationship between the files

`master_nodes.csv` and `master_edges.csv` together preserve the broader
architectural ontology used in the study. The same data structure was
represented in Neo4j to allow the concepts and semantic relationships to
be explored as a knowledge graph.

The three figure-level CSV files document simplified versions of this
broader ontology, adapted to the specific exterior/façade,
interior/spatial, and merged views presented in Figures 1--3.

Selected ontology concepts and relationships were subsequently
translated into structured linguistic constraints within the
prompt-engineering workflow.
