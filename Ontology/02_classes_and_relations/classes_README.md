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

  ------------------------------------------------------------------------------------------------------
  Class                    Meaning                 Representative example
  ------------------------ ----------------------- -----------------------------------------------------
  `Exterior`               Top-level class         `Exterior → INCLUDES → Materials`
                           grouping concepts       
                           associated with the     
                           exterior and façade of  
                           the building.           

  `Interior`               Top-level class         `Interior → INCLUDES → Room Type`
                           grouping concepts       
                           associated with the     
                           interior and spatial    
                           organisation of the     
                           building.               

  `Structure`              Represents structural   `Structure → CONSTRAINS → Spatial Organisation`
                           characteristics and     
                           their relationship to   
                           the organisation and    
                           form of the building.   

  `Materials`              Represents the          `Materials → HAS_FEATURE → primary_material`
                           principal materials and 
                           finishes associated     
                           with architectural      
                           elements.               

  `Massing`                Represents the overall  `Massing → ORGANISES → Openings`
                           external form, volume,  
                           height, and composition 
                           of the building.        

  `Roof`                   Represents roof form    `Roof → HAS_FEATURE → pitch`
                           and associated          
                           architectural           
                           characteristics.        

  `Walls`                  Represents wall         `Walls → CONTAINS → Openings`
                           elements and their      
                           relationships to        
                           materials, openings,    
                           and other façade        
                           characteristics.        

  `Openings`               Represents openings     `Openings → HAS_FEATURE → window_shape`
                           within the building     
                           envelope, including     
                           windows and doors and   
                           their positioning.      

  `Ornamentation`          Represents decorative   `Ornamentation → HAS_FEATURE → decorative_elements`
                           architectural elements  
                           and façade detailing.   

  `Room Type`              Represents categories   `Spatial Organisation → ARRANGES → Room Type`
                           of interior rooms and   
                           their functional or     
                           spatial                 
                           characteristics.        

  `Spatial Organisation`   Represents the          `Spatial Organisation → ARRANGES → Room Type`
                           organisation, zoning,   
                           and arrangement of      
                           interior spaces.        

  `Circulation`            Represents movement and `Circulation → CONNECTS → Room Type`
                           connectivity between    
                           interior spaces.        

  `Lighting`               Represents lighting     `Lighting → ILLUMINATES → Room Type`
                           characteristics         
                           associated with         
                           interior spaces.        

  `Primary`                Represents the primary  `Primary → INCLUDES → Classrooms`
                           spatial grouping within 
                           the interior ontology.  

  `Secondary`              Represents the          `Secondary → INCLUDES → WelfareSpaces`
                           secondary spatial       
                           grouping within the     
                           interior ontology.      

  `Classrooms`             Represents classroom    `Classrooms → ADJACENT_TO → Halls`
                           spaces within the       
                           interior spatial        
                           structure.              

  `Halls`                  Represents hall spaces  `Classrooms → ADJACENT_TO → Halls`
                           and their relationship  
                           to other interior       
                           spaces.                 

  `WelfareSpaces`          Represents              `WelfareSpaces → ADJACENT_TO → StorageRooms`
                           welfare-related spaces  
                           within the interior     
                           spatial structure.      

  `StorageRooms`           Represents storage      `WelfareSpaces → ADJACENT_TO → StorageRooms`
                           spaces within the       
                           interior spatial        
                           structure.              

  `Doors`                  Represents door         `Doors → PROVIDE_ACCESS_TO → Primary`
                           openings and their role 
                           in providing access     
                           between spaces.         

  `Windows`                Represents window       `Windows → PROVIDE_LIGHT_TO → Primary`
                           openings and their      
                           relationship to natural 
                           lighting of spaces.     

  `Brickwork`              Represents brickwork as `Walls → CONSTRUCTED_WITH → Brickwork`
                           an architectural        
                           material or             
                           construction            
                           characteristic.         
  ------------------------------------------------------------------------------------------------------

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
