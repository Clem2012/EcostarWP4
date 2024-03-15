# EcostarWP4
WP4: Quantify changes within the benthic fauna, structure (diversity and biomass) and functions (traits, productivity) in response to the introduction of different types of man-made structures

Version	Date Updated	Author/Amender	Notes
1.0	25th November 2021	Gareth Thomas	Creation of original R.M.
1.1	29th November 2021	Clement Garcia	Added two files
			

Note: a polite reminder, prior to the publishing of any data and/or its analysis/interpretation all authors/parties involved in the curation of databases and the collaborations should be consulted and authorship credited where appropriate. Please do not share data/analysis outside of those pre-authorised to have access unless explicit permission has been granted.

Public & INSITE Domain:

•	Original Raw UK Benthos data: this folder contains all the original raw data files.
•	INSITE Documents: word files providing structural overview/descriptions of raw data.

University of Essex (UoE):

Every UoE file starts with the term “UoE” and ends with a Month/Year date of last update. Authors include Dr Gareth Thomas (lead – gthomab@essex.ac.uk), Dr Eoin O’Gorman (PI – e.ogorman@essex.ac.uk), Hugh Kinsella (student – hkinsell@tcd.ie), Zelin Chen (PhD student - zc21617@essex.ac.uk).

•	UKB_data: main environmental and chemistry database that has been compiled from the raw databases, processed, and cleaned up (see rules). This should be interpreted in conjunction with “Database structure v 5” within the “INSITE Documents” folder.

•	UKB_species_master_list: this database has been compiled of the unique species names found with “UKB_data”. Detailed taxonomic information has been included, as has species habitat, feeding strategy, and life cycle stage (see rules).

•	UKB_survey_coordinates: database includes the survey code and platform name alongside the longitudinal and latitudinal coordinates of the platform being surveyed.

•	UKB_consumer_resources: this database is under construction and as such has not been shared yet. However, it will include every species from “UKB_data” and their food web links to all over predator/prey relationships or basal resources. Literature references are included in support or otherwise noted as inferred from different taxonomic levels.

•	UKB_Data_Analysis_Rules: a list of rules and assumptions taken as the UoE analytical team, these should be referred to as the databases are analysed and interpreted. It is important it is kept up to date with any changes.

Centre for Environment, Fisheries and Aquaculture Science (Cefas):

Every Cefas file starts with the term “Cefas” and ends with a Month/Year date of last update. Insite authors only includes Dr Clement Garcia (clement.garcia@cefas.co.uk) but data are based on Cefas legacy work whose main contributors (still in activity) include Dr Stefan Bolam (traits) (stefan.bolam@cefas.co.uk) and Dr Keith Cooper (keith.cooper@cefas.co.uk) (OneBenthic database and some individual biomass).

•	TraitMatrix: The Cefas functional traits database for the benthic infauna in the shelf seas of the North East Atlantic. It contains 10 traits subdivided into few attributes (the modalities that each trait can take). The traits are fuzzy-coded which means that for each taxon has been allocated a score from 0 (no affinity) to 3 (maximum affinity) for each trait modality. The information is provided at Genus level for 1031 taxa. PLEASE DO BE CAREFUL as this database has been created by multiple experts over the years whose understanding could have been different of what the “affinity” means (ranging from “real” recorded affinity, general uncertainty or a mix of both), some would have considered that various scoring should be mutually exclusive (the presence of a 3 would be excluding any other scoring) others not. I would highly recommend using this database as an exploratory tool and double-check with different data source any pattern that might emerge from your analysis. We are currently reworking this database and it has been submitted as data paper with some of the above issues partially solved, in the meantime please find further technical details (including the name definitions) and reference it as Bolam & Eggleton (2014) Macrofaunal production and biological traits: Spatial relationships along the UK continental shelf. Journal of Sea Research.

•	Ind_biomass_database: compilation from various sources (peer-review literature and available datasets) of benthic infauna (with some epifauna) taxa from the North East Atlantic shelf seas. The “decomposed” tab contains all the unchanged original data which includes reference and sources of each of the record. The tab “mean” has summarised the raw information to provide a mean body mass value per unit – wet weight (WW), dry weight (DW) or ash-free dry weight (AFDW). The tab “gWW” has converted all “no WW” into WW (the most common unit) by using the Brey algorithm (http://www.thomas-brey.de/science/virtualhandbook/). The “(1) mean gWW species & above” tab provides a unique “body-mass” average value per taxa using weighted average with the respective abundance per unit. The other sheets, from (2) to (6) are showing the average body mass (using weigthed average) of all level of taxa aggregation from Genus to Phylum. This database was compiled by Olivier Beauchard from NIOZ and Clement Garcia with the help of Keith Cooper from Cefas – it is currently being formatted for a data paper but can be used for now, please let me know when it is about to be published so I can give you an update on what to cite.
