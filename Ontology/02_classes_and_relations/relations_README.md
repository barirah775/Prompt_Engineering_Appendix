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

  --------------------------------------------------------------------------------------------------------
  Relation                Meaning                 Representative example
  ----------------------- ----------------------- --------------------------------------------------------
  `INCLUDES`              Indicates that a        `Exterior → INCLUDES → Materials`
                          broader architectural   
                          concept contains or     
                          comprises the target    
                          concept.                

  `CONSTRAINS`            Indicates that one      `Structure → CONSTRAINS → Spatial Organisation`
                          architectural concept   
                          places limits on or     
                          influences the          
                          organisation of         
                          another.                

  `DEFINES`               Indicates that one      `Structure → DEFINES → Walls`
                          concept establishes or  
                          determines the          
                          character or form of    
                          another.                

  `DECORATES`             Indicates that an       `Ornamentation → DECORATES → Walls`
                          ornamental element is   
                          applied to or visually  
                          modifies another        
                          architectural element.  

  `FINISHED_WITH`         Indicates the material  `Walls → FINISHED_WITH → Materials`
                          or finish applied to an 
                          architectural element.  

  `CONTRIBUTES_TO`        Indicates that one      `Roof → CONTRIBUTES_TO → Massing`
                          architectural element   
                          contributes to the      
                          formation or character  
                          of another.             

  `CONTAINS`              Indicates that an       `Walls → CONTAINS → Openings`
                          architectural element   
                          physically contains or  
                          accommodates another    
                          element.                

  `CONSTRUCTED_WITH`      Indicates the material  `Walls → CONSTRUCTED_WITH → Brickwork`
                          or construction element 
                          used to form another    
                          architectural element.  

  `CONNECTS`              Indicates that an       `Circulation → CONNECTS → Room Type`
                          element provides a      
                          connection between      
                          architectural spaces or 
                          concepts.               

  `PROVIDE_ACCESS_TO`     Indicates that an       `Doors → PROVIDE_ACCESS_TO → Primary`
                          opening or element      
                          provides access to a    
                          spatial category.       

  `PROVIDE_LIGHT_TO`      Indicates that an       `Windows → PROVIDE_LIGHT_TO → Primary`
                          opening provides        
                          natural light to a      
                          spatial category.       

  `USES`                  Indicates that an       `Exterior → USES → Materials`
                          architectural concept   
                          makes use of the target 
                          element or material.    

  `DETERMINES`            Indicates that one      `Spatial Organisation → DETERMINES → Circulation`
                          architectural concept   
                          determines the          
                          organisation or         
                          behaviour of another.   

  `REQUIRES`              Indicates that a        `Room Type → REQUIRES → Lighting`
                          concept depends on or   
                          requires the presence   
                          of the target element.  

  `SUPPORTS`              Indicates a supporting  `Structure → SUPPORTS → Room Type`
                          structural, spatial, or 
                          functional              
                          relationship.           

  `ADJACENT_TO`           Indicates that two      `Classrooms → ADJACENT_TO → Halls`
                          spatial elements are    
                          positioned next to or   
                          in close relation to    
                          one another.            

  `HAS_FEATURE`           Connects an             `Roof → HAS_FEATURE → pitch`
                          architectural concept   
                          to a descriptive        
                          feature or attribute    
                          used to characterise    
                          it.                     

  `DEFINES_LIMITS_OF`     Indicates that one      `Structure → DEFINES_LIMITS_OF → Spatial Organisation`
                          architectural concept   
                          establishes physical or 
                          spatial limits for      
                          another.                

  `ARRANGES`              Indicates that spatial  `Spatial Organisation → ARRANGES → Room Type`
                          organisation determines 
                          the arrangement of a    
                          room type.              

  `IS_ARRANGED_BY`        Expresses the inverse   `Room Type → IS_ARRANGED_BY → Spatial Organisation`
                          of `ARRANGES`,          
                          indicating that a room  
                          type is arranged by     
                          spatial organisation.   

  `FOLLOWS`               Indicates that          `Circulation → FOLLOWS → Spatial Organisation`
                          circulation follows or  
                          responds to spatial     
                          organisation.           

  `IS_CONNECTED_TO`       Indicates that one      `Room Type → IS_CONNECTED_TO → Circulation`
                          architectural or        
                          spatial concept is      
                          connected to another.   

  `ILLUMINATES`           Indicates that lighting `Lighting → ILLUMINATES → Room Type`
                          provides illumination   
                          to an interior spatial  
                          concept.                

  `IS_CONSTRAINED_BY`     Expresses the inverse   `Spatial Organisation → IS_CONSTRAINED_BY → Structure`
                          of `CONSTRAINS`,        
                          indicating that a       
                          concept is constrained  
                          by another.             

  `CONTRIBUTES`           Indicates that one      `Roof → CONTRIBUTES → Massing`
                          architectural element   
                          contributes to the form 
                          or character of         
                          another.                

  `INFLUENCES`            Indicates that one      `Structure → INFLUENCES → Massing`
                          architectural element   
                          affects the form or     
                          configuration of        
                          another.                

  `ARE_PLACED_IN`         Indicates the           `Openings → ARE_PLACED_IN → Walls`
                          architectural element   
                          within which openings   
                          are positioned.         

  `ORGANISES`             Indicates that one      `Massing → ORGANISES → Openings`
                          architectural concept   
                          structures the          
                          arrangement of another. 

  `APPLIES_TO`            Indicates the           `Ornamentation → APPLIES_TO → Walls`
                          architectural element   
                          to which ornamentation  
                          is applied.             

  `MAY_INCLUDE`           Indicates that a        `Ornamentation → MAY_INCLUDE → decorative_elements`
                          broader architectural   
                          concept may optionally  
                          contain the target      
                          concept.                
  --------------------------------------------------------------------------------------------------------

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
