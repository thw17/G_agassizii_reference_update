# G_agassizii_reference_update
This repository contains scripts used in processing and updating the Gopherus agassizii reference genome to version 1.1

There are two Python scripts, ```Remove_and_split_contamination.py``` and ```Trim_Ns_fasta.py```. Both require Python 2.7 because of the iteration syntax on lines 61-65 in ```Remove_and_split_contamination.py``` and lines 86-88 in ```Trim_Ns_fasta.py```. In both cases, manually changing ```.next()``` to ```._next_()``` should make the scripts Python 3 compatible.

For more details on how we used the scripts in our update to the G. agassizii reference, see our preprint:

Webster TH, Dolby GA, Wilson Sayres MA, Kusumi K. (2018) Improved draft of the Mojave Desert tortoise genome, Gopherus agassizii, version 1.1. PeerJ Preprints 6:e3266v4. [https://doi.org/10.7287/peerj.preprints.3266v4](https://doi.org/10.7287/peerj.preprints.3266v4)

If you use these scripts, please cite this paper. And if you run into any problems or have any questions, please open an Issue in our [Github repo](https://github.com/thw17/G_agassizii_reference_update/issues)

The assembly is available at [NCBI](https://www.ncbi.nlm.nih.gov/assembly/GCA_002896415.1/) and the assembly and annotation are available on [Harvard's Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HUASUW).

Tim Webster - Updated Jan 31, 2018
