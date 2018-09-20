# Data schema for lab 4


**Pulled from kegg

*Glycolysis Pathway enzymes:
glucose-1-phosphatase [EC:3.1.3.10]
glucose-6-phosphatase [EC:3.1.3.9]
phosphoglucomutase [EC:5.4.2.2]
hexokinase [EC:2.7.1.1]

*Pentose Phosphate Pathway enzymes:
fructose-1,6-bisphosphatase I [EC:3.1.3.11]
6-phosphofructokinase 1 [EC:2.7.1.11]
ADP-dependent phosphofructokinase/glucokinase [EC:2.7.1.146]
diphosphate-dependent phosphofructokinase [EC:2.7.1.90]

*TCA enzymes:
pyruvate dehydrogenase E2 component (dihydrolipoamide acetyltransferase) [EC:2.3.1.12]
acetate---CoA ligase (ADP-forming) subunit alpha [EC:6.2.1.13]
phosphoenolpyruvate carboxykinase (ATP) [EC:4.1.1.49]
L-lactate dehydrogenase [EC:1.1.1.27]


## Gene table
CREATE TABLE genes (id INT PRIMARY KEY ASC, name TEXT, description TEXT, nucleotide_seq TEXT);


## Pathway table
CREATE TABLE pathways (name TEXT, description TEXT);

## Enzyme table
CREATE TABLE enzymes (name TEXT, function TEXT)

