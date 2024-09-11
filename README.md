# ButterflyfishMovement-CoralSpawning

https://zenodo.org/doi/10.5281/zenodo.13750129

This git contains raw GPS data (24 .gpx files) and data on visitation to corals and other substrates to investigate the movement and space use by butterflyfish during a coral spawning event on a coral reef in Bonaire, Netherlands in June/July 2021.

The raw data were processed, visualized, and analyzed in the RMarkdown file CCAP_Movement.rmd

Processed data files used in analyses include:

ccap.movement - contains raw GPS data for all butterflyfishes (n = 24) tracked at The Lake, a coral reef in Bonaire, Netherlands.
  ID - a unique identifier for each observation
  lon - longitude data
  lat - latitude data
  ele - elevation data (not useful for tracking that occurs via snorkeling on the surface of the ocean)
  time - UTC time for the GPS data

visitations - contains data on visitations to various substrates by the GPS-tracked focal butterflyfish.
  Date - date of the observation
  Follow_Type - the spawning period during which the observation happened
  Observer - the observer's name
  Time_Start - start time of observation as recorded by the observer (Bonaire local)
  Time_End - end time of observation as recorded by the observer (Bonaire local)
  Total_Follow - total duration of the follow in h:mm:ss 
  Ofav_Visits - visits to Orbicella faveolata
  Oann_Visits - visits to Orbicella annularis
  Ofrank_Visits - visits to Orbicella franksi
  Acer_Visits - visits to Acropera cervicornis
  Dlab_Visits - visits to Diploria labyrinthiformis
  Pstrig_Visits - visits to Pseudodiploria strigosa
  Ssid_Visits - visits to Siderastrea siderea
  Gorg_Visits - visits to gorgonians
  Ag_Visits - visits to Agaricia spp.
  Sed_Visits - visits to sediment
  Past_Visits - visits to Porites astreoides
  Malc_Visits - visits to Millepora alcicornis
  Mmir_Visits - visits to Madracis mirabilis
  Mcav_Visits - visits to Montastraea cavernosa
  Cnat_Visits - visits to Colpophyllia natans
  Efas_Visits - visits to Eusmilia fastigiata
  Sponge_Visits - visits to sponges
  Unk_Visits - visits to substrates that could not be confidently identified
  Total_Visits - total visits to all substrates
  
  
