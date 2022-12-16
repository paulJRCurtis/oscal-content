schema
https://github.com/usnistgov/OSCAL/tree/main/json/schema


# Catalog
The structure of the catalog is taken from the high level structure of the standard but supplemented with the sub-headings from the guide.

The cpg234 section "Considerations for the Board" is not included as a separate section as the content is included in other parts of the catalog.

## TODO
- create control objectives, need to explore SSPs first to see if this is worth while.
- use props to capture source [cps234 | cpg234] and section need to check if this is of value


## IDs
- group and sub-group ids are two or three letter abbreviations of the heading.
- control ids are the parent group and subgroup is separated by '-' followed by a sequence number starting with 1.
- sub-controls ids are the parent control id followed by '-' followed by a sequence number starting with 1
- parts are the parent control id followed by '_' and a three letter abbreviation of the part name;
  - objective = obj
  - statement = smt
  - guidance = gdn
  - footnote = fnt
  where required sequence numbers can be used if there are multiple parts with the same name.
- subpart ids are the parent part id followed by '_' and a three letter abbreviation of the part name.

Example: rr-bur-1_gdn-2_fnt


## additional sections
under Policy framework the sub-group "Roles and responsibilities" has been added to contain cps234 para19

under "Testing control effectiveness" the sub-group "Third-party testing" has been added to contain cps234-para28
under "Testing control effectiveness" the sub-group "Testing program review" has been added to contain cps234-para31
under "Internal audit" the sub-group "Appropriately skilled personnel" has been added to contain cps234-para33

## controls at group level
"id": "ic",
"title": "Implementation of controls",
cps234-para21

