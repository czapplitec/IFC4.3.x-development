IfcRelAssigns
=============
The assignment relationship, _IfcRelAssigns_, is a generalization of "link"
relationships among instances of _IfcObject_ and its various 1^st^ level
subtypes. A link denotes the specific association through which one object
(the client) applies the services of other objects (the suppliers), or through
which one object may navigate to other objects.  
  
The client is denoted as the relating object and is established at the level
of the specific, instantiable subtypes of _IfcRelAssigns_. The suppliers are
denoted as the related objects and they are established by the
_RelatedObjects_ attribute.  
  
> NOTE  The terms "client" and "supplier" are used in a general concept and do
> not imply any meaning for implementations of systems (like client-server).  
  
> EXAMPLE  A resource may receive information about its nature of representing
> real building products by establishing a link between _IfcResource_ and
> _IfcBuildingElement_ (subtype of _IfcProduct_) through the assignment
> relationship _IfcRelAssignsToResource_. The resource is then the client that
> applies the services of other objects (here building elements) to express
> the particular view of elements to be consumed as a resource in a process.  
  
The assignment relationship establishs a bi-directional relationship among the
participating objects and does not imply any dependency. The subtypes of
_IfcRelAssigns_ establishes the particular semantic meaning of the assignment
relationship.  
  
> HISTORY  New entity in IFC2x.  
[ _bSI
Documentation_](https://standards.buildingsmart.org/IFC/DEV/IFC4_2/FINAL/HTML/schema/ifckernel/lexical/ifcrelassigns.htm)


Attribute definitions
---------------------
| Attribute          | Description                                                                                                                                                                                                                                                                      |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| RelatedObjectsType | Particular type of the assignment relationship. It can constrain the applicable object types, used within the role of _RelatedObjects_.\X\0D{ .change-ifc2x4}\X\0D> IFC4 CHANGE  The attribute is deprecated and shall no longer be used. A NIL value should always be assigned. |

Formal Propositions
-------------------
| Rule   | Description   |
|--------|---------------|
| WR1    |               |

Associations
------------
| Attribute      | Description   |
|----------------|---------------|
| RelatedObjects |               |

