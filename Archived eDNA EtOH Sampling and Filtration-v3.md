---
# MIOP terms
methodology_category: sample collection 
project: CalCOFI Archived eDNA Sampling
purpose: biodiversity assessment objective [OBI:0001969]
analyses: filtration [OBI:0302885], environmental material collection process [OBI:0600012] 
geographic_location: North Pacific Ocean [GAZ:00002418] 
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: marine pelagic zone [ENVO:00000208], marine pelagic biome [ENVO:01000023] 
environmental_medium: ethanol [CHEBI:16236], dwc:material sample 
target: deoxyribonucleic acid (DNA) [NCIT:C449]
creator: Erin Thompson, Nastassia Patin
materials_required: filtration [OBI:0302885] 
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 840
personnel_required: 1
language: en
issued: # YYYY-MM-DD
audience: scientists
publisher: Scripps Institution of Oceanography, UC San Diego
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_category: sample
env_broad_scale: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
env_local_scale: marine pelagic zone [ENVO:00000208], marine pelagic biome [ENVO:01000023] 
env_medium: ethanol [CHEBI:16236], dwc:material sample 
habitat_natural_artificial_0_1: 0
samp_collect_method: serological pipette
samp_collect_device: 50 mL conical tubes 
samp_size: 100
samp_size_unit: mL
---

# Archived eDNA EtOH Sampling and Filtration


### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY  | AFFILIATION  | ORCID        | DATE       |
| ------------ | ------------ | ------------ | ---------- |
| Erin Thompson | UC San Diego, CalCOFI |  | 2025-10-06 |
| Nastassia Patin | UC San Diego, CalCOFI | 0000-0001-8522-7682 | 2025-10-06 |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-10-17 | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| SIO | Scripps Institution of Oceanography |
| CalCOFI | California Cooperative Oceanic Fisheries Investigations |
| PIC  | Pelagic Invertebrate Collection |
| DI | Deionized water |
| PVDF | Polyvinylidene fluoride|

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Jars  | Screw-cap sampling containers with archived samples |


## BACKGROUND

### Summary

This protocol describes the sampling and filtration of marine environmental DNA from archived bulk organism sample jars in the SIO Pelagic Invertebrate Collections. The jar contents were originally sampled via bongo net tow on CalCOFI quarterly cruises and preserved in ethanol. The filters obtained from this protocol can be used for DNA extraction and any downstream amplification and/or sequencing protocols. For the purposes of this project, we are aiming to detect phytoplankton, zooplankton, benthic and pelagic invertebrate, and fish species presence in the California Current for biodiversity assessment. 

### Method Description and Rationale

This protocol describes the sampling of archival biomass samples, originally collected using bongo nets and preserved in 95% or 100% ethanol, for DNA extraction. This approach could be applied to similar biorepositories to reconstruct historical time series using eDNA. From each jar containing biological material in ethanol, 100 mL of ethanol are sampled and run through a 0.22 µm PVDF filter. Previous work determined 100 mL was an appopriate volume to generate sufficient eDNA for downstream processes, in this case metabarcoding. The volume could be modified based on the specific repository and planned molecular work (e.g. shotgun metagenomics, qPCR, etc.).


### Spatial Coverage and Environment(s) of Relevance

This protocol can be used for any single specimen or bulk marine samples, or similar samples from other environments, preserved in ethanol. 

## PERSONNEL REQUIRED

One person with experience in sterile technique and pipetting.

### Safety

There are no major safety concerns in this protocol. Proper PPE should be worn at all times. Subsampling and filtration should be performed in a fume hood to avoid inhalation of ethanol fumes. 

### Training Requirements

Standard lab safety training, including sterile technique, is necessary for this protocol. Personnel should also be trained in handling and proper disposal of hazardous materials. 

### Time Needed to Execute the Procedure

Sampling around 100 jars takes about 6-8 hours. Filtration of around 100 samples takes about 4-5 hours. 

## EQUIPMENT


| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| Seroligical pipetter |Serological pipette controller | Generic brand | 1 |  |
| Vacuum Manifold| MultiVac 610-MS-T, 6-Branch Aluminum Manifold Vacuum Filtration System | Steriltech | 1 |  |
| **Consumable equipment** |
| Gloves | Powder-free nitrile gloves | Generic brand | 1 box|
| Serological pipettes | 50mL Serological Pipettes | Generic brand | 100 | Quantity depends on number and size of samples and pipette size |
| Conicals| 50mL Conical tubes| Generic brand| 200 | Quantity depends on number and size of samples|
| Filters | 0.22μm PVDF Membrane, 47mm | Durapore | 100 | Quantity depends on number of samples |
| Vials| 20mL Disposable Scintillation Vials | Generic brand| 100 | Quantity depends on number of samples |
| Glass beakers |100mL glass beaker | Generic brand | 2 |Used for paper discard and holding clean forceps|
|Cryovials| 2.0mL cryogenic vials|Generic brand|100|Quantity depends on number of samples|
| **Chemicals** |
|Ethanol| 200 proof ethanol | Generic brand |2.5 L | About 20mL per sample |
| Deionized Water | DI water | Generic brand |  | Used for rinsing, about 150mL in vacuum chamber between filtrations|
| TRIS-buffered ethanol | 125 ml 1.0M Tris Buffer, 5 gallon can of 100% (200 proof) ethanol | Generic brand |  | Used to top-off sample jars |

## STANDARD OPERATING PROCEDURE


### Preparation


1. Wipe down fume hood with ethanol or lab-grade wipes. Lay down lab paper and mark clean areas for EtOH work to prevent contamination from other chemical reagents used in the space, such as formalin. 
2. Prepare the following supplies:
- Serological pipettes (50 mL): at least one per sample
- Serological pipettor
- 50 mL conical tubes (2 per sample)
- Sample sheet & pen
- TRIS-buffered ethanol
- Lab Markers
3.  Assign both full and short sample IDs to each one based on the following: cruise number, vessel, line, station, order occasion. The short ID should only contain the cruise number and event number.
4.   Label 50 mL conical tubes with the short sample IDs.
5.    Set up your work space in the fume hood. Have jars on a cart or table next to the hood. Don gloves before moving anything in and out of the hood.

### Sampling
1. Invert each jar five times to mix the ethanol, then let the biomass settle to the bottom. This can be done outside the fume hood. If working on groups of about 30 jars at a time, the first one will have settled by the time you finish inverting the last jar. 
2. For each jar, perform the following steps: 
    a. Bring the jar into the fume hood and carefully unscrew the lid. Use a serological pipette to transfer 2 x 50 mL ethanol into the labeled 50 mL conicals. If the jar contains too much biomass to cleanly extract 100 mL of ethanol, use a mesh lid or plankton sock to filter out 100 mL into another container. Transfer the 100 mL into the conicals, return any remaining ethanol to the jar, and squirt ethanol on and through the mesh/sock to return any remaining biomass to the jar. Make a note on sample sheet when the mesh/sock is used. Clean mesh or sock with DI water between samples.
b. Use a different pipette for each sample. If <100 mL ethanol is available for transfer, make a note in the sample sheet. 
c. Transfer new TRIS-buffered ethanol into the sampled jar, either by carefully pouring or with a “clean” pipette. Be careful not to splash.
d. Carefully screw the lid back onto the jar. Mark it as sampled.
e. Repeat steps a-c for each sample on the sheet. If a sample is on the sheet but the jar is missing, make a note.
3. When finished, wipe up any spills in and around the fume hood. Confirm all jars have been topped off and are tightly closed.

### Filtration


1. Set up 6-prong manifold(Appendix A, Figure 1) in a chemical fume hood. Plug in and turn the motor on. Turn the lever on each individual vacuum to be parallel with the floor of the hood (Appendix A, Figure 2). Air should not be flowing through the chamber.
11. Prepare the following supplies:
- DI water
- 200 proof ethanol
- 50 mL conical vials containing samples
- Labeled 20-mL scintillation vials
- 0.22 μm PVDF membrane filters, 47 mm
- Lab marker
- Sample sheet and pen
- Forceps
- 2 small beakers
- Kim wipes or paper towels

