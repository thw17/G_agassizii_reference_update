# G_agassizii_reference_update
This repository contains scripts used in processing and updating the Gopherus agassizii reference genome to version 1.1

There are two Python scripts, ```Remove_and_split_contamination.py``` and ```Trim_Ns_fasta.py```. Both require Python 2.7 because of the iteration syntax on lines 61-65 in ```Remove_and_split_contamination.py``` and lines 86-88 in ```Trim_Ns_fasta.py```. In both cases, manually changing ```.next()``` to ```._next_()``` should make the scripts Python 3 compatible.

For more details on how we used the scripts in our update to the G. agassizii reference, see our paper. (I'll update with a link when we submit a preprint later this week - written 9/11/2017):

Webster et al. In prep. Update to the draft genome of the Mojave Desert Tortoise, Gopherus agassizii: version 1.1.

If you use these scripts, please cite this paper. And if you run into any problems or have any questions, please open an Issue in our [Github repo](https://github.com/thw17/G_agassizii_reference_update/issues)

Tim Webster - 9/11/2017
