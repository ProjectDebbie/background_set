# Background set

The backgroud set is a list of PMIDs representing non-biomaterials abstracts for the purpose of relevance classification. 

## Description 

This randomly sampled set was created to enable classification and comparative analysis of the biomaterials literature against the general literature. To ensure maximal random distribution of the abstracts from the PubMed database, PMIDs were generated as pseudo-random numbers (within the range of PMIDs in the years 1999-2018), using python’s random package (Python Software Foundation, version 3.6, Available at http://www.python.org). These PMIDs were used to retrieve full citations via the PubMed eBot tool, which is one of the educational resources offered by the National Center for Biotechnology Information (NCBI). To ensure the random set does not contain any biomaterials articles, it was also ranked in the MedlineRanker, and the top 200 ranked records were manually scanned, of which 7 records were deemed relevant to the biomaterials set and were therefore removed. Reviews, records with no abstracts, non-english records and records published earlier than 2004 were also excluded.


## Created With

* [PubMed Ebot](https://www.ncbi.nlm.nih.gov/Class/PowerTools/eutils/ebot/ebot.cgi) 
* [Python](http://www.python.org)
* [MedlineRanker](http://cbdm-01.zdv.uni-mainz.de/~jfontain/cms/?page_id=4)

## Versioning

Versions of the background set are labeled with the number of PMIDs they contain. 

## Authors

**Osnat Hakimi**

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE Version 3 - see the [LICENSE](LICENSE) file for details

## Citation

@article{doi:10.1002/adfm.201909910,
	author = {Hakimi, Osnat and Gelpi, Josep Luis and Krallinger, Martin and Curi, Fabio and Repchevsky, Dmitry and 	Ginebra, Maria-Pau},
	title = {The Devices, Experimental Scaffolds, and Biomaterials Ontology (DEB): A Tool for Mapping, Annotation, and 	   Analysis of Biomaterials Data},
	journal = {Advanced Functional Materials},
	volume = {30},
	number = {16},
	pages = {1909910},
	keywords = {biomaterials, databases, ontology},
	doi = {10.1002/adfm.201909910},
	url = {https://onlinelibrary.wiley.com/doi/abs/10.1002/adfm.201909910},
	eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1002/adfm.201909910},
	year = {2020}
}

	
		
