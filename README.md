[![Build Status](https://travis-ci.com/globalbioticinteractions/wardeh2021.svg)](https://travis-ci.com/globalbioticinteractions/wardeh2021) [![GloBI](http://api.globalbioticinteractions.org/interaction.svg?accordingTo=globi:globalbioticinteractions/wardeh2021)](http://globalbioticinteractions.org/?accordingTo=globi:globalbioticinteractions/wardeh2021)

Configuration to help Global Biotic Interactions (GloBI, https://globalbioticinteractions.org) index: 

Wardeh, M., Baylis, M. & Blagrove, M.S.C. Predicting mammalian hosts in which novel coronaviruses can be generated. Nat Commun 12, 780 (2021). https://doi.org/10.1038/s41467-021-21034-5

Included mammals_viruses.tsv derived from:

```
$ curl "https://ndownloader.figshare.com/files/25984997" > wardeh.zip
$ unzip -p wardeh.zip covs-recombination-hosts/data/networks/mammals_viruses.txt > mammals_viruses.tsv
```
