# Equipment preparation

40ml EPA vials (Fisher Scientific part number 03-339-14A): EPA vials were rinsed with water purified using a Millipore Milli-Q lab water system (Milli-Q). If the vials were previously used, sample labels were removed and vials were soaked in 2% Micro-90 solution overnight. Vials were scrubbed if needed to remove visible particles/precipitate, rinsed with hot tap water and soaked overnight in freshly made 10% hydrochloric acid. Vials were rinsed again with Milli-Q and allowed to dry completely while covered in a clean area. Vials were then wrapped in foil and combusted at 450 degC for at least 4 hours. 

Teflon-lined septa (Thermo part number B7995-24): Used septa were discarded. Used vial locking collars were rinsed in Milli-Q and dried completely in a clean, covered area. Brand new septa without any pre-cleaning were handled with clean gloves and inserted into vial collars with the Teflon lining facing into the vial (critical to avoid sample contamination).  

Final vial prep: Using gloves, vials were capped with clean, dry, Teflon-lined silicone septa and locking collars. Each lid was covered with pre-combusted foil to keep clean until sample collection. Label tape was placed on vials ahead of time to decrease the amount of handling vials in the field. Sample ID labels were written in the field and placed on the lab tape so that labels could be more easily removed for re-use.

47mm Whatman Glass Microfiber Filters (GF/F) (part number 1825-047): Each filter was individually wrapped in a piece of foil, leaving one side unfolded for ease of access and combustion efficiency. Approximately 7 filters were combined in a consolidated foil package, leaving one side unfolded. Filters were combusted at 450 degC for at least 4 hours. After combustion, the remaining edge of the larger foil packets was folded close and packets were stored in a clean plastic reclosable bag. New filters were freshly combusted prior to each cruise. Unused combusted filters from a previous cruise were used on the following cruise, often less than 6 months later.

4N hydrochloric acid: A combusted glass graduated cylinder was used to measure Milli-Q and 12N hydrochloric acid to mix 4N hydrochloric acid prior to each cruise. The 4N acid was stored in new, combusted glass vials with Teflon-lined lids. Plastic storage vials were never used. 

# CTD Rosette Bottle Sampling on NES-LTER cruises

Samples were collected from the water column at multiple depths along the NES-LTER transect using Niskin bottles on a CTD rosette system. Every main NES-LTER station (L1 - L11) and sometimes Martha's Vineyard Coastal Observatory (MVCO) was sampled when feasible. Stations L2, L4, L6, L8, L10, and L11 were prioritized when necessary. Surface was always sampled and an additional 1-3 depths were also sampled as determined by the depth of each station. Sample depths were always matched with particulate organic carbon (POC) depths at surface and subsurface chlorophyll max (SCM). On AT46, our first sampling effort, the third depth was always paired with the third POC depth. On AR66B, our second sampling effort, a third or fourth depth was sometimes paired with the third POC depth and/or sometimes a dissolved inorganic carbon (DIC) sampled depth. On EN687, our third sampling effort, the third depth changed to a standardized depth of approximately 90 meters for stations L6 through L11 (main stations deeper than 90 m). The standard sampling plan since the summer of 2022 includes a 3rd standardized depth of approximately 100 meters at L6 through L11 and a 4th depth of the deepest water at L10 and L11. Approximately 10% replicate samples were collected on each cruise to check sampling precision. Replicate samples were always collected from the deepest depth of the most offshore station (typically 500 m at L11) on every cruise to act as a baseline for the cruise, assuming this discrete depth will have the lowest dissolved organic carbon observed on that cruise. 

# Filtering Protocol

Cruise, cast, Niskin, and replicate B, when applicable, were written on cryo-labels using permanent marker and placed on label tape already wrapped on the vials.

Using nitrile gloves, a 47mm polycarbonate filter cartridge (part number 1119) and silicone tubing were retrieved from a 10% acid bath and rinsed thoroughly with Milli-Q. A pre-combusted, individually wrapped GF/F filter (nominal pore size 0.7 microns) was inserted into the filter cartridge using clean, dedicated forceps. The sample vials and filter cartridge were then placed in the clean, designated DOC cooler and brought out on deck for sampling.

