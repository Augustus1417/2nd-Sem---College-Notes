### Data Model
**Model**
- an abstraction of a real world object or event
- Useful in understanding complexities of the real world environment

**Data Model** - a diagram that displays a set of tables and relationships between them

#### History
- Peter Chen proposed ER diagrams in 19xx.

**What is an ERD (Entity Relationship Diagram)**
- is a data modeling technique used in software engineering

ERD
- Major activity of this phase is identifying entities, attributes

##### Peter Chen's ER Diagrams
- **Rectangles** - entity
- **Ellipses** - attribute
- **Diamonds** - relationship
- **Lines**
- **Primary Key**
- **Double Ellipses** - multivalued attribute
- **Broken Ellipses** - derived attribute

##### Entity 
- anything about which we store information
- identified by name or noun

Entity instance: a single occurrence of an entity

##### Weak entity 
- is a type of entity that does not have any unique key for the the attribute tuples
- is an entity that cannot exist without an entity it depends on

##### Attribute 
- contains a piece of information that describes an entity

**Key Attribute** - uniquely identifies an entity
**Composite Attribute** - attribute composed of several other attributes
**Multivalued Attribute** - can posses over one value
**Derived Attribute** - can be derived from other attributes of the entity

##### Relationships
- associations between entities
- is indicated by a verb connecting two or more entities
- are assigned to projects

**Cardinalities** - is the number of occurrence in one entity which are associated to the number of occurrence in another

```mermaid

```
**Identifier**
- attributes that uniquely identify entity instances