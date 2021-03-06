IfcShadingDeviceType
====================
The building element type **IfcShadingDeviceType** defines commonly shared
information for occurrences of shading devices. The set of shared information
may include:  
  
* common properties with shared property sets  
* common representations  
* common materials  
* common composition of elements  
  
It is used to define a shading device type specification indicating the
specific product information that is common to all occurrences of that product
type. The **IfcShadingDeviceType** may be declared within _IfcProject_ or
_IfcProjectLibrary_ using _IfcRelDeclares_ and may be exchanged with or
without occurrences of the type. Occurrences of **IfcShadingDeviceType** are
represented by instances of _IfcShadingDevice_. Refer to the documentation at
_IfcShadingDevice_ for supported property sets, materials, and composition.  
  
> HISTORY  New entity in IFC4.  
[ _bSI
Documentation_](https://standards.buildingsmart.org/IFC/DEV/IFC4_2/FINAL/HTML/schema/ifcsharedbldgelements/lexical/ifcshadingdevicetype.htm)


Formal Propositions
-------------------
| Rule                  | Description   |
|-----------------------|---------------|
| CorrectPredefinedType |               |

Associations
------------
| Attribute      | Description   |
|----------------|---------------|
| PredefinedType |               |

