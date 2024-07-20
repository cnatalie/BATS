# BATS
Notebooks associated with the study "Protistan metabolism across the western North Atlantic Ocean revealed through autonomous underwater profiling". Using an Autonomous Underwater Vehicle (AUV), high resolution vertical sampling of the microbial community was performed along a western North Atlantic Ocean transect, capturing metabolic signatures from oligotrophic, continental margin, and coastal ecosystems. Plankton biomass was collected along the surface gradient and across depths (to 4,100 m), and taxonomy and function was examined using a paired metatranscriptomic and metaproteomic approach. The metatranscriptomic assembly was generated using the <i>euk</i>rhythmic pipeline (https://github.com/AlexanderLabWHOI/eukrhythmic).

## Notebooks
<b>BATS_R_cleaned.ipynb</b> = Protein normalizations, community composition stacked barplots, NMDS plots, MA plots, Partial Least Squares regression with transcripts and metadata. This notebook is "choose your own adventure" style, where you can read in the dataset of interest in the first code block (by commenting/uncommenting them out), and perform which normalizations/visualizations to run. Datasets are available on Zenodo (see below).

<b>network.ipynb</b> = Network analysis with transcripts

<b>network-proteins.ipynb</b> = Network analysis with proteins, Partial Least Squares regression with proteins and metadata, and Partial Least Squares regression with proteins and transcripts

<b>profiles.ipynb</b> = Trace metal profiles. Trace metal data is contained in metals_ODV.csv, and CTD data is available on Zenodo. At the bottom of this notebook is extracted protein (ug/L), eukaryotic transcript (copies/L) and pigment (ng/kg) correlations.

## Analysis files
<b>metals_ODV.csv</b> = Dissolved trace metals in nM, macronutrients in uM, and particulate trace metals in pM

<b>id.csv</b> = Sequencing file ID to sample key

<b>levels.csv</b> = Order of samples for stacked barplot plotting

<b>CLIO_BV55_fullpigments_forcopiesL.csv</b> = Pigment concentrations in ng/kg. Pigments were not measured from Clio dives at Stations 1 or 3, and instead pigments were collected from the CTD casts, which generally agreed with Clio measurements at other stations. Note that DvA and Vix were not measured at St. 1 and 3. (Pigment abbreviations: ChlC3 = Chlorophyll c3, ChlC2 = Chlorophyll c2, Per = Peridinin, NBut = 19'But-Fucoxanthin, Fux = Fucoxanthin, NHex = 19'Hex-Fucoxanthin, Prx = Prasinoxanthin, Vix = Violoxanthin, Ddx = Diadinoxanthin, Alx = Alloxanthin, Dt = Diatoxanthin, Lut = Lutein, Zex = Zeaxanthin, ChlB = chlorophyll b, DvA = Divinyl Chlorophyll a, Chla = chlorophyll a, ABCar = Alpha & Beta Carotene.)

<b>BATS_metaproteome_sample_progress_forbarplot.csv</b> = total extracted protein concentration from Clio filters in ug/L

<b>pigments_trans_prot.csv</b> = For biomass comparisons. Total protein abundance from Clio filters in spectral counts/L, transcript copies/L estimates summed across EUKulele-annotated eukaryotes from Clio filters, and pigment concentrations in ng/kg

<b>BATS_quant.csv</b> = For visualizing protein distributions. Total protein amount from Clio filters, amount injected onto the mass spectrometer, and volume filtered. These parameters are used to calculate "protein spectral counts per L" = spectral counts * (total protein/protein injected) / volume filtered.

<b>correlations.csv</b> = Nutrient and physicochemical metadata for network and PLS correlation analyses

<b>ko2brite.csv</b> = Kegg KO to BRITE category key

<b>rest.kegg.jp.txt</b> = Kegg KOs alongside definitions

## Assemblies, annotations, read counts are available on Zenodo: https://zenodo.org/record/7317272#.Y3Z5w-zMInV
