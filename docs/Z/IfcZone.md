IfcZone
=======
A zone is\S\ a group of spaces, partial spaces or other zones. Zone structures
may not be hierarchical (in contrary to the spatial structure of a project -
see _IfcSpatialStructureElement_), i.e. one individual _IfcSpace_ may be
associated with zero, one, or several _IfcZone_''s. _IfcSpace_''s are grouped
into an _IfcZone_ by using the objectified relationship _IfcRelAssignsToGroup_
as specified at the supertype _IfcGroup_.  
  
> NOTE \S\ Certain use cases may restrict the freedom of non hierarchical
> relationships. In some building service use cases the zone denotes a\S\ view
> based delimited volume for the purpose of analysis and calculation. This
> type of zone cannot overlap with respect to that analysis, but may overlap
> otherwise.  
  
> HISTORY  New entity in IFC1.0  
  
{ .change-ifc2x4}  
> IFC4 CHANGE  The entity is now subtyped from _IfcSystem_ (not its supertype
> _IfcGroup_) with upward compatibility for file based exchange.  
[ _bSI
Documentation_](https://standards.buildingsmart.org/IFC/DEV/IFC4_2/FINAL/HTML/schema/ifcproductextension/lexical/ifczone.htm)


Attribute definitions
---------------------
| Attribute   | Description                                                                                                                                                                                                                                                                                                                                                                                              |
|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| LongName    | Long name for a zone, used for informal purposes. It should be used, if available, in conjunction with the inherited _Name_ attribute.\X\0D> NOTE  In many scenarios the _Name_ attribute refers to the short name or number of a zone, and the _LongName_ refers to the full name.\X\0D\X\0D \X\0D{ .change-ifc2x4}\X\0D> IFC4 CHANGE The attribute has been added at the end of the entity definition. |

Formal Propositions
-------------------
| Rule   | Description   |
|--------|---------------|
| WR1    |               |

