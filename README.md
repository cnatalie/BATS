# BATS
Notebooks associated with the study "Protistan metabolism across the western North Atlantic Ocean revealed through autonomous underwater profiling". Using an Autonomous Underwater Vehicle (AUV), high resolution vertical sampling of the microbial community was performed along a western North Atlantic Ocean transect, capturing metabolic signatures from oligotrophic, continental margin, and coastal ecosystems. Plankton biomass was collected along the surface gradient and across depths (to 4,100 m), and taxonomy and function was examined using a paired metatranscriptomic and metaproteomic approach. The metatranscriptomic assembly was generated using the <i>eukrhythmic</i> pipeline (https://github.com/AlexanderLabWHOI/eukrhythmic).

## Notebooks
BATS_R_cleaned.ipynb = Protein normalizations, community composition stacked barplots, NMDS plots, MA plots, Partial Least Squares regression with transcripts and metadata

network.ipynb = Network analysis with transcripts

network-proteins.ipynb = Network analysis with proteins, Partial Least Squares regression with proteins and metadata, and Partial Least Squares regression with 
proteins and transcripts

<i>Note: annotation and count data is available on Zenodo.</i>

profiles.ipynb = Trace metal profiles. Trace metal data is contained in metals_ODV.csv, and CTD data is available on Zenodo.

## Analysis files
metals_ODV.csv = Dissolved trace metals in nM, macronutrients in uM, and particulate trace metals in pM

id.csv = Sequencing file ID to sample key

levels.csv = Order of samples for stacked barplot plotting

CLIO_BV55_forcopiesL.csv = Pigment concentrations in ng/kg. Pigments were not measured from Clio dives at Stations 1 or 3, and instead pigments were collected from the CTD casts, which generally agreed with Clio measurements at other stations. If CTD collection depths did not match those sampled by Clio, concentrations were estimated from nearby depths. Note that DvA and Vix were not measured at St. 1 and 3, and at these stations, the maximum depth pigments were measured was 150 m. (Pigment abbreviations: ChlC3 = Chlorophyll c3, ChlC2 = Chlorophyll c2, Per = Peridinin, NBut = 19'But-Fucoxanthin, Fux = Fucoxanthin, NHex = 19'Hex-Fucoxanthin, Prx = Prasinoxanthin, Vix = Violoxanthin, Ddx = Diadinoxanthin, Alx = Alloxanthin, Dt = Diatoxanthin, Lut = Lutein, Zex = Zeaxanthin, ChlB = chlorophyll b, DvA = Divinyl Chlorophyll a, Chla = chlorophyll a, ABCar = Alpha & Beta Carotene.)

BATS_metaproteome_sample_progress_forbarplot.csv = extracted protein concentration from Clio filters in ug/L

BATS_quant.csv = Total protein amount from Clio filters, amount injected onto the mass spectrometer, and volume filtered. These parameters are used to calculate protein spectral counts per L: spectral counts * (total protein/protein injected) / volume filtered.

correlations.csv = Nutrient and physicochemical metadata for network and PLS correlation analyses

ko2brite.csv = Kegg KO to BRITE category key

rest.kegg.jp.txt = Kegg KOs alongside definitions

## Assemblies, annotations, read counts are available on Zenodo: https://zenodo.org/record/7317272#.Y3Z5w-zMInV
