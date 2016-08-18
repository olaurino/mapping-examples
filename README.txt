Mapping docs in ../docs/MappingDMtoVOTable-v1.0-201607xx.docx/pdf

VOTable schema with mapping extensions in ../xsd/ext/VOTable-1.3_vodml.xsd

This folder contains a collection of sample VOTable documents with VO-DML annotations.

starting from test1... they become more complex, highlighting dfferent mapping patterns.
The votables named testNeM.votable.xml, with N and M integers, are variants of the testN.votable.xml document 
with errors introduced that a paresre should be able to discover.

Next should come a description of each test votable, with the aspect it focuses on:
:::::

- test1: model annotation
- test1e1: model annotaiton, illegal ROLE on a vodml-map:Model

- test2: "singleton"/"standalone" object-as-a-GROUP (here PhotometryFilter from the sample/filter/FIlter model)

- test3: singleton object, here a filter:PhotometrySystem, containing some contained PhotometryFilter objects in its filter:PhotometricSystem.photometryFilter collection

- test4: table mapping (should possibly come a bit later in the sequence of samples)