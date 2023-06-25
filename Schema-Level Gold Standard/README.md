# T2D Schema-Level Gold Standard

This directory contains the (Web Data Commons) [T2D Schema-Level-Gold Standard]((http://webdatacommons.org/webtables/goldstandard.html)) (also published as 'Complete gold standard') in the format used by [T2K Match](https://github.com/olehmberg/T2KMatch).

### Overview
- 1478 web tables
- 763 class mappings *
- 2148 attribute to property mappings *

### Deviation *
The schema level gold standard contains 1688 class matchings instead of 762 as described on the website. It is mentiod that only for content tables a mapping to DBpedia is usefull. A so called content table contains relational data and has at least one column that is mappable. I removed all tables from the class mapping, which have no attribute to property mapping. This results to 763 class mappings which still differs from the announced 762 mappings.  
I also found 2148 attribute to property mapping instead of the announced 2048 on the webseite. [1, 2]

#### Download DBPedia subset
https://data.dws.informatik.uni-mannheim.de/webtables/dbpedia_subset.tar.gz  
#### Download Web Tables data
http://webdatacommons.org/webtables/tables_complete.tar.gz

## Source
Gold standard is provided and published through the [Web Data Commons Project](http://webdatacommons.org/webtables/goldstandard.html).

## License
The T2D Gold standard is provided by the [Web Data Commons Project](http://webdatacommons.org/webtables/goldstandard.html) and published under the terms of [Apache license](https://www.apache.org/licenses/LICENSE-2.0). The Web tables are provided according the same terms of use, disclaimer of warranties and limitation of liabilities that apply to the Common Crawl corpus.
 The DBpedia subset is provided under the terms of the [Creative Commons Attribution-ShareAlike License](http://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License) and the [GNU Free Documentation License](http://en.wikipedia.org/wiki/Wikipedia:Text_of_the_GNU_Free_Documentation_License) that applies to DBpedia.

 ## References
 [1] Ritze, D., Lehmberg, O., & Bizer, C. (2015, July). Matching html tables to dbpedia. In Proceedings of the 5th International Conference on Web Intelligence, Mining and Semantics (p. 10). ACM.

 [2] Ritze, D., Lehmberg, O., & Bizer, C., T2D Gold Standard for Matching Web Tables to DBpedia, http://webdatacommons.org/webtables/goldstandard.html (Stand: 20.06.2023)