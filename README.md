# BATS
Notebooks associated with the study "Protistan metabolism across the western North Atlantic Ocean revealed through autonomous underwater profiling". Using an Autonomous Underwater Vehicle (AUV), high resolution vertical sampling of the microbial community was performed along a western North Atlantic Ocean transect, capturing metabolic signatures from oligotrophic, continental margin, and coastal ecosystems. Plankton biomass was collected along the surface gradient and across depths (to 4,100 m), and taxonomy and function was examined using a paired metatranscriptomic and metaproteomic approach. The metatranscriptomic assembly was generated using the <i>eukrhythmic</i> pipeline (https://github.com/AlexanderLabWHOI/eukrhythmic).

## Notebooks
BATS_R_cleaned.ipynb = Protein normalizations, community composition stacked barplots, NMDS plots, MA plots, Partial Least Squares regression with transcripts and metadata

network.ipynb = Network analysis with transcripts

network-proteins.ipynb = Network analysis with proteins, Partial Least Squares regression with proteins and metadata, and Partial Least Squares regression with 
proteins and transcripts

Note: annotation and count data is available on Zenodo.

profiles.ipynb = Trace metal profiles. Trace metal data is contained in metals_ODV.csv, and CTD data is available on Zenodo.

## Analysis files
correlations.csv

ko2brite.csv

rest.kegg.jp.txt

id.csv

levels.csv

CLIO_BV55_forcopiesL.csv

BATS_metaproteome_sample_progress_forbarplot.csv = extracted protein concentration from Clio filters in ug/L

BATS_quant.csv = Total protein amount from Clio filters, amount injected onto the mass spectrometer, and volume filtered. These parameters are used to calculate protein spectral counts per L: spectral counts * (total protein/protein injected) / volume filtered.

transcripts.goi.pls.csv

## Assemblies, annotations, read counts are available on Zenodo: https://zenodo.org/record/7317272#.Y3Z5w-zMInV