3. Designate one pair of clean forceps, which can be stored in one of the beakers and used for placing clean filters on the manifold. 
13. Pour 50-100 mL DI water into the first vacuum and switch the vacuum on until empty. Repeat for each of the 6 vacuums. 
14. Label the cap of each of the first six vials for the first six 100 mL samples (two 50 mL conicals) with the sample’s short ID (found on the conicals). Place each vial next to the corresponding vacuum. 
15. Dry any remaining water from underneath the vacuum chambers with a Kim-wipe or paper towel.
16. Filters are white and are individually separated by blue paper. Using the clean forceps, place one 0.22 µm filter under each vacuum cup. Make sure the magnet between the cup and the base of the vacuum is fully sealed to prevent losing sample volume. Collect blue paper waste in the second beaker.
17. Carefully pour both 50 mL volumes of each sample in the corresponding vacuum chamber. While or after pouring, turn the lever to be perpendicular to the floor of the fume hood (Appendix A, Figure 2) so that the suction is on and liquid is being drawn through the filter.
18. When the vacuum chamber appears empty, turn off the suction (lever parallel to the floor). 
19. When ready to transfer the filter, uncap the vial for the sample. Using a new pair of forceps, remove the filter from the vacuum. Using a second pair of forceps, carefully roll the filter into a tube and place the filter into the vial. Discard the forceps into a “dirty” bag.
20. Add 200-proof ethanol to the vial until the filter is submerged. Cap and invert to prevent air bubbles. Return the vial to the appropriate slot in the box.
21. Repeat steps 8-12 for each of the six samples. You can start pouring the next sample before the previous one has finished filtering. Turn off the vacuums as they empty to prevent air being pulled through the filters.
22. Note any spills or other abnormalities during filtering on the sample sheet.
23. After removing all filters, repeat steps 4-13 for the next six samples.
24. Repeat steps 4-11 with 100mL of DI water.
25. After all samples and blank have been filtered, assign the vial numbers and any filtering notes to the appropriate samples in the sample sheet.



### Sample Preservation


In this protocol, all samples are filtered. Filters are placed in 20mL of 200-proof ethanol in scintillation filters and kept at 4°C until processing. When ready, filters are cut in half using sterile technique. Half of the filter is kept in the scintillation vial and ethanol until extraction, and the other half is placed into a cryovial for long-term storage. 

### Storage

Freeze cryovials at -80°C.

### Quality Control
A filtration blank is performed using 100mL DI water. Observe and note any leaks during filtration, or problems with the filters (any tears, contact with other objects, etc.).


### Basic Troubleshooting Guide

- If liquid is leaking from vacuum during filtration, check that the magnet between the vacuum chamber and prong is fully sealed. 
- Tips for cutting filters in half:
    - Use forceps to fold filter in half. Cut the filter almost entirely in half, but leaving a small connection. Position one half over the scintillation vial. Use the scissors to push the half into the vial while holding th second half with forceps. Let the remaining connection between the halves rip as the first half enters the vial. Use the forceps to roll the second half into the cryovial.
    - Have a sanitation station (DNA Away, DI Water, and ethanol) ready to sanitize scissors as you work. Have multiple pairs of scissors to increase efficiency. 

## REFERENCES

- No studies have yet been published using this method.

## APPENDIX A: DATASHEETS
![Image_1)](https://github.com/CalCOFI/Archived-eDNA-Sampling/blob/main/IMG_3710%20(1).jpeg)
Figure 1. 6-prong manifold, pictured and labeled according to terminology as used in this protocol. 

![Image_2](https://github.com/CalCOFI/Archived-eDNA-Sampling/blob/main/IMG_3713%20(1).jpeg)
Figure 2. Individual vacuums, shown both "on" (suction going through the vacuum) and "off" (no suction). 

