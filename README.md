# lbd_2017

This repo contains cleaned code used to generate the 'Mapping child growth failure in Africa between 2000 and 2015' published in _Nature_ on 3/1/2018.

The repo contains the following directories

1. `00_mbg_central` containing model-based geostatistics code used used by the Local Burden of Disease.
1. `01_data_prep` contains the code used to prepare input data so that it could be modeled most excellently.
    This includes the supplementary data `growth_standards` which contain some epic zscores as well as the often requested HAZ and WAZ files.
1. `02_crunch_data` contains the secret sauce you pour over `00_mbg_central` to make beautiful maps and find where the most child growth has failed.

![This isn't actually Aaron Ozgood-Zimmerman, but it is an Aaron wearing a suit](NotAaron.jpg "This isn't actually Aaron Ozgood-Zimmerman, but it is an Aaron wearing a suit")