DOC was the first sample collected from the Niskins, which were sampled deepest to shallowest (least to most concentrated). An integrity check was performed on each Niskin prior to sampling to confirm the Niskin was properly sealed and air-tight. The silicone tubing was connected to the stopcock, and the filter cartridge was purged of air, filled with water, and flushed with sample water for 20-30 seconds. The vial and lid were then rinsed three times and the vial was filled approximately three-fourths of the way full (about 30ml). Once all depths were sampled at the rosette, samples were immediately brought into lab for acidification.

A clean, DOC-dedicated pipette (never used with contaminants such as organic solutions), was used to add 60 microliters of 4N hydrochloric acid to each vial. A new, sterile pipette tip was used for each cast. The same tip was used to acidify all samples as long as the tip was not submerged in the sample or contaminated by contacting any other surface. Acidified vials were gently inverted a few times to ensure acid was well mixed and then stored in a clean, secured location at room temperature.

Used GF/Fs were discarded and the filter cartridge was disassembled and placed into a 10% acid bath until its next use. The filter cartridge was always assembled close in time to sample collection (not prepared hours ahead of time) to avoid tearing of the filter or possible contamination. 

Blanks: approximately 2-3 Milli-Q blanks were typically collected for each cruise and acidified with the acid used on that cruise. Possible blank sources include the ship's Milli-Q system during the cruise and shore-side Milli-Q used when sample supplies were being prepared.

# Sample Analysis

Samples remained covered and were stored at ambient room temperature in the lab until they were submitted to E. Kujawinski's lab at Woods Hole Oceanographic Institution for analysis where they were refrigerated at approximately 4 degC. To obtain the concentration of total organic carbon (TOC) and total nitrogen (TN), samples were analyzed with a Shimadzu TOC-LCPH total organic carbon analyzer coupled to a TNM-L analyzer. Blanks (MilliQ) and standard curves with potassium hydrogen phthalate and potassium nitrate were interspersed into the sample runs. The coefficient of variability between replicate injections was <2%. Comparisons to standards provided by Prof. D. Hansell (University of Miami) were made daily.

Data were received from the facility as Non Purgeable Organic Carbon (NPOC) and Total Nitrogen (TN). Because samples were pre-filtered through GF/F filters, NPOC and TN are operationally equivalent to dissolved organic carbon (DOC) and dissolved total nitrogen (DTN) and identified as DOC and DTN in this package. Blanks are not applied to the data.

Note: DTN values for cruises EN706 and AR77 are from a second round of sample analysis. Some samples did not have enough remaining sample volume to be re-analyzed and thus DTN values do not exist for these samples and are flagged as missing. DOC data for these cruises are from the initial analysis. 

# Data Cleaning and Assembly

Sample metadata were combined with lab results by concatenating cruises called from the REST API of the NES-LTER data system. Nearest station uses a specific station list including NES-LTER standard stations L1 to L11 and the Martha's Vineyard Coastal Observatory (MVCO). IODE quality flags were applied to carbon and nitrogen data separately. Any value flagged as bad was converted to NA. Further documentation can be found on GitHub, at https://github.com/WHOIGit/nes-lter-doc-transect. 

# Quality Assurance

We assured that the geographic and temporal coverage of the clean data table were within expected ranges. In addition to checking replicate samples mentioned above, the carbon to nitrogen ratio was examined as well as pattern of concentrations relative to depth and geographic location. 

# Differences From Previous Versions

In version 2, data from five cruises were added. A second quality flag was added to distinguish C from N quality, and both quality flags were identified as IODE primary level flags. The column previously called "date" was renamed to "date\_time\_utc". Missing value codes were updated to NaN for numeric columns and blank entries for text columns. 

# Related Packages

Dissolved inorganic nutrient data, which could be used together with these data to calculate dissolved organic nitrogen (DON) and the DOC to DON ratio, are in the following packages: 

Sosik, H.M., E. Crockford, and E. Peacock. 2021. Dissolved inorganic nutrients from NES-LTER Transect cruises, including 4 macro-nutrients from water column bottle samples, ongoing since 2017 ver 2. Environmental Data Initiative. https://doi.org/10.6073/pasta/ec6e5c76c7ad4e0da0a8d1cec84fa3f5 (Accessed 2024-04-16).
