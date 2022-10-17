# Lease ontology over Canada

The 2-level ontology for residential leases is class diagram in xml format, built with drawio.

The "Lease_class_diagram" contains the ontologies and the mapping between national and regional ontology.
![](./Structure.png)

- File "Core.xml": The core ontology for residential leases over CA
- Dir "Regional": The regional ontologies for each province or territory
- Dir "mapping": mapping file mapping components in regional ontologies to the core ontology
- Dir "Std_lease_form" directory contains the standard forms provided by local governments.
- Dir "Doc" contains all description of each regional and national ontologies 

## Core ontology evaluation 

### Evaluate the completeness of the core ontology 


To measure the completeness of the core ontology, we mapped standard forms to the core ontology, while calculating How many blanks in standard forms can be mapped to core ontology. 

> Blank definition: "blank" means the blank that need to be filled by user in a form of tenancy agreement. We consider:
> (1: the blanks related to 1 address as 1 blank. For example, {"commmunity address" + "city" + "province" + "postcode"} is ONE blank. (2: the blanks related to 1 date as 1 blank.For example, {"day" + "month" + "year" } is ONE blank. 

$$ 
Completeness = (number of blanks can be mapped in a form) /(the total number of all blanks in a form)
$$


### Evaluate the correctness of the core ontology 

To measure the correctness of the core ontology, for each attribute in core ontology, we calculate the frequency that this attribute appears in standard lease forms. 


