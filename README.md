## CB_LOOKUPS
# A collection of data tables to support cohort creation/analysis of Connected Bradford Data.

Where possible the source of the data is referenced and links provided. In most cases these lists are open source or produced internally.
The list below is a summary of the available data - by type 

GEO - is geographical data

Code - coded, ctv3, snomed etc

Data - useful data for projects

CodeLists - These are lists of codes associated with a specific condition

Docs - The document folder contains any data dictionary type documentation we have on these and any other datasets that are not specifically contained within a FDM.

|table_name	|	Type	|	Desc	|  Clinically Assured |
|-----------|-------|-------|---------------------|
|	lookup_pseudonymised_uprn_lsoa	|	GEO	|	includes pseudonymised UPRN (Unique Property Number) and its associated lsao	| 
|	tbl_AE_CodeToSnomed_lookup	|	Code	|	The snomed code that each ICD10 A&E code links to	|
|	tbl_BNF_DMD_SNOMED_lkp	|	Code	|	British National Formulary and its snomed code	|
|	tbl_CTV3Codes_Lookup	|	Code	|	List of CTV3 Codes and Description	|
|	tbl_CTV3ToSnomed_Map	|	Code	|	CTV3 code and the linked snomed code	|
|	tbl_CTV3ToSnomed_Map_2	|	Code	|	As above but updated with new entries	|
|	tbl_EFI2_Codelist	|	Code	|	CTV3 Codes  that form the Electronic Frailty index, with the deficits included	|
|	tbl_EFI_Codelist	|	Code	|	CTV3 Codes that form the Electronic Frailty index version2 with additional factors, including Snomed Code	|
|	tbl_IMD_2019	|	GEO	|	Detailed IMD by LSAO for 2019	|
|	tbl_IMD_by_LSOA	|	GEO	|	The IMD score for each Bradford District LSAO	|
|	tbl_LSOA_AREA	|	GEO	|	The geo data for each LSOA	|
|	tbl_LSOA_to_Ward	|	GEO	|	The wards within each LSOA	|
|	tbl_OpenSafelyCategory	|		|	Contains coding and data used for a previous project. May be useful	|
|	tbl_bradford_map_prep	|	GEO	|	Geo Data fro Bradford District	|
|	tbl_lsoa_boundaries	|	GEO	|	Shapefile data for LSOA	|
|	tbl_lsoa_to_msoa	|	GEO	|	links the LSOA to the MSOA	|
|	tbl_msoa_boundaries	|	GEO	|	Shapefile data for MSOA	|
|	tbl_person_efi	|	Data	|	The Currently calculated EFI for all individuals	|
|	tbl_person_lsoa	|	GEO	|	Links Person  data to current LSOA , where known	|
|	tbl_ward_boundaries	|	GEO	|	Shapefile data for Wards	|
| cb_DailyAverage_AirQuality_4Yrs | Data | Daily Air quality across Bradford District , see docs for details. |
| tbl_CodeList_MultipleSclerosis |CodeList | CTV3 codes associated with multiple sclerosis, see https://datacompass.lshtm.ac.uk/id/eprint/2600/ for provenance | Not Clinically Assured |
| lkp_SensitiveCodes | CodeList | CTV codes associated with sensitive data - these are NOT included in Connected Bradford Data | Not Clinically Assured | 




Docs
Contains: Deaths+DSCRO+Spec.xlsx - data dictionary for the Death Data (available upon request) 





